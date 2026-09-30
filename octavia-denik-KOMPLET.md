# OCTAVIA I - DENÍK RENOVACE LAKU A RZI (všechno v jednom souboru)

Toto je sloučený obsah repozitáře Jondova_octavie k 30. 9. 2026. Pořadí: README, přehled, dny. Každá část začíná řádkem ZDROJ.


---

ZDROJ: README.md

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


---

ZDROJ: 00-prehled/01-aktualni-stav.md

# Aktuální stav (k 30. 9. 2026)

ČTI TENTO SOUBOR JAKO PRVNÍ. Potom 06-chyby-a-opravy-asistenta.md a 08-otevrene-a-nepotvrzene.md.

## Projekt v jedné větě
Svépomocná renovace laku a rzi na Škodě Octavii I 1.8T (AGU, 1997, černá metalíza). Jonda, začátečník, pracuje v oblepené suché garáži (15-19 °C), šetří.

## Hotovo
- Nákup materiálu (lakyrmat.cz 1 813 Kč, Koch Chemie přes Alzu, claybar, barva namíchaná skenerem, plniče, Würth, spreje). Viz 03-nakupy.md.
- Auto umyté (Koch Green Star 1:10 předmytí + myčka), claybar (voda + pár kapek jaru), odmaštění Novol 780.
- Kapota vyleštěná Tusonem (B9.01 + tvrdý pad, doleštění nejměkčím padem s pastou). Testovací čtverec 20x20 cm potvrdil, že čirý lak uprostřed kapoty žije. Zákaly po hraně u skla a v prolisu zůstaly.
- Rez na kapotě: povrchová, od odražených kamínků shora (zespodu čistý plech, žádný průraz). Přední část: desítky mělkých bodů, cca každých 5 cm. Vybroušeno na plech (celý přední pás P80 na excentru, pak P100, dobroušeno na P400).
- Odželezovač (Moje Auto Felgi krwawe) omylem použit na holý plech. Vysvětleno: reaguje na železo ne na rez, je kyselý. Opláchnout, vysušit, přebrousit.
- Würth antikorozní nátěr / inhibitor (1 l): jedna tenká vrstva štětečkem jen na holý plech, lem a drážka po stranách kapoty ošetřeny (štědře do spáry).
- Plnič: tři vrstvy (podle poznámek celá plechovka Novol Acrylic Primer šedý), hrubý povrch normální. Chamäleon Thick Layer Filler (400 ml) plánován na body a pás, použití nepotvrzeno.
- Broušení plniče: P400 (ruční hoblík) + rouno K800 (excentr), vodicí vrstva Spectrum Metallic black spray (mlha). Důlky zarovnané (podle poznámek). Stav dokončení ověřit fotkou pod šikmým světlem.

## Rozděláno / další kroky (v pořadí)
1. Zjemnění rounem K800 nasucho přes celou kapotu, hrany a prolisy ručně, žádné tahy po P400 pod šikmým světlem, dlaň přes tenký igelit (kontrola roviny).
2. Prodřená místa (kde se objeví Würth nebo kov): 2 tenké vrstvy Novolu, 2 h, zjemnit rounem. Báze má ležet všude na plniči.
3. Před bází: vysát celou kapotu a spáry, odmastit Novol 780 (nanést, hned setřít suchou utěrkou), 10 minut počkat, antistatická utěrka Gerson bez tlaku. (Nad Würth místy se doporučovalo jen vysát a přejet suchou antistatickou utěrkou, viz 08.) Topení vypnout a odsunout, dózy báze ve vlažné vodě do 40 °C, respirátor.
4. Báze: 2 vrstvy, 20-25 cm, překryv 50 %, mačkat/pouštět za okrajem dílu, poslední vrstva z větší vzdálenosti a lehce. Báze musí zůstat matná. Lampou pod úhlem ověřit, že šedá neprosvítá (jinak třetí lehká vrstva). Odvětrat podle etikety.
5. 2K čirý: 2 vrstvy (první tenčí, druhá plná). Respirátor s filtry A2P3 (polomaska), NE protiprachový. Po aktivaci spotřebovat do 3 dnů.
6. Montáž nejdřív za 3-4 dny po laku, raději týden. Voskovat až za měsíc. Po laku vosk do dutin do lemu kapoty.
7. Hodnotit výsledek jedním silným zdrojem pod ostrým úhlem, ne všemi lampami naráz. Hologramy a mraky vylezou na denním světle, před prohlášením za hotové vyjet ven.

## Ještě NEZAČATO
- Střecha (čirý se odlupuje v plátech, potřebuje lak; dokup 2+2 dózy báze/čirého, viz 03-nakupy.md).
- Zadní víko (delaminace čirého, potřebuje lak).
- Blatníky jen dole u prahu (rez), jinak rozleštit.
- Prahy a zadní sloupek u řidiče: konzervace (Würth).
- Leštění svislých dílů (dveře, boky, blatníky) dvoukrokem, začít zadními dveřmi spolujezdce.
- Škrábance pod klikou předních dveří a dlouhý škrábanec u lišty.

## Podmínky (rychle)
- Garáž suchá, elektřina, hodně světel, 15-19 °C, oblepená igelitem. Prach jde ze stropu a zpod vrat, ne ze země.
- Auto nikam nejezdí, může stát týden a víc.
- Lakuje se, až je připraveno (broušení hotové, garáž uklizená), ne podle kalendáře.


---

ZDROJ: 00-prehled/02-vybava-a-material.md

# Vybavení a materiál (kompletní inventář)

Stav podle konverzací do 30. 9. 2026. Ceny jen tam, kde je Jonda uvedl.

## Lakýrnický materiál - lakyrmat.cz (zaplaceno 1 813 Kč celkem)
- Laminovací souprava Novol Plus 710, 250 g (skelná rohož + pryskyřice; patří na blatníky dole u prahu, ne na kapotu)
- 2x 2K Pro bezbarvý lak, sprej 400 ml s tužidlem
- Odmašťovač Novol Plus 780, 1 l
- Antistatická utěrka Gerson 2000
- 2x SIA P1500 pod vodu, 2x SIA P400 pod vodu
- Tmel Novol Fiber se skelným vláknem, 200 g
- Plnič sprej Novol středně šedý 500 ml (Novol Acrylic Primer, 1K akrylový). Jonda uvedl cenu 170 Kč.
- Lepicí páska Novol 30 mm / 50 m
- Brunox Epoxy 100 ml: ROZPOR v datech (viz 08-otevrene). Jonda říká, že místo Brunoxu má Würth.

## Koch Chemie (objednáno přes Alzu)
- Kotouč Micro Cut fialový 126x25 mm (kód 9998317)
- Pasta Micro Cut M3.02, 250 ml (finiš)
- Kotouč Fine Cut žlutý 126x25 mm (kód 9998314)
- Pasta Heavy Quick Cut B9.01, 250 ml (řez)
- Aktivní pěna Green Star, 1 l (předmytí 1:10)
- Zvolil žlutý Fine Cut místo červeného Heavy Cut

## Barva
- 2 dózy černé metalízy 400 ml (1K báze) namíchané skenerem u lakýrníka, cca 1 dcl báze v každé. Původní kód odstínem nesedí, lakýrník dělá metalízu jen 1K. Kód/receptura nejsou k dispozici (skener dal měření).
- Kapota a blatníky musí být ze stejné dávky. Střecha může být z jiné.

## Rez a základ
- Würth antikorozní nátěr / inhibitor 1 l (disperzní, na vodní bázi, štětec/váleček). Reakční doba 3 h, přetřít v okně 3-48 h. Neoplachovat vodou, ne na horké plochy nad 40 °C.
- Chamäleon Thick Layer Filler High Build Primer, grey, 400 ml, 370 Kč (1K, rozpouštědlový, 3 tenké vrstvy, P400-500 nasucho)
- Novol Acrylic Primer šedý 500 ml (170 Kč)
- Spectrum Metallic High-Gloss Metallic black, sprej 400 ml (používá jako vodicí vrstvu, ne pod lak)
- Moje Auto Felgi krwawe koło (Wheel Cleaner Red), čistič s efektem krvácení, odželezovač (jen na lak)

## Zbytky a ostatní
- Tmel HB Body Bodysoft 211 (zbytek, hladký)
- Claybar Liquid Elements

## Nářadí a pomůcky
- Leštička Tuson 130050 (DA/orbitální, 125 mm, 720 W, závit M8x16)
- Kotouče: žlutý z balení leštičky (tvrdost neověřená), 5 levných 125mm z Actionu, Koch žlutý a fialový
- Excentrická (kulatá) bruska na suchý zip. Disky P80, P120, P180, P240, rouno K800 (hnědočervené měkčí, z vláken).
- Malá elektrická bruska na tvary
- Ruční brusný hoblík (blok na papír) s P400
- Aku vrtačka + drátěné kotouče (jen na hrubé odlupování, ne plošně)
- Brusné houby 120-320, papíry 400/600/1000/1500/2000/3000 (podle posledního sdělení má pro plnič jen P400 a pak P1000 a víc)
- Aku vapka Parkside, technický vysavač
- Respirátor s filtrem (typ neuveden; pro 2K čirý je potřeba polomaska A2P3, protiprachový nestačí)
- Turbo ruční větráček
- Hromada mikrovláknových utěrek
- Igelity, malířské plachty, izolepy, malířské pásky
- Světla: žárovky, LED trubice, lampička, reflektory
- Plachta na zem NEKOUPENA (nepotřeba)

## Co Jonda NEMÁ
- Kozy (nemá na čem stříkat díly naležato, nemá kam kapotu dát)
- Rotační leštičku (nechce)
- Šroubovací hlavici torx T45/T50 1/2" (doporučeno, nákup nepotvrzen)
- 2K epoxidový základ (odmítl kupovat)
- Spárovací tmel do lemu kapoty (odmítl kupovat další tmel)

## Odhad dokupu (pokud se lakuje i střecha)
- 2 dózy báze + 2 dózy čirého ze stejné mícharny, cca 2 000-2 200 Kč.
- Tekutý vosk do dutin cca 150 Kč (po laku).


---

ZDROJ: 00-prehled/03-nakupy.md

# Nákupy (chronologicky) a zamítnuté nákupy

## Před 14. 9. 2026 (přesná data neznám)
- Leštička Tuson 130050, rozpočet cca 1 800 Kč včetně kotoučů a past.
- Koch Chemie přes Alzu: pasta Heavy Quick Cut B9.01 250 ml, pasta Micro Cut M3.02 250 ml, žlutý Fine Cut a fialový Micro Cut kotouč 126 mm, Green Star 1 l.
- lakyrmat.cz: 1 813 Kč (2K čirý sprej 2x, plnič Novol šedý, odmašťovač Novol 780, laminovací sada 710, tmel Novol Fiber, páska, SIA P400 2x a P1500 2x, antistatická utěrka Gerson). Brunox Epoxy: rozpor, viz 08.
- Claybar Liquid Elements.
- Nářadí a drobnosti: aku vrtačka + drátěné kotouče, houby, papíry, vapka Parkside, technický vysavač, čistič s efektem krvácení, igelity, izolepy, respirátor s filtrem, turbo větráček.
- Pady z Actionu (5 levných).

## 14. 9. 2026 večer
- 2 dózy černé metalízy 400 ml, lakýrník je namíchal skenerem (cca 1 dcl báze v každé). Cena neuvedena.

## Neurčené datum (17.-22. 9.)
- Würth antikorozní nátěr / inhibitor 1 l (produkt z autochladek.cz).
- Chamäleon Thick Layer Filler High Build Primer 400 ml: 370 Kč.
- Novol Acrylic Primer šedý 500 ml: 170 Kč.
- Spectrum Metallic black sprej 400 ml (vodicí vrstva). Cena neuvedena.
- Moje Auto Felgi krwawe koło (odželezovač). Cena neuvedena.

