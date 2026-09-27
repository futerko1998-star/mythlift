# RAPORT WERYFIKACJI NAUKOWEJ — Mythlift (eksport `weryfikacja_calosc.html`, 2026-09-27)

<!-- PODSUMOWANIE ZBIORCZE: sekcja zostanie scalona na początku pliku po zakończeniu wszystkich partii i przebiegu adwersaryjnego (zgodnie z instrukcją audytu). Do tego czasu aktualne liczniki są w POSTEP.md. -->

> Status: AUDYT W TOKU. Raport jest dopisywany partiami (partia 0: źródła i twierdzenia; partie 1-22: pytania wg kart pojęć). Wcześniej zapisane sekcje nie są nadpisywane.

---

# PARTIA 0 — WERYFIKACJA ŹRÓDEŁ I AUDYT CLAIM → SOURCE (fundament dla wszystkich pytań)

Data wykonania: 2026-09-27. Zakres: 60 rekordów źródeł (`sources/SRC-*.yaml`) = 48 unikalnych publikacji wg DOI, 68 twierdzeń (`claims/CL-*.yaml`).

## 0.1 Metodyka i ograniczenia (przeczytać przed interpretacją wyników)

- **Brak dostępu do pełnych tekstów.** W środowisku audytu narzędzia pobierania stron (WebFetch, curl) były zablokowane dla wszystkich domen naukowych (PubMed, doi.org, PMC, Europe PMC, Crossref, strony wydawców). Dostępna była wyłącznie wyszukiwarka internetowa (tytuły wyników i ich streszczenia). W związku z tym:
  - **żadne źródło nie zostało zweryfikowane z pełnego tekstu** (0/48);
  - wszystkie 48 publikacji zweryfikowano **częściowo**: dane bibliograficzne i kluczowe wyniki na poziomie abstraktu/streszczeń w wynikach wyszukiwania; szczegóły metod, tabele i dokładne wielkości efektów, których nie było w wynikach, oznaczono jako NIEZWERYFIKOWANE albo jako wiedzę recenzenta [WIEDZA] (niepotwierdzoną w sesji);
  - nie podaję dosłownych cytatów ze źródeł (nie widziałem pełnych tekstów). Cudzysłowy w raporcie oznaczają wyłącznie treść Mythlift.
- **Oznaczenia pewności informacji o źródłach:** [SEARCH] – potwierdzone w wynikach wyszukiwania w tej sesji (URL w dossier i w tabeli 0.2); [WIEDZA] – wiedza recenzenta, niepotwierdzona w sesji; NIEZWERYFIKOWANE – nie udało się ustalić.
- **Wsparcie (SUPPORT):** DIRECT – źródło bada dokładnie to, co twierdzenie (populacja, interwencja, outcome); PARTIAL – wspiera część twierdzenia lub z istotnym zastrzeżeniem; INDIRECT – wspiera pośrednio (inna populacja/outcome/mechanizm); NONE – nie wspiera.
- **QUALITY** – ocena siły dowodów na samo twierdzenie (niezależna od tego, czy źródło je wspiera) na skali Mythlift A–D; podaję ocenę Mythlift → ocenę recenzenta.
- Numeracja problemów: `S-xx` (rekordy źródeł), `C-xx` (twierdzenia). Problemy w pytaniach mają numerację w partiach 1–22.

## 0.2 Weryfikacja źródeł (48 publikacji / 60 rekordów)

Legenda kolumn: **Bibl.** – autorzy/tytuł/czasopismo/rok/tom/strony/DOI/PMID; **Retr./kor.** – retrakcja, korekta, istotna krytyka; **PT** – pełny tekst (wszędzie: NIE); **Poziom** – CZĘŚCIOWA = bibliografia + wyniki na poziomie abstraktu potwierdzone w wyszukiwarce.

