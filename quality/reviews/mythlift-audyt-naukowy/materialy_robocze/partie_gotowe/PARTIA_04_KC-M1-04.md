## Partia 4: KC-M1-04 — Wysiłek i bliskość upadku (Effort and proximity to failure)

**Zakres partii:** pytania IT-M1-04-01 … IT-M1-04-61 (13: 01-11, 51, 61), twierdzenia: CL-EFF-001, CL-EFF-002, CL-EFF-003, CL-RIR-001, CL-REPS-001, CL-TENS-001, CL-VOL-003, źródła: SRC-0100, SRC-0101, SRC-0102, SRC-0103, SRC-0104, SRC-0105, SRC-0106, SRC-0107, SRC-0109, SRC-0202, SRC-0203, SRC-0211.

Podstawa oceny: audyt twierdzeń (CLAIMS_AUDIT.md: C-02, C-05, C-27 i tabela 0.3), dossier G1, G2 i EXTRA (m.in. Lasevicius 2022 i Refalo 2023 [SEARCH]), rekordy SRC-0104, SRC-0105 i SRC-0106. Do tego dwa własne wyszukiwania WebSearch w tej partii:
- Grgic i in. 2022, J Sport Health Sci 11(2):202-211. Ogółem brak istotnej różnicy między treningiem do upadku a bez upadku. W podgrupie osób trenujących siłowo trening do upadku miał małą, istotną przewagę dla hipertrofii: ES 0,15 (95% CI 0,03-0,26). Źródło: streszczenie w wynikach wyszukiwarki [SEARCH https://pubmed.ncbi.nlm.nih.gov/33497853/ ; https://www.sciencedirect.com/science/article/pii/S2095254621000077].
- Refalo i in. 2024, J Sports Sci: istnienie pracy potwierdzone [SEARCH https://www.tandfonline.com/doi/full/10.1080/02640414.2024.2321021]. Tytuł mówi o podobnej hipertrofii przy treningu do upadku i z zapasem powtórzeń u osób trenujących. Porównanie 0 vs 1-2 RIR pochodzi z wiedzy recenzenta [WIEDZA].

Pełnych tekstów nie sprawdzono (WebFetch zablokowany).

### Tabela statusów
| ID | STATUS | SEVERITY | CLAIMS | SOURCES | KRÓTKIE UZASADNIENIE |
|---|---|---|---|---|---|
| IT-M1-04-01 | PASS WITH NOTES | LOW | CL-EFF-001, CL-RIR-001 | SRC-0105, SRC-0104, SRC-0100, SRC-0107, SRC-0106 | Klucz B (liczba powtórzeń do upadku) jest poprawny, a dystraktory jednoznacznie błędne. Jedyna uwaga: niespójna definicja upadku (feedback B nazywa „upadkiem mięśniowym” to, co W2 opisuje jako wcześniejszy, techniczny punkt przerwania serii). |
| IT-M1-04-02 | REVISION REQUIRED | MEDIUM | CL-EFF-002, CL-EFF-001 | SRC-0104, SRC-0100, SRC-0105 | Przedziały full [1,3] i partial {0, 4} są obronialne. W W2 jest odwrócona logika: zaniżanie zapasu ma uzasadniać margines 1-3. Uwagi LOW: nieudokumentowane „mniej męczy”, zapas „niewielki” przypisany metaanalizie, brak zastrzeżenia dla lekkich ciężarów. |
| IT-M1-04-03 | REVISION REQUIRED | MEDIUM | CL-EFF-001, CL-REPS-001 | SRC-0105, SRC-0104, SRC-0100, SRC-0101, SRC-0102, SRC-0103 | Klucz A, C, E jest arytmetycznie poprawny (RIR 2, 2, 1). W1.expert i W2 dziedziczą C-02: badania nad ciężarami dotyczyły serii do upadku, a treść mówi „blisko upadku”. |
| IT-M1-04-04 | REVISION REQUIRED | MEDIUM | CL-EFF-003, CL-EFF-002 | SRC-0104, SRC-0105, SRC-0100 | Klucz „mit” jest poprawny (bezpośrednie dowody). Feedback i W1 dziedziczą C-05: podobny przyrost przypisany seriom kończonym „kilka” powtórzeń przed upadkiem. |
| IT-M1-04-05 | REVISION REQUIRED | MEDIUM | CL-EFF-001, CL-REPS-001 | SRC-0105, SRC-0104, SRC-0100, SRC-0101, SRC-0102, SRC-0103 | Klucz C (Ola) jest poprawny i dodatkowo wspiera go Lasevicius 2022. W1 dziedziczy C-02 („niezależnie od ciężaru”, „Kasia mogłaby rosnąć podobnie”). Uwaga LOW: założenie o większym tonażu Kasi. |
| IT-M1-04-06 | REVISION REQUIRED | MEDIUM | CL-EFF-001, CL-REPS-001 | SRC-0105, SRC-0104, SRC-0100, SRC-0101, SRC-0102, SRC-0103 | Klucz B jest poprawny. Treść dziedziczy C-02 i zawiera nieprzetestowaną receptę „27-29 powtórzeń” przy ciężarze na 30 powtórzeń, podaną dla każdej z 3 serii. Uwaga LOW: tonaż. |
| IT-M1-04-07 | REVISION REQUIRED | MEDIUM | CL-EFF-001, CL-TENS-001 | SRC-0105, SRC-0104, SRC-0100, SRC-0109, SRC-0103, SRC-0101 | Klucz D jest najlepszą opcją. Model „rekrutacja + zwolnienie ruchu = większe napięcie włókna” nie ma jednak źródła w bazie, a w W1.expert i feedbacku D jego elementy podano jako fakty. W2 dziedziczy C-02. |
| IT-M1-04-08 | REVISION REQUIRED | MEDIUM | CL-EFF-003 | SRC-0104, SRC-0105, SRC-0100 | Klucz C jest poprawny. Główne uzasadnienie (zmęczenie, regeneracja, technika) jest nieudokumentowane w bazie i podane kategorycznie; CL-EFF-002 nie jest przypięte do pytania. W2 dziedziczy C-05. |
| IT-M1-04-09 | REVISION REQUIRED | MEDIUM | CL-EFF-001 | SRC-0105, SRC-0104, SRC-0100 | Klucz B jest poprawny. Feedback B i W2 dziedziczą C-02: lżejszy ciężar „blisko upadku”, recepta 22-24 powtórzenia przy ciężarze na 25 powtórzeń. |
| IT-M1-04-10 | REVISION REQUIRED | MEDIUM | CL-REPS-001 | SRC-0101, SRC-0102, SRC-0103, SRC-0100 | Klucz B jest najlepszą opcją, ale cała teza opiera się na C-02 w wersji „Badania pokazują… blisko upadku”. Recepta RIR 1-3 (27-29 pompek) przy lekkim oporze nie była testowana. Pompki są poza bazą źródeł. |
| IT-M1-04-11 | PASS | — | CL-EFF-001, CL-VOL-003 | SRC-0105, SRC-0104, SRC-0100, SRC-0203, SRC-0211, SRC-0202 | Klucz „mit” jest poprawny (zdanie absolutne). Język jest ostrożny, niepewność progu serii efektywnej jest ujawniona, brak nieudokumentowanych tez. |
| IT-M1-04-51 | REVISION REQUIRED | MEDIUM | CL-EFF-002, CL-EFF-001, CL-EFF-003 | SRC-0104, SRC-0100, SRC-0105 | Klucz „fakt” jest poprawny. Feedback „depends” dziedziczy C-05 („kilka”). Uwagi LOW: pominięta przewaga upadku u trenujących (Grgic 2022), nieudokumentowane zmęczenie, zbyt szerokie przypisanie wniosku „metaanalizom”. |
| IT-M1-04-61 | FAIL | HIGH | CL-EFF-001, CL-EFF-002 | SRC-0105, SRC-0104, SRC-0100 | Klucz „zależy” jest niejednoznaczny. Zdanie zawiera fałszywą koniunkcję („tak samo… masy i siły”), więc według konwencji Mythlift (IT-M1-04-04, IT-M1-04-11) jest mitem; pytanie egzaminacyjne daje za „mit” 0 pkt. Dodatkowo overclaim w W2. |

### Szczegóły problemów

#### M1-04-P01 · LOW · IT-M1-04-01 · pole `localizations.pl.option_texts.B.feedback`, `localizations.pl.w1.simple`, `localizations.pl.w0` (analogicznie EN) vs `w1.expert`, `w2`
- **Claim / source:** CL-RIR-001 (SRC-0107, SRC-0106), CL-EFF-001 (SRC-0104)
- **OBECNIE:** B.feedback: „Upadek mięśniowy to moment, w którym mimo pełnego wysiłku nie da się wykonać kolejnego powtórzenia w poprawnej technice.” W1.expert: „Upadek mięśniowy to chwila, w której mimo maksymalnego wysiłku nie da się ukończyć fazy koncentrycznej kolejnego powtórzenia.” W2: „Część badań kończy serię wcześniej, gdy nie da się już utrzymać poprawnej techniki albo gdy osoba sama przerywa wysiłek.” oraz „Najczęściej chodzi o upadek mięśniowy”.
- **PROBLEM:** Pytanie definicyjne podaje dwie różne definicje punktu końcowego:
  - feedback B nazywa upadkiem mięśniowym niemożność wykonania powtórzenia w poprawnej technice (upadek techniczny);
  - W1.expert i W2 definiują upadek mięśniowy jako niemożność ukończenia fazy koncentrycznej, a punkt „utraty techniki” W2 opisuje jako wcześniejszy i inny.

  CL-RIR-001 rozdziela te pojęcia: RIR liczy powtórzenia w poprawnej technice przed upadkiem mięśniowym. SRC-0104 również rozróżnia definicję ścisłą i szeroką. Zdanie „Najczęściej chodzi o upadek mięśniowy” (częstość definicji w badaniach) nie ma źródła w bazie. Klucz B pozostaje poprawny przy obu definicjach.
- **PROPONOWANA KOREKTA:** B.feedback: „Tak. Bliskość upadku mówi, ile powtórzeń w poprawnej technice dzieli koniec serii od upadku, niezależnie od ciężaru. Upadek mięśniowy to moment, w którym mimo pełnego wysiłku nie da się ukończyć kolejnego powtórzenia; w praktyce serię często kończy się chwilę wcześniej, gdy technika zaczyna się psuć.” W W2 usunąć „Najczęściej” albo zastąpić zdaniem „Badania stosowały różne definicje upadku”. Analogicznie w EN.
- **Pewność oceny:** wysoka (spójność wewnętrzna)
- **Weryfikacja:** CL-RIR-001 statement; SRC-0104 (summary: definicja ścisła vs szeroka); dossier EXTRA (Refalo 2023 [SEARCH]).

#### M1-04-P02 · MEDIUM · IT-M1-04-02 · pole `localizations.pl.w2` (analogicznie `localizations.en.w2`)
- **Claim / source:** CL-EFF-002; dane o trafności RIR: CL-RIR-001/SRC-0106 (Halperin 2022)
- **OBECNIE:** „Zapas 1-3 powtórzeń daje też margines na błąd oceny, bo ludzie zaniżają swój zapas średnio o około jedno powtórzenie.”
- **PROBLEM:** Rozumowanie jest odwrócone. Halperin 2022: uczestnicy zaniżali liczbę pozostałych powtórzeń średnio o 0,95 (95% CI 0,17-1,73; I²≈98%). Rzeczywisty zapas jest więc zwykle większy od deklarowanego: seria oceniona na „2 w zapasie” kończy się średnio ok. 3 powtórzenia przed upadkiem. Takie zaniżanie nie grozi przypadkowym upadkiem i nie uzasadnia marginesu 1-3. Wręcz przeciwnie, przesuwa realny wysiłek dalej od upadku, niż zakłada cel. Margines bezpieczeństwa miałby sens przy przeszacowywaniu zapasu. Poprawnie ten sam fakt ujmuje IT-M1-04-51 W2: „seria oceniona na 2 w zapasie może w rzeczywistości kończyć się 3-4 powtórzenia przed upadkiem”. Mamy więc błędne wyjaśnienie w W2 i niespójność między pytaniami.
- **PROPONOWANA KOREKTA:** „Pamiętaj też, że ludzie zaniżają swój zapas średnio o ok. jedno powtórzenie (z dużymi różnicami między osobami), więc seria oceniona na 2 w zapasie może w rzeczywistości kończyć się ok. 3 powtórzenia przed upadkiem. Dlatego warto od czasu do czasu sprawdzić swoją ocenę w bezpiecznym ćwiczeniu.” Analogicznie w EN.
- **Pewność oceny:** wysoka
- **Weryfikacja:** SRC-0106 (summary); CLAIMS_AUDIT 0.2 (Halperin: zaniżanie 0,95, CI 0,17-1,73 [SEARCH]); EXTRA.

#### M1-04-P03 · LOW · IT-M1-04-02 · pola `localizations.pl.numeric_feedback.in_partial`, `.in_full`, `w1.simple`, `w1.expert`, `w2` (analogicznie EN)
- **Claim / source:** CL-EFF-002 (SRC-0104, SRC-0100, SRC-0105) – żadne twierdzenie w bazie nie obejmuje zmęczenia
- **OBECNIE:** „nie szkodzi to wzrostowi, ale nie jest konieczne i bardziej męczy”; „a mniej męczy”; „łączy więc większość bodźca z mniejszym zmęczeniem”; „Upadek w każdej serii zwykle zwiększa zmęczenie, przez co kolejne serie bywają słabsze, a w ciężkich ćwiczeniach wielostawowych utrudnia utrzymanie techniki.”
- **PROBLEM:** Teza o większym zmęczeniu i wolniejszej regeneracji po treningu do upadku oraz o gorszej technice jest nieudokumentowana. Nie ma jej w statement ani evidence_summary żadnego przypiętego twierdzenia ani źródła. Od niej zależy jednak uzasadnienie, dlaczego odpowiedź „0” dostaje tylko częściową punktację. Kierunek jest zgodny z literaturą [WIEDZA: np. Morán-Navarro i in. 2017, Eur J Appl Physiol – dłuższa regeneracja po seriach do upadku; badania nad progami spadku prędkości – do potwierdzenia], a sformułowania są w większości ostrożne („zwykle”, „bywają”). Chodzi więc o lukę dokumentacyjną, nie o błąd.
- **PROPONOWANA KOREKTA:** Dodać twierdzenie o kosztach zmęczeniowych treningu do upadku ze źródłem (np. Morán-Navarro 2017 – po weryfikacji bibliografii) i przypiąć je do pytania. Do tego czasu pisać „prawdopodobnie mniej męczy”.
- **Pewność oceny:** umiarkowana
- **Weryfikacja:** przegląd claims CL-EFF-001/002/003 (brak treści o zmęczeniu); [WIEDZA].

#### M1-04-P04 · LOW · IT-M1-04-02 · pole `localizations.pl.w1.expert` (analogicznie EN)
- **Claim / source:** CL-EFF-002, SRC-0104 (Refalo 2023)
- **OBECNIE:** „a metaanaliza treningu do upadku nie wykazała wyraźnej przewagi nad treningiem z niewielkim zapasem.”
- **PROBLEM:** Refalo 2023 porównywała trening do upadku z treningiem przerwanym przed upadkiem. Rekord SRC-0104 (limitations) mówi, że zapasu w grupach bez upadku zwykle nie mierzono, a w części badań był on duży (np. Lasevicius: ok. 20 z ok. 34 możliwych powtórzeń). Opis „z niewielkim zapasem” zawęża porównanie w sposób, którego źródło nie potwierdza. W W2 to samo ujęto poprawnie („z treningiem kończonym wcześniej”).
- **PROPONOWANA KOREKTA:** „…a metaanaliza nie wykazała wyraźnej przewagi treningu do upadku nad treningiem kończonym przed upadkiem (zapasu zwykle nie mierzono).”
- **Pewność oceny:** wysoka
- **Weryfikacja:** SRC-0104 (limitations); EXTRA (Refalo 2023, Lasevicius 2022 [SEARCH]).

#### M1-04-P05 · LOW · IT-M1-04-02 · pola `localizations.pl.stem`/`numeric_feedback.in_full`/`w2` (analogicznie EN)
- **Claim / source:** CL-EFF-002 (C-05), CL-REPS-001 (C-02)
- **OBECNIE:** „Zakres 1-3 powtórzeń w zapasie to praktyczny wniosek z dwóch rodzajów danych.” (bez zastrzeżenia co do ciężaru)
- **PROBLEM:** Korekta C-05 w audycie twierdzeń zawęża zakres 1-3 RIR do umiarkowanych i dużych ciężarów. Przy lekkich ciężarach bliskość upadku ma większe znaczenie (Lasevicius 2022), a w seriach powyżej ok. 12 powtórzeń zapas ocenia się gorzej (Halperin 2022). Pytanie dotyczy „większości serii roboczych”, więc klucz jest obronialny, ale W2 nie mówi, że zakres 1-3 nie przenosi się automatycznie na bardzo długie serie lekkim ciężarem.
- **PROPONOWANA KOREKTA:** Dopisać w W2: „Przy lekkich ciężarach i długich seriach (ok. 20 i więcej powtórzeń) warto kończyć serie bliżej upadku. Dane dla takich ciężarów dotyczą głównie serii do upadku, a zapas trudniej w nich ocenić.”
- **Pewność oceny:** umiarkowana
- **Weryfikacja:** CLAIMS_AUDIT C-02, C-05; EXTRA (Lasevicius 2022 [SEARCH]); SRC-0106.

#### M1-04-P06 · MEDIUM · IT-M1-04-03 · pola `localizations.pl.w1.expert`, `localizations.pl.w2` (analogicznie EN)
- **Claim / source:** CL-REPS-001 (SRC-0101, SRC-0103, SRC-0102, SRC-0100) – dziedziczone C-02
- **OBECNIE:** W1.expert: „Przy wysiłku blisko upadku lekkie i ciężkie obciążenia dają podobny przyrost mięśni, a serie z dużym zapasem prawdopodobnie słabszy.” W2: „Badania, w których serie kończono blisko upadku, pokazują podobny przyrost mięśni w szerokim zakresie obciążeń, mniej więcej od 30% maksimum wzwyż.”
- **PROBLEM:** Treść dziedziczy problem C-02 (MEDIUM). Główne dowody (Schoenfeld 2017: kryterium włączenia to wszystkie serie do chwilowego upadku; Morton 2016: serie do upadku) dotyczą serii **do upadku**, a nie „blisko upadku”. Dla lekkich ciężarów (ok. 30% 1RM) seria przerwana wcześniej dawała mniejszą hipertrofię niż seria do upadku, a przy 80% 1RM nie (Lasevicius 2022). W2 błędnie opisuje warunek badań. W tym pytaniu, które uczy, że serie 23/25 i 10/12 są „równie blisko upadku”, może to sugerować, że lekki ciężar z RIR 2-3 daje taki sam bodziec jak ciężki. Tego nie testowano.
- **PROPONOWANA KOREKTA:** W2: „Badania, w których serie kończono na upadku mięśniowym, pokazują podobny przyrost mięśni w szerokim zakresie obciążeń, mniej więcej od 30% maksimum wzwyż. Przy lekkich ciężarach warunek jest ostrzejszy: seria powinna kończyć się bardzo blisko upadku, bo seria lekkim ciężarem przerwana wyraźnie wcześniej dawała w badaniu mniejszy przyrost.” W1.expert: „Przy seriach do upadku lub bardzo blisko niego lekkie i ciężkie obciążenia dają podobny przyrost…”. Analogicznie w EN.
- **Pewność oceny:** wysoka
- **Weryfikacja:** CLAIMS_AUDIT C-02; dossier G1 (Schoenfeld 2017 – kryteria [SEARCH]); EXTRA (Lasevicius 2022 [SEARCH https://pubmed.ncbi.nlm.nih.gov/31895290/]).

#### M1-04-P07 · LOW · IT-M1-04-03 · pole `localizations.pl.w2` (analogicznie EN)
- **Claim / source:** CL-RIR-001 / SRC-0106 (niepodpięte do pytania)
- **OBECNIE:** „w długich seriach zapas trudniej ocenić, bo zmęczenie i pieczenie narastają stopniowo”
- **PROBLEM:** Pierwsza część zdania ma wsparcie (Halperin 2022: trafność gorsza w seriach powyżej ok. 12 powtórzeń). Wyjaśnienie przyczynowe („bo zmęczenie i pieczenie narastają stopniowo”) nie ma źródła w bazie i jest hipotezą autora treści.
- **PROPONOWANA KOREKTA:** „w długich seriach (powyżej ok. 12 powtórzeń) zapas ocenia się mniej trafnie, a ludzie zaniżają go średnio o około jedno powtórzenie.”
- **Pewność oceny:** umiarkowana
- **Weryfikacja:** SRC-0106 (summary); CLAIMS_AUDIT 0.2.

#### M1-04-P08 · MEDIUM · IT-M1-04-04 · pola `localizations.pl.main_feedback.myth`, `.main_feedback.fact`, `w1.simple` (analogicznie EN: „a few reps short”)
- **Claim / source:** CL-EFF-002 (SRC-0104, SRC-0100, SRC-0105) – dziedziczone C-05
- **OBECNIE:** myth: „Serie zakończone kilka powtórzeń przed upadkiem też budują mięśnie, a różnica względem upadku jest zwykle mała albo żadna.” fact: „Badania porównujące trening do upadku z kończeniem serii kilka powtórzeń wcześniej pokazują jednak przyrost w obu grupach i małe różnice albo żadne.” W1.simple: „W badaniach osoby kończące serie kilka powtórzeń przed upadkiem zyskiwały podobnie jak te, które dochodziły do upadku.”
- **PROBLEM:** Treść dziedziczy C-05 (MEDIUM). „Kilka” (PL: zwykle 3-9; EN „a few”) jest szersze niż dane:
  - w Refalo 2023 zapasu w grupach bez upadku zwykle nie mierzono;
  - RCT u osób trenujących porównywało 0 z 1-2 RIR (Refalo 2024 [SEARCH – istnienie; szczegóły WIEDZA]);
  - metaregresja Robinson 2024 wskazuje malejący przyrost przy rosnącym RIR;
  - u osób trenujących metaanaliza Grgic 2022 pokazała małą przewagę upadku (ES 0,15; 95% CI 0,03-0,26 [SEARCH]).

  Powstaje też sprzeczność wewnętrzna: to samo pytanie mówi, że „duży zapas powtórzeń daje prawdopodobnie mniej” (W1.simple), a CL-VOL-003 uznaje serie z 5 i więcej RIR za słabszy bodziec. W0 („też buduje mięśnie”) jest poprawne i nie wymaga zmiany.
- **PROPONOWANA KOREKTA:** Zastąpić „kilka powtórzeń” sformułowaniem „1-3 powtórzenia (przy umiarkowanych i dużych ciężarach)”. myth: „Tak, to mit. Serie zakończone 1-3 powtórzenia przed upadkiem też budują mięśnie, a różnica względem upadku jest zwykle mała albo żadna.” W1.simple: „…osoby kończące serie z niewielkim zapasem (np. 1-2 powtórzenia) zyskiwały podobnie…”. Analogicznie w EN.
- **Pewność oceny:** wysoka
- **Weryfikacja:** CLAIMS_AUDIT C-05; SRC-0104 (limitations); WebSearch Grgic 2022 i Refalo 2024 (URL we wstępie).

#### M1-04-P09 · LOW · IT-M1-04-04 · pole `localizations.pl.main_feedback.depends` (analogicznie EN)
- **Claim / source:** CL-EFF-002
- **OBECNIE:** „seria zakończona 1-3 powtórzenia przed upadkiem nie jest stracona i daje podobny przyrost.”
- **PROBLEM:** Twierdzenie CL-EFF-002 mówi „podobny albo tylko nieco mniejszy”. Ten feedback usuwa drugą część. Metaregresja (Robinson 2024) i przewaga upadku w podgrupie osób trenujących (Grgic 2022) wskazują, że mała różnica jest możliwa.
- **PROPONOWANA KOREKTA:** „…nie jest stracona i daje podobny albo tylko nieco mniejszy przyrost.” Analogicznie w EN.
- **Pewność oceny:** wysoka
- **Weryfikacja:** CL-EFF-002 statement; WebSearch Grgic 2022.

#### M1-04-P10 · LOW · IT-M1-04-04 · pole `localizations.pl.w2` (analogicznie EN)
- **Claim / source:** brak twierdzenia w bazie
- **OBECNIE:** „Upadek ma też koszty. Zwykle zwiększa zmęczenie, przez co kolejne serie bywają słabsze, a w ciężkich ćwiczeniach ze sztangą utrudnia utrzymanie techniki i bez asekuracji bywa ryzykowny.”
- **PROBLEM:** Teza o kosztach zmęczeniowych i technicznych jest nieudokumentowana w bazie (jak w P03). Sformułowania są ostrożne, a kierunek zgodny z literaturą [WIEDZA]. Zdanie o ryzyku bez asekuracji to rozsądna praktyka bezpieczeństwa (opinia ekspercka), ale nie jest oznaczone jako praktyka.
- **PROPONOWANA KOREKTA:** Podpiąć twierdzenie o kosztach zmęczeniowych (patrz P03). Zdanie o asekuracji oznaczyć jako zalecenie praktyczne: „…w praktyce zaleca się wtedy asekurację.”
- **Pewność oceny:** umiarkowana
- **Weryfikacja:** przegląd claims; [WIEDZA].

#### M1-04-P11 · MEDIUM · IT-M1-04-05 · pola `localizations.pl.w1.simple`, `localizations.pl.w1.expert` (analogicznie EN)
- **Claim / source:** CL-REPS-001 – dziedziczone C-02; CL-EFF-001
- **OBECNIE:** W1.simple: „Mięśnie rosną zwykle lepiej, gdy seria kończy się blisko upadku, niezależnie od tego, czy ciężar jest lekki, czy ciężki. Kasia mogłaby rosnąć podobnie, gdyby wydłużyła serie.” W1.expert: „…a przy wysiłku blisko upadku lekkie i ciężkie obciążenia dają podobny przyrost.”
- **PROBLEM:** Treść dziedziczy C-02 (patrz P06). Dowody na równoważność ciężarów dotyczą serii do upadku. Kasia używa ciężaru na ok. 30 powtórzeń, czyli lekkiego, a dla takich ciężarów upadek wydaje się mieć większe znaczenie (Lasevicius 2022). Zdanie „mogłaby rosnąć podobnie, gdyby wydłużyła serie” nie mówi, jak blisko upadku musiałaby kończyć serie. Sam klucz C jest dobrze uzasadniony: Lasevicius 2022 bezpośrednio pokazało mniejszy przyrost przy lekkim ciężarze przerwanym daleko od upadku i brak różnicy przy ciężkim ciężarze.
- **PROPONOWANA KOREKTA:** W1.simple: „…Przy serii do upadku lub bardzo blisko niego także lekki ciężar buduje mięśnie podobnie jak ciężki. Kasia mogłaby rosnąć podobnie, gdyby kończyła serie bardzo blisko upadku.” W1.expert: „…a przy seriach do upadku lub bardzo blisko niego lekkie i ciężkie obciążenia dają podobny przyrost.”
- **Pewność oceny:** wysoka
- **Weryfikacja:** CLAIMS_AUDIT C-02; EXTRA (Lasevicius 2022 [SEARCH]).

#### M1-04-P12 · LOW · IT-M1-04-05 · pole `localizations.pl.option_texts.A.feedback` (analogicznie EN)
- **Claim / source:** brak (założenie scenariusza)
- **OBECNIE:** „To kusi, bo Kasia robi prawie dwa razy więcej powtórzeń i łącznie podnosi więcej kilogramów.”
- **PROBLEM:** Kontekst nie podaje ciężarów, a większy tonaż Kasi nie wynika ze scenariusza. Kasia wykonuje 45 powtórzeń ciężarem na ok. 30 RM, Ola 24 powtórzenia ciężarem na ok. 10 RM (ok. 75% 1RM). Kasia podnosi łącznie więcej tylko wtedy, gdy jej ciężar przekracza ok. 40% 1RM. Według wzoru Epleya [WIEDZA] 30 RM to ok. 50% 1RM i warunek jest spełniony. W ćwiczeniach jednostawowych 30% 1RM pozwala jednak na ok. 34 powtórzenia (Lasevicius 2022), a wtedy tonaż Kasi byłby mniejszy. Klucz się nie zmienia.
- **PROPONOWANA KOREKTA:** Dopisać do kontekstu „…i łącznie podnosi więcej kilogramów niż Ola” albo w feedbacku napisać „zwykle podnosi łącznie więcej kilogramów”.
- **Pewność oceny:** umiarkowana
- **Weryfikacja:** obliczenie własne; EXTRA (Lasevicius 2022 – ok. 34 powt. przy 30% 1RM [SEARCH]); [WIEDZA – wzór Epleya].

#### M1-04-P13 · MEDIUM · IT-M1-04-06 · pola `localizations.pl.option_texts.A.feedback`, `w1.simple`, `w1.expert`, `w2` (analogicznie EN)
- **Claim / source:** CL-REPS-001 – dziedziczone C-02; CL-EFF-001
- **OBECNIE:** A.feedback: „Przy wysiłku blisko upadku podobny przyrost dają jednak także serie po 20-30 powtórzeń.” W1.simple: „Gdyby Kasia robiła swoim ciężarem ok. 27-29 powtórzeń, mogłaby rosnąć podobnie jak Ola.” W1.expert: „przy wysiłku blisko upadku obciążenia od ok. 30% 1RM dają podobną hipertrofię”. W2: „Badania, w których serie lekkim i ciężkim ciężarem kończono blisko upadku, pokazują podobny przyrost… Kluczowy jest ten warunek: blisko upadku.”
- **PROBLEM:** Treść dziedziczy C-02 (patrz P06). W2 błędnie opisuje warunek badań: były to serie do upadku. Konkretna recepta „27-29 powtórzeń” przy ciężarze na 30 RM (RIR 1-3) nie była testowana, a dla lekkich ciężarów dane (Lasevicius 2022) sugerują, że upadek ma większe znaczenie. Recepta pomija też zmęczenie w obrębie sesji: przy 3 seriach i typowych przerwach 27-29 powtórzeń w drugiej i trzeciej serii jest zwykle niewykonalne, bo maksimum spada. Zalecenie powinno być ujęte jako zapas, a nie stała liczba powtórzeń.
- **PROPONOWANA KOREKTA:** W1.simple: „Gdyby Kasia kończyła każdą serię bardzo blisko upadku (w pierwszej serii to ok. 28-30 powtórzeń, w kolejnych mniej), mogłaby rosnąć podobnie jak Ola.” W2: „Badania, w których serie lekkim i ciężkim ciężarem kończono na upadku mięśniowym, pokazują podobny przyrost… Przy lekkim ciężarze kluczowe jest, żeby seria kończyła się bardzo blisko upadku.” A.feedback i W1.expert: „przy seriach do upadku lub bardzo blisko niego”. Analogicznie w EN.
- **Pewność oceny:** wysoka (C-02); umiarkowana (wykonalność powtórzeń w kolejnych seriach – [WIEDZA])
- **Weryfikacja:** CLAIMS_AUDIT C-02; EXTRA (Lasevicius 2022 [SEARCH]).

#### M1-04-P14 · LOW · IT-M1-04-06 · pola `localizations.pl.option_texts.C.feedback`, `w2` (analogicznie EN)
- **Claim / source:** brak (założenie scenariusza)
- **OBECNIE:** C.feedback: „…a Kasia mimo większej sumy kończy serie z ok. 15 powtórzeniami w zapasie.” W2: „Kasia robi więcej powtórzeń i podnosi łącznie więcej kilogramów…”
- **PROBLEM:** Ten sam problem co w P12: większy tonaż Kasi nie wynika z kontekstu, a w ćwiczeniach jednostawowych może być fałszywy.
- **PROPONOWANA KOREKTA:** Uzupełnić kontekst o informację o tonażu albo pisać „zwykle podnosi łącznie więcej kilogramów”.
- **Pewność oceny:** umiarkowana
- **Weryfikacja:** jak P12.

#### M1-04-P15 · MEDIUM · IT-M1-04-07 · pola `localizations.pl.option_texts.D.feedback`, `w0`, `w1.expert`, `w2` (analogicznie EN)
- **Claim / source:** CL-TENS-001 (SRC-0109), CL-EFF-001 (SRC-0105). Żadne z nich nie obejmuje mechanizmu rekrutacji ani zależności siła-prędkość blisko upadku.
- **OBECNIE:** D.feedback: „W miarę narastania zmęczenia układ nerwowy włącza kolejne jednostki ruchowe, także te sterujące największymi włóknami, a ruch zwalnia, więc włókna pracują pod dużym napięciem.” W1.expert: „Wraz ze zmęczeniem rośnie rekrutacja jednostek ruchowych o wysokim progu pobudzenia, z włóknami typu II, a spadek prędkości skurczu zwiększa siłę generowaną przez pojedyncze włókno.” W0: „Blisko upadku pracuje więcej włókien pod dużym napięciem…”
- **PROBLEM:** Klucz D jest najlepszą opcją: A (hormony), B (pompa) i C (uszkodzenia/zakwasy) mają słabsze uzasadnienie w bazie (CL-TENS-001, Wackerhage 2019, Morton 2016). Mechanizm z klucza nie ma jednak źródła w bazie:
  - CL-TENS-001 mówi tylko, że napięcie mechaniczne uznaje się za główny bodziec;
  - model „zmęczenie → rekrutacja jednostek o wysokim progu → wolny skurcz → większe napięcie pojedynczego włókna” to hipoteza mechanistyczna (tzw. model „efektywnych powtórzeń”).

  Element siła-prędkość jest najbardziej spekulatywny: we włóknach zmęczonych spadek prędkości wynika częściowo ze spadku zdolności do generowania siły. Mimo to W1.expert i feedback D podają go jako fakt („zwiększa siłę generowaną przez pojedyncze włókno”). Dane o pełnej rekrutacji przy lekkich ciężarach są częściowo sporne [WIEDZA: Morton i in. 2019, J Physiol – podobna aktywacja włókien typu I i II przy 30% i 80% 1RM do upadku, wspierające; badania dekompozycji EMG sugerujące niepełną rekrutację przy niskich obciążeniach, sprzeczne – szczegóły do potwierdzenia]. Pozytywnie: W1.simple i W2 uczciwie zaznaczają, że to model oparty na badaniach mechanizmów, niesprawdzony w całości.
- **PROPONOWANA KOREKTA:** Dodać twierdzenie mechanistyczne (np. „Blisko upadku rekrutowane są także jednostki ruchowe o wysokim progu; to najczęstsze wyjaśnienie większego bodźca, oparte głównie na danych mechanistycznych”, pewność C) ze źródłem (np. Morton 2019 – po weryfikacji bibliografii). W1.expert: „Najczęstsze wyjaśnienie (model, nie bezpośredni pomiar): wraz ze zmęczeniem rośnie rekrutacja jednostek ruchowych o wysokim progu pobudzenia; według tej hipotezy wolniejszy skurcz pozwala pojedynczym włóknom wytwarzać większe napięcie.” Feedback D: „…więc włókna prawdopodobnie pracują pod dużym napięciem.” Analogicznie w EN.
- **Pewność oceny:** umiarkowana
- **Weryfikacja:** CL-TENS-001 i SRC-0109 (dossier G1, EXTRA [SEARCH]); [WIEDZA] jak wyżej.

#### M1-04-P16 · MEDIUM · IT-M1-04-07 · pole `localizations.pl.w2` (analogicznie EN)
- **Claim / source:** CL-REPS-001 (niepodpięte do pytania) – dziedziczone C-02
- **OBECNIE:** „…a lekkie ciężary dają przyrost podobny do ciężkich wtedy, gdy serie kończą się blisko upadku.”
- **PROBLEM:** Ten sam problem co w P06: badania dotyczyły serii do upadku. Pytanie powtarza tezę, nie mając podpiętego CL-REPS-001.
- **PROPONOWANA KOREKTA:** „…a lekkie ciężary dają przyrost podobny do ciężkich, gdy serie kończą się na upadku lub bardzo blisko niego.” Analogicznie w EN. Podpiąć CL-REPS-001.
- **Pewność oceny:** wysoka
- **Weryfikacja:** CLAIMS_AUDIT C-02; EXTRA.

#### M1-04-P17 · MEDIUM · IT-M1-04-08 · pola `localizations.pl.option_texts.C.feedback`, `w0`, `w1.simple`, `w1.expert` (analogicznie EN), metadane `claims`
- **Claim / source:** CL-EFF-003 (jedyne przypięte); CL-EFF-002 nieprzypięte; brak twierdzenia o zmęczeniu
- **OBECNIE:** C.feedback: „…a mniej męczą, więc kolejne serie i treningi będą mocniejsze. W przysiadzie łatwiej też utrzymać technikę.” W0: „Zapas 1-3 powtórzeń daje podobny przyrost przy mniejszym zmęczeniu.” W1.simple: „Dzięki temu w kolejnych seriach zrobi więcej powtórzeń i szybciej się zregeneruje.” W1.expert: „…a upadek zwiększa zmęczenie i spadek powtórzeń w kolejnych seriach.”
- **PROBLEM:** W tym scenariuszu teza o kosztach zmęczeniowych upadku jest głównym uzasadnieniem klucza (kontekst: spadek 10→7→5 powtórzeń, dwa dni zmęczenia). Nie ma jej jednak w żadnym twierdzeniu ani źródle bazy. Sformułowania są kategoryczne: „będą mocniejsze”, „zrobi więcej powtórzeń i szybciej się zregeneruje”. Kierunek jest zgodny z literaturą [WIEDZA: np. Morán-Navarro 2017], ale siła języka przekracza udokumentowaną podstawę. Pytanie ma przypięte tylko CL-EFF-003 (mit), choć klucz rekomenduje zakres 1-3 RIR, czyli treść CL-EFF-002. W0 pomija też część „albo nieco mniejszy” z CL-EFF-002. Klucz C pozostaje poprawny niezależnie od tej luki, bo A i B opierają się na micie, a D prowadzi do dużego zapasu.
- **PROPONOWANA KOREKTA:** Podpiąć CL-EFF-002 i twierdzenie o kosztach zmęczeniowych (patrz P03). Złagodzić: C.feedback: „…a zwykle mniej męczą, więc kolejne serie i treningi mogą być mocniejsze.”; W1.simple: „Dzięki temu w kolejnych seriach prawdopodobnie zrobi więcej powtórzeń i szybciej się zregeneruje.”; W0: „Zapas 1-3 powtórzeń daje podobny albo tylko nieco mniejszy przyrost przy mniejszym zmęczeniu.” Analogicznie w EN.
- **Pewność oceny:** umiarkowana
- **Weryfikacja:** przegląd claims; CL-EFF-002 statement; [WIEDZA].

#### M1-04-P18 · MEDIUM · IT-M1-04-08 · pole `localizations.pl.w2` (analogicznie EN: „stopping a few reps short”)
- **Claim / source:** CL-EFF-002 – dziedziczone C-05
- **OBECNIE:** „W badaniach porównujących trening do upadku z treningiem kończonym kilka powtórzeń wcześniej przyrost mięśni był podobny albo różnica była niewielka.”
- **PROBLEM:** Treść dziedziczy C-05 (patrz P08). W badaniach grup bez upadku zapasu zwykle nie mierzono (SRC-0104). „Kilka” poszerza zakres podobieństwa ponad dane, a u osób trenujących (jak Paweł) metaanaliza Grgic 2022 pokazała małą przewagę upadku.
- **PROPONOWANA KOREKTA:** „W badaniach porównujących trening do upadku z treningiem kończonym przed upadkiem przyrost mięśni był podobny albo różnica była niewielka; w badaniu u osób trenujących zapas 1-2 powtórzeń dał podobną hipertrofię jak upadek.” Wymaga dodania źródła Refalo 2024 do bazy.
- **Pewność oceny:** wysoka
- **Weryfikacja:** CLAIMS_AUDIT C-05; SRC-0104; WebSearch Grgic 2022 i Refalo 2024.

#### M1-04-P19 · MEDIUM · IT-M1-04-09 · pola `localizations.pl.option_texts.B.feedback`, `localizations.pl.w2` (analogicznie EN)
- **Claim / source:** CL-EFF-001; CL-REPS-001 (niepodpięte) – dziedziczone C-02
- **OBECNIE:** B.feedback: „Może zostać przy tym ciężarze i robić ok. 22-24 powtórzenia…” W2: „Może zostać przy tym ciężarze i wydłużyć serie do ok. 22-24 powtórzeń, bo lżejszy ciężar też buduje mięśnie, jeśli seria kończy się blisko upadku.”
- **PROBLEM:** Ten sam problem co w P06: równoważność lżejszych ciężarów wykazano dla serii do upadku. Recepta RIR 1-3 przy ciężarze na ok. 25 powtórzeń to ekstrapolacja, a zapas w tak długich seriach ocenia się mniej trafnie (Halperin 2022, co W2 częściowo zaznacza). Recepta „22-24 powtórzenia” w każdej z 3 serii pomija spadek maksimum w kolejnych seriach. Klucz B pozostaje poprawny, bo kierunek (zmniejszyć zapas) jest dobrze uzasadniony.
- **PROPONOWANA KOREKTA:** W2: „…Może zostać przy tym ciężarze i kończyć serie bardzo blisko upadku (w pierwszej serii to ok. 23-25 powtórzeń, w kolejnych mniej), bo lżejszy ciężar też buduje mięśnie, jeśli seria kończy się na upadku lub bardzo blisko niego…”. Analogicznie B.feedback i EN.
- **Pewność oceny:** wysoka (C-02); umiarkowana (wykonalność powtórzeń w kolejnych seriach)
- **Weryfikacja:** CLAIMS_AUDIT C-02; EXTRA (Lasevicius 2022); SRC-0106.

#### M1-04-P20 · MEDIUM · IT-M1-04-10 · pola `localizations.pl.option_texts.B.text`, `.B.feedback`, `w0`, `w1.simple`, `w1.expert`, `w1.apply`, `w2` (analogicznie EN)
- **Claim / source:** CL-REPS-001 (SRC-0101, SRC-0102, SRC-0103, SRC-0100) – dziedziczone C-02
- **OBECNIE:** W1.simple: „Badania pokazują, że przy seriach kończonych blisko upadku lżejszy opór buduje mięśnie podobnie jak duży ciężar.” B.text: „Robić w każdej serii tyle pompek, żeby do upadku zostawały 1-3, nawet ok. 27-29”. W2: „Badania, w których serie lżejszym i cięższym obciążeniem kończono blisko upadku, pokazały jednak podobny przyrost mięśni w szerokim zakresie obciążeń, mniej więcej od 30% maksimum wzwyż. (…) Wydłużenie serii do ok. 27-29 powtórzeń rozwiązuje ten problem.”
- **PROBLEM:** To najbardziej istotne wystąpienie C-02 w tej karcie, bo teza jest osią pytania:
  - Mocne „Badania pokazują” dotyczy serii do upadku (Schoenfeld 2017, Morton 2016), a nie „blisko upadku”.
  - Dla lekkiego oporu (pompki przy ok. 30 możliwych powtórzeniach) upadek wydaje się mieć większe znaczenie (Lasevicius 2022).
  - Recepta RIR 1-3 przy takim oporze to nieprzetestowana ekstrapolacja przedstawiona jako wynik badań.
  - Zapas w seriach powyżej ok. 12 powtórzeń ocenia się mniej trafnie (Halperin 2022). Osoba celująca w „3 w zapasie” może realnie kończyć 5-8 powtórzeń przed upadkiem.
  - „27-29 w każdej serii” pomija spadek maksimum w kolejnych seriach.
  - Pompki (masa ciała) nie są objęte źródłami w bazie. Istnieją badania porównujące pompki z wyciskaniem [WIEDZA: np. Kikuchi i Nakazato 2017; Calatayud i in. 2015 – do potwierdzenia], ale nie są podpięte.

  Klucz B pozostaje najlepszą opcją, bo A, C i D są wyraźnie gorsze. Problem dotyczy precyzji recepty i opisu dowodów.
- **PROPONOWANA KOREKTA:** B.text: „Kończyć każdą serię bardzo blisko upadku, w pierwszej serii nawet przy ok. 28-30 pompkach”. W1.simple: „Badania, w których serie kończono na upadku, pokazują, że lżejszy opór buduje mięśnie podobnie jak duży ciężar. Przy lekkim oporze seria powinna więc kończyć się bardzo blisko upadku (0-2 powtórzenia w zapasie).” W2: jak w P06 oraz „w kolejnych seriach powtórzeń będzie mniej – liczy się zapas, nie stała liczba”. Rozważyć dodanie źródła o pompkach. Analogicznie w EN.
- **Pewność oceny:** wysoka (C-02, opis dowodów); umiarkowana (dokładny próg RIR dla lekkiego oporu nie jest znany)
- **Weryfikacja:** CLAIMS_AUDIT C-02; dossier G1 (Schoenfeld 2017 – kryteria [SEARCH]); EXTRA (Lasevicius 2022 [SEARCH]); SRC-0106; [WIEDZA] (pompki).

#### M1-04-P21 · MEDIUM · IT-M1-04-51 · pole `localizations.pl.main_feedback.depends` (analogicznie EN: „a few reps short”)
- **Claim / source:** CL-EFF-002 – dziedziczone C-05
- **OBECNIE:** „U zdrowych dorosłych serie kończone kilka powtórzeń przed upadkiem dają podobny albo nieco mniejszy przyrost niż serie do upadku, więc to po prostu fakt.”
- **PROBLEM:** Stem dotyczy zapasu 1-3 powtórzeń, a feedback rozszerza tezę na „kilka” powtórzeń, czyli to samo nadmierne uogólnienie co C-05 (patrz P08). Stanowczo sformułowane „to po prostu fakt” dla szerszego zakresu jest overclaimem.
- **PROPONOWANA KOREKTA:** „U zdrowych dorosłych serie kończone 1-3 powtórzenia przed upadkiem dają podobny albo nieco mniejszy przyrost niż serie do upadku, więc zdanie jest faktem.” Analogicznie w EN.
- **Pewność oceny:** wysoka
- **Weryfikacja:** CLAIMS_AUDIT C-05.

#### M1-04-P22 · LOW · IT-M1-04-51 · pole `localizations.pl.followup_texts.A.feedback` (analogicznie EN)
- **Claim / source:** CL-EFF-002 (applicability: różny staż); dowód niecytowany: Grgic 2022
- **OBECNIE:** „Badania obejmowały osoby o różnym stażu i nie wykazały, że bez upadku przyrost przestaje się pojawiać.”
- **PROBLEM:** Zdanie jest prawdziwe, ale obala tezę słabszą niż zawarta w opcji: opcja twierdzi, że zaawansowani „muszą” dochodzić do upadku, a feedback odpowiada, że przyrost nie ustaje. Pomija najbardziej istotny dowód dla tej opcji. W metaanalizie Grgic 2022 w podgrupie osób trenujących trening do upadku dał małą, istotną przewagę dla hipertrofii (ES 0,15; 95% CI 0,03-0,26 [SEARCH – streszczenie]). RCT u osób trenujących (Refalo 2024) wykazało natomiast podobną hipertrofię przy 0 i 1-2 RIR. Klucz „fakt” się nie zmienia („prawie tak samo” jest zgodne z ES 0,15), ale użytkownik nie dostaje rzetelnej informacji o tym moderatorze. Dodatkowo tylko ok. 2% uczestników syntez to osoby wysoko wytrenowane (Fry 2026, dossier G1).
- **PROPONOWANA KOREKTA:** „U osób trenujących przewaga upadku w metaanalizie była mała, a w badaniu z randomizacją zapas 1-2 powtórzeń dał podobny przyrost jak upadek. Upadek nie jest więc konieczny, choć u zaawansowanych może dawać niewielką dodatkową korzyść; osób wysoko wytrenowanych badano mało.” Dodać źródła do bazy. Analogicznie w EN.
- **Pewność oceny:** umiarkowana (wynik podgrupy z streszczenia wyszukiwarki; pełny tekst niedostępny)
- **Weryfikacja:** WebSearch Grgic 2022 [https://pubmed.ncbi.nlm.nih.gov/33497853/]; Refalo 2024 [https://www.tandfonline.com/doi/full/10.1080/02640414.2024.2321021]; dossier G1 (Fry 2026 [SEARCH]).

#### M1-04-P23 · LOW · IT-M1-04-51 · pola `localizations.pl.main_feedback.fact`, `w1.expert` (analogicznie EN)
- **Claim / source:** brak twierdzenia o zmęczeniu
- **OBECNIE:** fact: „…dają podobny albo tylko nieco mniejszy przyrost, a mniej męczą.” W1.expert: „Upadek w każdej serii mocniej męczy…”
- **PROBLEM:** Teza o zmęczeniu jest nieudokumentowana w bazie (jak w P03). Kierunek jest zgodny z literaturą [WIEDZA].
- **PROPONOWANA KOREKTA:** Podpiąć twierdzenie o kosztach zmęczeniowych albo pisać „zwykle mniej męczą”.
- **Pewność oceny:** umiarkowana
- **Weryfikacja:** przegląd claims; [WIEDZA].

#### M1-04-P24 · LOW · IT-M1-04-51 · pole `localizations.pl.w1.expert` (analogicznie EN)
- **Claim / source:** CL-EFF-001 (SRC-0105), CL-EFF-002 (SRC-0104)
- **OBECNIE:** „Metaanalizy wskazują, że hipertrofia rośnie wraz z bliskością upadku, ale różnica między upadkiem a zapasem 1-3 powtórzeń jest mała.”
- **PROBLEM:** Pierwsza część pochodzi z eksploracyjnej metaregresji z szacowanym RIR (Robinson 2024), a „wskazują” jest mocniejsze niż „sugerują” użyte w twierdzeniu. Druga część nie jest wynikiem żadnej metaanalizy. Refalo 2023 porównywała upadek z treningiem bez upadku o nieznanym zapasie, a porównanie 0 z 1-2 RIR pochodzi z pojedynczego RCT (Refalo 2024). Zakresu 3 RIR nie testowano wprost.
- **PROPONOWANA KOREKTA:** „Metaregresje (z szacowanym zapasem) sugerują, że hipertrofia rośnie wraz z bliskością upadku, a metaanaliza porównań z upadkiem i badanie z randomizacją u osób trenujących (0 vs 1-2 powtórzenia w zapasie) wskazują, że różnica między upadkiem a niewielkim zapasem jest mała.”
- **Pewność oceny:** wysoka
- **Weryfikacja:** SRC-0104, SRC-0105 (summary/limitations); WebSearch Refalo 2024.

#### M1-04-P25 · HIGH · IT-M1-04-61 · pola `localizations.pl.stem` (analogicznie EN), `correct`, `localizations.pl.main_feedback.myth`, `main_misconceptions`
- **Claim / source:** CL-EFF-001 (SRC-0105), CL-EFF-002 (SRC-0104)
- **OBECNIE:** stem: „Ktoś mówi: „Im bliżej upadku kończy się seria, tym większy przyrost, i dotyczy to tak samo masy mięśniowej, jak i siły.”” `correct: depends`; myth.feedback: „…Przy sile ta zależność jest dużo słabsza, dlatego trafna odpowiedź to „to zależy”.”; `main_misconceptions: { myth: MC-106, fact: MC-105 }`; `roles: [exam]`, `score_if_wrong_main: 0`, `confidence_allowed: false`.
- **PROBLEM:** Klucz jest niejednoznaczny, a odpowiedź „mit” jest co najmniej równie obronialna.
  - Zdanie zawiera wprost fałszywą koniunkcję: „tak samo” dla masy i siły, podczas gdy siła jest na bliskość upadku znacznie mniej wrażliwa (Robinson 2024; własny feedback „fact”: „Twierdzenie jest więc prawdziwe tylko w połowie”).
  - Część o hipertrofii („im bliżej, tym większy”) też jest tylko częściowo prawdziwa, bo zależność wypłaszcza się przy 0-3 RIR (C-27; SRC-0104: zależność może nie być liniowa), co pytanie samo przyznaje.
  - Konwencja stosowana w tej samej karcie każe zdanie fałszywe jako całość oceniać jako mit, mimo trafnego elementu: IT-M1-04-04 („Samo zdanie jest jednak mitem…”), IT-M1-04-11 („Zdanie jako całość to jednak mit…”), a w eksporcie także pytanie o trafność RIR („zależy od warunków… więc całe zdanie jest mitem”).
  - Użytkownik, który przyswoił tę konwencję, wybierze „mit” i w pytaniu egzaminacyjnym dostanie 0 pkt.
  - Diagnostyka jest błędna: wybór „mit” jest przypisany do MC-106 („liczy się tylko liczba serii”), choć może wynikać z poprawnego rozumowania.

  Odpowiedź „zależy” byłaby jednoznacznie poprawna dla zdania bez klauzuli „tak samo”.
- **PROPONOWANA KOREKTA:** Wariant zalecany: stem „Ktoś mówi: „Im bliżej upadku kończy się seria, tym większy przyrost.”” z kluczem „zależy” i follow-up A („czy celem jest masa mięśniowa, czy siła”). Feedback „zależy” powinien dodatkowo wspominać wypłaszczenie przy 0-3 RIR. Wariant alternatywny: zostawić stem i zmienić klucz na „mit”, z feedbackiem „Dla masy mięśniowej bliskość upadku ma znaczenie, ale dla siły znacznie mniejsze, więc zdanie, że dotyczy to obu tak samo, jest mitem”. W obu wariantach poprawić mapowanie `main_misconceptions`. Analogicznie w EN.
- **Pewność oceny:** umiarkowana-wysoka (merytoryka jest jednoznaczna; niejednoznaczność wynika z konwencji formatu, którą potwierdzają inne pytania)
- **Weryfikacja:** SRC-0105 (summary: siła podobna w szerokim zakresie RIR), SRC-0104 (nieliniowość); CLAIMS_AUDIT C-27; porównanie z IT-M1-04-04, IT-M1-04-11 oraz tekstem innego pytania myth_fact_depends w `weryfikacja_calosc.html`.

#### M1-04-P26 · MEDIUM · IT-M1-04-61 · pole `localizations.pl.w2` (analogicznie EN: „one of the most important variables”)
- **Claim / source:** CL-EFF-001 (SRC-0105, SRC-0104, SRC-0100)
- **OBECNIE:** „Bliskość upadku to jedna z najważniejszych zmiennych w treningu na masę mięśniową.”
- **PROBLEM:** Teza jest mocna i nieudokumentowana. ACSM 2026 (SRC-0100) wśród czynników zwiększających hipertrofię wymienia objętość (≥10 serii/grupę/tydz.) i trening ekscentryczny. Nie znalazło spójnego wpływu treningu do upadku i nie wymienia bliskości upadku. Dowód na zależność od RIR to eksploracyjna metaregresja z szacowanym RIR (pewność B/C wg audytu). Ranking ważności zmiennych nie ma oparcia w źródłach. Audyt C-27 zaznacza też, że rekomendacja „strongly_recommended” uzasadnia unikanie bardzo łatwych serii, a nie tezę o jednej z najważniejszych zmiennych.
- **PROPONOWANA KOREKTA:** „Bliskość upadku ma znaczenie dla przyrostu masy mięśniowej: serie przerwane z dużym zapasem powtórzeń dają prawdopodobnie wyraźnie mniejszy przyrost niż serie kończone blisko upadku.” Analogicznie w EN.
- **Pewność oceny:** wysoka
- **Weryfikacja:** dossier G1 (ACSM 2026 [SEARCH]); CLAIMS_AUDIT 0.3 (CL-EFF-001: B→B/C) i C-27.

#### M1-04-P27 · LOW · IT-M1-04-61 · pole `localizations.pl.w2` (analogicznie EN)
- **Claim / source:** brak
- **OBECNIE:** „Dlatego trening siłowy, np. przed zawodami w trójboju, często używa ciężkich serii z zapasem 2-4 powtórzeń.”
- **PROBLEM:** Zdanie opisuje praktykę trenerską bez źródła w bazie. „Dlatego” sugeruje, że praktyka wynika z dowodów. Zdanie poprzedzające (siła zależy od ciężaru i ćwiczenia ruchu) jest ostrożne („Prawdopodobnie”) i częściowo zgodne z CL-REPS-002.
- **PROPONOWANA KOREKTA:** „W praktyce trening siłowy, np. przed zawodami w trójboju, często używa ciężkich serii z zapasem ok. 2-4 powtórzeń (to praktyka trenerska, a nie wynik porównawczych badań).”
- **Pewność oceny:** umiarkowana
- **Weryfikacja:** przegląd claims; [WIEDZA].

### Karta pojęcia i błędne przekonania

#### M1-04-P28 · LOW · KC-M1-04 · pole `card.pl` (analogicznie `card.en`)
- **Claim / source:** CL-TENS-001 (SRC-0109) – nie obejmuje mechanizmu rekrutacji
- **OBECNIE:** „Blisko upadku pracuje prawdopodobnie coraz więcej włókien, także tych największych, więc bodziec jest silniejszy.”
- **PROBLEM:** Mechanizm nie jest udokumentowany w żadnym twierdzeniu (jak w P15). Sformułowanie jest ostrożne („prawdopodobnie”), ale „więc bodziec jest silniejszy” podaje wniosek z hipotezy jako fakt.
- **PROPONOWANA KOREKTA:** „Najczęstsze wyjaśnienie: blisko upadku pracuje coraz więcej włókien, także tych największych, więc bodziec jest prawdopodobnie silniejszy.” Dodać twierdzenie mechanistyczne (pewność C).
- **Pewność oceny:** umiarkowana
- **Weryfikacja:** CL-TENS-001; [WIEDZA].

#### M1-04-P29 · LOW · KC-M1-04 · pole `card.pl` (analogicznie `card.en`)
- **Claim / source:** CL-EFF-002 (C-05), CL-REPS-001 (C-02)
- **OBECNIE:** „zapas 1-3 powtórzeń daje podobny albo tylko nieco mniejszy przyrost, a mniej męczy.”
- **PROBLEM:** Zakres 1-3 jest poprawny, co zaznacza sam audyt C-05. Karta nie podaje jednak zastrzeżenia dla lekkich ciężarów i długich serii (Lasevicius 2022; Halperin 2022), a „a mniej męczy” nie ma źródła w bazie (jak w P03).
- **PROPONOWANA KOREKTA:** „…zapas 1-3 powtórzeń daje podobny albo tylko nieco mniejszy przyrost i zwykle mniej męczy. Przy lekkich ciężarach i bardzo długich seriach lepiej kończyć bliżej upadku.”
- **Pewność oceny:** umiarkowana
- **Weryfikacja:** CLAIMS_AUDIT C-02, C-05; EXTRA.

#### M1-04-P30 · LOW · KC-M1-04 · pole `card.pl` (analogicznie `card.en`)
- **Claim / source:** CL-RIR-001
- **OBECNIE:** „Upadek to moment, w którym mimo pełnego wysiłku nie da się zrobić kolejnego powtórzenia w dobrej technice.”
- **PROBLEM:** Karta łączy upadek techniczny z mięśniowym, a pytania IT-M1-04-01 (W1.expert, W2) rozdzielają te pojęcia (jak w P01).
- **PROPONOWANA KOREKTA:** „Upadek to moment, w którym mimo pełnego wysiłku nie da się ukończyć kolejnego powtórzenia. Zapas liczymy w powtórzeniach wykonanych w dobrej technice.”
- **Pewność oceny:** umiarkowana
- **Weryfikacja:** CL-RIR-001; SRC-0104.

#### M1-04-P31 · MEDIUM · MC-105 · pole `refutation.pl` (analogicznie `refutation.en`: „stopping a few reps short”)
- **Claim / source:** CL-EFF-002 – dziedziczone C-05
- **OBECNIE:** „Badania porównujące trening do upadku z kończeniem serii kilka powtórzeń wcześniej zwykle nie pokazują wyraźnej różnicy w przyroście mięśni.”
- **PROBLEM:** Ten sam problem co w P08 i P18: „kilka” jest szersze niż dane, a zapasu w grupach bez upadku zwykle nie mierzono. Stoi to też w sprzeczności z MC-106 i CL-VOL-003 (duży zapas = słabszy bodziec).
- **PROPONOWANA KOREKTA:** „Badania porównujące trening do upadku z kończeniem serii przed upadkiem zwykle nie pokazują wyraźnej różnicy w przyroście mięśni, a przy zapasie 1-2 powtórzeń przyrost był podobny.” Dalsza część bez zmian.
- **Pewność oceny:** wysoka
- **Weryfikacja:** CLAIMS_AUDIT C-05; SRC-0104.

#### M1-04-P32 · LOW · MC-106 · pole `refutation.pl` (analogicznie `refutation.en`)
- **Claim / source:** CL-EFF-001 – dziedziczone C-27
- **OBECNIE:** „Seria buduje mięśnie tym skuteczniej, im bliżej upadku się kończy.”
- **PROBLEM:** Zależność jest podana jako monotoniczna, bez przypisania do metaregresji i bez zastrzeżenia o wypłaszczeniu przy 0-3 RIR (C-27; SRC-0104: zależność może nie być liniowa). Dalsza część, o serii z dużym zapasem, jest poprawna i ostrożna.
- **PROPONOWANA KOREKTA:** „Seria buduje mięśnie zwykle skuteczniej, gdy kończy się blisko upadku, niż gdy zostaje duży zapas.”
- **Pewność oceny:** umiarkowana
- **Weryfikacja:** CLAIMS_AUDIT C-27; SRC-0104.

MC-107 i MC-630: brak istotnych problemów. Refutacja MC-107 zgadza się z Halperin 2022, a MC-630 ma poprawny przekaz („ciężar ma większe znaczenie dla siły maksymalnej”, zgodnie z CL-REPS-002).

### Uwagi informacyjne (bez severity)
- PL/EN: nie stwierdzono zmian znaczenia, które zmieniałyby siłę tezy, liczby lub klucz. Drobna różnica siły języka: IT-M1-04-01 W1.expert PL „Metaregresje wskazują” / EN „suggest”; CL-EFF-001 ma „sugerują”.
- Klucze scenariuszy IT-M1-04-05 i IT-M1-04-06 (Ola > Kasia) mają lepsze wsparcie, niż podaje treść. Lasevicius 2022 wprost pokazało mniejszy przyrost przy lekkim ciężarze przerwanym daleko od upadku i brak straty przy ciężkim ciężarze przerwanym przed upadkiem. Warto dodać to źródło do bazy.
- Metadane twierdzeń są niekompletne. IT-M1-04-08, 09 i 10 opierają klucz na treści CL-EFF-002, a 07 i 09 na treści CL-REPS-001, ale tych twierdzeń nie mają przypiętych. Przy przyszłej rewizji twierdzeń (C-02, C-05) ta zależność nie zostanie wykryta automatycznie.
- Bezpieczeństwo: treści o upadku w ciężkich ćwiczeniach ze sztangą (04, 08, 51) zalecają ostrożność i asekurację. Nie stwierdzono treści mogących prowadzić do szkody.
- Numeryczne IT-M1-04-02: przy `input_range` [0, 30] i partial {0} feedback `below` nigdy się nie wyświetli. To kwestia techniczna, nie merytoryczna.

### Podsumowanie partii
- Pytania: PASS 1, PASS WITH NOTES 1, REVISION REQUIRED 10, FAIL 1, UNVERIFIED 0 (razem 13)
- Problemy (tylko w pytaniach): CRITICAL 0, HIGH 1, MEDIUM 13, LOW 13
- Problemy w karcie/MC (osobno): CRITICAL 0, HIGH 0, MEDIUM 1, LOW 4
- Ostatnie ID w partii: IT-M1-04-61