## Doporučeno, ale nepotvrzeno jako koupeno
- Torx hlavice T45 a T50, 1/2" (80-150 Kč za kus, železářství).
- Tekutý vosk do dutin, cca 150 Kč (až po laku).
- 2+2 dózy (báze + čirý) z téže mícharny na střechu, cca 2 000-2 200 Kč.

## Zamítnuto nebo nekoupeno (a proč)
- Černý plnič: šedý stačí, ostrůvky plniče se podstříknou bází.
- Vracet šedý plnič: nevracet.
- Levná černá metalíza z Actionu za 60 Kč jako první vrstva báze: 1K akrylát se nezasíťuje, 2K čirý by ho nadzvedl, dvě neladící metalízy.
- SprayMax 2K Epoxy (cca 450 Kč): Jonda odmítl, má Würth.
- Brunox Epoxy znovu: Jonda navrhl vzít Brunox místo Würthu, nakonec zůstal Würth.
- Set BOLL pasta + houbička: nekvalitní.
- Rotační leštička: kvůli hologramům, upgrade leštičky (cca 5 000 Kč) až když Tuson nebude stačit.
- Použité přední blatníky z Bazoše: zrušeno, blatníky se nemění.
- Pískovací plachta na zem: prach jde ze stropu a zpod vrat, ne ze země. Místo toho igelit na strop a pokropit podlahu.
- Silikon do lemu: dělá v laku kráterky.
- Další tmel: Jonda nechce, do lemu jen Würth a případně pružný spárovací tmel/vosk.
- Konkurence s kódem barvy: kód není k dispozici, skener dal měření, receptura je majetek systému.
- Kozy na odložení dílů: nekoupeny (kapota zůstává na autě).

## Rozpočet
Původně 1 500, max 2 000 Kč bez černého laku. Rozšířil se (leštění, pravé 2K spreje). Jonda uvedl: "nechci nic extra objednávat, max že bych to sehnal za levno a byl by to gamechanger."


---

ZDROJ: 00-prehled/04-diagnozy-dilu.md

# Diagnózy podle dílů

Značky: [POTVRZENO] = ověřeno testem, fotkou nebo Jondovým tvrzením. [TEORIE] = hypotéza, neověřeno.

## Diagnostická pravidla
- Rovnoměrný šedý závoj bez ostrých hranic = oxidace = leštitelné. Skvrny s tvrdými hranicemi = odlupování čirého laku = neleštitelné, chce lak.
- Suché fotky nesou diagnózu, mokré ne (voda vyplní mikrodrsnost i na mrtvém laku, a na fotkách nebyla rovnoměrně smočená).
- Kritérium "pad zčerná = báze" nestačí. Spolehlivější je druhý průchod: když se to zlepší, je do čeho řezat.
- Test třemi bílými utěrkami (B9.01, 20 kroužků, 3 utěrky): postupné světlání = čirý lak zbývá, všechny stejně tmavé = báze.

## Svislé díly (dveře, boky, blatníky)
- [POTVRZENO] Čirý lak žije, ostrý odraz. Stačí leštit dvoukrokem (B9.01 na žlutý Fine Cut, M3.02 na fialový Micro Cut).
- [POTVRZENO] Swirly a škrábance různé hloubky. Pod klikou předních dveří ostré bílé škrábance skrz čirý. Dole u lišty předních dveří dlouhý škrábanec s přenosem barvy.
- Přední blatníky: [POTVRZENO] velké díry od rzi (dle dřívějších popisů), Jonda ale říká, že blatníky jsou "v pohodě", rez jen dole u prahu. Rozdíl mezi popisy zjistit.

## Kapota
- [POTVRZENO] Čirý lak uprostřed žije (testovací čtverec 20x20 cm, výrazný rozdíl proti okolí, po vyleštění se v laku vidí obličej).
- [POTVRZENO] Bělavé zákaly po hraně u skla a v prolisu uprostřed přežily leštění. Jonda trvá na tom, že lak nespálil ani neprobrousil na bázi.
- [TEORIE] Čirý lak je tam po 30 letech UV degradovaný skrz naskrz, nebo na hraně a prolisu došel přirozeně (z výroby ho tam bývá nejmíň). V obou případech víc leštění nepomůže. Test utěrkami to měl rozhodnout, nedokončen, překonán rozhodnutím lakovat celou kapotu.
- [POTVRZENO] Rez: zespodu čistý plech, žádný průraz. Rez je povrchová od odražených kamínků shora (puchýře a mělké krátery, cca každých 5 cm na přední části, hodně bodů). Rozsah větší než původní odhad 4-6 ohnisek.
- [POTVRZENO] Lem (okraj) kapoty a drážka po stranách, kde byl plast/guma: rez, popraskaný starý tmel. Vážnější než tečky nahoře (voda tam zůstává).
- [POTVRZENO] Bubliny po Würthu na některých místech (viz sezení 4 a 6).
- Původní verdikt 15. 9. "kapota se nebude lakovat, bude se leštit" byl překonán rozhodnutím lakovat celou kapotu (17.-22. 9.).

## Střecha
- [POTVRZENO] Čirý lak se odlupuje v plátech. Skvrnité bílé křídové ostrůvky s tvrdými hranicemi. Leštění nepomůže, chce lak.
- Čirý je odloupnutý i na sloupku u zrcátka, na zadní hraně střechy / C sloupku matný pás s prasklinou v laku.
- Plocha cca 1,2 m2.

## Zadní víko (kufr)
- [POTVRZENO] Delaminace: vyloupnutý flek čirého s roztřepeným okrajem, prasklina. Chce lak.

## Prahy, zadní sloupek u řidiče
- [POTVRZENO] Povrchová rez, přivařené díly. Jen konzervace (Würth), nikdo na to nebude tmelit. Hloubka nezkoumána.
- [POZNÁMKA] Jonda nemá svářečku a neumí svařovat, hlubší rez u prahů by se musela řešit jinak než svařováním.

## Rez shrnutí
- Kapota: povrchová od kamínků (shora).
- Blatníky (dole u prahu): laminovací sada + Novol Fiber, pokud jsou díry.
- Prahy a zadní sloupek: konzervace.


---

ZDROJ: 00-prehled/05-rozhodnuti.md

# Rozhodnutí (aktuální platné i překonané)

Značky: [PLATÍ] aktuální. [PŘEKONÁNO] nahrazeno pozdějším rozhodnutím.

## Rozsah a organizace
- [PLATÍ] Chce udělat všechno (rez i vzhled), ne jen část.
- [PLATÍ] Lakuje se, až je připraveno, ne podle kalendáře. Při stabilních 15-19 °C je počasí irelevantní, limit je materiál (hlavně čirý lak) a připravenost.
- [PLATÍ] Garáž: najet jednou a všechno udělat tam. Auto nikam nejezdí.
- [PLATÍ] Prach: igelit na strop nad kozy, podlahu v den lakování pokropit vodou, mezeru pod vraty ucpat ručníkem. Plachtu na zem nekupovat.

## Diagnostika a leštění
- [PLATÍ] Svislé díly: leštit dvoukrokem (B9.01 na Fine Cut, M3.02 na Micro Cut). Začít zadními dveřmi spolujezdce.
- [PŘEKONÁNO] "Kapota se nebude lakovat, bude se leštit" (15. 9.).
- [PLATÍ] Kapota se lakuje celá (rez po celé přední části, zbytkový zákal, metalíza se nedá rozstříkat do ztracena uprostřed plochy).
- [PLATÍ] Střecha a zadní víko: lakovat (čirý mrtvý / odlupuje se). Střecha později, klidně z jiné dávky.
- [PLATÍ] Rotační leštičku nekupovat. Tuson stačí.

## Rez
- [PLATÍ] Bez 2K epoxidového základu (Jonda ho nekupuje).
- [PLATÍ] Würth antikorozní nátěr/inhibitor (1 l): jedna tenká vrstva štětečkem jen na holý plech, ne na lak. Přetřít plničem v okně 3-48 h po nanesení, po 3 h reakční době. Tento produkt tmelení povoluje.
- [PLATÍ] Rez kapoty: povrchová, od kamínků. Celý přední pás brousit najednou (P80 na excentru), ne bodově.
- [PLATÍ] Odželezovač jen na lak před claybarem, nikdy na holý plech.
- [PLATÍ] Lem kapoty: jen Würth štědře do spáry, po vytvrzení případně pružný spárovací tmel nebo vosk. Žádný polyesterový tmel, žádný silikon.
- [PLATÍ] Prahy a zadní sloupek: konzervace Würthem.
- [PLATÍ] Blatníky se nemění, opraví se jen dole u prahu. Laminovací sada + Novol Fiber patří sem (ne na kapotu).
- [PŘEKONÁNO] Použité přední blatníky z Bazoše.
- [PŘEKONÁNO] Kapotu a blatníky sundat na kozy. Jonda kozy nemá a nemá kam díly dát. Sundává jen masku s grilem, kapota zůstává na autě (fotky později ukazují kapotu položenou vodorovně, ověřit).
- [PLATÍ] Tmel na kapotě jen když nehet zadrhne. Důlky dorovnat po vodicí vrstvě, tmel nad plničem.

## Plnič
- [PLATÍ] Novol šedý nevracet, černý neshánět.
- [PLATÍ] Plnič přes celou kapotu (jednotná savost poslední vrstvy). Navrchu všude jedna značka.
- [PLATÍ] Plán: Chamäleon jen na body a pás (3 vrstvy, každá o 2 cm širší, spoušť mačkat a pouštět mimo tečku), Novol přes celou kapotu 2 vrstvy. Skutečné provedení nepotvrzeno.
- [PLATÍ] Schnutí plniče řídit etiketou (Chamäleon: 2 h před broušením a přelakováním). Žádných 24 h.
- [PLATÍ] Broušení plniče: P400 nasucho + rouno K800 nasucho. P1000 pod vodou ne (1K plnič nasákne, Würth se nesmí oplachovat).
- [PLATÍ] Vodicí vrstva: Spectrum Metallic black sprej z velké dálky (50 cm), schnout 20-30 min, celá se zbrousí.

## Barva
- [PLATÍ] Černá metalíza 1K, 2 dózy 400 ml (cca 1 dcl báze v každé). Levná metalíza z Actionu zamítnuta.
- [PLATÍ] Ke konkurenci s kódem nechodit pro kapotu a blatníky (jiná dávka by se poznala přes spáru).
- [PLATÍ] Báze: 2 tenké vrstvy (u metalízy i lepší), na čirém nešetřit (2 vrstvy, spotřebovat do 3 dnů po aktivaci).

## Nákupy
- Viz 03-nakupy.md.


---

ZDROJ: 00-prehled/06-chyby-a-opravy-asistenta.md

# Chyby a opravy asistenta

Účel: nový Claude v projektu nemá opakovat tyto chyby. Jonda opakovaně a oprávněně oponoval, když rada neseděla. Pravidlo: NEŘÍKAT věc z obecné znalosti, když jde o konkrétní produkt. Přečíst etiketu / technický list, nebo říct, že nevím.

