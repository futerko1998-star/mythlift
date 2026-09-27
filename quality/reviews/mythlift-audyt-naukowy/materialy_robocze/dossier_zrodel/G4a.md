# G4a – weryfikacja źródeł: żywienie (energia, białko)

Zakres: SRC-0406/SRC-0504 (Murphy & Koehler 2022), SRC-0407/SRC-0500 (Morton 2018), SRC-0501 (Jäger 2017), SRC-0502 (Schoenfeld 2013), SRC-0503 (Trommelen 2023), SRC-0505 (Slater 2019), SRC-0506 (Longland 2016).
Twierdzenia przeczytane: CL-PLAT-001, CL-PLAT-003, CL-ENRG-001, CL-ENRG-002, CL-ENRG-003, CL-PROT-001, CL-PROT-002, CL-PROT-003, CL-PROT-004.

**Ograniczenia tej weryfikacji (uczciwie):**
- WebFetch zablokowany (sprawdzone: pubmed.ncbi.nlm.nih.gov → EGRESS_BLOCKED; curl do eutils.ncbi → 403). Brak dostępu do pełnych tekstów, tabel i suplementów.
- WebSearch: wykonano 34 zapytania; przy 35. wyczerpał się sesyjny limit wyszukiwań (200/200, limit wspólny dla sesji). W efekcie **Slater 2019 zweryfikowano tylko bibliograficznie i częściowo co do treści abstraktu, a Longland 2016 nie został sprawdzony w wyszukiwarce ani razu** – wszystkie informacje o nim mają tag [WIEDZA] lub [NIEZWERYFIKOWANE].
- Tag [SEARCH] oznacza treść widoczną w wynikach/streszczeniach wyszukiwarki (często generowanych automatycznie na podstawie stron). Nie jest to weryfikacja pełnego tekstu. Tam, gdzie wartość pochodziła z jednego streszczenia (np. blogu) i nie udało się jej potwierdzić drugim zapytaniem, zaznaczono to osobno.
- Nie wykonano dedykowanych zapytań „retraction” dla każdej publikacji (poza zapytaniem o korektę Morton 2018). Status „brak retrakcji” oznacza jedynie brak sygnałów w uzyskanych wynikach.

---

### Murphy & Koehler 2022 – Energy deficiency impairs RT gains in lean mass but not strength (SRC-0406, SRC-0504)

- **Bibliografia:**
  - Autorzy (Murphy C, Koehler K): POTWIERDZONE [SEARCH onlinelibrary.wiley.com/doi/10.1111/sms.14075; semanticscholar].
  - Tytuł: POTWIERDZONE [SEARCH jw.].
  - Czasopismo, rok, tom(zeszyt):strony – Scand J Med Sci Sports 2022;32(1):125-137: POTWIERDZONE [SEARCH – streszczenie wyszukiwarki podało 2022 Jan;32(1):125-137]. Uwaga: PDF z repozytorium TUM ma nagłówek „2021;00:1–13” (wersja early view z 2021 r.) [SEARCH mediatum.ub.tum.de/doc/1632530/1632530.pdf] – to nie jest rozbieżność.
  - DOI 10.1111/sms.14075: POTWIERDZONE [SEARCH URL Wiley].
  - PMID 34623696: NIEZWERYFIKOWANE (nie pojawił się w wynikach; próba WebFetch zablokowana). [WIEDZA] wartość wiarygodna, ale niepotwierdzona.
  - Oba rekordy (SRC-0406 i SRC-0504) mają identyczne dane bibliograficzne; to duplikat tej samej publikacji.
- **Status (retrakcja/korekta):** BRAK ZNALEZIONYCH sygnałów w wynikach; dedykowanego zapytania o retrakcję nie wykonano → formalnie NIEZWERYFIKOWANE.
- **Dostęp do pełnego tekstu:** brak (WebFetch zablokowany); poziom weryfikacji: CZĘŚCIOWA (abstrakt i streszczenia wyszukiwarki).
- **Rzeczywisty projekt i wyniki:**
  - Typ: przegląd systematyczny z metaanalizą i metaregresją; przeszukano PubMed i SPORTDiscus pod kątem RCT z treningiem oporowym (RT) w deficycie energii (ED) trwającym ≥3 tygodnie [SEARCH wiley / sci-sport / examine].
  - Dwie ścieżki analizy: Analiza A – badania z równoległą grupą RT bez deficytu (RT+CON), metaanaliza porównawcza; Analiza B – badania bez grupy RT+CON, zestawiane z osobnymi badaniami RT+CON dopasowanymi pod względem uczestników i interwencji [SEARCH strongerbyscience.com/muscle-caloric-deficit; wiley].
  - Liczba badań: Analiza A – 7 badań dla masy beztłuszczowej (LM) i 5 dla siły; łącznie ok. 31 badań RT+ED spełniających kryteria; 1213 uczestników w 57 grupach, średni wiek 51 ± 16 lat [SEARCH – jedno automatyczne streszczenie wyszukiwarki, nie potwierdzone drugim zapytaniem; traktować jako wstępne].
  - Wyniki Analizy A: przyrost LM gorszy w RT+ED vs RT+CON (ES = −0,57; p = 0,02); przyrost siły bez istotnej różnicy (ES = −0,31; p = 0,28) [SEARCH wiley/semanticscholar – wartości z abstraktu].
  - Wyniki Analizy B: LM w RT+ED ES = −0,11 (p = 0,03), w RT+CON ES = 0,20 (p < 0,001); siła RT+ED ES = 0,84 vs RT+CON ES = 0,81 [SEARCH jw.]. Czyli w badaniach z deficytem LM średnio lekko spadała.
  - Metaregresja: deficyt ok. 500 kcal/d odpowiadał średnio brakowi zmiany LM (punkt zerowy linii regresji) [SEARCH]. Wniosek autorów: osoby budujące LM powinny unikać długotrwałego deficytu, a osoby chcące zachować LM przy redukcji – deficytów > 500 kcal/d [SEARCH].
  - Metoda pomiaru LM: różne metody (DXA, BIA, densytometria itd.) – dokładna lista NIEZWERYFIKOWANA. LM/FFM nie jest bezpośrednim pomiarem mięśni (obejmuje wodę, glikogen, narządy) – to ograniczenie wynikające z definicji [WIEDZA].
  - Wielkość deficytu w badaniach była w dużej mierze szacowana (x w metaregresji to „estimated energy deficit” – taki podpis figury widoczny w wynikach) [SEARCH researchgate figure].
  - Heterogeniczność (I²), CI dla ES: NIEZWERYFIKOWANE.
