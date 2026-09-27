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

---

## UZUPEŁNIENIE PARTII 0 — nowe ustalenie na poziomie twierdzenia (wykryte podczas audytu partii 1)

#### C-45 · MEDIUM · CL-TENS-003 · pola `applicability`, `evidence_summary`
- **Source:** SRC-0109 (supports), SRC-0101 (context).
- **OBECNIE:** applicability: „Brak badań, które sprawdzałyby wprost, czy wielkość pompy przewiduje przyrost.”; evidence_summary: „Pewność wstępna, bo żadne badanie nie sprawdziło wprost, czy większa pompa przy tej samej pracy oznacza większy przyrost.”
- **PROBLEM:** Stwierdzenie o braku badań jest nieaktualne. Hirono i in. 2022 (J Strength Cond Res 36(2):359-364; 22 nietrenujących mężczyzn, prostowanie kolan 3×8 przy 80% 1RM, 3×/tydz., 6 tyg.) wykazali dodatnią korelację między ostrym obrzękiem mięśnia bezpośrednio po pierwszej sesji (USG) a przyrostem mięśnia po 6 tygodniach; podobny związek opisano w późniejszych małych badaniach (m.in. mięśnie strzałkowe, 2023; zginacze łokcia, Sport Sci Health 2025 – szczegóły NIEZWERYFIKOWANE). To badania korelacyjne u osób nietrenujących, z obrzękiem mierzonym ultrasonograficznie – nie pokazują, że pompa powoduje wzrost, ani że subiektywne odczucie pompy jest dobrym wskaźnikiem skuteczności serii. Rekomendacja „niezalecane” (nie oceniać serii po pompie) pozostaje obronna, ale jej uzasadnienie musi uwzględnić te dane (dowody nie są „żadne”, tylko słabe i niejednoznaczne co do przyczynowości).
- **PROPONOWANA KOREKTA:** applicability: „Badano głównie: pośrednio (mechanizmy, lekkie ciężary, BFR) oraz w kilku małych badaniach korelacyjnych u osób nietrenujących, w których większy ostry obrzęk mięśnia (USG) po pierwszej sesji wiązał się z większym przyrostem.” evidence_summary: „…Małe badania korelacyjne sugerują umiarkowany związek ostrego obrzęku mięśnia z późniejszym przyrostem, ale nie wiadomo, czy to przyczyna, czy wskaźnik indywidualnej reakcji na trening, ani czy odczuwaną pompę da się tak wykorzystywać. Pewność wstępna.” Dodać Hirono 2022 jako źródło (rola: context/contradicts dla części „brak badań”).
- **Pewność oceny:** wysoka co do istnienia i kierunku wyniku; umiarkowana co do wielkości efektu (ρ ≈ 0,44 wg streszczenia uzyskanego w partii 1).
- **Weryfikacja:** [SEARCH https://pubmed.ncbi.nlm.nih.gov/31904714/ ; https://journals.lww.com/nsca-jscr/fulltext/2022/02000/relationship_between_muscle_swelling_and.10.aspx ; https://www.sciencedirect.com/science/article/abs/pii/S0966636223011931].
- **Treści dziedziczące:** IT-M1-01-02, -04, -07 (MEDIUM), IT-M1-01-52, -71 (LOW), MC-100 (LOW) – patrz partia 1.

Po uzupełnieniu liczniki partii 0 dla twierdzeń: CRITICAL 0, HIGH 1, MEDIUM 25, LOW 19.

---

## Partia 1: KC-M1-01 — Napięcie mechaniczne jako główny bodziec

**Zakres partii:** pytania IT-M1-01-01 … IT-M1-01-71 (15: -01…-10, -51, -52, -61, -62, -71), twierdzenia: CL-TENS-001, CL-TENS-002, CL-TENS-003, CL-REPS-001, CL-REPS-003, CL-DOMS-001, CL-DOMS-002, CL-PROG-001, CL-REST-003, źródła: SRC-0100, SRC-0101, SRC-0102, SRC-0103, SRC-0108, SRC-0109, SRC-0110, SRC-0111, SRC-0208, SRC-0210. Publikacje spoza bazy, które wykorzystano w ocenie: Hirono i in. 2022 (JSCR; [SEARCH] w tej partii), Rønnestad i in. 2011 oraz West i in. 2010 (hormony; [SEARCH] wg CLAIMS_AUDIT C-01 i EXTRA), Lasevicius i in. 2022 ([SEARCH] wg EXTRA), Morton i in. 2019 (J Physiol) oraz Nunes i in. 2021 (kolejność ćwiczeń), oba tylko [WIEDZA].

**Metodyka:** przeczytałem w całości każde pytanie (PL i EN), kartę, MC-100/101/109 oraz MC-103/104/106/206 powiązane z opcjami, 9 twierdzeń, CLAIMS_AUDIT (C-01, C-02, C-03, C-04, C-06, C-26, C-27, C-32), dossier G1 i EXTRA. Wykonałem 2 zapytania WebSearch (pompa/obrzęk a hipertrofia). Pełnych tekstów nie czytałem (WebFetch zablokowany).

### Tabela statusów
| ID | STATUS | SEVERITY | CLAIMS | SOURCES | KRÓTKIE UZASADNIENIE |
|---|---|---|---|---|---|
| IT-M1-01-01 | PASS WITH NOTES | LOW | CL-TENS-001 | SRC-0109, SRC-0103, SRC-0101 | Klucz (napięcie mechaniczne) poprawny, distraktory jednoznacznie błędne, pewność opisana trafnie. W W2 „lub blisko niego” dziedziczy C-02 (P01). |
| IT-M1-01-02 | REVISION REQUIRED | MEDIUM | CL-TENS-003, CL-TENS-001 | SRC-0109, SRC-0101, SRC-0103 | Klucz A/C/E jest obronialny. Zdania „nikt tego nie sprawdził” i „wstępne dane nie potwierdzają” są sprzeczne z badaniami korelacyjnymi obrzęk → hipertrofia (Hirono 2022) (P02). Opcja E i determinanty pompy nie mają źródła (P03). |
| IT-M1-01-03 | REVISION REQUIRED | MEDIUM | CL-TENS-002, CL-TENS-001 | SRC-0103, SRC-0109, SRC-0101 | Klucz „mit” jest obronialny. Treść dziedziczy C-01: opisuje radę „przysiady dla hormonów”, ale pomija eksperymenty West 2010 (bez efektu) i Rønnestad 2011 (z efektem) (P04). |
| IT-M1-01-04 | REVISION REQUIRED | MEDIUM | CL-TENS-003, CL-TENS-001 | SRC-0109, SRC-0101, SRC-0103 | Klucz C poprawny. W1.expert i W2 („brak badań, w których … pompa przewidywałaby większy przyrost”) są wprost sprzeczne z Hirono 2022 (P05). Feedback D dziedziczy C-02 (P06). |
| IT-M1-01-05 | REVISION REQUIRED | MEDIUM | CL-REPS-001, CL-TENS-001 | SRC-0100, SRC-0101, SRC-0102, SRC-0103, SRC-0109 | Kontekst „blisko upadku” przy 25-30 powt. i klucz „podobny przyrost” dziedziczą C-02, a W1.expert przypisuje metaanalizom „lub blisko niego” (P07). Średnia grupowa przeniesiona na dwie konkretne osoby (P08). Zakres „6-12 tyg.” i opis populacji niezweryfikowane (P09). |
| IT-M1-01-06 | REVISION REQUIRED | MEDIUM | CL-TENS-001, CL-REPS-001 | SRC-0100, SRC-0101, SRC-0102, SRC-0103, SRC-0109 | Klucz D to dominujące wyjaśnienie, ale żadne twierdzenie ani źródło w bazie go nie dokumentuje (P10). Hipoteza siła–prędkość („napięcie na włókno rośnie”) podana jako fakt (P11). Przesłanka „blisko upadku” w stemie: C-02 (P12). |
| IT-M1-01-07 | REVISION REQUIRED | MEDIUM | CL-TENS-001, CL-TENS-003, CL-DOMS-001, CL-PROG-001 | SRC-0100, SRC-0101, SRC-0103, SRC-0108, SRC-0109, SRC-0110, SRC-0111 | Klucz A+C obronialny (pytanie porównawcze). W2 „rola pompy jako wskaźnika nie była badana wprost” jest błędne (P13). Superlatyw „najlepsze wskaźniki” nie ma źródła (P14). Mechanizm w feedbacku E nie pasuje do ciężkich serii (P15). |
| IT-M1-01-08 | REVISION REQUIRED | MEDIUM | CL-TENS-001, CL-TENS-002, CL-DOMS-001 | SRC-0101, SRC-0103, SRC-0109, SRC-0110, SRC-0111 | Klucz C poprawny. „Jeśli ciężary/powtórzenia rosną, trening działa” pomija warunek „przy podobnym wysiłku”, choć zmiana kryterium kończenia serii sama podnosi liczbę powtórzeń; do tego progres to nie dowód przerostu (P16). Brak powiązania z CL-EFF-001 (P17). Nieudokumentowane porównania i mechanizm (P18). |
| IT-M1-01-09 | REVISION REQUIRED | MEDIUM | CL-TENS-002, CL-TENS-001, CL-REST-003 | SRC-0101, SRC-0103, SRC-0109, SRC-0208, SRC-0210 | Klucz B poprawny. „Hormony nic nie dodają” i „nie znajduje potwierdzenia” pomijają eksperyment o dokładnie takim układzie (Rønnestad 2011) (P19). „Wystarczy przestawić kolejność” nie ma źródła, a metaanaliza [WIEDZA] nie pokazuje wpływu kolejności na hipertrofię (P20). |
| IT-M1-01-10 | PASS WITH NOTES | LOW | CL-TENS-001, CL-REPS-001, CL-REPS-003 | SRC-0100, SRC-0101, SRC-0102, SRC-0103, SRC-0109 | Scenariusz (25-30 powt. do upadku) wprost wspierany, klucz D poprawny. W0/W1 rozszerzają wniosek na „blisko upadku” (P21). Próg „35-40 powt.” i zalecenie praktyczne nie mają źródła (P22). |
| IT-M1-01-51 | REVISION REQUIRED | MEDIUM | CL-TENS-002, CL-TENS-001 | SRC-0101, SRC-0103, SRC-0109 | Klucz „mit” obronialny według całości korpusu. Teza ze stemu (ramiona po nogach) była testowana eksperymentalnie z wynikami sprzecznymi (West 2010 vs Rønnestad 2011), a treść cytuje tylko korelacje i formułuje W0 kategorycznie (P23). |
| IT-M1-01-52 | PASS WITH NOTES | LOW | CL-TENS-001, CL-TENS-003 | SRC-0101, SRC-0103, SRC-0109 | Klucz „fakt” wspierany (ciężkie serie blisko upadku). W1.expert: z „brak badań” wynika „pełnowartościowe” (non sequitur) i pominięto Hirono 2022 (P24). Followup C i W2: C-02 (P25). |
| IT-M1-01-61 | REVISION REQUIRED | MEDIUM | CL-TENS-002, CL-TENS-001 | SRC-0101, SRC-0103, SRC-0109 | Klucz A poprawny. W2: „badania, w których mierzono hormony i przyrost, nie potwierdziły” w kontekście rady „przysiady przed ramionami”, bez wzmianki o Rønnestad 2011 (C-01) (P26). |
| IT-M1-01-62 | PASS WITH NOTES | LOW | CL-TENS-001, CL-DOMS-002 | SRC-0101, SRC-0103, SRC-0109, SRC-0110, SRC-0111 | Klucz B poprawny, W2 uczciwie mówi o jednym małym badaniu. Feedback A („Badania pokazują”) i W1.expert uogólniają Damas 2016 (n=10, nietrenujący; C-26) (P27). |
| IT-M1-01-71 | REVISION REQUIRED | MEDIUM | CL-TENS-001, CL-DOMS-001 | SRC-0101, SRC-0103, SRC-0109, SRC-0110, SRC-0111 | Klucz B najlepszy z opcji. „Dziennik najlepszym wskaźnikiem” i „szybciej pokazują, czy trening działa” to nieudokumentowany overclaim (P28). Populacja badania hormonów błędnie opisana: w badaniu byli tylko mężczyźni, Ola jest kobietą (P29). Pompa: pominięto Hirono 2022 (P30). Wniosek o zakwasach silniejszy niż dane (C-04) (P31). |

### Szczegóły problemów

#### M1-01-P01 · LOW · IT-M1-01-01 · pole `localizations.pl.w2` (i `en.w2`)
- **Claim / source:** CL-TENS-001 (pośrednio CL-REPS-001), SRC-0101, SRC-0103
- **OBECNIE:** „Dlatego przy seriach do upadku lub blisko niego szeroki zakres ciężarów daje podobny przyrost.”
- **PROBLEM:** Problem dziedziczony z C-02. Główne dowody (Schoenfeld 2017, Morton 2016) dotyczą serii **do** upadku. Przy ok. 30% 1RM seria przerwana przed upadkiem dawała mniejszą hipertrofię (Lasevicius 2022). Klucza to nie dotyczy.
- **PROPONOWANA KOREKTA:** „Dlatego w badaniach z seriami do upadku podobny przyrost dawał szeroki zakres ciężarów, od ok. 30% ciężaru maksymalnego. Przy lekkich ciężarach seria musi się kończyć na upadku lub tuż przed nim.” (analogicznie EN)
- **Pewność oceny:** wysoka
- **Weryfikacja:** CLAIMS_AUDIT C-02; EXTRA (Lasevicius 2022, [SEARCH] https://pubmed.ncbi.nlm.nih.gov/31895290/); G1 (SRC-0101: kryterium „wszystkie serie do upadku”).

#### M1-01-P02 · MEDIUM · IT-M1-01-02 · pola `localizations.pl.option_texts.B.feedback`, `pl.w1.simple`, `pl.w1.expert`, `pl.w2` (i analogiczne EN)
- **Claim / source:** CL-TENS-003 (SRC-0109, SRC-0101). Problem dziedziczony z twierdzenia (nowe ustalenie, patrz sekcja „Uwaga dla audytu twierdzeń”).
- **OBECNIE:** w1.simple: „Wstępne dane nie potwierdzają, że większa pompa oznacza większy przyrost, choć wprost nikt tego nie sprawdził.” w1.expert: „Brak badań, w których przy tej samej pracy i wysiłku większa pompa dawałaby większy przyrost”. w2: „Pewność tego wniosku jest ograniczona, bo nikt nie sprawdził wprost, czy większa pompa przy tej samej pracy daje większy przyrost.” feedback B: „Brak jednak badań pokazujących, że większa pompa przy tej samej pracy daje większy przyrost.”
- **PROBLEM:** Twierdzenie „nikt nie sprawdził” jest fałszywe. Hirono i in. (J Strength Cond Res 2022, DOI 10.1519/JSC.0000000000003478) zbadali 22 nietrenujących młodych mężczyzn: prostowanie kolan 3×8 przy 80% 1RM, 3×/tydz., 6 tyg. Ostry wzrost grubości mięśnia po pierwszej sesji wyniósł 8,3±3,2% (obrzęk, czyli obiektywny odpowiednik pompy), a przyrost po 6 tyg. 2,9±2,6%. Korelacja była dodatnia i istotna (ρ=0,443; p=0,039). Przy **tym samym protokole** osoby z większym obrzękiem zyskały więcej. Badanie z 2023 r. na mięśniach strzałkowych podaje podobny związek (szczegóły NIEZWERYFIKOWANE). „Wstępne dane nie potwierdzają” odwraca więc kierunek dostępnych, choć słabych danych. Ograniczenia: dane są korelacyjne, próba mała, uczestnicy nietrenujący, badano jeden mięsień. Obrzęk może być tylko znacznikiem indywidualnej reakcji. Główny przekaz (pompa nie nadaje się do porównywania serii, bo serie lekkie i ciężkie do upadku dają podobny przyrost mimo różnej pompy) i klucz pozostają poprawne.
- **PROPONOWANA KOREKTA:** w1.simple: „Pompa to przejściowe nabrzmienie mięśnia od krwi i płynów, które mija wkrótce po treningu. W dwóch małych badaniach u osób początkujących ci, u których mięsień bardziej nabrzmiewał po pierwszym treningu, zyskali potem nieco więcej mięśni. Nie wiadomo jednak, czy pompa była przyczyną, czy tylko oznaką lepszej reakcji na trening. Serie lekkie i ciężkie do upadku dają podobny przyrost mimo zupełnie innej pompy, więc do porównywania serii pompa się nie nadaje.” w2 (ostatnie zdanie): „Pewność jest ograniczona: w dwóch małych badaniach korelacyjnych u nietrenujących większy obrzęk mięśnia po pierwszym treningu wiązał się z nieco większym przyrostem po kilku tygodniach, ale nikt nie sprawdził, czy celowe zwiększanie pompy przy tej samej pracy zwiększa przyrost.” Expert i feedback B analogicznie („brak badań, w których celowe zwiększanie pompy…; w badaniach korelacyjnych obrzęk tylko umiarkowanie wiązał się z przyrostem”). Analogicznie EN.
- **Pewność oceny:** wysoka (istnienie i wynik Hirono 2022); umiarkowana (badanie 2023 znam tylko z tytułu i streszczenia)
- **Weryfikacja:** WebSearch [SEARCH]: https://journals.lww.com/nsca-jscr/fulltext/2022/02000/relationship_between_muscle_swelling_and.10.aspx ; https://www.semanticscholar.org/paper/Relationship-Between-Muscle-Swelling-and-Induced-by-Hirono-Ikezoe/dc0b5fa2aa531241c97ce0f86c39260b7348be0d ; https://www.sciencedirect.com/science/article/abs/pii/S0966636223011931 . Pełnych tekstów nie czytałem.

#### M1-01-P03 · LOW · IT-M1-01-02 · pola `localizations.pl.option_texts.E` (klucz) + feedback, `pl.w2` (i EN)
- **Claim / source:** brak twierdzenia. CL-REST-003 wspomina o pompie tylko w evidence_summary, a jego źródła tego nie badają (C-32).
- **OBECNIE:** E: „Zwykle jest silniejsza przy wielu powtórzeniach i krótkich przerwach”. w2: „Efekt jest najsilniejszy przy wielu powtórzeniach i krótkich przerwach”, „mimo że pompa jest w nich bardzo różna”.
- **PROBLEM:** Opcja oznaczona jako poprawna i zdania w W2 o determinantach pompy nie mają źródła w bazie. [WIEDZA]: większa akumulacja metabolitów przy wysokich powtórzeniach i krótkich przerwach jest dobrze znana, więc klucz („zwykle”) jest obronialny. „Najsilniejszy” jest jednak mocniejsze niż „zwykle silniejszy”, a silny obrzęk daje też np. ograniczenie przepływu krwi przy małym ciężarze. Różnic pompy między seriami lekkimi i ciężkimi w metaanalizach nie mierzono.
- **PROPONOWANA KOREKTA:** w2: „Efekt jest zwykle silniejszy przy wielu powtórzeniach i krótkich przerwach (a także przy ograniczeniu przepływu krwi) i mija wkrótce po treningu.” Dodać do bazy źródło o ostrym obrzęku i metabolitach, np. badanie porównujące obrzęk przy różnych protokołach. Analogicznie EN.
- **Pewność oceny:** umiarkowana
- **Weryfikacja:** [WIEDZA]; CLAIMS_AUDIT C-32.

#### M1-01-P04 · MEDIUM · IT-M1-01-03 · pola `localizations.pl.main_feedback.depends`, `pl.w1.expert`, `pl.w2` (i EN)
- **Claim / source:** CL-TENS-002 (SRC-0103, SRC-0109). Problem dziedziczony z C-01.
- **OBECNIE:** w2: „…stąd rady, by skracać przerwy albo zaczynać trening od przysiadów „dla hormonów”. W badaniu z randomizacją 49 trenujących mężczyzn (…) Wielkość skoku hormonów po treningu nie korelowała ani z przyrostem mięśni, ani z przyrostem siły. (…) Zastrzeżenia: dane pochodzą z niewielu badań, głównie u młodych mężczyzn, a analiza hormonów opiera się na korelacjach.” depends: „Niezależnie od sposobu wielkość tego krótkiego skoku nie przekładała się jednak na przyrost.”
- **PROBLEM:** Rada „przysiady przed treningiem dla hormonów” była testowana eksperymentalnie. West i in. 2010 (J Appl Physiol): u nietrenujących mężczyzn podniesienie hormonów ćwiczeniami nóg nie zwiększyło hipertrofii zginaczy łokcia, co wspiera mit. Rønnestad i in. 2011 (Eur J Appl Physiol): ćwiczenia nóg przed ćwiczeniami ramion dały większy przyrost przekroju zginaczy łokcia (w części mięśnia), co przeczy mitowi. Ten wynik kwestionowano, np. Phillips 2012. Pytanie przedstawia tylko dowody korelacyjne, a zdanie „niezależnie od sposobu … nie przekładała się” jest kategoryczne. Etykieta „mit” jest uzasadniona całością korpusu, ale treść nie pokazuje obu stron.
- **PROPONOWANA KOREKTA:** Do w2 dopisać: „Pomysł sprawdzono też wprost u nietrenujących mężczyzn. W jednym badaniu trening ramion po ćwiczeniach nóg (z większym wyrzutem hormonów) nie zwiększył przyrostu ramion, w drugim zwiększył go w części mięśnia, ale ten wynik jest kwestionowany. Całość dowodów nie wspiera układania treningu pod wyrzut hormonów, choć pewność jest umiarkowana.” depends: „…wielkość tego krótkiego skoku w większości badań nie przekładała się na przyrost.” W w1.expert dopisać: „Eksperymenty, w których zmieniano wyrzut hormonów, dały wyniki niejednoznaczne.” Analogicznie EN.
- **Pewność oceny:** wysoka (istnienie i kierunek badań); umiarkowana (szczegóły Rønnestad 2011, [WIEDZA])
- **Weryfikacja:** CLAIMS_AUDIT C-01 ([SEARCH] https://link.springer.com/article/10.1007/s00421-011-1860-0); EXTRA („Hormony – dowody sprzeczne”).

#### M1-01-P05 · MEDIUM · IT-M1-01-04 · pola `localizations.pl.option_texts.A.feedback`, `pl.option_texts.C.feedback`, `pl.w1.simple`, `pl.w1.expert`, `pl.w2` (i EN)
- **Claim / source:** CL-TENS-003 (SRC-0109, SRC-0101). IT-M1-01-04 jest pytaniem referencyjnym tego twierdzenia. Problem dziedziczony.
- **OBECNIE:** w1.expert: „Brak badań, w których przy tej samej pracy i wysiłku większa pompa przewidywałaby większy przyrost, więc wniosek jest wstępny.” w2: „Nikt nie sprawdził wprost, czy większa pompa przy tym samym wysiłku przewiduje większy przyrost, więc pewność jest ograniczona.” w1.simple: „Nikt nie wykazał wprost, że większa pompa przy tej samej pracy daje większy przyrost.” A: „…i brak badań, w których większa pompa dawałaby większy przyrost.” C: „Wstępne dane nie potwierdzają ich jako miary skuteczności.”
- **PROBLEM:** Hirono 2022 wprost przeczy tym zdaniom: ostry obrzęk po pierwszej sesji przy tym samym protokole **przewidywał** hipertrofię po 6 tyg. (ρ=0,44). Klucz C pozostaje poprawny. Korelacja rzędu 0,44 wyjaśnia ok. 20% zmienności w małej próbie nietrenujących i nie czyni pompy wiarygodną miarą pojedynczej serii. Między protokołami (seria lekka vs ciężka do upadku) różna pompa nie przekłada się na różny przyrost. Wyjaśnienia są więc częściowo błędne, a klucz nie.
- **PROPONOWANA KOREKTA:** w1.expert: „Rola stresu metabolicznego we wzroście opiera się na dowodach pośrednich. W dwóch małych badaniach korelacyjnych u nietrenujących większy obrzęk mięśnia po pierwszym treningu umiarkowanie wiązał się z większym przyrostem po kilku tygodniach; nie wiadomo, czy przyczynowo. Serie ciężkie i lekkie do upadku dają jednak podobny przyrost mimo zupełnie innej pompy, więc pompa nie nadaje się do porównywania skuteczności serii. Wniosek jest wstępny.” w2 analogicznie. A: „…a nie powiększanie się włókien. W małych badaniach obrzęk po treningu tylko umiarkowanie wiązał się z późniejszym przyrostem, a serie z małą pompą budują mięśnie podobnie.” Analogicznie EN.
- **Pewność oceny:** wysoka
- **Weryfikacja:** WebSearch [SEARCH], adresy jak w P02.

#### M1-01-P06 · LOW · IT-M1-01-04 · pole `localizations.pl.option_texts.D.feedback` (i EN)
- **Claim / source:** CL-REPS-001 (C-02)
- **OBECNIE:** „…przy seriach blisko upadku lżejsze ciężary z wieloma powtórzeniami budują mięśnie podobnie jak cięższe.”
- **PROBLEM:** Problem dziedziczony z C-02 (patrz P01).
- **PROPONOWANA KOREKTA:** „…przy seriach do upadku lub tuż przed nim lżejsze ciężary…” (EN: „with sets taken to or just short of failure”).
- **Pewność oceny:** wysoka. **Weryfikacja:** CLAIMS_AUDIT C-02; EXTRA (Lasevicius 2022).

#### M1-01-P07 · MEDIUM · IT-M1-01-05 · pola `localizations.pl.context`, `pl.option_texts.A.feedback`, `pl.option_texts.B.feedback`, `pl.option_texts.C.feedback`, `pl.w0`, `pl.w1.simple`, `pl.w1.expert` (i EN)
- **Claim / source:** CL-REPS-001 (SRC-0101, SRC-0102, SRC-0103, SRC-0100). Problem dziedziczony z C-02 (MEDIUM).
- **OBECNIE:** context: „Każdą serię kończą blisko upadku. Jedna używa ciężaru, który pozwala na 25-30 powtórzeń…”. B: „Gdy serie kończą się blisko upadku, lżejsze i cięższe ciężary dają podobny przyrost mięśni.” w1.expert: „Metaanalizy pokazują podobną hipertrofię przy obciążeniach od około 30% do ponad 60% 1RM, jeśli serie kończą się na upadku lub blisko niego.”
- **PROBLEM:** Scenariusz dotyczy dokładnie sytuacji, w której dowody są najsłabsze: lekki ciężar (25-30 powt.) i seria kończona „blisko”, a nie „do” upadku. Metaanaliza Schoenfeld 2017 obejmowała wyłącznie serie do chwilowego upadku. Lasevicius 2022 pokazał, że przy 30% 1RM seria przerwana przed upadkiem daje mniejszy przyrost. Przy 25-30 powtórzeniach ocena zapasu jest najmniej trafna (Halperin 2022; samo pytanie przyznaje to w W2). Zdanie w expert przypisuje metaanalizom warunek „lub blisko niego”, którego one nie badały. Klucz B pozostaje najlepszą odpowiedzią, ale opiera się na ekstrapolacji, której treść nie sygnalizuje.
- **PROPONOWANA KOREKTA:** context: „Każdą serię kończą na upadku mięśniowym lub najwyżej jedno powtórzenie przed nim.” B: „Tak. Gdy serie kończą się na upadku lub tuż przed nim, lżejsze i cięższe ciężary dają w badaniach podobny przyrost mięśni.” w1.expert: „Metaanaliza badań z seriami do upadku pokazuje podobną hipertrofię przy obciążeniach od ok. 30% do ponad 60% 1RM. Przy lekkich ciężarach seria przerwana wyraźnie przed upadkiem dawała mniejszy przyrost. Dla obciążeń poniżej ok. 30% 1RM danych jest mało.” A, C, w0 i w1.simple analogicznie („do upadku lub tuż przed nim”). Analogicznie EN.
- **Pewność oceny:** wysoka
- **Weryfikacja:** CLAIMS_AUDIT C-02, C-03; G1 (SRC-0101); EXTRA (Lasevicius 2022 [SEARCH], Halperin 2022 [SEARCH]).

#### M1-01-P08 · LOW · IT-M1-01-05 · pola `localizations.pl.option_texts.B.text`, `pl.w1.simple` (i EN)
- **Claim / source:** CL-REPS-001
- **OBECNIE:** „Podobnego przyrostu mięśni u obu osób”.
- **PROBLEM:** Średnia grupowa przeniesiona na dwie konkretne osoby. Indywidualna zmienność odpowiedzi hipertroficznej jest duża [WIEDZA, np. Hubal 2005], więc dwie osoby mogą urosnąć bardzo różnie niezależnie od ciężaru. Klucz jest najlepszy, bo stem mówi o oczekiwaniu („najprawdopodobniej”), ale sformułowanie sugeruje przewidywanie indywidualne.
- **PROPONOWANA KOREKTA:** B: „Brak wyraźnej przewagi któregokolwiek ciężaru: średnio przyrost byłby podobny”. Można też zmienić kontekst na „dwie grupy”. Analogicznie EN.
- **Pewność oceny:** umiarkowana. **Weryfikacja:** [WIEDZA].

#### M1-01-P09 · LOW · IT-M1-01-05 · pole `localizations.pl.w2` (i EN)
- **Claim / source:** CL-REPS-001 (applicability)
- **OBECNIE:** „Obejmowały młodych dorosłych obu płci, nietrenujących i trenujących, w programach trwających od 6 do 12 tygodni.”
- **PROBLEM:** Twierdzenie mówi „badano głównie”, a pytanie podaje opis jako wyczerpujący. Górna granica 12 tyg. jest NIEZWERYFIKOWANA (G1: potwierdzono tylko kryterium ≥6 tyg.). [WIEDZA, niska pewność]: część badań porównujących obciążenia dotyczyła osób starszych lub trwała dłużej niż 12 tyg.
- **PROPONOWANA KOREKTA:** „Obejmowały głównie młodych dorosłych obu płci, nietrenujących i trenujących, najczęściej w programach kilkutygodniowych (zwykle 6-12 tygodni).” Analogicznie EN.
- **Pewność oceny:** niska-umiarkowana. **Weryfikacja:** G1 (SRC-0101, „6-12 tygodni → NIEZWERYFIKOWANE”).

#### M1-01-P10 · MEDIUM · IT-M1-01-06 · pola `claims` (metadane), klucz `D` + `localizations.pl.option_texts.D.feedback`, `pl.w0`, `pl.w1.simple` (i EN)
- **Claim / source:** CL-TENS-001, CL-REPS-001. Żadne z nich nie zawiera mechanizmu rekrutacji. SRC-0109 dotyczy mechanosensorów, SRC-0101 i SRC-0103 wyniku, nie mechanizmu.
- **OBECNIE:** D: „Pod koniec serii pracuje coraz więcej włókien, także największych, pod dużym napięciem”. Feedback: „Gdy pierwsze włókna się męczą, organizm włącza kolejne, aż pracują także największe…”
- **PROBLEM:** Główna teza pytania typu „dlaczego” (rekrutacja jednostek wysokoprogowych wymuszona zmęczeniem wyjaśnia podobną hipertrofię) nie ma twierdzenia ani źródła w bazie. [WIEDZA]: to dominujące wyjaśnienie. Wspiera je zasada Hennemana i Morton i in. 2019 (J Physiol 597(17):4601-4613): podobne zużycie glikogenu we włóknach typu I i II przy 30% i 80% 1RM do upadku. Pomiary EMG (niższa amplituda przy lekkich ciężarach) są natomiast sporne. Opcja D jest najlepsza, a hedging („tak wyjaśnia się to najczęściej”) trafny, ale fundament klucza jest nieudokumentowany.
- **PROPONOWANA KOREKTA:** Dodać twierdzenie, np. CL-TENS-004: „Przy seriach do upadku z lekkim ciężarem zmęczenie prowadzi do stopniowej rekrutacji jednostek motorycznych wysokoprogowych; uważa się to za główne wyjaśnienie podobnej hipertrofii przy różnych obciążeniach (dowody pośrednie: EMG, zużycie glikogenu we włóknach typu II).” Certainty C. Źródła: Morton 2019 (J Physiol) i przegląd krytyczny interpretacji EMG. Podpiąć je pod IT-M1-01-06 (i IT-M1-01-10, IT-M1-01-01).
- **Pewność oceny:** umiarkowana (dane bibliograficzne Morton 2019 tylko [WIEDZA], do potwierdzenia)
- **Weryfikacja:** przegląd twierdzeń i SRC w bazie; [WIEDZA].

#### M1-01-P11 · MEDIUM · IT-M1-01-06 · pola `localizations.pl.w1.expert`, `pl.w2`, `pl.w1.apply` (i EN)
- **Claim / source:** brak (patrz P10)
- **OBECNIE:** expert: „Zwolnienie skurczu blisko upadku zwiększa, zgodnie z zależnością siła-prędkość, napięcie przypadające na włókno.” w2: „Do tego ruch mimowolnie zwalnia, a wolniej skracające się włókno może wytworzyć większą siłę. Dlatego ostatnie powtórzenia lekkiej serii dają podobny bodziec jak powtórzenia ciężkiej serii…” apply: „Przy lżejszym ciężarze najcenniejsze są ostatnie powtórzenia…”
- **PROBLEM:** Hipoteza mechanistyczna (model siła–prędkość i „efektywne powtórzenia”) jest podana jako fakt. Napięcia przypadającego na włókno u ludzi pod koniec serii nie zmierzono. Zmęczone włókno ma przy tym zmniejszoną zdolność generowania siły (metabolity, spadek wrażliwości na Ca²⁺) [WIEDZA], więc nie wiadomo, czy napięcie na włókno jest „podobne” jak w ciężkiej serii. Zastrzeżenie w W2 dotyczy tylko EMG, a nie tej części. Wniosek praktyczny (lekka seria działa, gdy dochodzi do upadku) ma dobre wsparcie w wynikach badań, ale nie w tym mechanizmie.
- **PROPONOWANA KOREKTA:** expert: „Dodatkowa hipoteza głosi, że zwolnienie skurczu blisko upadku zwiększa, zgodnie z zależnością siła-prędkość, napięcie przypadające na włókno; nie zostało to zmierzone u ludzi.” w2: „Do tego ruch mimowolnie zwalnia. Według jednej z hipotez wolniej skracające się włókno może wtedy wytworzyć większą siłę, choć zmęczone włókno ma też mniejsze możliwości. Pewne jest to, że w badaniach lekkie serie do upadku dawały podobny przyrost jak ciężkie.” apply: „Przy lżejszym ciężarze kończ serię dopiero wtedy, gdy ruch wyraźnie zwalnia mimo pełnego wysiłku: w badaniach lekkie serie działały, gdy dochodziły do upadku.” Analogicznie EN.
- **Pewność oceny:** umiarkowana
- **Weryfikacja:** [WIEDZA] (fizjologia zmęczenia mięśnia; brak bezpośrednich pomiarów napięcia na włókno w treningu u ludzi).

#### M1-01-P12 · LOW · IT-M1-01-06 · pole `localizations.pl.stem` (i EN)
- **Claim / source:** CL-REPS-001 (C-02)
- **OBECNIE:** „Dlaczego przy seriach kończonych blisko upadku lżejszy ciężar może budować mięśnie podobnie jak cięższy?”
- **PROBLEM:** Przesłanka dziedziczy C-02. Łagodzi ją słowo „może”.
- **PROPONOWANA KOREKTA:** „…przy seriach kończonych na upadku lub tuż przed nim…” (EN analogicznie).
- **Pewność oceny:** wysoka. **Weryfikacja:** CLAIMS_AUDIT C-02.

#### M1-01-P13 · MEDIUM · IT-M1-01-07 · pole `localizations.pl.w2` (i `en.w2`)
- **Claim / source:** CL-TENS-003 (problem dziedziczony; patrz P02)
- **OBECNIE:** „Rola pompy jako wskaźnika nie była badana wprost, więc ta część wniosku jest wstępna.”
- **PROBLEM:** Zdanie jest błędne w świetle Hirono 2022 (obrzęk po pierwszej sesji korelował z hipertrofią po 6 tyg., ρ=0,44) i badania z 2023 r. Klucza to nie zmienia: pytanie jest porównawcze, a pompa pozostaje słabszym wskaźnikiem niż bliskość upadku i progres.
- **PROPONOWANA KOREKTA:** „Pompę jako wskaźnik badano tylko w dwóch małych badaniach korelacyjnych u początkujących: większy obrzęk mięśnia po pierwszym treningu umiarkowanie wiązał się z większym przyrostem. Serie lekkie i ciężkie do upadku dają jednak podobny przyrost mimo zupełnie innej pompy, więc do porównywania serii się ona nie nadaje. Ta część wniosku jest wstępna.” Analogicznie EN.
- **Pewność oceny:** wysoka. **Weryfikacja:** WebSearch [SEARCH], adresy jak w P02.

#### M1-01-P14 · LOW · IT-M1-01-07 · pola `localizations.pl.w2`, `pl.option_texts.C.feedback` (i EN)
- **Claim / source:** CL-PROG-001 dotyczy potrzeby progresji, a nie jej wartości diagnostycznej dla hipertrofii. Brak twierdzenia.
- **OBECNIE:** w2: „Najlepsze z nich to bliskość upadku i postęp.”
- **PROBLEM:** Superlatyw nie ma źródła. Wzrost ciężaru i powtórzeń odzwierciedla też adaptacje nerwowe i technikę, zwłaszcza na początku; związek między przyrostem siły a przyrostem mięśni jest umiarkowany [WIEDZA]. W1.expert trafnie nazywa to „przybliżeniami”.
- **PROPONOWANA KOREKTA:** „Najbardziej praktyczne z nich to bliskość upadku i postęp, choć postęp w ciężarach i powtórzeniach odzwierciedla też lepszą technikę i pracę układu nerwowego, a nie tylko wzrost mięśni.” Analogicznie EN.
- **Pewność oceny:** umiarkowana. **Weryfikacja:** [WIEDZA]; CLAIMS_AUDIT C-06 (kontekst).

#### M1-01-P15 · LOW · IT-M1-01-07 · pole `localizations.pl.option_texts.E.feedback` (i EN); `claims`
- **Claim / source:** brak CL-EFF-001 w `claims`
- **OBECNIE:** „Seria przerwana daleko od upadku daje jednak prawdopodobnie słabszy bodziec, bo duże napięcie nie obejmuje w niej wielu włókien.”
- **PROBLEM:** Uzasadnienie mechanistyczne pasuje do serii lekkich i umiarkowanych. W ciężkiej serii duże jednostki pracują od pierwszego powtórzenia (tak pisze IT-M1-01-06 w W2), więc wewnątrz modułu jest niespójność. Wniosek („prawdopodobnie słabszy bodziec”) ma natomiast wsparcie empiryczne: Robinson 2024 (CL-EFF-001), którego nie podpięto.
- **PROPONOWANA KOREKTA:** „Seria przerwana daleko od upadku daje jednak prawdopodobnie słabszy bodziec: w metaanalizie przyrost był tym mniejszy, im więcej powtórzeń zostawało w zapasie, zwłaszcza przy lżejszych ciężarach.” Dodać CL-EFF-001 do `claims`. Analogicznie EN.
- **Pewność oceny:** umiarkowana. **Weryfikacja:** CLAIMS_AUDIT (CL-EFF-001, SRC-0105); EXTRA (Robinson 2024 [SEARCH]).

#### M1-01-P16 · MEDIUM · IT-M1-01-08 · pola `localizations.pl.w1.simple`, `pl.w2` (i EN)
- **Claim / source:** brak twierdzenia (CL-PROG-001 niepodpięty i dotyczy czego innego)
- **OBECNIE:** w1.simple: „Jeśli z czasem rosną, trening działa, nawet gdy pompa jest mniejsza.” w2: „Jeśli po kilku tygodniach ciężary lub powtórzenia zaczną rosnąć, trening działa, nawet gdy pompa będzie mniejsza niż wcześniej.”
- **PROBLEM:** (1) Wskaźnik jest zaburzony przez samą interwencję. Kuba przerywał serie z kilkoma powtórzeniami zapasu, więc po przejściu na serie blisko upadku liczba powtórzeń wzrośnie od razu z powodu większego wysiłku, a nie adaptacji. Brakuje warunku „przy podobnym wysiłku”, który IT-M1-01-07 i IT-M1-01-71 zawierają. (2) Wzrost ciężaru i powtórzeń w rozpiętkach nie dowodzi przyrostu mięśni klatki (technika, adaptacje nerwowe), a „trening działa” odnosi się tu do celu Kuby, czyli wzrostu klatki. Zdanie jest mocne i nieudokumentowane.
- **PROPONOWANA KOREKTA:** w2: „Pierwszy skok liczby powtórzeń po tej zmianie wynika głównie z większego wysiłku. Jeśli później, przy podobnym wysiłku (tym samym zapasie powtórzeń), ciężary lub powtórzenia nadal rosną, to dobry, choć pośredni znak, że mięśnie się adaptują, nawet gdy pompa jest mniejsza.” w1.simple analogicznie. Analogicznie EN.
- **Pewność oceny:** umiarkowana-wysoka
- **Weryfikacja:** analiza logiczna scenariusza; [WIEDZA] (adaptacje nerwowe i siła vs hipertrofia).

#### M1-01-P17 · LOW · IT-M1-01-08 · pole `claims` (metadane)
- **Claim / source:** CL-EFF-001, CL-PROG-001 (niepodpięte)
- **OBECNIE:** `claims: [CL-TENS-001, CL-TENS-002, CL-DOMS-001]`
- **PROBLEM:** Klucz C („kończyć serie blisko upadku i śledzić ciężar oraz powtórzenia”) opiera się na CL-EFF-001 (bliskość upadku a hipertrofia) i CL-PROG-001. Podpięte twierdzenia dotyczą tylko distraktorów, więc łańcuch źródło → klucz jest niekompletny.
- **PROPONOWANA KOREKTA:** Dodać CL-EFF-001 i CL-PROG-001 do `claims`.
- **Pewność oceny:** wysoka. **Weryfikacja:** plik YAML pytania.

#### M1-01-P18 · LOW · IT-M1-01-08 · pola `localizations.pl.w1.expert`, `pl.w2` (i EN)
- **Claim / source:** brak
- **OBECNIE:** expert: „Dobór ćwiczeń i długość przerw mają mniejsze znaczenie niż to, czy serie są wymagające.” w2: „…a to właśnie ostatnie, najtrudniejsze powtórzenia dają najwięcej napięcia w wielu włóknach.”
- **PROBLEM:** Porównanie względnej ważności zmiennych nie było badane i jest to opinia praktyczna. Mechanizm „ostatnie powtórzenia dają najwięcej napięcia” to hipoteza (patrz P11), podana jako fakt.
- **PROPONOWANA KOREKTA:** expert: „W tej sytuacji ważniejsze niż zmiana ćwiczeń czy przerw wydaje się to, czy serie są wymagające (to wniosek z praktyki, nie z bezpośrednich porównań).” w2: „…a według dominującego wyjaśnienia to ostatnie, najtrudniejsze powtórzenia angażują najwięcej włókien pod dużym napięciem.” Analogicznie EN.
- **Pewność oceny:** umiarkowana. **Weryfikacja:** CLAIMS_AUDIT (CL-REST-001, CL-EFF-001); [WIEDZA].

#### M1-01-P19 · MEDIUM · IT-M1-01-09 · pola `localizations.pl.option_texts.A.feedback`, `pl.option_texts.B.feedback`, `pl.w0`, `pl.w1.simple`, `pl.w1.expert`, `pl.w2` (i EN)
- **Claim / source:** CL-TENS-002 (SRC-0103, SRC-0109). Problem dziedziczony z C-01, tu w ostrej postaci.
- **OBECNIE:** w1.simple: „Krótki wzrost hormonów po przysiadach nie przyspiesza wzrostu innych mięśni.” w1.expert: „Założenie (…) nie znajduje potwierdzenia: wielkość tego wzrostu nie korelowała z przyrostem.” w2: „W planie Ewy hormony nic więc nie dodają…” B: „O wzroście ramion decyduje napięcie w ich własnych włóknach.”
- **PROBLEM:** Plan Ewy (ćwiczenia ramion po ciężkich ćwiczeniach nóg „dla hormonów”) to dokładnie układ eksperymentów West 2010 (brak efektu) i Rønnestad 2011 (większy przyrost przekroju zginaczy łokcia w części mięśnia; wynik kwestionowany). Zdania „nic nie dodają” i „nie znajduje potwierdzenia” zamieniają „nie wykazano spójnie” na „nie istnieje” i pomijają badanie przeczące. Wszystkie dane pochodzą od mężczyzn, a Ewa jest kobietą. Pytanie tego nie odnotowuje, choć u kobiet ostry wzrost testosteronu jest zwykle mały [WIEDZA], więc argument hormonalny jest dla niej jeszcze słabszy. „Decyduje” jest mocniejsze niż „uznaje się za główny bodziec” (CL-TENS-001). Klucz B pozostaje poprawny, bo niezależnie od hormonów serie Ewy kończą się daleko od upadku.
- **PROPONOWANA KOREKTA:** w1.simple: „Krótki wzrost hormonów po przysiadach najpewniej nie przyspiesza wyraźnie wzrostu innych mięśni: w większości badań nie miał takiego efektu, a jedyny przeciwny wynik jest kwestionowany. Za to zmęczenie realnie osłabia serie na ramiona.” w1.expert: „…nie znajduje przekonującego potwierdzenia: w badaniach korelacyjnych wielkość wzrostu nie wiązała się z przyrostem, a eksperymenty z treningiem ramion po nogach dały wyniki sprzeczne. Badania prowadzono u mężczyzn.” w2: „W planie Ewy ewentualna korzyść z hormonów jest więc niepewna i najpewniej niewielka, a zmęczenie po przysiadach realnie odbiera ramionom bodziec…” B: „Za główny bodziec wzrostu ramion uznaje się napięcie w ich własnych włóknach.” Analogicznie EN.
- **Pewność oceny:** wysoka (istnienie badań); umiarkowana (szczegóły Rønnestad 2011; odpowiedź hormonalna u kobiet [WIEDZA])
- **Weryfikacja:** CLAIMS_AUDIT C-01 [SEARCH]; EXTRA.

#### M1-01-P20 · MEDIUM · IT-M1-01-09 · pola `localizations.pl.w2`, `pl.w1.apply`, `pl.w1.expert` (i EN)
- **Claim / source:** brak twierdzenia o kolejności ćwiczeń
- **OBECNIE:** w2: „Wystarczy przestawić kolejność, np. zaczynać od ramion w dniu, w którym są priorytetem, albo trenować je w osobny dzień.” apply: „Ćwiczenia na partie, na których najbardziej ci zależy, rób wtedy, gdy masz najwięcej sił.” expert: „Kolejność ćwiczeń warto dobierać pod jakość serii w partiach priorytetowych…”
- **PROBLEM:** Zalecenie nie ma źródła w bazie. [WIEDZA, pewność umiarkowana]: metaanaliza Nunes i in. 2021 (Eur J Sport Sci) wskazuje, że kolejność zwiększa przyrost **siły** w ćwiczeniu wykonywanym na początku, ale nie ma wyraźnego wpływu na **hipertrofię**. „Wystarczy” to overclaim: samo przestawienie nie gwarantuje serii blisko upadku, a to jest sedno problemu Ewy. Zalecenie jest rozsądne, ale treść powinna zaznaczyć, że wynika z praktyki.
- **PROPONOWANA KOREKTA:** w2: „Rozsądnym krokiem jest przestawienie kolejności, np. zaczynanie od ramion w dniu, w którym są priorytetem, albo trening ramion w osobny dzień, ale kluczowe jest, by serie na ramiona kończyły się blisko upadku. Badania nad kolejnością ćwiczeń pokazują przewagę w sile ćwiczeń wykonywanych na początku, a dla przyrostu mięśni różnice są niejasne.” apply: „Ćwiczenia na partie, na których najbardziej ci zależy, rób wtedy, gdy masz siły, by kończyć serie blisko upadku.” Analogicznie EN.
- **Pewność oceny:** umiarkowana
- **Weryfikacja:** [WIEDZA] (Nunes 2021, niezweryfikowane w sesji).

#### M1-01-P21 · LOW · IT-M1-01-10 · pola `localizations.pl.w0`, `pl.w1.expert` (i EN)
- **Claim / source:** CL-REPS-001 (C-02)
- **OBECNIE:** w0: „Lekkie hantle wystarczą, jeśli serie kończą się na upadku lub blisko niego.”
- **PROBLEM:** Scenariusz Tomka (25-30 powt. **do upadku**) jest wprost wspierany (Morton 2016, Schoenfeld 2017). W0 i expert uogólniają go jednak na „blisko upadku” przy lekkim ciężarze (C-02), ze słowem „wystarczą”.
- **PROPONOWANA KOREKTA:** „Lekkie hantle wystarczą, jeśli serie kończą się na upadku lub tuż przed nim, a trudność ćwiczenia z czasem rośnie.” Analogicznie EN.
- **Pewność oceny:** wysoka. **Weryfikacja:** CLAIMS_AUDIT C-02.

#### M1-01-P22 · LOW · IT-M1-01-10 · pola `localizations.pl.w2`, `pl.w1.expert` (i EN)
- **Claim / source:** brak (pośrednio CL-RIR-002 / Halperin 2022)
- **OBECNIE:** „…gdy liczba powtórzeń urośnie do 35-40, serie staną się bardzo długie i męczące (…). Wtedy lepiej utrudnić ćwiczenie (…) niż dokładać kolejne powtórzenia.”
- **PROBLEM:** Próg 35-40 powtórzeń to liczba praktyczna bez źródła. Zalecenie „lepiej utrudnić” nie było testowane, a treść nie sygnalizuje ograniczonej podstawy empirycznej. Kierunek wspierają: spadek trafności oceny zapasu przy wielu powtórzeniach (Halperin 2022) i mniejsza hipertrofia przy 20% 1RM (Lasevicius 2018 [WIEDZA]).
- **PROPONOWANA KOREKTA:** „…gdy liczba powtórzeń wyraźnie przekroczy ok. 30-40 (to próg praktyczny, nie wynik badań), serie staną się bardzo długie (…). Wtedy rozsądniej jest utrudnić ćwiczenie (…). Przy bardzo lekkich ciężarach, poniżej ok. 30% maksimum, danych jest mało.” Analogicznie EN.
- **Pewność oceny:** umiarkowana. **Weryfikacja:** EXTRA (Halperin 2022 [SEARCH]); G1 (Lasevicius 2018 [WIEDZA]).

#### M1-01-P23 · MEDIUM · IT-M1-01-51 · pola `localizations.pl.main_feedback.myth`, `pl.main_feedback.depends`, `pl.w0`, `pl.w1.expert`, `pl.w2` (i EN)
- **Claim / source:** CL-TENS-002 (SRC-0103, SRC-0109). Problem dziedziczony z C-01.
- **OBECNIE:** w0: „Mit. Krótki skok hormonów po treningu nie przyspiesza wzrostu mięśni, liczy się bodziec w ramionach.” w2: „…W 12-tygodniowym badaniu z randomizacją u 49 trenujących mężczyzn wielkość tych wzrostów nie wiązała się ani z przyrostem mięśni, ani z przyrostem siły. (…) Pewność jest umiarkowana, bo badań jest niewiele i dotyczą głównie młodych mężczyzn.”
- **PROBLEM:** Teza ze stemu („ramiona rosną szybciej, jeśli trenuje się je zaraz po ciężkim treningu nóg, bo więcej T i GH”) była testowana wprost. West 2010 nie wykazał efektu. Rønnestad 2011 wykazał większy przyrost przekroju zginaczy łokcia w części mięśnia i większy przyrost siły; wynik kwestionowano. Pytanie cytuje tylko korelacje z Morton 2016 i formułuje W0 kategorycznie. Etykieta „mit” jest obronialna na podstawie całości dowodów (korelacje Morton 2016 i innych oraz West 2010), ale uzasadnienie pomija wynik przeciwny, a pewność opisuje niepełnie.
- **PROPONOWANA KOREKTA:** w0: „Mit. Krótki skok hormonów po treningu nóg najpewniej nie przyspiesza wyraźnie wzrostu ramion; liczy się bodziec w samych ramionach.” Do w2 dopisać: „Pomysł sprawdzono też wprost u nietrenujących mężczyzn. W jednym badaniu trening ramion po ćwiczeniach nóg nie zwiększył ich przyrostu, w drugim zwiększył go w części mięśnia, ale ten wynik jest kwestionowany i niepowtórzony.” Myth i depends: „W większości badań…”. Analogicznie EN.
- **Pewność oceny:** wysoka (istnienie badań); umiarkowana (szczegóły)
- **Weryfikacja:** CLAIMS_AUDIT C-01 [SEARCH https://link.springer.com/article/10.1007/s00421-011-1860-0]; EXTRA.

#### M1-01-P24 · LOW · IT-M1-01-52 · pole `localizations.pl.w1.expert` (i EN)
- **Claim / source:** CL-TENS-003 (patrz P02), CL-REPS-001
- **OBECNIE:** „Nie ma badań pokazujących, że większa pompa przy tej samej pracy daje większy przyrost, więc ciężkie serie z małą pompą są pełnowartościowe.”
- **PROBLEM:** (1) Pominięto korelacyjne dane Hirono 2022. „Daje” w sensie przyczynowym jest formalnie prawdziwe, ale mylące. (2) Non sequitur: z braku dowodów na korzyść pompy wyprowadzono równoważność („pełnowartościowe”). Wniosek ma wsparcie gdzie indziej: metaanalizy obciążeń pokazują podobny przyrost mimo różnej pompy.
- **PROPONOWANA KOREKTA:** „Serie ciężkie i lekkie doprowadzone do upadku dają w badaniach podobny przyrost mimo zupełnie innej pompy, więc ciężkie serie z małą pompą są skuteczne. Brak badań, w których celowe zwiększanie pompy przy tej samej pracy zwiększałoby przyrost; w małych badaniach korelacyjnych obrzęk po treningu tylko umiarkowanie wiązał się z przyrostem.” Analogicznie EN.
- **Pewność oceny:** wysoka. **Weryfikacja:** WebSearch [SEARCH] (jak P02); G1 (SRC-0101).

#### M1-01-P25 · LOW · IT-M1-01-52 · pola `localizations.pl.followup_texts.C.feedback`, `pl.w2` (i EN)
- **Claim / source:** CL-REPS-001 (C-02)
- **OBECNIE:** C: „Przy wysiłku blisko upadku szeroki zakres powtórzeń buduje jednak mięśnie podobnie”. w2: „Blisko upadku obie mogą jednak budować mięśnie podobnie…”
- **PROBLEM:** Problem dziedziczony z C-02 w odniesieniu do długich, lekkich serii. W w2 łagodzi go słowo „mogą”.
- **PROPONOWANA KOREKTA:** „Przy seriach do upadku lub tuż przed nim…”. Analogicznie EN.
- **Pewność oceny:** wysoka. **Weryfikacja:** CLAIMS_AUDIT C-02.

#### M1-01-P26 · MEDIUM · IT-M1-01-61 · pola `localizations.pl.w2`, `pl.w1.simple` (i EN)
- **Claim / source:** CL-TENS-002 (SRC-0103, SRC-0109). Problem dziedziczony z C-01.
- **OBECNIE:** w2: „Na tej podstawie zalecano np. robienie przysiadów przed treningiem ramion albo skracanie przerw. Badania, w których mierzono zarówno hormony, jak i przyrost mięśni, nie potwierdziły tej zależności: osoby z większym skokiem hormonów nie rosły bardziej.” w1.simple: „W badaniach osoby z większym wyrzutem hormonów nie przybierały więcej mięśni.”
- **PROBLEM:** Rønnestad 2011 mierzył hormony i przyrost i dla rady „nogi przed ramionami” uzyskał wynik pozytywny (kwestionowany). West 2010 nie wykazał efektu. Zdanie „nie potwierdziły” jest kategoryczne i stoi bezpośrednio po wzmiance o tej radzie. Dla korelacji międzyosobniczych (Morton 2016 oraz [WIEDZA] Mitchell 2013, West & Phillips 2012) wniosek „brak istotnego związku” jest zasadniczo trafny. Klucz A jest poprawny.
- **PROPONOWANA KOREKTA:** w2: „Badania korelacyjne, w których mierzono hormony i przyrost mięśni, nie potwierdziły tej zależności: osoby z większym skokiem hormonów nie rosły wyraźnie bardziej. Eksperymenty z ćwiczeniami nóg przed treningiem ramion dały wyniki sprzeczne: w jednym bez efektu, w drugim z niewielkim, kwestionowanym efektem.” w1.simple: „W badaniach osoby z większym wyrzutem hormonów zwykle nie przybierały więcej mięśni.” Analogicznie EN.
- **Pewność oceny:** wysoka (istnienie badań); umiarkowana (szczegóły)
- **Weryfikacja:** CLAIMS_AUDIT C-01 [SEARCH]; EXTRA; [WIEDZA] (Mitchell 2013 PLoS One).

#### M1-01-P27 · LOW · IT-M1-01-62 · pola `localizations.pl.option_texts.A.feedback`, `pl.w1.expert`, `pl.w2` (i EN)
- **Claim / source:** CL-DOMS-002 (SRC-0110, SRC-0109, SRC-0111). Problem dziedziczony z C-26.
- **OBECNIE:** A: „Badania pokazują jednak, że uszkodzenia są największe na początku nowego programu, a mięśnie rosną, gdy uszkodzeń jest coraz mniej.” expert: „W małym badaniu z biopsjami wczesny wzrost syntezy białek szedł głównie na naprawę…”
- **PROBLEM:** Opis dotyczy jednego badania (Damas 2016, n=10, wcześniej nietrenujący mężczyźni). „Szedł głównie na naprawę” to interpretacja autorów oparta na korelacjach (twierdzenie mówi „wydaje się”), podana jako wynik pomiaru. Istnieje komentarz przeciwny (J Physiol 2016). Spadek uszkodzeń przy powtarzaniu ćwiczeń jest dobrze udokumentowany (efekt powtórzonej sesji [WIEDZA]), więc kierunek A jest trafny. W2 poprawnie mówi o „jednym małym badaniu”.
- **PROPONOWANA KOREKTA:** A: „W małym badaniu u początkujących uszkodzenia były największe na początku programu, a mięśnie rosły, gdy uszkodzeń było coraz mniej. To, że uszkodzeń ubywa przy powtarzaniu ćwiczeń, potwierdzają też inne badania.” expert: „…wczesny wzrost syntezy białek nie wiązał się z przyrostem, co autorzy interpretują jako przewagę naprawy; uczestnicy byli wcześniej nietrenujący.” Analogicznie EN.
- **Pewność oceny:** wysoka. **Weryfikacja:** CLAIMS_AUDIT C-26; EXTRA (Damas 2016 [SEARCH], komentarz PMID 27976401).

#### M1-01-P28 · MEDIUM · IT-M1-01-71 · pola `localizations.pl.option_texts.B.feedback`, `pl.w1.expert`, `pl.w2` (i EN)
- **Claim / source:** CL-TENS-001, CL-DOMS-001 nie dotyczą tej tezy. CL-PROG-001 niepodpięty i dotyczy konieczności progresji, nie jej wartości jako wskaźnika.
- **OBECNIE:** B: „Dwa dodatkowe powtórzenia tym samym ciężarem przy podobnym wysiłku pokazują, że mięśnie nadal się adaptują, a trening działa.” w2: „W praktyce najlepszym wskaźnikiem jest dziennik (…). Zmiany obwodów i wyglądu są wolniejsze i łatwo je przeoczyć, dlatego zapiski wyników szybciej pokazują, czy trening działa.”
- **PROBLEM:** Stem pyta o „bodziec do wzrostu”. Progres wyników jest rozsądnym, ale pośrednim wskaźnikiem, bo obejmuje adaptacje nerwowe, technikę i koordynację; związek zmian siły ze zmianami masy mięśniowej jest umiarkowany [WIEDZA]. „Najlepszym wskaźnikiem” i „szybciej pokazują, czy trening działa” to superlatywy bez źródła. Wyniki reagują szybciej właśnie dlatego, że odzwierciedlają też czynniki inne niż przerost. Klucz B pozostaje najlepszy wśród opcji (zakwasy, pompa, hormony), ale główna teza wyjaśnień jest przeszacowana i nieudokumentowana.
- **PROPONOWANA KOREKTA:** B: „…pokazują, że trening nadal wywołuje adaptację. To dobry, choć pośredni znak, bo wzrost siły wynika też z lepszej techniki i pracy układu nerwowego.” w2: „W praktyce najwygodniejszym, choć pośrednim wskaźnikiem jest dziennik (…). Wyniki zmieniają się szybciej niż obwody, ale odzwierciedlają też poprawę techniki, więc co kilka tygodni warto sprawdzać także obwody lub zdjęcia.” Dodać CL-PROG-001 do `claims`. Analogicznie EN.
- **Pewność oceny:** umiarkowana. **Weryfikacja:** [WIEDZA]; przegląd twierdzeń w bazie (brak twierdzenia o wartości diagnostycznej progresji).

#### M1-01-P29 · LOW · IT-M1-01-71 · pole `localizations.pl.option_texts.D.feedback` (i `en`: „In a study of trained people”)
- **Claim / source:** CL-TENS-002 (SRC-0103)
- **OBECNIE:** „W badaniu z osobami trenującymi wielkość tego skoku nie wiązała się jednak z przyrostem mięśni ani siły.”
- **PROBLEM:** Morton 2016 badał wyłącznie młodych mężczyzn. Pytanie dotyczy kobiety (Oli), a opis populacji ją uogólnia.
- **PROPONOWANA KOREKTA:** „W badaniu z udziałem trenujących mężczyzn…” (EN: „In a study of trained men…”).
- **Pewność oceny:** wysoka. **Weryfikacja:** SRC-0103; EXTRA (Morton 2016 [SEARCH]).

#### M1-01-P30 · LOW · IT-M1-01-71 · pole `localizations.pl.option_texts.C.feedback` (i EN)
- **Claim / source:** CL-TENS-003 (patrz P02)
- **OBECNIE:** „Nie ma badań pokazujących, że większa pompa przy tej samej pracy daje większy przyrost.”
- **PROBLEM:** Pominięto dane korelacyjne (Hirono 2022). Sformułowanie przyczynowe („daje”) jest formalnie obronialne, ale mylące.
- **PROPONOWANA KOREKTA:** „Nie ma badań, w których celowe zwiększanie pompy przy tej samej pracy zwiększałoby przyrost, a serie z małą pompą budują mięśnie podobnie jak serie z dużą.” Analogicznie EN.
- **Pewność oceny:** wysoka. **Weryfikacja:** WebSearch [SEARCH] (jak P02).

#### M1-01-P31 · LOW · IT-M1-01-71 · pola `localizations.pl.w2`, `pl.w1.expert` (i EN)
- **Claim / source:** CL-DOMS-001 (C-04), CL-DOMS-002/003 (C-26)
- **OBECNIE:** „Zakwasy słabo odzwierciedlają nawet samo uszkodzenie, więc tym bardziej nie mierzą wzrostu.”
- **PROBLEM:** Wniosek „tym bardziej” jest logiczny, a nie empiryczny: żadne źródło nie testuje nasilenia zakwasów jako predyktora hipertrofii (C-04). Dane Damas pochodzą od nietrenujących, a Ola trenuje 5 miesięcy (C-26). Kierunek jest trafny, ale siła sformułowania przekracza dowody.
- **PROPONOWANA KOREKTA:** „Zakwasy słabo odzwierciedlają nawet samo uszkodzenie, a nie ma badań, które wiązałyby ich nasilenie z długoterminowym przyrostem, więc nie są dobrą miarą skuteczności.” Analogicznie EN.
- **Pewność oceny:** umiarkowana. **Weryfikacja:** CLAIMS_AUDIT C-04, C-26; G1 (SRC-0110, SRC-0111).

### Karta pojęcia i błędne przekonania

#### M1-01-P32 · MEDIUM · KC-M1-01 · pole `card.pl` (i `card.en`)
- **Claim / source:** CL-REPS-001 (C-02), CL-TENS-001
- **OBECNIE:** „Duże napięcie daje ciężka seria, ale też lżejsza, jeśli kończy się blisko upadku: pod jej koniec pracują także największe włókna. Dlatego przy takich seriach podobny przyrost daje szeroki zakres ciężarów, od około 30% ciężaru maksymalnego wzwyż.”
- **PROBLEM:** (1) Problem dziedziczony z C-02: przy lekkich ciężarach dowody dotyczą serii do upadku (Lasevicius 2022). (2) „Dlatego” przedstawia hipotezę rekrutacyjną jako udowodnioną przyczynę podobnego przyrostu (patrz P10, P11). Karta jest treścią nadrzędną, a błąd powtarzają IT-M1-01-05, -06, -10 i -52.
- **PROPONOWANA KOREKTA:** „Duże napięcie daje ciężka seria, ale też lżejsza, jeśli kończy się na upadku lub tuż przed nim. Uważa się, że pod jej koniec pracują wtedy także największe włókna. W badaniach z seriami do upadku podobny przyrost dawał szeroki zakres ciężarów, od około 30% ciężaru maksymalnego wzwyż.” Analogicznie EN.
- **Pewność oceny:** wysoka. **Weryfikacja:** CLAIMS_AUDIT C-02; EXTRA (Lasevicius 2022).

#### M1-01-P33 · LOW · MC-100 · pole `refutation.pl` (i `en`)
- **Claim / source:** CL-TENS-003
- **OBECNIE:** „Nie ma badań pokazujących, że większa pompa przy tej samej pracy daje większy przyrost.”
- **PROBLEM:** Pominięto korelacyjne dane Hirono 2022 (patrz P02 i P30).
- **PROPONOWANA KOREKTA:** „Nie ma badań, w których celowe zwiększanie pompy przy tej samej pracy zwiększałoby przyrost; w małych badaniach korelacyjnych obrzęk po treningu tylko umiarkowanie wiązał się z przyrostem, a serie lekkie i ciężkie dają podobny przyrost mimo różnej pompy.” Analogicznie EN.
- **Pewność oceny:** wysoka. **Weryfikacja:** WebSearch [SEARCH].

#### M1-01-P34 · LOW · MC-101 · pole `refutation.pl` (i `en`)
- **Claim / source:** CL-TENS-002 (C-01)
- **OBECNIE:** „W badaniu z randomizacją u trenujących mężczyzn jego wielkość nie wiązała się ani z przyrostem mięśni, ani z przyrostem siły. O wzroście decyduje przede wszystkim bodziec lokalny…”
- **PROBLEM:** Problem dziedziczony z C-01: pominięto eksperymenty West 2010 (zgodny) i Rønnestad 2011 (przeczący, kwestionowany). Łagodzi go sformułowanie „przede wszystkim”.
- **PROPONOWANA KOREKTA:** Dopisać: „Eksperymenty, w których celowo podnoszono poziom hormonów ćwiczeniami nóg, dały wyniki niejednoznaczne, więc całość dowodów nie wspiera układania treningu pod wyrzut hormonów.” Analogicznie EN.
- **Pewność oceny:** wysoka. **Weryfikacja:** CLAIMS_AUDIT C-01.

#### M1-01-P35 · LOW · MC-109 · pole `refutation.pl` (i `en`)
- **Claim / source:** CL-DOMS-001/002 (C-26)
- **OBECNIE:** „Gdy organizm przyzwyczaja się do programu, uszkodzeń jest mniej, a mięśnie nadal rosną.”
- **PROBLEM:** Kategoryczne uogólnienie z Damas 2016 (n=10, nietrenujący, 10 tyg.). Pytania używają ostrożniejszego „mogą nadal rosnąć”.
- **PROPONOWANA KOREKTA:** „…uszkodzeń jest mniej, a mięśnie mogą nadal rosnąć (dane głównie od osób początkujących).” Analogicznie EN.
- **Pewność oceny:** wysoka. **Weryfikacja:** CLAIMS_AUDIT C-26; G1.

**Uwagi informacyjne (MC z innych kart, powiązane z opcjami tej partii; nieliczone, do oceny w partiach ich KC):**
- MC-103 (KC-M1-03), refutation: „Gdy serie kończą się blisko upadku, podobny przyrost dają (…) serie po 20-30 powtórzeń z lżejszym” dziedziczy C-02.
- MC-104 (KC-M1-03): „Przy wysiłku blisko upadku lekkie ciężary (…) budują mięśnie podobnie” dziedziczy C-02.
- MC-106 (KC-M1-04): „Seria buduje mięśnie tym skuteczniej, im bliżej upadku się kończy” zakłada zależność monotoniczną (C-27).
- MC-206 (KC-M2-04): brak istotnych problemów (zgodne z Singer 2024 i Schoenfeld 2016).

**Uwaga dla audytu twierdzeń (nowe ustalenie, poza licznikami partii):** CL-TENS-003, pola `applicability` („Brak badań, które sprawdzałyby wprost, czy wielkość pompy przewiduje przyrost”) i `evidence_summary` („żadne badanie nie sprawdziło wprost”; „Wstępne dane nie potwierdzają…”). Oba sformułowania są sprzeczne z Hirono i in. 2022 (J Strength Cond Res; n=22 nietrenujących; ρ=0,443 między ostrym obrzękiem a przyrostem po 6 tyg.) oraz z badaniem z 2023 r. (mięśnie strzałkowe; szczegóły NIEZWERYFIKOWANE). Proponuję nowy problem C-45 · MEDIUM. Dodać Hirono 2022 jako źródło „context” (częściowo przeczące) i przeformułować: „W małych badaniach korelacyjnych u nietrenujących większy obrzęk po pierwszym treningu umiarkowanie wiązał się z przyrostem; nie badano, czy celowe zwiększanie pompy przy tej samej pracy zwiększa przyrost, a serie lekkie i ciężkie do upadku dają podobny przyrost mimo różnej pompy.” Rekomendacja „niezalecane” i pewność C pozostają uzasadnione. Kontekst aktualności CL-TENS-001: wyszukiwarka pokazała nowszy przegląd „Load-induced human skeletal muscle hypertrophy: Mechanisms, myths, and misconceptions” (J Sport Health Sci 2025; https://www.sciencedirect.com/science/article/pii/S2095254625000869). Znam tylko tytuł, treść NIEZWERYFIKOWANA.

### Podsumowanie partii
- Pytania: PASS 0, PASS WITH NOTES 4 (IT-M1-01-01, -10, -52, -62), REVISION REQUIRED 11 (IT-M1-01-02, -03, -04, -05, -06, -07, -08, -09, -51, -61, -71), FAIL 0, UNVERIFIED 0 (razem 15)
- Problemy (tylko w pytaniach): CRITICAL 0, HIGH 0, MEDIUM 13, LOW 18
- Problemy w karcie/MC (osobno): CRITICAL 0, HIGH 0, MEDIUM 1, LOW 3 (oraz 1 nowe ustalenie na poziomie twierdzenia CL-TENS-003, proponowane C-45 · MEDIUM, poza licznikami)
- Klucze odpowiedzi: wszystkie 15 poprawne lub obronialne. Problemy dotyczą wyjaśnień (feedback, W0-W2), metadanych i dziedziczenia z twierdzeń (C-01, C-02, C-04, C-26).
- Ostatnie ID w partii: IT-M1-01-71

---

## Partia 2: KC-M1-02 — Progresywne przeciążenie

**Zakres partii:** pytania IT-M1-02-01 … IT-M1-02-71 (13: -01, -02, -03, -04, -05, -06, -07, -08, -09, -10, -51, -61, -71), twierdzenia: CL-PROG-001, CL-PROG-002, CL-PROG-003, CL-EFF-001, CL-REPS-001, CL-RIR-001; źródła: SRC-0100 (ACSM 2026), SRC-0101 (Schoenfeld 2017), SRC-0102 (Currier 2023), SRC-0103 (Morton 2016), SRC-0104 (Refalo 2023), SRC-0105 (Robinson 2024), SRC-0106 (Halperin 2022), SRC-0107 (Zourdos 2016), SRC-0108 (Plotkin 2022). Błędne przekonania karty: MC-102, MC-610 (pozostałe MC powiązane przez opcje – tylko sygnalizacja, patrz niżej).

**Uwagi metodyczne partii**
- Weryfikacja źródeł oparta na CLAIMS_AUDIT.md oraz dossier G1, G3a, EXTRA (wszystkie źródła zweryfikowane częściowo, bez pełnych tekstów). Wykonano jedno wyszukiwanie WebSearch (spór o udział hipertrofii we wzroście siły – potwierdzony, patrz P10).
- Dziedziczenie C-06 (CL-PROG-001: „muszą” – konieczność progresji nie była testowana wprost) oceniam konsekwentnie: **LOW**, gdy pytanie samo zawiera zastrzeżenie o ograniczonych dowodach (np. „niewiele badań porównuje wprost trening z progresją i bez niej”) albo gdy zdanie o konieczności jest pojedyncze i peryferyjne; **MEDIUM**, gdy konieczność/wystarczalność jest podana wielokrotnie lub jako wynik badań, bez żadnego zastrzeżenia w pytaniu.
- Wyjaśnienia „szybki start = nauka ruchu (technika, koordynacja)” nie mają w bazie żadnego twierdzenia ani źródła. Część o wczesnych adaptacjach nerwowych jest zgodna z głównym nurtem [WIEDZA] → LOW, gdy pojawia się w W1/W2. Część „później siła coraz bardziej zależy od przyrostu mięśni” to model sporny w literaturze → MEDIUM, gdy stanowi rdzeń wyjaśnienia (IT-08, IT-10). Zdania w feedbacku dystraktorów „szybki wzrost w nowym ćwiczeniu to głównie nauka ruchu” traktuję informacyjnie (obecne w MC-401, zgodne z głównym nurtem).

### Tabela statusów
| ID | STATUS | SEVERITY | CLAIMS | SOURCES | KRÓTKIE UZASADNIENIE |
|---|---|---|---|---|---|
| IT-M1-02-01 | PASS WITH NOTES | LOW | CL-PROG-001, CL-PROG-003 | SRC-0100, SRC-0108 | Klucz A (definicja) poprawny i jedyny najlepszy; dystraktory B-D faktycznie błędne. „Musi” (C-06) złagodzone zastrzeżeniem w W2; nieudokumentowane wyjaśnienie „technika i koordynacja” w W2. |
| IT-M1-02-02 | PASS WITH NOTES | LOW | CL-PROG-001 | SRC-0100, SRC-0108 | Klucz multi A+B+C poprawny i kompletny (ciężar, powtórzenia, serie); D i E słusznie niepoprawne. Mechanizm „stały bodziec traci skuteczność” podany jako fakt bez zastrzeżenia (peryferyjne). |
| IT-M1-02-03 | PASS WITH NOTES | LOW | CL-PROG-001 | SRC-0100, SRC-0108 | Klucz A („najpewniej zwolnią…”) poprawny niezależnie od mechanizmu (przyrosty zwalniają także przy progresji). C-06 w W0/W1.simple, zastrzeżenie obecne w W1.expert; ramy „po kilku miesiącach” nieudokumentowane. Brak W2 (informacyjnie). |
| IT-M1-02-04 | PASS WITH NOTES | LOW | CL-PROG-001, CL-EFF-001 | SRC-0100, SRC-0108, SRC-0105, SRC-0104 | Klucz B najlepszy spośród opcji (pozostałe to mity); W2 uczciwie mówi o mechanizmie i o naturalnym spowolnieniu także przy progresji. „Trzeba” w W1.simple (C-06), złagodzone w W2. |
| IT-M1-02-05 | PASS WITH NOTES | LOW | CL-PROG-003, CL-PROG-001 | SRC-0108, SRC-0100 | Klucz „mit” obronialny (twierdzenie absolutne; SRC-0108 DIRECT dla „bez ciężaru nie ma postępu”); „zależy” słusznie oceniane jako mit. Arytmetyka 2,5 kg × 156 = 390 kg ≈ 860 lb poprawna. Nieudokumentowany czas trwania fazy liniowej i mechanizm nerwowy; przewaga siłowa LOAD bez zaznaczenia niepewności. |
| IT-M1-02-06 | PASS WITH NOTES | LOW | CL-PROG-002, CL-PROG-001, CL-REPS-001 | SRC-0108, SRC-0100, SRC-0101, SRC-0102, SRC-0103 | Klucz C poprawny; opis Plotkin 2022 wzorcowo ostrożny (jedno badanie, 8 tyg., nogi, różnica siły „mała i niepewna”). W W2 uogólnienie „blisko upadku… bardzo różne liczby powtórzeń” dziedziczy C-02/C-03 (peryferyjne). |
| IT-M1-02-07 | REVISION REQUIRED | MEDIUM | CL-PROG-001, CL-PROG-003 | SRC-0100, SRC-0108 | Klucz D poprawny. Konieczność („sama regularność nie wystarcza”) i wystarczalność („Wystarczy progresja…”, „Rozwiązaniem jest”) podane jako pewne, bez żadnego zastrzeżenia w pytaniu (C-06 + „wystarczy”). |
| IT-M1-02-08 | REVISION REQUIRED | MEDIUM | CL-PROG-003, CL-PROG-001 | SRC-0108, SRC-0100 | Klucz B poprawny. Rdzeń W2 („później siła coraz bardziej zależy od przyrostu mięśni”) – model nieudokumentowany w bazie i sporny w literaturze. Drobna luka ostrożności: brak wskazania, by kończyć serię przed rozpadem techniki / cofnąć ciężar. |
| IT-M1-02-09 | REVISION REQUIRED | MEDIUM | CL-PROG-001, CL-REPS-001 | SRC-0100, SRC-0108, SRC-0101, SRC-0102, SRC-0103 | Klucz C poprawny. Scenariusz z lekkim ciężarem opiera się na „blisko upadku” (C-02: dowody dotyczą serii do upadku; Lasevicius 2022) i „podobnej” hipertrofii (C-03); W2 „lekkie hantle wystarczą” – ekstrapolacja poza dane (≤30% 1RM, długi okres). |
| IT-M1-02-10 | REVISION REQUIRED | MEDIUM | CL-PROG-003 | SRC-0108, SRC-0100 | Numeric poprawny: 2,5 kg × 156 = 390 kg; full [350, 400] obejmuje wariant 5 lb (780 lb ≈ 354 kg); partial rozłączne; feedback below/above spójny. W1.expert/W2 – ten sam sporny, nieudokumentowany model nerwowy → hipertrofia co w IT-08; niepowiązane CL-RATE-002. |
| IT-M1-02-51 | REVISION REQUIRED | MEDIUM | CL-PROG-001, CL-PROG-003 | SRC-0100, SRC-0108 | Klucz C poprawny, dystraktory błędne. W1.expert/W2 podają konieczność progresji w najsilniejszej formie („potrzebne jest”, „warunkiem długoterminowych postępów”) w pytaniu o to, co „zgodne z badaniami”; bez zastrzeżeń. EN W2: 5 lb × 156 ≠ 860 lb; nieudokumentowane „nauka ruchu”. |
| IT-M1-02-61 | REVISION REQUIRED | MEDIUM | CL-PROG-001, CL-PROG-003, CL-RIR-001 | SRC-0100, SRC-0108, SRC-0107, SRC-0106, SRC-0105 | Klucz B poprawny w ramach scenariusza (zapas podany jako fakt). Uogólniona reguła „wzrost zapasu = wzrost możliwości o ok. 2 powtórzenia” pomija błąd szacunku RIR (Halperin 2022: ~1 powt., I² ≈ 98%, gorsza trafność dalej od upadku) i zmienność dzień do dnia – nadmierna precyzja. |
| IT-M1-02-71 | PASS WITH NOTES | LOW | CL-PROG-001, CL-PROG-003, CL-REPS-001 | SRC-0100, SRC-0108, SRC-0101, SRC-0102, SRC-0103 | Klucz C poprawny (15 powt. przy podobnym RIR = postęp; skok 10→12 kg = +20% – poprawne). Uwagi LOW: „warunkiem” (C-06), „blisko upadku” (C-02/C-03), „różnice między programami niewielkie” (C-07, niepowiązane), nieudokumentowane „technika i koordynacja”. |

### Szczegóły problemów

#### M1-02-P01 · LOW · IT-M1-02-01 · pola `localizations.pl.option_texts.A.feedback`, `localizations.pl.w1.simple` (analogicznie EN)
- **Claim / source:** CL-PROG-001 (C-06), SRC-0100, SRC-0108
- **OBECNIE:** „Mięśnie dostosowują się do treningu, więc żeby dalej rosły, trening musi z czasem stawiać większe wymagania.”; W1.simple: „Dlatego trening musi stopniowo stawiać więcej: większy ciężar, więcej powtórzeń albo dodatkową serię.”
- **PROBLEM:** Dziedziczone z C-06. Konieczności progresji nie testowano wprost: SRC-0108 (Plotkin 2022) porównuje dwie formy progresji, a nie progresję z jej brakiem (INDIRECT); ACSM 2026 zaleca trening progresywny (PARTIAL, dosłowne brzmienie zalecenia niezweryfikowane). Pytanie samo zawiera zastrzeżenie w W2 („choć niewiele badań porównuje wprost trening z progresją i bez niej”), dlatego LOW.
- **PROPONOWANA KOREKTA:** Feedback A: „…więc żeby dalej rosły, zaleca się, by trening z czasem stawiał większe wymagania.” W1.simple: „Dlatego zaleca się stopniowo stawiać więcej: …”. Analogicznie w EN („is recommended to” zamiast „has to”).
- **Pewność oceny:** wysoka
- **Weryfikacja:** CLAIMS_AUDIT C-06; dossier G3a (Plotkin → CL-PROG-001 INDIRECT), G1 (ACSM → PARTIAL).

#### M1-02-P02 · LOW · IT-M1-02-01 · pole `localizations.pl.w2` (analogicznie EN)
- **Claim / source:** brak (żadne twierdzenie bazy nie obejmuje adaptacji nerwowych)
- **OBECNIE:** „Na początku ciężar potrafi rosnąć prawie z treningu na trening, bo szybko poprawiają się technika i koordynacja.”
- **PROBLEM:** Nieudokumentowane zdanie mechanistyczne w W2. Merytorycznie zgodne z głównym nurtem (wczesny wzrost siły w dużej części z adaptacji nerwowych i uczenia się ruchu) [WIEDZA: np. Folland i Williams 2007, Sports Med – przegląd wkładu adaptacji morfologicznych i nerwowych], ale bez twierdzenia i źródła w bazie. Nie wpływa na klucz.
- **PROPONOWANA KOREKTA:** Dodać twierdzenie o wczesnych adaptacjach nerwowych ze źródłem przeglądowym i powiązać je z pytaniem; brzmienie może zostać, ewentualnie „…bo duża część wczesnej poprawy siły to nauka ruchu: technika i koordynacja”.
- **Pewność oceny:** umiarkowana
- **Weryfikacja:** [WIEDZA]; brak w CLAIMS_AUDIT i dossier.

#### M1-02-P03 · LOW · IT-M1-02-02 · pola `localizations.pl.w1.expert`, `localizations.pl.option_texts.D.feedback` (analogicznie EN)
- **Claim / source:** CL-PROG-001 (C-06), pośrednio CL-EFF-001 (niepowiązane); SRC-0100, SRC-0108
- **OBECNIE:** W1.expert: „Stały bodziec traci skuteczność, bo ta sama praca oznacza coraz mniejszy wysiłek względny.”; D: „Gdy jednak mięśnie się dostosują, te same serie stają się łatwiejsze i przestają być wyzwaniem, więc przyrosty zwalniają.”
- **PROBLEM:** Mechanizm podany jako ustalony fakt, a w całym pytaniu nie ma informacji, że to wniosek z mechanizmu i z pośrednich danych o bliskości upadku (Robinson 2024 – RIR szacowane, analiza eksploracyjna), a nie z bezpośrednich porównań. Peryferyjne wobec klucza (pytanie definicyjne), dlatego LOW.
- **PROPONOWANA KOREKTA:** „Stały bodziec najpewniej traci skuteczność, bo ta sama praca oznacza coraz mniejszy wysiłek względny. To wniosek z badań nad wysiłkiem, bo bezpośrednich porównań treningu z progresją i bez niej jest mało.”
- **Pewność oceny:** wysoka
- **Weryfikacja:** CLAIMS_AUDIT C-06, C-27; dossier G1 (Robinson 2024).

#### M1-02-P04 · LOW · IT-M1-02-03 · pola `localizations.pl.w0`, `localizations.pl.w1.simple`, `localizations.pl.option_texts.A.feedback` (analogicznie EN)
- **Claim / source:** CL-PROG-001 (C-06), SRC-0100, SRC-0108
- **OBECNIE:** W0: „Bez stopniowego zwiększania wymagań przyrosty po kilku miesiącach zwykle zwalniają albo stają.”; W1.simple: „Żeby mięśnie dalej rosły, wymagania trzeba stopniowo podnosić.”
- **PROBLEM:** (1) C-06 (konieczność) – złagodzone w W1.expert, dlatego LOW. (2) Ramy czasowe „po kilku miesiącach” nie mają źródła (brak badań ze stałym obciążeniem przez miesiące). (3) W0 sugeruje, że spowolnienie wynika wyłącznie z braku progresji, tymczasem przyrosty zwalniają także przy progresji (CL-RATE-002; przegląd mechanizmów plateau: „The Plateau in Muscle Growth with Resistance Training: An Exploration of Possible Mechanisms”, Sports Med [SEARCH – tylko tytuł]). Klucz A („najpewniej zwolnią”) pozostaje poprawny niezależnie od mechanizmu.
- **PROPONOWANA KOREKTA:** W0: „Bez stopniowego zwiększania wymagań przyrosty po kilku miesiącach najpewniej wyraźnie zwolnią, a z czasem mogą stanąć.” W1.simple: „Żeby mięśnie dalej rosły, zaleca się stopniowo podnosić wymagania.”
- **Pewność oceny:** umiarkowana-wysoka
- **Weryfikacja:** CLAIMS_AUDIT C-06, C-15; WebSearch (link.springer.com/article/10.1007/s40279-023-01932-y – tytuł).

#### M1-02-P05 · LOW · IT-M1-02-04 · pole `localizations.pl.w1.simple` (analogicznie EN)
- **Claim / source:** CL-PROG-001 (C-06), SRC-0100, SRC-0108
- **OBECNIE:** „Dlatego trzeba stopniowo dokładać ciężar, powtórzenia albo serie.”
- **PROBLEM:** C-06, złagodzone w W2 („choć długich badań porównujących wprost trening z progresją i bez niej jest niewiele”), dlatego LOW. Informacyjnie: klucz B to najlepsze z podanych wyjaśnień, ale nie jedyna przyczyna spowolnienia (W2 poprawnie to zaznacza).
- **PROPONOWANA KOREKTA:** „Dlatego zaleca się stopniowo dokładać ciężar, powtórzenia albo serie.”
- **Pewność oceny:** wysoka
- **Weryfikacja:** CLAIMS_AUDIT C-06.

#### M1-02-P06 · LOW · IT-M1-02-05 · pola `localizations.pl.w1.expert`, `localizations.pl.w2` (analogicznie EN)
- **Claim / source:** brak twierdzenia (CL-PROG-003 i CL-DPRG-003 obejmują mit i arytmetykę, nie mechanizm ani czas trwania fazy liniowej)
- **OBECNIE:** W1.expert: „Liniowe dokładanie ciężaru działa krótko, głównie u początkujących; później obciążenie rośnie co kilka treningów lub tygodni.”; W2: „U początkujących ciężar rzeczywiście rośnie niemal z treningu na trening, bo szybko poprawiają się technika i koordynacja (…) Ten etap mija jednak po kilku tygodniach lub miesiącach.”
- **PROBLEM:** Mechanizm (adaptacje nerwowe) i czas trwania fazy („kilka tygodni lub miesięcy”) są nieudokumentowane w bazie. Są zgodne z głównym nurtem i praktyką [WIEDZA], ale czas trwania to obserwacja praktyczna, nie wynik badań. Nie wpływa na klucz.
- **PROPONOWANA KOREKTA:** Powiązać z twierdzeniem o adaptacjach nerwowych (patrz P02). W2: „…Jak długo trwa ten etap, zależy od osoby i ćwiczenia; zwykle są to tygodnie do kilku miesięcy (obserwacja z praktyki, nie wynik badań).”
- **Pewność oceny:** umiarkowana
- **Weryfikacja:** [WIEDZA]; brak w CLAIMS_AUDIT i dossier.

#### M1-02-P07 · LOW · IT-M1-02-05 · pole `localizations.pl.w2` (analogicznie EN)
- **Claim / source:** CL-PROG-002 (niepowiązane z pytaniem), SRC-0108
- **OBECNIE:** „Badanie z osobami trenującymi pokazało, że dokładanie powtórzeń przy tym samym ciężarze daje podobny przyrost mięśni jak dokładanie ciężaru, a dokładanie ciężaru dało nieco większy wzrost siły maksymalnej.”
- **PROBLEM:** Różnica w 1RM wynosiła 2,0 kg przy CI90% od −2,4 do 7,8 kg, czyli przedział obejmuje brak różnicy. CL-PROG-002 określa ją jako „o niepewnym znaczeniu praktycznym”, a IT-06 i IT-51 to zaznaczają. IT-05 podaje przewagę bez zastrzeżenia. Następne zdanie („wstępne dane z jednego, 8-tygodniowego badania”) częściowo łagodzi problem.
- **PROPONOWANA KOREKTA:** „…a dokładanie ciężaru dało nieco większy, ale niepewny wzrost siły maksymalnej.” Dodać CL-PROG-002 do `claims`.
- **Pewność oceny:** wysoka
- **Weryfikacja:** dossier G3a (Plotkin: CI90% 1RM −2,4 do 7,8 kg); CLAIMS_AUDIT tabela 0.2.

#### M1-02-P08 · LOW · IT-M1-02-06 · pole `localizations.pl.w2` (analogicznie EN)
- **Claim / source:** CL-REPS-001 (C-02, C-03), SRC-0101, SRC-0103, SRC-0102
- **OBECNIE:** „…przy seriach kończonych blisko upadku podobny przyrost dają bardzo różne liczby powtórzeń.”
- **PROBLEM:** Dziedziczone z C-02 i C-03. Metaanaliza (Schoenfeld 2017) i RCT (Morton 2016) dotyczą serii do upadku. Przy ok. 30% 1RM seria przerwana przed upadkiem dawała mniejszą hipertrofię (Lasevicius 2022). „Podobny” oznacza tu brak istotnej różnicy, bez testu równoważności. W scenariuszu Oli (8-12 powtórzeń, umiarkowany ciężar) uogólnienie jest peryferyjne, dlatego LOW.
- **PROPONOWANA KOREKTA:** „…przy seriach kończonych na upadku lub bardzo blisko niego podobny przyrost dawały w badaniach bardzo różne liczby powtórzeń (przy lekkich ciężarach seria musi dojść praktycznie do upadku).”
- **Pewność oceny:** wysoka
- **Weryfikacja:** CLAIMS_AUDIT C-02, C-03; EXTRA.md (Lasevicius 2022, PMID 31895290).

#### M1-02-P09 · MEDIUM · IT-M1-02-07 · pola `localizations.pl.option_texts.C.feedback`, `localizations.pl.w1.simple`, `localizations.pl.w1.expert` (analogicznie EN)
- **Claim / source:** CL-PROG-001 (C-06), SRC-0100, SRC-0108
- **OBECNIE:** C: „…te same serie są teraz łatwe, więc sama regularność nie wystarcza do dalszego wzrostu.”; W1.simple: „Rozwiązaniem jest stopniowe podnoszenie wymagań…”; W1.expert: „Zasada progresywnego przeciążenia, zalecana w syntezach badań, każe podnosić wymagania w miarę adaptacji. Wystarczy progresja powtórzeń lub obciążenia w obecnych ćwiczeniach; zmiana całego planu nie usuwa przyczyny zastoju.”
- **PROBLEM:** Konieczność („nie wystarcza”) i wystarczalność („Wystarczy”, „Rozwiązaniem jest”) są podane jako pewne. (1) Konieczność dziedziczy C-06: nie była testowana (SRC-0108 INDIRECT, ACSM – zalecenie). (2) „Wystarczy” wykracza poza dowody: żadne źródło nie testowało, czy sama progresja usuwa zastój, a sama baza (MC-402, MC-404) wymienia inne częste przyczyny zastoju (objętość, regenerację, żywienie, sen). W całym pytaniu brak informacji o ograniczonej podstawie empirycznej (brak W1/W2-owego zastrzeżenia, które mają IT-01, IT-03, IT-04). Klucz D pozostaje najlepszą odpowiedzią: rekomendacja jest rozsądna i zgodna z ACSM.
- **PROPONOWANA KOREKTA:** C: „…więc sama regularność najpewniej nie wystarczy do dalszego wzrostu.” W1.simple: „Najprostszym pierwszym krokiem jest stopniowe podnoszenie wymagań…”. W1.expert: „Zasada progresywnego przeciążenia, zalecana w syntezach badań, każe podnosić wymagania w miarę adaptacji. Jest spójna z literaturą, choć rzadko testowano ją wprost. Pierwszym krokiem jest progresja powtórzeń lub obciążenia w obecnych ćwiczeniach, bo zmiana całego planu nie usuwa przyczyny zastoju. Jeśli mimo progresji postęp nie wraca, warto sprawdzić objętość, regenerację, żywienie i sen.” Analogicznie w EN („is enough” → „is the first step”).
- **Pewność oceny:** umiarkowana-wysoka
- **Weryfikacja:** CLAIMS_AUDIT C-06; dossier G1, G3a; spójność z MC-402/MC-404.

#### M1-02-P10 · MEDIUM · IT-M1-02-08 · pola `localizations.pl.w1.expert`, `localizations.pl.w2` (analogicznie EN)
- **Claim / source:** brak twierdzenia (CL-PROG-003/CL-PROG-001 nie obejmują mechanizmu); SRC-0108, SRC-0100 nie dotyczą tej tezy
- **OBECNIE:** W1.expert: „Liniowa progresja obciążenia działa krótko, w dużej mierze dzięki szybkiej poprawie techniki i koordynacji u początkujących.”; W2: „Dlaczego etap szybkiego dokładania się kończy? W pierwszych tygodniach siła rośnie w dużej mierze dzięki nauce ruchu: lepszej technice i koordynacji. To pozwala dokładać ciężar niemal co trening. Później wzrost siły coraz bardziej zależy od przyrostu mięśni, a to proces dużo wolniejszy.”
- **PROBLEM:** Rdzeń wyjaśnienia w W2 opiera się na modelu, który nie ma w bazie ani twierdzenia, ani źródła. Część o wczesnych adaptacjach nerwowych jest zgodna z głównym nurtem [WIEDZA]. Teza „później siła coraz bardziej zależy od przyrostu mięśni” to klasyczny schemat, a nie zmierzona zależność, i jest przedmiotem otwartego sporu. Loenneke, Buckner, Dankel i Abe (Sports Med 2019; PMID 31020548) argumentują, że zmiany wielkości mięśnia nie przyczyniają się do zmian siły. Taber, Vigotsky, Nuckols i Haun (Sports Med 2019;49(7):993-997) uważają hipertrofię za przyczynę współdziałającą [SEARCH]. Poza tym koniec progresji liniowej ma też prostsze przyczyny: malejące przyrosty w miarę zbliżania się do bieżących możliwości i narastające zmęczenie. Nieudokumentowane, nieoczywiste zdanie mechanistyczne jest podane jako fakt, więc MEDIUM. Klucz B nie jest zagrożony.
- **PROPONOWANA KOREKTA:** W2: „Dlaczego etap szybkiego dokładania się kończy? W pierwszych tygodniach duża część wzrostu siły to nauka ruchu: lepsza technika i koordynacja. To pozwala dokładać ciężar niemal co trening. Z czasem tego łatwego zapasu ubywa, a dalszy wzrost siły jest wolniejszy, bo zależy od wolniejszych adaptacji, m.in. od przyrostu mięśni (jak duży jest ich udział, wciąż się dyskutuje).” W1.expert: „Liniowa progresja obciążenia działa krótko; u początkujących w dużej mierze dzięki szybkiej nauce ruchu.” Dodać twierdzenie o adaptacjach nerwowych i morfologicznych ze źródłem przeglądowym i powiązać z pytaniem.
- **Pewność oceny:** umiarkowana
- **Weryfikacja:** WebSearch [https://pubmed.ncbi.nlm.nih.gov/31020548/ ; https://link.springer.com/article/10.1007/s40279-019-01107-8]; [WIEDZA] Folland i Williams 2007 (Sports Med).

#### M1-02-P11 · LOW · IT-M1-02-08 · pola `localizations.pl.option_texts.B.feedback`, `localizations.pl.w1.apply`, `localizations.pl.w2` (analogicznie EN)
- **Claim / source:** brak (praktyka trenerska); CL-PROG-003
- **OBECNIE:** Klucz B: „Zostać przy tym ciężarze i dokładać powtórzenia, aż zrobi wszystkie serie”; W1.apply: „Gdy ciężar przestaje rosnąć co trening, zostań przy nim i dokładaj powtórzenia, a ciężar zwiększ dopiero po zrobieniu wszystkich serii.”
- **PROBLEM:** Według kontekstu przy obecnym ciężarze Tomek zrobił 3 powtórzenia, a technika w ostatniej serii „się sypała”. Feedback i W1.apply nie mówią, by kończyć serię przed rozpadem techniki, ani nie wspominają o cofnięciu ciężaru o jeden skok, co jest powszechną praktyką trenerską. Dowody na związek rozpadu techniki z urazami są słabe, więc to kwestia ostrożności (przysiad ze sztangą, początkujący), a nie błąd klucza. B nadal jest najlepszą opcją.
- **PROPONOWANA KOREKTA:** Feedback B: „…Teraz postępem jest także każde dodatkowe powtórzenie przy podobnym wysiłku i dobrej technice. Serię warto kończyć, zanim technika się rozpadnie, a jeśli obecny ciężar jest za duży na poprawne powtórzenia, można cofnąć się o jeden skok. Gdy zrobi 3 serie po 5 z dobrą techniką, może znów dołożyć ciężar.” W1.apply analogicznie.
- **Pewność oceny:** umiarkowana
- **Weryfikacja:** [WIEDZA] praktyka trenerska; brak źródła w bazie.

#### M1-02-P12 · MEDIUM · IT-M1-02-09 · pola `localizations.pl.option_texts.B.feedback`, `localizations.pl.option_texts.C.feedback`, `localizations.pl.w1.simple`, `localizations.pl.w1.expert` (analogicznie EN)
- **Claim / source:** CL-REPS-001 (C-02, C-03), SRC-0101, SRC-0102, SRC-0103, SRC-0100
- **OBECNIE:** B: „Badania pokazują jednak, że przy seriach kończonych blisko upadku lekkie ciężary i wysokie powtórzenia dają podobny przyrost mięśni jak ciężkie.”; C: „Przy seriach kończonych blisko upadku mięśnie rosną w szerokim zakresie powtórzeń, także przy 20 i więcej powtórzeniach w serii.”; W1.expert: „Metaanalizy pokazują podobną hipertrofię przy lekkich (od ok. 30% 1RM) i ciężkich obciążeniach, jeśli serie kończą się blisko upadku.”
- **PROBLEM:** C-02 i C-03 są tu dziedziczone w pytaniu, którego scenariusz dotyczy właśnie lekkiego ciężaru i wysokich powtórzeń, więc problem nie jest peryferyjny. Metaanaliza Schoenfeld 2017 włączała wyłącznie serie do chwilowego upadku, a Morton 2016 stosował serie do upadku. Przy ok. 30% 1RM seria przerwana wyraźnie przed upadkiem dawała mniejszą hipertrofię niż seria do upadku (Lasevicius 2022). „Blisko upadku” przy lekkich ciężarach nie ma więc bezpośredniego wsparcia, a W1.expert błędnie opisuje kryterium metaanaliz. „Podobny” to brak istotnej różnicy w małych, krótkich badaniach, bez testu równoważności. Ania ma przy tym oceniać zapas przy 20-30 powtórzeniach, gdzie szacunki RIR są najmniej trafne (Halperin 2022), więc łatwo zatrzyma się za daleko od upadku.
- **PROPONOWANA KOREKTA:** B: „…Badania pokazują jednak, że przy seriach kończonych na upadku lub tuż przed nim lekkie ciężary i wysokie powtórzenia dają przyrost mięśni zbliżony do ciężkich.” W1.expert: „Metaanalizy nie wykazały istotnej różnicy w hipertrofii między lekkimi (od ok. 30% 1RM) a ciężkimi obciążeniami, gdy serie kończono na upadku. Przy lekkich ciężarach seria powinna dojść praktycznie do upadku (0-1 powtórzenie w zapasie).” C i W1.simple analogicznie („bardzo blisko upadku”, „praktycznie do upadku”).
- **Pewność oceny:** wysoka
- **Weryfikacja:** CLAIMS_AUDIT C-02, C-03; dossier G1 (Schoenfeld 2017 – kryterium upadku); EXTRA.md (Lasevicius 2022, Halperin 2022).

#### M1-02-P13 · MEDIUM · IT-M1-02-09 · pole `localizations.pl.w2` (analogicznie EN)
- **Claim / source:** CL-REPS-001 (applicability), SRC-0101, SRC-0102
- **OBECNIE:** „Do siły maksymalnej lepsze są większe ciężary, ale celem Ani jest przyrost mięśni, a do tego lekkie hantle wystarczą.”
- **PROBLEM:** „Wystarczą” to ekstrapolacja przedstawiona jako fakt. (1) Dla ok. 30% 1RM badań jest mało, a poniżej ok. 30% 1RM bardzo mało (applicability CL-REPS-001). Para hantli 2×10 kg w przysiadzie może u trenującej osoby być blisko tego progu albo poniżej niego, zwłaszcza w miarę postępów. (2) Badania trwały 6-12 tygodni i brak danych, że długotrwała progresja wyłącznie przez powtórzenia z tym samym lekkim ciężarem (serie powyżej 30 powtórzeń) wystarcza. W2 sam proponuje wersję jednonóż, która w praktyce zwiększa względne obciążenie. Pominięte ograniczenie, więc MEDIUM.
- **PROPONOWANA KOREKTA:** „…ale celem Ani jest przyrost mięśni, a do tego lekkie hantle mogą wystarczyć, jeśli serie będą kończyć się tuż przed upadkiem. Gdy powtórzeń robi się bardzo dużo (np. ponad 30), lepiej zwiększyć trudność ćwiczenia, np. przejść na wersję na jednej nodze, bo dla bardzo lekkich obciążeń badań jest mało.”
- **Pewność oceny:** umiarkowana-wysoka
- **Weryfikacja:** CLAIMS_AUDIT C-02, C-03; applicability CL-REPS-001; EXTRA.md (Lasevicius 2022).

#### M1-02-P14 · MEDIUM · IT-M1-02-10 · pola `localizations.pl.w1.expert`, `localizations.pl.w2` (analogicznie EN)
- **Claim / source:** brak twierdzenia dla mechanizmu; CL-RATE-002 (C-15) niepowiązane; SRC-0108, SRC-0100
- **OBECNIE:** W1.expert: „Liniowa progresja obciążenia to krótki etap, oparty w dużej mierze na szybkiej poprawie techniki i koordynacji.”; W2: „U osób zaczynających trening siła rośnie w pierwszych tygodniach w dużej mierze dzięki nauce ruchu: lepszej technice i koordynacji. (…) Później siła coraz bardziej zależy od przyrostu mięśni, a ten jest powolny: u osób trenujących od lat postępy ocenia się raczej w miesiącach niż w tygodniach.”
- **PROBLEM:** Ten sam nieudokumentowany i sporny model co w P10 (Loenneke i in. 2019 vs Taber i in. 2019). Dodatkowo zdanie o osobach trenujących od lat korzysta z CL-RATE-002, które nie jest powiązane z pytaniem i ma problem C-15 (teza „dużo wolniej” opiera się na jednym małym, nierandomizowanym badaniu). Część numeryczna jest poprawna: 2,5 kg × 156 = 390 kg; 5 lb × 156 = 780 lb ≈ 354 kg mieści się w przedziale full [350, 400]; partial [300-349] i [401-450] są rozłączne; feedback below/above jest spójny.
- **PROPONOWANA KOREKTA:** Jak w P10. W1.expert: „Liniowa progresja obciążenia to krótki etap; u początkujących w dużej mierze dzięki szybkiej nauce ruchu.” W2: „…Z czasem dalszy wzrost siły jest wolniejszy, bo zależy od wolniejszych adaptacji, m.in. od przyrostu mięśni (ich udział wciąż się dyskutuje). U osób trenujących od lat postępy lepiej oceniać w skali miesięcy.” Dodać CL-RATE-002 do `claims`.
- **Pewność oceny:** umiarkowana
- **Weryfikacja:** WebSearch (jak P10); CLAIMS_AUDIT C-15; obliczenia własne.

#### M1-02-P15 · MEDIUM · IT-M1-02-51 · pola `localizations.pl.w1.expert`, `localizations.pl.w2` (analogicznie EN)
- **Claim / source:** CL-PROG-001 (C-06), SRC-0100, SRC-0108
- **OBECNIE:** W1.expert: „Adaptacja zmniejsza względną trudność stałego bodźca, więc do dalszych przyrostów masy i siły potrzebne jest stopniowe zwiększanie wymagań.”; W2: „Progresywne przeciążenie nie jest osobną metodą, tylko warunkiem długoterminowych postępów.”
- **PROBLEM:** Pytanie przejmuje C-06 w najsilniejszej formie („warunkiem”, „potrzebne jest”). Stem pyta, co jest „zgodne z badaniami”, więc sugeruje, że konieczność progresji wykazano w badaniach. Tak nie jest: brak długich RCT porównujących trening z progresją i bez niej, SRC-0108 to wsparcie INDIRECT, a ACSM daje zalecenie. W pytaniu nie ma żadnego zastrzeżenia.
- **PROPONOWANA KOREKTA:** W1.expert: „…więc do dalszych przyrostów masy i siły zaleca się stopniowe zwiększanie wymagań. Zasada jest zgodna z literaturą, choć jej konieczność rzadko testowano wprost.” W2: „Progresywne przeciążenie nie jest osobną metodą, tylko zasadą, na której opierają się zalecenia dotyczące długoterminowych postępów.” Analogicznie w EN („is required” / „the condition for” → „is recommended” / „the principle behind”).
- **Pewność oceny:** wysoka
- **Weryfikacja:** CLAIMS_AUDIT C-06; dossier G3a, G1.

#### M1-02-P16 · LOW · IT-M1-02-51 · pole `localizations.pl.w2` (analogicznie EN)
- **Claim / source:** brak twierdzenia
- **OBECNIE:** „Na początku ciężar rośnie szybko, bo duża część poprawy to nauka ruchu.”
- **PROBLEM:** Jak P02: nieudokumentowane w bazie, merytorycznie zgodne z głównym nurtem [WIEDZA].
- **PROPONOWANA KOREKTA:** Powiązać z twierdzeniem o adaptacjach nerwowych (patrz P02); brzmienie może zostać.
- **Pewność oceny:** umiarkowana
- **Weryfikacja:** [WIEDZA].

#### M1-02-P17 · LOW · IT-M1-02-51 · pole `localizations.en.w2`
- **Claim / source:** CL-PROG-003 (arytmetyka jak w CL-DPRG-003)
- **OBECNIE:** „…adding weight every session becomes impossible: 5 lb (2.5 kg) three times a week would add about 860 lb (390 kg) in a year.”
- **PROBLEM:** W EN jednostką podstawową jest 5 lb, a 5 lb × 156 = 780 lb (ok. 354 kg), nie 860 lb. 860 lb to przeliczenie 390 kg (2,5 kg × 156). Liczby są te same co w PL, ale rachunek w EN jest wewnętrznie niespójny (ok. 10%). Przekaz się nie zmienia. IT-10 poprawnie podaje zakres 780-860 lb.
- **PROPONOWANA KOREKTA:** „…2.5 kg (about 5 lb) three times a week would add about 390 kg (about 860 lb) in a year” (kolejność jak w PL) albo „…about 780-860 lb (350-390 kg)”.
- **Pewność oceny:** wysoka
- **Weryfikacja:** obliczenie własne.

#### M1-02-P18 · MEDIUM · IT-M1-02-61 · pola `localizations.pl.option_texts.A.feedback`, `localizations.pl.option_texts.B.feedback`, `localizations.pl.w1.expert`, `localizations.pl.w2` (analogicznie EN)
- **Claim / source:** CL-RIR-001 (SRC-0107, SRC-0106, SRC-0105); CL-RIR-002 (SRC-0106, C-29) użyte, ale niepowiązane
- **OBECNIE:** A: „Ta sama praca wykonana z większym zapasem oznacza jednak, że Marta jest silniejsza…”; W1.expert: „Wzrost zapasu przy tej samej pracy oznacza wzrost wydolności.”; W2: „Dziś te same serie kończą się ok. 3 powtórzenia przed upadkiem, więc jej możliwości wzrosły o ok. 2 powtórzenia. (…) Zapas warto oceniać uczciwie, bo ludzie zwykle zaniżają go o ok. jedno powtórzenie.”
- **PROBLEM:** W scenariuszu zapas podano jako fakt, więc klucz B jest poprawny i najlepszy. Pytanie uczy jednak praktycznej reguły (W1.apply: zapisuj zapas, żeby wykrywać postęp), a w praktyce RIR jest szacunkiem. W metaanalizie Halperin 2022 średni błąd wynosił ok. 0,95 powtórzenia (95% CI 0,17-1,73) przy ogromnej niejednorodności (I² ≈ 98%), a trafność spada wraz z odległością od upadku, więc „3 w zapasie” jest mniej pewne niż „1”. Różnica 2 powtórzeń z jednej sesji mieści się więc w typowym błędzie szacunku i w zmienności z dnia na dzień. „Oznacza” i „wzrosły o ok. 2 powtórzenia” to nadmierna pewność i precyzja. Zdanie o zaniżaniu opisuje tylko średnie przesunięcie, które przy porównaniu tej samej osoby częściowo się znosi. Nie zastępuje informacji o błędzie losowym, a „zwykle” powinno brzmieć „średnio” (duża rozpiętość).
- **PROPONOWANA KOREKTA:** W2: „…Dziś te same serie kończą się ok. 3 powtórzenia przed upadkiem, więc jej możliwości najpewniej wzrosły. Zapas to jednak szacunek: ludzie mylą się w nim średnio o ok. jedno powtórzenie, a różnice między osobami i treningami są duże, zwłaszcza dalej od upadku. Zmianę o 1-2 powtórzenia warto więc potwierdzić na kolejnych treningach, najprościej dokładając powtórzenia albo ciężar i sprawdzając, czy seria nadal kończy się z podobnym zapasem.” W1.expert: „Wzrost zapasu przy tej samej pracy, jeśli utrzymuje się na kolejnych treningach, najpewniej oznacza wzrost możliwości.” Feedback A: „…oznacza najpewniej, że Marta jest silniejsza…”. Dodać CL-RIR-002 do `claims`.
- **Pewność oceny:** umiarkowana
- **Weryfikacja:** CLAIMS_AUDIT tabela 0.2 (Halperin 2022), C-29; EXTRA.md.

#### M1-02-P19 · LOW · IT-M1-02-71 · pole `localizations.pl.w1.expert` (analogicznie EN)
- **Claim / source:** CL-PROG-001 (C-06), SRC-0100, SRC-0108
- **OBECNIE:** „Stopniowe zwiększanie wymagań jest warunkiem dalszych przyrostów, ale nie musi oznaczać większego ciężaru na każdym treningu.”
- **PROBLEM:** C-06 w pojedynczym zdaniu, peryferyjnym wobec głównej tezy pytania (więcej powtórzeń to też postęp), dlatego LOW.
- **PROPONOWANA KOREKTA:** „Stopniowe zwiększanie wymagań to zalecana droga do dalszych przyrostów, ale nie musi oznaczać…”.
- **Pewność oceny:** wysoka
- **Weryfikacja:** CLAIMS_AUDIT C-06.

#### M1-02-P20 · LOW · IT-M1-02-71 · pola `localizations.pl.option_texts.B.feedback`, `localizations.pl.w2` (analogicznie EN)
- **Claim / source:** CL-REPS-001 (C-02, C-03), SRC-0101, SRC-0103
- **OBECNIE:** B: „Gdy serie kończą się blisko upadku, podobny przyrost dają jednak zarówno serie po 6-12, jak i po 20 i więcej powtórzeń.”; W2: „…gdy serie kończą się blisko upadku, podobny przyrost dają serie po 6-12 i po 20 i więcej powtórzeń.”
- **PROBLEM:** Jak P08. W scenariuszu (15 powtórzeń, umiarkowany ciężar) problem jest peryferyjny, dlatego LOW.
- **PROPONOWANA KOREKTA:** „Gdy serie kończą się na upadku lub bardzo blisko niego, w badaniach podobny przyrost dawały…”.
- **Pewność oceny:** wysoka
- **Weryfikacja:** CLAIMS_AUDIT C-02, C-03.

#### M1-02-P21 · LOW · IT-M1-02-71 · pole `localizations.pl.option_texts.D.feedback` (analogicznie EN)
- **Claim / source:** CL-CONS-001 (C-07), niepowiązane z pytaniem; SRC-0102, SRC-0100
- **OBECNIE:** „Różnice między rozsądnymi programami są jednak zwykle niewielkie, a plan Oli nadal działa…”
- **PROBLEM:** Dziedziczone z C-07. Dla przyrostu masy teza jest zgodna ze źródłami, ale dla siły maksymalnej różnice nie są niewielkie (ciężar ≥80% 1RM, ACSM 2026, Currier 2023). Kontekst nie precyzuje celu Oli. Dotyczy dystraktora, dlatego LOW.
- **PROPONOWANA KOREKTA:** „Różnice między rozsądnymi programami w przyroście mięśni są jednak zwykle niewielkie…”. Dodać CL-CONS-001 do `claims`.
- **Pewność oceny:** wysoka
- **Weryfikacja:** CLAIMS_AUDIT C-07; dossier G1.

#### M1-02-P22 · LOW · IT-M1-02-71 · pole `localizations.pl.w2` (analogicznie EN)
- **Claim / source:** brak twierdzenia
- **OBECNIE:** „U początkujących ciężar rośnie szybko, bo poprawia się technika i koordynacja, ale po kilku miesiącach tempo naturalnie spada.”
- **PROBLEM:** Jak P02 i P06: mechanizm i czas trwania fazy są nieudokumentowane w bazie, choć zgodne z głównym nurtem [WIEDZA].
- **PROPONOWANA KOREKTA:** Powiązać z twierdzeniem o adaptacjach nerwowych. „…bo duża część wczesnej poprawy to nauka ruchu; później tempo naturalnie spada.”
- **Pewność oceny:** umiarkowana
- **Weryfikacja:** [WIEDZA].

**Uwagi informacyjne (bez severity, nie liczone):**
- Powiązania `claims` są niepełne w całej karcie. Pytania wykorzystują treści twierdzeń, których nie wymieniają: CL-EFF-001 (IT-01, -02, -07, -09, -61), CL-TENS-001/-003 (pompa: IT-03, -06, -09), CL-DOMS-001 (zakwasy: IT-02, -03, -04, -06, -51, -61), CL-TENS-002 (hormony: IT-04, -06), CL-CONF-001 (zaskakiwanie mięśni: IT-01, -04, -07, -51), CL-DOSE-001 (malejące korzyści z serii: IT-02), CL-DPRG-001/-003 (podwójna progresja, arytmetyka: IT-02, -05, -07, -08, -10, -51, -71), CL-REPS-002 (IT-06, -09), CL-RATE-002 (IT-04, -10), CL-RIR-002 (IT-61), CL-CONS-001 (IT-71), CL-REST-* (IT-09 D). Skutek: rewizja tych twierdzeń (np. C-04 dla CL-DOMS-001, C-07, C-15) nie oznaczy tych pytań do przeglądu.
- IT-03 nie ma pola `w2` (para PAIR-M1-02-01, krok 1). Nie jest to błąd naukowy.
- IT-71: feedback klucza C odwołuje się do „górnej granicy zakresu” (10-15), której nie ma w kontekście. Zakres pojawia się dopiero w W2. Nie zmienia klucza.
- IT-04: klucz B jest najlepszy spośród opcji, ale spowolnienie przyrostów ma też inne mechanizmy (np. osłabienie odpowiedzi anabolicznej w miarę treningu; przegląd „The Plateau in Muscle Growth with Resistance Training…”, Sports Med [SEARCH – tytuł]). W2 częściowo to uwzględnia („przyrosty z czasem naturalnie zwalniają nawet przy dobrej progresji”).
- Wersje PL/EN: poza P17 nie stwierdzono zmian siły twierdzeń, liczb ani klucza. W IT-09 C w EN jest „much closer” zamiast „bliżej”; to bez znaczenia merytorycznego.
- Liczby i przeliczenia sprawdzone: 2,5 kg × 156 = 390 kg ≈ 860 lb; 5 lb × 156 = 780 lb ≈ 354 kg; 2,5 kg × 104 = 260 kg ≈ 573 lb (IT-08); 10→12 kg = +20% (IT-71); 12 kg ≈ 26 lb, 10 kg ≈ 22 lb, 18 kg ≈ 40 lb. Wszystkie są poprawne poza P17.

### Karta pojęcia i błędne przekonania

#### M1-02-K01 · MEDIUM · KC-M1-02 · pole `card.pl` / `card.en`
- **Claim / source:** CL-PROG-001 (C-06), SRC-0100, SRC-0108
- **OBECNIE:** „Dlatego trening musi stopniowo stawiać większe wymagania.” / „That is why training has to ask a little more over time.”
- **PROBLEM:** Główna teza karty podaje konieczność progresji jako pewnik, bez żadnego zastrzeżenia (dziedziczone z C-06). Karta jest podstawowym tekstem nauczającym dla wszystkich 13 pytań. Poza tym karta jest poprawna: mechanizm adaptacji, trzy dźwignie, spowolnienie tempa i zapisywanie ciężaru oraz powtórzeń są zgodne z dowodami i dobrą praktyką.
- **PROPONOWANA KOREKTA:** „Dlatego zaleca się, żeby trening stopniowo stawiał większe wymagania. To zasada zgodna z badaniami, choć rzadko testowana wprost.” Analogicznie w EN („That is why training is recommended to ask a little more over time; the principle fits the research, though it has rarely been tested directly.”).
- **Pewność oceny:** wysoka
- **Weryfikacja:** CLAIMS_AUDIT C-06.

#### M1-02-K02 · LOW · MC-610 · pole `refutation.pl` / `refutation.en`
- **Claim / source:** CL-PROG-001 (C-06)
- **OBECNIE:** „Regularność jest podstawą, ale do dalszego wzrostu trzeba stopniowo zwiększać wymagania: ciężar, powtórzenia albo serie.”
- **PROBLEM:** C-06, czyli konieczność podana jako pewnik. Etykieta „błędne przekonanie” dla tezy „wystarczy powtarzać ten sam trening” (ten sam ciężar i te same powtórzenia) jest obronialna mechanistycznie i zgodna z zaleceniami. Why_popular jest poprawne i uczciwie oddaje ziarno prawdy (ACSM 2026: „consistency over perfection”).
- **PROPONOWANA KOREKTA:** „…ale do dalszego wzrostu zaleca się stopniowo zwiększać wymagania: ciężar, powtórzenia albo serie.”
- **Pewność oceny:** wysoka
- **Weryfikacja:** CLAIMS_AUDIT C-06; dossier G1 (komunikat ACSM).

**MC-102:** brak istotnych problemów. Refutation jest zgodna z Plotkin 2022 („w badaniu z osobami trenującymi”) i nie przecenia wyniku.

**MC powiązane przez opcje (spoza karty) – tylko sygnalizacja, ocena należy do partii macierzystych, nie liczone:**
- MC-105 (KC-M1-04), refutation: „kończeniem serii kilka powtórzeń wcześniej” dziedziczy C-05 („kilka” szersze niż dane).
- MC-401 (KC-M4-03): why_popular przypisuje poprawę motywacji zmienności „zaplanowanej”, a wykazano ją dla zmienności losowej (C-16). Refutation („zbyt częsta rotacja może wręcz osłabiać efekty”) opiera się na słabych dowodach i jest wewnętrznie niespójna z poprzednim zdaniem (losowa zmiana dawała podobny przyrost).
- MC-103 (KC-M1-03): „20-30 powtórzeń… blisko upadku” dziedziczy C-02.
- MC-108 (KC-M1-06): „różnice między programami były zwykle niewielkie” dziedziczy C-07 (siła).
- MC-101 (KC-M1-01): pomija dowody eksperymentalne za i przeciw (C-01), ale sama teza jest poprawna.
- MC-404 (KC-M4-01): „Zbliżanie się do granicy możliwości trwa zwykle wiele lat” nie ma źródła w bazie.
- MC-109, MC-100, MC-206, MC-300, MC-402: z perspektywy tej partii brak uwag.

### Podsumowanie partii
- Pytania: PASS 0, PASS WITH NOTES 7, REVISION REQUIRED 6, FAIL 0, UNVERIFIED 0 (razem 13)
- Problemy (tylko w pytaniach): CRITICAL 0, HIGH 0, MEDIUM 7, LOW 15
- Problemy w karcie/MC (osobno): CRITICAL 0, HIGH 0, MEDIUM 1, LOW 1
- Ostatnie ID w partii: IT-M1-02-71