## Chyby, které Jonda odhalil
1. Mokré fotky nebyly rovnoměrně smočené. Diagnózu nesou suché fotky, ne mokré.
2. Plnič Novol středně šedý doporučil asistent (v jiném chatu), ne Jonda sám. A s doporučením nákupu asistent přestřelil.
3. Argument "střecha až na jaro" stál na počasí, které je při 19 °C v garáži irelevantní. Skutečný limit je materiál, ne kalendář.
4. Rychlost leštění 3-4 byla na DA málo. Správně: řezat 4-5, finiš 3-4.
5. Kritérium "pad zčerná = báze" nestačí (odbroušená oxidace je taky tmavá). Spolehlivější je druhý průchod.
6. Hrana u skla a flek u světel hozeny do jednoho pytle, i když se chovají jinak. Mlha u skla s měkkým okrajem je lepší případ.
7. Zákal na kapotě: asistent naznačoval, že Jonda "prošel skrz". Jonda opakovaně trval, že lak nespálil, a to je důležitý vstupní údaj.
8. Brunox: asistent tvrdil, že má stejné omezení jako konvertor a že tmel na něj nesmí. Nepravda. Technický list Brunox Epoxy polyesterový tmel po ztvrdnutí povoluje. Brunox má epoxidovou složku.
9. Laminát a Novol Fiber byly škrtnuty jako nepotřebné, ale patří na blatníky (dole u prahu), které Jonda chce opravit místo výměny.
10. Würth: tvrdilo se obecně, že na konvertor nesmí polyesterový tmel a že si ho má nechat jen na prahy. U Würth antikorozního nátěru/inhibitoru (1 l) to neplatí, výrobce tmelení povoluje. Také "pauza 6-12 h" patřila Brunoxu, ne Würthu (Würth tekutý: reakční doba 3 h, přetřít v okně 3-48 h).
11. Zrnitost před plničem: P240 bylo hrubé pro tenký 1K sprejový plnič (pro tlustý 2K high build by sedělo). GPT (P320), Grok a YouTube (P400) měli pravdu. Rozdíl 320 vs 400 je v praxi bezvýznamný.
12. Schnutí plniče: "24 hodin" bylo zbytečně dlouhé, etiketa Chamäleonu říká 2 h před broušením/přelakováním.
13. Zpočátku se počítalo s demontáží kapoty a blatníků na kozy. Jonda kozy nemá a nemá kam kapotu dát.
14. Rada odmašťovat Novol 780 vs "neodmašťovat nad Würthem": neověřeno u toho konkrétního produktu. Etiketa Würthu říká: povrch musí být před aplikací čistý, suchý a bez mastnot, a neoplachovat vodou. Zda smí rozpouštědlový odmašťovač po vytvrzení, není z etikety jisté.
15. Rozdíl v diagnóze příčiny rzi: nejdřív hypotéza průrazu zespodu, po ohledání zespodu se ukázalo, že rez jde shora od kamínků.

## Co Jonda dělá dobře, když oponuje
- Ověřuje tvrzení asistenta z etikety a z technických listů (fotky etiket Würthu a Chamäleonu, odkaz na autochladek).
- Porovnává rady z více zdrojů (GPT, Grok, YouTube).
- Když se něco nedává, ptá se znovu a nenechá se odbýt. Vždy mu vysvětlit důvod, ne opakovat pravidlo.

## Pravidla pro Clauda
- Nenavrhovat nákup, dokud nejsou vyčerpány zdroje z toho, co Jonda už má.
- Když je v etiketě údaj, řídit se etiketou, ne obecnou znalostí. Když údaj v etiketě chybí, říct to.
- Odpovídat česky, krátce, jako číslovaný checklist ("idiot-proof"). Nejdřív odpověď, pak důvody.
- Přiznat chybu jednou, stručně, a opravit. Nepřehnaně se omlouvat.
- Nepředpokládat, že mokrý povrch nebo foto s jedním světlem cokoli dokazuje.


---

ZDROJ: 00-prehled/07-technicke-poznatky.md

# Technické poznatky a postupy

Značky zdroje: [ETIKETA] přečteno z etikety, kterou Jonda vyfotil. [WEB] z webu / technického listu. [PRAXE] obecná praxe, asistent bez dokumentu. [ODHAD] neověřeno.

## Würth antikorozní nátěr / inhibitor (1 l, disperzní)
- [ETIKETA] Povrch čistý, suchý a bez mastnot. Odstranit kartáčem/škrabákem volnou rez, starý nátěr a nečistoty. Jedna tenká rovnoměrná vrstva štětcem nebo válečkem, zabránit stékání. V rozmezí 3 až 48 hodin po aplikaci přetřít krycím ochranným prostředkem na kovy na bázi vody nebo rozpouštědel. Dodržet 3hodinovou reakční dobu. Zakrýt plochy, které se neošetřují.
- [WEB] Nepoužívat na horkých plochách nad 40 °C. Neoplachovat vodou. Lze přetírat všemi běžnými krycími nátěry. Tmelení výslovně umožňuje.
- [PRAXE] Nepřidávat horkovzduch (odpaří vodu z disperze, reakce se nedokončí). Nebrousit po nanesení (vrstva jen pár mikrometrů, brousí se celá).
- Sprej Würth Odrezovač (jiný produkt): přelakovat po 2 h, 2-3 tenké vrstvy z 25-30 cm, přetírat jen 1K produkty.

## Brunox Epoxy (jen pokud by se koupil)
- [WEB] Po ztvrdnutí (nedá se rýt nehtem) lze tmelit polyesterovým tmelem. 2-4 vrstvy, mezischnutí 6-12 h, zavadnutí 1 h, vytvrzení 12 h, při teplotě pod 20 °C a vyšší vlhkosti déle než 24 h. Neomývat, nebrousit, nečistit odstraňovačem silikonu po nanesení.

## Novol Acrylic Primer šedý 500 ml
- [WEB] 1K akrylový plnič ve spreji, určený na tmely a staré laky, ideální na bodové opravy. Nižší přilnavost ke kovu, bez antikorozní ochrany, není vhodný jako základ na holý kov. Nanáší se ve 2-3 tenkých vrstvách, 20-30 cm, protřepat 2-3 min. Pouze 1K produkty přes něj.
- Plní desetiny milimetru. Mělký talířek zarovná, hlubší důlek ne.

## Chamäleon Thick Layer Filler High Build Primer, šedý, 400 ml
- [ETIKETA] 3 tenké vrstvy, 5 minut mezi vrstvami, vzdálenost 25-30 cm, zpracování 15-25 °C, protřepat 2 min. Proschnutí 1 h při 20 °C (20 min při 60 °C, IR 15-20 min). Brousit a přelakovat po 2 h. Broušení nasucho P400-500, pod vodu P800-1000. Rozpouštědlový (aceton, butylacetát, uhlovodíky C10), 1K, žádné tužidlo, žádný aktivátor.

## Broušení před plničem a po něm
- Brousit křížem (jeden směr dělá drážky), na hoblíku nebo excentru, ne na houbičce (vlny).
- Hrany a prolisy jen ručně. Přechody vyzáběhnout do ztracena (nehet přes okraj, nesmí zadrhnout).
- Nikde nesmí zůstat lesk na starém laku (plnič tam nedrží). Lampa pod ostrým úhlem.
- Pod tenký 1K sprejový plnič: P320 až P400. Pro tlustý 2K high build P240.
- Po plniči: vodicí vrstva, P400 nasucho na hoblíku (rovina se dělá tady), pak zjemnění rounem 800 nasucho (rýhy po P400 můžou prosvitnout pod černou metalízou).
- 1K plnič je porézní, nasákne vodu a pod bází udělá puchýře. Proto nasucho.
- Kontrola roviny: dlaň přes tenký igelit po celé ploše. Co ucítíš, uvidíš po nalakování.

## Vodicí vrstva
- Tenká mlha černého spreje z 50 cm a víc, jeden rychlý přelet, schnout 20-30 min. Brousit, dokud černá nezmizí. Kde zůstane, je důlek.
- Alternativa: suchý prášek z tužky nebo uhlu rozetřený suchým hadříkem.

## Leštění (DA leštička Tuson, Koch pasty)
- Test 20x20 cm ohraničený páskou, vyfotit před tím.
- Rozetření pasty stupeň 1-2 při vypnutém stroji. Řezání B9.01 na žlutý Fine Cut stupeň 4-5. Finiš M3.02 na fialový Micro Cut stupeň 3-4.
- Přítlak cca váha předloktí (5 kg): u DA přítlak dělá rotaci, ne agresivitu. Fixou čárka přes okraj padu, musí se otáčet.
- Tempo 2-3 cm/s, úseky 30x30 cm, 6-8 křížových přejezdů. Pad čistit kartáčem po každém čtverci. Nejezdit přes hrany a prolisy. Kontrola IPA nebo odmašťovačem mezi kroky.
- Leštící oleje po dni práce dělají falešně "hotové" plochy. Před hodnocením odmastit.

## Claybar
- Voda + jen pár kapek jaru (ne silný poměr). Nenechat lubrikant zaschnout. Nepoužívat papírové ubrousky. Po claybaru vlhké mikrovlákno, tahy jedním směrem. Spadlý clay vyhodit.

## Barva a čirý lak
- Odmastit: nanést a hned setřít druhou utěrkou nasucho. Antistatická utěrka Gerson bez tlaku.
- Podstřik ostrůvků plniče bází, dokud šedá nezmizí, pak dvě rovnoměrné vrstvy přes celý díl.
- Báze: 2 vrstvy, 20-25 cm, překryv 50 %, mačkat/pouštět za okrajem dílu. Poslední vrstva z větší vzdálenosti a lehce (srovná natočení hliníku). Báze musí zůstat matná. Lampou pod úhlem ověřit, že plnič neprosvítá.
- 2K čirý: 2 vrstvy, první tenčí, druhá plná. Po aktivaci spotřebovat do 3 dnů (SprayMax).
- Dózy zahřát ve vlažné vodě do 40 °C. Topení vypnout a odsunout před stříkáním.
- Kapota naležato / nastojato: nastojato tenčí vrstvy a pozor na stékance.
- Montáž nejdřív za 3-4 dny po laku. Voskovat až za měsíc.
- Vydatnost (odhad z webu, velký rozptyl): báze 400 ml míchaná 0,75-1 m2, čirý 400 ml 1-1,5 m2 při dvou vrstvách.
- Hodnotit jedním silným zdrojem pod ostrým úhlem, ne všemi lampami. Hologramy a mraky vylezou na denním světle.

## Rez obecně
- Konvertor je nástroj na rez, kterou nejde odstranit mechanicky. Z vybroušeného lesklého plechu se rez nerozleze, rozleze se ze zbytků v důlcích, ze spodní strany a z okraje.
- Plošné broušení dělá mapu: v matném povrchu vyskočí neodbroušené krátery jako lesklé tečky.
- Drátěný kotouč rez v důlku spíš uhladí a začerní. Pro plošné broušení papír nebo lamelový kotouč.
- Jiskry z drátěného kotouče se zapékají do laku, před broušením zakrýt auto plachtou.
- Odželezovač (thioglykolát) reaguje na železo ne na rez. Na holý plech nepatří (falešný poplach a kyselé zbytky, flash rust).
- Holý plech přes noc: při vlhkosti nad normál a poklesu teploty (15 °C přes noc) kondenzace = hnědý závoj. Řešení: Würth ještě ten den, nebo suchý hadr, větráček, ráno P240 nasucho.
- Lem kapoty: pracuje, je to past na vodu. Žádný polyesterový tmel, žádný silikon. Würth do spáry, po vytvrzení pružný tmel nebo vosk do dutin.

## Bezpečnost
- 2K čirý obsahuje isokyanáty. Protiprachový FFP2/FFP3 nechrání proti parám. Nutná polomaska s filtry A2P3.
- Nikdy nelakovat v zavřené garáži bez větrání. Turbo větráček foukat ven.
- Rozpouštědlové spreje: žádný oheň, jiskry, kouření.

## Garáž a prach
- Prach jde ze stropu a zpod vrat, ne ze země. Igelit na strop nad kozy. Podlahu jen pokropit vodou. Mezeru pod vraty ucpat ručníkem.

## Kód barvy a konkurence
- Skener dal měření, ne kód. Receptura je majetek systému té značky, konkurence ji nepřečte. Kapota a blatníky sousedí přes spáru a musí být ze stejné dávky.


---

ZDROJ: 00-prehled/08-otevrene-a-nepotvrzene.md

# Otevřené otázky a nepotvrzené informace

Tohle jsou díry v deníku. Než se z nich udělá závěr, zeptej se Jondy.

