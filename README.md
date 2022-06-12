# sda-eshop
puslapiai
  - pagrindinis - shop
    produktu sarasas (nuoroda i produkto puslapi, jo image, title, price, add buttonas)
  - produkto puslapis (produkto image, pavadinimas, aprasymas, kaina, add buttonas)
  - krepselio puslapis (panasus i produktu sarasa, bet turi rodyti amount, o ne add buttona; nuoroda i apmokejimo forma)
  - apmokejimo forma (vardas, adresas, telefonas, emailas, korteles duomenys visi su logiska validacija)

turi buti headeris
  - navigacija i reikiamus puslapius
  - krepselis su pridetu produktu kiekiu
turi buti footeris
stiliai (neskaitant defaultu ir reseto) turi buti komponentuose, rekomenduoju css modules arba styled-components
pridedami produktai saugomi localStorage
apmokant sekmingai krepselis isvalomas

optional
  - pridedant preke gauti pranesima (toast)
  - uzsakant prekes gauti pranesima (toast)
  - produkto puslapyje prideti buttonas imtu pridet norimu produktu kieki is kokio nors inputo, o ne tiesigo viena pridetu
  - krepselyje galimybe keisti produktu kieki
  - testai
