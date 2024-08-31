# Scrum-Ohje-Tiimi3
Kuvitteellisen kehitystiimin Scrum-ohje

## Työjonot

Kaksi päätyyppistä työjonoa:
### Tuotejono (Product Backlog)
Syntyy vähitellen listaamaan mahdolliset tehtävät ja ominaisuudet tuotteelle. Tuotejono on jatkuvasti kehittyvä, järjestetty lista tarvittavista parannuksista tuotteeseen. Se on ainoa työlista, jota Scrum-tiimi käyttää. Backlogiin kuuluvat tehtävät, jotka tiimi voi suorittaa yhden Sprintin aikana, ovat valmiita valittavaksi Sprintin suunnittelussa. Näiden tehtävien tarkkuus paranee, kun niitä pilkotaan pienemmiksi ja tarkemmiksi osiksi Backlogin tarkennusvaiheessa. Tämä on jatkuva prosessi, jossa lisätään yksityiskohtia, kuten kuvaus, järjestys ja koko. Työn suorittavat kehittäjät vastaavat tehtävien koon arvioinnista, ja Tuoteomistaja voi vaikuttaa heihin auttamalla ymmärtämään eri vaihtoehtoja ja kompromisseja.

Lähde:  Scrum Guide. https://scrumguides.org/docs/scrumguide/v2020/2020-Scrum-Guide-US.pdf


### Sprintin työjono (Sprint Backlog)
Sprintin työlista, joka koostuu kohteista, jotka tiimi pyrkii toteuttamaan sprintin aikana. Sprintin työjono koostuu sprintin tavoitteesta (miksi), sprintille valituista tuotejonon tehtävistä (mitä) ja toimintasuunnitelmasta inkrementin toteuttamiseksi (miten). Se on kehittäjien itselleen tekemä suunnitelma ja tarjoaa reaaliaikaisen kuvan työstä, joka heidän on tarkoitus suorittaa sprintin aikana tavoitteen saavuttamiseksi. SSprintin työjonoa päivitetään sprintin aikana uusien oppien mukaan, ja siinä tulee olla riittävästi yksityiskohtia, jotta kehittäjät voivat seurata edistymistään.

Lähde: Scrum Guide. https://scrumguides.org/docs/scrumguide/v2020/2020-Scrum-Guide-US.pdf


### Scrum-sykli

#### Sprintti
Aikarajallinen ajanjakso, jonka sisällä tuotetaan kehitysjonon ja tehtävälistan perusteella "potentiaalisesti" valmis tuoteversio.


#### Sprintin-suunnittelupalaveri 
Suunnitellaan sprintin aikana tehty työ sekä määritellään työnjako.

#### Päiväpalaveri 
15 minuutin palaveri, jossa projektitiimi tahdittaa työn sekä laatii suunnitelman aina seuraavalle päivälle. Jokainen vuorollaan kertoo:
1. Mitä on tehnyt viimeisen 24h aikana
2. Mitä tulee tekemään seuraavan 24h aikana
3. Onko esiintynyt ongelmia

Päiväpalaverin päätavoite on optimoida työntekoa ja aina 15 minuuttia ei siihen riitä. Tällöin voidaan sopia erillinen tapaamisaika, jossa puretaan yksityiskohtaisemmin kaikki tarvittavat, esilletulleet asiat.

### Tuotteen kehitysjonon työstö
Tuotteen kehitysjonoa päivitetään aktiivisesti yhdessä tuoteomistajan kanssa, lisäämällä sinne työmääräarvioita, uusia tehtäviä sekä yksityiskohtia. Tämä on toistuva prosessi, jonka työmääräarvion päättää työntekijät (kehitystiimi) ja sisällön loppupeleissä tuoteomistaja. Kehitysjonon työstöön käytetään enintään 10% tiimin työkapasiteetista.

