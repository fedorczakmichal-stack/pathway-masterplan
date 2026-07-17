# Pathway — Living Map Masterplan

Publiczna, stała wersja planu wdrożenia Pathway do udostępniania i wspólnego przeglądu.

Strona: https://fedorczakmichal-stack.github.io/pathway-masterplan/

## Wersje

- `index.html` + `assets/` — aktualna, odchudzona wersja WEB.
- `offline/Pathway_Implementation_Masterplan.html` — aktualna, w pełni samodzielna wersja offline.
- `offline/Pathway_Implementation_Masterplan_OFFLINE.zip` — wersja offline do pobrania.
- `archive/2026-07-17-before-claude-max-budget/Pathway_Implementation_Masterplan.html` — wersja bezpośrednio sprzed przeliczenia całego planu pod Claude Max 5x + Claude Pro i szczegółowe pakiety QA.
- `archive/2026-07-17-before-table-padding-fix/Pathway_Implementation_Masterplan.html` — wersja bezpośrednio sprzed poprawy odstępów w tabelach i polach kosztowych.
- `archive/2026-07-17-before-mobile-metric-fix/Pathway_Implementation_Masterplan.html` — wersja bezpośrednio sprzed poprawy mobilnych kart budżetowych.
- `archive/2026-07-17-before-founder-brief/Pathway_Implementation_Masterplan.html` — wersja bezpośrednio sprzed Founder Brief, dokładnego budżetu, sześciu ekranów MVP i nowych bramek decyzyjnych.
- `archive/Pathway_Implementation_Masterplan_before_toc_and_budget_fix.html` — wersja bezpośrednio sprzed naprawy spisu treści i przebudowy budżetu founder-led.
- `archive/Pathway_Implementation_Masterplan_before_alignment_polish.html` — wersja bezpośrednio sprzed ostatnich poprawek wyrównania.
- `archive/Pathway_Implementation_Masterplan_Seasons_Backup.html` — archiwum wcześniejszej koncepcji Seasons.

Wersje WEB i offline pokazują tę samą treść. WEB ładuje obrazy i fonty z katalogu `assets/`, dlatego jest lżejszy; offline zawiera wszystko w jednym pliku i działa bez internetu.

## Kontrola zgodności

- aktualna WEB: `dca59a216dd0f26fb50211b04bf3946aaa209869f5559c0dd82e6feafa54f884`
- aktualna offline: `9f215ac0ee25d734af09b1d4696cccfafd294de5dddc816e9064ae81926b27b4`
- ZIP offline: `2e222d62f1a69eaf0a63008346dc5b0b92b884c285ce4bc84f81f6b98a6e0831`
- wersja sprzed przeliczenia Claude Max i QA: `a894008efb5d76d1e8d0c4ca646db4fe76407ee4a3563ef9ebd3d09d5df8a98c`
- wersja sprzed poprawy odstępów w tabelach: `c9850cdb8554edb331ae6fb686f2076a8ea340d163bb3c092f6d7928306a538b`
- wersja sprzed poprawy mobilnych kart budżetowych: `b2bdfba5641f34ed64f2c8243c7a41cb5cd29581fb38c30b64b2e2f15e0a66d9`
- wersja sprzed Founder Brief: `95f9624cdd7293f4abbad2e6ee73b958bc2ed282229112638e8a815d8284c74f`
- wersja sprzed naprawy spisu i budżetu: `c6317a1fccf3bc7bd0dbb30f93ff0e815f321b1670afecd95dcc7ec65e85118c`
- wersja sprzed poprawek wyrównania: `c19869da6aa336c5ef05dfc000a393d9a0212ec71629f9f3595eeac7fddadb4b`
- archiwum Seasons: `03fba2c00e3b99e0b3acb8c3ab1450f55cf74fc50d56f08eba7ae9afd3a63a70`

## Ostatnia kontrola jakości

- 64 bloki, 28 tabel, 8 wykresów i 3 karty metryk zgodne z modelem źródłowym.
- karty budżetowe sprawdzone w widokach 320, 375, 390, 430 i 1440 px;
- pełne etykiety i kwoty bez wielokropków, przycięć i nakładania na sąsiednie linie;
- wszystkie 28 nagłówków tabel ma jednakowy odstęp od ramki: 16 px na mobile i 24 px na desktopie;
- długie tytuły tabel nie nachodzą na przycisk menu;
- 18 stabilnych odnośników spisu treści, obsługa cofania/do przodu i aktywna sekcja;
- aktywna pozycja spisu ma jasny tekst, delikatne złote tło i stały lewy marker, dzięki czemu pozostaje czytelna podczas przewijania;
- bezpośrednie adresy z `#`, skróty Founder Brief i boczny spis wskazują tę samą widoczną sekcję także po przełączeniu pełnego czytnika;
- brak poziomego przepełnienia strony mobilnej;
- kwoty sprawdzone w źródle, kartach, wykresach i tabelach: 360 USD teraz, 1,5 tys. USD pełnej Walidacji V1, 9,8 tys. USD planu i 11,3 tys. USD koperty z rezerwą;
- Claude Max 5x (1 200 USD/rok w przeliczeniu) i Claude Pro (200 USD/rok) są jawnie wliczone, a QA rozdzielono na pakiet alfy 300 USD i pakiet bety z retestem 700 USD;
- pełna sekcja źródeł i obsługa klawiatury zachowane.