## Data
- Konverzace po 16. 9. večer (po shrnutí) nemá časová razítka. Sezení 1-6 ve složce 2026-09-17-az-22_datum-neznamy jsou seřazená chronologicky, ale přesná data neznám. Z uložených poznámek: plnič hotový do 22. 9. 2026. Sezení 6 a založení deníku je 30. 9. 2026.
- Jak byla splněna původní osa 15.-19. 9. (lakování v sobotu 19. 9.) není doloženo. Podle pozdějších zpráv se lakování kapoty ještě nekonalo (sezení 6: příprava na bázi).

## Co je nejasné z hlediska materiálu
- Brunox Epoxy: uložené poznámky říkají, že objednávka lakyrmat dorazila včetně Brunox Epoxy 100 ml. Jonda 14. 9. říká, že místo Brunoxu má Würth. Zjistit, jestli Brunox fyzicky má.
- Který plnič se skutečně použil: uložené poznámky říkají 3 vrstvy Novolu, celá plechovka. Plán byl Chamäleon na body a pás + Novol přes celé. Zjistit, jestli Chamäleon (370 Kč) padl.
- Kde a kdy Jonda koupil Würth antikorozní nátěr 1 l (odkaz autochladek.cz).
- Novol 170 Kč: je to plechovka z objednávky lakyrmat, nebo druhá dokoupená.
- Cena barvy (2 dózy) a Spectrum spreje neuvedena.

## Co je nejasné z hlediska stavu
- Je kapota teď na autě, nebo položená vodorovně? (Sezení 2: zůstala na autě, sundána jen maska s grilem. Fotky z pozdější doby ukazují kapotu položenou vodorovně a šroubek pantu.)
- Byl Würth nakonec nanesen po dobroušení (fotky z pozdějších dní ukazují krémové prstence), a kolik hodin před plničem.
- Bylo dokončeno broušení plniče P400 + K800? Jaký je stav tahů pod šikmým světlem?
- Zda se použil Novol navrch (2 vrstvy) po broušení Chamäleonu, nebo se od toho ustoupilo.
- Kolik z rzi na blatnících je skutečně děr (dřívější popis: velké díry v předních blatnících, později Jonda: v pohodě, jen dole u prahu).
- Zda byly vyhlédnuty a nakoupeny torx hlavice T45/T50.
- Stav střechy a zadního víka (nezačato).

## Technická nejistota
- Zda smí rozpouštědlový odmašťovač Novol 780 na vytvrzený Würth inhibitor. Etiketa říká čisté, suché a bez mastnot před aplikací, neoplachovat vodou. Rada asistenta byla odmašťovač nepoužít, ale jde o odhad.
- Přesná zrnitost pod Novol Acrylic Primer: technický list Novolu s předepsanou zrnitostí asistent nenašel. Pracovní hodnota P320-400.
- Přesná vydatnost Novolu na m2 nenalezena (jen popis).
- Zda je Chamäleon Thick Layer Filler skutečně 1K (etiketa neuvádí 2K ani aktivátor, složení jen rozpouštědla). Jonda tvrdí 1K, potvrzeno absencí aktivátoru.

## Úkoly z dřívějška, které mohou být stále otevřené
- Ověřit etiketu čističe s efektem krvácení, jestli smí na lak. (Zodpovězeno částečně: reaguje na železo, na lak před claybarem ano, na holý plech ne.)
- Palcový test žlutého kotouče Tuson (tvrdost).
- Test třemi utěrkami na kapotě (překonán rozhodnutím lakovat celou kapotu, ale hodí se na střechu a svislé díly).
- Odhad kolik báze a čirého zbyde po kapotě a jestli stačí na střechu.


---

ZDROJ: dny/0000_pozadi-pred-14-9/pozadi.md

# Pozadí - co bylo před 14. 9. 2026

Zdroj: dřívější chaty a uložené poznámky o projektu (přenosový souhrn ze 11. 9. 2026). Přesná data jednotlivých událostí tady neznám, proto jsou v jednom souboru.

## Kdo a co
- Jonda, IT student (Brno), bydlí Blansko / Brno, komunikuje česky.
- Auto: Škoda Octavia I 1.8T (motor AGU), rok 1997, černá metalíza.
- Začátečník v lakování i leštění. Neumí svařovat a nemá svářečku. Opravuje sám a šetří.

## Stav laku a rzi (podle dřívějších popisů)
- Lak po 30 letech vybledlý od slunce, hlavně střecha, kufr a kapota. Hromada škrábanců po celé karoserii.
- Mokré auto vypadá dobře, suché ne (to se později ukázalo jako klíč k diagnóze).
- Střecha je nejhorší plocha: velké oblasti bez bezbarvého laku, okraje se odlupují, čirý lak je odloupnutý i na sloupku u zrcátka. Na zadní hraně střechy / C sloupku je matný pás s prasklinou v laku.
- Svislé díly (dveře, boky, blatníky): lak lesklý, ale swirly a škrábance různé hloubky. Dveře poškrábané od vjezdu do garáže a od jiných aut. Pod klikou předních dveří ostré bílé škrábance skrz bezbarvý lak. Dole u lišty předních dveří dlouhý škrábanec s přenosem barvy.
- Rez: velké díry v předních blatnících (šroubované), zadní sloupek na straně řidiče (zadek vlevo nad kolem) a prahy (přivařené).

## Rozpočet a postoj
- Původní rozpočet 1 500, max 2 000 Kč bez černého laku. Rozšířil se kvůli leštění a kvůli tomu, že levné "2K" spreje nejsou pravé 2K.
- Chce udělat všechno (rez i vzhled), ne jen část.
- Odmítl levný set BOLL pasta + karosářská houbička jako nekvalitní.
- Leštička: Tuson 130050 (DA/orbitální, 125 mm, 720 W, závit M8x16). Kupoval ji s rozpočtem cca 1 800 Kč včetně kotoučů a past. Novou leštičku (cca 5 000 Kč) nekupuje, dokud stroj nebude brzdit. Rotační leštičku nechce kvůli hologramům, i když ji doporučoval známý autolakýrník.
- Kotouče: žlutý z balení leštičky (tvrdost neověřená) a sada 5 levných 125mm z Actionu. Ke Koch pastám má Koch pady 126 mm, žlutý Fine Cut a fialový Micro Cut. Zvolil žlutý Fine Cut místo červeného Heavy Cut.

## Objednávky před 14. 9.
Kompletní seznam je v 00-prehled/03-nakupy.md. Zkráceně: lakyrmat.cz (1 813 Kč, laky, plnič, tmely, odmašťovač), Koch Chemie přes Alzu (pasty, pady, Green Star), claybar Liquid Elements.

## Jeho původní plán postupu
Umýt Green Starem na myčce, odželeznit, claybar, odmastit, pak zkusit rozleštit střechu a kapotu a podle výsledku rozhodnout, kolik brousit a lakovat. Chtěl šetřit barvou.

## Otevřené úkoly z té doby
- Ověřit etiketu čističe s efektem krvácení, jestli smí na lak.
- Palcový test žlutého kotouče.


---

ZDROJ: dny/2026-09-14_po/denik.md

# 2026-09-14 (pondělí) + noc na 15. 9.

Časy jsou místní (UTC+2), přepočtené z časových razítek konverzace. Datum je JISTÉ.

## Shrnutí dne
Jonda přišel s hotovým nákupem materiálu a chtěl kompletní plán opravy. Ve dne se sestavil první plán, večer po nákupu barvy a po umytí auta se plán přepracoval podle fotek suchý/mokrý. Po půlnoci se řešil plnič (barva, nevracet) a rozpis dnů.

## Co jsem dělal
- Koupil 2 spreje černé metalízy po 400 ml. Lakýrník je namíchal skenerem, v každém je cca 1 dcl báze (koupeno večer 14. 9.).
- Auto důkladně předmyl Koch Green Star 1:10 a umyl na automyčce.
- Vyfotil každou část auta suchou i mokrou (podklad pro diagnózu).
- Garáž je oblepená igelitem / malířskými plachtami.

## Co jsem měl v ten den nakoupeno a připraveno
(Viz 00-prehled/02-vybava-a-material.md.) Claybar Liquid Elements, aku vrtačka + drátěné kotouče, brusné houby 120-320, papíry 400-600-1000-1500-2000-3000, aku vapka Parkside, technický vysavač, čistič na brzdy/kola s efektem krvácení, igelity a izolepy, respirátor s filtrem, antistatická utěrka, malá el. bruska na tvary, turbo ruční větráček, hromada mikrovláken. Místo Brunoxu má odrezovač / konvertor rzi Würth.

## Co jsem řešil (otázky a odpovědi)
1. Kompletní plán opravy: co nakoupit, co dělat první. Jeho vlastní pořadí: koupit barvu, umýt, zaparlovat, claybar, odmaštění, pak zkusit vyleštit střechu a kapotu (jestli je čirý lak jen zoxidovaný, nebo pryč) a podle toho buď leštit, nebo brousit a lakovat.
2. Doptávací otázky (odpovědi): auto může v garáži stát týden a víc. Garáž je nevytápěná, ale suchá, s elektřinou. Když peníze nestačí na všechno: chce všechno.
3. Vyhledávání: kompatibilita Brunox Epoxy a SprayMax 2K Epoxy s polyesterovým tmelem (podklad pro rozhodnutí o rzi).
4. Po umytí (22:27): zopakoval kontext, poslal hromadu fotek suchý+mokrý po dílech. Obchodník s barvami (profík) mu poradil nechat barvu před leštěním vytvrdnout. Jonda ale nechce stříkat celé auto ani celou kapotu a střechu. Podle něj auto vypadá mokré super, takže většinu asi půjde rozleštit.
5. Diagnóza podle fotek (viz 00-prehled/04-diagnozy-dilu.md).
6. Oprava chyby: voda na mokrých fotkách není rovnoměrná (foceno po částečném odkapání), takže diagnózu nesou hlavně suché fotky. Také upozornil, že .md soubor s plánem je celý rozsypaný (kódování).
7. Plnič: profík v obchodě řekl, že je plnič strašně důležitý a musí mít správný odstín. Jonda se ptal, jestli asistent vybral správný (šedý). Ukázalo se, že plnič Novol středně šedý 500 ml mu doporučil asistent v jiném chatu, ne že by si ho vybral sám. Asistent hledal na webu a v obrázcích, jak vypadá báze přes různé barvy plniče.
8. Po půlnoci (00:02): chce dávat max dvě vrstvy a nestříkat celou kapotu. Ptal se, jestli má šedý plnič vrátit a koupit černý.
9. Po půlnoci (01:57): chce rozpis po jednotlivých dnech podle jeho časových oken (viz níže), řeší plachtu na zem vs igelit na stěnách (v garáži po 3 dnech zase prach a smetí na zemi) a ptá se, jestli mu konkurence s kódem barvy namíchá stejný odstín levněji.
10. Po půlnoci (02:12): s autem nikam nejezdí, v garáži je pořád 19 stupňů a hromada světla z různých žárovek, LED a reflektorů. Na jaře nic malovat nechce, chce to udělat teď: tento týden, nebo příští po škole (škola mu začíná).

## Jeho časová okna (pro rozpis)
- Út 15. 9.: 9:00-21:00 (parkuje auto, čistí, clay, pak leštění). Musí ještě dolepit garáž.
- St 16. 9.: 16:00-21:00
- Čt 17. 9.: 18:30-22:00
- Pá 18. 9.: 17:30-22:00
- So 19. 9.: celý den

## Výstupy asistenta
- octavia-plan-renovace.md ve třech verzích: v1 (přibližně 16:40, hned po doptávacích otázkách), v2 (po fotkách z myčky), potom čistý přepis bez poškozených bytů a bez typografických znaků (oprava kódování), nakonec verze s denním rozpisem Út 15. - So 19. 9. včetně scénářů A-E, sekce o podlaze a o kódu barvy, go/no-go checkpointů a seznamu typických chyb.

