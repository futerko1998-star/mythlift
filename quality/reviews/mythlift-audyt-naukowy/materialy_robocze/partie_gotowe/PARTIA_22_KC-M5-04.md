## Partia 22: KC-M5-04 — Zakwasy a uraz i sygnały alarmowe (treści z `sensitivity: pain_injury`, podwyższona ostrożność)

**Zakres partii:** pytania IT-M5-04-01 … IT-M5-04-62 (12), twierdzenia: CL-PAIN-001, CL-PAIN-002, CL-PAIN-003, CL-PAIN-004, źródła: SRC-0509, SRC-0510, SRC-0511. Audyt wykonany bezpośrednio przez recenzenta głównego. Wszystkie pytania mają `physio_reviewed: false` – recenzja fizjoterapeuty (wymagana przez FR-DOM-016) nie została jeszcze przeprowadzona; niniejszy audyt jej nie zastępuje.

### Tabela statusów
| ID | STATUS | SEVERITY | CLAIMS | SOURCES | KRÓTKIE UZASADNIENIE |
|---|---|---|---|---|---|
| IT-M5-04-01 | REVISION REQUIRED | MEDIUM | CL-PAIN-001 | SRC-0509 | Klucz 24-72 h poprawny, przedziały sensowne; W2 podaje mechanizm zakwasów („przyczyną są drobne uszkodzenia…”) jako pewny – nieaktualne i sprzeczne z CL-DOMS-001. |
| IT-M5-04-02 | PASS | — | CL-PAIN-001, CL-PAIN-003 | SRC-0509, SRC-0510 | Opis typowych zakwasów zgodny ze źródłem; dystraktory jednoznacznie błędne; brak twierdzeń mechanistycznych. |
| IT-M5-04-03 | REVISION REQUIRED | HIGH | CL-PAIN-004 | SRC-0511, SRC-0509 | Klucz (A-D) obronny, ale W1/W2/apply kierują WSZYSTKIE sygnały (w tym ból nocny, izolowane drętwienie kończyny) do „112 lub SOR”; źródło dotyczy tylko kręgosłupa i samo odróżnia stany nagłe od pilnych (dziedziczy C-25). |
| IT-M5-04-04 | REVISION REQUIRED | MEDIUM | CL-PAIN-001 | SRC-0509 | Klucz „mit” poprawny; W2 podaje mechanizm („To efekt drobnych uszkodzeń…”) jako pewny. |
| IT-M5-04-05 | REVISION REQUIRED | MEDIUM | CL-PAIN-002, CL-PAIN-003 | SRC-0510, SRC-0509 | Klucz A poprawny; feedback A i W1 simple/expert: „działa nie gorzej niż przerwa” – brak testu non-inferiority (dziedziczy C-24). |
| IT-M5-04-06 | REVISION REQUIRED | MEDIUM | CL-PAIN-002, CL-PAIN-001 | SRC-0510, SRC-0509 | Klucz A poprawny („podobnie jak przerwa” – dobrze); W1 expert: „nie była gorsza od przerwy” (C-24). |
| IT-M5-04-07 | REVISION REQUIRED | HIGH | CL-PAIN-004 | SRC-0511, SRC-0509 | Treść o rabdomiolizie merytorycznie poprawna, ale przypisane twierdzenie nie ma źródła obejmującego rabdomiolizę (SRC-0511 – kręgosłup) → fundament źródłowy do uzupełnienia. |
| IT-M5-04-08 | REVISION REQUIRED | HIGH | CL-PAIN-004 | SRC-0511, SRC-0509 | Klucz D (pilna pomoc przy podejrzeniu zerwania) poprawny; brak źródła obejmującego zerwania ścięgna (C-25). |
| IT-M5-04-09 | PASS WITH NOTES | LOW | CL-PAIN-003, CL-PAIN-001 | SRC-0509, SRC-0510 | Klucz C poprawny; feedback D wymienia „obrzęk” i „drętwienie” jako sygnały alarmowe bez kwalifikacji. |
| IT-M5-04-10 | PASS WITH NOTES | LOW | CL-PAIN-001, CL-PAIN-004 | SRC-0509, SRC-0511 | Klucz A (i częściowy B=0,5) obronny; kontrast z rabdomiolizą poprawny; źródło dla rabdomiolizy – jak IT-M5-04-07. |
| IT-M5-04-61 | REVISION REQUIRED | MEDIUM | CL-PAIN-002, CL-PAIN-003 | SRC-0510, SRC-0509 | Klucz B poprawny; feedback C, W1 expert, W2: „wyniki nie gorsze niż przerwa” (C-24). |
| IT-M5-04-62 | PASS WITH NOTES | LOW | CL-PAIN-001, CL-PAIN-003 | SRC-0509, SRC-0510 | Klucz A poprawny; „trening … zazwyczaj bezpieczny”, „wydłuża regenerację” – drobne, nieudokumentowane uogólnienia. |