| Rekord(y) SRC | Publikacja | Bibl. | Retr./kor. | PT | Poziom | type | Najważniejsze ustalenia / rozbieżności |
|---|---|---|---|---|---|---|---|
| 0100, 0211, 0401 | Currier i in. 2026, ACSM Position Stand, MSSE 58(4):851-872 | POTWIERDZONE (DOI, PMID 41843416, 58(4):851-872; wersja 58(3):512-545 z jednego wyniku wyszukiwarki nie ma poparcia) | brak; krytyka kontekstowa: Fry i in. 2026 JSCR (niski udział osób wysoko wytrenowanych w syntezach) | NIE | CZĘŚCIOWA | position_stand OK | 137 przeglądów, >30 000 uczestników, ≥18 lat, 6-52 tyg. – ZGODNE. Siła: ≥80% 1RM, pełny ROM, ≥2 sesje/tydz.; hipertrofia: ≥10 serii/grupę mięśniową/tydz.; brak spójnego wpływu upadku, sprzętu, periodyzacji – ZGODNE. **S-01 (MEDIUM):** „przeciążenie fazy ekscentrycznej” – w źródle (wg streszczeń) chodzi o skurcze wyłącznie ekscentryczne vs wyłącznie koncentryczne. Czas pod napięciem / struktura serii / przerwy – tylko źródła wtórne (NIEZWERYFIKOWANE). Trzy zdublowane rekordy z różnym zapisem autorów (LOW). |
| 0101 | Schoenfeld, Grgic, Ogborn, Krieger 2017, JSCR 31(12):3508-3523 | POTWIERDZONE | nie znaleziono | NIE | CZĘŚCIOWA | meta_analysis OK | 21 badań, ≤60% vs >60% 1RM, wszystkie serie do upadku; hipertrofia podobna, 1RM większe przy ciężkich, izometria bez różnicy – ZGODNE. Wielkości efektów – NIEZWERYFIKOWANE. |
| 0102 | Currier i in. 2023, BJSM 57:1211-1220 (bayesowska NMA) | POTWIERDZONE (zeszyt 18 niezweryfikowany) | nie znaleziono | NIE | CZĘŚCIOWA | meta_analysis OK | Siła: 178 badań, n=5097; hipertrofia: 119 badań, n=3364, 47% kobiet – ZGODNE. Wszystkie warianty > brak treningu; w rankingu siły najwyżej wyższy ciężar – ZGODNE. Kategorie ciężaru (próg ok. 80% 1RM) [WIEDZA] → wsparcie dla „~30% = ciężkie” tylko pośrednie. |
| 0103 | Morton i in. 2016, J Appl Physiol 121(1):129-138 | POTWIERDZONE | nie znaleziono | NIE | CZĘŚCIOWA | rct OK | 49 trenujących mężczyzn, 12 tyg.; obciążenie nie determinowało hipertrofii; ostre zmiany hormonów niezwiązane z przyrostami (R² < 0,25) – ZGODNE. Szczegóły grup (20-25 vs 8-12 powt.; istotna różnica 1RM tylko w wyciskaniu) – [WIEDZA]. |
| 0104 | Refalo i in. 2023, Sports Med 53(3):649-665 | POTWIERDZONE | komentarz + odpowiedź autorów (bez retrakcji) | NIE | CZĘŚCIOWA | meta_analysis OK | 15 badań; trywialna przewaga upadku przy dowolnej definicji (ES 0,19; 95% CI 0,00-0,37; p=0,045) – ZGODNE z opisem Mythlift. |
| 0105, 0203, 0403 | Robinson i in. 2024, Sports Med 54(9):2209-2231 | POTWIERDZONE | nie znaleziono | NIE | CZĘŚCIOWA | meta_analysis OK | RIR szacowane z opisów protokołów; hipertrofia rośnie bliżej upadku, siła – znikome różnice – ZGODNE. Trzy zdublowane rekordy (LOW). |
| 0106, 0304, 0404 | Halperin i in. 2022, Sports Med 52(2):377-390 | POTWIERDZONE | nie znaleziono | NIE | CZĘŚCIOWA | meta_analysis – dokładniej scoping review z eksploracyjną MA (LOW) | 12 badań / 414 uczestników; zaniżanie o 0,95 powt. (95% CI 0,17-1,73), I²=97,9%; trafność rośnie przy mniejszej liczbie powtórzeń, brak istotnych różnic <12 powt. – ZGODNE. Wpływ stażu i „późniejszych serii” – NIEZWERYFIKOWANE w wynikach. |
| 0107 | Zourdos i in. 2016, JSCR 30(1):267-275 | POTWIERDZONE | nie znaleziono | NIE | CZĘŚCIOWA | observational (przekrojowe badanie walidacyjne) OK | 29 osób; korelacja prędkość–RPE r=−0,88 (doświadczeni) i −0,77 (początkujący) – opis Mythlift spłaszcza różnicę (LOW). |
| 0108, 0300, 0405 | Plotkin i in. 2022, PeerJ 10:e14142 | POTWIERDZONE | nie znaleziono; COI zadeklarowany | NIE | CZĘŚCIOWA | rct OK | 43 osoby (27 M/16 K), ≥1 rok stażu, 8 tyg., tylko nogi – ZGODNE. CI90%: 1RM −2,4 do 7,8 kg; RF −0,5 do 5,8 mm (szerokie). Trzy zdublowane rekordy; „skład ciała” w SRC-0108.measurement – NIEZWERYFIKOWANE (LOW). |
| 0109 | Wackerhage i in. 2019, J Appl Physiol 126(1):30-43 | POTWIERDZONE | nie znaleziono | NIE | CZĘŚCIOWA | narrative_review OK | Sygnały mechaniczne = główni kandydaci; uszkodzenie prawdopodobnie niekonieczne; metabolity – dowody pośrednie – ZGODNE. |
| 0110 | Damas i in. 2016, J Physiol 594(18):5209-5222 | POTWIERDZONE | komentarz przeciwny w J Physiol 2016 (PMID 27976401) | NIE | CZĘŚCIOWA | mechanistic dopuszczalne | Uszkodzenie max w T1, mniejsze T2, minimalne T3; MyoPS koreluje z hipertrofią dopiero w T2/T3 – ZGODNE. n=10; uczestnicy nietrenujący [WIEDZA] – nieopisane w Mythlift (LOW). |
| 0111 | Nosaka, Newton, Sacco 2002, Scand J Med Sci Sports 12(6):337-346 | POTWIERDZONE | nie znaleziono | NIE | CZĘŚCIOWA | mechanistic (ostre badanie eksperymentalne) dopuszczalne | 110 studentów płci męskiej; 12/24/60 skurczów ekscentrycznych zginaczy łokcia; DOMS nie odzwierciedla wielkości uszkodzenia – ZGODNE. |
| 0200 | Schoenfeld, Ogborn, Krieger 2017, J Sports Sci 35(11):1073-1082 | POTWIERDZONE | krytyka: Buckner i in. 2023 (J Trainology) | NIE | CZĘŚCIOWA | meta_analysis OK | 15 badań; ciągła zależność istotna (P=0,002; ~0,37%/serię); porównanie kategorii <5 / 5-9 / 10+ tylko trend (P=0,074) – rekord Mythlift poprawny, ale twierdzenia/pytania podają próg jako wynik (→ C-08). |
| 0201, 0402 | Pelland i in. 2026, Sports Med 56(2):481-505 | POTWIERDZONE (PMID 41343037) | nie znaleziono | NIE | CZĘŚCIOWA | meta_analysis OK | 67 badań, 2058 osób (79% M, ~25 lat); malejące przyrosty, wyraźniejsze dla siły; częstotliwość – efekt znikomy dla hipertrofii, dodatni dla siły; liczenie serii pośrednich jako 0,5 najlepiej dla hipertrofii – ZGODNE. Zdublowane rekordy (LOW). |
| 0202 | Baz-Valle i in. 2021, JSCR 35(3):870-878 | POTWIERDZONE | nie znaleziono | NIE | CZĘŚCIOWA | systematic_review OK | 14 RCT, 18-35 lat, ≥1 rok stażu, 6-20+ powt., bez metaanalizy – ZGODNE. |
| 0204 | Krieger 2010, JSCR 24(4):1150-1159 | POTWIERDZONE (PMID niepotwierdzony w wynikach) | nie znaleziono | NIE | CZĘŚCIOWA | meta_analysis OK | Istotna tylko różnica „wiele vs jedna” (różnica ES 0,10; CI 0,02-0,19); 2-3 vs 1 i 4-6 vs 1 – trendy. **S-02 (MEDIUM):** rekord sugeruje wyraźny gradient 1 → 2-3 → 4-6 i „40% większy przyrost” (to względna różnica ES). |
| 0205 | Iversen i in. 2021, Sports Med 51(10):2079-2095 | POTWIERDZONE (DOI niepotwierdzony w wynikach) | komentarz i odpowiedź autorów, bez istotnej krytyki | NIE | CZĘŚCIOWA | narrative_review OK | Minimum ~4 serie/grupę/tydz. przy 6-15 RM – rekomendacja autorów (opinia ekspercka) – ZGODNE. |
| 0206 | Schoenfeld, Grgic, Krieger 2019, J Sports Sci 37(11):1286-1295 | POTWIERDZONE | nie znaleziono | NIE | CZĘŚCIOWA | meta_analysis OK | 25 badań; przy wyrównanej objętości brak różnicy częstotliwości – ZGODNE. |
| 0207 | Grgic i in. 2018, Sports Med 48(5):1207-1220 | POTWIERDZONE (PMID niepotwierdzony) | nie znaleziono | NIE | CZĘŚCIOWA | meta_analysis OK | Przy wyrównanej objętości p=0,421; efekty w podgrupach (wielostawowe, górna część ciała, kobiety) – ZGODNE. |
| 0208 | Singer i in. 2024, Front Sports Act Living 6:1429789 | POTWIERDZONE | nie znaleziono | NIE | CZĘŚCIOWA | meta_analysis OK | 9 badań, 19 pomiarów; niewielka korzyść >60 s, być może przez volume load; brak wyraźnych różnic >90 s – ZGODNE. ES/CrI – NIEZWERYFIKOWANE. |
| 0209 | Grgic i in. 2018, Sports Med 48(1):137-151 | POTWIERDZONE | nie znaleziono | NIE | CZĘŚCIOWA | systematic_review OK | 23 badania, 491 osób (84% M); >2 min u trenujących, 60-120 s u nietrenujących – ZGODNE. |
| 0210 | Schoenfeld i in. 2016, JSCR 30(7):1805-1812 | POTWIERDZONE | nie znaleziono | NIE | CZĘŚCIOWA | rct OK | 21 trenujących mężczyzn, 1 vs 3 min, 8 tyg.; grubość mięśni istotnie większa tylko przód uda (triceps trend p=0,06); 1RM przysiad i wyciskanie większe przy 3 min – ZGODNE. |
| 0301 | ACSM 2009 Position Stand, MSSE 41(3):687-708 | POTWIERDZONE | krytyka: Carpinelli 2009 (Medicina Sportiva); **zastąpione przez ACSM 2026** | NIE | CZĘŚCIOWA | position_stand OK | Reguła +2-10% gdy wykonuje się 1-2 powt. ponad cel w dwóch kolejnych sesjach – Mythlift pomija warunek „dwóch kolejnych sesji” (LOW). |
| 0302 | Hickmott i in. 2022, Sports Med Open 8(1):9 | POTWIERDZONE | nie znaleziono | NIE | CZĘŚCIOWA | meta_analysis OK | 15 badań (6 autoregulacja ciężaru, 9 objętości); MD 1RM 2,07 kg (CI −0,32 do 4,46) – łącznie RPE i VBT (→ C-10). |
| 0303 | Helms i in. 2018, Front Physiol 9:247 | POTWIERDZONE | krytyka metody MBI (ogólna) | NIE | CZĘŚCIOWA | rct OK | 21 mężczyzn, 8 tyg., RPE vs %1RM; podobna siła i grubość mięśni – ZGODNE. |
| 0305 | Coleman i in. 2024, PeerJ 12:e16777 | POTWIERDZONE (PMID niepotwierdzony) | nie znaleziono | NIE | CZĘŚCIOWA | rct OK | 39 osób, 9 tyg., tydzień całkowitej przerwy; hipertrofia podobna; siła: prawdopodobieństwo przewagi treningu ciągłego 0,851 (1RM) i 0,924 (izometria) – ZGODNE. **Nowsze RCT (Sci Rep 2026)** – patrz C-13. |
| 0306 | Rogerson i in. 2024, Sports Med Open 10(1):26 | POTWIERDZONE | nie znaleziono | NIE | CZĘŚCIOWA | observational OK | 246 osób; deload ~6,4 dnia co ~5,6 tyg. (SD 2,3); redukcja objętości, ciężaru i wysiłku przy tej samej częstotliwości – ZGODNE. |
| 0307 | Hwang i in. 2017, JSCR 31(4):869-881 | POTWIERDZONE | nie znaleziono | NIE | CZĘŚCIOWA | rct (randomizowano suplement, nie przerwę) | Siła i LBM (DXA) utrzymane po 2 tyg. przerwy – ZGODNE; wynik CSA RF – NIEZWERYFIKOWANE. |
| 0308 | Ogasawara i in. 2013, Eur J Appl Physiol 113(4):975-985 | POTWIERDZONE | nie znaleziono | NIE | CZĘŚCIOWA | rct (randomizacja niepotwierdzona) | 14 wcześniej NIETRENUJĄCYCH mężczyzn [SEARCH/WIEDZA]; 3-tyg. przerwy co 6 tyg. – końcowa hipertrofia podobna. Rekord nie podaje statusu treningowego (S-06, LOW). |
| 0309 | Benito i in. 2020, IJERPH 17(4):1285 | POTWIERDZONE | nie znaleziono | NIE | CZĘŚCIOWA | meta_analysis OK | 111 badań, 1927 mężczyzn; +1,53 kg (95% CI 1,30-1,76); FFM/LMM/SMM łącznie – ZGODNE. „Średnio ok. 10 tyg. (4-24)” – NIEZWERYFIKOWANE (w wynikach tylko kryterium „>2 tyg.”) → C-14. |
| 0310 | Ahtiainen i in. 2003, Eur J Appl Physiol 89(6):555-563 | POTWIERDZONE | NIEZWERYFIKOWANE | NIE | CZĘŚCIOWA | other (nierandomizowane) OK | 21 tyg.; CSA mięśnia czworogłowego +5,6% (nietrenujący) vs −1,8% (zawodnicy); siła +20,9% vs +3,9% – ZGODNE. |
| 0311 | Iraki i in. 2019, Sports 7(7):154 | POTWIERDZONE | nie znaleziono | NIE | CZĘŚCIOWA | narrative_review OK | Nadwyżka 10-20%, przyrost masy ciała 0,25-0,5%/tydz. (wolniej u zaawansowanych) – ZGODNE. |
| 0406, 0504 | Murphy & Koehler 2022, Scand J Med Sci Sports 32(1):125-137 | POTWIERDZONE (PMID niepotwierdzony) | nie znaleziono | NIE | CZĘŚCIOWA | meta_analysis OK | Próg ~500 kcal/d dla LM; siła: ES −0,31, p=0,28 (ok. 5 badań) – ZGODNE. Średni wiek ~51 lat i przewaga interwencji odchudzających – wg jednego streszczenia (niepotwierdzone) → C-20. SRC-0406.population sugeruje, że wszystkie badania miały kontrolę bez deficytu (S-07, LOW). |
| 0407, 0500 | Morton i in. 2018, BJSM 52(6):376-384 | POTWIERDZONE | **KOREKTA: BJSM 2020;54(19):e7, PMID 32943392** (treść prawdopodobnie dot. ujawnienia COI – NIEZWERYFIKOWANE) | NIE | CZĘŚCIOWA | meta_analysis OK | 49 RCT, 1863 osoby; próg 1,62 g/kg/d (95% CI 1,03-2,20); FFM +0,30 kg; 1RM +2,49 kg – ZGODNE. **S-03 (MEDIUM):** rekordy mają status „active” zamiast „corrected” (reguła 16.7 Mythlift wymaga wtedy przeglądu CL-PROT-003 i CL-PLAT-003). |
| 0408, 0508 | Lamon i in. 2021, Physiol Rep 9(1):e14660 | POTWIERDZONE | nie znaleziono | NIE | CZĘŚCIOWA | mechanistic vs rct – niespójne (S-04, LOW) | 13 osób (7 M/6 K), crossover, jedna noc bez snu; MPS −18%, kortyzol +21%, testosteron −24% – ZGODNE. Zdanie w SRC-0508.limitations o testosteronie „głównie u mężczyzn” – NIEZWERYFIKOWANE. |
| 0409 | Moesgaard i in. 2022, Sports Med 52(7):1647-1666 | POTWIERDZONE | NIEZWERYFIKOWANE | NIE | CZĘŚCIOWA | meta_analysis OK | 35 badań; hipertrofia bez różnic; siła – niewielka przewaga periodyzacji, UP u trenujących ES 0,61 (CI 0,00-1,22) – ZGODNE. |
| 0410 | Kassiano i in. 2022, JSCR 36(6):1753-1762 | POTWIERDZONE (PMID niepotwierdzony) | NIEZWERYFIKOWANE | NIE | CZĘŚCIOWA | systematic_review OK | 8 badań, 241 młodych mężczyzn; zaplanowana zmienność może sprzyjać hipertrofii regionalnej, nadmierna rotacja może szkodzić – ZGODNE. Nowsze RCT Kassiano i in. 2024/2025 (RQES, 70 kobiet) – brak przewagi zmienności → C-16. |
| 0411 | Fonseca i in. 2014, JSCR 28(11):3085-3092 | POTWIERDZONE (PMID niepotwierdzony) | NIEZWERYFIKOWANE | NIE | CZĘŚCIOWA | rct (randomizacja niepotwierdzona) | 12 tyg., MRI; wszystkie głowy czworogłowego tylko w grupach ze zmiennymi ćwiczeniami (testy wewnątrzgrupowe) – ZGODNE. |
| 0412 | Baz-Valle i in. 2019, PLoS One 14(12):e0226989 | POTWIERDZONE | nie znaleziono | NIE | CZĘŚCIOWA | rct OK | ≥2 lata stażu [wtórne], losowe vs stałe ćwiczenia, 8 tyg.; podobna MT i siła, większa motywacja przy losowej zmienności – ZGODNE. |
| 0501 | Jäger i in. 2017, JISSN 14:20 | POTWIERDZONE | nie znaleziono | NIE | CZĘŚCIOWA | position_stand OK | 1,4-2,0 g/kg/d; 0,25 g/kg lub 20-40 g/posiłek; co 3-4 h; zwiększona wrażliwość ≥24 h – ZGODNE. Pominięte zastrzeżenie, że efekt z czasem słabnie (LOW). |
| 0502 | Schoenfeld, Aragon, Krieger 2013, JISSN 10:53 | POTWIERDZONE (PMID niepotwierdzony) | **istotna krytyka: Beale 2016 JISSN** (tylko 3 badania / 77 osób z wyrównanym białkiem) | NIE | CZĘŚCIOWA | meta_analysis OK | 23 badania; efekt timingu znikał po uwzględnieniu całkowitego białka – ZGODNE. Nowsza MA Casuso & Goossens 2025 (Nutrients) – brak efektu timingu – wzmacnia mit. |
| 0503 | Trommelen i in. 2023, Cell Rep Med 4(12):101324 | POTWIERDZONE (PMID niepotwierdzony) | komentarz Witard & Mettler 2024 (IJSNEM) | NIE | CZĘŚCIOWA | rct (ostre, mechanistyczne) | 36 osób, 0/25/100 g, 12 h; większa i dłuższa odpowiedź po 100 g, znikoma oksydacja – ZGODNE. Uczestnicy nie byli wytrenowani oporowo – nieopisane (S-08, LOW). |
| 0505 | Slater i in. 2019, Front Nutr 6:131 | POTWIERDZONE | nie znaleziono | NIE | TYLKO BIBLIOGRAFIA + ogólny zakres | narrative_review OK | **Liczba 1500-2000 kJ/d – NIEZWERYFIKOWANA w wynikach** ([WIEDZA]: prawdopodobnie zgodna) → C-21. |
| 0506 | Longland i in. 2016, AJCN 103(3):738-746 | POTWIERDZONE | nie znaleziono | NIE | CZĘŚCIOWA | rct OK | 40 młodych mężczyzn **z nadwagą**, ~40% deficyt, 4 tyg., 2,4 vs 1,2 g/kg; LBM +1,2 kg vs ~0; tłuszcz −4,8 vs −3,5 kg – ZGODNE; populacja „z nadwagą” pominięta w Mythlift → C-22. |
| 0507 | Nedeltcheva i in. 2010, Ann Intern Med 153(7):435-441 | POTWIERDZONE | nie znaleziono | NIE | CZĘŚCIOWA | rct (crossover) OK | 10 osób z nadwagą (7 M/3 K), 41 lat, BMI 27,4; 14 dni; krótki sen: −55% utraty tłuszczu, +60% utraty FFM – ZGODNE. Replikacja kierunku: Wang i in. 2018 (Sleep, 8 tyg., n=36). |
| 0509 | Cheung, Hume, Maxwell 2003, Sports Med 33(2):145-164 | POTWIERDZONE | nie znaleziono | NIE | CZĘŚCIOWA | narrative_review OK | Przebieg DOMS (szczyt 24-72 h, ustąpienie 5-7 dni), zalecenia treningowe – ZGODNE; mechanizm „mikrouszkodzenia” jest nieaktualny jako jedyne wyjaśnienie (Mizumura & Taguchi 2016/2024; Hotfiel 2018) – dotyczy kart/pytań, nie rekordu. |
| 0510 | Silbernagel i in. 2007, Am J Sports Med 35(6):897-906 | POTWIERDZONE | list do redakcji (Knobloch 2007), bez retrakcji | NIE | CZĘŚCIOWA | rct OK | 38 pacjentów (2×19); ból ≤5/10, ustępuje do rana, nie narasta z tygodnia na tydzień; brak negatywnych skutków kontynuowania aktywności – ZGODNE; brak formalnego testu non-inferiority → C-24. |
| 0511 | Finucane i in. 2020, JOSPT 50(7):350-372 | POTWIERDZONE | nie znaleziono | NIE | CZĘŚCIOWA | position_stand (ramy konsensusowe IFOMPT) dopuszczalne | Wyłącznie poważne patologie KRĘGOSŁUPA; rozróżnia stany nagłe (ogon koński) i pilne (np. podejrzenie przerzutów – dni) → C-25 (HIGH). |

