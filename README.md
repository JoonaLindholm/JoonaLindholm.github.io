## Tämä on Bootstrap harjoittelusivu

### Etusivu / Navigaatio
•	Rakensin responsiivisen Bootstrap navigaation, jossa on hampurilaisvalikko ja toimiva collapse valikko. Aluksi valikko avautui aina väärälle puolelle näyttöä, mutta sain sen korjattua.
•	Lisäsin logon sekä erikokoiset bränditekstit pienille ja suurille näytöille, koska aluksi sivuston otsikko oli aina liian pieni isolla näytöllä.
•	Toteutin saavutettavuuden ARIA attribuuteilla ja alt teksteillä ruudunlukijoille.
•	Tein etusivulle kaksi tummasävyistä esittelyosiota containereilla, jotka kertovat sivuston sisällöstä.
•	Rakensin footerin, jossa on logo, linkit ja pieni infoteksti tekoälykuvista. Tähän keksin laittaa rajaavaan viivan, jota käytin sitten lopulta myös header navigaatio osiossa.
### Karuselli
•	Toteutin Bootstrapin carousel-komponentin, jossa on neljä kuvaa, indikaattorit kuville sekä (edellinen – seuraava) navigointinuolet.
•	Käytin d-block ja w-100 asetuksia, jotta kuvat täyttävät karusellin ja skaalautuvat oikein eri näytöillä. Kuvat myös vaihtuvat automaattisesti karusellissa.
•	Lisäsin kuville kevyen pyöristyksen (rounded) visuaalisen ilmeen parantamiseksi ja laitoin kuvakarusellin containeriin, että se oli paremmin keskitetty sivulle eikä ulottunut enää sivun reunoihin asti.
•	Tein sivulle myös esittely containerin ja pidin sivun ulkoasun samanlaisena muihin sivuihin verrattuna.
•	Navigaatio ja footer ovat yhtenevät muiden sivujen kanssa, ja sivu toimii responsiivisesti myös kapeilla näytöillä.
### Ruudukko
•	Rakensin sivulle kaksi erillistä Bootstrap ruudukkoa (row + col-12 col-md-6), jotka näyttävät kuvat päällekkäin pienillä näytöillä ja vierekkäin isommilla.
•	Käytin g-4 välitystä ja img-fluid luokkaa, jotta kuvat säilyvät responsiivisina ja ruudukko pysyy siistinä eli ruudut eivät ole toisissaan kiinni.
•	Ruudukoissa on samat kuvat yö ja päivä versioina hauskana kuva-arvoitus vertailuna.
•	Lisäksi tein otsikko ja seliteosion saman tyyliin, kuin muilla sivuilla.
•	Navigaatio, footer ja ARIA merkinnät vastaavat muiden sivujen rakennetta, jolloin kokonaisuus on saavutettava ja yhtenäinen.
### Kortit
•	Tein Bootstrapin korttiruudukon ruudukkoon, jossa näkyy neljä vuodenaikaa omilla kuvillaan ja teksteillään. Keskitin kortin sisällön keskelle korttia. Yhdistin siis ruudukko ominaisuuden ja kortti ominaisuuden.
•	Käytin responsiivista row-cols-1, row-cols-md-2, row-cols-lg-4 rakennetta, jolloin kortteja näkyy 1, 2 tai 4 vierekkäin. Nuo md ja lg mahdollistivat eri näyttökoot.
•	Laitoin kortteihin muotoiluja esim. shadow-sm, border-5, border-white, rounded ja overflow-hidden tuomaan yhtenäinen ja viimeistelty ulkoasu. Shadow ei oikein näkynyt kuitenkaan, mutta jätin sen mukaan koodiin.
•	Korttien sisällöt asetettiin pystysuuntaan d-flex ja flex-column ominaisuuksilla, jotta otsikko, kuva ja teksti pysyivät hienosti järjestyksessä.
•	Sivu alkaa erillisellä esittelyosiolla ja sisältää saman navin ja footerin kuin muut sivut, joten sivun kokonaisrakenne ja ulkoasu on yhdenmukainen muiden sivuston sivujen kanssa.
### Haitari
•	Toteutin Bootstrapin accordion komponentin eli haitarin, jossa on neljä haitariosiota (Kesä, Syksy, Talvi, Kevät). Nämä avautuvat ja sulkeutuvat collapse toiminnon avulla.
•	Käytin data-bs-parent asetusta, jotta vain yksi osio voi olla auki kerrallaan, ja lisäsin jokaiselle osiolle oman AI-kuvan ja AI tekstillä tehdyn vitsin. Laitoin haitarin niin, että kaikki osat ovat kiinni sivulle saavuttaessa.
•	Asettelin sisällön riveihin (row + col-md-4 / col-md-8), jolloin kuva ja teksti ovat vieretysten isommilla näytöillä ja päällekkäin pienillä.
•	Tein sivulle oman esittelyotsikon ja vaihdoin navissa sekä footerissa logon sivun teemaan sopivaksi.
•	Muut rakenteet (navbar, footer, tumma teema) on yhtenäistetty muun sivuston kanssa, joten sivu on responsiivinen ja saavutettava.
### Taulukko
•	Tein Bootstrapin table komponentin käyttäen table-dark, table-striped, table-hover ja align-middle  luokkia siistin ja selkeän taulukon luomiseksi. Table-dark teki taulukosta tumman, table-striped loi joka taulukon rivin eri sävyllä, table-hover loi efektin, kun hiirellä meni taulukon päälle ja align-middle keskitti taulukon.
•	Koko taulukko on table-responsive sisällä, joten se toimii oikein myös pienillä näytöillä vaakasuunnan vierityksellä.
•	Taulukossa on neljä saraketta (ominaisuus, lyhenne, esimerkki ja selitys) ja rivit on muotoiltu thead ja tbody rakenteella.
•	Käytin <code> elementtejä korostamaan luokkien ja lyhenteiden nimiä koodimuodossa, jotta taulukko toimii myös pienenä Bootstrap muistilistana.
•	Sivun toteutus noudattaa samaa rakennetta kuin muut sivut: responsiivinen navbar, tumma teema, selkeä otsikko container ja yhtenäinen footer.
### Lisäominaisuus
Tein pienen lisäominaisuuden: badgen, johon voi laittaa esimerkiksi versionumeron. Laitoin sen taulukkosivulle.