### Szczegóły problemów

#### M5-04-P01 · MEDIUM · IT-M5-04-01 · pola `localizations.pl.w2`, `localizations.en.w2`
- **Claim / source:** CL-PAIN-001 / SRC-0509 (oraz CL-DOMS-001 / SRC-0111 – spójność bazy).
- **OBECNIE:** „Ich przyczyną są drobne uszkodzenia włókien mięśniowych i tkanki łącznej oraz reakcja zapalna, która rozwija się przez kolejne godziny.” / EN: „It is caused by small-scale damage to muscle fibers and connective tissue plus an inflammatory response…”.
- **PROBLEM:** Mechanizm podany jako ustalony. SRC-0509 (Cheung 2003) omawia kilka hipotez i wskazuje raczej ich połączenie; nowsze prace (Mizumura & Taguchi 2016, 2024; Hotfiel 2018) pokazują, że hiperalgezja typu DOMS może wystąpić bez widocznego uszkodzenia włókien, z udziałem czynników neurotroficznych (NGF, GDNF) uwrażliwiających zakończenia nerwowe (także w powięzi). Zdanie jest też wewnętrznie niespójne z CL-DOMS-001/KC-M1-07 („zakwasy słabo odzwierciedlają uszkodzenie mięśni”). Nie wpływa na klucz.
- **PROPONOWANA KOREKTA:** „Zakwasy wiążą się z drobnymi uszkodzeniami włókien mięśniowych i tkanki łącznej, reakcją zapalną oraz uwrażliwieniem zakończeń nerwowych w mięśniu i powięzi; dokładny mechanizm nie jest w pełni poznany.” (analogicznie EN).
- **Pewność oceny:** umiarkowana-wysoka. **Weryfikacja:** dossier G4b_pain [SEARCH https://link.springer.com/article/10.1007/s12576-015-0397-0 ; https://pmc.ncbi.nlm.nih.gov/articles/PMC10809664/].

#### M5-04-P02 · HIGH · IT-M5-04-03 · pola `localizations.pl.w1.simple`, `w1.apply`, `w2`, feedback opcji C i D (PL i EN)
- **Claim / source:** CL-PAIN-004 / SRC-0511 (dziedziczy C-25).
- **OBECNIE:** W1 simple: „Wymagają telefonu pod 112 lub wizyty na SOR.”; W2: „Drętwienie, osłabienie kończyny, zaburzenia czucia w okolicy krocza lub problemy z kontrolą pęcherza mogą wynikać z ucisku na nerwy. Ból z gorączką, zaczerwienieniem i ociepleniem okolicy albo ból nocny niezwiązany z ruchem może świadczyć o infekcji lub innej poważnej chorobie. (…) Przy każdym z nich właściwy krok to telefon pod 112 lub wizyta na SOR.”; feedback C: „…a także drętwienie lub osłabienie kończyny mogą oznaczać ucisk na nerwy. To wymaga pilnej pomocy.”; feedback D: „…a także ból nocny niezwiązany z ruchem…”.
- **PROBLEM:** Klucz (A-D poprawne, E-F błędne) jest merytorycznie obronny, bo wszystkie cztery opcje wymagają szybkiej oceny medycznej. Wyjaśnienia utożsamiają jednak „pilną pomoc” z „112/SOR natychmiast” dla każdego sygnału. Jedyne źródło (Finucane 2020) dotyczy kręgosłupa i samo rozróżnia stany nagłe (ogon koński – natychmiast) od pilnych (np. podejrzenie nowotworu, ból nocny – ocena w ciągu dni). Izolowane drętwienie kończyny po treningu i ból nocny nie są zwykle wskazaniem do wezwania 112. Objawy sercowe i rabdomioliza nie są objęte przypisanym źródłem. Adwersaryjnie: brak na liście nagłego, bardzo silnego bólu głowy w trakcie wysiłku (istotne dla osób dźwigających). Nadmierny triaż jest kierunkowo „bezpieczny”, ale uczy nieprawidłowej kwalifikacji i obciąża system ratunkowy; to treść zdrowotna, więc severity podniesione.
- **PROPONOWANA KOREKTA:** W1 simple: „Część z nich wymaga natychmiastowej pomocy (112 lub SOR): ból lub ucisk w klatce piersiowej, duszność lub omdlenie przy wysiłku, brunatny mocz z silnym bólem i obrzękiem mięśni, zaburzenia czucia w kroczu lub kłopoty z pęcherzem. Ból z gorączką, zaczerwienieniem i ociepleniem wymaga pilnej wizyty u lekarza tego samego dnia.” W2: rozdzielić analogicznie; ból nocny niezwiązany z ruchem i utrzymujące się drętwienie – „pilna konsultacja lekarska”; dodać nagły, bardzo silny ból głowy przy wysiłku do kategorii natychmiastowej. Źródła: Riebe 2015 (ACSM), O'Connor 2021 (rabdomioliza wysiłkowa) + SRC-0511 dla kręgosłupa. Wymaga recenzji fizjoterapeuty/lekarza.
- **Pewność oceny:** wysoka co do zakresu źródła i nadmiernego triażu; umiarkowana co do dokładnej kwalifikacji (wymaga recenzji klinicznej). **Weryfikacja:** audyt C-25; [SEARCH https://www.jospt.org/doi/10.2519/jospt.2020.9971].

#### M5-04-P03 · MEDIUM · IT-M5-04-04 · pola `localizations.pl.w2`, `localizations.en.w2`
- **Claim / source:** CL-PAIN-001 / SRC-0509.
- **OBECNIE:** „To efekt drobnych uszkodzeń włókien i tkanki łącznej oraz reakcji zapalnej.”
- **PROBLEM:** jak M5-04-P01 (mechanizm podany jako pewny).
- **PROPONOWANA KOREKTA:** „Wiąże się to z drobnymi uszkodzeniami włókien i tkanki łącznej, reakcją zapalną i uwrażliwieniem zakończeń nerwowych; mechanizm nie jest w pełni poznany.”
- **Pewność:** umiarkowana-wysoka.

#### M5-04-P04 · MEDIUM · IT-M5-04-05 · pola `option_texts.A.feedback`, `w1.simple`, `w1.expert` (PL i EN)
- **Claim / source:** CL-PAIN-002 / SRC-0510 (dziedziczy C-24).
- **OBECNIE:** feedback A: „Wstępne dane sugerują, że w takiej sytuacji dostosowany trening z obserwacją bólu działa nie gorzej niż przerwa.”; W1 simple: „…takie podejście działa nie gorzej niż przerwa.”; W1 expert: „…aktywność z monitorowaniem bólu dawała wyniki nie gorsze niż przerwa.” (EN: „no worse than a break”).
- **PROBLEM:** Silbernagel 2007 (2×19) – brak istotnych różnic i brak negatywnych skutków; nie był to test non-inferiority, więc „nie gorzej” to przekształcenie braku różnicy w równoważność. Dodatkowo dane dotyczą tendinopatii Achillesa w nadzorowanej rehabilitacji (ból dopuszczalny do 5/10), a scenariusz – bólu przedniej części kolana w przysiadzie; W2 poprawnie nazywa to ekstrapolacją, feedback A tego nie robi.
- **PROPONOWANA KOREKTA:** „Wstępne dane z jednego badania (ból ścięgna Achillesa) sugerują, że dostosowana aktywność z obserwacją bólu dawała podobne wyniki jak przerwa, bez niekorzystnych skutków.”
- **Pewność:** wysoka.

#### M5-04-P05 · MEDIUM · IT-M5-04-06 · pole `localizations.pl.w1.expert`, `localizations.en.w1.expert`
- **Claim / source:** CL-PAIN-002 / SRC-0510 (C-24).
- **OBECNIE:** „…aktywność z monitorowaniem bólu nie była gorsza od przerwy.” / „was not worse than a break”.
- **PROBLEM:** jak M5-04-P04. Pozostałe pola pytania („podobnie jak przerwa”) są sformułowane poprawnie – niespójność wewnątrz pytania.
- **PROPONOWANA KOREKTA:** „…aktywność z monitorowaniem bólu dała podobne wyniki jak przerwa.”
- **Pewność:** wysoka.

#### M5-04-P06 · HIGH · IT-M5-04-07 · pole `claims` / fundament źródłowy (bez zmiany treści)
- **Claim / source:** CL-PAIN-004 / SRC-0511, SRC-0509 (C-25).
- **OBECNIE:** Pytanie o rabdomiolizę wysiłkową opiera się wyłącznie na CL-PAIN-004, którego jedyne źródło „supports” to ramy sygnałów alarmowych dla kręgosłupa.
- **PROBLEM:** Treść pytania jest merytorycznie poprawna i zgodna z wytycznymi klinicznymi (mioglobinuria, ryzyko ostrego uszkodzenia nerek, czynniki ryzyka: nietypowy wysiłek, powrót po przerwie, dużo pracy ekscentrycznej, upał, odwodnienie; odróżnienie od odwodnienia). Jednak przypisane źródło nie obejmuje rabdomiolizy – w łańcuchu źródło → twierdzenie → pytanie brak ogniwa (wsparcie NONE dla tej tezy). Zdanie „Lista sygnałów alarmowych wynika z konsensusu klinicznego, bez badań porównawczych” jest prawdziwe, ale istnieją wytyczne kliniczne dotyczące rabdomiolizy wysiłkowej, które należy przywołać.
- **PROPONOWANA KOREKTA:** Dodać do CL-PAIN-004 (lub osobnego twierdzenia o rabdomiolizie) źródło: O'Connor FG i in. Clinical Practice Guideline for the Management of Exertional Rhabdomyolysis in Warfighters 2020, Curr Sports Med Rep 2021;20(3):169-178. Treści pytania nie trzeba zmieniać poza W1 expert: „…Lista sygnałów alarmowych wynika z konsensusu klinicznego i wytycznych postępowania…”.
- **Pewność:** wysoka. **Weryfikacja:** [SEARCH https://journals.lww.com/acsm-csmr/fulltext/2021/03000/clinical_practice_guidelines_for_exertional.10.aspx].

#### M5-04-P07 · HIGH · IT-M5-04-08 · pole `claims` / fundament źródłowy
- **Claim / source:** CL-PAIN-004 / SRC-0511 (C-25).
- **OBECNIE:** Scenariusz podejrzenia zerwania ścięgna Achillesa (trzask, szybki obrzęk, niemożność wspięcia na palce) → „Pilna pomoc: zadzwonić pod 112 lub jechać na SOR”.
- **PROBLEM:** Klucz D jest poprawny (podejrzenie ostrego zerwania wymaga pilnej oceny tego samego dnia; dystraktor C trafnie odrzucony jako „wizyta za kilka dni”). Przypisane źródło nie obejmuje urazów ścięgien/mięśni – fundament źródłowy nieobecny w bazie. Drobna uwaga: przy podejrzeniu zerwania właściwa jest wizyta na SOR/izbie przyjęć; wezwanie 112 zwykle nie jest konieczne – feedback D poprawnie mówi „pilnej pomocy tego samego dnia”.
- **PROPONOWANA KOREKTA:** Dodać źródło kliniczne dot. ostrych urazów ścięgien (np. wytyczne postępowania w ostrym zerwaniu ścięgna Achillesa) lub przegląd diagnostyki; opcję D doprecyzować: „Pilna pomoc: SOR tego samego dnia (w razie potrzeby 112)”.
- **Pewność:** wysoka co do braku źródła; umiarkowana co do proponowanego źródła (NIEZWERYFIKOWANE – należy dobrać po uzyskaniu dostępu do literatury).

#### M5-04-P08 · LOW · IT-M5-04-09 · pole `option_texts.D.feedback` (PL i EN)
- **OBECNIE:** „Ania nie ma jednak sygnałów alarmowych, takich jak gorączka, obrzęk, drętwienie czy nagła utrata funkcji.”
- **PROBLEM:** „Obrzęk” i „drętwienie” bez kwalifikacji nie są sygnałami alarmowymi w modelu triażu (tam: szybki obrzęk z trzaskiem; zaburzenia czucia w kroczu). Drobna niespójność z modelem; nie wpływa na klucz.
- **PROPONOWANA KOREKTA:** „…takich jak gorączka z zaczerwienieniem, nagły trzask z szybkim obrzękiem, zaburzenia czucia czy nagła utrata funkcji.”

#### M5-04-P09 · LOW · IT-M5-04-10 · pole `claims`
- **PROBLEM:** Kontrast z rabdomiolizą w W1 expert/W2 jest poprawny, ale opiera się na CL-PAIN-004 bez źródła dla rabdomiolizy (jak M5-04-P06). Drobne, bo nie jest główną tezą pytania.
- **PROPONOWANA KOREKTA:** jak M5-04-P06 (uzupełnienie źródła w twierdzeniu).

#### M5-04-P10 · MEDIUM · IT-M5-04-61 · pola `option_texts.C.feedback`, `w1.expert`, `w2` (PL i EN)
- **Claim / source:** CL-PAIN-002 / SRC-0510 (C-24).
- **OBECNIE:** feedback C: „…w badanym schorzeniu dalszy trening ze zmienionym obciążeniem dawał wyniki nie gorsze niż przerwa.”; W1 expert i W2: „…wyniki nie gorsze niż odpoczynek/przerwa…”.
- **PROBLEM:** jak M5-04-P04 („nie gorsze” bez testu non-inferiority). Pozytywnie: W2 zaznacza ekstrapolację i zawiera zastrzeżenie, że aplikacja nie diagnozuje.
- **PROPONOWANA KOREKTA:** „…dawał podobne wyniki jak przerwa, bez niekorzystnych skutków.”
- **Pewność:** wysoka.

#### M5-04-P11 · LOW · IT-M5-04-62 · pola `w1.expert`, `option_texts.B.feedback`
- **OBECNIE:** W1 expert: „Trening w tym czasie jest zazwyczaj bezpieczny…”; feedback B: „Ciężki trening obolałych mięśni do upadku daje jednak zwykle słabsze serie i wydłuża regenerację.”
- **PROBLEM:** „Bezpieczny” to słowo o większej sile niż źródło (przegląd zaleca lżejszy trening przez 1-2 dni ze względu na obniżoną siłę i propriocepcję); EN używa łagodniejszego „generally fine” – drobna różnica siły między PL i EN. „Wydłuża regenerację” – nieudokumentowane w bazie (prawdopodobne, [WIEDZA]).
- **PROPONOWANA KOREKTA:** W1 expert PL: „Trening w tym czasie jest zazwyczaj w porządku…”; feedback B: „…daje zwykle słabsze serie i może wydłużyć regenerację.”

### Karta pojęcia i błędne przekonania

#### M5-04-K01 · HIGH · KC-M5-04 · pole `card.pl/en` (oraz model triażu 7.6 i komponent PainTriageCard)
- **OBECNIE:** „Pilna pomoc (112 lub SOR): ból lub ucisk w klatce piersiowej, duszność, zawroty głowy lub omdlenie przy wysiłku; brunatny mocz z silnym bólem i obrzękiem mięśni; nagły trzask z obrzękiem lub utratą funkcji; drętwienie, osłabienie kończyny, zaburzenia czucia w kroczu, kłopoty z pęcherzem; ból z gorączką, zaczerwienieniem i ociepleniem albo nocny, niezwiązany z ruchem.”
- **PROBLEM:** Dziedziczy C-25: jedna kategoria „natychmiast 112/SOR” dla objawów o różnej pilności; brak rozróżnienia nagłe vs pilne; brak nagłego silnego bólu głowy przy wysiłku; źródło nie obejmuje większości listy. To najważniejsza treść bezpieczeństwa w aplikacji.
- **PROPONOWANA KOREKTA:** jak w C-25 (dwie podkategorie: „Natychmiast – 112/SOR” oraz „Pilnie do lekarza tego samego/następnego dnia”) + recenzja fizjoterapeuty/lekarza przed publikacją.

#### M5-04-K02 · MEDIUM · KC-M5-04 · pole `card.pl/en`
- **OBECNIE:** „Zakwasy to tępy, rozlany ból mięśni po nowym lub mocniejszym wysiłku, skutek mikrouszkodzeń, nie kwasu mlekowego.”
- **PROBLEM:** Mechanizm podany kategorycznie (jak M5-04-P01); niespójne z KC-M1-07 („słabo odzwierciedlają nawet samo uszkodzenie mięśni”).
- **PROPONOWANA KOREKTA:** „…ból mięśni po nowym lub mocniejszym wysiłku; wiąże się z drobnymi uszkodzeniami, stanem zapalnym i uwrażliwieniem zakończeń nerwowych, a nie z kwasem mlekowym.”

#### M5-04-K03 · LOW · MC-506 · pole `refutation.pl/en`
- **OBECNIE:** „Tłumaczy je raczej połączenie mikrouszkodzeń mięśni i tkanki łącznej oraz stanu zapalnego…”.
- **PROBLEM:** Sformułowanie ostrożne („raczej”), ale pomija rolę uwrażliwienia nocyceptorów (czynniki neurotroficzne). Drobne.
- **PROPONOWANA KOREKTA:** dodać „…oraz uwrażliwienia zakończeń nerwowych”.

#### M5-04-K04 · LOW · MC-509 · pole `refutation.pl/en`
- **OBECNIE:** „…w badaniu z kontrolą bólu dalsza aktywność nie dawała gorszych wyników niż przerwa.”
- **PROBLEM:** Sformułowanie opisowe, bliskie „nie gorsze”; lepiej „dawała podobne wyniki”. Brak informacji o schorzeniu (tendinopatia Achillesa).
- **PROPONOWANA KOREKTA:** „…w badaniu u osób z bólem ścięgna Achillesa dalsza aktywność z kontrolą bólu dawała podobne wyniki jak przerwa.”

#### M5-04-K05 · MEDIUM · MC-812, MC-814 · pola `refutation.pl/en`
- **OBECNIE:** MC-814: „Pilna pomoc jest potrzebna przy sygnałach alarmowych, np. (…) bólu z gorączką i zaczerwienieniem.”; MC-812: „Wymagają pilnej pomocy: telefonu pod 112 lub wizyty na SOR…”.
- **PROBLEM:** Dziedziczy C-25 (utożsamienie „pilnej pomocy” z 112/SOR dla wszystkich sygnałów).
- **PROPONOWANA KOREKTA:** dostosować do dwupoziomowej kategorii (jak C-25).

Pozostałe MC (MC-507, MC-508, MC-810, MC-811, MC-813, MC-815, MC-816): brak istotnych problemów (MC-816 „zakwasom rzeczywiście towarzyszą drobne uszkodzenia” – sformułowanie „towarzyszą” jest poprawne).

### Podsumowanie partii
- Pytania: PASS 1, PASS WITH NOTES 3, REVISION REQUIRED 8, FAIL 0, UNVERIFIED 0 (razem 12)
- Problemy (tylko w pytaniach): CRITICAL 0, HIGH 3, MEDIUM 5, LOW 3
- Problemy w karcie/MC (osobno): CRITICAL 0, HIGH 1, MEDIUM 2, LOW 2
- Ostatnie ID w partii: IT-M5-04-62
