# Työaikakirjanpito
| päivä   | aika | mitä tein                                                                              |
|--------:|:----:|:---------------------------------------------------------------------------------------|
| 25.10.  | 3    | Frontendin initialisointi, API spesifikaation aloitus                                  |
| 27.10.  | 4    | Lisää API spesifikaation työstämistä                                                   |
| 27.10.  | 4    | Backendin implementaation aloitus, pieniä korjauksia API spesifikaatioon               |
| 29.10.  | 2    | Pluginien lataukseen liittyviä korjauksia, plugin APIn implementaatiota                |
| 30.10.  | 3    | Plugin APIn implementaatio valmiiksi ja toimivuuden varmistus, kirjautumisjärjestelmä  |
| 31.10.  | 4    | Instance APIn alku, sisäinen refaktorointi asioiden käynnistysjärjestykseen            |
| 1.11.   | 1    | Pluginien live-upload+reload korjauksia, korjauksia matrix-kirjastoon                  |
| 1.11.   | 4    | Instance API valmiiksi ja lisää sisäisiä muutoksia                                     |
| 1.11.   | 2    | Client API valmiiksi                                                                   |
| 2.11.   | 1    | Echo botin avulla valmistuneiden APIen testaus ja korjaus                              |
| 2.11.   | 1    | Lisää APIn testausta ja korjausta                                                      |
| 4.11.   | 2    | UIn aloitus                                                                            |
| 6.11.   | 2    | Kirjautumisen implementointi UIssa                                                     |
| 6.11.   | 1    | Päänäkymän aloitus                                                                     |
| 7.11.   | 3    | Yläpalkki ja sivupalkki                                                                |
| 8.11.   | 1    | Uusi API endpoint tietyn pluginin päivitykseen, käyttöliittymän sivupalkkiin +-napit   |
| 8.11.   | 2    | Clienttien päänäkymän aloitus                                                          |
| 9.11.   | 6    | Clienttien päänäkymä valmiiksi                                                         |
| 10.11.  | 1    | Clienttien päänäkymän viimeistely                                                      |
| 10.11.  | 3    | Instanssien päänäkymä                                                                  |
| 10.11.  | 2    | Ulkoasun parantelua, pluginien päänäkymä                                               |
| 10.11.  | 1    | Koodin duplikaation poistamista, olemattomien polkujen käsittely, pieniä korjauksia    |
| 10.11.  | 1    | Yksinkertainen mobiilioptimointi                                                       |
| 10.11.  | 1    | Frontendin jakelu tuotannossa, dockerfilessä automaatinen kääntäminen                  |
| 11.11.  | 3    | Palvelimen logit käyttöliittymään websocketilla, mobiililla sivupalkin animaatio       |
| 26.11.  | 1    | Pieniä korjauksia frontendiin ja pluginien reloadaamiseen                              |
| **yht** | 59   |                                                                                        |


# Muu maubottiin liittyvä työaikakirjanpito
Nämä eivät varsinaisesti liity projektiin eli maubotin
hallintaohjelmointirajapintaan ja hallintakäyttöliittymään, mutta
liittyvät maubottiin muuten (esim. liitännäisten kehitys)

| päivä   | aika | mitä tein                                                                                                                         |
|--------:|:----:|:----------------------------------------------------------------------------------------------------------------------------------|
| 28.10.  | 4    | [maubot/dice](https://github.com/maubot/dice): Yhdistetty laskin ja nopanheittobotti                                              |
| 30.10.  | 1    | [maubot/media](https://github.com/maubot/media): Botti, joka vastaa sille lähetettyihin kuviin niiden kuvien `mxc://`-osoitteella |
| 1.11.   | 2    | [maubot/xkcd](https://github.com/maubot/xkcd): xkcd-botti                                                                         |
| 2.11.   | 0    | [maubot/echo](https://github.com/maubot/echo): yksinkertainen !ping ja !echo komennot sisältävä botti                             |
| 2.11.   | 1    | xkcd-botin bugien korjausta                                                                                                       |
| 26.11.  | 3    | [maubot/rss](https://github.com/maubot/rss): RSS-syötteiden seurantabotti                                                         |
| **yht** | 11   |                                                                                                                                   |


# Alkuperäisen projektin työaikakirjanpito
Projekti oli aluksi React Nativella tehty Matrix-asiakasohjelma
[Remuks](https://github.com/tulir/remuks), mutta matrix-js-sdk:n ja
react nativen outouksien takia se jäi kesken.

| päivä | aika | mitä tein                                                                                             |
|------:|:----:|:------------------------------------------------------------------------------------------------------|
| 4.9.  | 3    | repon luonti, projektin initialisointi, työympäristö, yms                                             |
| 5.9.  | 2    | React Nativen tutkimista, alustava kirjautumisnäkymä                                                  |
| 5.9.  | 2    | Flow setup, matrix-js-sdk tallennuksen tutkiminen ja implementaation aloitus                          |
| 7.9.  | 5    | Navigator, päänäkymän aloitus, tallennuksen tutkimista                                                |
| 8.9.  | 4    | Puolet tallennusimplementaatiosta, MatrixClient instanssin luominen                                   |
| 8.9.  | 1    | "Väliaikainen" logo, cryptotallennusimplementaatio ~valmiiksi, RemuksClient-luokka                    |
| 9.9   | 2    | Tallennuksen muokkaaminen monelle käyttäjälle sopivaksi, navigaatiovaihtoehtojen tutkimista           |
| 15.9. | 4    | Välimuistimahdollisuuksien tutkiminen, browser-request kirjastosta RNssä toimiva versio, login toimii |
|**yht**| 23   |                                                                                                       |

# Yhteenlaskettuna

| alue                  | aika      |
|----------------------:|:----------|
| hallintajärjestelmä   | 59 tuntia |
| muut maubot asiat     | 11 tuntia |
| alkuperäinen projekti | 23 tuntia |
| **yhteensä**          | 93 tuntia |
