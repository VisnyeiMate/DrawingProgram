# Snake Case VS Camel Case VS Pascal Case VS Kebab Case

## Case-ek amiket használunk:
### Snake case
### Kebab case
### Camel case
### Pascal case

## Snake case

    Minden szó között használunk egy _ jelet.
    pl: pelda_erre_asd

    Változók illetve metódusok elnevezésére használjuk leginkább, de hasznos lehet a fájlok elnevezésére is.
    Adatbázisban is a tábla és oszlop nevekre is használható.

    Lehet full capsel is használni
    pl: PELDA_ERRE_ASD

## Kebab case
    Nagyon hasonlít a snake case-hoz, annyi a különbség, hogy nem (_) van hanem (-)-et használunk.
    pl: pelda-erre-asd


## Camel case

    Az első szó kis betűvel kezdődik a többi pedig nagy betűvel és egybe.
    pl: peldaErreAsd

    Használható, függvény nevekre, változó nevekre és metódusok neveire is.

## Pascal case

    Hasonlít a camel case-ra annyi különbség van, hogy itt az első szó kezdőbetűje is nagy.
    pl: PeldaErreAsd




# Mi az a Clean Code és hogyan használjuk?

## Elnevezés

    Fontos, hogy az elnevezések mindig egyértelműek legyenek, és ne tévesszen meg. Mindig egy dolgot jelentsen, hogy ne zavarjon meg.

## Kommentelés
     
    Hogy ha az elnevezések jók, akkor általában nincs szükség kommentelésre. Komment hasznos lehet ha valami információt learakunk írni, amit a későbbikben elfelejthetünk illetve feladatok szempontjait lehet még leírni. A túl sok kommentelés van egy kódban az nem nevezhető "Clean" kódnak.

## Szerkezeti tagolás

    A kódot felkell bontani programegységekre ahhoz, hogy könnyen értelmezhető illetve átlátható legyen. Fontos, hogy melyik utasítás melyik után következik fentről-lefelé.

## Whitespace

    A whitespace könnyebben átláthatóvá teszi a kódot, még ott is alkalmazható ahol a fájlméret egy szempont.

## Mire gondolt a költő?

    Ha nem átlátható a kódod, illetve az elnevezésekre sem figyelsz oda, akkor könnyen bele eshetsz abba a hibába, hogy mire befejeznénk a programot, az elején megkell változtatni valamit. A leghatásosabb mód, hogy igéket használunk a függvények elnevézésénél, vagy utasításoknál.

## Töröld, ami nem fontos

    Fontos, hogy olyan funkció ne kerüljön a kódba amit nem kel használni. Fokozatosan kis lépésekkel haladva kell felépíteni a kódot, így nem kerül bele felesleges funkció.

## Ne ismételd magad

    Ha van a kódban duplikált kódsor, akkor az nem csak nehezebben átláthatóvá teszi a kódot, hanem hibába is ütközhet az egész.

## Logikus funkcionitás

    A hosszú függvénydefiniciók nem előnyősek, megkell keresni a felesleges sorokat, és azt át lehet írni egy másik függvénybe. Az utasításokat úgy kell megírni, hogy csak azt csinálja amire te meg írtad, mást nem. Rövid soros függvényeket érdemes írni.

## Mágikus értékek

    Vannak olyan értékek amik "varázslatos" módon kerültek be a kódba, jelentésüket nem tudják megmondani, hogy mi, mert vagy számok vagy stringek.

## Újrafelhasználhatóság

    Az objektum orientált programozási nyelvek egyik legjobb tulajdonsága, hogy könnyen újralehet használni a kódot. Egy funkciót ha már megírtunk akkor azt fel lehet használni több helyen is.


## A tiszta kód előnyei

### Egyszerű módosításokat lehet végezni
### Kevesebb hiba
### Kevesebb kód