## Rozhodnutí
- Šedý plnič Novol se nevrací a černý se nekupuje. Plnič půjde jen na opravená ohniska. Ostrůvky plniče se podstříknou vlastní bází, dokud šedá nezmizí, pak dvě rovnoměrné vrstvy přes celý díl. Asistent přiznal, že s doporučením nákupu přestřelil.
- Ke konkurenci s kódem barvy nechodit pro kapotu a blatníky. Skener dal měření, ne kód. Receptura je majetek systému té značky. Kapota a blatníky sousedí přes spáru a musí být ze stejné dávky. Střecha s kapotou nesousedí (mezi nimi je sklo), tam může být jiná šarže.
- Plachtu na zem nekupovat. Prach po třech dnech nepřišel ze země, ale ze stropu a zpod vrat. Igelit dát na strop nad kozy, podlahu v den lakování pokropit vodou, mezeru pod vraty ucpat ručníkem.
- Lakování původně plánováno na sobotu 19. 9. (čt a pá jsou po setmění).

## Korekce (kde měl pravdu Jonda)
- Mokré fotky nebyly rovnoměrně smočené, proto diagnózu nesou suché.
- Šedý plnič nevybral on, ale asistent v jiném chatu.
- Argument "střecha až na jaro" stál na počasí, které je při 19 °C v garáži irelevantní. Skutečný limit je materiál (hlavně čirý lak), ne kalendář. Spouštěč lakování = připravenost, ne datum.

## Další krok
Út 15. 9. od 9:00: garáž (strop, mezera pod vraty), clay, odmaštění, testy.


---

ZDROJ: dny/2026-09-15_ut/denik.md

# 2026-09-15 (úterý)

Časy jsou místní (UTC+2). Datum je JISTÉ. Jonda byl v garáži plánovaně od 9:00 do 21:00.

## Shrnutí dne
Claybar, odstranění šmouh od jaru, první leštění na kapotě přes testovací čtverec, pak celá kapota. Ukázalo se, že čirý lak na kapotě žije, ale po hraně u skla a v prolisu zůstaly bělavé zákaly. Kapotu ani blatníky nesundával.

## Plán vs. skutečnost
Rozpis na úterý (garáž, clay, demontáž dílů na kozy, testy, rez, leštění) se splnil jen částečně: garáž a clay ano, leštění kapoty ano. Kapota a blatníky nebyly sundány (nemá kozy ani kam díly dát), rez se ten den neřešila.

## Co jsem dělal
- Claybar celého auta. Lubrikant: voda + jar. Lak pod claybarem "krásně hladoučký".
- Odmastil odmašťovačem (Novol 780), ohraničil testovací čtverec 20x20 cm páskou, vyleštil ho.
- Vyleštil kapotu: nejdřív jen Heavy Cut (B9.01) a nejhrubším kotoučem, později "hromadou kroků" a dolešťoval nejměkčím kotoučem a pastou.

## Co jsem řešil (otázky a odpovědi)
1. 12:09 - Clay dělá šmouhy, protože stříká vodu s jarem "celkem silný poměr". Jak to umýt, nebo stírat papírovými ubrousky? Odpověď: šmouhy dělá jar, ne clay. Papírové ubrousky ne (brusivo). Postříkat čistou vodou, setřít vlhkým mikrovláknem tahy jedním směrem, dosušit suchým. Jaru jen pár kapek na litr. Nenechat lubrikant zaschnout. Zbytek stejně sundá odmaštění a leštění.
2. 16:11 - Vyclayováno vodou a jarem, umyto vlhkými hadříky, "furt tam něco bude", chce zkusit leštění. Mám otřít odmašťovačem a jak leštit? Odpověď: odmastit Novol 780 (nanést mikrovláknem, druhou suchou hned setřít). Testovací čtverec 20x20 cm ohraničit páskou, vyfotit před tím. Pad lehce navlhčit, 4-5 kapek B9.01, rozetřít při vypnutém stroji. Stupeň 2, pak řezat. Přítlak střední. Fixou čárka přes okraj padu, musí se otáčet. Tempo 3-5 cm/s, překryv 50 %.
3. 16:50 - Fotky před/po, ještě trochu flek. Nevím jak leštit (rychlosti, přítlak), zatím jen Heavy Cut a nejhrubší kotouč. Odpověď: rozdíl mezi čtvercem a okolím je obrovský, čirý lak na kapotě ŽIJE a má do čeho řezat. Kapota se nebude lakovat, bude se leštit. Oprava dřívější rady: rychlost řezání na DA je stupeň 4-5 (3-4 bylo málo), finiš stupeň 3-4. Přítlak asi váha předloktí (cca 5 kg), protože u DA přítlak dělá rotaci. Pad čistit kartáčem po každém čtverci.
4. 19:25 - Vyleštěná celá část několika kroky a doleštěná nejměkčím kotoučem a pastou. Co s tím? Zbrousit na tvrdo, nebo dolakovat pár vrstvami? Odpověď: na fotce se v laku vidí (uprostřed čirý lak je a leštění zabralo). Bělavé zákaly se táhnou po hraně a po prolisu uprostřed kapoty. Hypotéza: uprostřed čirý lak je, na hraně a prolisu už ne. Navržen test třemi bílými utěrkami (postupné světlání = čirý lak zbývá, stejně tmavé = báze).
5. 20:33 - Kterou "čmouhu" myslíš, tu nahoře u skla (světlá mlha, uvnitř krásná černá), nebo dole u světel? Odpověď (asistent přiznal, že oba případy hodil do jednoho pytle): nahoře u skla je lepší případ (měkký nepravidelný okraj = "tady jsem projel a tady ještě ne"), dole u světel víc hlídat (plošší bělavý flek na přední hraně). Před hodnocením odmastit celou kapotu (leštící oleje dělají falešně "hotové" plochy). Rozdělit kapotu na 6 polí + pole u světel a na prolisu.
6. 20:35 - Jonda: mlhu jsem projel celou opakovaně a cíleně, lak jsem určitě nespálil a rozhodně si nemyslím, že jsem probrousil leštičkou až na bázi. Odpověď: přijato. Zbývají dvě vysvětlení: (a) čirý lak je po 30 letech UV degradovaný skrz naskrz, (b) na hraně a prolisu ho z výroby bývá nejmíň a došel přirozeně. V obou případech víc leštění nepomůže.

## Technické poznatky z toho dne
- Diagnostické pravidlo: rovnoměrný závoj = oxidace = leštitelné. Skvrny s tvrdými hranami = odlupování = neleštitelné.
- Kritérium "pad zčerná = báze" nestačí (odbroušená oxidace je taky tmavá). Spolehlivější je druhý průchod: zlepší-li se to, je do čeho řezat.
- Rychlosti a přítlak leštění: viz 00-prehled/07-technicke-poznatky.md.

## Korekce (kde měl pravdu Jonda)
- Rychlost leštění 3-4 byla na DA málo.
- Kritérium zčernání padu nestačí.
- Zákal u skla a flek u světel nejsou totéž.
- Trval na tom, že lak nespálil, a byl to podstatný údaj, který změnil vysvětlení.

## Stav na konci dne
Kapota vyleštěná, čirý lak uprostřed žije, zákaly u hrany a v prolisu zůstávají. Čeká se na test třemi utěrkami (nedokončen, později překonán rozhodnutím lakovat celou kapotu).

## Další krok
Test třemi utěrkami na 6+2 polích, prosvítit kapotu zespodu, zjistit rozsah rzi.


---

ZDROJ: dny/2026-09-16_st/denik.md

# 2026-09-16 (středa)

Časy jsou místní (UTC+2). Datum je JISTÉ. V plánu bylo okno 16:00-21:00.

## Shrnutí dne
Otázky k barvě (levná metalíza z Actionu), k testu třemi utěrkami, k množství materiálu na střechu + kapotu (2,5 m2) a rozhodnutí o rzi: bez epoxidu, jen Würth. Ke konci dne se konverzace zkrátila (shrnutí) a následující zprávy už nemají časová razítka (viz složka 2026-09-17-az-22_datum-neznamy).

## Co jsem řešil (otázky a odpovědi)
1. 16:21 - Když budu lakovat a první vrstva báze má být jen jemná, nemůžu dát černý metalický lak z Actionu za 60 Kč (je akrylový) jako první vrstvu, aby druhá poctivá z drahé barvy lépe držela a ušetřil jsem? Odpověď: NE. 1K akrylát se nikdy plně nezasíťuje, 2K čirý navrch by ho nadzvedl. A metalíza pod metalízou dá dvě neladící vrstvy třpytu.
2. 18:02 - Jak udělat pořádně test s utěrkami. Postup: odmastit pole, utěrka č. 1 + kapka B9.01, 20 kroužků ručně, setřít, zopakovat s utěrkou č. 2 a č. 3, porovnat. Trend postupného světlání = čirý lak zbývá, všechny stejně tmavé = báze. Mřížka 6 polí + zvlášť pole na přední hraně u světel a na prolisu. Etalon = střed kapoty, kde se Jonda vidí v odraze.
3. 21:19 - Střecha + kapota jsou 2,5 m2. Kolik plechovek dokoupit (barva, plnič, čirý), max dvě vrstvy, co nejšetrněji. Asistent hledal na webu vydatnost sprejů.
4. 21:22 - "Nebudu kupovat epoxy, mám ten Würth, na něj dám normální plnič."

## Výpočet materiálu na 2,5 m2 (střecha + kapota)
Rozptyl vydatností mezi zdroji je velký. Použité údaje z webu:
- Báze 400 ml míchaný sprej: 3/4 až 1 m2 (Unimax/SprayMax). Česká mícharna Autoplay: min. 100 ml neředěné barvy v dóze 375-400 ml a cca 1 m2 na sprej.
- Čirý 400 ml: Renopro cca 2 m2 v jedné vrstvě. ColorMatic 2K 200 ml = 0,3-0,4 m2 (tedy 400 ml = 0,6-0,8 m2). MoTip akryl 500 ml = 1,5-2,0 m2. Plánovat 1-1,5 m2 na dózu při dvou vrstvách.
- SprayMax 2K čirý: po aktivaci tužidla spotřebovat do 3 dnů.
Potřeba na 2,5 m2: báze 3-4 dózy (má 2, dokoupit 2), čirý 3-4 dózy (má 2, dokoupit 2), plnič 0 (500 ml stačí). Cca 2 000-2 200 Kč.
Levnější varianta: kapota sama je cca 1 m2, na ni má materiálu přesně dost. Střecha později, klidně z jiné dávky (nesousedí s kapotou).
Zásada: na bázi šetřit lze (tenké vrstvy jsou u metalízy i lepší), na čirém ne. Tenký čirý je přesně to, proč je auto v tomhle stavu.

## Rozhodnutí
- Levná metalíza z Actionu: zamítnuto.
- Bez epoxidového základu (Jonda ho odmítl kupovat, má Würth). Würth konvertor jen tam, kde se nebude tmelit (spodek kapoty, prahy, zadní sloupek). Na vybroušený čistý plech rovnou polyesterový tmel (tehdejší tvrzení asistenta, později částečně opravené, viz 06-chyby-a-opravy-asistenta.md). Plnič nikdy na holý plech (je 1K). Cena za to: životnost opravy spíš 3-5 let než 8. Kritické je ošetření spodní strany kapoty.
- Postup u díry skrz: vybrousit do zdravého plechu, odmastit, laminovací sada 710 zespodu (skelná rohož + pryskyřice), Novol Fiber shora, P80/P120/P240, plnič, báze, čirý. (Později se ukázalo, že kapota skrz prorezlá není.)
- Kapotu a blatníky sundat z auta a lakovat na kozách naležato (později zrušeno: kozy nemá, kapota zůstala na autě, sundána jen maska).

## Stav na konci dne
Před shrnutím konverzace nebyl hotový test třemi utěrkami ani prosvícení masky kapoty zespodu. Materiál zůstává: báze 2 dózy, čirý 2 dózy. Dokup jen pokud se lakuje střecha.

## Další krok
Test třemi utěrkami, prosvítit masku zespodu, zjistit, kde je rez. Sehnat blatníky z Bazoše (později zrušeno).


---

