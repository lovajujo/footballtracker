Üdv a Match Tracker Pro használati útmutatójában! ⚽📊


Ez a program egy könnyen kezelhető mérkőzéselemző szoftver, amely közvetlenül a webböngésződben fut. Nincs szükség telepítésre, regisztrációra és mivel az adatok a saját gépeden tárolódnak, akár internetkapcsolat nélkül, a pálya szélén is hibátlanul működik.


Ez az útmutató lépésről lépésre bemutatja, hogyan hozhatod ki a legtöbbet a programból.


1. Első lépések: A Főmenü és a Modulok
Amikor megnyitod a programot, a főmenü fogad, ahol kiválaszthatod, hogy milyen típusú adatokat szeretnél rögzíteni. 


⚽ Alap statisztika (Field Tilt): A klasszikus meccsesemények rögzítésére szolgál (Kapura lövés, Gól, Szöglet, Támadó harmadba adott passz, Les, Falt).


📊 Labdabirtoklás (PPDA): Speciális modul a letámadás hatékonyságának (PPDA) és a tiszta labdabirtoklási időnek a mérésére. Itt a csapatok sikeres passzait és a megszakítás nélküli passz-szekvenciákat tudod számolni.


⚙️ Egyedi Kódoló Panel: Ha a fenti kettő nem elég, itt te magad hozhatsz létre saját gombokat (pl. letámadás, labdakihozatal, átmenet).


2. A Két Fő Üzemmód: ÉLŐ vs. UTÓLAGOS
Bármelyik modulba lépsz be, legfelül ki kell választanod, hogyan dolgozol. Figyelem: A két mód közötti váltás törli az addig rögzített adatokat az adott modulban, ezért ezt mindig a munka legelején állítsd be! (Tipp: ha élőről utólagosra váltanál, mentsd le a projektet (lásd később), majd töltsd vissza.)


🔴 ÉLŐ Mód (Meccs közben a pálya szélén)


Az óra a számítógéped/tableted belső idejéhez igazodik. Ha elindítod, nem lehet megállítani (hiszen a valós meccs sem áll meg).


Ideális arra, hogy a lelátóról vagy a kispadról kódold az eseményeket.


🎬 UTÓLAGOS Mód (Videóelemzés otthon)


Megjelennek a videószinkronizációs beállítások (Videó URL, sebesség, tekerés).


Az órát bármikor megállíthatod, gyorsíthatod a lejátszási sebességet (pl. 1.5x) és ugrálhatsz az időben (-5 mp / +5 mp).


A nagy óra ilyenkor a videólejátszó idejét mutatja, nem a meccsidőt, így sokkal könnyebb szinkronban maradni a felvétellel.


3. Hogyan kódolj le egy mérkőzést? (Lépésről lépésre)
A) A mérkőzés elindítása
Lépj be a választott modulba, válaszd ki a módot (Élő vagy Utólagos).


Nyomd meg a zöld START gombot (vagy a Szóköz billentyűt). Az óra elindul.


Ha egy esemény történik a pályán, kattints a megfelelő gombra, vagy nyomd meg a gomb melletti betűt a billentyűzeten (pl. 'Q' a Hazai kapura lövéshez).


A képernyő alján lévő "Legutóbbi események" naplóban azonnal megjelenik a rögzített adat a pontos időbélyeggel.


B) Félidő és meccs vége
Amikor a bíró lefújja az első félidőt, Élő módban hagyd futni az órát.


Amikor elkezdődik a második játékrész, nyomd meg a fehér MÁSODIK FÉLIDŐ START (45:00) gombot. Az óra automatikusan 45:00-ra ugrik és onnan számol tovább.


A meccs végén nyomd meg a MECCS VÉGE gombot az adatok letöltéséhez.


C) Hibáztál? Semmi gond!
Ha véletlenül rossz gombot nyomtál meg, csak kattints a piros ↩ VISSZAVONÁS (Z) gombra (vagy nyomd meg a Z betűt a billentyűzeten). Ez azonnal törli a legutolsó eseményt, valamint utólagos módban visszaállítja az órát a törölt esemény időpontjába. Akár a "Második félidő" elindítását is visszavonhatod vele!


4. A PPDA modul használata
A PPDA (Passes Per Defensive Action) modul picit máshogy működik, mint a többi, mivel itt a labda folyamatos birtoklását figyeljük.


Birtoklás beállítása (1, 2, 3 gombok): Mindig jelezned kell, kinél van a labda (Hazai, Kint, vagy Vendég). Kattints a dobozokra, vagy használd a számokat a billentyűzeten.


