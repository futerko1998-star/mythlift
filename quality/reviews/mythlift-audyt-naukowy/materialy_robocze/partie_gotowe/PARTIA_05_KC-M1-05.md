## Partia 5: KC-M1-05 — RIR: definicja i szacowanie

**Zakres partii:** pytania IT-M1-05-01 … IT-M1-05-71 (13: 01-10, 51, 61, 71), twierdzenia: CL-RIR-001, CL-RIR-002, CL-RIR-003, CL-EFF-003, źródła: SRC-0107 (Zourdos 2016), SRC-0106 (Halperin 2022), SRC-0105 (Robinson 2024), SRC-0104 (Refalo 2023), SRC-0100 (ACSM 2026). Treści zależne: karta KC-M1-05, MC-107, MC-640, MC-641, MC-642, MC-643, MC-644 oraz MC przypięte do opcji z innych kart: MC-105, MC-106 (KC-M1-04), MC-302 (KC-M3-02).

**Podstawa weryfikacji:** CLAIMS_AUDIT.md (CL-RIR-001 PARTIAL/DIRECT, B; CL-RIR-002 DIRECT, B→B/C, C-29; CL-RIR-003 INDIRECT, D; CL-EFF-003 DIRECT), dossier G1 i EXTRA (Halperin 2022, Zourdos 2016 – bibliografia i wyniki na poziomie abstraktu potwierdzone). W tej partii wykonano 2 wyszukiwania WebSearch (Halperin 2022). Z wyników (streszczenia wyszukiwarki, nie pełny tekst) wynika:
- błąd trafności bliżej upadku był „nieznacznie” mniejszy, β = −0,025 (95% CI −0,05 do 0,0014), więc przedział obejmuje 0;
- numer serii wpływał „trywialnie”: β = −0,07 powtórzenia na serię (95% CI −0,14 do −0,005);
- główny model: zaniżenie o 0,95 powtórzenia (95% CI 0,17-1,73), 262 efekty w 12 klastrach, duża niejednorodność;
- według źródeł wtórnych staż treningowy nie wpływał na trafność, a trafność była lepsza w seriach ≤12 powtórzeń.