ZDROJ: dny/2026-09-17-az-22_datum-neznamy/sezeni-1_dira-tmel-brunox-vs-wurth.md

# Sezení 1 - díra skrz, tmel, Brunox vs Würth

DATUM NENÍ ZNÁMÝ. Zprávy po shrnutí konverzace (16. 9. večer) nemají časová razítka. Odhad: 17.-22. 9. 2026. Pořadí sezení 1-6 je ale správné (chronologické). Nahraď datum, jakmile ho budeš znát.

## Co jsem řešil (otázky a odpovědi)
1. Když vybrousím díru skoro skrz naskrz, co tam dám: Würth, na to tmel a na to plnič? Odpověď asistenta (později zpřesněná): u díry rovnou vybrousit do zdravého plechu, odmastit, polyesterový tmel (Novol Fiber se sklem přemosťuje), P80 -> P120 -> P240, plnič. Würth na prahy, zadní sloupek a spodek kapoty. Pravidlo z té doby: kde budeš tmelit, tam Würth nedávat.
2. Jak srovnat tmel, mám ještě normální hladký. Asistent hledal na webu rady od lidí z oboru. Shrnutí:
   - Novol Fiber (se sklem) první, plní hloubku. Hladký tmel navrch, dorovnává tvar a plní póry po skelném vláknu.
   - Nikdy celý defekt jednou silnou vrstvou. Vrstvy 2-3 mm, každou nechat vytvrdnout.
   - Míchání do jednolité barvy bez šmouh, nedostatek tužidla = nikdy neztvrdne.
   - Zrnitosti P80 -> P120 -> P180-240, na hoblíku nebo excentrické brusce, ne na houbičce.
   - Broušení má kopírovat původní tvar karoserie, ne vytvářet nové hrany.
   - Kontrolní pudr nebo tenká mlha černého spreje z dálky = vodicí vrstva.
   - Rovinu kontrolovat dlaní přes tenký igelit. Brousit křížem. Okraj tmelu vyzáběhnout do ztracena (schod nehtem = uvidíš pod lakem).
3. Jonda: "Takže když vybrousím rezavou díru, tak tam nemám dávat odrezovač? To nedává smysl. I když to probrousím na plech, tak se to může rozlézt, ne? To odrezovač můžu vrátit rovnou." Odpověď: konvertor je nástroj na rez, kterou nedokážeš odstranit. Z lesklého plechu se rez nerozlézá, rozleze se ze zbytků v důlcích, ze spodní strany a z okraje. Shora tam, kde se tmelí: brousit do hnědé pryč, bodově konvertor jen do důlků, ne plošně. Zespodu plošně. Prahy a zadní sloupek plošně. Konvertor nevracet, použije se na spodek kapoty, prahy a sloupek.
4. Jonda: vrátí Würth a vezme Brunox. Asistent nejdřív chybně řekl, že Brunox má stejné omezení jako konvertor a že mu nic nevyřeší. Jonda: "Vždyť Brunox má v sobě i epoxidovou vrstvu." Asistent ověřil technický list.
5. Jonda: "Zdělej mi seznam věcí, co mám, co jsme na autě udělali, jaké jsou zatím diagnózy (jen teoretické) a co chci na autě dělat." Byl sestaven přehled (vybavení, hotové kroky, potvrzené vs teoretické diagnózy, plán).

## Zjištění o Brunox Epoxy (z technického listu a webu výrobce)
- Po kompletním ztvrdnutí ochranné vrstvy (nedá se udělat nehtem rýha) lze nanést i polyesterový tmel, se skelným vláknem nebo jemnou stěrku.
- Nanáší se 2-4x podle stupně zrezavění, mezischnutí 6-12 hodin. Zavadnutí po hodině, vytvrzení 12 hodin. Při teplotě pod 20 °C a vyšší vlhkosti schne déle než 24 hodin (garáž má 19 °C, počítat s 2-3 dny).
- Neomývat, neobrušovat, nečistit odstraňovačem silikonu, jinak se sundá základní nátěr.
- Vrstva cca 5 mikrometrů.
- Jeden velký český eshop píše na stránce obojí (použitelný s polyesterem a zároveň nelze přímo aplikovat polyester). To je text prodejce, ne výrobce.
- Odmaštění a broušení proto před Brunoxem, ne po něm. U 2K se doporučuje zkouška slučitelnosti na zkušebním kartónu.

## Rozhodnutí
- Würth se nevrací. Použije se na spodek kapoty, prahy, zadní sloupek a později i jinde.
- Brunox: Jonda je pro (sám navrhl), ale skladovost a dokoupení nevyřešeno (v minulosti byl doprodaný). Nakonec v tomto projektu se používá Würth.

## Korekce
- Asistent tvrdil, že Brunox a konvertory mají totéž omezení. Nepravda, Brunox má epoxidovou složku a polyesterový tmel na něm smí.
- Zamotané vysvětlení "tabulkou" pro Würth vs tmel: uživatel se opakovaně ptal, protože to nedávalo smysl. Pravidlo pak: konvertor jen na rez, kterou nejde odstranit mechanicky.

## Další krok
Zjistit rozsah rzi na kapotě, rozhodnout, co dělat s hodinou volného času.


---

ZDROJ: dny/2026-09-17-az-22_datum-neznamy/sezeni-2_hodina-casu-kapota-torx.md

# Sezení 2 - hodina volného času, kapota, blatníky, torx

DATUM NENÍ ZNÁMÝ (odhad 17.-22. 9. 2026). Pořadí sezení je správné.

## Co jsem řešil (otázky a odpovědi)
1. "Budu mít teď hodinu čistého času, mám vybrousit a zatmelit rez?" Odpověď: ne brousit a netmelit. Důvody: čerstvě vyleštěná kapota (jiskry z drátěného kotouče se zapékají do laku), kapota je pořád na autě (u díry skrz musí jít laminát zespodu první), Brunox nebyl koupený. Doporučeno: test třemi utěrkami a mapování rzi.
2. Jonda: "Co? Nebudu mapovat." Asistent: sundat kapotu. Jonda: kapotu odmontovávat nebude, nemá kozy a nemá ji kam dát, jen odmontuje masku s grilem. Asistent: OK, kapota zůstane na autě, důkladně zamaskovat předek plachtou (jiskry), lakovat naležato nebude možné, tedy tenčí vrstvy a pozor na stékance.
3. Fotky kapoty (6 kusů) a poznámka: "Z druhé strany nic není za rez." Ukázalo se, že rez nejde zespodu ven, ale shora dovnitř: odražené kamínky prorazí lak, pod ním začne plech rezavět a rez nadzvedne lak do puchýře. Důsledky: žádný průraz, prosvěcování zespodu škrtnuto, laminovací sada Novol 710 není na kapotu potřeba, Novol Fiber taky ne (na svařenec a hluboké díry, ne na důlek po kamínku). Zbývá hladký tmel v tenké stěrce, u mělkých důlků možná ani ten (vyplní plnič).
4. Jonda: "Tohle teďka asi nemá smysl nelakovat celé, ne? To bude mnohem jednodušší udělat celou kapotu." Asistent souhlasil: metalíza se nedá rozstříkat do ztracena uprostřed rovné plochy (pět šest ohnisek po celé ploše = pět šest hal), celou kapotou zmizí i zákal a test utěrkami už nemusí dělat, práce navíc je jen broušení plochy. Postup: rez otevřít, ošetřit, ohniska tmelit tenkou stěrkou, celou kapotu přebrousit P400, plnič jen na opravená místa, báze na celou kapotu 2 vrstvy, čirý 2 vrstvy.
5. Blatníky. Asistent nabízel zvážit výměnu použitých z Bazoše. Jonda: "Nechci blatníky měnit, já ti říkám, proč bych kupoval ty laminát." Asistent se omluvil: laminát a Novol Fiber patří na prorezlé blatníky, ne na kapotu. Blatníky jsou šroubované (Octavia I jde sundat bez řezání), lakují se celé edge to edge. Jonda upřesnil: blatníky bude dělat jen dole u prahu, jinak jsou v pohodě a stačí rozleštit.
6. Velké hvězdičky (torx) na šrouby kapoty, bity v sadě na šroubovák byly moc malé. Jaký je to rozměr a kde to sehnat do ruky? Odpověď: torx T45 (horní šroub pantu kapoty na každé straně), ber i T50. Chtít bitovou hlavici 1/2" (ne bit v držáku). Koupit v železářství (Hornbach, Bauhaus, Mountfield) cca 80-150 Kč za kus. Sada BGS Technic 5098 (12 hlavic, cca 479 Kč) je na 1/4", slabší. Honiton HA080 1/2" T15-T60 za cca 1 322 Kč je zbytečná. Penetrační olej hodinu předem, hlavici zatlačit vší silou.

## Rozhodnutí
- Kapota zůstane na autě (bez koz). Sundána bude jen maska s grilem, aby šlo k přední hraně zespodu.
- Kapota se lakuje CELÁ (změna oproti 15. 9., kdy se počítalo jen s leštěním).
- Blatníky se nemění a nesundávají. Opraví se jen dole u prahů (rez) a jinak se rozleští.
- Laminovací sada: patří na blatníky (spodek u prahu), ne na kapotu.

## Korekce
- Asistent nejdřív navrhl prosvěcování a laminát u díry, ale rez byla povrchová od kamínků.
- Asistent si spletl, ke kterému dílu se laminát vztahuje (viz bod 5).
- Jonda odmítl mapovat rez a sundávat kapotu, důvody byly praktické (nemá kam).

## Nákupy
- Torx hlavice T45 (případně T50), 1/2", doporučeno (nákup nepotvrzen).

## Další krok
Otevřít každý puchýř brusnou (malou bruskou), vysát, odmastit, Würth.


---

ZDROJ: dny/2026-09-17-az-22_datum-neznamy/sezeni-3_brouseni-na-plech-wurth-zelezo.md

# Sezení 3 - broušení do plechu, odželezovač na holém plechu, Würth

DATUM NENÍ ZNÁMÝ (odhad 17.-22. 9. 2026). Pořadí sezení je správné.

