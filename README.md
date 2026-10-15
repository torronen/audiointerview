# audiointerview

## Kehitysympäristö ja käynnistys

Historiallinen linkkirepo; ei asennettavaa tai käynnistettävää haastattelusovellusta.

Tämän repon lukeminen ei tarvitse SDK:ta, npm-paketteja tai palvelutunnuksia. Varsinainen sovellus asennetaan
ja käynnistetään `efiapps/interview-sim`-repon README:n mukaan; puhe-/analyysikirjasto on
`torronen/audiogen`. Molempien lokakuun ylläpitomuutokset on yhdistetty niiden main-haaroihin. Mainiin
pushattu lähdekoodi ei tarkoita tuotantoasennusta tai palvelutunnusten saatavuutta.

Asennusohje kuvaa paikallisen kehityspolun. Ulkoisen palvelun, oikean sähköpostitoimituksen tai
tuotantoympäristön toimivuutta ei ole varmennettu tällä dokumentaatiopäivityksellä.

Tämä repo on alkuperäinen paikkamerkki äänihaastattelun idealle. Se sisältää
README-tiedoston ja Git-asetuksen; tässä repossa ei ole ajettavaa haastattelusovellusta.

Varsinainen toteutus on [efiapps/interview-sim](https://github.com/efiapps/interview-sim).
Se sisältää haastattelutehtävät, hakijan suoritukset ja itsearvioinnin sekä
rekrytoijan palautteen. Puheproviderit ja analyysikirjasto ovat erillisessä
[torronen/audiogen](https://github.com/torronen/audiogen)-repossa.

Lokakuun 2026 puhe-, analyysi- ja bonuskeskustelulisäykset on yhdistetty
[interview-simin main-haaraan](https://github.com/efiapps/interview-sim/tree/main).
Ne eivät tämän kuvauksen perusteella ole tuotantoon asennettuja. Avaimeton demo
ja tekstikäyttö säilyvät; oikea puhe- ja malliyhteys tarvitsee palvelimelle asetukset.
Käynnistys, konfiguraatio, testaus ja tunnetut rajat kuvataan toteutusrepon READMEssa.

Tätä repoa säilytetään vanhojen linkkien vuoksi. Uusi sovelluskoodi ja korjaukset
tehdään yllä oleviin toteutusrepoihin.

## Testidata ja seedaus

**Nykyinen menetelmä:** Ei ajettavaa sovellusta tai seedattavaa kantaa tässä repossa.

Haastattelun testidata luodaan efiapps/interview-simin DEMO.md:n nykyisellä paikallisella seed-endpointilla.
Puhe-/tapahtumafixuret ovat torronen/audiogen-repossa. Tähän linkkirepoon ei asenneta toista seed- tai
tietokantatoteutusta.

**Varmista tulos ja uusinta:** Varmista linkit toteutusrepojen main-versioon. Niissä syntyneen demon
toimivuutta ei päätellä tästä hakemistosta.

**Jatkoidea (ei toteutettu tässä työssä):** Jos demon kattavuutta laajennetaan, lisää skenaario toteutusrepon
olemassa olevaan seed- tai fixture-rakenteeseen ja pidä täällä vain linkki.
