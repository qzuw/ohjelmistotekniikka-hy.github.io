---
layout: page
permalink: /
---
### Yleistä

_Kurssin nimi on muuttunut syksyllä 2018, tätä aiemmin kurssi tunnettiin nimellä Ohjelmistotekniikan menetelmät_

Kurssilla tutustutaan ohjelmistokehityksen periaatteisiin sekä menetelmiin ja sovelletaan niitä toteuttamalla pienehkö harjoitustyö.

Kurssin kolmella ensimmäisellä viikolla on muutama ohjauksessa tai omatoimisesti tehtävä harjoitustehtävä. Kurssin pääpainon muodostaa viikolla 2 aloitettava, itsenäisesti tehtävä harjoitustyö. Työtä on tarkoitus edistää pala palalta [viikoittaisten](#aikataulu) tavoitteiden ohjaamana.

Kurssin arvostelu perustuu pääasiassa harjoitustyöstä saataviin pisteisiin. Osa pisteistä kertyy [aikatauluun](#aikataulu) määriteltyjen viikoittaisten välitavoitteiden kautta, osa taas perustuu työn lopulliseen palautukseen.

Kurssilla ei ole koetta. Harjoitustyö tulee tehdä kurssin aikataulujen puitteissa. Kesken jäänyttä harjoitustyötä ei voi jatkaa seuraavalla kurssilla (syksyllä 2021), joten **muista varata riittävästi aikaa (10-15h viikossa) koko periodin ajaksi!**

Tarkemmat arvosteluperusteet [täällä](./web/arvosteluperusteet.md).

### Kirjoitusvirheitä

Jos huomaat tehtävissä tai muussa materiaalissa kirjoitusvirheitä, kirjaudu GitHubiin ja toimi [täällä](./web/typokorjaukset.md) olevan ohjeen mukaan.

### Kieli

Voit tehdä kurssin Javalla tai Pythonilla. Tämä on molempien kielten kurssisivu.

{% include ajankohtaista.md %}

{% include harjoitustyon_toimivuus.md %}

### Aikataulu

#### viikko 1

Palautuksen deadline ti {{ site.wk1dl }}. klo 23:59

- Tiistaina 16.03. klo 12-14 aloitustilaisuus [tallenne](https://youtu.be/JaM4hbns2P8)
- Komentorivi- ja Git-harjoittelu (2p)
  - Pajassa tehtävät tai omatoimiset tehtävät [Java](/java/viikko1) [Python](/python/viikko1)
- Tehtävien palautus tapahtuu tekemällä repositorio githubiin ja rekisteröitymällä labtooliin

#### viikko 2

Palautuksen deadline ti {{ site.wk2dl }}. klo 23:59

- Harjoitustyön aiheen alustava määrittelydokumentti (1p)
  - katso tarkemmin [Java](/java/ht-viikko2) [Python](/python/ht-viikko2)
- JUnit/Unittest-harjoittelu (2p)
  - Pajassa tehtävät tai omatoimiset tehtävät [Java](/java/viikko2) [Python](/python/viikko2)
- Oman projektin koodaus alkaa

#### viikko 3

Palautuksen deadline ti {{ site.wk3dl }}. klo 23:59

- Harjoitustyön koodin runko valmiina (2p)
  - katso tarkemmin [Java](/java/ht-viikko3) [Python](/python/ht-viikko3)
- Pajassa tehtävät tai omatoimiset tehtävät luokka- ja sekvenssikaaviosta [Java](/java/viikko3) [Python](/python/viikko3) (1p)

#### viikko 4

Palautuksen deadline ti {{ site.wk4dl }}. klo 23:59

- Harjoitustyö (3p)
  - Ohjelman perustoiminnallisuus
  - Testien aloitus
  - Alustava rakenne luokkakaaviona
  - Checkstyle/Pylint otettu käyttöön
- Tarkemmat ohjeet [täältä](/tehtavat/harjoitustyo_viikko4.md)

#### viikko 5

Palautuksen deadline ti {{ site.wk5dl }}. klo 23:59

- Harjoitustyö (3p)
  - Release 1
  - Testikattavuus nousee
  - Jotain päätoiminnallisuutta kuvaava sekvenssikaavio
- Tarkemmat ohjeet [täältä](/tehtavat/harjoitustyo_viikko5.md)
- Koodikatselmointi (2p)
  - [Koodikatselmointi](/web/koodikatselmointi.md)

#### viikko 6

Palautuksen deadline ti {{ site.wk6dl }}. klo 23:59

- Harjoitustyö (3p)
  - Release 2
  - Testikattavuus nousee
  - JavaDoc aloitettu
  - Alustava versio arkkitehtuuridokumentista
- Tarkemmat ohjeet [täältä](/tehtavat/harjoitustyo_viikko6.md)

#### viikko 7

Lopullisen palautuksen deadline su {{ site.finaldl }}. klo 23:59

- [loppupalautuksen ohjeet](/tehtavat/harjoitustyo_viikko7.md)

### Linkkejä

- [Kurssimateriaali](./web/materiaali.md)
- Viikoittaiset palautukset

  - viikko 1 [laskarit](./tehtavat/viikko1.md)
  - viikko 2 [laskarit](./tehtavat/viikko2.md) ja [harjoitustyö](./tehtavat/harjoitustyo_viikko2.md)
  - viikko 3 [laskarit](./tehtavat/viikko3.md) ja [harjoitustyö](./tehtavat/harjoitustyo_viikko3.md)
  - viikko 4 [harjoitustyö](./tehtavat/harjoitustyo_viikko4.md)
  - viikko 5 [harjoitustyö](./tehtavat/harjoitustyo_viikko5.md)
  - viikko 6 [harjoitustyö](./tehtavat/harjoitustyo_viikko6.md)
  - viikko 7 [harjoitustyö](./tehtavat/harjoitustyo_viikko7.md)

- Kurssin referenssisovellus [OtmTodoApp](https://github.com/mluukkai/OtmTodoApp)
  - Sovelluksen tarkoituksena on demonstroida erästä tapaa tehdä suurin piirtein täysiin pisteisiin riittävä dokumentaatio ja testaus projektillesi. Itse ohjelma on sen verran suppea, että saadaksesi kurssilta arvosanan 5 joudut tekemään hieman laajemman sovelluksen.
- [Labtool](https://study.cs.helsinki.fi/labtool/courses/TKT20002.2021.K.K.1)
- Ohjeita
  - Kaikki ohjeista eivät ole kurssin alussa vielä ajankohtaisia. Kaikkeen tärkeään tulee aikanaan linkki laskareihin tai harjoitustöiden viikkotavoitteisiin
  - [Aiheideoita ja ohjeita työn harjoitustyön aloittamiseen](./web/tyon_aloitus.md)
  - [JUnit-ohje](./web/junit.md)
  - [Käyttöliittymän ja tietojen tallettamisen toteuttamiseen sekä sovelluksen konfigurointiin liittyviä vihjeitä](./web/java.md)
  - [Maven](./web/maven.md)
  - [Checkstyle](./web/checkstyle.md)
  - [JavaDoc](./web/javadoc.md)
  - [koodin laatu](./web/koodin_laatuvaatimukset.md)
- Työkaluja kaavioiden piirtoon
  - <http://yuml.me/> luokkakaaviot
  - <https://www.websequencediagrams.com/> sekvenssikaavioihin
  - <https://app.diagrams.net/> kaikki kaaviot