## Co jsem řešil (otázky a odpovědi)
1. Fotka místa vybroušeného na plech: "Vybrousil jsem rez úplně na plech, co s tím? Mám tam dávat Würth? Prý se na to může dát plnič, říkal výrobce, nebo mám stříknout jen plničem?" Odpověď: Würth ano (u vybroušeného místa bez tmelu), samotný 1K plnič na holý plech ne (Novol 1K má nižší přilnavost ke kovu, neobsahuje antikorozní ochranu, není vhodný jako základ na holý kov). Na fotce vlevo nahoře byla ještě neošetřená rez na ohnuté hraně a kolem otvoru. Postup: odmastit Novol 780, nesahat na plech prsty, Würth tence dvě vrstvy podle etikety, doba přelakovatelnosti z etikety, plnič 2-3 vrstvy, přebrousit P400, báze, čirý. Otázka na důlek nehtem: pokud je prohlubeň, 1K plnič ji nedorovná (plní desetiny milimetru), pak tenká stěrka hladkého tmelu rovnou na čistý plech.
2. Fotky 7 kusů (velké množství vybroušených děr od kamínků, ohniska rozeseté po celé přední části): "Je tam strašně moc děr od kamínků, které jsou prorezlé, nemám ten předek kapoty vzít celý smirglem, abych na něco nezapomněl?" Odpověď: ano, ale plošné broušení slouží jako mapa (lesklé tečky vyskočí na matném povrchu), rez v kráteru samo o sobě neodstraní. Na fotkách žlutavý prstenec kolem fleků = tovární plnič (v pořádku, prošel čirým a bází, ne ještě na plech).
3. Jonda: "Je tam každých 5 cm milimetrová dírka, ale není hluboká, je to jen povrchová rez." Odpověď: při té hustotě a mělkosti celý přední pás dolů na plech najednou. Vymezit pás páskou, P80 na excentrické brusce, kontrola pod světlem a nehtem, vysát, odmastit, Würth celý pás, plnič celý pás, P400, báze, čirý. Drátěný kotouč na plošné broušení nestačí (drát rez v důlku spíš vyhladí a začerní). Na přední hraně opatrně (plech nejtenčí), dokončit ručně. Pokud je to jen mělká povrchová rez, tmel nejspíš vůbec nebude potřeba.
4. Fotky a etiketa čističe kol Moje Auto "Felgi krwawe koło" (Wheel Cleaner Red, efekt krvácení): použil ho na vybroušený plech, teče červeně i z vyleštěných míst, i po ocelovém kartáči. "Jak tento saponát funguje, je tam opravdu rez? Nebo to reaguje na železo?" Odpověď: reaguje na ŽELEZO (derivát kyseliny thioglykolové vytvoří s ionty železa červenofialový komplex), ne na rez. Na holém plechu je to plošný falešný poplach a kyselina, která zůstane v pórech, naruší adhezi a způsobí flash rust. Ocelový kartáč rozetřel mikročástice oceli. Co udělat: důkladně opláchnout, okamžitě vysušit, přebrousit P80-P120 celý pás (soli se odmašťovačem nedostaneš), vysát, odmastit, Würth. V levém flaku byla skutečná oranžová rez (matně oranžová až hnědá, v důlku), ostatní byly reakce činidla. Na příště: odželezovač na lak před claybarem, ne na holý plech.
5. Fotka celé kapoty s mnoha tečkami. Jonda: hodně teček obroušeno na plech, není to úplně hladké, za 30 minut chce končit: zapatlat Würthem a jít domů, nebo dát plnič? A vadí, že to není nejlépe zabroušené? Nebo jen jednu vrstvu Würthu? Odpověď: Würth a jít domů. Nehladkost teď nevadí (rovina se dělá po plniči). Kolik vrstev: kolik říká etiketa. Nejdřív vysát, odmastit, Würth první vrstvu. Plnič dnes ne (po vytvrzení Würthu a v okně přelakovatelnosti).
6. "Würth i tam, kde to není na plech?" Odpověď: ne. Jen na holý plech a zbytky rzi, štětečkem bodově s přesahem 2-3 mm přes okraj. Plnič pak plošně přes celý pás.
7. "Zítra to budu muset dobrousit? Mám to jen 100kou celý broušený." Odpověď: ano, P100 je pod plnič moc hrubá. Cíl P180 -> P240 (později se ukázalo, že je lepší P320-400). Na vytvrzený Würth se brousit nesmí (podle tehdejší informace, viz 06-chyby). Varianta A (doporučená): dnes dobrousit, Würth zítra. Varianta B: dnes Würth na tečky a zítra brousit jen mezi nimi.
8. "Nemám tam dát vrstvičku Würthu a pak ji zbrousit a dát další? Nevadí, že bude plech odkrytý třeba 12 h?" Odpověď: ne brousit a nedávat další (vrstva má pár mikrometrů, zbrousíš ji celou, narušíš vazbu). Holý plech přes noc v suché garáži by nevadil.
9. Jonda doplnil: vlhkost je normální možná lehce nad normál, teplota bude kolem 15 přes noc, v garáži tak 17. Odpověď: to mění situaci, kondenzace na chladnějším plechu způsobí ráno rovnoměrný hnědý závoj. Dnes tedy dobrousit P180 -> P240, vysát, odmastit, Würth štětečkem jen na tečky, nechat běžet větráček. Pomůcka: přejet suchým hadrem před odchodem.
10. "Nevadí kdybych ten Würth zítra obrousil a dal nový?" Odpověď: vadí (chemicky vázaná vrstva, zbroušením obnažíš zreagovaný plech, horší vazba, nepoznáš, kdy jsi ji prošel). Pojistka: přečíst etiketu (doba mezi vrstvami, počet vrstev).
11. Jonda: "Tak to nechám hold tak, jak to je, bez Würthu." Odpověď: v pohodě, ráno bude nejspíš lehký hnědý závoj, sundat P240 nasucho, odmastit, Würth. Suchý hadr před odchodem, větráček běží.

## Rozhodnutí
- Celý přední pás kapoty se brousí najednou na plech (P80 excentr), ne bodově.
- Würth jen na holý plech, ne na lak.
- Večer po tomto sezení nechal plech bez Würthu, Würth šel až po dobroušení dalším dnem (viz sezení 4).
- Odželezovač už nikdy na holý plech.

## Korekce
- Použití čističe s krvácením na holém plechu byla chyba na straně Jondy (asistent to vysvětlil, nezavinil).
- Asistent později opravil informaci, že Würth nelze po vytvrzení brousit/odmašťovat (u tohoto konkrétního produktu jde o "neoplachovat vodou"), viz 06-chyby.

## Nákupy
- Žádné.

## Další krok
Dobrousit na P180 -> P240, Würth, plnič, P400.


---

ZDROJ: dny/2026-09-17-az-22_datum-neznamy/sezeni-4_plnice-wurth-1l-tmel-lem.md

# Sezení 4 - dva plniče, Würth 1 l, tmel, lem kapoty, silikon

DATUM NENÍ ZNÁMÝ (odhad 17.-22. 9. 2026). Pořadí sezení je správné.

## Co jsem řešil (otázky a odpovědi)
1. Jonda viděl video o lakování černé metalízy a "asi bude potřebovat na kapotu dva plniče", pod černou jde všechno vidět. Mám dělat jen s jedním, nebo dokoupit druhý od jiné značky? Nebo koupit dva od jiné značky a první vrátit? Vybroušil na plech některá místa i u čelního skla a uprostřed kapoty. Odpověď: obava je opodstatněná (halo vzniká z rozdílné savosti plniče a starého laku, ne z barvy). Plnič přes celou kapotu je správně. Druhou dózu koupit (kapota 1-1,2 m2, 500 ml na 2-3 vrstvy je na hraně). Novol nevracet. Míchat značky u 1K akrylového plniče není problém, pokud jsou oba 1K akrylové a středně šedé. Asistent nenašel přesnou vydatnost Novolu na m2 (jen popis produktu), počítal z obecných hodnot 500ml aerosolů.
2. Novol Acrylic Primer je podle popisu výrobce určený na tmely a staré laky a má nižší přilnavost ke kovu, není vhodný jako základ na holý kov. Tudíž pořadí: Würth bodově na holý plech, teprve pak plnič.
3. Jak dlouho Würth schne? Odpověď (web): sprej lze přelakovat po 2 h (2-3 tenké vrstvy z 25-30 cm), tekutý Odrezovač 1 l musí být v okně 3-48 h po aplikaci přetřen ochranným prostředkem na kov po 3hodinové reakční době. Pouze jednosložkové produkty na přetírání (tvůj Novol 1K je OK). Předchozí zmínka o 6-12 h pauze patřila Brunoxu.
4. Jonda poslal odkaz na autochladek.cz: Würth antikorozní nátěr / inhibitor 1 l. "Mám tento, urychlím to horkovzduškou třeba po hodině a půl?" Odpověď: NE. 3 h je reakční doba, ne doba schnutí. Produkt je disperzní (voda je nosič), horkovzduchem se reakce zastaví. Nepoužívat na horkých plochách nad 40 °C. Nanést jednu tenkou rovnoměrnou vrstvu štětcem nebo válečkem, zabránit stékání. Neoplachovat vodou. Lze přetírat všemi běžnými krycími nátěry. TENTO PRODUKT tmelení výslovně umožňuje (oprava dřívějších tvrzení asistenta).
4b. Zrnitost před plničem: Jonda přeposlal rady jiných AI. GPT řekl, ať před plničem končí P320, Grok řekl P400, YouTube taky 400. Kde asistent vzal P240? Odpověď: P240 sedí pro tlustý 2K high build plnič, ne pro tenký 1K akrylový sprej (Novol), který nanese zlomek a rýhu po P240 neschová. Technický list Novolu s předepsanou zrnitostí asistent nenašel, jen popisy produktu. Pracovní hodnota: P320, klidně P400 (rozdíl v praxi bezvýznamný). Jonda měl pravdu.
5. Poslal fotku etikety (Wurth ANTIKOROZNÍ NÁTĚR/INHIBITOR). "Kolik vrstev mám dát, mám to vysmirglované 400 a žádné tečky rzi nejdou vidět, důlky nejdou cítit po přejetí." Odpověď: jednu (etiketa říká: naneste tenkou rovnoměrnou vrstvu, žádný počet). Aplikace: štětec, jen holý plech, přesah 2-3 mm, odmastit těsně předtím, zakrýt plochy, které neošetřuješ, 3 h reakční doba, plnič v okně 3-48 h, po Würthu nebrousit a neoplachovat vodou. Žádné důlky = tmel nebude potřeba, plnič zarovná sám.
6. Fotky po Würthu (5 kusů: kapota shora, lem/okraj kapoty, drážka po stranách). Jonda: mám dát jemný tmel? Nevyleze to na laku, když tam dám jen plnič? Po bocích kapoty je drážka, kde byl nějaký plast/guma, a u toho to rezne, mám to vytmelit nebo jen zatřít Würthem (nebude to vidět z venku)? Odpověď: 
   - Na fotkách Würth funguje (krémový prstenec = film na čistém plechu, fialovočerný střed = zreagovaná rez).
   - Tmel na Würth smí (tento produkt to povoluje), ale jen tam, kde nehet zadrhne. Rozhodovací pravidlo: nezadrhne = jen plnič, zadrhne = tenká stěrka. Důlky dorovnáš až po vodicí vrstvě a broušení plniče, tmel nad plničem je bezpečnější než nad Würthem.
   - Lem/drážka po stranách kapoty: jen Würth, tmel ne (lem pracuje, je to vodní past, polyester je porézní). Vyškrábat popraskaný starý tmel, kartáčem volnou rez, odmastit, Würth do spáry, po vytvrzení pružný karosářský spárovací tmel (butyl / MS polymer / PU) nebo tekutý vosk do dutin. Rez v lemu je vážnější než tečky nahoře.
