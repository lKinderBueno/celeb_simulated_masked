# celeb_simulated_masked

<img src="https://github.com/lKinderBueno/celeb_simulated_masked/blob/c45c36949f8514c1b4b3b11791632b658c883eb2/CMS.png?raw=true" width="370" height="260">

Celebs Masked Simulated è un dataset contenente identità di politici e persone famose.
Nasce per colmare l'assenza di dataset utili a confrontare e classificare stesse identità, ma con mascherine diverse.

Esso è stato generato a partire dal dataset MS-CELEB-1M, dal quale sono state estratte 10.000 identità senza alcun tipo di mascherina. 
Una volta effettuata l’estrazione si è applicato Mask The Face, generando così 4 immagini con 4 tipi di mascherine diverse per identità. 

Il dataset si presenta diviso in 5 classi per identità:
(1)    Unmasked: Immagine del soggetto senza mascherina
(2)    Mask type 1: Immagine del soggetto avente una mascherina chirurgica bianca.
(3)    Mask type 2: Immagine del soggetto avente una mascherina di tessuto nera
(4)    Mask type 3: Immagine del soggetto avente una mascherina FFP2 blu
(5)    Mask type 4: Immagine del soggetto avente una mascherina di tessuto rossa
