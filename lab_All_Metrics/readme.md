Šis kodas skirtas atstatyti praleistą duomenų reikšmę naudojant tris skirtingas metrikas: Euklido, Manhattan ir Čebyševo. Pirmiausia, vykdoma duomenų normalizacija, naudojant vidurkį ir vidutinį kvadratinį nuokrypį kiekvienam stulpeliui, kad būtų išvengta matavimo vienetų įtakos atstumo skaičiavimams.

Kodas iš esmės yra suskirstytas į kelias dalis:

Duomenų paruošimas: Nuskaitoma lentelė ir praleistos reikšmės pakeičiamos NaN (Not a Number) reikšmėmis. Vykdoma duomenų normalizacija.
Atstumo skaičiavimai: Naudojant Euklido, Manhattan ir Čebyševo metrikas, skaičiuojami atstumai tarp pasirinkto duomenų taško ir visų kitų lentelės taškų.
Duomenų atstatymas: Pagal gautus atstumus ir panaudojant svorinę vidurkio formulę, apskaičiuojamas galimas praleistos reikšmės atstatymas.


Euklido atstumas (distance.euclidean): tai tiesiausias atstumas tarp dviejų taškų daugiamačiame erdviniame kontekste. Eilutėje skaičiuojamas Euklido atstumas tarp pasirinkto vartotojo (indeksas 4) ir visų kitų vartotojų lyties bei svorio normalizuotų reikšmių.

Manhattan atstumas (distance.cityblock): taip pat žinomas kaip „Manhattan length“ arba „city block distance“. Tai yra atstumų suma tarp taškų kiekvienoje ašyje. Šis atstumas naudingas tada, kai atstumai matuojami diskretiškai, pavyzdžiui, eismą reguliuojant miesto gatvėse.

Čebyševo atstumas (distance.chebyshev): tai yra didžiausias vienos ašies atstumas tarp dviejų taškų. Ši metrika yra naudinga scenarijuose, kur svarbiausia yra maksimali reikšmė.
