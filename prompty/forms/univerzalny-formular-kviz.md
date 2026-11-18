# Univerzálny prompt pre Microsoft Forms

## O čom to je

Univerzálny prompt pomáha učiteľom pripraviť v Microsoft Forms formulár alebo kvíz pre konkrétnu triedu, predmet a účel. Pomocou hranatých zátvoriek si určíte typ a počet otázok, ich obsah, nastavenia odpovedí aj prípadné vetvenie.

## Prompt

```text
Vytvor v Microsoft Forms [formulár/kvíz] pre [cieľová skupina].

KONTEXT
- Predmet alebo oblasť: [predmet/oblasť]
- Téma: [téma]
- Ročník alebo publikum: [ročník/publikum]
- Účel: [čo chcem zistiť alebo overiť]
- Čas na vyplnenie: [počet minút]
- Počet otázok: [počet]

OBSAH
Použi tieto typy otázok:
- [počet] otázok s výberom odpovede,
- [počet] škálových alebo Likertových otázok,
- [počet] krátkych otvorených otázok,
- [ďalšie typy otázok a ich počet].

Požiadavky:
- Použi jazyk primeraný [publikum] a téme.
- Každá otázka nech zisťuje alebo overuje iba jednu vec.
- Nepoužívaj navádzajúce, nejednoznačné ani zbytočne záporne formulované otázky.
- Otázky zoraď od jednoduchších ku komplexnejším.
- Rozdeľ otázky do sekcií: [názvy sekcií].
- Odpovede budú [anonymné/neanonymné]. Pri anonymných odpovediach nežiadaj meno ani iné identifikačné údaje a vypni zaznamenávanie mena, ak je toto nastavenie dostupné.
- Ako povinné označ tieto otázky: [čísla alebo názvy otázok; pri ostatných uveď, že sú nepovinné].
- Nastav ukončenie prijímania odpovedí na [dátum; uveď aj čas a časové pásmo, ak sú dôležité].
- Ako ďakovnú správu po odoslaní odpovede použi: „[text]“.

PRE KVÍZ
Nasledujúce pokyny použi iba vtedy, ak vytváraš kvíz:
- Nastav správne odpovede pri otázkach, ktoré majú jednoznačne overiteľnú správnu odpoveď.
- Pri otázkach s výberom odpovede vytvor vierohodné, ale jednoznačne nesprávne distraktory.
- Ku každej otázke s vyhodnocovanou správnou odpoveďou pridaj krátke vysvetlenie správnej odpovede.
- Zameraj otázky na tieto úrovne Bloomovej taxonómie alebo náročnosti: [úrovne/náročnosť].
- Zameraj sa na [poznanie/porozumenie/aplikáciu/analýzu/iné].
- Ak otázka nemá jednu overiteľnú správnu odpoveď, nevyhodnocuj ju automaticky ako správnu alebo nesprávnu; označ ju ako otvorenú alebo na manuálne posúdenie.

VETVENIE
Použi iba základné vetvenie Microsoft Forms.
- Ak respondent odpovie [odpoveď], presmeruj ho na [sekcia/otázka].
- Ďalšie pravidlo vetvenia: [odpoveď] → [sekcia/otázka].
- Ostatné odpovede pokračujú na [ďalšia otázka/sekcia].

Pred publikovaním najprv zobraz prehľad vetvenia ako zoznam pravidiel a stručne opíš, kam vedie každá vetva. Počkaj na kontrolu logiky; vetvenie nezverejňuj, ak je neúplné alebo si pravidlá odporujú. Ak vetvenie nie je potrebné, túto časť preskoč.

KONTROLA
Pred dokončením:
1. Skontroluj faktickú správnosť otázok a odpovedí.
2. Označ otázky alebo odpovede, ktoré musí overiť učiteľ, najmä tie závislé od konkrétneho učiva alebo školských pravidiel.
3. Skontroluj vekovú a jazykovú primeranosť cieľovej skupine.
4. Over, či počet otázok a ich typy zodpovedajú zadaniu a či sa otázky zbytočne neopakujú.
5. Skontroluj nastavenie anonymity, povinných otázok, termínu ukončenia a ďakovnej správy.
6. Navrhni jednu užitočnú následnú otázku, ktorá pomôže analyzovať výsledky.

Ak niektoré nastavenie Microsoft Forms alebo požadovaný typ otázky nie je dostupný, výslovne to uveď a navrhni najbližšiu vhodnú alternatívu. Nevymýšľaj, že formulár alebo nastavenie bolo vytvorené či zmenené, ak to nevieš priamo urobiť. Ak nemáš možnosť vytvoriť formulár priamo v Microsoft Forms, priprav otázky, odpovede, správne odpovede, vysvetlenia a nastavenia v prehľadnej podobe na manuálne prenesenie.
```

## Využitie v praxi

- **ZŠ:** učiteľ pripraví krátky anonymný dotazník o triednej aktivite alebo kvíz na overenie prebraného učiva.
- **SŠ:** učiteľ vytvorí kvíz s otázkami rôznej náročnosti, prípadne formulár na spätnú väzbu po projekte.

## Ako na to

1. Skopírujte prompt a nahraďte text v hranatých zátvorkách vlastnými údajmi.
2. Vložte ho do nástroja s podporou Microsoft Forms, napríklad do Microsoft 365 Copilota.
3. Pred zdieľaním skontrolujte otázky, správne odpovede, anonymitu, termín ukončenia a vetvenie.

## Čo potrebujete

- Microsoft Forms
- Nástroj s podporou generovania obsahu alebo vytvárania vo Forms, napríklad Microsoft 365 Copilot

## Autor

Zuzka Molčanová, Učiteľka Zuzka, www.ucitelkazuzka.sk
EDU špecialistka, Aricoma

## História verzií

| Verzia | Dátum | Poznámka |
|---|---|---|
| 1.0 | 18. 11. 2026 | Prvé zverejnenie |
