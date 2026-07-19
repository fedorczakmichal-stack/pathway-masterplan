# Pathway — Living Map Masterplan

Publiczna, stała wersja planu wdrożenia Pathway do udostępniania i wspólnego przeglądu.

Strona: https://fedorczakmichal-stack.github.io/pathway-masterplan/

## Wersje

- `index.html` + `assets/` — aktualna, odchudzona wersja WEB.
- `offline/Pathway_Implementation_Masterplan.html` — aktualna, w pełni samodzielna wersja offline.
- `offline/Pathway_Implementation_Masterplan_OFFLINE.zip` — wersja offline do pobrania.
- `archive/2026-07-19-before-real-map-replan/Pathway_Implementation_Masterplan.html` — wersja bezpośrednio sprzed przebudowy planu pod prawdziwą mapę OSM, katalog miast demo, automatyczny MapPackage własnej okolicy oraz korektę kosztów pracy mapowej.
- `archive/2026-07-19-before-app-redesign-sync/Pathway_Implementation_Masterplan.html` — wersja bezpośrednio sprzed synchronizacji masterplanu z aktualną aplikacją Carlstadt, grafem ulic, klikalnymi milestone'ami i dwukrokowym kreatorem.
- `archive/2026-07-17-before-claude-max-budget/Pathway_Implementation_Masterplan.html` — wersja bezpośrednio sprzed przeliczenia całego planu pod Claude Max 5x + Claude Pro i szczegółowe pakiety QA.
- `archive/2026-07-17-before-table-padding-fix/Pathway_Implementation_Masterplan.html` — wersja bezpośrednio sprzed poprawy odstępów w tabelach i polach kosztowych.
- `archive/2026-07-17-before-mobile-metric-fix/Pathway_Implementation_Masterplan.html` — wersja bezpośrednio sprzed poprawy mobilnych kart budżetowych.
- `archive/2026-07-17-before-founder-brief/Pathway_Implementation_Masterplan.html` — wersja bezpośrednio sprzed Founder Brief, dokładnego budżetu, sześciu ekranów MVP i nowych bramek decyzyjnych.
- `archive/Pathway_Implementation_Masterplan_before_toc_and_budget_fix.html` — wersja bezpośrednio sprzed naprawy spisu treści i przebudowy budżetu founder-led.
- `archive/Pathway_Implementation_Masterplan_before_alignment_polish.html` — wersja bezpośrednio sprzed ostatnich poprawek wyrównania.
- `archive/Pathway_Implementation_Masterplan_Seasons_Backup.html` — archiwum wcześniejszej koncepcji Seasons.

Wersje WEB i offline pokazują tę samą treść. WEB ładuje obrazy i fonty z katalogu `assets/`, dlatego jest lżejszy; offline zawiera wszystko w jednym pliku i działa bez internetu.

## Kontrola zgodności

- aktualna WEB: `41a5d4bfa90c243b5da2dbe33305d570721ef49d2563e4d7b684a7f2a1fc16e4`
- aktualna offline: `f952c0c63fa83a16cd053c808b3ae6207b245b76e40e3f0c94f29b6727023407`
- ZIP offline: `38c5795035b08db52847f991b75bc4f9fa058f2cfa00a1c8479dd10118fa396d`
- manifest zasobów WEB: `ecf06c0e67f45324e3a86465c3b929835bf969213b8b0a998a84d047283a036c` — zawiera SHA-256 każdego fontu, logo, obrazu hero i ośmiu aktualnych ekranów aplikacji;
- wersja sprzed przebudowy pod prawdziwą mapę: `ce1f875a5d0ff31a6f2b7dd8c3c976411b5e5a3140292d46127f0359ebc45c17`
- wersja sprzed synchronizacji z aktualną aplikacją: `9f215ac0ee25d734af09b1d4696cccfafd294de5dddc816e9064ae81926b27b4`
- wersja sprzed przeliczenia Claude Max i QA: `a894008efb5d76d1e8d0c4ca646db4fe76407ee4a3563ef9ebd3d09d5df8a98c`
- wersja sprzed poprawy odstępów w tabelach: `c9850cdb8554edb331ae6fb686f2076a8ea340d163bb3c092f6d7928306a538b`
- wersja sprzed poprawy mobilnych kart budżetowych: `b2bdfba5641f34ed64f2c8243c7a41cb5cd29581fb38c30b64b2e2f15e0a66d9`
- wersja sprzed Founder Brief: `95f9624cdd7293f4abbad2e6ee73b958bc2ed282229112638e8a815d8284c74f`
- wersja sprzed naprawy spisu i budżetu: `c6317a1fccf3bc7bd0dbb30f93ff0e815f321b1670afecd95dcc7ec65e85118c`
- wersja sprzed poprawek wyrównania: `c19869da6aa336c5ef05dfc000a393d9a0212ec71629f9f3595eeac7fddadb4b`
- archiwum Seasons: `03fba2c00e3b99e0b3acb8c3ab1450f55cf74fc50d56f08eba7ae9afd3a63a70`

