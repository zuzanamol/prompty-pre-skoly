# Analýza používania Copilota: komu a akú podporu ponúknuť

## O čom to je
Prompt pomáha vedeniu školy, univerzity alebo koordinátorovi digitalizácie zistiť z údajov o používaní, ako ľudia Copilot reálne používajú. Výsledkom je predbežné rozdelenie používateľov do skupín a návrh, akú podporu alebo školenie ponúknuť každej z nich.

Nie je to hodnotenie ľudí, ale podklad na plánovanie ďalšej adopcie.

## Prompt
```
Analyzuj priloženú tabuľku s údajmi o používaní Microsoft Copilot. Cieľom je zistiť, ako ho ľudia používajú, a pripraviť podklad na plánovanie ďalšej podpory a školení.
Najprv skontroluj, čo jednotlivé stĺpce znamenajú, aké obdobie údaje pokrývajú a či rozlišujú Copilot Chat od ostatných funkcií Microsoft 365 Copilot. Ak význam údajov nie je jasný, vypýtaj si vysvetlenie. Pracuj iba s údajmi v tabuľke.
Odpovedz na otázky:

1. Koľko ľudí si Copilot aspoň vyskúšalo?
Uveď počet a podiel ľudí s aspoň jedným zaznamenaným použitím. Vysvetli, čo v tejto tabuľke považuješ za použitie a z akej skupiny počítaš podiel.
2. Kto sa k nemu vracia?
Identifikuj ľudí s opakovaným používaním v rôznych dňoch alebo týždňoch podľa dostupných údajov. Rozlišuj jednorazovú aktivitu od používania rozloženého v čase.
3. Vidíme po školení iba krátky nárast alebo pokračujúce používanie?
Porovnaj používanie pred školením, krátko po ňom a v ďalších týždňoch. Ak dátum školenia chýba, vypýtaj si ho. Ak nemáme dostatočné časové údaje, jasne uveď, že to nemožno vyhodnotiť. Samotný nárast po školení nepovažuj za dôkaz, že ho spôsobilo školenie.

Priprav predbežné rozdelenie používateľov:

* Pravidelné používanie – opakovaná aktivita rozložená počas sledovaného obdobia.
* Príležitostné používanie – ojedinelá alebo nepravidelná aktivita.
* Nezaznamenané používanie – v sledovanom období nie je zaznamenaná aktivita.

Konkrétne hranice kategórií navrhni podľa dĺžky sledovaného obdobia a podrobnosti údajov. Pred rozdelením ich stručne vysvetli. Chýbajúce údaje nepovažuj automaticky za nulové používanie. Ak tabuľka obsahuje iba súhrnný počet aktivít alebo dátum poslednej aktivity, neoznačuj pravidelnosť za spoľahlivo preukázanú.
Výstup priprav v tejto štruktúre:

1. Stručné zistenia – priame odpovede na tri otázky, podložené číslami.
2. Prehľad skupín – tabuľka: skupina | kritérium zaradenia | počet ľudí | podiel | odporúčaný ďalší krok.
3. Zaradenie jednotlivých používateľov – používateľ alebo ID | predbežná skupina | dôvod zaradenia. Nejasné prípady označ „nedostatok údajov“.
4. Vývoj používania – stručne opíš trend; ak to údaje umožňujú, doplň graf počtu aktívnych používateľov po týždňoch.
5. Čo potrebujeme vedieť pred ďalším školením – uveď chýbajúce informácie a vysvetli, ako ovplyvnia rozhodnutie. Zohľadni najmä pracovné roly, účasť na školení, prístupy a licencie, potreby používateľov a prekážky používania.
6. Odporúčanie – navrhni vhodnú podporu pre každú skupinu. Zváž praktický workshop, konzultácie, zdieľanie skúseností alebo pomoc s prístupom.

Píš po slovensky, stručne a zrozumiteľne. Oddeľ zistenia z dát od predpokladov. Z frekvencie používania nevyvodzuj kvalitu práce, motiváciu ani ochotu pomáhať kolegom. Aktívneho používateľa automaticky neoznačuj za championa a človeka bez zaznamenanej aktivity za odporcu AI.
```

## Využitie v praxi
- **Škola po úvodnom školení:** riaditeľ chce vedieť, či učitelia Copilot používajú aj mesiac po workshope, alebo išlo len o jednorazový záujem.
- **Plánovanie ďalšieho školenia:** koordinátor digitalizácie zistí, kto potrebuje základný workshop, kto skôr konzultáciu a kde je problém s prístupom alebo licenciou.
- **Univerzita alebo úrad:** tím adopcie pripraví podklad pre vedenie o tom, ako sa Copilot reálne používa naprieč pracoviskami.

## Ako na to
1. Pripravte tabuľku s údajmi o používaní (napr. export z reportu používania Copilota v Microsoft 365 admin centre alebo vlastnú evidenciu).
2. Mená nahraďte ID alebo údaje anonymizujte, ak to nie je nevyhnutné.
3. Otvorte Microsoft 365 Copilot Chat, priložte tabuľku a vložte prompt.
4. Ak sa Copilot opýta na význam stĺpcov alebo dátum školenia, doplňte ich.
5. Výsledok berte ako predbežný podklad a overte ho s ľuďmi, ktorí školenia vedú.

## Čo potrebujete
- Microsoft 365 Copilot Chat s možnosťou priložiť súbor
- Tabuľku s údajmi o používaní (ideálne s dátumami aktivity po dňoch alebo týždňoch)
- Dátum školenia, ak chcete vyhodnotiť jeho vplyv

## Dôležité
Pri údajoch o zamestnancoch dodržiavajte pravidlá ochrany osobných údajov vašej inštitúcie. Výsledok slúži na plánovanie podpory, nie na hodnotenie jednotlivcov.

## Autor
Zuzka Molčanová, EDU špecialistka, Aricoma

## História verzií
| Verzia | Dátum | Poznámka |
|---|---|---|
| 1.0 | 10/2026 | Prvé zverejnenie |
