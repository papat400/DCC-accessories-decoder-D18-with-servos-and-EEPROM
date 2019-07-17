# DCC-accessories-decoder-D18-with-servos-and-EEPROM
ENGLISH :
-------

Based on Ulysse's D18 decoder, allows to use servos direcly from a Nano
.
Quote from the Ulysse's original project (his file readme.md) :

  The D18 is a DIY DCC Accessories decoder based on Arduino board.

  At the moment, main site and documenation is in French.
  http://udelmas.e-monsite.com/pages/decodeur-d18.html

  I created this github to easyly share the Arduino source code
  (d18_acc_decoder.ino)

end of quote.
.
Original project is available here : https://github.com/ullysse/d18

My own adaptations are :

1) Using directly some outputs of the arduino to pilot up to 16 servos (max. 12 servos) and/or digital outputs.

2) Keep a backup of the last servos Set Point and digital outputs state in EEPROM memory. This is used to retrieve positions when the arduino is turned off and on again later.
The eeprom is only adapted when a state changes. This allows at least 100,000 changes per servo or binary output, which is more than enough!

If you use and share this project, please mention Ulysse, the creator of this project.

Note : I add an Eagle zip file for the D18 PCB design (made for an arduino NANO).
.
.
FRANCAIS :
--------

D'après le décodeur d'accessoires D18 d'Ulysse, cette version permet de gérer des servos directement depuis l'arduino.
.
Citation, d'après le fichier readme.md d'Ulysse :

  Le D18 est un décodeur d'accessoires DCC à faire soi-même avec une carte Arduino

  Lien vers le site principal et la documentation:
  http://udelmas.e-monsite.com/pages/decodeur-d18.html

  J'ai créé ce github pour facilement partager le code source de l'Arduino
  (d18_acc_decoder.ino)

Fin de citation.
.
Le projet original est disponible ici : https://github.com/ullysse/d18

Mes adaptations sont :

1) Utiliser directement des sorties de l'arduino pour gérer jusqu'à 16 servos (max. 12 servos) et/ou sorties "tout ou rien" (binaires).

2) Effectuer un backup des position "en cours" des servos et des sorties binaires dans l'EEPROM de l'arduino. Ceci permet de récupérer les positions après coupure et réalimentation de l'arduino.
L'EEPROM n'est mise à jour que lors d'un changement d'état de la sortie. Ceci permet au moins 100000 commutations par sortie, ce qui est amplement suffisant !

If you use and share this project, please mention Ulysse, the creator of this project.
Si vous utilisez et partagez ce projet, merci de mentionner le créateur initial : Ulysse.

Note : j'ai ajouté un fichier zip Eagle pour le PCB du D18 (pour un arduino NANO).


Thierry.