7. Dva plniče od různých značek, trochu jiný odstín šedé. Jonda: mám dát jednu vrstvu jeden a druhou vrstvu Novol, aby to nebylo flekaté, nebo půl na půl? Odpověď: neprokládat po plochách, vrstvit přes celou kapotu. Navrchu má být všude jedna značka (jednotná savost poslední vrstvy). Plnič po vybroušení nemá být vidět skrz, od toho jsou dvě vrstvy báze.
8. "Nebudu kupovat další tmel, co silikon?" Odpověď: NE. Silikon migruje a dělá v laku kráterky, na silikon nejde nic nalakovat. Na lem nedávat nic, jen Würth. Po laku tekutý vosk do dutin (cca 150 Kč), ne teď.
9. "Mám ready, můžu dát plnič? Chtělo by to zabrousit některé části, kde to udělalo bublinky malé." Odpověď: bublinky nebrousit (Würth se brousit nesmí). Zkusit nehtem: nezadrhne = nechat, zrnka = setřít suchým hadrem, tvrdé puchýřky = poslat foto zblízka. Před stříkáním: reakční doba 3 h, vysát, neodmašťovat Novolem 780 (asistent tvrdil, že na vytvrzený konvertor rozpouštědlový odmašťovač nepatří, viz 08-otevrene), topení pryč, dózy ve vlažné vodě do 40 °C, respirátor.
10. Fotky dvou plničů: Novol Acrylic Primer šedý 500 ml (170 Kč) a Chamäleon Thick Layer Filler High Build Primer 400 ml šedý (370 Kč). "Jaký dát dolů?" Odpověď: Chamäleon dolů, ale jen na opravená místa (tečky a přední pás), protože 400 ml high build nevystačí na celou kapotu. Novol přes celou kapotu nakonec (poslední vrstva = jednotná savost).
11. Fotky etikety Chamäleonu: Jonda upozornil, že to NENÍ 2K a po 2 h se může přelakovat a brousit. Odpověď: etiketa říká 3 tenké vrstvy, 5 min mezi nimi, vzdálenost 25-30 cm, zpracování 15-25 °C, proschnutí 1 h při 20 °C, brousit a přelakovat po 2 h, brousit nasucho P400-500, pod vodou P800-1000, rozpouštědlový 1K (aceton, butylacetát, uhlovodíky). Původní "nechat přes noc" bylo zbytečně opatrné.
12. "Chameleon vydrží jednu lehkou a druhou tlustší, pak dojde, ale co dělat, kdyby mi došel v půlce druhé?" Odpověď: stříkat podle priority (přední hrana a pás, tečky, kde nehet zadrhne, mělké tečky nakonec), pokud dojde, pokračovat Novolem, vodicí vrstva ukáže, kde plniče chybí. Nešetřit stříkáním z větší dálky (suchý nástřik). Protřepat mezi vrstvami. Trysku vyčistit až nakonec.
13. Jonda: "Udělej mi to graficky vyznačeně na nakreslené kapotě, kde mám co stříkat." Vznikl diagram zón (Chamäleon = přední hrana + tečky, Novol = celá plocha navrch). Otázka: první vrstva jen tečky na vybroušené body, nevyleze to pak? Odpověď: neprosvitne, pokud okraje "zmizí do ztracena" (mačkat a pouštět spoušť mimo tečku, po vybroušení nehet přes okraj).
14. Jonda přeposlal radu od Groku: nejdřív Novol (lepší přilnavost, levnější), potom Chamäleon, 24 hodin čekat není nutné. Odpověď: 24 h čekání opravdu není nutné (etiketa: 2 h). Premisa o lepší přilnavosti Novolu je obrácená (Novol má nižší přilnavost ke kovu, přilnavost dělá Würth). Plán "Novol všude ve dvou vrstvách, pak Chamäleon, pak Novol znovu" by spotřeboval materiál, který nemá (3 průchody celou kapotou z jedné 500ml dózy). Kus pravdy: jedna vrstva Novolu přes všechno pro sjednocení = přesně princip, o který jde.
15. "Takže mám nastříkat nejdřív body a pás? Nebo první vrstvu Chamäleonu klasickou tenkou a pak ty body? Nebo jen body a pás a brousit? Jak teda? Zamysli se." Odpověď (finální): jen body a pás, žádná celoplošná vrstva Chamäleonu. Nastříkat oblasti ne jednotlivé tečky (kužel 15-20 cm): přední pás jako souvislý tah, přední polovina s tečkami každých 5 cm jako souvislá plocha, jednotlivé tečky vzadu a u skla zvlášť. Tři vrstvy, každá o cca 2 cm širší (rozprostřít schody). Pak 2 h, vodicí vrstva, P400 do roviny, nehet přes okraj, vysát, odmastit, Novol přes celou kapotu 2 vrstvy, jen zmatovat P400, báze.

## Rozhodnutí
- Würth: jedna tenká vrstva štětečkem jen na holý plech (v lemu štědře do spáry).
- Plniče: Chamäleon jen na opravená místa (3 vrstvy, každá o 2 cm širší), Novol přes celou kapotu 2 vrstvy navrch.
- Lem kapoty: jen Würth, později pružný spárovací tmel nebo vosk. Žádný silikon.
- Další tmel se nekupuje.
- 24 h schnutí plniče neplatí, řídit se etiketou (2 h).

## Korekce
- 24 h čekání u plniče: zbytečně dlouhé.
- Tvrzení "6-12 h pauza u Würthu" patřilo Brunoxu.
- Celou dobu se tvrdilo, že na konvertor nesmí polyesterový tmel. U Würth inhibitoru to neplatí, u Novol/Chamäleon 1K plniče to nebyl problém.

## Nákupy
- Würth antikorozní nátěr/inhibitor 1 l (odkaz autochladek.cz, kdy a kde přesně koupeno neuvedeno).
- Chamäleon Thick Layer Filler High Build Primer grey 400 ml, 370 Kč.
- Novol Acrylic Primer šedý 500 ml, 170 Kč (druhý nebo první kus, viz 08-otevrene).
- Nekoupeno: silikon, spárovací tmel, černý plnič.


---

ZDROJ: dny/2026-09-17-az-22_datum-neznamy/sezeni-5_nastrik-plnice.md

# Sezení 5 - nástřik plniče (první, druhá, třetí vrstva)

DATUM NENÍ ZNÁMÝ (odhad 17.-22. 9. 2026). Pořadí sezení je správné. Z uložených poznámek vyplývá, že plnič byl hotový do 22. 9. 2026.

## Co jsem dělal
- Stříkal plnič na kapotu (viz níže, která značka přesně, není jisté).
- Poslal fotky první, druhé a hotové vrstvy.

## Co jsem řešil (otázky a odpovědi)
1. Fotka první vrstvy: "Nestříkalo to vůbec dobře." Odpověď: první vrstva má vypadat takhle (tenká, nesouvislá, prosvítá), druhá a třetí to srovnají. Zkontrolovat: (a) jestli není povrch na omak jako smirek (suchý nástřik, stříkáš z velké dálky nebo rychle), (b) vzdálenost 25-30 cm, pomaleji, (c) jestli dóza nevychladla (15-25 °C, ponořit na pár minut do vlažné vody, max 40 °C). Další vrstva: protřepat 2 min, 5 min pauza, překryv 50 %, o 2 cm širší.
2. Fotka druhé vrstvy. Odpověď: velký skok, krytí souvislé po celé ploše, žádné prosvítání. Drobnosti: vodorovné pruhy (přechody mezi tahy, vybrousí se), lehký lesk vlevo dole (vlhčí vrstva, tam nezůstávat). Třetí vrstva: nejtenčí ze všech, o 2 cm širší, po 5 min, pak 2 h a broušení. Připravit černý sprej na vodicí vrstvu, P400 nasucho, tvrdý hoblík, tenký igelit na kontrolu dlaní.
3. Hotový základ (5 fotek): "Takhle vypadá můj základ, padla celá plechovka, povrch je hrubý jako smirgl." Odpověď: hrubý povrch je u plniče normální (materiál určený k broušení). Test 10x10 cm P400: pod hrubým povrchem hladká kompaktní šedá = textura (brousit dál), drolí se/práškuje = suchý nástřik skrz naskrz (přidat materiál). Dál: vodicí vrstva, P400 nasucho na hoblíku/tvrdé houbě, křížem, dokud černá nezmizí, dlaň přes igelit. Po broušení bude mozaika různých podkladů, Novol navrch ji sjednotí.

## Poznámky o materiálu
- Uložené poznámky říkají: 3 vrstvy plniče Novol SPRAY Acrylic Primer šedý, celá plechovka. Ze zpráv ale není jisté, jestli se Chamäleon Thick Layer Filler skutečně použil na body a pás podle plánu. Ověřit.

## Rozhodnutí
- Přejít k broušení plniče P400 nasucho s vodicí vrstvou.
- Novol navrch (2 vrstvy) po broušení jako sjednocení savosti (podle doporučení), použití nepotvrzeno.

## Další krok
Vodicí vrstva, P400, zjemnění rounem K800 (viz sezení 6).


---

ZDROJ: dny/2026-09-17-az-22_datum-neznamy/sezeni-6_brouseni-plnice-vodici-vrstva.md

# Sezení 6 - broušení plniče, rouno K800, vodicí vrstva, založení deníku

DATUM NENÍ ZNÁMÝ (odhad: 22. 9. a později, do 30. 9. 2026). Poslední sezení před založením tohoto deníku (30. 9. 2026).

## Co jsem dělal
- Plnič je "dávno uschlý". Nejvíc viditelné vady vyfotil (7 fotek): ruční hoblík s P400, excentrická bruska s hnědočerveným rounem (K800 / nonwoven disk), tmavá kapota po broušení, hrudky a stékance u přední hrany, tmavé tečky prachu v plniči.
- Použitá výbava: papír P400 (má jen tyhle), na excentr K800 rouno (tlusté měkké disky z vláken), papíry 1000 a větší.

## Co jsem řešil (otázky a odpovědi)
1. "Plnič už je dávno uschlý, největší nedostatky jsem ti vyfotil, ale nevypadá to špatně. Mám papíry akorát 400, pak na excentrickou brusku 800 (tlusté měkčí disky z vláken). Jak mám perfektně připravit na lakování báze? Brusné papíry mám pak už jen 1000 a větší." Odpověď:
   - Na fotkách: čtvrtá fotka u přední hrany vystouplé hrudky a táhlé výstupky (buď stékance plniče, nebo bublinky z Würthu zkopírované plničem), šestá fotka tmavé tečky = prach zachycený v plniči.
   - P400 (etiketa Chamäleonu) je broušení pro rovinu, ale pod černou metalízou můžou rýhy po P400 prosvitnout (vločky hliníku se zalehnou jinak).
   - Postup: (1) vady P400 na tvrdém hoblíku (hrudky, tečky prachu; pozor, jestli jsou to bublinky Würthu, nebrousit až na krémovou nebo kov), (2) vodicí vrstva a P400 na celou plochu, poslední průchody s menším přítlakem, (3) zjemnit rounem 800 na excentru nasucho, brusku naplocho, hrany a prolisy ručně, (4) kontrola pod ostrým světlem (žádné tahy) a dlaní přes tenký igelit.
   - Proč ne P1000 pod vodou: 1K plnič nasákne vodu (puchýře pod bází) a Würth se nesmí oplachovat vodou. Rouno 800 nasucho dá podobnou jemnost.
   - Prodřené místo: podstříknout Novolem 2 tenké vrstvy, 2 h, znovu zjemnit rounem. Báze má ležet všude na plniči.
   - Těsně před bází: vysát, odmastit Novol 780 (nanést a hned setřít), 10 minut počkat, antistatická utěrka Gerson, topení pryč, dózy báze do vlažné vody max 40 °C, respirátor, větrání.
2. Foto: Spectrum Metallic (Spray paint) High-Gloss Metallic black, 400 ml (1,75-2,25 m2, 10 min quick dry, in & out door, low odour). "Můžu použít toto na broušení? Levnější sprej nemám." Odpověď: ano, jako vodicí vrstvu (na kapotě nezůstane, celá se zbrousí). Podmínky: jen mlha z velké dálky (50 cm a víc, jeden rychlý přelet), schnout 20-30 min (ne jen 10 min z dózy, jinak zalepí papír), zbrousit úplně celý (pod bázi z něj nesmí zůstat nic), kontrolovat papír (zanesený dělá hlubší rýhy). Alternativa: suchá vodicí vrstva (prášek z tužky nebo uhlu rozetřený suchým hadříkem).
3. 30. 9. 2026: "Udělej mi GitHub repozitář nebo prostě repozitář, který budu moct vložit do nového Claude projektu, chci aby tam bylo ve složkách po jednotlivých dnech, kdy jsem co dělal a úplně všechny věci, co jsem řešil, dělal a koupil. Chci aby to bylo jako takový deník, z kterého by Claude mohl čerpat informace." Vznikl tento repozitář.

## Rozhodnutí
- Po plniči: vodicí vrstva Spectrum černý metalický sprej (mlha, schnout 20-30 min), P400 dobrousit vady na hoblíku, zjemnit rounem K800 nasucho.
- P1000 pod vodou se nepoužije.
- Prodřené místo: Novol 2 tenké vrstvy, 2 h, zjemnit.

## Korekce
- P240 pod 1K plnič bylo hrubé (GPT/Grok/YouTube měli pravdu ohledně P320-400).
- Původní tvrzení "24 h schnutí" už dřív opraveno na 2 h.

## Nákupy
- Spectrum Metallic black spray 400 ml (má ho, cena neuvedena, sloužil jako "levnější sprej" pro vodicí vrstvu).

## Stav na konci
Plnič na kapotě, broušení P400 + K800 rozpracováno / hotovo (nepotvrzeno). Další krok: kontrola šikmým světlem, případné podstříknutí prodřených míst, odmastit, báze, čirý.
