# Transformácia motýľa

## O čom to je

Prompt pre Copilot v PowerPointe vytvorí interaktívnu snímku s posuvným porovnaním fotografie motýľa a digitálneho ASCII zobrazenia toho istého motýľa. Obe podoby sa synchronizovane animujú, takže snímka názorne ukazuje analógovú a digitálnu podobu.

## Prompt

```text
Vytvor interaktívnu snímku cez celú plochu: posuvné porovnanie „pred a po“, ktoré stavia vedľa seba fotografiu motýľa a toho istého motýľa vykresleného ako ASCII art.

Kompozícia. Snímka siaha od okraja po okraj, bez vonkajších okrajov a čiernych pásov. Snímku delí jedna zvislá deliaca čiara. Keď ju používateľ potiahne doľava alebo doprava, prepína sa medzi oboma polovicami. Do stredu deliacej čiary pridaj malý okrúhly úchyt na ťahanie a pod neho krátky popis „◀ Potiahnite deliacu čiaru ▶“.

Obrázky: vygeneruj ich, nekresli. Vytvor dva obrázky pomocou AI:
- Jeden fotorealistický motýľ s roztvorenými krídlami, odfotený spredu na jednoduchom pozadí, aby sa dal čisto vystrihnúť. Vystrihni ho a zachovaj priehľadnosť.
- Jemné, silno rozmazané pozadie zeleného lístia: husté listy mimo zaostrenia, malá hĺbka ostrosti, bez hlavného objektu.

Ani jeden z nich nenahrádzaj vektorovou ani SVG grafikou.

Pozadie musí byť na oboch polovicách rovnaké. Za ľavú aj pravú stranu daj ten istý obrázok rozmazanej zelene s rovnakým jasom, sýtosťou a vinetou. Polovice sa majú líšiť iba tým, ako je vykreslený motýľ. Na oboch stranách pozadie výrazne stmav (približne na 40 % jasu), aby bol text na ňom dobre čitateľný.

Ľavá polovica: Analógové. Vystrihnutá fotografia motýľa, ostrá a v plných farbách, na tmavej rozmazanej zeleni.

Pravá polovica: Digitálne. Presne ten istý motýľ, na presne tom istom mieste a v presne rovnakej veľkosti, priebežne prekresľovaný ako ASCII art: jas motýľa sa navzorkuje do mriežky znakov a priradí sa k škále hustoty znakov. Znaky vykresli čisto bielou farbou, tučne a s vrstveným žiarením: tesný tmavý obrys na oddelenie od pozadia a k tomu jemná biela žiara, aby boli na tmavom pozadí dobre čitateľné.

Animácia. Motýľ neustále máva krídlami plynulým pohybom s jemným zrýchľovaním a spomaľovaním a mierne sa pohupuje hore a dole. Fotografická aj ASCII strana sa musia animovať synchronne z tých istých hodnôt, aby na seba obe polovice na deliacej čiare vždy presne nadväzovali. Krídla sa v najužšom bode mávnutia nesmú zložiť príliš, obrys motýľa má byť čitateľný počas celého cyklu. ASCII sa v každom snímku animácie vygeneruje nanovo podľa aktuálnej polohy krídel, takže pri mávaní je vidieť, ako sa znaky preskupujú.

Veľkosť. Obe polovice musia mať rovnakú mierku, motýľ nesmie byť na jednej strane väčší ani posunutý. Pri prevode obrázka do mriežky znakov počítaj s tým, že znaky s pevnou šírkou sú vyššie ako širšie. Inak bude ASCII vodorovne stlačené.

Text: čo najmenej. Nadpis: „Cesta premeny“, slovo „premeny“ zvýraznené. Na každej polovici jeden štítok: vľavo Analógové, vpravo Digitálne. Nič iné: žiadne podnadpisy, štatistiky ani popisy okrem pokynu na ťahanie.

Prispôsobenie veľkosti. Celá kompozícia sa prispôsobí akejkoľvek veľkosti snímky bez orezania a bez posúvačov.
```

## Využitie v praxi

- **Biológia na ZŠ:** ukážka premeny a rôznych spôsobov zobrazenia toho istého motýľa.
- **Informatika na ZŠ a SŠ:** názorné predstavenie ASCII artu a prevodu obrazu na znakovú mriežku.

## Ako na to

1. Otvorte Copilot v PowerPointe a zvoľte vytvorenie interaktívnej snímky.
2. Skopírujte prompt, vložte ho a odošlite.
3. Vyskúšajte posúvanie deliacej čiary a skontrolujte synchronizáciu animácie.

## Čo potrebujete

- Copilot v PowerPointe s funkciou vytvárania interaktívnych snímok
- Dostupné generovanie obrázkov pomocou AI

## Zdroj

Prompt je inšpirovaný príkladom [Interactive Slider: Butterfly Before/After Reveal](https://github.com/RollySeth/copilot-powerpoint-workiq-image-prompts/tree/main/samples/powerpoint-interactivity/slider-before-after-reveal).

## Autor

Preklad a úprava promptu: Zuzka Molčanová, EDU špecialistka, Aricoma
