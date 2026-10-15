# AGENTS.md

## Paikallinen kehitys ja agentin aloitus

Asenna riippuvuudet ja käynnistä oikea osaprojekti
[README:n käynnistysohjeella](README.md#kehitysympäristö-ja-käynnistys). Siinä erotetaan paikallinen demo,
offline-tarkistus ja ulkoisia palveluja tarvitseva käyttö. Käytä kyseisen työpuun lukitustiedostoja ja
työkaluversion valintaa; älä kopioi toisen koneen virtuaaliympäristöä asennukseksi. Pelkkää
dokumentaatiomuutosta varten tarkista muuttuneet polut, komennot, linkit ja `git diff --check`; älä aja
lähettäviä tai dataa muuttavia prosesseja smoke-testinä. Koodimuutoksissa noudata lisäksi tämän repon
varsinaisia testausohjeita.

Pidä tämä repo osoittimena oikeisiin toteutuksiin. Älä lisää rinnakkaista haastattelusovellusta tai kopioi
muiden repoiden käynnistyskomentoja tänne paikallisesti ajettavina.

## Testidatan valmistelu

Katso [README:n testidata- ja seedausohje](README.md#testidata-ja-seedaus) ennen demo-/testiajon valmistelua.
Ei ajettavaa sovellusta tai seedattavaa kantaa tässä repossa. Valmiin menetelmän, testifixturen ja jatkoidean
tila on erotettu ohjeessa. Älä keksi toimivaa seed-komentoa tai oleta uusintaa idempotentiksi. Tarkista
kohde, käyttäjä-/tenant-raja ja nykyisen menetelmän kirjoitus-/poistovaikutus; käytä nimettyä testikohdetta.
Synteettisen datan onnistuminen ei todenna live-integraatiota. Tässä ohjepäivityksessä seedausta ei ajettu.