## Ostatnia kontrola jakości

- plan rozdziela trzy poziomy produktu: działający wariant Carlstadt, planowany katalog przygotowanych miast USA oraz pełną mapę własnej okolicy;
- opisano automatyczny pipeline `lokalizacja → geokodowanie → OSM → graf ulic → Maya i routing → Urban Nocturne → cache, manifest i QA`, bez ręcznego redrawu kolejnych miast;
- etap pilotażowy przed G4 korzysta z Carlstadt i lekkich prototypów OSM ze wspólnego stylu — bez artystycznego redrawu i ręcznej kalibracji rastra;
- payload czytnika i semantyczny fallback obejmują 6 doświadczeń MVP, 18 ekranów pierwszej wersji, 56 przypadków QA, 62 bloki, 28 tabel, 8 wykresów i 3 karty metryk;
- hero 1600×980 oraz osiem ekranów 390×844 pochodzą z aktualnej aplikacji Carlstadt; zachowują proporcje i nie są przycinane;
- widoki 320, 375, 390, 430 i 1440 px nie mają poziomego przepełnienia; tekst, karty i tabele nie nachodzą na siebie, a tabele pozostają w przewijanych kontenerach;
- 18 stabilnych odnośników spisu treści, skróty Founder Brief, bezpośrednie adresy z `#`, cofanie/do przodu i aktywna sekcja wskazują właściwe miejsca;
- nawigacja pozostaje otwarta jako pełny boczny spis na desktopie, a zwija się w jednoznaczny pasek „Nawigacja” dopiero przy szerokości 1180 px i mniejszej;
- bieżące funkcje demonstratora są oddzielone od planowanych ekranów wyboru miasta i własnej lokalizacji; biblioteka czterech szablonów bez udawania AI jest oznaczona jako zrealizowana;
- lokalizacja jest minimalizowana: bez śledzenia w tle, bez adresu domu w koncie i bez surowych współrzędnych w analityce; opisano zgodę, retencję, eksport, usunięcie, [attribution OSM/ODbL](https://www.openstreetmap.org/copyright) oraz ograniczenia [Nominatim](https://operations.osmfoundation.org/policies/nominatim/) i [standardowego serwera kafli](https://operations.osmfoundation.org/policies/tiles/);
- kwoty są zgodne w źródle, kartach, tabelach i wykresach: 360 USD teraz, 1,5 tys. USD Walidacji V1, 5,6 tys. USD do alfy, 9,6 tys. USD do bety, 10,8 tys. USD do startu, 11,2 tys. USD planu oraz 12,7 tys. USD koperty z rezerwą;
- changelog budżetu jest jawny: Alfa 3,2→4,1 tys. USD, Beta 3,5→4,0 tys. USD, Start bez zmiany 1,2 tys. USD, plan 9,8→11,2 tys. USD, koperta 11,3→12,7 tys. USD;
- wzrost o 1,4 tys. USD obejmuje wyłącznie 700 USD geo/OSM, 200 USD dostawcy i cache, 250 USD wielomiastowego QA oraz 250 USD privacy/ODbL; pensje founderów, Walidacja V1, Claude i rezerwa pozostają bez zmian;
- ZIP zawiera dokładnie jeden samodzielny HTML, którego SHA-256 jest identyczne z bieżącą wersją offline; manifest zawiera 12 zweryfikowanych zasobów WEB;
- pełna sekcja źródeł, obsługa klawiatury i równoważny widok listowy zostały zachowane.
