# Brief: weryfikacja źródeł (Faza A audytu naukowego Mythlift)

Kontekst: prowadzimy rygorystyczny audyt naukowy bazy quizowej Mythlift (trening siłowy/hipertrofia/żywienie/ból).
Pełne zasady audytu: /home/user/mythlift/prompt (PRZECZYTAJ sekcje "WERYFIKACJA ŹRÓDEŁ", "WERYFIKACJA CYTOWAŃ",
"AKTUALNOŚĆ WIEDZY", "ZAKAZ DOMYŚLANIA SIĘ").

Rozpakowane pliki YAML eksportu:
  SRC=/tmp/claude-0/-home-user-mythlift/2759af1c-d785-517d-b474-c89fd3bd6867/scratchpad/yaml
  $SRC/sources/SRC-xxxx.yaml  – opis źródła w Mythlift (citation, doi, pmid, type, population, summary, limitations)
  $SRC/claims/CL-*.yaml       – twierdzenia; pole sources: wskazuje source_id i rolę (supports/contradicts/context)
Aby znaleźć twierdzenia używające źródła: grep -l "SRC-xxxx" $SRC/claims/*.yaml

OGRANICZENIE SIECI (ważne, bądź uczciwy): WebFetch jest zablokowany dla WSZYSTKICH domen (PubMed, doi.org, PMC,
EuropePMC, wydawcy). Działa tylko WebSearch (wyniki + streszczenia). Nie masz więc dostępu do pełnych tekstów.
Konsekwencje:
- Nigdy nie oznaczaj źródła jako "zweryfikowane z pełnego tekstu".
- Każdą informację o badaniu oznacz poziomem pewności:
  [SEARCH] – potwierdzone w wynikach WebSearch w tej sesji (podaj URL wyniku),
  [WIEDZA] – z Twojej wiedzy o publikacji, NIE potwierdzone w tej sesji (podawaj tylko, jeśli jesteś naprawdę pewien;
             nie zmyślaj liczb – jeśli nie pamiętasz dokładnie, napisz to),
  [NIEZWERYFIKOWANE] – nie udało się ustalić.
- Nie twórz fikcyjnych cytatów. Nie używaj cudzysłowu dla tekstu, którego dosłownie nie widziałeś w wyniku wyszukiwania.
- Nie wymyślaj DOI/PMID/liczb.

Dla KAŻDEJ publikacji z Twojej listy (uwaga: kilka rekordów SRC może wskazywać tę samą publikację – oceń je razem,
ale sprawdź różnice między rekordami, np. różny "type", różne listy autorów, różne summary):

1. Weryfikacja bibliograficzna: autorzy, tytuł, czasopismo, rok, tom(zeszyt):strony, DOI, PMID – każde pole:
   POTWIERDZONE [SEARCH url] / ROZBIEŻNOŚĆ (co jest w źródle vs w Mythlift) / NIEZWERYFIKOWANE.
   Szukaj np. "<tytuł> <rok>", "<DOI>", "PMID <pmid>".
2. Status: retrakcja / korekta / erratum / expression of concern / istotna krytyka (komentarze, letters) – szukaj
   "<tytuł> retraction", "<tytuł> correction erratum". Wynik: BRAK ZNALEZIONYCH / ZNALEZIONO (opis) / NIEZWERYFIKOWANE.
3. Rzeczywisty projekt i wyniki: typ badania, populacja, n, status treningowy, płeć, wiek, interwencja, porównanie,
   czas trwania, outcome i metoda pomiaru (np. DXA-FFM/LBM vs USG grubość mięśnia vs MRI/CSA vs biopsja CSA włókien),
   wielkość efektu z CI/CrI, heterogeniczność, primary/secondary outcome, istotność, ograniczenia, wnioski autorów
   (w tym czy autorzy formułują wniosek ostrożniej niż Mythlift). Każdy element z tagiem pewności.
4. Zgodność opisu w Mythlift (population, summary PL/EN, limitations, type) z rzeczywistym źródłem – wypisz
   KAŻDĄ rozbieżność lub nadinterpretację (np. FFM nazwane mięśniami, ostre MPS jako hipertrofia, n, liczba badań).
5. Liczby używane w twierdzeniach opierających się na tym źródle (przeczytaj te claims: statement + evidence_summary +
   applicability): dla każdej liczby/zakresu/progu → ZGODNE / NIEZGODNE / NIEZWERYFIKOWANE, z uzasadnieniem.
   Oceń też wstępnie, czy źródło wspiera dokładnie to, do czego jest użyte (supports/contradicts/context) –
   DIRECT / PARTIAL / INDIRECT / NONE.
6. Aktualność: czy są nowsze metaanalizy/position stands/duże RCT (do 09.2026), które zmieniają lub doprecyzowują
   wniosek? Szukaj aktywnie także dowodów przeciwnych (adversarial). Podaj konkretne publikacje (z [SEARCH] lub [WIEDZA]).
7. Poprawność pola "type" (np. rct / meta_analysis / observational / mechanistic / narrative_review).

FORMAT WYJŚCIA: zapisz plik markdown (ścieżka podana w zadaniu) z sekcją na każdą publikację:

### <Pierwszy autor Rok – krótki tytuł> (SRC-..., SRC-...)
- **Bibliografia:** ...
- **Status (retrakcja/korekta):** ...
- **Dostęp do pełnego tekstu:** brak (WebFetch zablokowany); poziom weryfikacji: CZĘŚCIOWA / TYLKO BIBLIOGRAFIA / NIEZWERYFIKOWANE
- **Rzeczywisty projekt i wyniki:** (lista z tagami)
- **Rozbieżności z opisem Mythlift:** (lista z severity sugerowaną: CRITICAL/HIGH/MEDIUM/LOW, lub "brak istotnych")
- **Liczby w twierdzeniach:** (CL-ID: liczba → werdykt)
- **Wstępna ocena wsparcia dla twierdzeń:** (CL-ID rola → DIRECT/PARTIAL/INDIRECT/NONE + 1-2 zdania)
- **Aktualność / nowsze dowody:** ...
- **Pole type:** poprawne / błędne (dlaczego)
- **Odnośniki użyte:** lista URL z WebSearch

Pisz po polsku, konkretnie. Priorytet: poprawność > długość. Po zapisaniu pliku zwróć krótkie podsumowanie
(max 15 linii) najważniejszych rozbieżności.
