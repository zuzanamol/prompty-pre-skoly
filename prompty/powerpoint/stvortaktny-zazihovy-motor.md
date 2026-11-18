# Štvortaktný zážihový motor

## O čom to je

Prompt pre Copilot v PowerPointe vytvorí interaktívnu snímku, ktorá názorne vysvetlí stavbu a činnosť štvortaktného zážihového (benzínového) motora. Žiaci môžu preskúmať jednotlivé súčiastky, prepínať medzi zloženým a rozloženým pohľadom a spustiť animáciu pracovných dôb.

## Prompt

```text
Vytvor jednu interaktívnu vzdelávaciu snímku s nadpisom „Ako funguje štvortaktný motor“. Je určená žiakom základnej a strednej školy, preto používaj správne, ale jednoduché vysvetlenia.

Hlavná vizualizácia: V strede snímky zobraz prehľadný technický rez zjednodušeným jednovalcovým štvortaktným zážihovým (benzínovým) motorom. Zobraz tieto časti: valec, piest s piestnymi krúžkami, ojnica, kľukový hriadeľ, hlava valca, sací ventil, výfukový ventil, vačkový hriadeľ, zapaľovacia sviečka, sacie potrubie a výfukové potrubie. Zachovaj správne vzájomné polohy, spojenia a funkciu súčiastok. Piest sa pohybuje vo valci, ojnica spája piest s kľukovým hriadeľom a ventily riadia prúdenie cez hlavu valca.

Prepínanie pohľadu: Pridaj dve tlačidlá s presnými názvami „Zložený motor“ a „Rozložený motor“. V zloženom pohľade sú všetky súčiastky na správnom mieste a nadväzujú na seba. V rozloženom pohľade sú tie isté súčiastky plynulo vysunuté od seba pozdĺž jednej prehľadnej osi rozloženia. Zachovaj ich mierku a orientáciu, aby bolo zrejmé, kam každá časť patrí. Pri prepnutí sa súčiastky plynulo rozídu alebo vrátia na svoje miesto; neobjavujú sa ani nemiznú náhle. Prepnutie pohľadu nesmie zastaviť ani zmeniť práve prehrávanú pracovnú dobu.

Klikateľné súčiastky: Každú súčiastku alebo skupinu súčiastok zvýrazni po kliknutí a zobraz pri nej krátku kartu s názvom, účelom a pohybom. Použi jednoduché slová, najviac dve vety na kartu. Vysvetlenia:
- Valec: vedie piest a tvorí priestor, v ktorom sa zmes stláča a spaľuje; je pevne spojený s motorom.
- Piest s piestnymi krúžkami: piest sa vo valci pohybuje hore-dolu a prenáša tlak na ojnicu; krúžky pomáhajú utesniť priestor medzi piestom a valcom.
- Ojnica: spája piest s kľukovým hriadeľom a prenáša medzi nimi silu; pri pohybe sa kýva.
- Kľukový hriadeľ: premieňa pohyb piesta hore-dolu na otáčanie; počas cyklu sa otáča.
- Hlava valca: uzatvára hornú časť valca a nesie ventily aj zapaľovaciu sviečku; pri činnosti motora zostáva na mieste.
- Sací ventil: vpúšťa čerstvú zmes do valca; otvára a zatvára sa podľa činnosti vačkového hriadeľa.
- Výfukový ventil: umožňuje odchod spalín z valca; otvára a zatvára sa podľa činnosti vačkového hriadeľa.
- Vačkový hriadeľ: ovláda otváranie ventilov v správnom čase; počas jedného cyklu sa otočí raz, teda o 360°.
- Zapaľovacia sviečka: na konci stláčania vytvorí iskru, ktorá zapáli zmes; jej telo je pevné a iskra sa objaví iba pri zapaľovaní.
- Sacie a výfukové potrubie: sacie potrubie vedie čerstvú zmes k valcu a výfukové potrubie odvádza spaliny; potrubia zostávajú pevné.

Pracovné doby: Pod motor umiestni štyri tlačidlá s názvami „Nasávanie“, „Stláčanie“, „Výbuch (expanzia)“ a „Výfuk“. Po kliknutí prehraj plynulú animáciu príslušnej doby, zvýrazni jej tlačidlo a zobraz krátke vysvetlenie:
1. Nasávanie: sací ventil je otvorený a výfukový zatvorený. Piest ide nadol a do valca sa nasáva zmes paliva so vzduchom.
2. Stláčanie: oba ventily sú zatvorené. Piest ide nahor a stláča zmes.
3. Výbuch (expanzia): sviečka zapáli zmes, horúce plyny sa rozpínajú a tlačia piest nadol. Iba táto doba dodáva prácu kľukovému hriadeľu.
4. Výfuk: výfukový ventil je otvorený a sací zatvorený. Piest ide nahor a vytláča spaliny z valca.

Synchronizácia: Pohyb piesta, ojnice a kľukového hriadeľa musí byť mechanicky prepojený a plynulo synchronizovaný s polohou piesta a otváraním ventilov. V nasávaní a výfuku je otvorený vždy len príslušný ventil; pri stláčaní a expanzii sú oba zatvorené. Vačkový hriadeľ sa počas dvoch otáčok kľukového hriadeľa otočí raz. Na konci stláčania zobraz pri sviečke krátky záblesk iskry a pri expanzii naznač tlak plynov na piest; vyhni sa realistickým plameňom mimo valca.

Farby zmesi: Nasávanú zmes zobraz modrou, stlačenú zmes žltou, horenie oranžovou a červenou a spaliny sivou. Farby používaj len na plyn alebo náplň vo valci a na prúdenie v potrubiach, nie na samotné súčiastky. Pridaj malú legendu farieb.

Celý cyklus: Pridaj tlačidlo „Prehrať celý cyklus“. Po stlačení plynulo a opakovane prehrávaj nasávanie, stláčanie, výbuch (expanziu) a výfuk v tomto poradí. Aktuálna doba sa zreteľne zvýrazní a tlačidlo umožní prehrávanie zastaviť alebo znovu spustiť. Používateľ môže počas prehrávania kliknúť na inú dobu alebo súčiastku.

Počítadlo: Do rohu snímky pridaj malé, čitateľné počítadlo uhla kľukového hriadeľa. Uhol sa počas animácie plynulo mení od 0° do 720° a potom sa cyklus opakuje od 0°. Zreteľne uveď, že jeden celý pracovný cyklus trvá dve otáčky kľukového hriadeľa (720°). Jednotlivé doby zodpovedajú približne úsekom 0°–180°, 180°–360°, 360°–540° a 540°–720°.

Rozloženie a text: Ovládanie pohľadu umiestni vedľa alebo nad motor, štyri tlačidlá dôb pod motor a tlačidlo celého cyklu na dobre viditeľné miesto. Popisy a počítadlo nesmú zakrývať motor. Všetky texty na snímke napíš po slovensky. Použi čistý technický štýl vhodný na vyučovanie, čitateľné popisy a rozloženie prispôsobené pomeru strán 16 : 9. Nepridávaj nesúvisiace dekorácie ani ďalšie texty.
```

## Využitie v praxi

- **ZŠ:** názorné predstavenie štyroch pracovných dôb a základných častí motora.
- **SŠ:** opakovanie mechanického prepojenia piesta, ojnice, kľukového hriadeľa a časovania ventilov.

## Ako na to

1. Otvorte Copilot v PowerPointe a zvoľte vytvorenie interaktívnej snímky.
2. Skopírujte prompt, vložte ho a odošlite.
3. Vyskúšajte oba pohľady, klikateľné súčiastky aj celý pracovný cyklus.

## Čo potrebujete

- Copilot v PowerPointe s funkciou vytvárania interaktívnych snímok

## Autor

Zuzka Molčanová, Učiteľka Zuzka, www.ucitelkazuzka.sk
EDU špecialistka, Aricoma

## História verzií

| Verzia | Dátum | Poznámka |
|---|---|---|
| 1.0 | 17. 11. 2026 | Prvé zverejnenie |
