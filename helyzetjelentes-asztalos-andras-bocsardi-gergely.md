# Önálló kutatási feladat 2020

## Helyzetjelentés

### Adatok

A projekt minden adatát begyűjtöttük, ezek a [GitHub repository-ban](https://github.com/bocsardigergely/onallo_kut_fel_2020) érhetőek el, itt vannak az Obama tweetek és a Trump tweetek, elég széles időintervallumból, hogy a hivatalban töltött idejükből tudjunk nagyjából egyforma szeletekben mintát venni. A tőzsde állapotát pedig egy index fund, névlegesen az S&P500 részvényekkel fogjuk követni, hiszen ez az 500 legnagyobb cég részvényeiből épül fel, így jó mutatója a piacnak. Felmerült, hogy kiterjesszük további tőzsdei termékekre is (főként az olajra), de arra juttotunk, hogy azt meghagyjuk egy potenciális további kutatás alanyának, hiszen a fő feladat itt úgyis a Natural Language Processing aspektus lesz.

### Feldolgozás

Az előbb említett Natural Language Processing eljárásokat kell behatóbban tanulmányoznunk, már van néhány cikk, ami releváns lehet a számunkra. Nagyban megkönnyíti a dolgunkat hogy tanulunk neurális hálókról, szóval az az oldal legalább kicsit tisztább, inkább a pontos implementáció lesz az időigényes. Az egyik irány amivel szemezünk az a "sentiment analysis", amivel a pozitív-negatív-neutrális tweeteket tudnánk clusterezni, amikben ezután az egyes szavak term frequency vagy idf értékeivel tudnánk kinyerni a nagyobb hatású szavakat.

## További lépések

A fő csapásirány tehát a NPL megismerése behatóbban, ezzel kisebb lépésekben próbálkozni, kitapasztalni az egyes library-k sajátosságait, előnyeit-hátrányait.

*Asztalos András és Bocsárdi Gergely, 2020.11.01*