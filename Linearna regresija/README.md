# Softver

## Matija Šelendić
## JMBAG: 1191230022

Moja tema za prvu domaću zadaću je linearna regresija.

U početku sam ukratko opisao što je to.
Počeo sam sa jednostavnom linearnom regresijom (ovisnost o jednoj varijabli) te dao primjer koristeći podatke koje sam našao na internetu. (Link je u bilježnici).
Podaci su i u .csv datoteci lokalno u repozitoriju (weight-height.csv). 

Opisao sam metodu najmanjih kvadrata te implementirao funkciju koju sam koristio za plotanje pravca na grafu na kojem su scatter-ane točke.
Plotao sam 3 grafa posebno za muškarce, žene i jedan zajednički.
Crtao sam reziduale na graf i slikom pokazao da su normalno raspodjeljeni.
Tada sam dao jedan primjer sa nelinearnom ovisnošću i pokazao kako izgleda graf sa rezidualima u tom slučaju.

Igrao sam se sa pandasom i dataframeom mijenjao podatke iz inches u cm za visinu te lbs u kg za težinu, sortirao, mijenjao na hrvatski jezik, filtrirao itd.

Nacrtao sam pie chart koji opisuje omjer visina. Logično, iz podataka zaključujem najveći postotak ljudi je visine 160-170 i 170-180.

Na kraju sam opisao multivarijantnu regresiju te dao primjer kako godine i relativna temperatura utječu na količinu ugljikovog dioksida u zraku (moglo je i obrnuto) te sam nacrtao grafove i pravac koji opisuje ovisnost.
Podaci su u .csv datotekama (year-co2.csv i year-temp.csv).

Neke od metoda koje sam koristio iz MatPlotLiba: suptitle, scatter, set_frame_on, axis, pie.
Metode koje sam koristio iz Pandasa: set_index, filter, tail, apply, sort_values.
Grafovi: Linearna regresija za visinu-težinu, reziduali, polinomijalna ovisnost, pie chart, 3D graf, 3D graf sa linearno regresijskim pravcem.
Moje metode: najmanjiKvadrati, plotaj, graf_rezidual, reziduali, normFjaGustoce.