**Podsumowanie weryfikacji źródeł:** 48/48 publikacji – bibliografia potwierdzona (w 7 publikacjach pojedyncze pola, głównie PMID, niepotwierdzone w wynikach; brak rozbieżności); 0/48 z pełnego tekstu; 47/48 zweryfikowane częściowo (bibliografia + wyniki na poziomie abstraktu), 1/48 (Slater 2019) – bibliografia bez potwierdzenia kluczowej liczby. Retrakcje: 0. Korekty: 1 (Morton 2018). Istotna opublikowana krytyka/komentarze: ACSM 2009 (Carpinelli), Schoenfeld 2013 (Beale 2016), Trommelen 2023 (Witard & Mettler 2024), Damas 2016 (komentarz przeciwny), Schoenfeld 2017 J Sports Sci (Buckner 2023). Duplikaty rekordów: 8 publikacji ma 2-3 rekordy SRC (20 rekordów), często z różnymi summary/type (problem systemowy, LOW).

### Problemy na poziomie rekordów źródeł

#### S-01 · MEDIUM · SRC-0100, SRC-0211, SRC-0401 · pole `summary.pl/en`
- **OBECNIE:** „a przyrost mięśni większa objętość (od 10 serii tygodniowo) i przeciążenie fazy ekscentrycznej” / „eccentric overload”.
- **PROBLEM:** Wg streszczeń i komunikatu ACSM czynnikiem sprzyjającym hipertrofii były skurcze wyłącznie ekscentryczne w porównaniu z wyłącznie koncentrycznymi, a nie „przeciążenie ekscentryczne” (supramaksymalne obciążenie fazy opuszczania dodane do typowego treningu). To inna interwencja. Ponadto „od 10 serii tygodniowo” bez „na grupę mięśniową”. Nie trafiło do statementów twierdzeń, ale jest powielane w opisie źródła.
- **PROPONOWANA KOREKTA:** „…a przyrost mięśni większa objętość (od ok. 10 serii tygodniowo na grupę mięśniową) oraz trening ekscentryczny (w porównaniu z wyłącznie koncentrycznym)”. Po uzyskaniu pełnego tekstu potwierdzić dokładne brzmienie.
- **Pewność oceny:** umiarkowana (brak pełnego tekstu). **Weryfikacja:** dossier G1 [SEARCH acsm.org Science Spotlight; źródła wtórne].

#### S-02 · MEDIUM · SRC-0204 · pole `summary.pl/en`
- **OBECNIE:** „Kilka serii wiązało się z wyraźnie większym przyrostem masy mięśniowej niż jedna seria, z efektem większym o ok. 40% (…). Efekty rosły wraz z liczbą serii (1, 2-3, 4-6 serii na ćwiczenie), choć różnica między 2-3 a 4-6 seriami nie była istotna statystycznie.”
- **PROBLEM:** Istotne było tylko porównanie „wiele vs jedna” (różnica ES 0,10; CI 0,02-0,19; p=0,016). Porównania 2-3 vs 1 i 4-6 vs 1 były trendami (p≈0,09). „40%” to względna różnica wielkości efektu, nie „40% większy przyrost masy mięśniowej”. Opis sugeruje wyraźny, stopniowany gradient.
- **PROPONOWANA KOREKTA:** „Kilka serii na ćwiczenie wiązało się z istotnie, choć umiarkowanie większą wielkością efektu hipertrofii niż jedna seria (względnie ok. 40% większy efekt standaryzowany). Porównania poszczególnych kategorii (2-3 i 4-6 serii vs 1) były jedynie trendami.”
- **Pewność:** wysoka co do kierunku; **Weryfikacja:** dossier G2 [SEARCH abstrakt].

