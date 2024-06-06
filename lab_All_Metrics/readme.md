Šis kodas skirtas atstatyti praleistą duomenų reikšmę naudojant tris skirtingas metrikas: Euklido, Manhattan ir Čebyševo. Pirmiausia, vykdoma duomenų normalizacija, naudojant vidurkį ir vidutinį kvadratinį nuokrypį kiekvienam stulpeliui, kad būtų išvengta matavimo vienetų įtakos atstumo skaičiavimams.

Kodas iš esmės yra suskirstytas į kelias dalis:

Duomenų paruošimas: Nuskaitoma lentelė ir praleistos reikšmės pakeičiamos NaN (Not a Number) reikšmėmis. Vykdoma duomenų normalizacija.
Atstumo skaičiavimai: Naudojant Euklido, Manhattan ir Čebyševo metrikas, skaičiuojami atstumai tarp pasirinkto duomenų taško ir visų kitų lentelės taškų.
Duomenų atstatymas: Pagal gautus atstumus ir panaudojant svorinę vidurkio formulę, apskaičiuojamas galimas praleistos reikšmės atstatymas.
