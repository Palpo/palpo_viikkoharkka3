Viikkoharjoitus 3: Cloud Storage
--------------------------------

[Cloud Storage](https://cloud.google.com/storage/) on Googlen tarjoama "pilvitiedostovarasto".
Sitä voi käyttää muun muassa [Cloud Storage Clientin](https://cloud.google.com/appengine/docs/python/googlecloudstorageclient/) avulla.

Cloud Storage Clientin käyttöön voi tutustua vaikkapa [tämän esimerkin](https://cloud.google.com/appengine/docs/python/googlecloudstorageclient/getstarted) avulla.

Cloud Storage Client pitää itse [ladata](https://cloud.google.com/appengine/docs/python/googlecloudstorageclient/download) ja lisätä projektiin mukaan. Tähän projektiin se on jo lisätty kansioon `cloudstorage`.

## Tehtävä: toteuta Cloud Storage -tallennus
1. Kloonaa itsellesi tämä git-repositorio. Se sisältää App Engine web-sovelluksen, jossa voi lisätä tiedostoja Cloud Storageen. Vain itse Cloud Storage -toteutus puuttuu.
2. Toteuta tallennus Cloud Storageen.
3. Salli kaikkien lukea tallentamiasi tiedostoja asettamalla sopiva [pääsynhallinta-asetus](https://cloud.google.com/storage/docs/accesscontrol) tallentaessasi. Tällöin tiedostojen pitäisi avautua vaikkapa nettiselaimella.

* Halutessasi voit kokeilla myös [Images-palvelua](https://cloud.google.com/appengine/docs/python/images/) tekemällä tallennettavalle kuvatiedostolle jonkun hauskan muunnoksen ennen tallennusta. Siis siinä tapauksessa, että tallennettava tiedosto on tyyppiä kuva.