### Sprinttikatselmus
Jokaisen sprintin lopussa pidettävä palaveri, jossa katselmoidaan ja arvioidaan kehitettyä tuoteversiota. Tämän jälkeen muokataan tuotteen kehitysjonoa sopivaksi. Usein tuoteversiosta esitetään "demo", jonka pohjalta aletaan suunnittelemaan seuraavaa sprinttiä varten.

### Sprintin restrospektiivi
Kehitystiimin oma palaveri, jossa pohditaan mahdollisia kehityskohteita sekä suunnitelmaa toteutettaville parannuksille seuraavassa sprintissä. 


# Backlogit
Scrumissa työjonot eli backlogit auttavat tiimiä organisoimaan ja priorisoimaan tehtäviä tehokkaasti. Backlogit tarjoavat näkyvyyden projektin nykyiseen tilaan ja tuleviin tehtäviin, mahdollistaen joustavan ja ketterän reagoinnin muutoksiin.

## Product backlog
Product backlog on priorisoitu lista kaikista ominaisuuksista, parannuksista, korjauksista ja muista tehtävistä, jotka ovat tarpeen tuotteen kehittämiseksi. Se toimii projektin "toivelistana" ja on jatkuvasti kehittyvä dokumentti, joka heijastaa tuotteen nykyisiä ja tulevia tarpeita

## Sprint backlog
Sprint backlog on alijoukko Product backlogista valituista tehtävistä, jotka tiimi sitoutuu suorittamaan seuraavan sprintin aikana. Se sisältää yksityiskohtaisen suunnitelman siitä, miten jaetaan työtehtävät sprintin ajalle, ja toimii tiimin päivittäisenä työlistana.

## Definition of Done (DoD)
Definition of Done (DoD) on selkeä ja yhteisesti sovittu kriteeristö, joka määrittää, milloin tehtävä tai tuoteinkrementti on valmis. Se varmistaa, että kaikki tiimin jäsenet jakavat yhteisen ymmärryksen siitä, mitä "valmis" tarkoittaa, mikä puolestaan parantaa työn laatua ja vähentää epäselvyyksiä.

### DoD ominaisuudet
* Yhtenäisyys: Johdonmukainen kaikkien tehtävien ja sprinttien välillä, varmistaen tasalaatuisen lopputuloksen
* Selkeys: Kriteerit ovat selkeästi määriteltyjä ja helposti ymmärrettäviä kaikille tiimin jäsenille
* Mitattavuus: Valmius voidaan todentaa objektiivisesti määriteltyjen kriteerien perusteella
* Sovittavuus: DoD voidaan tarpeen mukaan päivittää ja kehittää projektin edetessä ja tiimin oppiessa

### Tyypillisiä DoD-kriteerejä voi olla esimerkiksi
* Koodi on kirjoitettu ja testattu yksikkö- ja integraatiotesteillä
* Ominaisuus on dokumentoitu asianmukaisesti
* Koodi on läpäissyt koodikatselmoinnin
* Ominaisuus on integroitu päähaaraan ja deployattu testausympäristöön.


## Miksi Scrum toimii?

Scrum-menetelmä soveltuu erittäin hyvin ohjelmistokehityksessä käytettäväksi, sillä se mahdollistaa helposti ohjelmiston jatkuvan parantamisen ja tarvittaviin muutoksiin voidaan reagoida nopeasti. Tiimin sujuva toiminta ja säännölliset palaverit varmistavat, että projekti etenee suunnitellussa aikataulussa eteenpäin. Toimintatapoja voidaan muuttaa projektin aikana ja työjonon säännöllinen läpikäynti varmistaa, että ohjelmiston kannalta tärkeimmät ja olennaisimmat toiminnallisuudet tulee tehtyä ensin.

Scrum parantaa tuotteen laatua, sillä ongelmat ja puutteet voidaan havaita ajoissa ja korjata lopulliseen tuotteeseen. Scrum-tiimin toiminta tiiviissä yhteistyössä asiakkaan kanssa edesauttaa, että asiakkaan tarpeet tunnistetaan oikein ja tuottetta kehitetään oikeaan suuntaan, jotta lopullinen tuote vastaa mahdollisimman hyvin asiakkaan tarpeita.

