# 2026-09-30 (středa)

Datum JISTÉ. Sloučení deníku v bodě 4 proběhlo večer 30. 9. až po půlnoci 1. 10.

## Co se dělo
Na autě se tento den nic nedělalo, řešil se jen deník.
1. V prvním chatu vznikl původní deník (stav k 30. 9. podle konverzace od 14. 9., viz dny/2026-09-17-az-22_datum-neznamy/sezeni-6). Do repozitáře Jondova_octavia (účet Jonda007) se dostal jako jeden commit (038c64e) už se strukturou složek 00-prehled/ a dny/.
2. Ve druhém chatu Jonda požádal o doplnění repozitáře o všechno do posledního detailu: co dělal, jaké má nástroje, jak to dopadlo, včetně fotek. První pokus se přerušil (Jondovi se chat seknul a došel limit), nic se nenahrálo. Potom Jonda v GitHubu dal Claudovi oprávnění k repozitáři, ale ten chat neměl nástroj pro GitHub ani přihlašovací údaje, push nebyl možný. Claude proto připravil zip pro ruční nahrání: nové dny 27.-30. 9., aktualizované přehledy 01-08, nové přehledy 09 (postup lakování na autě) a 10 (fotky), 10 fotek a sloučený KOMPLET. Soubory v něm byly ploché (složka v názvu před dvojitým podtržítkem), protože ten chat předpokládal, že GitHub složky při ručním nahrání neuchová.
3. Plochá pojmenování ze zipu neodpovídala skutečné struktuře repozitáře (ten složky měl).
4. Ve třetím kroku (Claude Code, přímo s git) byl zip s deníkem sloučen do repozitáře se zachováním složek: soubory přejmenovány do struktury dny/DATUM/denik.md, 00-prehled/NN-*.md a fotky/, odkazy v textu přepsány na cesty se složkami, duplicity nepřidány. Verze přehledů 01-08 ze zipu měly v několika místech zkrácený nebo vypuštěný starý text, ten byl vrácen. Nepřesnosti ve starších zápisech byly opraveny (seznam v 00-prehled/06, body 20-24, a poznámky "doplněno 30. 9." v dnech 14. 9., 16. 9., sezení 2 a sezení 6). KOMPLET byl přegenerován tak, aby obsahoval všechny dny 14.-30. 9. (zip ho měl bez starších dnů).

## Stav práce na kapotě
Nepotvrzen. Poslední známý stav je z 29. 9. večer (viz 00-prehled/01 a 00-prehled/08).

## Další krok
Potvrdit, co se 29.-30. 9. udělalo (srovnání, finální plnič, broušení), pak lakování podle 00-prehled/09.