- **Rozbieżności z opisem Mythlift:**
  - SRC-0406 population („porównane z treningiem bez deficytu”) sugeruje, że wszystkie badania miały kontrolę bez deficytu; w rzeczywistości tylko Analiza A (ok. 7 badań LM) miała równoległą grupę kontrolną [SEARCH]. SRC-0504 poprawnie to opisuje w limitations. Severity: LOW (SRC-0406 do ujednolicenia z SRC-0504).
  - Populacja: Mythlift pisze ogólnie „dorośli”; wg streszczenia wyszukiwarki średni wiek wynosił ok. 51 lat, a badania w deficycie to w dużej części interwencje odchudzające. Mythlift nie sygnalizuje, że próg 500 kcal pochodzi głównie od osób w średnim/starszym wieku, często z nadwagą, zwykle nietrenujących. Severity: MEDIUM (applicability dla młodych, szczupłych trenujących) – do potwierdzenia w pełnym tekście.
  - „Przyrost siły podobny” (summary PL/EN obu rekordów): w Analizie A różnica była nieistotna (ES −0,31, p = 0,28, tylko ok. 5 badań) – punktowo na niekorzyść deficytu. Brak istotnej różnicy przedstawiono jako podobieństwo. Analiza B (0,84 vs 0,81) wspiera podobieństwo opisowo. Severity: LOW. Sformułowanie „w mniejszym stopniu” (jak w CL-PLAT-003) jest trafniejsze.
  - Tytuł/abstrakt mówi o LM; Mythlift w obu rekordach konsekwentnie używa „beztłuszczowa masa ciała” i zaznacza, że to pośrednia miara – poprawnie.
  - Rekordy są duplikatami (SRC-0406 vs SRC-0504) z nieco różnymi limitations. Rekomendacja: scalić, zachować limitations z SRC-0504 plus uwagę o wieku/populacji.
- **Liczby w twierdzeniach:**
  - CL-ENRG-001: „ok. 500 kcal (ok. 2100 kJ) dziennie średnio uniemożliwiał przyrost LM” → ZGODNE [SEARCH] (500 kcal = 2092 kJ, przeliczenie poprawne). „≥3 tygodnie” → ZGODNE [SEARCH]. „badania z randomizacją” → ZGODNE (kryterium wyszukiwania) [SEARCH].
  - CL-ENRG-003: „przy deficycie ok. 500 kcal dziennie przyrost przeciętnie zanika” → ZGODNE [SEARCH].
  - CL-PLAT-003: „deficyt rzędu 500 kcal dziennie wystarczał, żeby go średnio zatrzymać” → ZGODNE [SEARCH].
  - CL-PLAT-001: brak liczb z tego źródła.
- **Wstępna ocena wsparcia dla twierdzeń:**
  - CL-ENRG-001 (supports) → DIRECT dla kierunku efektu i progu grupowego; PARTIAL dla sformułowania „strength gains are largely preserved” (nieistotność przy małej liczbie badań). Wymaga dopisania w applicability, że próba to głównie osoby w średnim wieku i odchudzające się.
  - CL-PLAT-003 (supports) → DIRECT dla części o deficycie (LM, nie „masa mięśniowa” – ostatnie zdanie twierdzenia przechodzi na „masa mięśniowa przestała rosnąć”; LOW).
  - CL-PLAT-001 (context) → INDIRECT; wspiera tylko to, że energia jest możliwym czynnikiem ograniczającym, a nie kolejność diagnostyki (Mythlift sam to przyznaje).
  - CL-ENRG-003 (context) → PARTIAL/poprawny kontekst („ziarno prawdy”). Warto wyjaśnić pozorną sprzeczność: Longland przy deficycie ok. 40% (znacznie > 500 kcal) uzyskał przyrost LM – próg z metaregresji to średnia międzybadaniowa, a nie granica fizjologiczna.
- **Aktualność / nowsze dowody:**
  - Nie znaleziono (w ramach dostępnych wyszukiwań) nowszej metaanalizy, która zmieniałaby wniosek. Przeglądy popularnonaukowe (Stronger by Science) interpretują wynik podobnie, podkreślając zależność od poziomu tkanki tłuszczowej i stażu [SEARCH strongerbyscience.com/muscle-caloric-deficit].
  - [WIEDZA] Murphy & Koehler 2020 (Eur J Appl Physiol) – restrykcja kaloryczna indukuje oporność anaboliczną na trening (dane mechanistyczne, zgodne kierunkowo). [WIEDZA] Areta i wsp. 2014 – 5 dni niskiej dostępności energii obniża MPS. [WIEDZA] Barakat i wsp. 2020 (Strength Cond J) – przegląd rekompozycji u trenujących: jednoczesna utrata tłuszczu i przyrost LM możliwy, ale mniej prawdopodobny u szczupłych i zaawansowanych.
  - Pojawił się też tytuł w SCJ o wpływie białka na FFM w deficycie energii [SEARCH journals.lww.com/nsca-scj/fulltext/9900/effect_of_dietary_protein_on_fat_free_mass_in.179.aspx – widoczny tylko tytuł, treść NIEZWERYFIKOWANA].
- **Pole type:** meta_analysis – poprawne.
- **Odnośniki użyte:**
  - https://onlinelibrary.wiley.com/doi/10.1111/sms.14075
  - https://www.semanticscholar.org/paper/Energy-deficiency-impairs-resistance-training-gains-Murphy-Koehler/f37d1a5308ed25158e24a6b165c35c04b8f67370
  - https://mediatum.ub.tum.de/doc/1632530/1632530.pdf
  - https://www.researchgate.net/figure/Relationship-between-estimated-energy-deficit-and-change-in-lean-mass-The-shaded-area-on_fig4_355179847
  - https://examine.com/research-feed/study/9KGMB9/
  - https://sci-sport.com/en/impact-of-energy-deficiency-on-resistance-training-gains/
  - https://www.strongerbyscience.com/muscle-caloric-deficit/

---

### Morton et al. 2018 – Protein supplementation and RT gains: SR, MA, meta-regression (SRC-0407, SRC-0500)

