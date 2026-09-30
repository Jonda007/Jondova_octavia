# Octavia I - deník renovace laku a rzi

Repozitář Jondova_octavie. Deník svépomocné opravy laku a rzi na Škodě Octavii I 1.8T (AGU, 1997, černá metalíza). Slouží jako paměť pro Claude v projektu: co Jonda dělal, řešil, koupil, co se ukázalo jako špatně a co je další krok.

Vytvořeno 30. 9. 2026 z konverzace probíhající od 14. 9. 2026 a z dřívějších uložených poznámek. Jazyk: čeština. Kódování: UTF-8.

## Instrukce pro Clauda (vlož do "Project instructions")
Jsi asistent Jondy, který svépomocně opravuje lak a rez na Octavii. Vždy nejdřív čti 00-prehled/01-aktualni-stav.md, potom 06-chyby-a-opravy-asistenta.md a 08-otevrene-a-nepotvrzene.md. Odpovídej česky, krátce, jako číslovaný checklist "idiot-proof". Nejdřív odpověď, potom důvod. Když jde o konkrétní produkt, řiď se etiketou / technickým listem, ne obecnou znalostí. Když údaj neznáš nebo je v deníku označen jako nepotvrzený, řekni to a zeptej se Jondy. Jonda oponuje, když rada nesedí, a bývá v právu: přiznej chybu jednou a stručně, opravu vysvětli. Při nové práci na autě po sobě dopiš do dne/deníku, co se udělalo a koupilo.

## Struktura
- 00-prehled/ - souhrny (stav, vybavení, nákupy, diagnózy, rozhodnutí, chyby, technické poznatky, otevřené otázky)
- dny/ - deník po jednotlivých dnech
- octavia-denik-KOMPLET.md - všechno v jednom souboru (vhodné k nahrání do Claude projektu)

## Index dnů
| Složka | Datum | Jistota data | Hlavní téma |
|---|---|---|---|
| dny/0000_pozadi-pred-14-9 | před 14. 9. 2026 | různá | Stav auta, rozpočet, dřívější objednávky |
| dny/2026-09-14_po | 14. 9. (+ noc na 15. 9.) | jistá | Plán, nákup barvy, diagnostika z fotek suchý/mokrý, plnič, rozpis dnů |
| dny/2026-09-15_ut | 15. 9. | jistá | Clay, leštění kapoty, testovací čtverec, zákaly |
| dny/2026-09-16_st | 16. 9. | jistá | Levná metalíza zamítnuta, test utěrkami, výpočet materiálu, bez epoxidu |
| dny/2026-09-17-az-22_datum-neznamy/sezeni-1 | 17.-22. 9. (odhad) | ODHAD | Díra skrz, tmel, Brunox vs Würth |
| dny/2026-09-17-az-22_datum-neznamy/sezeni-2 | 17.-22. 9. (odhad) | ODHAD | Hodina času, kapota zůstává na autě, torx, blatníky jen dole |
| dny/2026-09-17-az-22_datum-neznamy/sezeni-3 | 17.-22. 9. (odhad) | ODHAD | Broušení na plech, odželezovač na holý plech, Würth, P100 |
| dny/2026-09-17-az-22_datum-neznamy/sezeni-4 | 17.-22. 9. (odhad) | ODHAD | Plniče, Würth 1 l, tmel, lem kapoty, silikon |
| dny/2026-09-17-az-22_datum-neznamy/sezeni-5 | 17.-22. 9. (odhad) | ODHAD | Nástřik plniče, tři vrstvy |
| dny/2026-09-17-az-22_datum-neznamy/sezeni-6 | 22.-30. 9. (odhad) | ODHAD | Broušení plniče, rouno K800, vodicí vrstva, založení deníku |

Až budeš znát přesná data sezení 1-6, přejmenuj složky (např. 2026-09-18_pa) a rozděl soubory podle dnů.

## Jak to použít
### GitHub
```
cd octavia-lak-denik
git remote add origin https://github.com/TVUJ-UCET/Jondova_octavie.git
git push -u origin main
```
(Složka už je git repozitář s jedním commitem.)

### Claude projekt (claude.ai)
1. Vytvoř nový projekt.
2. Nahraj octavia-denik-KOMPLET.md (jeden soubor), nebo jednotlivé soubory ze složek.
3. Do "Project instructions" vlož text z odstavce "Instrukce pro Clauda" výše.
4. Po každém pracovním dni přidej nový soubor do dny/ (nebo řekni Claudovi, ať ti navrhne zápis).

## Šablona nového dne
```
# RRRR-MM-DD (den)
## Shrnutí dne
## Co jsem dělal
## Co jsem řešil (otázky a odpovědi)
## Nákupy
## Rozhodnutí
## Korekce
## Fotky
## Další krok
```