## Roolit Scrum-tiimissä
Lähteenä: https://scrumguides.org/docs/scrumguide/v2020/2020-Scrum-Guide-US.pdf

Tiimin kullekin jäsenelle jaetaan kuhunkin tehtävään sopivat roolit, jotta projekti etenee sujuvasti. On hyvä, että jokaisella tiimin jäsenellä on omaan osaamistasoon sopiva rooli, jossa pystyy edistämään projektia sujuvasti eteenpäin.

Scrum-perustana on pieni ja tiivis tiimi, jota kutsutaan Scrum-tiimiksi. Tiimi koostuu Scrum Masterista, tuoteomistajasta ja kehittäjistä. Scrum-tiimissä ei ole alatiimejä tai hierarkioita; se on itsenäinen, ammattilaisista koostuva yksikkö, joka keskittyy yhteen tavoitteeseen kerrallaan, Tuotteen tavoitteeseen.

Scrum-tiimit ovat monipuolisia ja itseohjautuvia. Tämä tarkoittaa, että tiimi päättää itse, kuka tekee mitä, milloin ja miten. Scrum-tiimien koko on yleensä korkeintaan 10 henkilöä, jotta tiimi pysyy ketteränä mutta kykenee suorittamaan merkittävää työtä sprintin aikana. Liian suuriksi kasvaneet tiimit tulisi jakaa useisiin tiimeihin.

### Kehittäjät (Developers)

Scrum-tiimissä kehittäjät vastaavat kaiken käyttökelpoisen inkerementin tuottamisesta jokaisessa sprinsissä. Kehittäjillä tulee olla useita taitoja, jotka vaihtelevat aina toimialan mukaan. Kehittäjät vastaavat Scrum-tiimissä aina sprintin kehitysjonosta, laadun varmistamisesta noudattamalla valmiin määritelmää, suunnitelman mukauttamisesta päivittäin Sprintin saavuttamiseksi sekä toistensa kohtelemisesta vastuullisina ammattilaisina.

### Tuoteomistaja (Product Owner)

Tuoteomistaja on aina yksi henkilö. Tuoteomistaja on vastuussa Scrum-tiimin mahdollisimman suuren arvon toteuttamisesta. Tämä vaihtelee usein käytännössä organisaation, tiimien ja yksilöiden mukaan. Tuoteomistaja huolehtii tuotteen kehitysjonon  tehokkaasta hallinnasta. Tämä sisältää tuotteen tavoitteen määrittelyn, kehitysjonon sisällön valmistelun, sisällön järjestämisen, kehitysjonon läpinäkyvyyden, saatavuuden ja ymmärrettävyyden varmistamisen sekä selkeän viestinnän. Tuoteomistaja on aina vastuussa näistä tehtävistä, vaikka voikin halutessaan myös delegoida näitä tehtäviä muille. Koko organisaation tulee kunnioittaa tuoteomistajien päätöksiä, jotta tuoteomistajat voivat menestyä.

### Scrum Master

Scrum Master vastaa Scrumin toteuttamisesta, auttaen tiimiä ja organisaatiota ymmärtämään ja soveltamaan Scrumia. Hän varmistaa tiimin tehokkuuden, edistää itseohjautuvuutta ja poistaa esteitä, samalla huolehtien, että Scrumin tapahtumat ovat tuottavia ja aikarajoissa. Tuoteomistajaa Scrum Master tukee tuotteen tavoitteen määrittelyssä, kehitysjonon hallinnassa ja sidosryhmien yhteistyössä. Organisaatiolle hän tarjoaa koulutusta ja valmennusta Scrumin käyttöönotossa sekä poistaa esteitä sidosryhmien ja tiimien välillä.
