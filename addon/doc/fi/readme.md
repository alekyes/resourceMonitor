# Resurssienvalvonta #

* Tekijät: Alex Hall, Joseph Lee, beqa gozalishvili, Tuukka Ojala sekä muut
  NVDA:n tekijät
* Lataa [vakaa versio][1]

Tämä lisäosa antaa tietoja suorittimen kuormituksesta, muistin käytöstä sekä
muista resursseista.

# Pikanäppäimet #

* NVDA+Shift+E: Lukee käytetyn RAM-muistin määrän, suorittimen
  keskimääräisen kuormituksen ja akun tiedot, mikäli sellainen on käytössä.
* NVDA+Shift+1: Lukee suorittimen ja ydinten keskimääräisen kuormituksen,
  mikäli käytössä on moniydinsuoritin.
* NVDA+Shift+2/5: Lukee sekä fyysisen että näennäisen RAM-muistin käytetyn
  ja kokonaismäärän.
* NVDA+Shift+3: Lukee kiintolevyjen ja siirrettävien asemien käytetyn ja
  kokonaistilan.
* NVDA+Shift+4: Lukee akun varauksen prosentteina, latauksen tilan, jäljellä
  olevan ajan (jos ei latauksessa) sekä varoituksen, mikäli varauksen taso
  on alhainen tai kriittinen.
* NVDA+Shift+6: Ilmoittaa suorittimen arkkitehtuurin (32- tai 64-bittinen)
  sekä Windowsin ja Service Packin version.
* NVDA+Shift+7 ilmoittaa järjestelmän käynnissäoloajan.

Voit muuttaa näitä pikanäppäimiä, mikäli käytössäsi on NVDA:n versio 2013.3
TAI uudempi.

## Huomautuksia käytöstä ##

Tämä lisäosa ei korvaa Windowsin tehtävienhallintaa tai muita
järjestelmätietoja näyttäviä ohjelmia. Huomaa lisäksi seuraavat seikat:

* Suorittimen käyttö ilmoitetaan loogisille suorittimille, ei fyysisille
  ytimille. Tällä on merkitystä Hyper Threading -teknologiaa käyttävissä
  suorittimissa, joissa suorittimien määrä on kaksi kertaa ydinten määrä.
* Levynkäyttötietoja haettaessa saattaa olla viivettä, mikäli levytoimintaa,
  kuten suurten tiedostojen kopiointia, on runsaasti.
* Tämän lisäosan Windows XP -tuki päättyy 31. joulukuuta 2017. Windows
  Server 2003:n ja Windows Vistan tuki päättyy 30. kesäkuuta 2018.

## Versio 17.09

Tärkeää: 17.09.x on viimeinen Windows XP:tä tukeva versio.

* Viimeinen Windows XP:ssä ajettava versio.
* Windows 10:n koontiversio 16278 ja uudemmat tunnistetaan versioksi
  1709. Tästä lisäosasta julkaistaan pieni päivitys, kun version 1709 vakaa
  koontiversio on julkistettu.

## Versio 17.07.1

* Palautettu Windows XP:n tuki (ollut rikki versiosta 17.02 lähtien).

## Versio 17.05

* Järjestelmän käynnissäoloajan ilmoittaminen (edellisestä käynnistyksestä
  kulunut aika; NVDA+Shift+7).

## Versio 17.02

* Päivitetty psutil-riippuvuus versioksi 5.0.1.
* NVDA ei näytä enää virheilmoitusta levynkäyttötietoja tarkistettaessa
  järjestelmissä, joissa siirrettävää tietovälinettä ei tunnistettu oikein
  (esim. kun muistikorttia ei ole asetettu kortinlukijaan).

## Versio 16.08

Lisäosan versionumerot ovat Versiosta 16.08 alkaen muotoa
vuosi.kuukausi.tarkistusversio.

* Windows 10:n eri versiot tunnistetaan nyt oikein (kuten 1607
  koontiversiossa 14393).
* Windows 10:n koontiversiot tunnistetaan oikein kumulatiivisten päivitysten
  asentamisen jälkeen (kuten 14393.51).
* Insider-esiversiot tunnistetaan oikein.

## Muutokset versiossa 4.5 ##

* Lisäosan koodivarasto on muuttanut GitHubiin (löytyy osoitteesta
  https://github.com/josephsl/resourcemonitor).
* Windows Server 2016 tunnistetaan asianmukaisesti.

## Muutokset versiossa 4.0 ##

* Päivitetty psutil-riippuvuus versioksi 2.2.1.
* Suorituskykyä paranneltu huomattavasti suorittimen kuormituksen tietoja
  haettaessa.
* Lisätty tuki Windows 10:n tunnistamiselle.
* Windows 10:n versiota ilmoitettaessa kerrotaan myös koontiversio.
* Ohje on käytettävissä Lisäosien hallinnasta.

## Muutokset versiossa 3.1 ##

* Resurssienvalvonta tukee virallisesti Windows 8.1:tä.
* Käännöksiä päivitetty.

## Muutokset versiossa 3.0 ##

* Päivitetty psutil-riippuvuus versioksi 1.2.1.
* Suorittimen arkkitehtuurin sekä Windowsin ja Service Packin version
  ilmoittaminen (NVDA+Shift+6).
* Mahdollisuus vaihtaa lisäosan pikanäppäimiä (NVDA:n 2013.3-versiossa tai
  uudemmassa).
* Mahdollisuus kopioida yksittäisen resurssin tiedot leikepöydälle
  painamalla komentoja kahdesti.

## Muutokset versiossa 2.4 ##

* Uusia kieliä: kiina (yksinkertaistettu), ukraina
* Käännöksiä päivitetty.

## Muutokset versiossa 2.3 ##

* Lisätty bulgariankielinen käännös.

## Muutokset versiossa 2.2 ##

* Lisätty seuraavat käännökset: arabia, aragonia, brasilianportugali,
  espanja, galego, hollanti, italia, japani, korea, kroatia, nepali, puola,
  ranska, saksa, slovakki, slovenia, suomi, tamili, turkki, unkari ja
  venäjä.

## Muutokset versiossa 2.1 ##

* Päivitetty psutil-riippuvuus versioksi 0.6.1.
* Korjattu pitkä viive asemien tietoja haettaessa.
* Koodia siivottu.

## Muutokset versiossa 2.0 ##

* Lisätty käännösten tuki ja käännöskommentteja.

## Muutokset versiossa 1.0 ##

* Ensimmäinen versio

[[!tag dev stable]]

[1]: https://addons.nvda-project.org/files/get.php?file=rm