#### S-03 · MEDIUM (proces) · SRC-0407, SRC-0500 · pole `status`
- **OBECNIE:** `status: active`.
- **PROBLEM:** Do publikacji opublikowano korektę (BJSM 2020;54(19):e7; PMID 32943392). Treść korekty wg dostępnych streszczeń prawdopodobnie dotyczy ujawnienia konfliktu interesów (NIEZWERYFIKOWANE). Wg reguły 16.7 Mythlift źródło skorygowane wymaga przeglądu używających go twierdzeń (CL-PROT-003, CL-PLAT-003), a raport „Przeglądy twierdzeń” w eksporcie stwierdza, że „wszystkie źródła mają status active”.
- **PROPONOWANA KOREKTA:** `status: corrected` + odnotowanie korekty w polu opisu; przegląd CL-PROT-003 i CL-PLAT-003 (patrz C-17, C-19).
- **Pewność:** wysoka co do istnienia korekty; niska co do jej treści. **Weryfikacja:** [SEARCH https://pubmed.ncbi.nlm.nih.gov/32943392/].

#### S-04 · LOW · SRC-0408 vs SRC-0508 · pola `type`, `limitations`
- **PROBLEM:** Ta sama publikacja (Lamon 2021) opisana jako `mechanistic` i `rct`, z różnymi summary; zdanie w SRC-0508.limitations („spadek testosteronu wydawał się dotyczyć głównie mężczyzn…”) – NIEZWERYFIKOWANE (może być dopowiedzeniem).
- **PROPONOWANA KOREKTA:** scalić rekordy; typ: randomizowane badanie crossover o charakterze mechanistycznym; zdanie o testosteronie zastąpić neutralnym „zmianę testosteronu podano dla całej grupy mieszanej płciowo”, chyba że pełny tekst potwierdzi analizę wg płci.

#### S-05 · LOW (systemowe) · duplikaty rekordów
- 8 publikacji ma po 2-3 rekordy SRC (0100/0211/0401; 0105/0203/0403; 0106/0304/0404; 0108/0300/0405; 0201/0402; 0406/0504; 0407/0500; 0408/0508) z niespójnymi listami autorów, typami, measurement i summary. Ryzyko: korekta/retrakcja odnotowana w jednym rekordzie nie obejmie pozostałych (przykład: S-03). **Korekta:** jeden rekord na publikację.

#### S-06 · LOW · SRC-0308 · pole `population`
- Brak informacji, że uczestnicy byli wcześniej nietrenujący; istotne dla CL-DLD-003 (twierdzenie o osobach trenujących). **Korekta:** dopisać „wcześniej nietrenujący”.

#### S-07 · LOW · SRC-0406 · pole `population`
- Sformułowanie sugeruje, że wszystkie badania miały grupę bez deficytu; tylko część analiz miała równoległą kontrolę (SRC-0504 opisuje to poprawnie). **Korekta:** ujednolicić z SRC-0504 i scalić.

#### S-08 · LOW · SRC-0503 · pole `population/limitations`
- Brak informacji, że uczestnicy nie byli wytrenowani oporowo, i o komentarzu Witard & Mettler 2024 (ograniczona generalizacja). **Korekta:** dopisać.

## 0.3 AUDYT CLAIM → SOURCE (68 twierdzeń)

Kolumna QUALITY: „Mythlift X → recenzent Y” (skala A–D Mythlift; A wysoka, B umiarkowana, C niska/wstępna, D bardzo niska/brak bezpośrednich badań). OVERCLAIM: TAK / CZĘŚCIOWO / NIE. AKTUALNOŚĆ: AKTUALNE / DO UZUPEŁNIENIA (są nowsze dowody zgodne, niecytowane) / CZĘŚCIOWO NIEAKTUALNE (jakiś element zdezaktualizowany). Szczegóły problemów C-xx w sekcji 0.4.

| CLAIM ID | ŹRÓDŁO (rola → wsparcie) | SUPPORT (łącznie) | QUALITY | OVERCLAIM | AKTUALNOŚĆ | UWAGI |
|---|---|---|---|---|---|---|
| CL-TENS-001 | SRC-0109 sup → PARTIAL/DIRECT; SRC-0103 ctx → INDIRECT; SRC-0101 ctx → INDIRECT | PARTIAL | B → B/C (konsensus oparty głównie na modelach zwierzęcych i komórkowych; u ludzi pośrednio) | NIE („uznaje się”, „co najwyżej pomocnicze”) | AKTUALNE (zgodne z Roberts i in. 2023 Physiol Rev [WIEDZA]) | Bez problemów wymagających korekty. |
| CL-TENS-002 (mit) | SRC-0103 contra → PARTIAL/DIRECT (korelacje, 1 badanie); SRC-0109 ctx → INDIRECT | PARTIAL | B → B (po dodaniu West 2009/2010) | NIE | DO UZUPEŁNIENIA | C-01 (MEDIUM): pominięte dowody eksperymentalne (West 2010 – wspierające; Rønnestad 2011 – przeciwne). |
| CL-TENS-003 (niezalecane) | SRC-0109 sup → INDIRECT; SRC-0101 ctx → INDIRECT | INDIRECT | C → C | NIE | AKTUALNE | Poprawnie oznaczone jako wstępne. |
| CL-REPS-001 | SRC-0101 sup → DIRECT (do upadku); SRC-0102 sup → PARTIAL/INDIRECT; SRC-0103 sup → DIRECT (trenujący M); SRC-0100 sup → PARTIAL | PARTIAL/DIRECT | A → B | CZĘŚCIOWO („lub blisko niego” dla ~30% 1RM; „podobny” = brak istotnej różnicy) | DO UZUPEŁNIENIA (Lasevicius 2022; Lopez 2021) | C-02 (MEDIUM), C-03 (MEDIUM). |
| CL-REPS-002 | SRC-0101 sup → DIRECT; SRC-0102 sup → DIRECT; SRC-0100 sup → DIRECT; SRC-0103 ctx → PARTIAL | DIRECT | A → A/B (spójne; część przewagi = specyficzność testu 1RM, co Mythlift zaznacza) | NIE | AKTUALNE | Bez problemów. |
| CL-REPS-003 (mit) | SRC-0101 contra → DIRECT; SRC-0103 contra → DIRECT; SRC-0102 contra → PARTIAL | DIRECT | A → A/B | NIE | AKTUALNE | Dziedziczy zastrzeżenie C-02 (warunek wysiłku przy lekkich ciężarach), ale mit jest absolutny („tylko 8-12”) i jest fałszywy. |
| CL-DOMS-001 (mit) | SRC-0111 contra → INDIRECT; SRC-0110 contra → INDIRECT; SRC-0109 ctx → INDIRECT | INDIRECT | B → C (brak bezpośredniego testu „nasilenie DOMS vs przyrost”) | NIE (w statement) | DO UZUPEŁNIENIA (Flann 2011) | C-04 (MEDIUM). |
| CL-DOMS-002 (niezalecane) | SRC-0110 sup → PARTIAL; SRC-0109 sup → PARTIAL; SRC-0111 ctx → INDIRECT | PARTIAL | C → C | NIE („wydaje się”) | AKTUALNE (istnieje komentarz przeciwny w J Physiol 2016) | C-26 (LOW). |
| CL-DOMS-003 | SRC-0110 sup → DIRECT (nietrenujący, n=10); SRC-0111 ctx → PARTIAL | PARTIAL/DIRECT | C → C | CZĘŚCIOWO („zdrowi dorośli” – dane od 10 nietrenujących mężczyzn) | AKTUALNE | C-26 (LOW). |
| CL-EFF-001 | SRC-0105 sup → DIRECT (kierunek; RIR szacowane); SRC-0104 ctx → PARTIAL; SRC-0100 ctx → PARTIAL | PARTIAL/DIRECT | B → B/C | CZĘŚCIOWO (zależność monotoniczna vs możliwe wypłaszczenie przy 0-3 RIR) | DO UZUPEŁNIENIA (Refalo 2024 JSS: 0 vs 1-2 RIR podobnie [WIEDZA]; Lasevicius 2022) | C-27 (LOW). |
| CL-EFF-002 | SRC-0104 sup → DIRECT (upadek niekonieczny); SRC-0100 sup → PARTIAL; SRC-0105 ctx → PARTIAL | PARTIAL | B → B | CZĘŚCIOWO („kilka powtórzeń przed upadkiem” także dla lekkich ciężarów) | DO UZUPEŁNIENIA (Lasevicius 2022) | C-05 (MEDIUM). |
| CL-EFF-003 (mit) | SRC-0104 contra → DIRECT; SRC-0105 contra → DIRECT; SRC-0100 contra → PARTIAL | DIRECT | B → B | NIE | AKTUALNE | Bez problemów. |
| CL-RIR-001 | SRC-0107 sup → DIRECT (definicja skali), PARTIAL (trafność); SRC-0106 sup → PARTIAL; SRC-0105 ctx → INDIRECT | PARTIAL/DIRECT | B → B | NIE | AKTUALNE | C-28 (LOW). |
| CL-RIR-002 | SRC-0106 sup → DIRECT; SRC-0107 ctx → INDIRECT | DIRECT | B → B/C (eksploracyjna MA, I²≈98%) | NIE | AKTUALNE | C-29 (LOW): szczegóły „późniejsze serie” i „staż” niepotwierdzone. |
| CL-RIR-003 | SRC-0106 sup → INDIRECT; SRC-0105 ctx → INDIRECT | INDIRECT | D → D | NIE (jawnie „praktyka”) | AKTUALNE | Bez problemów. |
| CL-PROG-001 | SRC-0100 sup → PARTIAL; SRC-0108 sup → INDIRECT (brak porównania z brakiem progresji) | PARTIAL/INDIRECT | B → B dla „trening progresywny skuteczny”; C/D dla „muszą” (konieczność niebadana) | TAK („muszą”) | AKTUALNE | C-06 (MEDIUM). |
| CL-PROG-002 | SRC-0108 sup → DIRECT; SRC-0100 ctx → INDIRECT | DIRECT | C → C | NIE | DO UZUPEŁNIENIA (Chaves 2024 – nietrenujący, zgodne) | Bez problemów wymagających korekty. |
| CL-PROG-003 (mit) | SRC-0108 contra → DIRECT/PARTIAL; SRC-0100 ctx → INDIRECT | DIRECT | B → B | NIE | AKTUALNE | Bez problemów. |
| CL-CONS-001 | SRC-0102 sup → PARTIAL/DIRECT; SRC-0100 sup → PARTIAL | PARTIAL | B → B (masa) / B (siła – ale różnice nie „niewielkie”) | CZĘŚCIOWO (siła) | AKTUALNE | C-07 (MEDIUM). |
| CL-CONS-002 (mit) | SRC-0102 contra → DIRECT; SRC-0100 contra → DIRECT/PARTIAL | DIRECT | B → B | NIE | AKTUALNE | Bez problemów. |
| CL-VOL-001 | SRC-0202 sup → DIRECT; SRC-0201 ctx → INDIRECT; SRC-0200 ctx → INDIRECT | DIRECT | B → B/C (1 przegląd bez MA; konwencja 0-4 RIR) | NIE | AKTUALNE | Bez problemów (konwencja jawnie oznaczona). |
| CL-VOL-002 | SRC-0200 sup → PARTIAL (ciągła zależność istotna, kategorie tylko trend); SRC-0201 sup → PARTIAL; SRC-0211 sup → DIRECT (≥10 serii) | PARTIAL | B → B (kierunek) / C (konkretne progi) | CZĘŚCIOWO (próg „≥10 vs <5” jako ustalony wynik; „efektywnych”) | AKTUALNE | C-08 (MEDIUM). |
| CL-VOL-003 | SRC-0203 sup → PARTIAL; SRC-0211 ctx → INDIRECT; SRC-0202 ctx → INDIRECT | PARTIAL | C → C | NIE | AKTUALNE | Bez problemów. |
| CL-VOL-004 | SRC-0201 sup → DIRECT/PARTIAL | PARTIAL | C → C | NIE | DO UZUPEŁNIENIA (preprint Remmert 2025: dla siły lepsze liczenie „direct”) | C-33 (LOW). |
| CL-DOSE-001 | SRC-0201 sup → DIRECT; SRC-0200 ctx → PARTIAL; SRC-0211 ctx → INDIRECT | DIRECT | B → B | NIE | AKTUALNE | Bez problemów. |
| CL-DOSE-002 | SRC-0204 sup → PARTIAL; SRC-0205 sup → PARTIAL (opinia ekspercka); SRC-0211 sup → PARTIAL | PARTIAL | B → C | CZĘŚCIOWO („wyraźne przyrosty … w porównaniu z brakiem treningu”) | DO UZUPEŁNIENIA (Fyfe 2022 – przegląd minimalnej dawki) | C-09 (MEDIUM); dziedziczy S-02. |
| CL-DOSE-003 (mit) | SRC-0204 contra → DIRECT; SRC-0200 contra → DIRECT; SRC-0201 contra → DIRECT | DIRECT | B → B | NIE | AKTUALNE | Bez problemów. |
| CL-FREQ-001 | SRC-0206 sup → DIRECT; SRC-0201 sup → PARTIAL | DIRECT | B → B | NIE | AKTUALNE | Bez problemów. |
| CL-FREQ-002 | SRC-0207 sup → DIRECT; SRC-0201 sup → DIRECT; SRC-0211 ctx → PARTIAL | DIRECT | C → C | NIE | AKTUALNE (dowód przeciwny: Ochi 2018 – efekt częstotliwości przy wyrównanej objętości [tytuł SEARCH]) | Bez problemów. |
| CL-FREQ-003 (mit) | SRC-0206 contra → DIRECT; SRC-0201 contra → PARTIAL | DIRECT | B → B | NIE | AKTUALNE | Bez problemów. |
| CL-REST-001 | SRC-0208 sup → DIRECT; SRC-0210 sup → PARTIAL (przewaga tylko przód uda) | DIRECT | C → C | NIE | AKTUALNE (preprint 2025 u trenujących: trywialna różnica dla hipertrofii) | C-30 (LOW). |
| CL-REST-002 | SRC-0209 sup → DIRECT; SRC-0210 sup → DIRECT | DIRECT | B → B/C (przegląd bez MA, heterogeniczne protokoły) | CZĘŚCIOWO („dają” vs „wydają się potrzebne”) | AKTUALNE (preprint 2025: przewaga siłowa >60 s, SMD −0,74) | C-31 (LOW). |
| CL-REST-003 (mit) | SRC-0208 contra → DIRECT (outcome), NONE (mechanizm); SRC-0210 contra → DIRECT | DIRECT | B → B | NIE | AKTUALNE | C-32 (LOW). |
| CL-AUTO-001 | SRC-0302 sup → PARTIAL (RPE+VBT łącznie); SRC-0303 sup → DIRECT (1 RCT, n=21, MBI) | PARTIAL | B → C (hipertrofia), B/C (siła) | NIE (ostrożne „może nieco większy”) | DO UZUPEŁNIENIA (NMA 2025 J Exerc Sci Fit – RPE ≥ %1RM) | C-10 (MEDIUM). |
| CL-AUTO-002 | SRC-0304 sup → PARTIAL | PARTIAL | C → C | NIE | AKTUALNE | C-42 (LOW). |
| CL-AUTO-003 (mit) | SRC-0304 contra → PARTIAL; SRC-0303 contra → DIRECT; SRC-0302 contra → PARTIAL/DIRECT | DIRECT | B → B | NIE | AKTUALNE | Bez problemów. |
| CL-DPRG-001 | SRC-0300 sup → PARTIAL (nie testowano podwójnej progresji jako schematu); SRC-0301 sup → PARTIAL (zastąpione stanowisko) | PARTIAL | C → C/D | NIE | CZĘŚCIOWO NIEAKTUALNE (ACSM 2009 zastąpione; „jedyne badanie z randomizacją” – istnieje Chaves 2024) | C-11 (MEDIUM). |
| CL-DPRG-002 | SRC-0300 sup → DIRECT | DIRECT | C → C | TAK (w evidence_summary: „przedziały … wąskie”) | AKTUALNE | C-12 (MEDIUM). |
| CL-DPRG-003 (mit) | SRC-0300 contra → DIRECT; SRC-0301 contra → DIRECT (opinia) | DIRECT | B → B | NIE | AKTUALNE | C-34 (LOW). |
| CL-DPRG-004 | SRC-0301 sup → PARTIAL; SRC-0300 ctx → INDIRECT | PARTIAL | D → D | NIE | AKTUALNE | Bez problemów (ACSM zaleca mniejsze % dla małych grup mięśniowych – wzmacnia argument). |
| CL-DLD-001 | SRC-0305 sup → DIRECT (dla całkowitej przerwy); SRC-0306 ctx → INDIRECT | DIRECT/PARTIAL | C → C | NIE | CZĘŚCIOWO NIEAKTUALNE („jedyne badanie z randomizacją” – Sci Rep 2026) | C-13 (MEDIUM). |
| CL-DLD-002 | SRC-0306 sup → DIRECT (opis praktyki), PARTIAL (część normatywna); SRC-0305 ctx | PARTIAL | D → D | NIE | DO UZUPEŁNIENIA (Sci Rep 2026; Bell i in. – praktyczne zasady) | C-35 (LOW). |
| CL-DLD-003 (mit) | SRC-0305 contra → DIRECT (1 tydz.); SRC-0307 contra → PARTIAL (LBM, brak kontroli ciągłej); SRC-0308 contra → PARTIAL (nietrenujący) | PARTIAL/DIRECT | B → B (łącznie z Halonen 2024) | NIE | DO UZUPEŁNIENIA (Halonen 2024) | C-36 (LOW). |
| CL-RATE-001 | SRC-0309 sup → DIRECT (średni przyrost FFM/LBM u mężczyzn) | DIRECT/PARTIAL | B → B | CZĘŚCIOWO (0,15 kg/tydz. = wyliczenie; „duże różnice między osobami” – nie z tego źródła) | AKTUALNE | C-14 (MEDIUM). |
| CL-RATE-002 | SRC-0310 sup → PARTIAL; SRC-0311 sup → INDIRECT; SRC-0309 ctx → użyte mylnie | PARTIAL/INDIRECT | C → C/D | CZĘŚCIOWO („dużo wolniej”) | DO UZUPEŁNIENIA | C-15 (MEDIUM). |
| CL-RATE-003 (mit) | SRC-0309 contra → PARTIAL/DIRECT; SRC-0311 contra → INDIRECT | PARTIAL/DIRECT | B → B | NIE | AKTUALNE | C-44 (LOW): dziedziczy wyliczone 0,15 kg/tydz. |
| CL-CHG-001 | SRC-0405 sup → DIRECT (część o powtórzeniach); SRC-0401 ctx → INDIRECT | PARTIAL | D → D | NIE | DO UZUPEŁNIENIA (Chaves 2024) | Bez problemów (próg 3-4 tyg. jawnie jako praktyka). |
| CL-CHG-002 | SRC-0409 sup → DIRECT; SRC-0401 sup → PARTIAL | DIRECT | B → B | NIE | AKTUALNE | Bez problemów. |
| CL-CHG-003 (niezalecane) | SRC-0409 → INDIRECT; SRC-0410 → INDIRECT; SRC-0402 → INDIRECT; SRC-0401 ctx | INDIRECT | D → D | CZĘŚCIOWO („sama zmienność … nie zwiększa przyrostu mięśni” – dla całego mięśnia) | AKTUALNE | C-37 (LOW). |
| CL-CONF-001 (mit) | SRC-0412 contra → DIRECT; SRC-0410 contra → DIRECT/PARTIAL; SRC-0409 contra → INDIRECT (powinno być context); SRC-0411 ctx → poprawne | DIRECT | B → B | NIE | DO UZUPEŁNIENIA (Kassiano 2024 RCT u kobiet – wzmacnia) | C-38 (LOW). |
| CL-CONF-002 | SRC-0410 sup → DIRECT; SRC-0411 sup → DIRECT (regionalnie, testy wewnątrzgrupowe); SRC-0412 sup → PARTIAL | PARTIAL | C → C | CZĘŚCIOWO | CZĘŚCIOWO NIEAKTUALNE (Kassiano 2024 – brak przewagi zmienności) | C-16 (MEDIUM). |
| CL-PLAT-001 | SRC-0401/0402 sup → INDIRECT; pozostałe ctx → INDIRECT | INDIRECT | D → D | NIE (jawnie „kolejności nie badano”) | AKTUALNE | C-43 (LOW). |
| CL-PLAT-002 | SRC-0403 sup → PARTIAL; SRC-0404 sup → DIRECT; SRC-0401 ctx | PARTIAL/DIRECT | B → B | NIE | AKTUALNE | Bez problemów. |
| CL-PLAT-003 | SRC-0406 sup → DIRECT (LM); SRC-0407 sup → PARTIAL | PARTIAL | B → B/C | CZĘŚCIOWO (interpretacja CI; „masa mięśniowa”) | DO UZUPEŁNIENIA (Nunes 2022; Tagawa 2021) | C-17 (MEDIUM); S-03. |
| CL-PLAT-004 | SRC-0408 sup → DIRECT (1. zdanie), INDIRECT (regeneracja i postępy) | PARTIAL | C → C | CZĘŚCIOWO | DO UZUPEŁNIENIA (Saner 2020 J Physiol) | C-18 (MEDIUM). |
| CL-PROT-001 (mit) | SRC-0502 contra → PARTIAL (dane skonfundowane; Beale 2016); SRC-0501 contra → PARTIAL | PARTIAL | B → B (łącznie z Casuso & Goossens 2025) | NIE | DO UZUPEŁNIENIA | C-39 (LOW). |
| CL-PROT-002 | SRC-0501 sup → DIRECT (liczby zalecenia); SRC-0503 ctx → PARTIAL | PARTIAL/DIRECT | C → C | NIE | AKTUALNE (Askow 2025: rozkład bez wpływu na dzienne MyoPS – zgodne z „mniejsze znaczenie”) | Bez problemów. |
| CL-PROT-003 | SRC-0500 sup → PARTIAL (kierunek DIRECT; plateau – nadmierna precyzja); SRC-0501 sup → DIRECT (zakres ekspercki) | PARTIAL | B → B (kierunek) / C (próg) | CZĘŚCIOWO (precyzja progu; interpretacja CI) | DO UZUPEŁNIENIA (Nunes 2022; Tagawa 2021 – zależność raczej stopniowa) | C-19 (MEDIUM); S-03. |
| CL-PROT-004 (mit) | SRC-0503 contra → DIRECT (mechanistycznie), PARTIAL („do budowy mięśni”); SRC-0501 ctx | PARTIAL/DIRECT | B → B/C | NIE | AKTUALNE (komentarz Witard & Mettler 2024) | Bez problemów wymagających korekty. |
| CL-ENRG-001 | SRC-0504 sup → DIRECT (LM, średnia grupowa); SRC-0505 ctx → INDIRECT | DIRECT/PARTIAL | B → B | CZĘŚCIOWO („podobny przyrost siły”; applicability) | AKTUALNE | C-20 (MEDIUM). |
| CL-ENRG-002 | SRC-0505 sup → PARTIAL (liczba NIEZWERYFIKOWANA) | PARTIAL | D → C/D (istnieje małe RCT u trenujących – Helms 2023) | CZĘŚCIOWO („większa nadwyżka dodaje więcej tłuszczu niż mięśni” – kategorycznie) | CZĘŚCIOWO NIEAKTUALNE („brak bezpośrednich badań”) | C-21 (MEDIUM). |
| CL-ENRG-003 (mit) | SRC-0506 contra → PARTIAL/DIRECT (LBM; młodzi mężczyźni z nadwagą); SRC-0504 ctx | PARTIAL | B → B/C | NIE (mit absolutny, obalony) | DO UZUPEŁNIENIA (Barakat 2020 [WIEDZA]) | C-22 (MEDIUM). |
| CL-SLEEP-001 | SRC-0507 sup → DIRECT (opis), PARTIAL (wniosek „chronić mięśnie”); SRC-0508 ctx → INDIRECT | PARTIAL | C → C | CZĘŚCIOWO (FFM → „mięśnie”) | DO UZUPEŁNIENIA (Wang 2018 Sleep – replikacja kierunku) | C-23 (MEDIUM). |
| CL-SLEEP-002 | SRC-0508 sup → DIRECT; SRC-0507 ctx → INDIRECT | DIRECT | C → C | NIE | DO UZUPEŁNIENIA (Saner 2020) | C-40 (LOW). |
| CL-PAIN-001 | SRC-0509 sup → DIRECT (przebieg), PARTIAL (zalecenia – opinia ekspercka) | PARTIAL/DIRECT | B → B (przebieg) / C (zalecenia treningowe) | NIE | AKTUALNE (przebieg); mechanizm – patrz karty/pytania | C-41 (LOW). |
| CL-PAIN-002 | SRC-0510 sup → PARTIAL (tendinopatia Achillesa, rehabilitacja); SRC-0509 ctx → INDIRECT | PARTIAL | C → C/D | TAK („nie gorsze”) | AKTUALNE | C-24 (MEDIUM). |
| CL-PAIN-003 | SRC-0509 sup → INDIRECT; SRC-0510 ctx → INDIRECT | INDIRECT | D → D | NIE | AKTUALNE | Bez problemów (bezpieczne, jawnie oparte na praktyce). |
| CL-PAIN-004 | SRC-0511 sup → PARTIAL/INDIRECT (tylko kręgosłup); SRC-0509 ctx → INDIRECT | PARTIAL/INDIRECT | D → D | TAK (triaż „112/SOR” dla objawów, które źródło kwalifikuje jako pilne, a nie nagłe) | DO UZUPEŁNIENIA (ACSM Riebe 2015; wytyczne rabdomiolizy wysiłkowej 2021) | C-25 (HIGH). |

**Podsumowanie audytu twierdzeń:** 68 twierdzeń; wsparcie łączne: DIRECT 22, DIRECT/PARTIAL 13, PARTIAL 24, PARTIAL/INDIRECT 3, INDIRECT 6, NONE 0 (żadne twierdzenie nie jest całkowicie pozbawione wsparcia, ale 6 opiera się wyłącznie na dowodach pośrednich – w 5 z nich Mythlift poprawnie sygnalizuje to pewnością C/D; wyjątek: CL-DOMS-001). Certainty Mythlift oceniam jako zawyżoną w 7 twierdzeniach (CL-REPS-001, CL-DOMS-001, CL-DOSE-002, CL-AUTO-001 [część o mięśniach], CL-PROG-001 [dla „muszą”], CL-VOL-002 [progi], CL-PROT-003 [próg]) i jako graniczną w 2 (CL-RIR-002, CL-REST-002). Problemy: HIGH 1, MEDIUM 24 (w 23 twierdzeniach; CL-REPS-001 ma dwa), LOW 19 (patrz 0.4).

## 0.4 Problemy na poziomie twierdzeń (C-xx)

Każde pytanie, które powtarza treść twierdzenia obciążoną problemem, dziedziczy ten problem (sprawdzane w partiach 1-22).

#### C-25 · HIGH · CL-PAIN-004 · pola `statement`, `sources`, `evidence_summary` (bezpieczeństwo)
- **Source:** SRC-0511 (supports), SRC-0509 (context).
- **OBECNIE:** „Niektóre objawy związane z treningiem wymagają pilnej pomocy medycznej, a nie odpoczynku czy zmiany ćwiczenia: ból lub ucisk w klatce piersiowej, duszność, zawroty głowy lub omdlenie w trakcie wysiłku; ciemny (brunatny) mocz z silnym bólem i obrzękiem mięśni po treningu; nagły ostry ból z trzaskiem, szybkim obrzękiem lub utratą funkcji stawu albo mięśnia; drętwienie, osłabienie kończyny, zaburzenia czucia w okolicy krocza lub problemy z kontrolą pęcherza; ból z gorączką, zaczerwienieniem i ociepleniem okolicy albo ból nocny niezwiązany z ruchem.” (karta KC-M5-04 i model triażu: kategoria 4 = „112 lub SOR, natychmiast”).
- **PROBLEM:** (1) Jedyne źródło „supports” (Finucane 2020) dotyczy wyłącznie poważnych patologii kręgosłupa; nie obejmuje objawów sercowych przy wysiłku, rabdomiolizy wysiłkowej, zerwań ani miejscowej infekcji kończyny – dla tych elementów wsparcie = NONE (źródło nie wspiera kluczowego twierdzenia → HIGH). (2) Źródło samo rozróżnia stany **nagłe** (np. zespół ogona końskiego – działanie natychmiastowe) i **pilne** (np. podejrzenie przerzutów – ocena w ciągu dni). Mythlift umieszcza w kategorii „112/SOR natychmiast” także „ból nocny niezwiązany z ruchem” oraz izolowane „drętwienie” – to nadmierny triaż sprzeczny z logiką cytowanego źródła. (3) Adwersaryjnie: lista pomija nagły, bardzo silny ból głowy w trakcie wysiłku (np. przy dźwiganiu z manewrem Valsalvy), który wymaga pilnej pomocy – dla aplikacji o treningu siłowym to istotne pominięcie (lista jest opisana jako „niektóre objawy”, więc to luka, nie błąd). (4) Ból/ucisk w klatce, duszność, omdlenie przy wysiłku oraz brunatny mocz z bólem i obrzękiem mięśni – kwalifikacja jako stany nagłe jest merytorycznie poprawna, ale wymaga innych źródeł (ACSM – objawy sugerujące chorobę sercowo-naczyniową, Riebe i in. 2015; wytyczne rabdomiolizy wysiłkowej O'Connor i in. 2021).
- **PROPONOWANA KOREKTA:** Rozdzielić kategorię 4 na: **„Natychmiast (112/SOR)”**: ból/ucisk w klatce piersiowej, duszność nieproporcjonalna do wysiłku, omdlenie lub zawroty głowy przy wysiłku; nagły, bardzo silny ból głowy w trakcie wysiłku; brunatny mocz z silnym bólem i obrzękiem mięśni; zaburzenia czucia w kroczu lub nowe problemy z kontrolą pęcherza/jelit; nagłe osłabienie kończyny lub twarzy, zaburzenia mowy; nagły trzask z szybkim obrzękiem i utratą funkcji (SOR/ortopeda tego samego dnia). **„Pilnie do lekarza (tego samego lub następnego dnia)”**: ból z gorączką, zaczerwienieniem i ociepleniem okolicy; ból nocny niezwiązany z ruchem, budzący ze snu, zwłaszcza z niewyjaśnioną utratą masy ciała; utrzymujące się drętwienie lub mrowienie kończyny. Źródła: dodać Riebe i in. 2015 (MSSE, PMID 26473759), O'Connor i in. 2021 (Curr Sports Med Rep 20(3):169-178), a SRC-0511 zostawić jako źródło dla objawów z kręgosłupa. Treść nadal wymaga recenzji fizjoterapeuty/lekarza (co eksport słusznie zaznacza).
- **Pewność oceny:** wysoka co do zakresu źródła; umiarkowana co do proponowanej kwalifikacji (wymaga recenzji klinicznej). **Weryfikacja:** [SEARCH https://www.jospt.org/doi/10.2519/jospt.2020.9971 ; https://pubmed.ncbi.nlm.nih.gov/26473759/ ; https://journals.lww.com/acsm-csmr/fulltext/2021/03000/clinical_practice_guidelines_for_exertional.10.aspx].

#### C-01 · MEDIUM · CL-TENS-002 · pole `evidence_summary`, `sources`
- **OBECNIE:** „W badaniu z randomizacją u 49 trenujących mężczyzn wielkość skoku stężenia hormonów po treningu nie korelowała ani z przyrostem mięśni, ani z przyrostem siły. (…) Pewność umiarkowana: wyniki są spójne, ale pochodzą z niewielu badań (…)”.
- **PROBLEM:** Jedyne źródło „contradicts” to analiza korelacyjna w jednym badaniu. Pominięto bezpośrednie badania eksperymentalne: West i in. 2009/2010 (manipulacja ostrym wyrzutem hormonów – brak wpływu na MPS i hipertrofię; wspierające) oraz Rønnestad i in. 2011 (podniesienie hormonów ćwiczeniami nóg – większy przyrost CSA zginaczy łokcia; przeciwne, później kwestionowane). Etykieta „mit” jest uzasadniona całością korpusu, ale evidence_summary nie przedstawia obu stron (ryzyko cherry-pickingu).
- **PROPONOWANA KOREKTA:** Dodać West i in. 2010 (J Appl Physiol) jako „contradicts” i Rønnestad 2011 (Eur J Appl Physiol) jako dowód sprzeczny; evidence_summary: „Większość badań, w tym eksperymenty manipulujące ostrym wyrzutem hormonów, nie wykazała wpływu na przyrost mięśni; pojedyncze badanie z przeciwnym wynikiem jest kwestionowane.”
- **Pewność:** wysoka. **Weryfikacja:** [SEARCH https://link.springer.com/article/10.1007/s00421-011-1860-0 ; https://link.springer.com/article/10.1007/s00421-011-2150-6].

#### C-02 · MEDIUM · CL-REPS-001 · pole `statement`
- **OBECNIE:** „gdy każda seria kończy się na upadku mięśniowym lub blisko niego, lżejsze ciężary (od około 30% 1RM …) i cięższe ciężary (…) dają podobny przyrost mięśni.”
- **PROBLEM:** Główne dowody (Schoenfeld 2017 – kryterium: wszystkie serie do chwilowego upadku; Morton 2016 – do upadku) dotyczą serii **do upadku**. Rozszerzenie na „blisko upadku” jest dla ciężkich ciężarów rozsądne, ale dla ~30% 1RM nie ma bezpośredniego wsparcia; Lasevicius i in. 2022 (JSCR; 25 nietrenujących, 8 tyg.): przy 30% 1RM seria do upadku dawała większą hipertrofię niż seria przerwana (~20 z ~34 możliwych powtórzeń), a przy 80% 1RM – nie. Evidence_summary zawiera zastrzeżenie („zwłaszcza przy lekkich ciężarach”), statement już nie.
- **PROPONOWANA KOREKTA:** „…gdy serie kończą się na upadku mięśniowym lub bardzo blisko niego – przy lekkich ciężarach (ok. 30-60% 1RM) wymaga to zwykle dojścia do upadku lub 0-1 powtórzenia przed nim…”.
- **Pewność:** wysoka. **Weryfikacja:** [SEARCH https://pubmed.ncbi.nlm.nih.gov/31895290/ ; dossier G1].

#### C-03 · MEDIUM · CL-REPS-001 · pole `certainty`
- **OBECNIE:** `certainty: A` („Proponowana pewność wysoka, bo wyniki są spójne w kilku niezależnych syntezach”).
- **PROBLEM:** „Podobny przyrost” opiera się na braku istotnej różnicy w metaanalizach małych, nieblindowanych, krótkich (6-12 tyg.) badań, bez formalnego testu równoważności; sieciowa MA (Currier 2023) grupowała ciężary w szerokie kategorie i nie kontrolowała bliskości upadku (dla ~30% 1RM wsparcie pośrednie); mało danych u zaawansowanych i dla lekkich ciężarów bez upadku. Wg kryteriów typu GRADE (ryzyko biasu, nieprecyzyjność, pośredniość) pewność umiarkowana.
- **PROPONOWANA KOREKTA:** `certainty: B`; evidence_summary: „brak istotnej różnicy w kilku syntezach; formalnej równoważności nie testowano”.
- **Pewność:** umiarkowana (ocena metodologiczna).

#### C-04 · MEDIUM · CL-DOMS-001 · pole `certainty`, `sources`
- **OBECNIE:** `certainty: B`; źródła: Nosaka 2002 (DOMS vs markery uszkodzenia po jednej sesji), Damas 2016 (uszkodzenie vs MyoPS), Wackerhage 2019 (kontekst).
- **PROBLEM:** Żadne z przypisanych źródeł nie testuje, czy nasilenie zakwasów przewiduje długoterminowy przyrost mięśni – wszystkie są pośrednie (sam claim to przyznaje). Mit jest logicznie mało prawdopodobny i sprzeczny z danymi pośrednimi, ale pewność B jest zawyżona względem bezpośredniości.
- **PROPONOWANA KOREKTA:** `certainty: C` albo dodać Flann i in. 2011 (J Exp Biol – grupa wstępnie zaadaptowana, bez uszkodzeń i bólu, uzyskała podobną hipertrofię) [WIEDZA – do potwierdzenia] jako bardziej bezpośredni dowód i wtedy utrzymać B.
- **Pewność:** umiarkowana.

#### C-05 · MEDIUM · CL-EFF-002 · pole `statement`
- **OBECNIE:** „Serie zakończone kilka powtórzeń przed upadkiem dają podobny albo tylko nieco mniejszy przyrost.”
- **PROBLEM:** „Kilka” (PL: zwykle 3-9; EN „a few”) jest szersze niż dane: RCT u trenujących (Refalo 2024 [WIEDZA]) porównywały 0 vs 1-2 RIR; metaregresja Robinson 2024 sugeruje spadek przyrostu wraz z rosnącym RIR; przy lekkich ciężarach (~30% 1RM) seria przerwana wyraźnie wcześniej dawała mniejszą hipertrofię (Lasevicius 2022). Karta KC-M1-04 poprawnie mówi o „1-3 powtórzeniach”.
- **PROPONOWANA KOREKTA:** „Serie zakończone ok. 1-3 powtórzenia przed upadkiem (przy umiarkowanych i dużych ciężarach) dają podobny albo tylko nieco mniejszy przyrost; przy lekkich ciężarach bliskość upadku ma większe znaczenie.”
- **Pewność:** wysoka.

#### C-06 · MEDIUM · CL-PROG-001 · pole `statement`
- **OBECNIE:** „Żeby masa i siła mięśni rosły przez kolejne miesiące, zdrowi dorośli muszą stopniowo zwiększać wymagania treningu w miarę adaptacji…”.
- **PROBLEM:** Konieczność („muszą”) nie była testowana – Mythlift sam pisze, że „niewiele badań porównuje wprost trening z progresją i bez niej”. SRC-0108 (Plotkin) nie porównuje progresji z brakiem progresji (obie grupy progresowały) → INDIRECT. ACSM zaleca trening progresywny (PARTIAL). Siła języka przekracza dowody; ponadto przy treningu blisko upadku z tym samym RIR wymagania rosną automatycznie (ciężar/powtórzenia rosną wraz z adaptacją).
- **PROPONOWANA KOREKTA:** „Żeby masa i siła mięśni rosły przez kolejne miesiące, zdrowym dorosłym zaleca się stopniowe zwiększanie wymagań treningu w miarę adaptacji (…), tak żeby serie pozostawały wymagające. Zasada jest zgodna z całą literaturą, choć jej konieczności nie testowano wprost.”
- **Pewność:** wysoka.

#### C-07 · MEDIUM · CL-CONS-001 · pole `statement`
- **OBECNIE:** „…bardzo różne rozsądne programy siłowe (…) zwiększają masę i siłę mięśni w porównaniu z brakiem treningu, a różnice między nimi są zwykle niewielkie.”
- **PROBLEM:** Dla hipertrofii – zgodne ze źródłami. Dla siły różnice między programami nie są „niewielkie”: w NMA Currier 2023 i w ACSM 2026 ciężar (≥80% 1RM) wyraźnie zwiększa przyrost siły; Mythlift sam to zaznacza w evidence_summary („wyjątki to m.in. ciężar dla siły”), ale nie w statement. Łączenie masy i siły spłaszcza wniosek.
- **PROPONOWANA KOREKTA:** „…a różnice między nimi w przyroście masy mięśniowej są zwykle niewielkie; dla siły maksymalnej większe znaczenie ma ciężar.”
- **Pewność:** wysoka.

#### C-08 · MEDIUM · CL-VOL-002 · pole `statement`, `evidence_summary`
- **OBECNIE:** „W badanych zakresach ok. 10 lub więcej serii efektywnych na mięsień tygodniowo daje większe przyrosty niż mniej niż 5 serii.”
- **PROBLEM:** W SRC-0200 porównanie kategorii (<5 / 5-9 / 10+) było tylko trendem (P=0,074); istotna była zależność ciągła (P=0,002). ACSM 2026 wskazuje ≥10 serii na grupę mięśniową/tydz. jako czynnik zwiększający hipertrofię (bez progu „<5”). Pelland 2026 opisuje krzywą ciągłą z malejącymi przyrostami, nie progi. Źródła liczyły serie (lub serie frakcyjne), a nie „serie efektywne” (konstrukcja Mythlift). Twierdzenie podaje progowe porównanie jako ustalony wynik; część pytań powtarza je jako „badania pokazują”.
- **PROPONOWANA KOREKTA:** „U dorosłych trenujących siłowo więcej serii tygodniowo na grupę mięśniową wiąże się z większym przyrostem masy mięśniowej (z malejącymi korzyściami). Stanowisko ACSM wskazuje ok. 10 lub więcej serii tygodniowo jako objętość sprzyjającą hipertrofii; porównania konkretnych progów (np. <5 vs ≥10) są mało precyzyjne.”
- **Pewność:** wysoka. **Weryfikacja:** dossier G2 [SEARCH abstrakt SRC-0200].

#### C-09 · MEDIUM · CL-DOSE-002 · pola `statement`, `certainty`
- **OBECNIE:** „Nawet mała objętość treningu, np. ok. 4 serie efektywne na grupę mięśniową tygodniowo albo 1 seria na ćwiczenie, daje wyraźne przyrosty masy mięśniowej i siły w porównaniu z brakiem treningu…”; `certainty: B`.
- **PROBLEM:** Krieger 2010 nie porównywał z brakiem treningu (analiza przed-po; dla 1 serii mała wielkość efektu, ES ~0,24 [SEARCH – dossier G2]); próg ~4 serii to rekomendacja przeglądu narracyjnego (Mythlift to zaznacza w evidence_summary). „Wyraźne” sugeruje większy efekt niż wynika z danych dla 1 serii; pewność B dla minimalnej dawki jest zawyżona. Kierunek (mała dawka działa, zwłaszcza u początkujących) jest prawdziwy (ACSM: jakikolwiek trening > brak treningu).
- **PROPONOWANA KOREKTA:** „…daje mierzalne przyrosty masy mięśniowej i siły, zwłaszcza u osób początkujących (…)”; `certainty: C`.
- **Pewność:** umiarkowana-wysoka.

#### C-10 · MEDIUM · CL-AUTO-001 · pola `evidence_summary`, `certainty`
- **OBECNIE:** „Metaanaliza 6 badań nie wykazała istotnej różnicy w przyroście 1RM między autoregulacją ciężaru a stałymi procentami: średnio ok. 2 kg (ok. 4 lb) (…) W badaniu z randomizacją (…) obie grupy zyskały podobnie dużo siły i grubości mięśni.”
- **PROBLEM:** (1) Oszacowanie 2,07 kg (CI −0,32 do 4,46) łączy autoregulację RPE/RIR i opartą na prędkości (VBT); twierdzenie dotyczy wyłącznie RIR/RPE. (2) Część o przyroście mięśni opiera się praktycznie na jednym RCT (Helms 2018, n=21, analiza MBI – metoda krytykowana). (3) 2,07 kg ≈ 4,6 lb, nie „ok. 4 lb” (LOW). Pewność B jest zawyżona dla hipertrofii.
- **PROPONOWANA KOREKTA:** „Metaanaliza 6 badań autoregulacji ciężaru (RPE i prędkość sztangi łącznie) (…) ok. 2 kg (ok. 4,5 lb) (…) Dane o przyroście mięśni pochodzą praktycznie z jednego małego badania.”; rozdzielić pewność: siła B/C, mięśnie C. Można dodać NMA 2025 (J Exerc Sci Fit, PMID 40791980) wskazującą, że RPE nie jest gorsze od %1RM.
- **Pewność:** wysoka.

#### C-11 · MEDIUM · CL-DPRG-001 · pole `evidence_summary`, `sources`
- **OBECNIE:** „W jedynym badaniu z randomizacją, które porównało te dwa sposoby (43 osoby trenujące, 8 tygodni) (…) Regułę zwiększania ciężaru o 2-10% po przekroczeniu docelowej liczby powtórzeń zaleca stanowisko towarzystwa naukowego z 2009 roku.”
- **PROBLEM:** (1) Stanowisko ACSM 2009 zostało zastąpione przez ACSM 2026 (sam Mythlift używa ACSM 2026 gdzie indziej); nie ustalono, czy nowe stanowisko utrzymuje regułę 2-10% (NIEZWERYFIKOWANE) – evidence_summary tego nie sygnalizuje. (2) Reguła ACSM 2009 brzmi: +2-10%, gdy wykonuje się 1-2 powtórzenia ponad cel w **dwóch kolejnych sesjach**; wersja Mythlift („gdy we wszystkich seriach osiągnie się górną granicę zakresu”) to adaptacja, nie treść stanowiska. (3) „Jedyne badanie z randomizacją” – istnieje Chaves i in. 2024 (Int J Sports Med; 39 nietrenujących, projekt wewnątrzosobniczy, 10 tyg.; podobne adaptacje) – poprawnie: „jedyne u osób trenujących”.
- **PROPONOWANA KOREKTA:** „W badaniu z randomizacją u 43 osób trenujących (oraz w badaniu u osób nietrenujących) oba sposoby dały podobny przyrost. Zbliżoną regułę (+2-10%, gdy przez dwie kolejne sesje wykonuje się 1-2 powtórzenia ponad cel) podawało stanowisko ACSM z 2009 r., zastąpione w 2026 r.; podwójna progresja jest praktyczną adaptacją tej reguły.”
- **Pewność:** wysoka (1, 3); umiarkowana (2 – brzmienie z abstraktu).

#### C-12 · MEDIUM · CL-DPRG-002 · pole `evidence_summary`
- **OBECNIE:** „Różnice między grupami były małe, a przedziały niepewności dla większości wyników wąskie.”
- **PROBLEM:** Przedziały były szerokie (CI90% dla 1RM −2,4 do 7,8 kg; dla prostego uda −0,5 do 5,8 mm) i obejmują zarówno brak różnicy, jak i różnice praktycznie istotne; rekord SRC-0108 sam mówi o różnicach „małych i niepewnych”. Wewnętrzna sprzeczność i nadinterpretacja precyzji.
- **PROPONOWANA KOREKTA:** „Różnice między grupami były małe, ale przedziały niepewności szerokie, więc badanie nie wyklucza drobnych, praktycznie istotnych różnic.”
- **Pewność:** wysoka. **Weryfikacja:** dossier G3a [SEARCH].

#### C-13 · MEDIUM · CL-DLD-001 · pole `evidence_summary` (aktualność)
- **OBECNIE:** „Jedyne badanie z randomizacją (39 osób) nie wykazało, by tydzień przerwy zwiększał przyrost mięśni…”.
- **PROBLEM:** W 2026 r. opublikowano RCT (Scientific Reports, projekt wewnątrzosobniczy, 19 nietrenujących mężczyzn, 8 tyg.), w którym deload polegał na zmniejszeniu objętości i częstotliwości (a nie całkowitej przerwie); oba warunki dały przyrosty, różnice minimalne. To częściowo spełnia revision_trigger twierdzenia („RCT nad deloadem w formie lżejszego treningu”).
- **PROPONOWANA KOREKTA:** „Jedyne badanie z randomizacją u osób trenujących (39 osób) (…). W nowszym badaniu u osób nietrenujących deload w formie lżejszego treningu również nie zmienił przyrostu mięśni.” Dodać źródło; uruchomić przegląd twierdzenia.
- **Pewność:** wysoka co do istnienia badania; umiarkowana co do szczegółów wyników. **Weryfikacja:** [SEARCH https://www.nature.com/articles/s41598-026-40612-5].

#### C-14 · MEDIUM · CL-RATE-001 · pola `statement`, `evidence_summary`
- **OBECNIE:** „programy (…) trwające średnio ok. 10 tygodni (od 4 do 24 tygodni) zwiększały masę beztłuszczową średnio o ok. 1,5 kg (…), z dużymi różnicami między osobami”; „czyli średnio ok. 0,15 kg (ok. 0,3 lb) tygodniowo”.
- **PROBLEM:** 1,53 kg (95% CI 1,30-1,76), 111 badań, 1927 mężczyzn – potwierdzone. Średni czas „ok. 10 tygodni (4-24)” – NIEZWERYFIKOWANY (w dostępnych wynikach tylko kryterium włączenia „>2 tyg.”); wartość 0,15 kg/tydz. to wyliczenie Mythlift (iloraz średnich), a nie wynik źródła – przedstawiona jak wynik. „Duże różnice między osobami” – metaanaliza średnich tego nie mierzy (i raportuje I²=0%); teza prawdopodobnie prawdziwa, ale wymaga innego źródła. Pozytywnie: twierdzenie poprawnie nazywa outcome „masą beztłuszczową”.
- **PROPONOWANA KOREKTA:** Po potwierdzeniu czasu trwania w pełnym tekście: „…to w przybliżeniu 0,1-0,2 kg tygodniowo (wyliczenie własne na podstawie średnich)”; zdanie o różnicach międzyosobniczych oprzeć na źródle o zmienności odpowiedzi (np. badania „responderów”) albo usunąć.
- **Pewność:** umiarkowana.

#### C-15 · MEDIUM · CL-RATE-002 · pola `evidence_summary`, `sources`
- **OBECNIE:** „W badaniu trwającym 21 tygodni mięsień czworogłowy osób bez stażu siłowego urósł o ok. 5,6%, a u zawodników z wieloletnim stażem praktycznie się nie zmienił. (…) Z drugiej strony w dużej metaanalizie cechy uczestników nie wyjaśniały różnic w przyroście.”
- **PROBLEM:** Liczby Ahtiainen 2003 zgodne (+5,6% vs −1,8%). Jednak (1) „cechy uczestników” w Benito 2020 to wiek, masa ciała, wzrost – nie staż treningowy; użycie jako kontrargumentu wobec tezy o stażu jest mylące. (2) „Dużo wolniej” opiera się na jednym małym, nierandomizowanym badaniu (8+8), w którym standardowy program mógł być dla zawodników bodźcem słabszym od ich zwykłego treningu (spadek CSA może częściowo odzwierciedlać detrening). (3) SRC-0311 wspiera tylko zalecenie tempa przyrostu **masy ciała**, nie mięśni (INDIRECT).
- **PROPONOWANA KOREKTA:** „…w dużej metaanalizie wiek i masa ciała nie wyjaśniały różnic (stażu nie analizowano jako moderatora)”; w statement: „przybierają mięśnie wolniej” zamiast „dużo wolniej”, z dopiskiem „bezpośrednich porównań jest bardzo mało”.
- **Pewność:** umiarkowana-wysoka. **Weryfikacja:** dossier G3b [SEARCH].

#### C-16 · MEDIUM · CL-CONF-002 · pola `statement`, `evidence_summary` (aktualność, spójność)
- **OBECNIE:** „…umiarkowana, zaplanowana zmienność ćwiczeń (…) może sprzyjać bardziej równomiernemu rozwojowi wszystkich części mięśnia i zwiększać motywację do treningu (…). Nadmierna, przypadkowa rotacja (…) może osłabiać efekty.”
- **PROBLEM:** (1) Nowsze RCT (Kassiano i in. 2024/2025, Res Q Exerc Sport; 70 młodych kobiet, 10 tyg.) nie wykazało przewagi systematycznie zmienianych ćwiczeń w grubości różnych regionów mięśni uda – osłabia tezę o „bardziej równomiernym rozwoju” (choć claim dotyczy mężczyzn). (2) Korzyść motywacyjną (Baz-Valle 2019) wykazano dla zmienności **losowej**, którą ten sam claim określa jako potencjalnie szkodliwą; dowód szkody z losowej rotacji jest słaby (różnica tylko w teście wewnątrzgrupowym jednej głowy, bez istotnej różnicy między grupami). Wewnętrzna niespójność.
- **PROPONOWANA KOREKTA:** „…Wstępne, niespójne dane: w jednym badaniu tylko grupy ze zmiennymi ćwiczeniami miały przyrost we wszystkich głowach mięśnia czworogłowego, w nowszym (u kobiet) zmienność nie dała takiej przewagi. Losowa zmienność zwiększyła motywację bez utraty efektów. Nie ma dobrych dowodów, że rotacja ćwiczeń – planowa czy losowa – wyraźnie zmienia przyrost całego mięśnia.”
- **Pewność:** umiarkowana. **Weryfikacja:** dossier G3b [SEARCH Kassiano 2024].

#### C-17 · MEDIUM · CL-PLAT-003 · pola `statement`, `applicability`
- **OBECNIE:** „…część osób może skorzystać z ilości do ok. 2,2 g/kg (…)”; „Gdy trening jest w porządku, a masa mięśniowa przestała rosnąć…”; applicability: „zdrowi dorośli”.
- **PROBLEM:** (1) 95% CI punktu przegięcia (1,03-2,20 g/kg) opisuje niepewność co do **średniego** progu w populacji, a nie zmienność międzyosobniczą – uzasadnienie „część osób może skorzystać” jest statystycznie błędne (wniosek praktyczny „rozważyć do ~2,2 g/kg dla pewności” jest zbliżony do sugestii autorów, ale z innego powodu). (2) Obie metaanalizy mierzą LM/FFM; ostatnie zdanie mówi o „masie mięśniowej”. (3) Próg ~500 kcal pochodzi z próby o średnim wieku ok. 51 lat, w dużej części z interwencji odchudzających (wg streszczenia – do potwierdzenia) – applicability tego nie sygnalizuje. (4) Źródło SRC-0407 ma niezaznaczoną korektę (S-03).
- **PROPONOWANA KOREKTA:** „…Średni próg korzyści szacowano na ok. 1,6 g/kg, z dużą niepewnością (górna granica ok. 2,2 g/kg), dlatego dla pewności zaleca się ok. 1,6-2,2 g/kg.” oraz „…a beztłuszczowa masa ciała / obwody przestały rosnąć…”; w applicability dopisać charakter próby.
- **Pewność:** wysoka (1, 2); niska-umiarkowana (3).

#### C-18 · MEDIUM · CL-PLAT-004 · pole `statement`, `sources`
- **OBECNIE:** „Wstępne dane sugerują, że może ograniczać regenerację i postępy, dlatego sprawdzenie snu to rozsądna część diagnozy plateau.”
- **PROBLEM:** Jedyne źródło (Lamon 2021) mierzy MPS i hormony po jednej nocy całkowitej deprywacji – nie mierzy regeneracji ani postępów; zdanie nie ma oparcia w przypisanym źródle (INDIRECT). Istnieją lepiej pasujące dane: Saner i in. 2020 (J Physiol) – 5 nocy po 4 h w łóżku obniżyło MyoPS, a wysiłek interwałowy utrzymał ją na poziomie kontroli (przewlekłe ograniczenie, a jednocześnie sygnał, że trening może łagodzić efekt).
- **PROPONOWANA KOREKTA:** Dodać Saner 2020 jako źródło; zdanie: „Przewlekle skrócony sen (5 nocy po 4 h) też obniżał syntezę białek mięśniowych, choć trening częściowo łagodził ten efekt; wpływu na przyrost mięśni w ciągu miesięcy nie zbadano.”
- **Pewność:** wysoka. **Weryfikacja:** [SEARCH https://pubmed.ncbi.nlm.nih.gov/32078168/].

#### C-19 · MEDIUM · CL-PROT-003 · pola `statement`, `evidence_summary`
- **OBECNIE:** „…zwiększanie dziennej podaży białka poprawia przyrost masy beztłuszczowej do ok. 1,6 g na kg (…). Powyżej tej wartości średni dodatkowy efekt przestaje być widoczny, choć część osób może skorzystać z ilości do ok. 2,2 g/kg”; „Niepewność tej wartości sięga ok. 2,2 g/kg, stąd górna granica zakresu”.
- **PROBLEM:** (1) Jak C-17: CI ≠ zmienność międzyosobnicza („część osób”). (2) Precyzja progu 1,6 g/kg jest większa, niż pozwalają dane (CI 1,03-2,20); nowsze metaanalizy (Nunes i in. 2022, J Cachexia Sarcopenia Muscle – efekt stopniowy, istotny przy ≥1,6 g/kg u <65 r.ż.; Tagawa i in. 2021, Nutr Rev – efekt rosnący także przy dużych dawkach dodatkowego białka) wskazują raczej na stopniową zależność niż ostre plateau. (3) Evidence_summary poprawnie mówi o masie beztłuszczowej. (4) Korekta źródła niezaznaczona (S-03).
- **PROPONOWANA KOREKTA:** „…poprawia przyrost masy beztłuszczowej, a korzyść średnio słabnie w okolicy ok. 1,6 g/kg dziennie; ze względu na dużą niepewność tego progu (do ok. 2,2 g/kg) rozsądny zakres to ok. 1,6-2,2 g/kg.” Dodać Nunes 2022.
- **Pewność:** wysoka (1); umiarkowana (2).

#### C-20 · MEDIUM · CL-ENRG-001 · pola `statement`, `applicability`
- **OBECNIE:** „…zmniejsza przyrost beztłuszczowej masy ciała (…), przy podobnym przyroście siły.”; applicability: „dorosłych (…) o różnym stażu i składzie ciała”.
- **PROBLEM:** (1) Dla siły: ES −0,31, p=0,28 w ok. 5 badaniach – to brak istotnej różnicy przy niskiej mocy, nie wykazane podobieństwo („brak różnicy → równoważność”). (2) Wg streszczenia wyszukiwarki średni wiek uczestników ok. 51 lat, a badania w deficycie to w dużej części interwencje odchudzające (do potwierdzenia) – applicability nie sygnalizuje, że próg ~500 kcal może słabo przenosić się na młode, szczupłe osoby trenujące. Pozytywnie: konsekwentnie „beztłuszczowa masa ciała”.
- **PROPONOWANA KOREKTA:** „…a przyrost siły nie różnił się istotnie (mało badań)”; applicability: „…głównie osoby w średnim wieku, często w programach odchudzania; próg to średnia międzybadaniowa”.
- **Pewność:** wysoka (1); niska-umiarkowana (2).

#### C-21 · MEDIUM · CL-ENRG-002 · pola `statement`, `evidence_summary`, `sources` (aktualność)
- **OBECNIE:** „…umiarkowana nadwyżka energii ok. 1500-2000 kJ (ok. 360-480 kcal) dziennie (…). Większa nadwyżka dodaje więcej tkanki tłuszczowej niż mięśni, a optymalnej wielkości nadwyżki u osób trenujących nie ustalono.”; applicability: „Brak bezpośrednich badań porównujących wielkość nadwyżki u osób trenujących”.
- **PROBLEM:** (1) Kluczowa liczba 1500-2000 kJ/d – NIEZWERYFIKOWANA w dostępnych wynikach (wg wiedzy recenzenta prawdopodobnie zgodna z propozycją autorów; wymaga pełnego tekstu). (2) Stwierdzenie „brak bezpośrednich badań” jest nieaktualne: Helms i in. 2023 (Sports Med Open; 17 trenujących, 8 tyg., +5% vs +15% energii) – większa nadwyżka głównie przyspieszała przyrost tłuszczu, a nie hipertrofii czy siły (małe RCT; wspiera kierunek). (3) „Większa nadwyżka dodaje więcej tkanki tłuszczowej niż mięśni” podane kategorycznie przy opieraniu się głównie na badaniach przekarmiania u nietrenujących.
- **PROPONOWANA KOREKTA:** Dodać Helms 2023 jako „supports”; „W małym badaniu u osób trenujących większa nadwyżka (ok. 15% vs 5%) przyspieszała głównie przyrost tłuszczu, a nie mięśni ani siły”; applicability: „jedno małe RCT u trenujących + badania przekarmiania”.
- **Pewność:** wysoka (2); niska (1). **Weryfikacja:** [SEARCH https://pubmed.ncbi.nlm.nih.gov/37914977/].

#### C-22 · MEDIUM · CL-ENRG-003 · pole `applicability`, `evidence_summary`
- **OBECNIE:** applicability: „młodych mężczyzn przez 4 tygodnie, przy bardzo intensywnym, nadzorowanym treningu i spożyciu białka 2,4 g/kg”; evidence_summary: „młodzi mężczyźni na deficycie ok. 40% (…) zwiększyli beztłuszczową masę ciała średnio o ok. 1,2 kg”.
- **PROBLEM:** Pominięto, że uczestnicy mieli **nadwagę** (i najpewniej nie trenowali wcześniej siłowo – do potwierdzenia) – to kluczowe dla zakresu obalenia mitu (rekompozycja jest najłatwiejsza u osób z nadwagą i początkujących). Etykieta „mit” dla absolutnej tezy „nie da się” pozostaje poprawna.
- **PROPONOWANA KOREKTA:** „…u młodych mężczyzn z nadwagą, bez regularnego treningu siłowego…”.
- **Pewność:** wysoka (nadwaga – [SEARCH https://clinicaltrials.gov/study/NCT01776359, streszczenie]); umiarkowana (status treningowy).

#### C-23 · MEDIUM · CL-SLEEP-001 · pole `statement`
- **OBECNIE:** „Dbanie o sen podczas redukcji to rozsądny sposób, by pomóc chronić mięśnie.”
- **PROBLEM:** Źródło mierzy masę beztłuszczową (FFM), nie mięśnie; różnica ok. 0,9 kg w 2 tygodnie może w dużej części być wodą i glikogenem; populacja: osoby z nadwagą w średnim wieku bez treningu siłowego. Przejście FFM → „mięśnie” to nadinterpretacja (wskazana w instrukcji audytu jako typowy błąd). Kierunek replikuje Wang i in. 2018 (Sleep; 8 tyg., n=36 – mniejszy udział tłuszczu w utracie masy przy skróconym śnie).
- **PROPONOWANA KOREKTA:** „…to rozsądny sposób, by pomóc chronić masę beztłuszczową (do której należą m.in. mięśnie).” Dodać Wang 2018.
- **Pewność:** wysoka. **Weryfikacja:** [SEARCH https://pubmed.ncbi.nlm.nih.gov/20921542/ ; https://academic.oup.com/sleep/article/41/5/zsy027/4846324].

#### C-24 · MEDIUM · CL-PAIN-002 · pole `statement` (bezpieczeństwo – podwyższona ostrożność)
- **OBECNIE:** „W badanym schorzeniu dawało to wyniki nie gorsze niż przerwa od bolesnej aktywności.”
- **PROBLEM:** Silbernagel 2007 (2×19 pacjentów) wykazało brak istotnych różnic i brak negatywnych skutków; badanie nie było zaprojektowane jako test non-inferiority, więc „nie gorsze” to przekształcenie „brak różnicy” w równoważność. Ponadto model dopuszczał ból do 5/10 w trakcie rehabilitacji tendinopatii – Mythlift przenosi go na ogólny „łagodny ból związany z ćwiczeniami” (ekstrapolacja jest przyznana w applicability, ale statement jest sformułowany ogólnie).
- **PROPONOWANA KOREKTA:** „W badanym schorzeniu (tendinopatia Achillesa) wyniki po roku były podobne jak przy przerwie od bolesnej aktywności i nie stwierdzono niekorzystnych skutków; przeniesienie tej zasady na inne dolegliwości to ekstrapolacja.”
- **Pewność:** wysoka.

### Uwagi LOW (C-26 – C-44)

| ID | Twierdzenie | Pole | Problem | Proponowana korekta |
|---|---|---|---|---|
| C-26 | CL-DOMS-002, CL-DOMS-003 | applicability | Brak informacji, że uczestnicy Damas 2016 byli nietrenujący (n=10); CL-DOMS-003 uogólnia na „zdrowych dorosłych”. | Dopisać „wcześniej nietrenujących”. |
| C-27 | CL-EFF-001 | statement / recommendation | Zależność podana jako monotoniczna; dane RCT u trenujących (0 vs 1-2 RIR) sugerują wypłaszczenie blisko upadku; „strongly_recommended” pasuje do „unikaj bardzo łatwych serii”, nie do „im bliżej, tym lepiej”. | „…zwykle większy, gdy serie kończą się blisko upadku (ok. 0-3 RIR), niż gdy zostaje duży zapas…”. |
| C-28 | CL-RIR-001 | evidence_summary | Korelacja z prędkością słabsza u początkujących (r=−0,77 vs −0,88). | Dodać „silniejszy u doświadczonych”. |
| C-29 | CL-RIR-002 | statement | „w późniejszych seriach” i „staż nie poprawiał wyraźnie trafności” – NIEZWERYFIKOWANE w dostępnych streszczeniach. | Potwierdzić w pełnym tekście. |
| C-30 | CL-REST-001 | evidence_summary | Przewaga 3 min w Schoenfeld 2016 istotna tylko dla przedniej części uda (triceps – trend). | „…w jednym z trzech mierzonych miejsc”. |
| C-31 | CL-REST-002 | statement / certainty | Przegląd bez metaanalizy; autorzy: dłuższe przerwy „wydają się potrzebne” do maksymalizacji siły u trenujących; B na granicy. | „…wydają się dawać większe przyrosty…”; rozważyć C. |
| C-32 | CL-REST-003 | evidence_summary | „kierunek wyników jest spójny” przy dużej niejednorodności; mechanizm (pompa, hormony) nie jest testowany przez źródła. | „brak przewagi krótkich przerw; mechanizm hormonalny nie znajduje potwierdzenia (patrz CL-TENS-002)”. |
| C-33 | CL-VOL-004 | statement | Przelicznik 0,5 najlepiej opisywał hipertrofię; dla siły nowszy preprint tych samych autorów wskazał liczenie tylko serii bezpośrednich. | Dodać „dla przyrostu masy mięśniowej”. |
| C-34 | CL-DPRG-003 | evidence_summary | Reguła ACSM wymaga 1-2 powt. ponad cel w dwóch kolejnych sesjach (pominięte). | Uzupełnić. |
| C-35 | CL-DLD-002 | evidence_summary | „co 5-6 tygodni” przy SD ~2,3 tyg. – duża rozpiętość praktyki. | „…średnio co ok. 5-6 tygodni, z dużą rozpiętością”. |
| C-36 | CL-DLD-003 | evidence_summary | Hwang 2017 mierzył LBM (DXA), bez grupy trenującej ciągle; Ogasawara – nietrenujący; brak wzmianki o możliwym niewielkim spadku przekroju włókien po ~2 tyg. bezczynności (Hortobágyi 1993 [WIEDZA]). Nowe dane wspierające: Halonen 2024. | Uzupełnić zastrzeżenia i źródło. |
| C-37 | CL-CHG-003 | statement | „sama zmienność programu nie zwiększa przyrostu mięśni” – dla całego mięśnia; regionalnie dane niejednoznaczne. | „…przyrostu całego mięśnia”. |
| C-38 | CL-CONF-001 | sources | SRC-0409 (periodyzacja obciążeń) nie testuje zmiany ćwiczeń ani „przyzwyczajenia” – rola powinna być „context”. | Zmienić rolę. |
| C-39 | CL-PROT-001 | evidence_summary / sources | Pominięta krytyka Beale 2016 (tylko 3 badania z wyrównanym białkiem); nowsza MA Casuso & Goossens 2025 wzmacnia wniosek. | Dodać obie informacje. |
| C-40 | CL-SLEEP-002 | statement | −24% testosteronu to wynik dla grupy mieszanej płciowo (7 M/6 K); nowsze dane o przewlekłym ograniczeniu snu (Saner 2020). | Dopisać „w całej grupie”; dodać Saner 2020. |
| C-41 | CL-PAIN-001 | certainty | Pewność B dotyczy przebiegu DOMS; zalecenia treningowe („trening z zakwasami jest zazwyczaj w porządku”) pochodzą z przeglądu narracyjnego (opinia ekspercka). | Rozdzielić pewność: przebieg B, zalecenia C. |
| C-42 | CL-AUTO-002 | evidence_summary | Lepsza trafność blisko upadku częściowo wynika z mniejszego możliwego błędu; Halperin: brak istotnych różnic trafności poniżej 12 powtórzeń. | Dopisać zastrzeżenie. |
| C-43 | CL-PLAT-001 | evidence_summary | „brak snu obniża syntezę białek mięśniowych (badanie mechanizmu)” – uogólnienie z jednej nocy całkowitej deprywacji. | „jedna nieprzespana noc (i kilka nocy skróconego snu – Saner 2020) obniżały…”. |
| C-44 | CL-RATE-003 | evidence_summary | Dziedziczy wyliczone 0,15 kg/tydz. i niezweryfikowany średni czas trwania (C-14). | Oznaczyć jako przybliżenie własne. |

## 0.5 Podsumowanie partii 0

- Źródła: 60 rekordów / 48 publikacji; bibliografia potwierdzona 48/48; pełny tekst 0/48; częściowo 48/48 (w tym 1 bez potwierdzenia kluczowej liczby); retrakcje 0; korekty 1; problemy rekordów: MEDIUM 3 (S-01, S-02, S-03), LOW 5 (S-04 – S-08).
- Twierdzenia: 68; problemy: CRITICAL 0, HIGH 1 (C-25), MEDIUM 24 (C-01 – C-24), LOW 19 (C-26 – C-44). Twierdzenia z problemem ≥ MEDIUM: 24; tylko z uwagami LOW: 20; bez problemów: 24.
- Najważniejsze wnioski dla audytu pytań: (1) bezpieczeństwo – triaż sygnałów alarmowych (C-25, KC-M5-04); (2) nadinterpretacje FFM → mięśnie (C-17, C-23, KC-M5-02); (3) warunek „blisko upadku” przy lekkich ciężarach (C-02, C-05); (4) progi objętości podawane jako ustalone (C-08, S-02, C-09); (5) nieaktualne „jedyne badanie” (C-11, C-13) i niezauważona korekta źródła (S-03); (6) interpretacja CI jako zmienności międzyosobniczej (C-17, C-19).