- **Bibliografia:**
  - Autorzy: pierwszych trzech (Morton RW, Murphy KT, McKellar SR) POTWIERDZONE [SEARCH scinergy/nutrient-metrics]; pełna lista 11 autorów zgodna z [WIEDZA], w tej sesji NIEZWERYFIKOWANA w całości.
  - Tytuł: POTWIERDZONE [SEARCH pubmed 28698222].
  - Czasopismo/rok: Br J Sports Med 2018 – POTWIERDZONE [SEARCH]. Tom/zeszyt/strony 52(6):376-384 – NIEZWERYFIKOWANE wprost (URL Ovid „201803150” wskazuje na zeszyt z 15.03.2018, co jest spójne) [WIEDZA: zgodne].
  - DOI 10.1136/bjsports-2017-097608: NIEZWERYFIKOWANE w wynikach ([WIEDZA]: zgodne).
  - PMID 28698222: POTWIERDZONE [SEARCH https://pubmed.ncbi.nlm.nih.gov/28698222/].
  - PMC5867436: POTWIERDZONE [SEARCH URL pmc.ncbi.nlm.nih.gov/articles/PMC5867436/ w wynikach].
  - Oba rekordy – identyczne dane bibliograficzne (duplikat).
- **Status (retrakcja/korekta):** ZNALEZIONO korektę: Correction, PubMed 32943392 [SEARCH https://pubmed.ncbi.nlm.nih.gov/32943392/]. Treść korekty NIEZWERYFIKOWANA (Mythlift SRC-0500 twierdzi, że dotyczy konfliktu interesów – wiarygodne, ale nie potwierdzone). Brak sygnałów retrakcji. Krytyka metodologiczna (niżej): szeroki CI i słaba identyfikowalność punktu przegięcia [SEARCH strongerbyscience.com/protein-science].
- **Dostęp do pełnego tekstu:** brak; poziom weryfikacji: CZĘŚCIOWA (abstrakt + streszczenia).
- **Rzeczywisty projekt i wyniki:**
  - SR/MA/metaregresja RCT z RT + suplementacja białka vs kontrola u zdrowych dorosłych; 49 badań, 1863 uczestników [SEARCH]. Minimalny czas RT ≥6 tygodni – [WIEDZA], NIEZWERYFIKOWANE w sesji.
  - Efekty suplementacji (średnia, 95% CI): 1RM +2,49 kg (0,64–4,33); FFM +0,30 kg (0,09–0,52); CSA włókien +310 µm² (51–570); CSA uda (mid-femur) +7,2 mm² (0,20–14,30) [SEARCH – wartości z abstraktu].
  - Moderatory: efekt na FFM malał z wiekiem (−0,01 kg/rok; −0,02 do −0,00; p = 0,002); większy u osób wytrenowanych oporowo (0,75 kg; 0,09–1,40; p = 0,03) [SEARCH].
  - Punkt przegięcia (segmentowa regresja FFM vs całkowite spożycie białka): 1,62 g/kg/d, 95% CI 1,03–2,20 [SEARCH]. Według jednego streszczenia analiza objęła 42 ramiona badań i 723 uczestników przy spożyciu 0,9–2,4 g/kg/d [SEARCH – pojedyncze streszczenie, niepewne].
  - Punkt przegięcia dotyczy **wyłącznie FFM** (nie CSA ani siły) [SEARCH – abstrakt mówi o dalszym braku przyrostów FFM].
  - Krytyka: przedział wiarygodnych wartości punktu przegięcia obejmuje prawie cały zakres badanych spożyć, a sam punkt przegięcia opisano jako nieistotny statystycznie [SEARCH strongerbyscience.com/protein-science]; spożycie często z samoopisu; różne metody składu ciała (DXA, BIA, ważenie hydrostatyczne); krótkie badania, zwykle 8–16 tygodni [SEARCH – blogi/streszczenia, średnia pewność].
  - FFM nie jest miarą mięśni; część wyników (CSA włókien, CSA uda) to bezpośrednie miary mięśni, ale były to mniejsze podzbiory [WIEDZA/SEARCH].
- **Rozbieżności z opisem Mythlift:**
  - SRC-0407 summary: górna granica CI (ok. 2,2 g/kg) „sugeruje, że części osób może służyć nieco więcej”. To błędna interpretacja statystyczna: 95% CI punktu przegięcia opisuje niepewność co do **średniego** punktu w populacji, a nie zmienność międzyosobniczą. Ten sam błąd powtarzają SRC-0500 (limitations), CL-PROT-003 i CL-PLAT-003. Praktyczny wniosek (rozważyć do ok. 2,2 g/kg) jest bliski temu, co sugerują autorzy [WIEDZA: autorzy wskazują ok. 2,2 g/kg jako ostrożną górną wartość], ale uzasadnienie jest nieprawidłowe. Severity: MEDIUM.
  - SRC-0407 limitations nie zawierają zastrzeżenia, że FFM ≠ mięśnie (SRC-0500 je zawiera). Severity: LOW (do scalenia).
  - SRC-0500 limitations: „Analizowano dodatek białka, a nie całą dietę” – częściowo sprzeczne z summary; główna MA dotyczy suplementacji, ale punkt przegięcia liczono względem **całkowitego** spożycia (dieta + suplement). Severity: LOW.
  - SRC-0500 summary: „przestawał być widoczny” – poprawnie ostrożne. Jednak precyzja „1,6 g/kg jako próg” jest większa, niż pozwalają dane (CI 1,03–2,20; wątpliwa istotność punktu przegięcia) – patrz CL-PROT-003. Severity: MEDIUM.
  - SRC-0500 COI (korekta 2020, rada doradcza producenta suplementów): NIEZWERYFIKOWANE co do treści.
  - Liczby 49/1863, 0,3 kg (≈0,66 lb, „ok. 0,7 lb” – poprawne), wiek i status treningowy – zgodne.
- **Liczby w twierdzeniach:**
  - CL-PROT-003: 49 RCT → ZGODNE [SEARCH]; 1863 osoby → ZGODNE [SEARCH]; ok. 1,6 g/kg/d → ZGODNE (1,62) [SEARCH]; ok. 0,7 g/lb → ZGODNE (1,6/2,2046 = 0,73); ok. 2,2 g/kg → ZGODNE jako górna granica CI (2,20) [SEARCH], ale interpretacja „some people may benefit” → NIEZGODNA z sensem statystycznym CI; ok. 1,0 g/lb → ZGODNE (przeliczenie); „co najmniej 6 tygodni” → NIEZWERYFIKOWANE ([WIEDZA] prawdopodobnie zgodne); „częściej mężczyzn” → NIEZWERYFIKOWANE.
  - CL-PLAT-003: 1,6 g/kg, 0,7 g/lb, 2,2 g/kg, 1 g/lb → jak wyżej (liczby ZGODNE, interpretacja 2,2 jako „część osób” – NIEZGODNA). „Próg białka pochodzi głównie z badań na młodszych dorosłych” → NIEZWERYFIKOWANE (jedno streszczenie mówi o „młodych i starszych” uczestnikach analizy punktu przegięcia).
- **Wstępna ocena wsparcia dla twierdzeń:**
  - CL-PROT-003 (SRC-0500 supports) → PARTIAL. Kierunek efektu (białko zwiększa przyrost FFM i siły, efekt mały) – DIRECT. Kształt zależności z wyraźnym plateau przy 1,6 g/kg i rekomendacja „strongly_recommended” przy tak niepewnym punkcie przegięcia – nadmierna precyzja. Wniosek dotyczy FFM, co twierdzenie poprawnie nazywa „masą beztłuszczową”.
  - CL-PLAT-003 (SRC-0407 supports) → PARTIAL (jak wyżej, dodatkowo ostatnie zdanie mówi o „masie mięśniowej”, a dane dotyczą FFM).
- **Aktualność / nowsze dowody:**
  - Nunes i wsp. 2022, J Cachexia Sarcopenia Muscle 13(2):795-810 [SEARCH onlinelibrary.wiley.com/doi/10.1002/jcsm.12922; PMC8978023]: 74 RCT; u osób z RT zwiększanie spożycia białka zwiększa przyrost LBM (SMD 0,22; 95% CI 0,14–0,30; 62 badania). Podgrupy: <1,2 g/kg – brak efektu; 1,2–1,59 g/kg – g = 0,17; ≥1,6 g/kg – g = 0,30. U osób ≥65 lat efekt istotny już przy 1,2–1,59 g/kg, u <65 lat przy ≥1,6 g/kg. Analiza ciągła: efekt istotny, ale marginalny (SMD 0,14; 0,00–0,27) [SEARCH]. Wskazuje raczej na zależność stopniową niż ostry próg. Do Nunes 2022 opublikowano komentarz i odpowiedź autorów w 2025 r. [SEARCH PMID 40716105; PMC12677926; PMC12547074] – treść NIEZWERYFIKOWANA.
  - Tagawa i wsp. 2021, Nutr Rev 79(1):66-75 [SEARCH academic.oup.com/nutritionreviews/article/79/1/66/5936522]: model spline; LBM rośnie już przy ok. 5 g/d dodatkowego białka, a efekt dalej rośnie przy >50 g/d dodatkowego białka [SEARCH].
  - Stronger by Science, „Protein Science Updated” [SEARCH strongerbyscience.com/protein-science/]: argumentuje za odejściem od sztywnej reguły 1,6–2,2 g/kg na rzecz zależności malejących korzyści.
  - Wniosek: zakres 1,6–2,2 g/kg pozostaje rozsądną praktyką, ale sformułowanie „powyżej 1,6 średnio nie widać korzyści” jest zbyt pewne. Nowsze MA nie potwierdzają ostrego plateau. Sugerowana severity dla CL-PROT-003: MEDIUM (nadmierna precyzja, mocna rekomendacja).
- **Pole type:** meta_analysis – poprawne.
- **Odnośniki użyte:**
  - https://pubmed.ncbi.nlm.nih.gov/28698222/
  - https://pubmed.ncbi.nlm.nih.gov/32943392/
  - https://pmc.ncbi.nlm.nih.gov/articles/PMC5867436/
  - https://www.ovid.com/00002412-201803150-00009
  - https://www.scinergy.io/learn/how-much-protein-for-muscle-gain
  - https://nutrient-metrics.com/en/evidence/morton-2018-protein-meta-analysis/
  - https://www.strongerbyscience.com/protein-science/
  - https://onlinelibrary.wiley.com/doi/10.1002/jcsm.12922
  - https://pmc.ncbi.nlm.nih.gov/articles/PMC8978023/
  - https://pubmed.ncbi.nlm.nih.gov/40716105
  - https://academic.oup.com/nutritionreviews/article/79/1/66/5936522

---

### Jäger et al. 2017 – ISSN Position Stand: protein and exercise (SRC-0501)

- **Bibliografia:**
  - Autorzy (22 osoby, od Jäger R do Antonio J): POTWIERDZONE – lista w wynikach wyszukiwania identyczna z Mythlift [SEARCH].
  - Tytuł: POTWIERDZONE [SEARCH].
  - Czasopismo/rok: J Int Soc Sports Nutr 2017, publikacja 20.06.2017 – POTWIERDZONE [SEARCH].
  - Tom:artykuł 14:20 – NIEZWERYFIKOWANE wprost ([WIEDZA]: zgodne).
  - DOI 10.1186/s12970-017-0177-8: POTWIERDZONE [SEARCH link.springer.com].
  - PMID 28642676: POTWIERDZONE [SEARCH pubmed.ncbi.nlm.nih.gov/28642676/; unboundmedicine].
  - PMC5477153: POTWIERDZONE [SEARCH].
- **Status (retrakcja/korekta):** BRAK ZNALEZIONYCH (bez dedykowanego zapytania). Czy ISSN wydało nowsze stanowisko o białku do 09.2026: NIEZWERYFIKOWANE (limit wyszukiwań).
- **Dostęp do pełnego tekstu:** brak; poziom weryfikacji: CZĘŚCIOWA (punkty abstraktu widoczne w wynikach).
- **Rzeczywisty projekt i wyniki (kluczowe punkty stanowiska):**
  - Typ: stanowisko towarzystwa (przegląd ekspercki, nie systematyczny) [SEARCH].
  - Łączne dzienne spożycie 1,4–2,0 g/kg/d wystarcza większości ćwiczących do budowy i utrzymania masy mięśniowej [SEARCH].
  - Wyższe spożycie 2,3–3,1 g/kg/d może być potrzebne do maksymalnego zachowania masy beztłuszczowej u osób wytrenowanych oporowo w okresach hipokalorycznych [SEARCH]. Uwaga: w równoległym stanowisku ISSN o dietach i składzie ciała ten sam zakres podano jako 2,3–3,1 g/kg **FFM** u szczupłych, wytrenowanych osób [SEARCH stevenlow.org]; pierwotnym źródłem jest [WIEDZA] Helms i wsp. 2014 (g/kg FFM).
  - Porcja: 0,25 g/kg wysokiej jakości białka lub 20–40 g, aby zmaksymalizować MPS; 700–3000 mg leucyny; porcje najlepiej równo co 3–4 h [SEARCH].
  - Timing: wysiłek oporowy i białko działają synergistycznie, gdy białko spożywa się przed lub po treningu; optymalny moment to kwestia indywidualnej tolerancji; efekt anaboliczny wysiłku trwa co najmniej 24 h, ale prawdopodobnie słabnie wraz z upływem czasu od treningu [SEARCH].
  - Pełnowartościowa żywność może pokryć zapotrzebowanie; suplementacja jest praktycznym sposobem zapewnienia ilości i jakości [SEARCH].
- **Rozbieżności z opisem Mythlift:**
  - Summary: „Pora posiłku względem treningu ma drugorzędne znaczenie, bo zwiększona reakcja mięśni na białko po treningu utrzymuje się co najmniej dobę” – pominięto zastrzeżenie ISSN, że efekt prawdopodobnie słabnie z czasem, oraz to, że ISSN podkreśla synergię białka spożytego przed lub po treningu. „Drugorzędne znaczenie” to interpretacja Mythlift, a nie sformułowanie stanowiska. Severity: LOW.
  - „2,3–3,1 g/kg” bez jednostki odniesienia: w stanowisku o białku zapisano g/kg/d, ale podstawa (Helms 2014) i stanowisko ISSN o składzie ciała podają g/kg FFM u szczupłych wytrenowanych. W przeliczeniu na masę ciała wartości są niższe. Mythlift nie zaznacza, że dotyczy to szczupłych, wytrenowanych osób w deficycie. Severity: LOW (to kontekst, nie liczba w twierdzeniach).
  - „20–40 g … co 3–4 godziny”: ZGODNE; Mythlift poprawnie w limitations zaznacza, że opiera się to na krótkich badaniach MPS.
  - COI (współpraca części autorów z producentami suplementów): NIEZWERYFIKOWANE w sesji; [WIEDZA] stanowiska ISSN zwykle zawierają takie deklaracje – wiarygodne.
- **Liczby w twierdzeniach:**
  - CL-PROT-003: 1,4–2,0 g/kg → ZGODNE [SEARCH].
  - CL-PROT-002: 0,25 g/kg → ZGODNE; 20–40 g → ZGODNE; co 3–4 h → ZGODNE [SEARCH].
  - CL-PROT-001: „co najmniej dobę” → ZGODNE [SEARCH] (bez zastrzeżenia o słabnięciu efektu).
  - CL-PROT-004: „20–40 g” jako porcje proponowane przez ISSN → ZGODNE [SEARCH].
- **Wstępna ocena wsparcia dla twierdzeń:**
  - CL-PROT-001 (contradicts) → PARTIAL. ISSN podważa sztywne okno (efekt ≥24 h, moment zależny od tolerancji), ale nadal traktuje spożycie około treningu jako korzystne i mówi o słabnięciu efektu z czasem. To opinia ekspercka, nie nowe dane.
  - CL-PROT-002 (supports) → DIRECT dla wartości liczbowych zalecenia. Stwierdzenie „ma mniejsze znaczenie niż dzienna suma” to synteza Mythlift, nie teza ISSN (NIEZWERYFIKOWANE w stanowisku).
  - CL-PROT-003 (supports) → DIRECT dla zakresu 1,4–2,0 g/kg jako zalecenia eksperckiego.
  - CL-PROT-004 (context) → DIRECT jako kontekst (źródło popularnej porcji 20–40 g opartej na ostrych badaniach MPS).
- **Aktualność / nowsze dowody:** zakres 1,4–2,0 g/kg jest zgodny z Morton 2018 i Nunes 2022 [SEARCH]. Zalecenie równego rozkładu co 3–4 h osłabiają nowsze dane: Trommelen 2023 (większa porcja wykorzystywana dłużej) [SEARCH] i Askow i wsp. 2025 MSSE (9 dni, D2O, 40 osób: brak różnicy w dziennym MyoPS między rozkładem zrównoważonym a niezrównoważonym przy 1,1–1,2 g/kg/d) [SEARCH]. Nie ma to wpływu na klucz CL-PROT-002 (Mythlift już pisze, że rozkład to rozsądna opcja, ale nie warunek).
- **Pole type:** position_stand – poprawne.
- **Odnośniki użyte:**
  - https://pubmed.ncbi.nlm.nih.gov/28642676/
  - https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5477153/
  - https://link.springer.com/article/10.1186/s12970-017-0177-8
  - https://www.unboundmedicine.com/medline/citation/28642676/International_Society_of_Sports_Nutrition_Position_Stand:_protein_and_exercise_
  - https://www.tandfonline.com/doi/full/10.1186/s12970-017-0177-8
  - https://stevenlow.org/issn-position-statements-protein-and-exercise-diets-and-body-composition-safety-and-efficacy-of-creatine-supplementation-in-exercise-sport-and-medicine/
  - https://www.nutraingredients.com/Article/2017/06/21/ISSN-publishes-position-stand-on-protein-and-exercise/

---

### Schoenfeld, Aragon, Krieger 2013 – Protein timing meta-analysis (SRC-0502)

- **Bibliografia:**
  - Autorzy, tytuł: POTWIERDZONE [SEARCH].
  - Czasopismo/rok/artykuł: J Int Soc Sports Nutr 2013;10:53, publikacja 03.12.2013 – POTWIERDZONE [SEARCH]. Zeszyt „(1)” – bez znaczenia (czasopismo z numeracją artykułów).
  - DOI 10.1186/1550-2783-10-53: POTWIERDZONE [SEARCH tandfonline URL].
  - PMC3879660: POTWIERDZONE [SEARCH].
  - PMID 24299050: NIEZWERYFIKOWANE (nie pojawił się w wynikach; [WIEDZA] wiarygodny).
- **Status (retrakcja/korekta):** retrakcji nie znaleziono. ZNALEZIONO istotną krytykę: Beale DJ 2016, Evidence inconclusive – comment on article by Schoenfeld et al., JISSN (PMID 27777541; PMC5057468) [SEARCH]. Według komentarza 20 z 23 badań porównywało suplement białkowy z placebo bez wyrównania dziennego białka, a tylko 3 badania (77 osób) nadawały się do odpowiedzi na pytanie o timing [SEARCH]. Odpowiedź autorów (blog Aragona) [SEARCH lookgreatnaked.com] – treść NIEZWERYFIKOWANA.
- **Dostęp do pełnego tekstu:** brak; poziom weryfikacji: CZĘŚCIOWA.
- **Rzeczywisty projekt i wyniki:**
  - Metaanaliza/metaregresja (model wielopoziomowy). Hipertrofia: 525 osób, 132 ES w 47 grupach z 23 badań [SEARCH].
  - Siła: 20 badań / 478 osób (dane Mythlift) – NIEZWERYFIKOWANE.
  - Kryteria: grupa „timing” – białko w ciągu ok. 1 h przed lub po treningu; kontrola – ≥2 h od treningu [SEARCH – streszczenie ogólne]; szczegóły (np. minimalna dawka EAA, ≥6 tygodni) – [WIEDZA], NIEZWERYFIKOWANE.
  - Wyniki: w prostej analizie bez kowariantów mały do umiarkowanego efekt na hipertrofię i brak istotnego efektu na siłę; w pełnym modelu z kowariantami brak istotnych różnic dla siły i hipertrofii; całkowite spożycie białka było istotnym predyktorem wielkości efektu [SEARCH].
  - Definicja „trenujący” = ≥1 rok treningu oporowego [SEARCH]. Liczba takich badań (Mythlift: 4) – NIEZWERYFIKOWANE.
  - Miary hipertrofii: MRI, CT, USG, biopsja, DXA, ważenie hydrostatyczne [SEARCH] – mieszanka miar bezpośrednich i FFM/LBM.
- **Rozbieżności z opisem Mythlift:**
  - Summary i limitations są zasadniczo zgodne z abstraktem. Mythlift sam wskazuje brak wyrównania białka w wielu badaniach.
  - Nie wspomniano, że po wyłączeniu badań z niewyrównanym białkiem zostają tylko ok. 3 badania / 77 osób (Beale 2016). Wynik „po uwzględnieniu innych czynników różnica znikała” to statystyczna korekta danych z założenia skonfundowanych; brak istotnej różnicy ≠ dowód braku efektu. Severity: MEDIUM (dla siły dowodu, nie dla klucza mitu).
  - Liczby „20 badań (478 osób)” i „4 badania na trenujących” – NIEZWERYFIKOWANE; COI („grant producenta suplementów”) – NIEZWERYFIKOWANE.
- **Liczby w twierdzeniach:**
  - CL-PROT-001: „w ciągu godziny przed/po vs co najmniej 2 godziny” → ZGODNE [SEARCH]. „30–60 minut” (fraza mitu) – MA testowała okno ≤1 h, nie 30 min; akceptowalne przybliżenie. „co najmniej 6 tygodni” → NIEZWERYFIKOWANE. „tylko kilka badań dotyczyło osób trenujących co najmniej rok” → definicja ZGODNA [SEARCH], liczba NIEZWERYFIKOWANA.
- **Wstępna ocena wsparcia dla twierdzeń:**
  - CL-PROT-001 (contradicts) → PARTIAL. Wspiera odrzucenie sztywnego okna (efekt zanika po kontroli całkowitego białka), ale dane są skonfundowane i ubogie w badania z wyrównanym białkiem (Beale 2016). Obalenie mitu wzmacnia nowsza MA Casuso & Goossens 2025 (niżej). Etykieta „myth” jest uzasadniona, pewność B – do utrzymania raczej dzięki łącznemu obrazowi niż samej MA 2013.
- **Aktualność / nowsze dowody:**
  - Casuso RA, Goossens L. 2025, Nutrients 17(13):2070 (PMID 40647175; PMC12250900) [SEARCH]: tylko badania bezpośrednio porównujące białko przed vs po treningu (≥4 tyg.); 5 badań (6 raportów); brak efektu timingu, np. RM w wyciskaniu SMD 0,07 (95% CI −0,25 do 0,40; I² = 0%). Autorzy uznają wynik za zgodny z wcześniejszymi MA [SEARCH]. Uwaga: porównuje przed vs po, a nie po vs z dala od treningu.
  - [WIEDZA] Schoenfeld i wsp. 2017 (PeerJ): białko przed vs po treningu u wytrenowanych mężczyzn przez ok. 10 tygodni, bez różnic. Wirth i wsp. 2020 (J Nutr, SR/MA RCT): timing białka bez przekonujących dowodów. Oba NIEZWERYFIKOWANE w sesji.
  - Kierunek wniosku Mythlift pozostaje aktualny.
- **Pole type:** meta_analysis – poprawne.
- **Odnośniki użyte:**
  - https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3879660/
  - https://www.tandfonline.com/doi/full/10.1186/1550-2783-10-53
  - https://www.semanticscholar.org/paper/The-effect-of-protein-timing-on-muscle-strength-and-Schoenfeld-Aragon/b66aa37862172c86bb822d9095bb5f98012b5d10
  - https://pubmed.ncbi.nlm.nih.gov/27777541/
  - https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5057468/
  - https://jissn.biomedcentral.com/articles/10.1186/s12970-016-0148-5
  - https://www.lookgreatnaked.com/blog/our-meta-analysis-of-protein-timing-thoughts-and-perspectives/
  - https://pmc.ncbi.nlm.nih.gov/articles/PMC12250900/
  - https://pubmed.ncbi.nlm.nih.gov/40647175/

---

### Trommelen et al. 2023 – 100 g vs 25 g protein, no upper limit (SRC-0503)

- **Bibliografia:**
  - Tytuł: POTWIERDZONE [SEARCH].
  - Autorzy: Trommelen (pierwszy) i van Loon (senior) POTWIERDZONE [SEARCH]; pozostali 10 – NIEZWERYFIKOWANE ([WIEDZA]: lista wygląda wiarygodnie).
  - Czasopismo/rok: Cell Rep Med 2023, publikacja 19.12.2023 – POTWIERDZONE [SEARCH].
  - Tom(zeszyt):artykuł 4(12):101324 – spójne z DOI; tom/zeszyt NIEZWERYFIKOWANE wprost.
  - DOI 10.1016/j.xcrm.2023.101324: POTWIERDZONE [SEARCH].
  - PMC10772463: POTWIERDZONE [SEARCH].
  - PMID 38118410: NIEZWERYFIKOWANE.
- **Status (retrakcja/korekta):** retrakcji nie znaleziono. ZNALEZIONO komentarz krytyczny: Witard OC & Mettler S 2024, IJSNEM 34(5):322 [SEARCH journals.humankinetics.com; kclpure.kcl.ac.uk]. Komentatorzy ostrzegają, że praktyczne implikacje mogły zostać błędnie zinterpretowane jako odrzucenie znaczenia rozkładu białka na posiłki; wskazują, że badani byli rekreacyjnie aktywni, ale nie wytrenowani oporowo; zauważają, że wczesne dane nie przenoszą wniosku „braku górnej granicy” na wytrenowane młode kobiety [SEARCH].
- **Dostęp do pełnego tekstu:** brak; poziom weryfikacji: CZĘŚCIOWA.
- **Rzeczywisty projekt i wyniki:**
  - Randomizowane, podwójnie zaślepione, kontrolowane placebo badanie w grupach równoległych; 36 zdrowych, rekreacyjnie aktywnych młodych mężczyzn; 0 g (placebo), 25 g lub 100 g białka mleka znakowanego wewnętrznie, po jednej sesji treningu oporowego całego ciała [SEARCH]. Równy podział 12/12/12 – [WIEDZA], NIEZWERYFIKOWANE. Wiek 18–40 – NIEZWERYFIKOWANE.
  - Metoda: czterokrotne znakowanie izotopowe (feeding-infusion), krew i biopsje mięśnia w czasie [SEARCH].
  - Wyniki: 100 g dało większą i dłuższą (>12 h) odpowiedź anaboliczną niż 25 g. Miofibrylarny FSR większy o ok. 20% (0–4 h) i ok. 40% (4–12 h). Wyższy był też bilans netto białka całego ciała oraz synteza białek mieszanych mięśnia, miofibrylarnych, tkanki łącznej mięśnia i osocza. Spożycie białka miało znikomy wpływ na rozpad białek całego ciała i oksydację aminokwasów [SEARCH].
  - Outcome: wyłącznie ostry (12 h), mechanistyczny; brak pomiaru przyrostu mięśni.
- **Rozbieżności z opisem Mythlift:**
  - Opis (population, summary, limitations) jest zgodny z tym, co widać w wynikach. Limitations poprawnie zaznaczają ostry pomiar, tylko młodych mężczyzn i niepełny powrót do poziomu wyjściowego.
  - Brakuje zastrzeżenia, że badani **nie byli wytrenowani oporowo**, oraz wzmianki o komentarzu Witard & Mettler 2024 (ograniczona generalizacja, kobiety wytrenowane). Severity: LOW.
  - „36 … po 12 osób” i „18–40 lat” – NIEZWERYFIKOWANE (liczba 36 potwierdzona).
  - COI (pracownik firmy mleczarskiej) – NIEZWERYFIKOWANE.
- **Liczby w twierdzeniach:**
  - CL-PROT-004: 100 g vs 25 g → ZGODNE; „12 godzin” → ZGODNE; „znikomy wpływ na spalanie aminokwasów” → ZGODNE [SEARCH]. „20–30 g” (fraza mitu) – nie dotyczy źródła.
  - CL-PROT-002: „większa porcja też jest wykorzystywana, tylko dłużej” → ZGODNE [SEARCH].
- **Wstępna ocena wsparcia dla twierdzeń:**
  - CL-PROT-004 (contradicts) → DIRECT na poziomie mechanistycznym (teza mitu dotyczy wykorzystania białka z posiłku, a badanie pokazuje wbudowanie do białek mięśnia w 12 h). PARTIAL dla słów „do budowy mięśni”, bo nie mierzono hipertrofii. Mythlift zaznacza to w evidence_summary. Pewność B dla obalenia mitu jest do obrony, bo kierunek wspierają też wcześniejsze dane (np. Macnaughton i wsp. 2016: 40 g > 20 g whey po treningu całego ciała [SEARCH – tytuł w wynikach, PMC4985555]), ale opiera się głównie na jednym badaniu ostrym (36 osób).
  - CL-PROT-002 (context) → INDIRECT/PARTIAL; poprawnie użyte jako kontekst osłabiający sztywność zalecenia porcji.
- **Aktualność / nowsze dowody:** Witard & Mettler 2024 (komentarz, IJSNEM) [SEARCH]; Askow i wsp. 2025 (MSSE; 9 dni; rozkład zrównoważony vs niezrównoważony bez wpływu na dzienny MyoPS) [SEARCH] – spójne z Mythlift (rozkład mniej ważny niż suma). Brak długich RCT porównujących jeden duży i kilka małych posiłków z pomiarem hipertrofii (w wynikach nie znaleziono; NIEZWERYFIKOWANE).
- **Pole type:** rct – formalnie poprawne (randomizowane, zaślepione, placebo). Merytorycznie to badanie ostre, mechanistyczne (MPS/bilans białka w 12 h). Jeśli taksonomia Mythlift używa typu do ważenia siły dowodów, rozważyć „mechanistic” albo oznaczenie „acute”. Severity: LOW.
- **Odnośniki użyte:**
  - https://www.cell.com/cell-reports-medicine/fulltext/S2666-3791(23)00540-2
  - https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10772463/
  - https://www.sciencedirect.com/science/article/pii/S2666379123005402
  - https://journals.humankinetics.com/view/journals/ijsnem/34/5/article-p322.xml
  - https://kclpure.kcl.ac.uk/portal/en/publications/the-anabolic-response-to-protein-ingestion-during-recovery-from-e/
  - https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4985555/
  - https://www.ovid.com/jnls/acsm-msse/abstract/10.1249/mss.0000000000003725~impact-of-vegan-diets-on-resistance-exercisemediated?redirectionsource=fulltextview
  - https://news.illinois.edu/omnivorous-vegan-makes-no-difference-to-muscle-building-after-weight-training-study-finds/

---

### Slater et al. 2019 – Is an energy surplus required to maximize hypertrophy? (SRC-0505)

- **Bibliografia:**
  - Autorzy (Slater GJ, Dieter BP, Marsh DJ, Helms ER, Shaw G, Iraki J): POTWIERDZONE [SEARCH].
  - Tytuł: POTWIERDZONE [SEARCH].
  - Czasopismo/rok: Front Nutr 2019, publikacja 20.08.2019 – POTWIERDZONE [SEARCH].
  - Tom 6, art. 131: spójne z DOI (…00131); tom NIEZWERYFIKOWANY wprost.
  - DOI 10.3389/fnut.2019.00131: POTWIERDZONE [SEARCH frontiersin URL].
  - PMID 31482093: POTWIERDZONE [SEARCH pubmed.ncbi.nlm.nih.gov/31482093/].
  - PMC6710320: POTWIERDZONE [SEARCH].
- **Status (retrakcja/korekta):** BRAK ZNALEZIONYCH (bez dedykowanego zapytania).
- **Dostęp do pełnego tekstu:** brak; poziom weryfikacji: TYLKO BIBLIOGRAFIA + fragment abstraktu (limit wyszukiwań wyczerpany przed potwierdzeniem kluczowej liczby).
- **Rzeczywisty projekt i wyniki:**
  - Przegląd (review) omawiający, jak bardzo zwiększyć energię, skąd powinna pochodzić dodatkowa energia i kiedy ją spożywać; wskazuje luki w literaturze [SEARCH].
  - Abstrakt: podręcznikowe zalecenia opierają się na energii zmagazynowanej w tkance i prawdopodobnie pomijają inne kosztowne energetycznie procesy hipertrofii, ostre adaptacje metaboliczne na nadwyżkę oraz indywidualne różnice (staż, stan energetyczny) [SEARCH].
  - Stwierdzenie, że samo przejadanie nie wystarcza, aby przybierać proporcjonalnie więcej FFM niż FM, pojawiło się w streszczeniu wyszukiwarki [SEARCH – niepewne, czy pochodzi z artykułu czy z bloga].
  - **Rekomendacja ok. 1500–2000 kJ/d (ok. 360–480 kcal/d): NIEZWERYFIKOWANE.** Zapytanie weryfikujące nie zostało wykonane (limit). [WIEDZA – niska/umiarkowana pewność] wydaje się, że przegląd proponował ostrożną nadwyżkę tego rzędu z monitorowaniem składu ciała, ale nie mogę tego potwierdzić. Uwaga: w wynikach pojawiły się blogi przypisujące Slaterowi inne wartości (np. 50–200 kcal/d) – to najpewniej nadinterpretacje stron trzecich, nie treść artykułu [SEARCH hypertrophy.towerofrecords.com – niewiarygodne].
  - Wzmianka, że kilka dni niedoboru energii obniża MPS (używana w CL-ENRG-001): NIEZWERYFIKOWANE w przeglądzie; [WIEDZA] zgodne z Areta i wsp. 2014, które przegląd prawdopodobnie cytuje.
- **Rozbieżności z opisem Mythlift:**
  - Nie stwierdzono rozbieżności w części zweryfikowanej (abstrakt o ograniczeniach wyliczeń tkankowych – ZGODNE).
  - Kluczowa liczba 1500–2000 kJ/d – NIEZWERYFIKOWANA; ponieważ CL-ENRG-002 opiera się na niej w całości, to **priorytet ręcznej weryfikacji** (sprawdzić sekcję „How much should energy intake be increased” w pełnym tekście).
  - Przeliczenie 1500–2000 kJ = 358–478 kcal → „ok. 360–480 kcal” poprawne arytmetycznie.
- **Liczby w twierdzeniach:**
  - CL-ENRG-002: 1500–2000 kJ (360–480 kcal) → NIEZWERYFIKOWANE (arytmetyka poprawna). „Optymalnej wielkości u trenujących nie ustalono” → zgodne z charakterem przeglądu (luki w literaturze) [SEARCH – ogólnie]. „Większa nadwyżka dodaje więcej tłuszczu niż mięśni” → NIEZWERYFIKOWANE w źródle; kierunek wiarygodny ([WIEDZA] badania przekarmiania, Helms 2023).
  - CL-ENRG-001 (context): „kilka dni niedoboru obniża MPS” → NIEZWERYFIKOWANE (w przeglądzie).
- **Wstępna ocena wsparcia dla twierdzeń:**
  - CL-ENRG-002 (supports) → PARTIAL (przegląd narracyjny i opinia ekspercka; liczba niepotwierdzona). Certainty D i „reasonable” – adekwatne. Zdanie „larger surpluses add more fat than muscle” jest w statement podane kategorycznie, choć evidence_summary opiera je na badaniach przekarmiania u nietrenujących. Severity: MEDIUM – złagodzić do „prawdopodobnie” lub podać źródło bezpośrednie.
  - CL-ENRG-001 (context) → INDIRECT; poprawnie jako kontekst.
- **Aktualność / nowsze dowody:**
  - Helms i wsp. 2023, Sports Med Open – Effect of Small and Large Energy Surpluses on Strength, Muscle, and Skinfold Thickness in Resistance-Trained Individuals: A Parallel Groups Design [SEARCH – tytuł i URL link.springer.com/article/10.1186/s40798-023-00651-y]. [WIEDZA – umiarkowana pewność] 8 tygodni, osoby wytrenowane, mała (~5%) vs duża (~15%) nadwyżka: podobne przyrosty grubości mięśni (USG) i siły, tendencja do większego przyrostu fałdów skórnych przy dużej nadwyżce; mała próba. To bezpośrednie (choć małe) RCT u trenujących, które częściowo odpowiada na revision_trigger CL-ENRG-002 – warto dodać jako źródło.
  - [WIEDZA] Iraki i wsp. 2019 (Sports; przegląd żywienia kulturystów poza sezonem) – rekomendacje nadwyżki w % i tempa przyrostu masy; NIEZWERYFIKOWANE w sesji.
- **Pole type:** narrative_review – poprawne (przegląd bez systematycznego wyszukiwania i metaanalizy [SEARCH – opis jako review]).
- **Odnośniki użyte:**
  - https://pubmed.ncbi.nlm.nih.gov/31482093/
  - https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6710320/
  - https://pmc.ncbi.nlm.nih.gov/articles/PMC6710320/figure/F2/
  - https://www.frontiersin.org/articles/10.3389/fnut.2019.00131/full
  - https://www.frontiersin.org/journals/nutrition/articles/10.3389/fnut.2019.00131/pdf
  - https://link.springer.com/article/10.1186/s40798-023-00651-y
  - https://hypertrophy.towerofrecords.com/hypertrophy/caloric-surplus (źródło niewiarygodne – przykład błędnych przypisań)

---

### Longland et al. 2016 – Higher vs lower protein during energy deficit + intense exercise (SRC-0506)

**UWAGA: w tej sesji NIE wykonano żadnego wyszukiwania dla tej publikacji (wyczerpany limit). Wszystko poniżej to [WIEDZA] lub NIEZWERYFIKOWANE.**

- **Bibliografia:**
  - Autorzy (Longland TM, Oikawa SY, Mitchell CJ, Devries MC, Phillips SM), tytuł, Am J Clin Nutr 2016;103(3):738-746, DOI 10.3945/ajcn.115.119339, PMID 26817506 – [WIEDZA] zgodne z moją wiedzą (wysoka pewność co do autorów, tytułu, czasopisma, roku i tomu; umiarkowana co do stron i PMID). Status: NIEZWERYFIKOWANE w sesji.
- **Status (retrakcja/korekta):** NIEZWERYFIKOWANE ([WIEDZA] nie znam retrakcji ani istotnej korekty).
- **Dostęp do pełnego tekstu:** brak; poziom weryfikacji: NIEZWERYFIKOWANE (tylko wiedza).
- **Rzeczywisty projekt i wyniki ([WIEDZA]):**
  - RCT, 40 młodych mężczyzn (~20/grupa) [WIEDZA – wysoka pewność].
  - Populacja: [WIEDZA – umiarkowana pewność] mężczyźni z nadwagą, rekreacyjnie aktywni, bez regularnego treningu oporowego. Dokładne BMI i wiek – NIEZWERYFIKOWANE.
  - Interwencja: 4 tygodnie, deficyt ok. 40% względem zapotrzebowania; dieta w całości zapewniona przez badaczy; białko 2,4 g/kg/d (PRO) vs 1,2 g/kg/d (CON), różnica białka głównie z napojów na bazie białka mleka [WIEDZA – wysoka pewność co do 4 tyg., ~40%, 2,4 vs 1,2; umiarkowana co do źródła białka].
  - Trening 6 dni/tydz.: obwodowy trening oporowy całego ciała, interwały o wysokiej intensywności (sprinty), plyometria/próby czasowe; nadzorowany [WIEDZA – umiarkowana pewność co do rozkładu sesji].
  - Pomiar: model czteroskładnikowy (DXA + pletyzmografia BodPod + woda całkowita metodą rozcieńczenia deuteru) [WIEDZA – średnio-wysoka pewność].
  - Wyniki: LBM +1,2 ± 1,0 kg (PRO) vs +0,1 ± 1,0 kg (CON), różnica istotna; tkanka tłuszczowa −4,8 kg (PRO) vs −3,5 kg (CON); wydolność i siła poprawiły się podobnie w obu grupach [WIEDZA – średnio-wysoka pewność co do LBM, umiarkowana co do FM].
  - Finansowanie: [WIEDZA – niska/umiarkowana pewność] możliwe finansowanie przez organizację mleczarską (Dairy Farmers of Canada) – do sprawdzenia; Mythlift nie podaje COI dla tego rekordu.
- **Rozbieżności z opisem Mythlift:**
  - Population „40 młodych mężczyzn” bez informacji o nadwadze i braku stażu siłowego (jeśli [WIEDZA] jest trafna). To kluczowe dla applicability CL-ENRG-003: rekompozycja jest najłatwiejsza u osób z nadwagą i niewytrenowanych. Mythlift zaznacza to tylko pośrednio („wyniki nie muszą przenosić się na szczupłe osoby z wieloletnim stażem”). Severity: MEDIUM (do potwierdzenia).
  - „open_access: false” – NIEZWERYFIKOWANE (bez znaczenia merytorycznego).
  - Pozostałe elementy (4 tyg., ~40%, 2,4 vs 1,2 g/kg, 6 dni/tydz., model 4C, +1,2 vs ~0 kg, LBM ≠ mięśnie) – zgodne z [WIEDZA].
  - Brak pola coi – do uzupełnienia po weryfikacji.
- **Liczby w twierdzeniach:**
  - CL-ENRG-003: „deficyt ok. 40%” → [WIEDZA] zgodne / NIEZWERYFIKOWANE; „2,4 g/kg” → [WIEDZA] zgodne / NIEZWERYFIKOWANE; „ok. 1,2 kg (ok. 2,6 lb)” → [WIEDZA] zgodne (1,2 kg = 2,65 lb) / NIEZWERYFIKOWANE; „4 tygodnie” → [WIEDZA] zgodne / NIEZWERYFIKOWANE; „młodzi mężczyźni” → [WIEDZA] zgodne.
- **Wstępna ocena wsparcia dla twierdzeń:**
  - CL-ENRG-003 (contradicts) → PARTIAL-DIRECT. Pokazuje przyrost LBM (model 4C, nie bezpośredni pomiar mięśni) w dużym deficycie u (prawdopodobnie) niewytrenowanych mężczyzn z nadwagą, w 4 tygodnie. Wystarcza do obalenia absolutnej tezy „nie da się”, ale nie mówi o mięśniach wprost ani o osobach wytrenowanych. Mythlift uczciwie zaznacza, że LBM obejmuje wodę i glikogen. Pewność B dla mitu – akceptowalna, jeśli dołożyć drugie źródło (np. przegląd rekompozycji Barakat 2020 – [WIEDZA]).
- **Aktualność / nowsze dowody:** [WIEDZA] Barakat i wsp. 2020 (Strength Cond J) – rekompozycja możliwa także u trenujących, zwłaszcza przy wysokim białku i dobrym treningu. [WIEDZA] Helms i wsp. 2014 (IJSNEM, SR) – 2,3–3,1 g/kg FFM w deficycie u szczupłych wytrenowanych. Murphy & Koehler 2022 [SEARCH] – średnio deficyt hamuje przyrost LM (kontekst). Nowszych RCT, które zmieniałyby wniosek, nie wyszukano (limit) – NIEZWERYFIKOWANE.
- **Pole type:** rct – poprawne ([WIEDZA]).
- **Odnośniki użyte:** brak (nie wykonano wyszukiwania – limit wyczerpany).

---

## Podsumowanie priorytetów dla autora

1. **MEDIUM – Morton 2018 (SRC-0407/0500) i CL-PROT-003, CL-PLAT-003:** górna granica 95% CI punktu przegięcia (2,2 g/kg) interpretowana jako „część osób może skorzystać”. CI dotyczy niepewności średniej, nie zmienności osobniczej. Dodatkowo „próg 1,6” jest bardziej precyzyjny, niż pozwalają dane (CI 1,03–2,20, słaba identyfikowalność punktu przegięcia), a nowsze MA (Nunes 2022, Tagawa 2021) wskazują raczej na zależność stopniową. Rozważyć złagodzenie i obniżenie „strongly_recommended” albo przeformułowanie na zakres praktyczny.
2. **HIGH (weryfikacja pilna) – Slater 2019 / CL-ENRG-002:** liczba 1500–2000 kJ/d niepotwierdzona w tej sesji; całe twierdzenie na niej stoi. Dodać Helms i wsp. 2023 (Sports Med Open) jako bezpośrednie RCT u trenujących.
3. **MEDIUM – Murphy & Koehler (SRC-0406/0504), CL-ENRG-001:** populacja głównie w średnim wieku (~51 lat wg streszczenia), często w interwencjach odchudzających. Applicability powinna to mówić; „strength gains similar/largely preserved” opiera się na nieistotności z ok. 5 badań.
4. **MEDIUM – Schoenfeld 2013 (SRC-0502):** krytyka Beale 2016 (tylko 3 badania / 77 osób z wyrównanym białkiem). Wniosek mitu CL-PROT-001 wzmocnić MA Casuso & Goossens 2025.
5. **MEDIUM – Longland 2016 (SRC-0506):** cała weryfikacja tylko z wiedzy. Population prawdopodobnie pomija nadwagę i brak stażu siłowego uczestników; brak pola COI.
6. **LOW:** duplikaty rekordów (SRC-0406=SRC-0504; SRC-0407=SRC-0500) do scalenia. ISSN: pominięte zastrzeżenie o słabnięciu efektu ≥24 h oraz niejednoznaczna jednostka 2,3–3,1 g/kg (masa ciała vs FFM). Trommelen: brak informacji, że badani nie byli wytrenowani oporowo, brak wzmianki o komentarzu Witard & Mettler 2024; typ „rct” formalnie poprawny, merytorycznie badanie ostre/mechanistyczne.
