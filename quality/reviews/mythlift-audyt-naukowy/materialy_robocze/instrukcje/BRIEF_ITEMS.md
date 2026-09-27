# Brief: audyt pytań jednej karty pojęć (Faza C audytu naukowego Mythlift)

Jesteś niezależnym, bardzo rygorystycznym recenzentem naukowym. Pełne zasady audytu są w pliku
/home/user/mythlift/prompt — PRZECZYTAJ GO W CAŁOŚCI przed rozpoczęciem (szczególnie: WERYFIKACJA PYTAŃ,
NADMIERNA PEWNOŚĆ, EKSTRAPOLACJE, BEZPIECZEŃSTWO, WERSJE PL I EN, ZAKAZ DOMYŚLANIA SIĘ, KLASYFIKACJA, STATUS).

## Materiały (tylko do odczytu)
Y=/tmp/claude-0/-home-user-mythlift/2759af1c-d785-517d-b474-c89fd3bd6867/scratchpad/yaml
A=/tmp/claude-0/-home-user-mythlift/2759af1c-d785-517d-b474-c89fd3bd6867/scratchpad/audit
- Karta pojęcia: $Y/kcs/<KC>.yaml
- Pytania: $Y/items/<KC>/*.yaml  (przeczytaj KAŻDE w całości: stem, context jeśli jest, opcje + score, feedback każdej
  opcji / numeric_feedback i przedziały full/partial/input_range, w0, w1.simple, w1.expert, w1.apply, w2 — PL i EN)
- Błędne przekonania powiązane z opcjami: $Y/misconceptions/MC-*.yaml (pola why_popular / refutation)
- Twierdzenia: $Y/claims/CL-*.yaml
- AUDYT TWIERDZEŃ (fundament — korzystaj z niego, nie powtarzaj go): $A/claims/CLAIMS_AUDIT.md
- Dossier źródeł (weryfikacja bibliografii i rzeczywistych wyników): $A/sources/*.md

## Ograniczenia sieci
WebFetch jest zablokowany dla wszystkich domen. Wspólny limit WebSearch dla agentów pomocniczych jest najpewniej
wyczerpany (spróbuj najwyżej 1-2 razy; jeśli narzędzie odmówi, nie ponawiaj). Weryfikacja źródeł została już wykonana:
korzystaj z $A/claims/CLAIMS_AUDIT.md (audyt 68 twierdzeń + tabela 48 publikacji) oraz dossier $A/sources/*.md
(G1, G2, G3a, G3b, G4a, G4b_sleep, G4b_pain, EXTRA.md – EXTRA zawiera późniejsze potwierdzenia recenzenta głównego,
które mają pierwszeństwo przed oznaczeniami NIEZWERYFIKOWANE w G1/G2/G4a). Jeżeli pytanie zawiera fakt/liczbę,
której nie ma w twierdzeniach, audycie ani dossier, oceń ją na podstawie swojej wiedzy z wyraźnym oznaczeniem
[WIEDZA] albo oznacz jako NIEZWERYFIKOWANE / nieudokumentowane (brak źródła w bazie) – samo nieudokumentowane
zdanie merytoryczne w W1/W2 to co najmniej LOW, a jeśli jest nieoczywiste lub mocne – MEDIUM.
Nie wymyślaj liczb, DOI ani cytatów.

## Co sprawdzić w KAŻDYM pytaniu (osobno PL i EN)
1. Klucz odpowiedzi (score) — czy odpowiedź oznaczona jako poprawna jest poprawna w świetle literatury.
2. Jednoznaczność (choice_single: tylko jedna najlepsza), choice_multi (wszystkie oznaczone poprawne, żadna nieoznaczona
   nie jest obronialna), myth_fact_depends (czy klucz mit/fakt/zależy jest obronialny), numeric (wartość docelowa,
   przedział full, partial, input_range — czy np. przedział full nie obejmuje wartości niepoprawnych albo nie pomija
   poprawnych; czy feedback below/above jest spójny z przedziałami).
3. Distraktory — czy są faktycznie niepoprawne, a nie „trochę mniej poprawne”.
4. Kontekst/stem — czy nie wprowadza dodatkowych założeń zmieniających odpowiedź.
5. Każde zdanie merytoryczne w feedbacku każdej opcji, w0, w1.simple, w1.expert, w1.apply, w2 — traktuj jak osobne
   twierdzenie. Sprawdź zgodność z claim i ze źródłem (liczby, zakresy, populacje, siła języka).
6. Czy pytanie dziedziczy problem z twierdzenia (patrz CLAIMS_AUDIT.md) — jeśli tak, oznacz to jawnie.
7. Nadinterpretacje: FFM/LBM nazwane mięśniami; MPS jako hipertrofia; ostre → długoterminowe; mechanizm → praktyka;
   początkujący → zaawansowani; jedna płeć → wszyscy; jedno ćwiczenie/mięsień → cały trening; korelacja → przyczyna;
   brak różnicy → równoważność; „nie wykazano” → „nie istnieje”; jedno małe badanie → ustalona wiedza; nadmierna precyzja;
   słowa „zawsze/nigdy/udowodniono/powoduje/najlepszy/optymalny/bezpieczny/taki sam/wystarczy/konieczny/musi”.
8. Ekstrapolacje: czy treść informuje o ograniczonej podstawie empirycznej, gdy rekomendacja nie była testowana.
9. PL vs EN: czy EN nie zmienia siły twierdzenia, zakresu, liczby, rekomendacji lub poprawnej odpowiedzi (nie rób
   korekty językowej).
10. Bezpieczeństwo (ból, urazy, żywienie, sensitivity): samodiagnoza, właściwa kwalifikacja sygnałów alarmowych,
    potencjalna szkoda — podnoś severity.

Oceń także kartę pojęcia (card PL/EN) i treści powiązanych błędnych przekonań (why_popular/refutation) — jako treści
zależne; problemy w nich zgłaszaj w osobnej podsekcji (nie nadają statusu pytaniom, chyba że pytanie powtarza błąd).

## Severity (stosuj konsekwentnie)
- CRITICAL: błędny klucz odpowiedzi; poważnie błędna teza; fałszywa interpretacja źródła; ryzyko szkody zdrowotnej.
- HIGH: źródło nie wspiera kluczowego twierdzenia; duży overclaim; istotna ekstrapolacja przedstawiona jako fakt;
  wniosek przestarzały wobec nowszych dowodów; konkretna liczba o masie beztłuszczowej podana wprost jako „mięśnie”
  i użyta jako kluczowa informacja pytania.
- MEDIUM: nieuwzględnione ograniczenie/niepewność; nadmierna precyzja; problem applicability; częściowo niepoprawny
  feedback lub wyjaśnienie; pojedyncze błędne/nieudokumentowane zdanie w W1/W2; FFM/LBM nazwane mięśniami na poziomie
  kierunku efektu; zmiana znaczenia w EN.
- LOW: drobna niedokładność merytoryczna bez wpływu na klucz i główny przekaz.
Stylistyki NIE zgłaszaj.

## Status pytania
- PASS: wszystkie istotne elementy sprawdzone, brak problemu wymagającego poprawki (dopuszczalne wyłącznie uwagi
  informacyjne bez severity).
- PASS WITH NOTES: klucz i główny przekaz poprawne; wyłącznie problemy LOW.
- REVISION REQUIRED: co najmniej jeden problem MEDIUM lub HIGH, naprawialny bez zmiany celu pytania.
- FAIL: błędny klucz, błędna główna teza albo niewystarczający fundament źródłowy głównej tezy (zwykle CRITICAL lub HIGH
  dotyczący klucza/głównej tezy).
- UNVERIFIED: nie da się rzetelnie sprawdzić podstawowych dowodów dla klucza.
Uwaga: jedno błędne lub nieudokumentowane zdanie w W2 wyklucza PASS.

## FORMAT WYJŚCIA (markdown, po polsku) — zapisz do pliku podanego w zadaniu
```
## Partia <n>: <KC-ID> — <nazwa>

**Zakres partii:** pytania <pierwsze ID> … <ostatnie ID> (<liczba>), twierdzenia: <lista>, źródła: <lista>.

### Tabela statusów
| ID | STATUS | SEVERITY | CLAIMS | SOURCES | KRÓTKIE UZASADNIENIE |
|---|---|---|---|---|---|
| IT-... | PASS WITH NOTES | LOW | CL-... | SRC-... | ... |
(SEVERITY = najwyższa severity problemów pytania albo „—”; SOURCES = źródła przypisane do claims pytania)

### Szczegóły problemów
Dla KAŻDEGO pytania ze statusem REVISION REQUIRED, FAIL lub UNVERIFIED (a także dla problemów LOW w PASS WITH NOTES
w skróconej formie) podaj każdy problem jako:

#### <ID-problemu: <prefiks partii>-Pnn, np. M1-01-P01> · <SEVERITY> · <ID pytania> · pole `<ścieżka pola, np. localizations.pl.w2>`
- **Claim / source:** CL-..., SRC-...
- **OBECNIE:** (dosłowny fragment obecnej treści — kopiuj z YAML, możesz cytować, bo to treść Mythlift)
- **PROBLEM:** (werdykt + uzasadnienie: co pokazuje źródło, dlaczego obecne sformułowanie jest/nie jest uzasadnione;
  czy dziedziczone z twierdzenia)
- **PROPONOWANA KOREKTA:** (konkretny nowy tekst PL; jeśli dotyczy też EN — wskaż, że analogicznie w EN)
- **Pewność oceny:** wysoka / umiarkowana / niska
- **Weryfikacja:** na czym opierasz ocenę (dossier źródła / audyt twierdzenia / WebSearch URL / wiedza — z zaznaczeniem)

### Karta pojęcia i błędne przekonania
(problemy w card PL/EN i w MC-* why_popular/refutation, w tym samym formacie problemu; albo „brak istotnych problemów”)

### Podsumowanie partii
- Pytania: PASS a, PASS WITH NOTES b, REVISION REQUIRED c, FAIL d, UNVERIFIED e (razem N)
- Problemy (tylko w pytaniach): CRITICAL w, HIGH x, MEDIUM y, LOW z
- Problemy w karcie/MC (osobno): CRITICAL …, HIGH …, MEDIUM …, LOW …
- Ostatnie ID w partii: IT-...
```
Liczniki problemów: licz każdy problem osobno (ten sam problem powtórzony w kilku polach jednego pytania = 1 problem
z listą pól; ten sam problem w różnych pytaniach = osobne problemy w każdym pytaniu).

Nie pomijaj żadnego pytania. Nie oceniaj wyrywkowo. Nie poprawiaj plików YAML. Nie wykonuj git commit.
Po zapisaniu pliku zwróć krótkie podsumowanie (liczniki + 3-5 najpoważniejszych problemów, max 15 linii).
