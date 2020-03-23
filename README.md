# Box_Office_Sales

## Release dates
* Emma: 6 maart
* Onward: 6 maart
* The Way Back: 6 maart
* The Hunt: 13 maart
* Godzilla vs. Kong: ~~13 maart~~
* My Spy: ~~13 maart~~ verplaatst naar 17 april
* Bloodshot: 13 maart
* I still believe: 20 maart
* A quiet place: ~~20 maart~~
* Mulan: 27 maart

## Document Structuur
_De datum van wanneer elk document is gescraped, staat in de naam van het document (bv. box_office_06_03_20 is data gescraped op 6 maart 2020)_

### 1 box_office
Data over de websites [The Numbers](https://www.the-numbers.com/weekend-box-office-chart). Deze wordt elk weekend gescraped voor de films dat weekend uitkomen in de VS.

1. title
2. distributor
3. gross_revenue (dependent variable)
4. theatres (aantal theaters waar de film wordt getoond)
5. revenue_per_theatre

### 2 imdb
#### 2.1 movie_page
Dit is alle data dat verzameld wordt op de imdb pagina's van die films (bv. [Emma](https://www.imdb.com/title/tt9214832/)).

1. movie
2. imdb_rating (de ster rating om de film 0-10)
3. imdb_rating_count (hoeveelheid mensen die een rating hebben nagelaten)
4. directors
5. writers
6. stars (belangrijkste acteurs in de film)
7. metacritic_rating (rating op metacritic 0-100)
8. popularity (score op basis van hoeveel mensen die film opzoeken op imdb)
9. runtime (duur van de film)
10. genres
11. languages
12. MPAA_rating (de leeftijdsgeshiktheid van de film bv. PG-13 is voor personen boven de 13 jaar)
13. release_date
14. storyline (kleine samenvatting van het plot van de film)

#### 2.2 user_reviews
Zip file van alle user reviews gevonden op imdb (bv. [Emma](https://www.imdb.com/title/tt9214832/reviews)).

#### 2.3 critic_reviews
Zip file van alle critic reviews gevonden op imdb (bv. [Emma](https://www.imdb.com/title/tt9214832/externalreviews)).

### 3 twitter
Tweets van 1 week van alle films. Dit is opgeslitst in earned media en owned media. Earned media zijn de tweets van de twitter pagina's van de films zelf (bv. [Emma](https://twitter.com/emmamovie)). Owned media zijn de tweets gemaakt onder een hashtag van die film. De laaste paar tweets slaan opgeslagen als .rar ipv .zip omdat deze betere compressie hebben (kleinere file size).

#### 3.1 twitter accounts
* https://twitter.com/emmamovie
* https://twitter.com/DisneysMulan
* https://twitter.com/TheHuntMovie
* https://twitter.com/pixaronward
* https://twitter.com/GodzillaVrsKong
* https://twitter.com/istillbelieve
* https://twitter.com/TheHuntMovie
* https://twitter.com/TheWayBackMovie
* https://twitter.com/Bloodshot
* https://twitter.com/quietplacemovie

#### 3.2 Hashtags
* #EMMA
* #mulan
* #TheHuntMovie
* #PixarOnward
* #GodzillaVsKong
* #IStillBelieve
* #MySpyMovie
* #TheWayBack
* #Bloodshot
* #AQuietPlace