Passzok számolása (Q, E gombok): Minden sikeres passznál nyomd meg a gombot. A rendszer automatikusan számolja a szekvencia hosszát (hogy hány passz ment zsinórban).


Szekvencia vége (A, D gombok): Ha a csapat elveszti a labdát (vagy kimegy), zárd le a szekvenciát.


Tipp: A program okos. Ha a labda "Kint" van, de te megnyomod a Hazai passz (Q) gombot, automatikusan a hazaikhoz adja a birtoklást, nem kell külön átállítanod! Ugyanez igaz a passzokra is: ha birtoklás váltás történik, akkor automatikus lezárja a rendszer a legutóbbi szekvenciát, így a szekvencia vége gombot nem is kell használnod.
Példa: passzolt hármat a hazai csapat, majd a vendég csapat megszerezte a labdát. Ekkor elég a vendég birtoklásra kattintanod, ezzel a hazai passz szekvencia is lezárul.


5. Projekt Mentése és Betöltése (A munka folytatása)
Nem tudod egy ültő helyedben befejezni a meccset? Vagy a pályán elkezdted, de videóról fejeznéd be?


Mentés: A modul tetején lévő 💾 Projekt mentése gombbal letölthetsz egy .json fájlt. Ez tartalmazza az addigi összes eseményt és az óra állását.


Betöltés: Később nyisd meg a programot, lépj be ugyanabba a modulba és nyomd meg a 📂 Betöltés gombot. Válaszd ki a .json fájlt és már folytathatod is a korábban elkezdett elemzést.


Fontos: A betöltött projektek automatikusan Utólagos módban nyílnak meg, az óra pedig megállítva várja, hogy beállítsd a videót és folytasd a munkát!


6. Videó Szinkronizáció 
Utólagos módban egy teljes értékű videóelemző rendszert kapsz:


Másold be a meccs YouTube linkjét a Videó URL mezőbe.


Keresd meg a videón, mikor indul az 1. félidő (pl. a videó 3. percében). Írd be a 1. félidő videó start dobozba, hogy 03:00. (Tedd meg ugyanezt a 2. félidővel is).


A nagy óra mostantól a videó idejét mutatja. Ha rákattintasz a nagy órára, kézzel is beírhatsz egy időt (pl. 12:45), ahová ugrani szeretnél. Fontos, hogy mindig perc:másodpercben add meg (pl. 1:12:12-t 72:12-nek kell megadni)!


Ha menet közben jössz rá, hogy a videó csúszik 5 másodpercet, csak írd át a Start időt felül. A program visszamenőleg az összes eddigi eseményed időbélyegét automatikusan kijavítja!


7. Exportálás (A Letöltött Adatok)
A képernyő alján lévő 💾 ADATOK LETÖLTÉSE (CSV) gombbal exportálhatod a munkádat Excelbe, Power BI-ba vagy más táblázatkezelőbe. Két formátum közül választhatsz:


Original (egyszerűsített): egy tiszta lista, az eredeti Tamás féle verzió.


Advanced (részletes): ha megadtál videó URL-t, a táblázat legutolsó oszlopában minden eseményhez generálódik egy kattintható YouTube link. Csak rákattintasz Excelben, és a videó hajszálpontosan a lövésnél vagy a passznál fog elindulni!


8. Biztonság


A program úgy lett megtervezve, hogy minimális esély legyen az adatvesztésre. Semmi probléma, ha véletlenül bezárod a böngészőt/újratöltöd az oldalt/vissza gombot nyomsz/lezárod a telefonodat, a munkád addig nem fog elveszni, amíg nem nyomsz rá a RESET gombra vagy váltasz élő és utólagos mód között.


TIPP: figyelj a felugró figyelmeztetésekre és akkor nem lesz gond! (Lehet idegesítő lesz a sok figyelmeztetés, de fő a biztonság)


⌨️ Gyorsbillentyűk Összegzése
Szóköz: Start / Szünet (Óra indítása, megállítása)


Z: Visszavonás (Undo) az utolsó esemény törlése.


Balra / Jobbra nyíl: Vissza/Előre tekerés 5 másodperccel (csak Utólagos módban).


Field Tilt modul:


Q / U: Kapura lövés (Hazai / Vendég)


W / I: Gól (Hazai / Vendég)


E / O: Szöglet (Hazai / Vendég)


A / J: Támadó harmadba passz (Hazai / Vendég)


S / K: Les (Hazai / Vendég)


D / L: Falt (Hazai / Vendég)


Jó elemzést és sikeres meccseket!


Kérdés, kérés, probléma esetén keresd Zsuzsót messengeren, telefonon vagy lovaszi.zsuzsanna@gmail.com email címen!