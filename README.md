# Tetris

Tein ohjelman projektina kurssille Ohjelmointi 2, jolla ohjelmointikielenä oli C++ ja ohjelmointiympäristönä Qt Creator. Tavoitteena oli toteuttaa mahdollisimman oikean Tetriksen kaltainen versio. Peli oli kurssin jälkeen nykyistä yksinkertaisempi, eikä siinä ollut esimerkiksi mahdollisuutta kääntää paloja, tai laittaa niitä säilöön. Lisäsin myöhemmin ohjelmaan ominaisuuksia, ja korjasin siinä olleita virheitä.

Olen tyytyväinen tämän hetkiseen versioon, sillä sain tehtyä pelistä toimivan. Tämä oli tavoitteenani, kun aloin täydentämään ja korjaamaan sitä. Pelistä ei myöskään puutu mitään suurempia oikeassa Tetriksessä olevia ominaisuuksia. Tulevaisuudessa peliin voisi lisätä paremman pistetaulukon, sillä nykyinen toimii vain tekstitiedostoa käyttäen. Lisäksi pelissä voitaisiin näyttää, mihin kohtaan pelilautaa nykyinen pala on putoamassa.

Pelin koodi sisältää jonkin verran toisteisuutta, mitä pystyisi vähentämään. Lisäksi luokka sisältää 18 metodia, mikä on melko paljon, ja voisi olla hyvä idea jakaa se pienempiin osiin. Metodit itsessään ovat kuitenkin mielestäni sopivan kokoisia ja sisällöltään loogisia. Ohjelmalla ei ole kunnollista dokumentointia esimerkiksi Doxygenillä tehtynä, mutta metodien tarkoitukset on kommentoitu otsikkotiedostossa.

# Ohjelman suorittaminen
Ohjelma pitäisi pystyä suorittamaan lataamalla kansio "Windeployqt_tetris" ja suorittamalla sen sisältämä tetris.exe. Kansio on luotu käyttäen Qt Creatorin Windows Deployment työkalua. Projekti on myös mahdollista avata Qt Creatorissa projektina tiedoston tetris.pro kautta.