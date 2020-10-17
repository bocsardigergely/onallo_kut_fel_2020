# Önálló Kutatási Feladat 2020

Ez a repo szolgál a projektben használt minden adat és source kultúrált tárolására.

## Vízió, a terv

A projektünk célja az Egyesült Államok elnökének twitter bejegyzéseinek segítségével a tőzsdei trendek előrejelzése (vagy legalábbis ennek megkísérlése). A koncepció az egyes twitter bejegyzésekben a szavak előfordulásának összefüggését vizsgálni a new york-i tőzsde ingadozásaival. 
A célunk az, hogy releváns képet alkossunk arról, hogy mely szavak megjelenése után lehet csökkenésre, mely szavak (akár együttes megjelenése) után lehet visszaesésre számítani. 

## Preprocessing

Az adatainkat a Kaggle.com-ról szereztük be, három datasettel dolgozunk. Az első a tőzsdei árakat tartalmazza, a másik kettő pedig Barack Obama és Donald Trump twitterjének scrapelt verziói. A két elnök hivatott kiegyensúlyozni a demokrata/republikánus eltéréseket, hogy az a jósolt adatban is minimálisra legyen csökkentve.
A preproc fő lépései a következőek lesznek:
* a twitter bejegyzéseket szavak előfordulására formálni, és elhagyni belőle a kötőszavakat, vagy egyéb redundáns információkat.
* a tőzsdei adatokból a lehető legkrövidebb, még kezelhető intervallumokra trendeket leírni (növekedés/csökkenés az intervallumon)
* kiválogatni, hogy mindkét elnök office periódusaira nagyjából hasonló mennyiségű entry jusson (a republikánus/demokrata pártpolitikai torzítást tovább csökkentendő)

## Előrejelzés

Mivel egy bináris osztályozási feladatot állítunk fel (növekedés = 1, visszaesés = 0), így elsősorban a kNN és a döntési fa algoritmusokat fogjuk kipróbálni, más-más paraméterezésekkel. A vizualizáció részében látványos lesz, hiszen, ha minden jól megy, a jósolt adatok alapján két szófelhőben ábrázolhatjuk a növekedést és a visszaesést "okozó" szavakat.


2020 - Bevezetés az adattudományba 1 - Asztalos András - Bocsárdi Gergely