[SEARCH https://pubmed.ncbi.nlm.nih.gov/34542869/ ; https://link.springer.com/article/10.1007/s40279-021-01559-x ; https://cris.tau.ac.il/en/publications/accuracy-in-predicting-repetitions-to-task-failure-in-resistance-/ ; wtórne: https://www.strongerbyscience.com/reps-in-reserve/ ; https://efsupit.ro/images/stories/november2025/Art%20262.pdf ; https://www.researchgate.net/figure/Meta-analytic-scatter-plot-of-training-history-and-prediction-accuracy_fig4_354704966].

Skutek: zastrzeżenie C-29 (późniejsze serie, staż) jest w dużej mierze wyjaśnione. Efekt późniejszych serii potwierdzono jako trywialny. Brak wpływu stażu potwierdzono na poziomie źródeł wtórnych. Dlatego nie oznaczam go jako problemu dziedziczonego w pytaniach. Wyjątek to miejsca, gdzie treść wzmacnia te efekty ponad dane.

### Tabela statusów
| ID | STATUS | SEVERITY | CLAIMS | SOURCES | KRÓTKIE UZASADNIENIE |
|---|---|---|---|---|---|
| IT-M1-05-01 | PASS | — | CL-RIR-001 | SRC-0107, SRC-0106, SRC-0105 | Definicja RIR i mapowanie RPE↔RIR (w tym RPE 8,5 = 1-2 RIR) zgodne ze skalą Zourdos 2016. Dystraktory jednoznacznie błędne. PL = EN. |
| IT-M1-05-02 | PASS WITH NOTES | LOW | CL-RIR-001 | SRC-0107, SRC-0106, SRC-0105 | Klucz RIR 2 poprawny. Przedziały full/partial i feedback below/above spójne. W1.expert/apply podają regułę „10 − RPE” bez ograniczenia zakresu (W2 ogranicza poprawnie). |
| IT-M1-05-03 | PASS | — | CL-RIR-001 | SRC-0107, SRC-0106, SRC-0105 | A i B poprawne, C i D błędne w przyjętej definicji (upadek w akceptowalnej technice). Uwaga informacyjna o RPE 9,5. |
| IT-M1-05-04 | PASS WITH NOTES | LOW | CL-RIR-002 | SRC-0106, SRC-0107 | Klucz (6-8 powt. blisko upadku) zgodny z Halperin 2022 (≤12 powt.; blisko upadku nieco trafniej). Feedback C dopowiada niezbadaną interakcję staż × rodzaj serii. |
| IT-M1-05-05 | REVISION REQUIRED | MEDIUM | CL-RIR-002 | SRC-0106, SRC-0107 | Klucz jest najlepszy spośród opcji, ale hipotetyczny mechanizm (mniej do przewidzenia, sygnał spowolnienia, pieczenie „właśnie dlatego”) podano jako fakt w feedbacku, W0, W1.simple i apply. Tylko W1.expert i W2 zastrzegają brak badań. |
| IT-M1-05-06 | PASS WITH NOTES | LOW | CL-RIR-002 | SRC-0106, SRC-0107 | Klucz „mit” obronialny dla reguły uniwersalnej („najwyżej”), a „zależy” ma częściowe punkty (0,5). Follow-up A twierdzi bez podstaw, że w seriach ≤12 powt. ludzie „zwykle zaniżają”. |
| IT-M1-05-07 | REVISION REQUIRED | MEDIUM | CL-RIR-002, CL-RIR-001 | SRC-0106, SRC-0107, SRC-0105 | Klucz poprawny. Treść zawyża jednak precyzję: nazywa błąd „przewidywalnym” i zaleca margines ok. 1 powt. dla każdej serii. Tymczasem I² = 97,9%, CI 0,17-1,73, a w długich seriach błędy są większe. EN „only”. |
| IT-M1-05-08 | PASS | — | CL-RIR-001 | SRC-0107, SRC-0106, SRC-0105 | Arytmetyka poprawna (10+5 = 15; 15−2 = 13). Klucz zgodny z logiką planu (zakres powtórzeń + RIR). Zastrzeżenie o przybliżonym charakterze RIR obecne. |
| IT-M1-05-09 | PASS WITH NOTES | LOW | CL-RIR-001 | SRC-0107, SRC-0106, SRC-0105 | Klucz RIR 0 poprawny w definicji z akceptowalną techniką. Zalecenie „skończ ok. 2 powt. wcześniej, czyli po ok. 6” pomija zmęczenie narastające między seriami. |
| IT-M1-05-10 | PASS WITH NOTES | LOW | CL-RIR-002, CL-RIR-003 | SRC-0106, SRC-0107, SRC-0105 | Klucz poprawny. Kalibracja jest jawnie oznaczona jako niebadana, a bezpieczeństwo (przysiad bez asekuracji) właściwie zakwalifikowane. „Trafność zależy od ćwiczenia” – brak źródła w bazie. |
| IT-M1-05-51 | PASS WITH NOTES | LOW | CL-RIR-002, CL-RIR-003, CL-RIR-001 | SRC-0106, SRC-0107, SRC-0105 | Klucz B zgodny (brak wyraźnego wpływu stażu – potwierdzone wtórnie). Feedback B zamienia brak efektu na „podobnie”. W2 wzmacnia trywialny efekt pierwszej serii. Feedback D korzysta z nieprzypisanego CL-EFF-002. |
| IT-M1-05-61 | PASS | — | CL-RIR-001 | SRC-0107, SRC-0106, SRC-0105 | 11 − 8 = 3, full [3,3], feedback below/above spójny. RIR 3 = RPE 7 poprawnie. Wzmianka o zaniżaniu ok. 1 powt. zgodna ze źródłem. |
| IT-M1-05-71 | REVISION REQUIRED | MEDIUM | CL-RIR-001, CL-EFF-003 | SRC-0107, SRC-0106, SRC-0105, SRC-0104, SRC-0100 | Klucz poprawny (≥7 RIR, cel 1-3). W2 przedstawia jednak trafność RIR jako umiejętność „do wyćwiczenia” i zawęża lukę dowodową do „jak często”, sprzecznie z CL-RIR-002/003. Dziedziczy C-27 i C-05. Uzasadnienie klucza opiera się na nieprzypisanych twierdzeniach. |

### Szczegóły problemów

#### M1-05-P01 · LOW · IT-M1-05-02 · pole `localizations.pl.w1.expert`, `localizations.pl.w1.apply` (analogicznie EN)
- **Claim / source:** CL-RIR-001, SRC-0107
- **OBECNIE:** „Na skali RPE opartej na RIR każdy punkt poniżej 10 odpowiada jednemu powtórzeniu w zapasie” oraz „Gdy plan podaje RPE, odejmij tę liczbę od 10, a wynik to docelowy zapas powtórzeń.”
- **PROBLEM:** W skali Zourdos 2016 relacja 1:1 obowiązuje w zakresie RPE 7-10 (z połówkami). Przy RPE 5-6 zapas to 4-6 powtórzeń, a RPE 1-4 nie ma odpowiednika w RIR. W2 tego samego pytania poprawnie ogranicza regułę do RPE 7-10, a W1.expert/apply formułują ją bez zastrzeżeń. Nie wpływa to na klucz.
- **PROPONOWANA KOREKTA:** W1.expert: „…w zakresie od RPE 7 do 10 każdy punkt poniżej 10 odpowiada jednemu powtórzeniu w zapasie…”. Apply: „Gdy plan podaje RPE od 7 do 10, odejmij tę liczbę od 10…”. Analogicznie w EN.
- **Pewność oceny:** wysoka
- **Weryfikacja:** dossier G1/EXTRA (Zourdos 2016); opis skali [WIEDZA]; W2 tego pytania.

#### M1-05-P02 · LOW · IT-M1-05-04 · pole `localizations.pl.option_texts.C.feedback` (analogicznie EN)
- **Claim / source:** CL-RIR-002, SRC-0106
- **OBECNIE:** „W zebranych badaniach staż treningowy nie poprawiał jednak wyraźnie trafności, a różnice między rodzajami serii pozostawały.” / EN „…and the differences between types of sets remained.”
- **PROBLEM:** Halperin 2022 raportuje moderatory w osobnych metaregresjach (bliskość upadku, liczba powtórzeń, numer serii, staż). Interakcji staż × rodzaj serii nie raportuje ani abstrakt, ani streszczenia wtórne. Druga część zdania to nieudokumentowane dopowiedzenie.
- **PROPONOWANA KOREKTA:** „…W zebranych badaniach staż treningowy nie poprawiał jednak wyraźnie trafności.” Usunąć drugą część. Analogicznie w EN.
- **Pewność oceny:** umiarkowana (brak pełnego tekstu)
- **Weryfikacja:** EXTRA (Halperin); WebSearch (streszczenia, linki wyżej).

#### M1-05-P03 · MEDIUM · IT-M1-05-05 · pola `localizations.pl.option_texts.A.feedback`, `…B.feedback`, `localizations.pl.w0`, `localizations.pl.w1.simple`, `localizations.pl.w1.expert`, `localizations.pl.w1.apply` (analogicznie EN)
- **Claim / source:** CL-RIR-002, SRC-0106; SRC-0107 (użyte w argumencie o prędkości)
- **OBECNIE:**
  - A.feedback: „Tak. Im bliżej upadku, tym krótszy odcinek serii trzeba przewidzieć, a zwalniający ruch jest czytelną wskazówką.”
  - B.feedback: „…W długich seriach pojawia się jednak wcześnie, na długo przed upadkiem, i właśnie dlatego zapas bywa wtedy zaniżany.”
  - w0: „Blisko upadku jest mniej do przewidzenia, a spowolnienie ruchu zapowiada koniec serii.”
  - w1.expert: „…spadek prędkości ruchu jest wyraźnym sygnałem, bo oceny na skali RIR wiążą się z prędkością sztangi.”
  - apply: „W długich seriach nie traktuj pieczenia jako znaku upadku; lepszą wskazówką jest wyraźne zwolnienie ruchu.”
- **PROBLEM:**
  - Halperin 2022 opisuje, kiedy szacunki są trafniejsze, ale nie bada, dlaczego. Samo W2 tego pytania to przyznaje („prawdopodobne, ale nie zostało wprost sprawdzone”), podobnie W1.expert („Prawdopodobne wyjaśnienie”).
  - Mimo to feedback klucza, W0, W1.simple i apply podają mechanizm jako fakt, a feedback B zawiera twierdzenie przyczynowe („właśnie dlatego”) o roli pieczenia w zaniżaniu zapasu. To hipoteza mechanistyczna przedstawiona jako wynik.
  - Argument z prędkością to ekstrapolacja. Zourdos 2016 wykazał korelację ocen RPE ze średnią prędkością przy różnych ciężarach (pojedyncze powtórzenia 60/75/90% 1RM i 1RM; r = −0,88 u doświadczonych i −0,77 u początkujących). Badanie nie pokazuje, że ćwiczący posługują się odczuciem spowolnienia jako wskazówką ani że poprawia ono szacunek w długich seriach.
  - Zalecenie w apply (spowolnienie jako lepsza wskazówka niż pieczenie) nie było testowane.
  - Klucz pozostaje najlepszą odpowiedzią, bo dystraktory są jednoznacznie błędne („dokładnie”, „całkiem usuwa”, „tylko przypadek”). Dlatego status to REVISION REQUIRED, a nie FAIL.
  - Uwaga: część efektu „bliżej upadku = trafniej” wynika z mniejszego możliwego zakresu błędu (C-42). Opcja A („mniej do przewidzenia”) ten element oddaje poprawnie.
- **PROPONOWANA KOREKTA:**
  - A.feedback: „Tak, to najbardziej prawdopodobne wyjaśnienie spośród podanych: im bliżej upadku, tym krótszy odcinek serii trzeba przewidzieć (więc i możliwy błąd jest mniejszy), a zwalniający ruch może być czytelną wskazówką. Mechanizmu nie sprawdzono jednak wprost.”
  - B.feedback: „…W długich seriach pojawia się jednak wcześnie, na długo przed upadkiem, co prawdopodobnie sprzyja zaniżaniu zapasu (to hipoteza, a nie wynik badań).”
  - w0: „Prawdopodobnie: blisko upadku jest mniej do przewidzenia, a ruch wyraźnie zwalnia.”
  - w1.simple: dodać „To prawdopodobne wyjaśnienie, nie wynik badań.”
  - w1.expert: „…spadek prędkości może być wyraźnym sygnałem (oceny na skali RIR korelują z prędkością sztangi, choć nie badano, czy ćwiczący z tego sygnału korzystają).”
  - apply: „W długich seriach nie traktuj samego pieczenia jako znaku upadku. Zwolnienie ruchu może być dodatkową wskazówką, ale najpewniej sprawdzisz się okazjonalną serią do upadku w bezpiecznym ćwiczeniu.”
  - Analogicznie w EN.
- **Pewność oceny:** wysoka (co do braku bezpośrednich badań mechanizmu), umiarkowana (co do dokładnego protokołu Zourdos – brak pełnego tekstu)
- **Weryfikacja:** EXTRA (Zourdos 2016: protokół i korelacje [SEARCH]); CLAIMS_AUDIT C-42; W2 samego pytania; WebSearch (Halperin – moderatory, brak analizy mechanizmów w abstrakcie).

#### M1-05-P04 · LOW · IT-M1-05-05 · pole `localizations.pl.option_texts.D.feedback` (analogicznie EN)
- **Claim / source:** CL-RIR-002, SRC-0106
- **OBECNIE:** „Mimo to kierunek się powtarza: blisko upadku i w krótszych seriach szacunki są trafniejsze.” / EN „Still, the direction repeats…”
- **PROBLEM:** „Kierunek się powtarza” sugeruje spójność między badaniami, której metaanaliza nie wykazała. W metaregresji efekt bliskości upadku był „nieznaczny”, a 95% CI obejmował 0 (β = −0,025; −0,05 do 0,0014), przy I² = 97,9%. Lepiej udokumentowany jest efekt liczby powtórzeń (≤12). Dystraktor D pozostaje błędny, bo neguje zależność od liczby powtórzeń.
- **PROPONOWANA KOREKTA:** „Mimo to w zestawieniu badań szacunki były trafniejsze w seriach do ok. 12 powtórzeń i nieco trafniejsze bliżej upadku.” Analogicznie w EN.
- **Pewność oceny:** umiarkowana (liczby ze streszczenia wyszukiwarki)
- **Weryfikacja:** WebSearch – streszczenie abstraktu Halperin 2022 (PubMed 34542869, Springer).

#### M1-05-P05 · LOW · IT-M1-05-06 · pole `localizations.pl.followup_texts.A.feedback` (analogicznie EN)
- **Claim / source:** CL-RIR-002, SRC-0106
- **OBECNIE:** „To realna zależność: w seriach do 12 powtórzeń ocena jest trafniejsza. Nawet w nich ludzie zwykle zaniżają zapas, więc samo zdanie to raczej mit.”
- **PROBLEM:** W seriach ≤12 powtórzeń błąd był mały. Według EXTRA różnice nie były istotne, a według źródeł wtórnych trafność w tych seriach była dobra. Twierdzenie, że także tam ludzie „zwykle zaniżają zapas”, nie ma oparcia w dostępnych danych. Feedback „depends” formułuje to ostrożniej („bywa zaniżany”). Nie wpływa to na klucz „mit”, który opiera się na długich seriach.
- **PROPONOWANA KOREKTA:** „To realna zależność: w seriach do 12 powtórzeń ocena jest trafniejsza, więc tam zdanie bywa bliskie prawdy. Jako ogólna reguła to jednak raczej mit, bo w dłuższych seriach zapas jest zwykle wyraźnie zaniżany.” Analogicznie w EN.
- **Pewność oceny:** umiarkowana
- **Weryfikacja:** EXTRA (Halperin); WebSearch (źródła wtórne).

#### M1-05-P06 · MEDIUM · IT-M1-05-07 · pola `localizations.pl.w2`, `localizations.pl.w1.apply`, `localizations.pl.w0`, `localizations.en.option_texts.A.text`
- **Claim / source:** CL-RIR-002, CL-RIR-001, SRC-0106
- **OBECNIE:**
  - w2: „…To jednak błąd przewidywalny, który można uwzględnić.”
  - apply: „Zapisuj RIR przy każdej serii roboczej i traktuj go jako przybliżenie z marginesem około 1 powtórzenia.”
  - w0: „To przesada: RIR myli się średnio o około 1 powtórzenie, więc dobrze opisuje wysiłek.”
  - EN A: „Estimates are imperfect, but off by only about 1 rep on average”.
- **PROBLEM:**
  - Wartość 0,95 powtórzenia to zbiorcza, grupowa średnia różnica ze znakiem (zaniżenie), z szerokim przedziałem (95% CI 0,17-1,73) i skrajną niejednorodnością (I² = 97,9%). Nie opisuje typowego błędu pojedynczej oceny, bo przeszacowania i niedoszacowania się znoszą.
  - Kierunek (zaniżanie) jest względnie typowy, ale wielkość błędu zależy od osoby, liczby powtórzeń i odległości od upadku. Samo W2 przyznaje, że w długich seriach błąd jest większy. Scenariusze tej karty (IT-M1-05-10, IT-M1-05-71) pokazują błędy rzędu 4-6 powtórzeń.
  - Nazwanie błędu „przewidywalnym” i zalecenie jednolitego marginesu ok. 1 powtórzenia dla każdej serii roboczej to nadmierna precyzja, która pomija niepewność.
  - EN dodaje „only”, co wzmacnia przekaz względem PL.
  - Klucz A pozostaje najlepszą odpowiedzią.
- **PROPONOWANA KOREKTA:**
  - W2: „…To jednak błąd o dość typowym kierunku (zwykle zaniżanie zapasu), choć jego wielkość różni się między osobami i rodzajami serii, więc warto go od czasu do czasu sprawdzić.”
  - Apply: „Zapisuj RIR przy każdej serii roboczej. W krótkich seriach blisko upadku traktuj go jako przybliżenie z marginesem ok. 1 powtórzenia, w długich seriach z wyraźnie większym.”
  - W0: „To przesada: szacunek RIR jest nieidealny (średnio zaniżony o ok. 1 powtórzenie, z dużymi różnicami), ale wystarcza, by opisać, czy seria była blisko upadku.”
  - EN A: usunąć „only”.
  - Analogicznie w EN pozostałe pola.
- **Pewność oceny:** wysoka
- **Weryfikacja:** EXTRA (Halperin: 0,95; CI 0,17-1,73; I² = 97,9% [SEARCH]); WebSearch (262 efekty / 12 klastrów, „considerable heterogeneity”); SRC-0106.limitations („nie wiadomo, czy taki poziom błędu jest w praktyce akceptowalny”).

#### M1-05-P07 · LOW · IT-M1-05-09 · pola `localizations.pl.option_texts.A.feedback`, `localizations.pl.w1.simple`, `localizations.pl.w2` (analogicznie EN)
- **Claim / source:** CL-RIR-001 (zastosowanie praktyczne; brak źródła w bazie dla zmęczenia międzyseryjnego)
- **OBECNIE:** „Żeby trafić w plan, kolejną serię warto zakończyć około 2 powtórzenia wcześniej albo zmniejszyć ciężar.”; W2: „…zakończyć ją około 2 powtórzenia wcześniej, czyli po około 6…”
- **PROBLEM:** Po serii doprowadzonej do upadku technicznego i dalej (oszukane powtórzenie) liczba możliwych powtórzeń w kolejnej serii z tym samym ciężarem zwykle spada, zależnie od przerwy [WIEDZA]. Zakończenie po stałych „ok. 6” powtórzeniach może więc dać RIR 0-1, a nie 2. Zalecenie liczone od wyniku poprzedniej serii pomija zmęczenie narastające między seriami. Nie wpływa to na klucz (ocena bieżącej serii jako RIR 0).
- **PROPONOWANA KOREKTA:** „W kolejnej serii zakończ ją, gdy ocenisz, że zostały ok. 2 czyste powtórzenia. Przy tym samym ciężarze będzie to prawdopodobnie mniej niż 6 powtórzeń, bo zmęczenie z poprzedniej serii się kumuluje. Możesz też zmniejszyć ciężar.” Analogicznie w EN.
- **Pewność oceny:** umiarkowana
- **Weryfikacja:** [WIEDZA] (spadek liczby powtórzeń w kolejnych seriach przy stałym ciężarze, opisywany m.in. w badaniach nad przerwami między seriami); brak źródła w bazie.

#### M1-05-P08 · LOW · IT-M1-05-10 · pole `localizations.pl.option_texts.D.feedback` (analogicznie EN)
- **Claim / source:** CL-RIR-002, SRC-0106
- **OBECNIE:** „Sprawdzenie szacunku w innym ćwiczeniu to dobry odruch, bo trafność zależy od ćwiczenia.” / EN „…since accuracy varies between exercises.”
- **PROBLEM:** Ćwiczenie nie należy do moderatorów w CL-RIR-002. W dostępnych streszczeniach Halperin 2022 takiego wyniku nie ma. Zdanie o zależności od ćwiczenia pojawia się tylko w evidence_summary CL-RIR-001, bez źródła. Status: NIEZWERYFIKOWANE, sformułowane kategorycznie.
- **PROPONOWANA KOREKTA:** „…to dobry odruch, bo trafność może się różnić między ćwiczeniami.” Analogicznie w EN.
- **Pewność oceny:** umiarkowana
- **Weryfikacja:** CL-RIR-002, EXTRA, WebSearch (brak moderatora „ćwiczenie” w streszczeniach).

#### M1-05-P09 · LOW · IT-M1-05-51 · pole `localizations.pl.option_texts.B.feedback` (analogicznie EN)
- **Claim / source:** CL-RIR-002, SRC-0106
- **OBECNIE:** „Tak. W badaniach osoby początkujące i trenujące myliły się podobnie, średnio o ok. 1 powtórzenie, zwykle zaniżając zapas.” / EN „…beginners and trained lifters erred to a similar degree, by about 1 rep on average…”
- **PROBLEM:**
  - Brak wyraźnego wpływu stażu (metaregresja międzybadaniowa, I² ≈ 98%, potwierdzone w źródłach wtórnych) zamieniono na wykazane podobieństwo. To nadinterpretacja typu brak różnicy → równoważność.
  - Wartość ok. 1 powtórzenia to średnia dla całej puli, a nie osobno dla obu grup.
  - Pojedyncze badania sugerowały lepszą trafność doświadczonych w niektórych warunkach (np. Zourdos 2016 przy 1RM; przyznaje to MC-641.why_popular).
  - Klucz („nie poprawiał wyraźnie”) jest sformułowany poprawnie.
- **PROPONOWANA KOREKTA:** „Tak. W zestawieniu badań staż treningowy nie poprawiał wyraźnie trafności: także osoby trenujące zwykle zaniżały zapas. Dlatego warto czasem…” Analogicznie w EN.
- **Pewność oceny:** wysoka
- **Weryfikacja:** WebSearch (źródła wtórne o braku wpływu stażu); EXTRA (Zourdos 2016).

#### M1-05-P10 · LOW · IT-M1-05-51 · pole `localizations.pl.w2` (analogicznie EN)
- **Claim / source:** CL-RIR-002, SRC-0106
- **OBECNIE:** „Najtrudniej ocenić zapas w długich seriach, daleko od upadku i w pierwszej serii ćwiczenia. Pieczenie i dyskomfort narastają wtedy wcześniej niż prawdziwa niemoc mięśnia, więc łatwo przerwać serię z większym zapasem, niż się wydaje.”
- **PROBLEM:**
  - Efekt numeru serii był według autorów trywialny (β = −0,07 powtórzenia na serię). Stawianie pierwszej serii obok długich serii jako sytuacji „najtrudniejszej” wzmacnia go ponad dane.
  - Wyjaśnienie przez pieczenie to hipoteza podana jako fakt, a słowo „wtedy” obejmuje też pierwszą serię, dla której ten mechanizm nie ma uzasadnienia.
  - To nieudokumentowane zdanie w W2 (wyklucza PASS), ale nie zmienia głównego przekazu.
- **PROPONOWANA KOREKTA:** „Najtrudniej ocenić zapas w długich seriach i daleko od upadku (w pierwszej serii ćwiczenia trafność jest tylko nieznacznie gorsza). Prawdopodobnie przyczynia się do tego to, że w długich seriach pieczenie i dyskomfort narastają wcześniej niż prawdziwa niemoc mięśnia…” Analogicznie w EN.
- **Pewność oceny:** umiarkowana (liczby ze streszczenia wyszukiwarki)
- **Weryfikacja:** WebSearch – streszczenie abstraktu Halperin 2022.

#### M1-05-P11 · LOW · IT-M1-05-51 · pole `localizations.pl.option_texts.D.feedback` (analogicznie EN), pole `claims`
- **Claim / source:** brak przypisania. Treść pochodzi z CL-EFF-002 (SRC-0104, SRC-0100, SRC-0105).
- **OBECNIE:** „Serie kończone 1-3 powtórzenia przed upadkiem dają jednak podobny lub nieco mniejszy przyrost przy mniejszym zmęczeniu, a do tego potrzebna jest ocena zapasu.”
- **PROBLEM:** Treść jest merytorycznie zgodna z kartą KC-M1-04 i z korektą C-05 („1-3” zamiast „kilka”). CL-EFF-002 nie jest jednak przypisane do pytania, więc rewizja tego twierdzenia nie obejmie tego pytania. Część „przy mniejszym zmęczeniu” nie ma źródła w bazie. Jest prawdopodobna [WIEDZA], ale nieudokumentowana.
- **PROPONOWANA KOREKTA:** Dodać CL-EFF-002 do `claims`. W tekście: „…dają podobny lub nieco mniejszy przyrost mięśni i zwykle mniej męczą…” oraz dodać źródło dla zmęczenia albo usunąć tę część.
- **Pewność oceny:** wysoka (proces), umiarkowana (zmęczenie)
- **Weryfikacja:** CLAIMS_AUDIT (CL-EFF-002, C-05); karta KC-M1-04.

#### M1-05-P12 · MEDIUM · IT-M1-05-71 · pole `localizations.pl.w2` (analogicznie EN)
- **Claim / source:** CL-RIR-002, CL-RIR-003 (nieprzypisane do pytania), SRC-0106
- **OBECNIE:** „Szacowanie zapasu powtórzeń to umiejętność, którą trzeba ćwiczyć.” oraz „Nie ma bezpośrednich badań, jak często robić taki sprawdzian, ale to rozsądny sposób kalibracji.”
- **PROBLEM:**
  - Pierwsze zdanie zakłada, że trafność szacunku da się wytrenować. Tego nie wykazano: staż treningowy nie wpływał wyraźnie na trafność (CL-RIR-002; Halperin 2022 według źródeł wtórnych).
  - Drugie zdanie zawęża lukę dowodową do „jak często”, co sugeruje, że skuteczność sprawdzianów jest ustalona. Według CL-RIR-003 (pewność D) brak jakichkolwiek bezpośrednich badań nad tym, czy okresowe serie do upadku poprawiają trafność.
  - To ekstrapolacja przedstawiona jako fakt i niespójność z innymi pytaniami tej karty (IT-M1-05-10 i IT-M1-05-51 opisują lukę poprawnie).
  - Klucz pozostaje poprawny.
- **PROPONOWANA KOREKTA:** Zdanie 1: „Szacowanie zapasu powtórzeń jest nieidealne i nie wiadomo, czy da się je wyraźnie poprawić praktyką.” Zdanie 2: „Nie zbadano bezpośrednio, czy taki sprawdzian poprawia trafność szacunków ani jak często go robić. To jednak tania i rozsądna praktyka kalibracji.” Analogicznie w EN.
- **Pewność oceny:** wysoka
- **Weryfikacja:** CLAIMS_AUDIT (CL-RIR-003 INDIRECT, D); CL-RIR-002; WebSearch (źródła wtórne o stażu).

#### M1-05-P13 · LOW · IT-M1-05-71 · pole `localizations.pl.option_texts.D.feedback` (analogicznie EN)
- **Claim / source:** CL-EFF-001 (nieprzypisane), SRC-0105; dziedziczy C-27
- **OBECNIE:** „Seria buduje jednak mięśnie tym skuteczniej, im bliżej upadku się kończy.”
- **PROBLEM:** Zależność podano jako monotoniczną, co dziedziczy C-27: RCT u trenujących (0 vs 1-2 RIR) sugerują wypłaszczenie blisko upadku. Jest to wewnętrznie niespójne z feedbackiem C i W2 tego samego pytania („trening do upadku nie daje wyraźnej przewagi”, „1-3 wcześniej daje podobny efekt”). Klucz nie jest zagrożony.
- **PROPONOWANA KOREKTA:** „Seria buduje jednak mięśnie zwykle skuteczniej, gdy kończy się blisko upadku (ok. 0-3 w zapasie), niż gdy zostaje duży zapas…” Analogicznie w EN.
- **Pewność oceny:** umiarkowana
- **Weryfikacja:** CLAIMS_AUDIT C-27; dossier G1 (Refalo 2024 [WIEDZA]).

#### M1-05-P14 · LOW · IT-M1-05-71 · pole `localizations.pl.option_texts.C.feedback` (analogicznie EN)
- **Claim / source:** CL-EFF-003 / CL-EFF-002, SRC-0104, SRC-0105; dziedziczy C-05
- **OBECNIE:** „Badania porównujące trening do upadku z kończeniem serii kilka powtórzeń wcześniej zwykle nie pokazują wyraźnej różnicy w przyroście mięśni.”
- **PROBLEM:** „Kilka” jest szersze niż dane, co dziedziczy C-05: porównania dotyczą głównie ok. 0 vs 1-3 RIR. Przy lżejszych ciężarach bliskość upadku ma większe znaczenie (Lasevicius 2022). W scenariuszu Ola używa ciężaru ok. 22RM, czyli stosunkowo lekkiego. Problem łagodzi następne zdanie („zapas 1-3 powtórzeń się liczy”) i klucz (1-3), dlatego severity LOW.
- **PROPONOWANA KOREKTA:** „…z kończeniem serii ok. 1-3 powtórzenia wcześniej zwykle nie pokazują wyraźnej różnicy w przyroście mięśni. Przy lżejszych ciężarach i długich seriach warto jednak kończyć naprawdę blisko upadku.” Analogicznie w EN.
- **Pewność oceny:** wysoka
- **Weryfikacja:** CLAIMS_AUDIT C-05; EXTRA (Lasevicius 2022 [SEARCH]).

#### M1-05-P15 · LOW · IT-M1-05-71 · pole `claims` (oraz `option_texts.A.feedback`, `C.feedback`, `w1`, `w2`)
- **Claim / source:** przypisane CL-RIR-001, CL-EFF-003; faktycznie używane CL-EFF-001, CL-EFF-002, CL-RIR-002, CL-RIR-003
- **OBECNIE:** `claims: [CL-RIR-001, CL-EFF-003]`, a uzasadnienie klucza opiera się na innych twierdzeniach: „Takie serie prawdopodobnie dają słabszy bodziec. Zapas ok. 1-3 powtórzeń wzmacnia go…”, „W seriach powyżej 12 powtórzeń zapas bywa niedoszacowany częściej…”, „co jakiś czas warto sprawdzić swoje odczucia w bezpiecznym ćwiczeniu”, „a zwykle mniej męczy”.
- **PROBLEM:** Łańcuch twierdzenie → pytanie jest przerwany. Uzasadnienie klucza i W1/W2 korzysta z CL-EFF-001 (bliskość upadku a przyrost), CL-EFF-002 (1-3 RIR), CL-RIR-002 (zaniżanie, >12 powt.) i CL-RIR-003 (kalibracja), których nie przypisano. Rewizja tych twierdzeń (np. C-05, C-27) nie obejmie pytania. „Mniej męczy” nie ma źródła w bazie.
- **PROPONOWANA KOREKTA:** Rozszerzyć `claims` o CL-EFF-001, CL-EFF-002, CL-RIR-002, CL-RIR-003. Dla „mniej męczy” dodać źródło albo złagodzić do „prawdopodobnie mniej męczy”.
- **Pewność oceny:** wysoka
- **Weryfikacja:** porównanie treści pytania z twierdzeniami w bazie.

**Uwagi informacyjne (bez severity):**
- IT-M1-05-03: w oryginalnej skali Zourdos 2016 RIR 0 odpowiada też ocenie 9,5 („brak kolejnych powtórzeń, ale można by zwiększyć ciężar”). Uproszczenie „RIR 0 = RPE 10” jest standardowe i zgodne z CL-RIR-001, więc nie zmienia klucza.
- IT-M1-05-61: w W2 zdanie „Badania pokazują, że takie szacunki są przydatne” jest nieco mocniejsze niż źródło trafności. Autorzy Halperin 2022 zostawiają otwarte, czy poziom błędu jest akceptowalny. Zdanie mieści się jednak w CL-RIR-001 („praktyczny sposób planowania i zapisywania”). Można napisać „…są niedoskonałe, ale niosą użyteczną informację”.
- IT-M1-05-01: W2 nie wspomina, że korelacja ocen z prędkością była słabsza u początkujących (C-28), ale też nie twierdzi, że była jednakowa.
- IT-M1-05-06: semantyka `score_if_wrong_main: 0.5` jest zgodna z konwencją innych pytań. Odpowiedź „zależy” dostaje 0,5 niezależnie od follow-upu, co jest obronialne, bo zależność od liczby powtórzeń jest realna.

### Karta pojęcia i błędne przekonania

#### M1-05-P16 · MEDIUM · KC-M1-05 · pole `card.pl`, `card.en`
- **Claim / source:** CL-RIR-003 (pewność D), SRC-0106 (INDIRECT), SRC-0105 (INDIRECT)
- **OBECNIE:** „Od czasu do czasu sprawdź swoją ocenę, kończąc serię do upadku w bezpiecznym ćwiczeniu, np. na maszynie.”
- **PROBLEM:** Zalecenie kalibracji nie było testowane: CL-RIR-003 ma pewność D i opiera się na praktyce trenerskiej. Karta, czyli podstawowa treść widziana przez wszystkich, podaje je w trybie rozkazującym, bez informacji o ograniczonej podstawie empirycznej. Wymaga tego zasada EKSTRAPOLACJE. Pytania IT-M1-05-10 i IT-M1-05-51 robią to poprawnie. Rekomendacja jest bezpieczna (maszyna), więc severity MEDIUM, a nie HIGH.
- **PROPONOWANA KOREKTA:** „Rozsądną, choć niebadaną bezpośrednio praktyką jest od czasu do czasu sprawdzić swoją ocenę, kończąc serię do upadku w bezpiecznym ćwiczeniu, np. na maszynie.” Analogicznie w EN.
- **Pewność oceny:** wysoka
- **Weryfikacja:** CLAIMS_AUDIT (CL-RIR-003: INDIRECT, D→D).

#### M1-05-P17 · LOW · KC-M1-05 · pole `card.pl`, `card.en`
- **Claim / source:** CL-RIR-002, SRC-0106
- **OBECNIE:** „…ludzie mylą się średnio o około 1 powtórzenie, zwykle zaniżając zapas. Trafniej oceniają blisko upadku i w seriach do 12 powtórzeń.”
- **PROBLEM:** CL-RIR-002 mówi „nieco trafniejsze”, a w metaregresji efekt bliskości upadku był nieznaczny, z CI obejmującym 0 (β = −0,025; −0,05 do 0,0014). Lepiej udokumentowany jest efekt serii ≤12 powtórzeń. Karta pomija też dużą niejednorodność (I² = 97,9%), przez co „około 1 powtórzenia” brzmi precyzyjniej, niż pozwalają dane.
- **PROPONOWANA KOREKTA:** „…ludzie średnio zaniżają zapas o około 1 powtórzenie, przy dużych różnicach między osobami i badaniami. Trafniej oceniają w seriach do ok. 12 powtórzeń i nieco trafniej blisko upadku.” Analogicznie w EN.
- **Pewność oceny:** umiarkowana (liczby ze streszczenia wyszukiwarki)
- **Weryfikacja:** WebSearch (abstrakt Halperin 2022); EXTRA.

#### M1-05-P18 · LOW · MC-107 · pole `refutation.pl`, `refutation.en`
- **Claim / source:** CL-RIR-002, CL-RIR-003, SRC-0106
- **OBECNIE:** „…Dyskomfort może więc pojawić się wyraźnie wcześniej niż prawdziwy upadek. Pomaga ocena RIR pod koniec serii i od czasu do czasu sprawdzenie jej w bezpiecznym ćwiczeniu.”
- **PROBLEM:**
  - „Więc” odwraca logikę: zaniżanie zapasu nie dowodzi, że dyskomfort pojawia się wcześniej. Wczesny dyskomfort to hipotetyczna przyczyna zaniżania, a nie wniosek z niego.
  - „Pomaga … sprawdzenie” podaje niebadaną kalibrację (CL-RIR-003, D) jako fakt.
- **PROPONOWANA KOREKTA:** „…Prawdopodobnie dlatego, że dyskomfort pojawia się wyraźnie wcześniej niż prawdziwy upadek. Rozsądnie jest oceniać RIR pod koniec serii i od czasu do czasu sprawdzić tę ocenę w bezpiecznym ćwiczeniu (to praktyka, niebadana bezpośrednio).” Analogicznie w EN.
- **Pewność oceny:** wysoka
- **Weryfikacja:** CLAIMS_AUDIT (CL-RIR-003).

#### M1-05-P19 · LOW · MC-641 · pole `refutation.pl`, `refutation.en`
- **Claim / source:** CL-RIR-002, CL-RIR-003, SRC-0106
- **OBECNIE:** „Zarówno początkujący, jak i doświadczeni zwykle zaniżali zapas, średnio o około 1 powtórzenie, a w długich seriach bardziej. Okazjonalne sprawdzenie szacunku przydaje się niezależnie od stażu.”
- **PROBLEM:**
  - Średnia ok. 1 powtórzenia dotyczy całej puli, a nie każdej grupy osobno. Przypisanie jej obu grupom to nadprecyzja i zamiana braku różnicy na równoważność.
  - „Przydaje się” podaje niebadaną kalibrację jako fakt. MC-641.why_popular poprawnie przyznaje, że pojedyncze badania sugerowały lepszą trafność doświadczonych.
- **PROPONOWANA KOREKTA:** „W zestawieniu badań staż treningowy nie poprawiał wyraźnie trafności: także doświadczeni zwykle zaniżali zapas, a w długich seriach bardziej. Okazjonalne sprawdzenie szacunku to rozsądna praktyka niezależnie od stażu, choć nie badano jej bezpośrednio.” Analogicznie w EN.
- **Pewność oceny:** wysoka
- **Weryfikacja:** WebSearch (źródła wtórne o stażu); CLAIMS_AUDIT (CL-RIR-003).

#### M1-05-P20 · LOW · MC-642 · pole `refutation.pl`, `refutation.en`
- **Claim / source:** CL-RIR-002, SRC-0106
- **OBECNIE:** „W długich seriach kończonych daleko od upadku błąd bywa większy, między innymi dlatego, że pieczenie i zmęczenie pojawiają się wcześnie.”
- **PROBLEM:** Mechanizm (pieczenie) to hipoteza. Halperin 2022 go nie badał, a MC podaje go jako ustaloną przyczynę. Ten sam problem występuje w IT-M1-05-05 (P03).
- **PROPONOWANA KOREKTA:** „…błąd bywa większy, prawdopodobnie m.in. dlatego, że pieczenie i zmęczenie pojawiają się wcześnie.” Analogicznie w EN.
- **Pewność oceny:** wysoka
- **Weryfikacja:** EXTRA/WebSearch (Halperin – moderatory bez analizy mechanizmu).

#### M1-05-P21 · MEDIUM · MC-302 (KC-M3-02; przypięte do IT-04 D, IT-07 D, IT-08 D, IT-09 D, IT-51 C) · pole `refutation.pl`, `refutation.en`
- **Claim / source:** CL-AUTO-001 / CL-AUTO-003, SRC-0302, SRC-0303; dziedziczy C-10
- **OBECNIE:** „Programy, w których ciężar dobierano według RIR lub RPE, dawały co najmniej podobne przyrosty siły i mięśni jak programy oparte na procentach 1RM.”
- **PROBLEM:**
  - Metaanaliza (Hickmott 2022) łączy autoregulację RPE i opartą na prędkości (2,07 kg; CI −0,32 do 4,46).
  - Dane o mięśniach pochodzą praktycznie z jednego RCT (Helms 2018, n = 21, analiza MBI).
  - „Co najmniej podobne” sugeruje wykazaną nie-gorszość, czyli brak różnicy zamieniony na równoważność. Dziedziczy C-10.
  - Żadne pytanie tej karty nie powtarza tego zdania.
- **PROPONOWANA KOREKTA:** „W nielicznych, małych badaniach programy, w których ciężar dobierano według RIR/RPE, dawały przyrosty siły nieróżniące się istotnie od programów opartych na % 1RM. Dane o przyroście mięśni pochodzą praktycznie z jednego badania.” Analogicznie w EN. Przy audycie KC-M3-02 nie liczyć tego problemu podwójnie.
- **Pewność oceny:** wysoka
- **Weryfikacja:** CLAIMS_AUDIT C-10; dossier G3a.

#### M1-05-P22 · LOW · MC-105 (KC-M1-04; przypięte do IT-51 D, IT-71 C, IT-07 B, IT-09 C, IT-10 C, IT-08 C) · pole `refutation.pl`, `refutation.en`
- **Claim / source:** CL-EFF-002 / CL-EFF-003; dziedziczy C-05
- **OBECNIE:** „Badania porównujące trening do upadku z kończeniem serii kilka powtórzeń wcześniej zwykle nie pokazują wyraźnej różnicy w przyroście mięśni.”
- **PROBLEM:** „Kilka” jest szersze niż dane (głównie 0 vs 1-3 RIR), a przy lekkich ciężarach bliskość upadku ma większe znaczenie. Dziedziczy C-05. Problem łagodzi następne zdanie („z niewielkim zapasem”).
- **PROPONOWANA KOREKTA:** „…z kończeniem serii ok. 1-3 powtórzenia wcześniej…”. Analogicznie w EN.
- **Pewność oceny:** wysoka
- **Weryfikacja:** CLAIMS_AUDIT C-05.

#### M1-05-P23 · LOW · MC-106 (KC-M1-04; przypięte do IT-08 B, IT-71 D) · pole `refutation.pl`, `refutation.en`
- **Claim / source:** CL-EFF-001; dziedziczy C-27
- **OBECNIE:** „Seria buduje mięśnie tym skuteczniej, im bliżej upadku się kończy.”
- **PROBLEM:** Monotoniczne ujęcie kłóci się z danymi o wypłaszczeniu przy 0-3 RIR (C-27). Tę samą treść powtarza IT-M1-05-71 D (P13).
- **PROPONOWANA KOREKTA:** „Seria buduje mięśnie zwykle skuteczniej, gdy kończy się blisko upadku, niż gdy zostaje duży zapas.” Analogicznie w EN.
- **Pewność oceny:** umiarkowana
- **Weryfikacja:** CLAIMS_AUDIT C-27.

MC-640, MC-643 i MC-644 nie mają istotnych problemów. MC-640: kierunki skal i mapowanie RPE↔RIR poprawne. MC-643: właściwa kwalifikacja ryzyka upadku w ćwiczeniach z wolnym ciężarem bez asekuracji, z rekomendacją maszyn, asekuracji lub ograniczników. MC-644: definicja zgodna z CL-RIR-001.

### Podsumowanie partii
- Pytania: PASS 4, PASS WITH NOTES 6, REVISION REQUIRED 3, FAIL 0, UNVERIFIED 0 (razem 13).
- Problemy (tylko w pytaniach): CRITICAL 0, HIGH 0, MEDIUM 3 (P03, P06, P12), LOW 12 (P01, P02, P04, P05, P07, P08, P09, P10, P11, P13, P14, P15).
- Problemy w karcie/MC (osobno): CRITICAL 0, HIGH 0, MEDIUM 1 (P16 karta), LOW 4 (P17, P18, P19, P20). Uwaga recenzenta głównego: P21 (MC-302, karta KC-M3-02), P22 i P23 (MC-105, MC-106, karta KC-M1-04) dotyczą błędnych przekonań należących do innych kart – są liczone w partiach macierzystych (13 i 4), aby uniknąć podwójnego liczenia.
- Nowe ustalenia weryfikacyjne dla audytu twierdzeń (Halperin 2022, streszczenie abstraktu w wynikach wyszukiwarki, nie pełny tekst):
  - efekt „późniejszych serii” potwierdzony jako trywialny (β = −0,07; 95% CI −0,14 do −0,005);
  - brak wpływu stażu potwierdzony w źródłach wtórnych, więc C-29 można w dużej mierze zamknąć;
  - efekt bliskości upadku był nieznaczny, a jego 95% CI obejmował 0 (β = −0,025; −0,05 do 0,0014). Słowo „nieco” w CL-RIR-002 jest więc uzasadnione i powinno trafić też do karty.
- Aktualność (do przeglądu w ramach revision_trigger CL-RIR-002):
  - wyszukiwarka wskazała nowsze badania pierwotne porównujące trafność RIR u doświadczonych i początkujących (J Hum Kinet, przysiad, PMC13215226) oraz nowszą pracę o trafności RIR (efsupit 2025). Wyników nie zweryfikowano;
  - WebSearch nie wskazał badań nad kalibracją, więc stwierdzenie CL-RIR-003 „brak bezpośrednich badań” pozostaje niepodważone. Przeszukanie było jednak ograniczone.
- Ostatnie ID w partii: IT-M1-05-71
