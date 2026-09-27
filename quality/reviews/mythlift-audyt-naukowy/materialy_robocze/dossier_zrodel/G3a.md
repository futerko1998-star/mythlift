# G3a – weryfikacja źródeł: progresja, autoregulacja, deload i przerwy w treningu

Data: 2026-09-27. Audytor: subagent G3a.

**Ograniczenia tej weryfikacji (dotyczą wszystkich sekcji):**
- WebFetch i curl są zablokowane (proxy zwraca 403 m.in. dla eutils.ncbi.nlm.nih.gov i api.crossref.org, sprawdzone w tej sesji). Nie miałem dostępu do żadnego pełnego tekstu.
- Tag [SEARCH] oznacza informację z wyników lub streszczeń WebSearch w tej sesji. Te streszczenia generuje wyszukiwarka i zwykle parafrazują abstrakt, więc nie są dosłownym cytatem. Liczby oznaczone [SEARCH] pochodzą z tych streszczeń, a nie z tabel publikacji.
- W trakcie pracy wyczerpał się wspólny limit wyszukiwań sesji (200/200). Części szczegółów (np. wynik CSA mięśnia prostego uda u Hwang, PMID dla Coleman, dokładna kategoria dowodów ACSM) nie dało się już sprawdzić. Oznaczyłem je jako NIEZWERYFIKOWANE.
- Twierdzenia (claims) przeczytane: CL-PROG-001/002/003, CL-DPRG-001/002/003/004, CL-CHG-001, CL-PLAT-001, CL-AUTO-001/003, CL-DLD-001/002/003.

---

### Plotkin 2022 – Progressive overload without progressing load? (SRC-0108, SRC-0300, SRC-0405)

