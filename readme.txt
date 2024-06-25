Program umoznuje zadat riadiace vrcholy prostrednictvom klikania mysi do vykreslovacej plochy.
Prvy segment sa vykresli po zadani dvoch riadiacich vrcholov.
Kazdy dalsi segment sa vykresli po zadani prislusneho riadiaceho vrchola.
Hranicna podmienka je prirodzeny splajn.
Kazdy segment sa vykresluje inou farbou.
Krivka sa pri zmene riadiacich vrcholov prekresluje pocas tahania mysou.
Pocet LOD je 42.
Stlacenim tlacidla reset sa splajn vymaze a mozno kreslit znova.

Na vypocet vektorov z riadiacich bodov som pouzila class Matrix:
http://www.ivank.net/blogspot/matrix_cs/Matrix.cs