- **Bibliografia:**
  - Autorzy: Plotkin D, Coleman M, Van Every D, Maldonado J, Oberlin D, Israetel M, Feather J, Alto A, Vigotsky AD, Schoenfeld BJ → POTWIERDZONE [SEARCH https://scholars.mssm.edu/en/publications/progressive-overload-without-progressing-load-the-effects-of-load/ ; lista afiliacji: CUNY, Renaissance Periodization, Northwestern]. SRC-0300 skraca listę do „et al.”, co jest poprawne, ale rekordy nie są spójne.
  - Tytuł → POTWIERDZONY [SEARCH https://peerj.com/articles/14142/].
  - Czasopismo, rok, numer: PeerJ 2022;10:e14142 → POTWIERDZONE [SEARCH https://pubmed.ncbi.nlm.nih.gov/36199287/ , https://peerj.com/articles/14142/].
  - DOI 10.7717/peerj.14142 → POTWIERDZONY [SEARCH].
  - PMID 36199287 → POTWIERDZONY (URL PubMed w wynikach) [SEARCH].
  - PMC9528903 → POTWIERDZONY [SEARCH https://pmc.ncbi.nlm.nih.gov/articles/PMC9528903/].
- **Status (retrakcja/korekta):** BRAK ZNALEZIONYCH [SEARCH: zapytanie o correction/erratum/retraction nic nie zwróciło; historia recenzji jest dostępna na https://peerj.com/articles/14142/reviews/]. COI jest zadeklarowany: Schoenfeld zasiada w radzie naukowej Tonal, a Israetel i Feather są zatrudnieni w Renaissance Periodization [SEARCH]. Opis COI w Mythlift jest ZGODNY.
- **Dostęp do pełnego tekstu:** brak (WebFetch zablokowany). Poziom weryfikacji: CZĘŚCIOWA (abstrakt przez streszczenia wyszukiwarki).
- **Rzeczywisty projekt i wyniki:**
  - RCT w grupach równoległych, 8 tygodni [SEARCH].
  - Uczestnicy: n=43 z co najmniej rocznym, regularnym stażem treningu dolnej części ciała. LOAD n=22 (13 M, 9 K), REPS n=21 (14 M, 7 K), łącznie 27 M i 16 K [SEARCH]. Wiek: NIEZWERYFIKOWANE.
  - Interwencja: 4 serie × 4 ćwiczenia (przysiad ze sztangą, prostowanie nóg, wspięcia na palce stojąc z prostymi nogami, wspięcia siedząc), 2×/tydz. Grupa LOAD zwiększała ciężar przy stałych powtórzeniach, grupa REPS zwiększała powtórzenia przy stałym ciężarze [SEARCH]. Dokładny zakres powtórzeń i kryterium bliskości upadku: NIEZWERYFIKOWANE.
  - Outcomes: 1RM przysiadu na maszynie Smitha (trenowano przysiad ze sztangą wolną, a testowano na Smithcie), wytrzymałość na prostowaniu nóg (liczba powtórzeń), CMJ oraz grubość mięśni w USG [SEARCH]. Miejsca pomiaru USG: środkowy czworogłowy (kompozyt RF+VI), boczny czworogłowy (VL+VI), brzuchaty łydki przyśrodkowy i boczny, płaszczkowaty. Mięśnie łydki mierzono na 25% długości podudzia [SEARCH https://peerj.com/articles/14142/]. Wyniki uda podano jako sumę kilku miejsc [SEARCH].
  - Analiza: ANCOVA z korektą na wartości wyjściowe i płeć, z 90% CI [SEARCH]. **Analizy bayesowskiej nie potwierdzono.** Abstrakt opisuje podejście częstościowe z CI90%. Jedno ze streszczeń wyszukiwarki wspominało o analizie bayesowskiej, ale wyglądało to na artefakt mojego zapytania i nie ma pokrycia w tekście abstraktu (NIEZWERYFIKOWANE). Analizę bayesowską potwierdziłem natomiast dla Coleman 2024.
  - Wyniki:
    - Wzrost RF był nieco większy w grupie REPS: +2.8 mm (CI90% −0.5 do 5.8), suma miejsc [SEARCH].
    - Siła dynamiczna była nieco większa w grupie LOAD: 2.0 kg (CI90% −2.4 do 7.8). Autorzy określają te różnice jako o wątpliwym znaczeniu praktycznym [SEARCH, streszczenie abstraktu; potwierdza to też https://lifestylemedicine.stanford.edu/increasing-weight-or-increasing-reps-can-both-make-you-stronger/]. Ten CI jest dość asymetryczny wokół 2.0, więc wartość należy sprawdzić w tabeli pełnego tekstu.
    - Poprawa 1RM i liczby powtórzeń na prostowaniu nóg była wyraźna, ale podobna w obu grupach. Wyniki CMJ są niejednoznaczne i podobne [SEARCH].
    - Wyników dla bocznego czworogłowego i łydek nie udało się uzyskać: NIEZWERYFIKOWANE.
  - Wniosek autorów: obie formy progresji są realnymi strategiami w 8-tygodniowym cyklu. Progresja ciężaru była nieco skuteczniejsza dla siły maksymalnej i równie skuteczna dla wytrzymałości [SEARCH].
  - Pomiar składu ciała (wymieniony tylko w SRC-0108): NIEZWERYFIKOWANE, bo abstrakt w wynikach go nie wymienia.
- **Rozbieżności z opisem Mythlift:**
  - Trzy rekordy SRC opisują tę samą publikację (ten sam DOI i PMID, type=rct). Różnią się listą autorów (SRC-0300 ma „et al.”), polem measurement (SRC-0108 dodaje „skład ciała”, niezweryfikowane) i treścią summary. SRC-0108 w summary podaje przewagę siłową LOAD bez zastrzeżenia o niepewności, które jest dopiero w limitations. **LOW** (higiena danych). Zalecenie: scalić w jeden rekord.
  - SRC-0108 measurement wymienia „skład ciała”, czego nie potwierdziłem. **LOW**.
  - Poza tym population, duration i summary są zgodne z abstraktem. Brak istotnych nadinterpretacji.
- **Liczby w twierdzeniach:**
  - CL-PROG-002: 43 osoby / 27 M / 16 K / co najmniej rok stażu / 8 tygodni / tylko dolna część ciała → ZGODNE [SEARCH].
  - CL-DPRG-001: 43 osoby trenujące, 8 tygodni → ZGODNE. Sformułowanie „jedyne badanie z randomizacją porównujące te dwa sposoby” → NIEZWERYFIKOWANE i prawdopodobnie nieaktualne. W wynikach wyszukiwania pojawiła się publikacja „Effects of Resistance Training Overload Progression Protocols on Strength and Muscle Mass” [SEARCH, sam tytuł: https://ouci.dntb.gov.ua/en/works/4gEjMX19/]. [WIEDZA, niepewne szczegóły] To prawdopodobnie Chaves i wsp. 2024 (Int J Sports Med), porównanie progresji ciężaru i powtórzeń u osób nietrenujących w układzie within-subject. Sugerowana zmiana: „jedyne badanie u osób trenujących”.
  - CL-DPRG-001 zakres 8-12 powtórzeń: w Plotkin 2022 nie sprawdziłem zakresu (NIEZWERYFIKOWANE). Zakres 8-12 RM dla początkujących i średniozaawansowanych pochodzi z ACSM 2009.
  - CL-DPRG-002: 43 osoby, 8 tygodni → ZGODNE. Fragment „przedziały niepewności dla większości wyników wąskie” → NIEZGODNE / nadinterpretacja. CI90% dla 1RM (−2.4 do 7.8 kg) i dla RF (−0.5 do 5.8 mm) obejmują zarówno brak różnicy, jak i różnice potencjalnie istotne praktycznie. Sam rekord SRC-0108 mówi, że różnice były „małe i niepewne” i że badanie „nie wyklucza drobnych różnic”, co jest sprzeczne wewnętrznie z tym fragmentem. **MEDIUM**.
  - CL-DPRG-003: arytmetyka 2.5 kg × 3/tydz. × 52 tyg. = 390 kg ≈ 860 lb → ZGODNE (obliczenie własne).
  - CL-DPRG-004: 10→12 kg = +20% oraz 22→26 lb → ZGODNE (obliczenie własne).
  - CL-CHG-001: 43 osoby, co najmniej rok stażu, kobiety i mężczyźni, 8 tygodni, tylko nogi → ZGODNE. Fragment „podobny przyrost grubości mięśni i siły” → ZGODNE (siła nieznacznie na korzyść LOAD, w granicach niepewności).
- **Wstępna ocena wsparcia dla twierdzeń:**
  - CL-PROG-001 (supports) → **INDIRECT/PARTIAL**. Badanie nie porównuje progresji z brakiem progresji, bo obie grupy progresowały. Wspiera tylko część „np. dokładając ciężar albo powtórzenia”. Dla tezy „muszą stopniowo zwiększać” nie daje dowodu.
  - CL-PROG-002 (supports) → **DIRECT**. Teza odwzorowuje wynik i wniosek autorów.
  - CL-PROG-003 (contradicts, mit) → **DIRECT** dla części „jeśli ciężar nie rośnie, nie ma postępu”, bo grupa REPS miała stały ciężar i przyrosty. Dla części „na każdym treningu” wsparcie jest **INDIRECT**.
  - CL-DPRG-001 (supports) → **PARTIAL**. Badanie wspiera tezę, że oba składniki podwójnej progresji działają, ale nie testowało podwójnej progresji jako schematu. Grupa REPS nigdy nie zwiększała ciężaru.
  - CL-DPRG-002 (supports) → **DIRECT**.
  - CL-DPRG-003 (contradicts, mit) → **DIRECT/PARTIAL**, jak w CL-PROG-003.
  - CL-DPRG-004 (context) → rola **context** jest adekwatna. Badanie nie dotyczyło ćwiczeń izolowanych z hantlami ani wyciągów (prostowanie nóg i wspięcia wykonywano na maszynach).
  - CL-CHG-001 (supports) → **DIRECT** tylko dla zdania o progresji powtórzeń. Progu 3-4 tygodni badanie nie dotyczy, co twierdzenie uczciwie zaznacza.
  - CL-PLAT-001 (context) → **INDIRECT**, rola context jest adekwatna.
- **Aktualność / nowsze dowody:**
  - Stanowisko ACSM 2026 (MSSE, kwiecień 2026, przewodniczący Stuart Phillips, przegląd przeglądów) zaleca progresywny trening oporowy o zmiennej preskrypcji. Periodyzacja złożona, trening do upadku i rodzaj sprzętu nie wpływały konsekwentnie na wyniki [SEARCH https://acsm.org/resistance-training-guidelines-update-2026/ , https://acsm.org/science-spotlight-acsm-releases-new-position-stand-on-resistance-training/]. Jest to spójne z tezą, że postęp ma więcej niż jedną formę.
  - Chaves i wsp. 2024: tytuł [SEARCH], szczegóły [WIEDZA, niepewne]. Nie znalazłem dowodów przeciwnych, czyli badań, w których progresja powtórzeń byłaby wyraźnie gorsza. Wyszukiwanie przeciwne było jednak ograniczone przez limit.
- **Pole type:** rct → **poprawne** (losowy przydział do równoległych grup [SEARCH]).
- **Odnośniki użyte:** https://peerj.com/articles/14142/ ; https://pubmed.ncbi.nlm.nih.gov/36199287/ ; https://pmc.ncbi.nlm.nih.gov/articles/PMC9528903/ ; https://scholars.mssm.edu/en/publications/progressive-overload-without-progressing-load-the-effects-of-load/ ; https://peerj.com/articles/14142/reviews/ ; https://lifestylemedicine.stanford.edu/increasing-weight-or-increasing-reps-can-both-make-you-stronger/ ; https://www.strongerbyscience.com/progressive-overload-strategies/ ; https://ouci.dntb.gov.ua/en/works/4gEjMX19/

---

### ACSM 2009 – Progression models in resistance training for healthy adults (SRC-0301)

- **Bibliografia:**
  - Autor: American College of Sports Medicine (autor korporacyjny) → POTWIERDZONE [SEARCH]. [WIEDZA] Zespół piszący: Ratamess NA, Alvar BA, Evetoch TK, Housh TJ, Kibler WB, Kraemer WJ, Triplett NT. Pominięcie ich w Mythlift jest akceptowalne, bo PubMed indeksuje stanowisko pod autorem korporacyjnym.
  - Tytuł → POTWIERDZONY [SEARCH].
  - Med Sci Sports Exerc 2009;41(3):687-708 → POTWIERDZONE. Rok, tom, strony, DOI i PMID widnieją w tytule rekordu ResearchGate [SEARCH https://www.researchgate.net/publication/223128732]. Zeszyt (3) wynika z URL LWW „2009/03000” [SEARCH https://journals.lww.com/acsm-msse/fulltext/2009/03000/progression_models_in_resistance_training_for.26.aspx].
  - DOI 10.1249/MSS.0b013e3181915670 → POTWIERDZONY [SEARCH].
  - PMID 19204579 → POTWIERDZONY [SEARCH].
- **Status (retrakcja/korekta):** retrakcji ani korekty nie znaleziono [SEARCH]. **Istotna krytyka: ZNALEZIONO.**
  - Carpinelli R. Challenging the American College of Sports Medicine 2009 Position Stand on Resistance Training. Medicina Sportiva 2009;13:131-137 [SEARCH https://www.researchgate.net/publication/244936612]. Wg streszczenia: nowe stanowisko jest bardzo podobne do stanowiska z 2002 r., które miało opierać większość tez na błędnej interpretacji badań i wybiórczym cytowaniu.
  - Carpinelli, Otto, Winett, krytyka stanowiska z 2002 r. [SEARCH https://www.researchgate.net/publication/238100785].
  - Fisher, Steele, Bruce-Low, Smith. Evidence-based resistance training recommendations (Medicina Sportiva 2011) [SEARCH, tytuł: https://scispace.com/pdf/evidence-based-resistance-training-recommendations-4p7ksem355.pdf; rok i czasopismo: WIEDZA].
  - Stanowisko zostało zastąpione przez stanowisko ACSM 2026 (MSSE, kwiecień 2026, DOI 10.1249/MSS.0000000000003897) [SEARCH https://www.ovid.com/jnls/acsm-msse/fulltext/10.1249/mss.0000000000003897~american-college-of-sports-medicine-position-stand , https://acsm.org/resistance-training-guidelines-update-2026/].
- **Dostęp do pełnego tekstu:** brak. Poziom weryfikacji: CZĘŚCIOWA (streszczenia wyszukiwarki z kilku kopii tekstu).
- **Rzeczywisty projekt i wyniki (zalecenia):**
  - Typ: stanowisko towarzystwa (position stand), oparte na przeglądzie literatury z kategoriami dowodów A-D [WIEDZA; kategorie widoczne pośrednio w SEARCH].
  - Reguła progresji: przy treningu z określonym obciążeniem RM zwiększać ciężar o 2-10%, gdy osoba wykona bieżące obciążenie na 1-2 powtórzenia ponad zakładaną liczbę **w dwóch kolejnych sesjach treningowych** (reguła „2-for-2”). Niższy procent dotyczy ćwiczeń na małe grupy mięśniowe, wyższy na duże [SEARCH https://www.ideafit.com/progression-models-in-resistance-training-for-healthy-adults/ , https://www.medscape.com/viewarticle/717047].
  - Kategoria dowodów dla reguły 2-10%: **NIEZWERYFIKOWANE, sprzeczne streszczenia.** Dwa streszczenia wyszukiwarki podały kategorię B, jedno C. Rozstrzygnięcie wymaga pełnego tekstu. [WIEDZA, niepewne] Skłaniam się ku B.
  - Hipertrofia: obciążenia 1-12 RM w sposób periodyzowany z naciskiem na 6-12 RM, przerwy 1-2 min, umiarkowana prędkość. Zalecane programy wieloseryjne o większej objętości. Dla zaawansowanych: 70-100% 1RM, 1-12 powtórzeń (głównie 6-12 RM), 3-6 serii [SEARCH]. [WIEDZA] Dla początkujących i średniozaawansowanych: 70-85% 1RM, 8-12 RM.
- **Rozbieżności z opisem Mythlift:**
  - Summary PL/EN pomija warunek „w dwóch kolejnych sesjach”. Mythlift pisze tylko o 1-2 powtórzeniach więcej niż zakładano. Ta część reguły jest bezpośrednio istotna dla CL-DPRG-001/003 i dodatkowo wzmacnia mit z CL-DPRG-003. **LOW/MEDIUM**.
  - Limitations: „Reguła zwiększania ciężaru opiera się głównie na praktyce i opinii ekspertów”. Merytorycznie jest to obronione krytyką (Carpinelli) i brakiem badań porównujących wielkość skoku obciążenia. Samo ACSM nadało jednak regule kategorię dowodów (B lub C, niezweryfikowane), a nie D (konsensus panelu). Sugerowane sformułowanie: ACSM nadał kategorię X, ale nie ma badań porównujących wielkości skoku obciążenia. **LOW**.
  - Limitations: „w 2026 roku zaktualizowane nowym stanowiskiem” → ZGODNE [SEARCH].
  - Summary: „nacisk na zakres ok. 6-12 powtórzeń w zmiennym programie” → ZGODNE [SEARCH].
- **Liczby w twierdzeniach:**
  - CL-DPRG-001: 2-10% → ZGODNE. Kryterium „gdy we wszystkich seriach osiągnie się górną granicę zakresu” → NIEZGODNE dosłownie z ACSM, gdzie kryterium to 1-2 powtórzenia ponad cel w dwóch kolejnych sesjach. To praktyczna adaptacja reguły, nie jej treść. Należy to zaznaczyć (**LOW**). Opis „najmniejszy praktyczny krok (ok. 2-10%)” to parafraza. ACSM wiąże wielkość skoku z masą mięśniową, a nie z najmniejszym dostępnym krokiem (**LOW**). Zakres 8-12 → ZGODNE z ACSM dla początkujących i średniozaawansowanych [WIEDZA].
  - CL-DPRG-003: 1-2 powtórzenia ponad plan → ZGODNE, ale niekompletne (brak warunku dwóch kolejnych sesji, **LOW**).
  - CL-DPRG-004: 2-10% → ZGODNE. ACSM zaleca niższy procent dla ćwiczeń na małe grupy mięśniowe [SEARCH], co wzmacnia argument o zbyt dużych skokach hantli. Warto to dopisać.
- **Wstępna ocena wsparcia dla twierdzeń:**
  - CL-DPRG-001 (supports) → **PARTIAL**. Stanowisko wspiera wielkość skoku i zasadę „najpierw powtórzenia, potem ciężar”, ale nie zawiera podwójnej progresji w formie z Mythlift. Wymaga dopisania, że 2026 ACSM zastąpił stanowisko z 2009 r. Czy nowe stanowisko utrzymuje regułę 2-10%, jest NIEZWERYFIKOWANE.
  - CL-DPRG-003 (contradicts, mit) → **DIRECT** jako opinia ekspertów: reguła zakłada zwiększanie ciężaru warunkowo, a nie na każdym treningu.
  - CL-DPRG-004 (supports) → **PARTIAL**. Wspiera tylko wielkość skoku i jej zależność od masy mięśniowej. Nie mówi o poszerzaniu zakresu powtórzeń. Certainty D jest adekwatna.
- **Aktualność / nowsze dowody:**
  - ACSM 2026 (overview of reviews, 137 przeglądów/badań wg komunikatów; wg streszczeń ponad 30 000 uczestników) [SEARCH]. Zaleca progresywny trening z elastyczną preskrypcją. Twierdzenia opierające regułę na stanowisku z 2009 r. powinny sprawdzić, czy nowe stanowisko podaje konkretną regułę progresji obciążenia (NIEZWERYFIKOWANE).
  - Zawężenie zakresu powtórzeń dla hipertrofii (6-12) zostało złagodzone przez nowsze dane o podobnej hipertrofii w szerokim zakresie obciążeń przy wysiłku bliskim upadku. Tak też mówi limitations w Mythlift ([WIEDZA], np. Schoenfeld 2017 i późniejsze metaanalizy).
- **Pole type:** position_stand → **poprawne**.
- **Odnośniki użyte:** https://www.ideafit.com/progression-models-in-resistance-training-for-healthy-adults/ ; https://www.medscape.com/viewarticle/717047 ; https://tourniquets.org/wp-content/uploads/PDFs/ACSM-Progression-models-in-resistance-training-for-healthy-adults-2009.pdf ; https://www.researchgate.net/publication/223128732 ; https://journals.lww.com/acsm-msse/fulltext/2009/03000/progression_models_in_resistance_training_for.26.aspx ; https://www.researchgate.net/publication/244936612_Challenging_the_American_College_of_Sports_Medicine_2009_Position_Stand_on_Resistance_Training ; https://paulogentil.com/pdf/Challenging%20the%20ACSM%202009%20position%20stand%20on%20resistance%20training.pdf ; https://www.researchgate.net/publication/238100785 ; https://scispace.com/pdf/evidence-based-resistance-training-recommendations-4p7ksem355.pdf ; https://acsm.org/resistance-training-guidelines-update-2026/ ; https://acsm.org/science-spotlight-acsm-releases-new-position-stand-on-resistance-training/ ; https://www.ovid.com/jnls/acsm-msse/fulltext/10.1249/mss.0000000000003897~american-college-of-sports-medicine-position-stand

---

### Hickmott 2022 – Load and volume autoregulation, SR/MA (SRC-0302)

- **Bibliografia:**
  - Autorzy: Hickmott LM, Chilibeck PD, Shaw KA, Butcher SJ → POTWIERDZONE [SEARCH].
  - Tytuł → POTWIERDZONY [SEARCH https://pubmed.ncbi.nlm.nih.gov/35038063/].
  - Sports Med Open 2022;8:9 → POTWIERDZONE (tom 8, artykuł 9) [SEARCH]. Zeszyt (1) jest konwencją wydawcy, NIEZWERYFIKOWANE osobno.
  - DOI 10.1186/s40798-021-00404-9 → POTWIERDZONY [SEARCH https://sportsmedicine-open.springeropen.com/articles/10.1186/s40798-021-00404-9].
  - PMID 35038063 → POTWIERDZONY [SEARCH].
  - PMC8762534 → POTWIERDZONY [SEARCH].
- **Status (retrakcja/korekta):** BRAK ZNALEZIONYCH (osobnego zapytania o errata nie wykonałem z powodu limitu; w wynikach nie pojawiła się żadna korekta).
- **Dostęp do pełnego tekstu:** brak. Poziom weryfikacji: CZĘŚCIOWA (abstrakt).
- **Rzeczywisty projekt i wyniki:**
  - Przegląd systematyczny z metaanalizą wg PRISMA. Bazy: MEDLINE, Embase, Scopus, SPORTDiscus [SEARCH].
  - Populacja wg celu pracy: osoby trenujące siłowo [SEARCH].
  - 15 badań: 6 o autoregulacji ciężaru (RPE oparte na RIR oraz VBT vs %1RM) i 9 o autoregulacji objętości (próg spadku prędkości ≤25% vs >25%) [SEARCH].
  - Autoregulacja ciężaru, 1RM: MD 2.07 kg (95% CI −0.32 do 4.46), p=0.09, SMD 0.21. Różnica nieistotna [SEARCH].
  - Autoregulacja ciężaru, hipertrofia: NIEZWERYFIKOWANE, czy w ogóle przeprowadzono metaanalizę CSA dla tego porównania. Abstrakt w wynikach podaje CSA tylko dla analizy spadku prędkości. [WIEDZA, niepewne] Prawdopodobnie danych było za mało.
  - Spadek prędkości ≤25% vs >25%: 1RM MD 2.32 kg (0.33 do 4.31), p=0.02, SMD 0.23 na korzyść ≤25%. CSA niższe przy ≤25%: MD 0.61 cm² (0.05 do 1.16), p=0.03, SMD 0.28. Spadek >25% vs ≤20%: CSA MD 0.64 cm² (0.07 do 1.20), SMD 0.34 [SEARCH].
  - Wnioski autorów: autoregulacja ciężaru i standaryzowana preskrypcja dają podobny przyrost siły. Przy wyrównanych seriach i intensywności względnej spadek prędkości ≤25% lepiej sprzyja sile, a >20-25% hipertrofii [SEARCH].
  - Heterogeniczność (I²), liczba badań RPE i VBT w puli 6 badań oraz ryzyko biasu: NIEZWERYFIKOWANE.
- **Rozbieżności z opisem Mythlift:**
  - Summary PL/EN → ZGODNE (MD ok. 2 kg w granicach niepewności; mniejszy spadek prędkości sprzyja sile, większy hipertrofii).
  - Population „15 badań (6 o autoregulacji ciężaru, 9 o autoregulacji objętości)” → ZGODNE.
  - Measurement „CSA (różne metody obrazowania)” → NIEZWERYFIKOWANE, ale wiarygodne.
  - Brak istotnych rozbieżności w samym rekordzie.
- **Liczby w twierdzeniach:**
  - CL-AUTO-001: „metaanaliza 6 badań” → ZGODNE. „ok. 2 kg na korzyść autoregulacji, w granicach niepewności” → ZGODNE (2.07 kg, CI −0.32 do 4.46). „ok. 4 lb” → drobne niedoszacowanie, bo 2.07 kg ≈ 4.6 lb (**LOW**, kosmetyczne).
  - CL-AUTO-003: brak liczb z tego źródła. Błąd szacowania RIR (ok. 1 powtórzenie) pochodzi z SRC-0304, spoza mojej listy.
- **Wstępna ocena wsparcia dla twierdzeń:**
  - CL-AUTO-001 (supports) → **PARTIAL**. Teza dotyczy RIR/RPE, a oszacowanie 2.07 kg łączy RPE i VBT. Z abstraktu nie wynika, czy istnieje osobna podgrupa RPE. Część „w nielicznych badaniach, które mierzyły mięśnie, ich przyrost był podobny” opiera się praktycznie na Helms 2018, a nie na metaanalizie. **MEDIUM**: w evidence_summary doprecyzować, że metaanaliza obejmuje RPE i VBT łącznie. Certainty B (umiarkowana) wygląda na zawyżoną dla części o hipertrofii (w praktyce jedno RCT, n=21) i prawdopodobnie także dla siły (6 małych badań, CI przechodzi przez 0). Rozważyć C albo rozdzielenie certainty dla siły i dla hipertrofii.
  - CL-AUTO-003 (contradicts, mit) → **PARTIAL/DIRECT**. Metaanaliza pokazuje, że autoregulowany dobór ciężaru daje podobny przyrost 1RM, co podważa tezę, że trening oparty na RPE nie działa. Pula łączy jednak RPE z VBT.
- **Aktualność / nowsze dowody:**
  - Metaanaliza sieciowa 2025 (J Exerc Sci Fit, PMID 40791980): APRE, VBRT i RPE istotnie skuteczniejsze od PBRT dla siły maksymalnej. SUCRA: APRE 93.0%, RPE 66.8%, VBRT 27.0%, PBRT 13.2%. Jednocześnie dla 1RM przysiadu nie stwierdzono umiarkowanych ani dużych różnic między interwencjami [SEARCH https://pubmed.ncbi.nlm.nih.gov/40791980/ , https://www.sciencedirect.com/science/article/pii/S1728869X25000590]. Kierunek jest zgodny z hasłem „podobny, może nieco większy”. Jakość NMA: NIEZWERYFIKOWANE.
  - Hickmott i wsp. 2026, JSCR (PMID 42297625), RCT u starszych dorosłych (n=36, ok. 62 lata, 12 tyg.). Przyrost 4RM w wyciskaniu był większy przy LRVBT (12.2 kg) niż przy PBT (6.8 kg). RBT (8.5 kg) nie różniło się od pozostałych [SEARCH https://pubmed.ncbi.nlm.nih.gov/42297625/]. Nie zmienia wniosku, ale poszerza populację.
  - Zhang i wsp. 2021, metaanaliza autoregulacji u sportowców [SEARCH, tytuł: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7994759/]. Wyników nie sprawdzono.
  - Nie znalazłem nowszych danych przeciwnych (autoregulacja gorsza od %1RM).
- **Pole type:** meta_analysis → **poprawne**.
- **Odnośniki użyte:** https://pubmed.ncbi.nlm.nih.gov/35038063/ ; https://sportsmedicine-open.springeropen.com/articles/10.1186/s40798-021-00404-9 ; https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8762534/ ; https://pubmed.ncbi.nlm.nih.gov/40791980/ ; https://www.sciencedirect.com/science/article/pii/S1728869X25000590 ; https://pubmed.ncbi.nlm.nih.gov/42297625/ ; https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7994759/

---

### Helms 2018 – RPE vs. percentage 1RM loading (SRC-0303)

- **Bibliografia:**
  - Autorzy: Helms ER, Byrnes RK… → pierwsze dwa nazwiska POTWIERDZONE [SEARCH https://ro.ecu.edu.au/ecuworkspost2013/4175/]. Cooke DM, Haischer MH, Carzoli JP, Johnson TK: [WIEDZA], w tej sesji NIEZWERYFIKOWANE.
  - Tytuł → POTWIERDZONY [SEARCH].
  - Front Physiol 2018;9:247 → POTWIERDZONE (DOI zawiera 2018.00247; publikacja z marca 2018) [SEARCH].
  - DOI 10.3389/fphys.2018.00247 → POTWIERDZONY [SEARCH].
  - PMID 29628895 → POTWIERDZONY [SEARCH].
  - PMC5877330 → POTWIERDZONY [SEARCH].
- **Status (retrakcja/korekta):** retrakcji ani korekty nie znaleziono [SEARCH]. **Krytyka metody: ZNALEZIONO (ogólnie, nie wobec tej pracy).** Badanie używa magnitude-based inference (MBI), metody szeroko krytykowanej. [WIEDZA] Sainani, MSSE 2018. [SEARCH, tytuł] Przegląd systematyczny użycia MBI w naukach o sporcie: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7319293/.
- **Dostęp do pełnego tekstu:** brak. Poziom weryfikacji: CZĘŚCIOWA (abstrakt).
- **Rzeczywisty projekt i wyniki:**
  - Porównanie dwóch grup, 8 tygodni, DUP 3×/tydz.: przysiad, a potem wyciskanie leżąc, z tą samą liczbą serii i powtórzeń. Grupa %1RM n=11, grupa RPE n=10, łącznie **n=21** [SEARCH].
  - Uczestnicy: mężczyźni trenujący siłowo, 19-35 lat [SEARCH].
  - Pomiary: 1RM przysiadu i wyciskania leżąc. USG: grubość mięśnia piersiowego oraz obszernego bocznego uda na 50% i 70% długości kości udowej [SEARCH].
  - Przyrost 1RM:
    - wyciskanie: %1RM +9.64±5.36 kg, RPE +10.70±3.30 kg;
    - przysiad: %1RM +13.91±5.89 kg, RPE +17.05±5.44 kg;
    - suma: %1RM +23.55±10.38 kg, RPE +27.75±7.94 kg [SEARCH].
  - MBI: 79% (przysiad), 57% (wyciskanie) i 72% (suma) szansy na małą przewagę ES na korzyść RPE. ES ±90% CL: 0.50±0.63, 0.28±0.73, 0.48±0.68 [SEARCH].
  - 1RM i grubość mięśni (PMT oraz VL w obu miejscach) wzrosły w obu grupach. Różnice między grupami nieistotne [SEARCH].
  - Wniosek autorów: oba typy obciążania są skuteczne, a obciążanie wg RPE może dawać małą przewagę w 1RM u większości osób [SEARCH].
  - Sposób losowania oraz średnie obciążenie treningowe w grupach: NIEZWERYFIKOWANE.
- **Rozbieżności z opisem Mythlift:** brak istotnych. Population (21 mężczyzn, 19-35 lat), measurement (USG piersiowy i VL, 1RM), summary i limitations (MBI, mała próba, tylko mężczyźni, kilka miejsc pomiaru) są zgodne z abstraktem.
- **Liczby w twierdzeniach:** CL-AUTO-001 i CL-AUTO-003 nie przytaczają liczb z tego badania. Fragment „obie grupy zyskały podobnie dużo siły i grubości mięśni” → ZGODNE.
- **Wstępna ocena wsparcia dla twierdzeń:**
  - CL-AUTO-001 (supports) → **DIRECT** dla RPE vs %1RM przy wyrównanych seriach i powtórzeniach. Jest to główne źródło dla części „nieliczne badania, które mierzyły mięśnie”. Przewaga siłowa „może nieco większa” opiera się na MBI i nie jest istotna w klasycznym sensie. Sformułowanie Mythlift jest ostrożne i adekwatne.
  - CL-AUTO-003 (contradicts, mit) → **DIRECT**. Program oparty na RPE dał wyraźne przyrosty siły i grubości mięśni, więc nie jest prawdą, że trening oparty na RPE nie działa.
- **Aktualność / nowsze dowody:** jak w Hickmott (NMA 2025 i RCT 2026 u starszych). Kierunek pozostaje zgodny, dowodów przeciwnych nie znalazłem.
- **Pole type:** rct → **poprawne**, o ile przydział był losowy. [WIEDZA] Był. Szczegółów randomizacji nie sprawdziłem.
- **Odnośniki użyte:** https://pubmed.ncbi.nlm.nih.gov/29628895/ ; https://www.frontiersin.org/journals/physiology/articles/10.3389/fphys.2018.00247/full ; https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5877330/ ; https://ro.ecu.edu.au/ecuworkspost2013/4175/ ; https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7319293/

---

### Coleman 2024 – Gaining more from doing less? One-week deload (SRC-0305)

- **Bibliografia:**
  - Autorzy: Coleman M, Burke R, Augustin F, Piñero A, Maldonado J, Fisher JP, Israetel M, Androulakis Korakakis P, Swinton P, Oberlin D, Schoenfeld BJ → POTWIERDZONE [SEARCH].
  - Tytuł → POTWIERDZONY [SEARCH].
  - PeerJ 2024;12:e16777 → POTWIERDZONE (opublikowane 22.01.2024) [SEARCH https://peerj.com/articles/16777.pdf].
  - DOI 10.7717/peerj.16777 → POTWIERDZONY [SEARCH].
  - PMID 38274324 → **NIEZWERYFIKOWANE** (nie pojawił się w wynikach; limit wyszukiwań).
  - PMC10809978 → POTWIERDZONY [SEARCH].
- **Status (retrakcja/korekta):** brak znalezionych korekt w wynikach (osobnego zapytania nie wykonano z powodu limitu). Preprint istnieje na SportRxiv [SEARCH https://sportrxiv.org/index.php/server/preprint/view/302]. COI z Mythlift (rada naukowa producenta sprzętu i współzałożyciel firmy z programami treningowymi) → NIEZWERYFIKOWANE w tej sesji. [WIEDZA] Jest to spójne z Schoenfeld–Tonal i Israetel–RP.
- **Dostęp do pełnego tekstu:** brak. Poziom weryfikacji: CZĘŚCIOWA.
- **Rzeczywisty projekt i wyniki:**
  - RCT w grupach równoległych. n=39 młodych osób trenujących siłowo (29 M, 10 K) [SEARCH].
  - Program: 9 tygodni, wysoka objętość. Grupa DELOAD całkowicie powstrzymała się od treningu oporowego przez tydzień w połowie programu. Grupa TRAD trenowała bez przerwy [SEARCH].
  - Trening nóg był nadzorowany, górnej części ciała nie [SEARCH].
  - Wysiłek: wysoki. Część uczestników kończyła serie przed upadkiem mięśniowym [SEARCH].
  - Outcomes: grubość mięśni (USG) w proksymalnej, środkowej i dystalnej części środkowego i bocznego czworogłowego oraz w środkowej części trójgłowego łydki. Ponadto siła izometryczna i dynamiczna nóg, wytrzymałość lokalna czworogłowego i moc nóg [SEARCH].
  - **Siła izokinetyczna nie była mierzona** wg abstraktu, mierzono izometryczną i dynamiczną. Konkretne ćwiczenie 1RM: NIEZWERYFIKOWANE.
  - Analiza bayesowska [SEARCH]. Hipertrofia: mediany różnic bliskie zeru, wszystkie 95% CrI wyraźnie obejmują zero. Analiza wielowymiarowa nie zmieniła wniosku [SEARCH]. Siła: prawdopodobieństwo a posteriori przewagi TRAD 0.851 dla 1RM i 0.924 dla siły izometrycznej [SEARCH]. Wytrzymałość i moc: bez istotnych różnic [SEARCH]. Gotowość do treningu (kwestionariusz): niewielka przewaga TRAD [SEARCH].
  - Wniosek autorów: tydzień przerwy w połowie 9-tygodniowego programu wydaje się niekorzystnie wpływać na siłę nóg, a nie wpływa na hipertrofię, moc ani wytrzymałość lokalną [SEARCH].
  - Uwaga projektowa (wnioskowanie z opisu, [WIEDZA]): DELOAD miał prawdopodobnie 8 tygodni treningu wobec 9 w TRAD. Mniejszy przyrost siły może więc wynikać z krótszej ekspozycji na trening, a nie ze szkodliwości samego deloadu.
- **Rozbieżności z opisem Mythlift:** brak istotnych. Summary, population, measurement i limitations (deload jako całkowita przerwa, nadzorowane tylko nogi) są zgodne. Drobiazg: summary mówi, że gotowość do treningu była nieco lepsza w TRAD, co jest zgodne z abstraktem.
- **Liczby w twierdzeniach:**
  - CL-DLD-001: 9 tygodni, 39 osób, tydzień całkowitej przerwy w połowie → ZGODNE. Sformułowanie „jedyne badanie z randomizacją” → **NIEAKTUALNE**. W lutym 2026 ukazało się RCT w układzie within-subject (Scientific Reports, NCT06825052): 19 nietrenujących młodych mężczyzn, 8 tygodni, deload w formie redukcji serii i częstotliwości (tygodnie 4 i 8: 1×/tydz., 2 serie). Nie stwierdzono interakcji dla grubości mięśni ani dla 10RM [SEARCH https://www.nature.com/articles/s41598-026-40612-5]. Sugerowana zmiana: „jedyne RCT u osób trenujących”, z dopisaniem nowego badania. Częściowo spełnia to też revision_trigger CL-DLD-001 (deload jako lżejszy trening), choć u osób nietrenujących. **MEDIUM**.
  - CL-DLD-003: tydzień całkowitej przerwy i 9-tygodniowy program → ZGODNE. Fragment „nie zmniejszył przyrostu mięśni” → ZGODNE (CrI wokół zera).
- **Wstępna ocena wsparcia dla twierdzeń:**
  - CL-DLD-001 (supports) → **DIRECT** dla tezy, że tydzień przerwy nie zwiększył hipertrofii, a siła rosła nieco mniej. Dla uogólnienia „deload jest opcją, a nie obowiązkiem” wsparcie jest **PARTIAL**, bo badano całkowitą przerwę, 9 tygodni i tylko nogi. Twierdzenie to uczciwie zaznacza.
  - CL-DLD-002 (context) → rola context jest adekwatna.
  - CL-DLD-003 (contradicts, mit) → **DIRECT** dla przerwy 1-tygodniowej u trenujących: brak utraty przyrostów mięśni.
- **Aktualność / nowsze dowody:**
  - Sci Rep 2026 (powyżej) [SEARCH].
  - Ankieta wśród trenerów przygotowania motorycznego o preskrypcji w czasie deloadu (PMID 39446750) [SEARCH, tytuł].
  - Bell i wsp.: A Practical Approach to Deloading, wytyczne praktyczne [SEARCH, tytuł: https://shura.shu.ac.uk/35313/3/Bell-APracticalApproach(AM).pdf].
  - Przeciwnych danych nie znalazłem.
- **Pole type:** rct → **poprawne**.
- **Odnośniki użyte:** https://peerj.com/articles/16777/ ; https://peerj.com/articles/16777.pdf ; https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10809978/ ; https://scholars.mssm.edu/en/publications/gaining-more-from-doing-less-the-effects-of-a-one-week-deload-per/ ; https://sportrxiv.org/index.php/server/preprint/view/302 ; https://www.nature.com/articles/s41598-026-40612-5 ; https://clinicaltrials.gov/study/NCT06825052 ; https://pubmed.ncbi.nlm.nih.gov/39446750/

---

### Rogerson 2024 – Deloading practices, cross-sectional survey (SRC-0306)

- **Bibliografia:**
  - Autorzy: Rogerson D, Nolan D, Androulakis Korakakis P, Immonen V, Wolf M, Bell L → POTWIERDZONE [SEARCH].
  - Tytuł → POTWIERDZONY [SEARCH].
  - Sports Med Open 2024;10(1):26 → POTWIERDZONE (online 18.03.2024) [SEARCH].
  - DOI 10.1186/s40798-024-00691-y → POTWIERDZONY [SEARCH].
  - PMID 38499934 → POTWIERDZONY [SEARCH].
  - PMC10948666 → POTWIERDZONY [SEARCH].
- **Status (retrakcja/korekta):** BRAK ZNALEZIONYCH w wynikach (osobne zapytanie nie zostało wykonane z powodu limitu).
- **Dostęp do pełnego tekstu:** brak. Poziom weryfikacji: CZĘŚCIOWA.
- **Rzeczywisty projekt i wyniki:**
  - Anonimowa ankieta internetowa (55 pytań), badanie przekrojowe [SEARCH].
  - Uczestnicy: n=246 zawodników sportów siłowych i sylwetkowych (181 M = 73.6%, 65 K = 26.4%), wiek 29.5±8.6 lat, staż treningu oporowego 8.2±6.2 lat, staż startowy 3.8±3.1 lat [SEARCH].
  - Wyniki:
    - Wszyscy stosowali deload, głównie dla zarządzania energią i zmęczeniem [SEARCH].
    - Deload trwał 6.4±1.7 dnia i pojawiał się co 5.6±2.3 tygodnia [SEARCH].
    - Strategia była proaktywna i planowana, czasem łączona z autoregulacją. Deload robiono też przy zastoju wyników, zwiększonej bolesności mięśni lub bólach stawów [SEARCH].
    - Objętość malała (mniej powtórzeń w serii i mniej serii w tygodniu), ciężar malał, wysiłek malał (więcej RIR). Częstotliwość i dobór ćwiczeń pozostawały bez zmian [SEARCH].
  - Czy „wszyscy stosowali” wynika z kryteriów rekrutacji: NIEZWERYFIKOWANE.
- **Rozbieżności z opisem Mythlift:** brak istotnych. Population (246, 74% M, ok. 8 lat), measurement (ankieta, 55 pytań), summary i limitations są zgodne.
- **Liczby w twierdzeniach:**
  - CL-DLD-002: 246 zawodników → ZGODNE. „średnio ok. 6 dni” → ZGODNE (6.4). „średnio co 5-6 tygodni” → ZGODNE (5.6, przy SD 2.3, czyli dużej rozpiętości, co warto wspomnieć). Redukcja objętości, ciężaru i wysiłku przy tej samej częstotliwości → ZGODNE.
  - CL-DLD-001: brak liczb z tego źródła.
- **Wstępna ocena wsparcia dla twierdzeń:**
  - CL-DLD-002 (supports) → **DIRECT** dla części opisowej: jak doświadczeni zawodnicy robią deload. **PARTIAL** dla części normatywnej („rozsądną reakcją jest...”) i dla sygnałów zmęczenia. Ankieta wymienia zastój wyników, bolesność i bóle stawów. Kryteria „spadek wyników przy tym samym RIR” i „wyraźnie gorsza gotowość” to ekstrapolacja. Certainty D i opis „brak badań skuteczności” są adekwatne.
  - CL-DLD-001 (context) → adekwatne.
- **Aktualność / nowsze dowody:** RCT z 2026 (Sci Rep) o deloadzie jako redukcji objętości u nietrenujących [SEARCH]. Praktyczne rekomendacje Bell i wsp. [SEARCH, tytuł]. Wniosek opisowy nie zmienia się.
- **Pole type:** observational → **poprawne** (ankieta przekrojowa).
- **Odnośniki użyte:** https://pubmed.ncbi.nlm.nih.gov/38499934/ ; https://sportsmedicine-open.springeropen.com/articles/10.1186/s40798-024-00691-y ; https://link.springer.com/article/10.1186/s40798-024-00691-y ; https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10948666/ ; http://shura.shu.ac.uk/33446/ ; https://www.springermedicine.com/sports-medicine-open-1-2024/26590728

---

### Hwang 2017 – Strength maintained after 2 weeks of detraining, whey protein (SRC-0307)

- **Bibliografia:**
  - Autorzy: Hwang PS, Andre TL, McKinley-Barnard SK… → pierwsze trzy nazwiska POTWIERDZONE [SEARCH]. Morales Marroquín FE, Gann JJ, Song JJ: NIEZWERYFIKOWANE.
  - Tytuł → POTWIERDZONY [SEARCH https://pubmed.ncbi.nlm.nih.gov/28328712/].
  - J Strength Cond Res 2017;31(4):869-881 → POTWIERDZONE [SEARCH].
  - DOI 10.1519/JSC.0000000000001807 → POTWIERDZONY [SEARCH, URL Ovid/LWW].
  - PMID 28328712 → POTWIERDZONY [SEARCH].
- **Status (retrakcja/korekta):** BRAK ZNALEZIONYCH w wynikach (osobne zapytanie nie zostało wykonane z powodu limitu).
- **Dostęp do pełnego tekstu:** brak. Poziom weryfikacji: CZĘŚCIOWA (abstrakt).
- **Rzeczywisty projekt i wyniki:**
  - Randomizowane, podwójnie zaślepione porównanie suplementów: 25 g białka serwatkowego (PRO) vs 25 g węglowodanów (CHO) [SEARCH].
  - Uczestnicy: n=20 mężczyzn trenujących siłowo, wiek 20.95±1.23 lat [SEARCH].
  - Program 4 dni/tydz.: 4 tyg. treningu, 2 tyg. przerwy (detraining), 4 tyg. ponownego treningu. Suplement przyjmowano w dni treningowe, a w czasie przerwy codziennie [SEARCH].
  - Pomiary: siła w wypychaniu nóg (LPS), CSA mięśnia prostego uda (USG), masa beztłuszczowa (DXA) na początku, po 4 tyg., po przerwie i po ponownym treningu [SEARCH].
  - Wyniki:
    - LPS rosła w całym 10-tygodniowym badaniu i nie spadła po przerwie w żadnej grupie [SEARCH].
    - Masa beztłuszczowa: obie grupy zachowały ją po przerwie, zmiany nieistotne statystycznie [SEARCH, parafraza abstraktu].
    - **Wynik CSA mięśnia prostego uda po przerwie: NIEZWERYFIKOWANE.** Brak go w dostępnych streszczeniach. To istotna luka dla CL-DLD-003, bo jest to jedyny pomiar mięśnia w tym badaniu.
  - Wniosek autorów: krótki okres przerwy może zachować siłę dolnej części ciała u młodych trenujących mężczyzn, niezależnie od suplementacji 25 g białka serwatkowego po treningu [SEARCH].
- **Rozbieżności z opisem Mythlift:**
  - Population, measurement, summary i limitations są zgodne. Limitations słusznie zaznacza, że losowano suplement, a nie przerwę, więc brak grupy trenującej ciągle.
  - Summary nie wspomina wyniku CSA RF (pomiaru mięśnia), a opisuje tylko DXA-LBM. Jeśli CSA RF spadło, opis byłby niepełny. **LOW/MEDIUM**, do weryfikacji w pełnym tekście.
- **Liczby w twierdzeniach:**
  - CL-DLD-003: fragment „po 2 tygodniach przerwy siła i masa beztłuszczowa się utrzymały” → ZGODNE z abstraktem.
  - Applicability „programy od 9 do 24 tygodni” → ZGODNE (Hwang 10 tyg.).
- **Wstępna ocena wsparcia dla twierdzeń:**
  - CL-DLD-003 (contradicts, mit) → **PARTIAL**. Siła: DIRECT (LPS bez spadku). Mięśnie: INDIRECT, bo DXA-LBM to nie masa mięśniowa (obejmuje wodę i glikogen), a wynik bezpośredniego pomiaru mięśnia (CSA RF) jest nieznany. Brak grupy kontrolnej trenującej ciągle to projekt pre-post dla pytania o przerwę. Mythlift poprawnie używa terminu „masa beztłuszczowa”, a nie „mięśnie”.
- **Aktualność / nowsze dowody:**
  - [WIEDZA] Hortobágyi i wsp. 1993 (MSSE), 14 dni bezczynności u sportowców siłowych: siła bez istotnych zmian, pole przekroju włókien typu II zmniejszyło się o kilka procent. Dane częściowo przeciwne co do samych mięśni, ale nie świadczą o utracie „dużej części” przyrostów.
  - [WIEDZA] Bosquet i wsp. 2013 (Scand J Med Sci Sports), metaanaliza przerwania treningu: siła maksymalna zwykle utrzymuje się do ok. 3 tygodni.
  - Encarnação i wsp. 2022, przegląd systematyczny detrainingu [SEARCH, tytuł: https://www.mdpi.com/2813-0413/1/1/1]. Szczegółów nie sprawdzono.
- **Pole type:** rct → **formalnie poprawne** (RCT suplementu). Dla pytania o przerwę dane są w praktyce obserwacyjne (pre-post bez kontroli). Mythlift to zaznacza. **LOW**: warto dodać adnotację w polu type lub summary.
- **Odnośniki użyte:** https://pubmed.ncbi.nlm.nih.gov/28328712/ ; https://www.ovid.com/jnls/nsca-jscr/abstract/10.1519/jsc.0000000000001807~resistance-traininginduced-elevations-in-muscular-strength?redirectionsource=fulltextview ; https://journals.lww.com/nsca-jscr/fulltext/2017/04000/resistance_training_induced_elevations_in_muscular.1.aspx ; https://www.semanticscholar.org/paper/Resistance-Training%E2%80%93Induced-Elevations-in-Muscular-Hwang-Andre/5b40820423676c5fd5620f5bcedfd8c35f0e093d ; https://www.mdpi.com/2813-0413/1/1/1

---

### Ogasawara 2013 – Continuous vs periodic strength training over 6 months (SRC-0308)

- **Bibliografia:**
  - Autorzy: Ogasawara R, Yasuda T, Ishii N, Abe T → POTWIERDZONE [SEARCH https://link.springer.com/article/10.1007/s00421-012-2511-9].
  - Tytuł → POTWIERDZONY [SEARCH].
  - Eur J Appl Physiol 2013;113:975-985 → POTWIERDZONE (tom i strony) [SEARCH]. Zeszyt (4): NIEZWERYFIKOWANE.
  - DOI 10.1007/s00421-012-2511-9 → POTWIERDZONY [SEARCH].
  - PMID 23053130 → POTWIERDZONY [SEARCH https://pubmed.ncbi.nlm.nih.gov/23053130/].
- **Status (retrakcja/korekta):** BRAK ZNALEZIONYCH [SEARCH].
- **Dostęp do pełnego tekstu:** brak. Poziom weryfikacji: CZĘŚCIOWA (abstrakt).
- **Rzeczywisty projekt i wyniki:**
  - n=14 młodych mężczyzn [SEARCH]. Status treningowy: **wcześniej nietrenujący** wg streszczenia wyszukiwarki [SEARCH]. Uwaga: streszczenie mogło mieszać tę pracę z pracą Ogasawara 2011 (Clin Physiol Funct Imaging), która jest wprost opisana jako „previously untrained”. [WIEDZA] W pracy z 2013 r. też uczestniczyli nietrenujący. Liczebność grup (prawdopodobnie 7/7) i sposób przydziału: NIEZWERYFIKOWANE.
  - Interwencja: wyciskanie leżąc 75% 1RM, 3×10, 3×/tydz. [SEARCH]. Grupa CTR trenowała bez przerwy 24 tygodnie. Grupa PTR przeszła 3 cykle po 6 tygodni treningu z 3-tygodniowymi przerwami między cyklami [SEARCH].
  - Pomiary: CSA mięśnia trójgłowego ramienia i piersiowego większego (MRI), MVC izometryczne prostowników łokcia, 1RM [SEARCH].
  - Wyniki:
    - Po pierwszych 6 tygodniach przyrosty były podobne w obu grupach [SEARCH].
    - W drugim cyklu (3 tyg. przerwy i 6 tyg. treningu) przyrost CSA i siły był istotnie większy w PTR niż w CTR w tym samym okresie [SEARCH].
    - W CTR adaptacje w ostatnim 6-tygodniowym okresie były mniejsze niż na początku [SEARCH].
    - Po 24 tygodniach hipertrofia była podobna w obu grupach [SEARCH].
    - Końcowy 1RM w obu grupach: NIEZWERYFIKOWANE (abstrakt w wynikach mówi w konkluzji tylko o hipertrofii).
    - Zmiany CSA w trakcie samych 3-tygodniowych przerw w pracy z 2013 r.: NIEZWERYFIKOWANE. W pracy z 2011 r. po 3 tygodniach przerwy nie było istotnego spadku CSA ani 1RM [SEARCH, praca z 2011].
- **Rozbieżności z opisem Mythlift:**
  - Population „14 młodych mężczyzn” pomija status treningowy (wg dostępnych danych: nietrenujący). Dla twierdzenia o osobach trenujących (CL-DLD-003 „w większości trenujący”) to istotne, bo szybki powrót przyrostów u początkujących nie musi dotyczyć zaawansowanych. **MEDIUM**: dopisać „wcześniej nietrenujący” po potwierdzeniu.
  - Summary: „po przerwach przyrosty w kolejnych cyklach były co najmniej takie jak w grupie trenującej bez przerwy” → ZGODNE dla drugiego cyklu (istotnie większe w PTR). „Po 24 tygodniach przyrost mięśni i siły był w obu grupach podobny” → hipertrofia ZGODNA, siła NIEZWERYFIKOWANA.
  - „łącznie 18 tygodni treningu zamiast 24” → ZGODNE arytmetycznie (3×6 = 18).
  - Limitations „umiarkowanej objętości” jest dyskusyjne. Jedno ćwiczenie, 3 serie × 3/tydz. to raczej niska objętość. **LOW**.
- **Liczby w twierdzeniach:**
  - CL-DLD-003: „3-tygodniowe przerwy co 6 tygodni”, „24 tygodnie”, „podobne przyrosty” → ZGODNE dla hipertrofii. Applicability „przerwy od 1 do 3 tygodni; programy od 9 do 24 tygodni” → ZGODNE. „w większości trenujący siłowo” → formalnie ZGODNE (2 z 3 badań). Należy jednak jawnie zaznaczyć, że badanie 24-tygodniowe dotyczyło osób nietrenujących (**LOW/MEDIUM**).
- **Wstępna ocena wsparcia dla twierdzeń:**
  - CL-DLD-003 (contradicts, mit) → **PARTIAL**. Badanie wspiera tezę, że 3-tygodniowe przerwy nie kasują długoterminowej hipertrofii. Uczestnicy byli jednak nietrenujący, n=14, ćwiczenie było jedno, a mit mówi o utracie po 1-2 tygodniach, a nie o wyniku po 24 tygodniach.
  - Certainty B dla mitu jest do przyjęcia łącznie z Coleman, Hwang, Ogasawara 2011 i Halonen 2024, bo kierunek jest spójny. Pojedyncze badania są jednak małe.
- **Aktualność / nowsze dowody:**
  - Halonen i wsp. 2024 (Scand J Med Sci Sports): 55 nietrenujących dorosłych (ukończyło 20 PRT i 22 CRT). Schemat 10 tyg. treningu, 10 tyg. przerwy, 10 tyg. treningu vs 10 tyg. kontroli i 20 tyg. treningu ciągłego. Na końcu brak różnic w sile (wypychanie nóg, uginanie ramion) i w CSA. W pierwszych 5 tygodniach powrotu przyrosty były szybsze [SEARCH https://onlinelibrary.wiley.com/doi/10.1111/sms.14739 , https://www.jyu.fi/en/news/breaks-in-resistance-training-do-not-impair-long-term-development-in-strength-and-muscle-size]. Wniosek jest spójny z CL-DLD-003, ale populacja jest nietrenująca.
  - Ogasawara 2011 (15 tyg., 3 tyg. przerwy, nietrenujący): brak istotnych spadków po przerwie [SEARCH https://onlinelibrary.wiley.com/doi/10.1111/j.1475-097X.2011.01031.x].
  - Nie znalazłem nowszych danych przeciwnych u osób trenujących. Wyszukiwanie przeciwne było jednak ograniczone przez limit.
- **Pole type:** rct → **NIEZWERYFIKOWANE**. Nie potwierdziłem losowego przydziału do grup CTR/PTR. Jeśli przydział nie był losowy, właściwy typ to badanie kontrolowane nierandomizowane.
- **Odnośniki użyte:** https://link.springer.com/article/10.1007/s00421-012-2511-9 ; https://pubmed.ncbi.nlm.nih.gov/23053130/ ; https://www.researchgate.net/publication/232229816_Comparison_of_muscle_hypertrophy_following_6-month_of_continuous_and_periodic_strength_training ; https://www.semanticscholar.org/paper/Comparison-of-muscle-hypertrophy-following-6-month-Ogasawara-Yasuda/fa1e518decb3fe6a603573d510dc4ae7b0bed2d3 ; https://onlinelibrary.wiley.com/doi/10.1111/j.1475-097X.2011.01031.x ; https://pubmed.ncbi.nlm.nih.gov/21771261/ ; https://onlinelibrary.wiley.com/doi/10.1111/sms.14739 ; https://www.jyu.fi/en/news/breaks-in-resistance-training-do-not-impair-long-term-development-in-strength-and-muscle-size ; https://www.mdpi.com/2813-0413/1/1/1

---

## Podsumowanie najważniejszych problemów (G3a)

| Severity | Gdzie | Problem |
|---|---|---|
| MEDIUM | CL-AUTO-001 (SRC-0302) | Pula 2.07 kg łączy RPE i VBT, a teza dotyczy RIR/RPE. Część o hipertrofii opiera się praktycznie na jednym RCT (Helms, n=21). Certainty B wydaje się zawyżona, rozważyć C lub rozdzielenie. |
| MEDIUM | CL-DPRG-002 (SRC-0300) | „przedziały niepewności wąskie” to nadinterpretacja. CI90% dla 1RM (−2.4 do 7.8 kg) i RF (−0.5 do 5.8 mm) są szerokie. Sprzeczne z własnym opisem SRC-0108. |
| MEDIUM | CL-DLD-001 (SRC-0305) | „jedyne badanie z randomizacją” jest nieaktualne. RCT w Sci Rep 2026 (deload jako redukcja objętości, nietrenujący) częściowo spełnia też revision_trigger. |
| MEDIUM | SRC-0308 / CL-DLD-003 | Brak statusu treningowego w population. Ogasawara 2013: wg dostępnych danych nietrenujący. Losowość przydziału niezweryfikowana. |
| LOW/MEDIUM | SRC-0301 / CL-DPRG-001/003 | Pominięty warunek „w dwóch kolejnych sesjach” z reguły ACSM 2-10%. Podwójna progresja z Mythlift to adaptacja, nie treść ACSM. Kategoria dowodów ACSM niezweryfikowana (B lub C). |
| LOW/MEDIUM | CL-DPRG-001 (SRC-0300) | „jedyne RCT porównujące progresję powtórzeń i ciężaru”: prawdopodobnie istnieje Chaves i wsp. 2024 (nietrenujący). Doprecyzować „u osób trenujących”. |
| LOW/MEDIUM | SRC-0307 | Wynik CSA RF (USG) po przerwie jest nieznany. Mythlift opisuje tylko DXA-LBM, które nie jest miarą mięśni. |
| LOW | SRC-0108/0300/0405 | Trzy duplikaty tej samej publikacji z różnym measurement (skład ciała niezweryfikowany) i summary. Scalić. |
| INDIRECT | CL-PROG-001 ← SRC-0108 | Plotkin nie testował progresji wobec braku progresji. Wspiera tylko formy progresji. |
| Info | Plotkin 2022 | Analizy bayesowskiej nie potwierdzono: abstrakt opisuje ANCOVA z CI90%. Analiza bayesowska dotyczy Coleman 2024 (posterior 0.851 i 0.924 dla przewagi siłowej TRAD). |
