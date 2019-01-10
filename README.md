# 2019-aa6-schoaken

**HOME:**

Welkom bij de documentatie van het informatica-project "schoaken".

**Dit project is gemaakt door:**

Niek ten Have
Sil Brouwer
Jeroen ten Brinke
Nico Datema
Jan Hoeksema
Stijn Wardenaar

**TAKEN PER PERSOON:**

*Project Owner (Niek):*

De product owner is de leider van het groepje. De product owner besluit wat er gedaan wordt en in welke volgorde dat gebeurd. Ook zorgt de product owner ervoor dat het spel zo veel mogelijk lijkt op het originele spel. Verder helpt de product owner waar nodig en zorgt hij dat iedereen door kan werken.

*Front-end (Nico):*

De Front-end designer zorgt voor het uiterlijk van ons spel. Hij is de man die met de decoratie bezig is en die alle objecten van het spel maakt. Hij werkt nauw samen met de Back-end developer die de objecten een taak geeft.

*Back-end (Sil):*

De Back-end developer is verantwoordelijk voor de code achter ons spel. Hij zorgt dat de objecten van het spel een functie krijgen en dat er bepaalde regels aan die objecten vast zitten. Bij ons schaakspel is hij bijvoorbeeld verantwoordelijk voor de zetten die de speler met een schaakstukkan doen. De Back-end developer zorgt ook dat de code overzichtelijk blijft, zo kunnen de andere teamleden hem makkelijk helpen.

*Architect (Jan):*

De architect is verantwoordelijk voor de logica in het spel. Hij heeft het overzicht over de regels die belangrijk zijn in het spel. Ook is het belangrijk dat dit in ons spel duidelijk naar voren komt. Verder is de architect bezig met de structuur van het spel. Hij moet daardoor ook zorgen dat het spelen van het spel zo min mogelijk afwijkt van het originele spel.

*Loodgieter (Jeroen):*

De loodgieter is een rol die wij zelf hebben verzonnen. Omdat er maar 5 rollen zijn en wij met 6 mensen zijn hebben wij zelf de loodgieter bedacht. De loodgieter is een mannetje van alles. Hij helpt iedereen waar nodig. Wij hebben deze taak daarom ook gegeven die van alles wat weet. De loodgieter dicht alle lekken in onze code.

*Documentatie (Stijn):*

Bij de documentatie is het belangrijk dat alle aspecten van ons project overzichtelijk en dus duidelijk te zien zijn. De taken van de teamleden moeten duidelijk zijn. Ook moet te zien zijn hoe wij tot ons eindproduct zijn gekomen en wat voor kijk wij hebben op ons spel. De documentatie moet dus zorgen voor een duidelijke samenvatting van ons spel.

**ARCHITECTUUR:**

De architect is verantwoordelijk voor een logische opbouw van het spel. Met de architectuur kan de rest van het team aan de slag met een handige opbouw. Bij dit spel hebben wij een schema van het spel en de spelregels gemaakt. Dit komt bijna overeen met de architectuur. Wij hebben bij dit schema ook nog wat extra architectuur gevoegd zodat dit schema de volledige architectuur bevat. Dit schema kan je hier vinden, bij de pagina: 'regels per schaakstuk'.


**REGELS PER SCHAAKSTUK:**

Wij hebben de regels per schaakstuk handig in een schema beschreven. Dit is tevens ook een groot deel van de architectuur.
Dit schema is een foto en kan dus helaas niet in de readme gezien worden. Ik heb hem daardoor in de Wiki van deze repository gezet.
Hier kun je dus alsnog het schema van de schaakstukken zien: https://github.com/Silbrouwer/2019-aa6-schoaken/wiki/Regels-per-schaakstuk

**PROJECT PROGRESS FRONT END:**

Hier beschrijven wij welke stappen we hebben gezet, hoe we die stappen hebben gezet en waarom we die stappen hebben gezet. Hier vindt je de progress van de Front-end.

Wij zijn begonnen met een leeg unity document. Hier hebben wij een landschap gecreëerd door een Terrain te maken met behulp van het kopje 3D-object en dan de optie "Terrain." Daarna wilden we een tafel maken en daarop een schaakbord zetten. Dit leuk ons een leuk idee om de opmaak wat aantrekkelijker te maken. Eerst hebben we een tafel gemaakt door 4 poten te maken en een tafelblad. Deze objecten kun je vinden onder het kopje: "Tafelblad." Daarna was ons doel om een schaakbord te maken met losse objecten, die uiteindelijk als 1 object kan bewegen. Om dit te bereiken hebben wij eerst de buitenste rand van het schaakbord gemaakt, om vervolgens met kleine vierkantjes het patroon van een schaakbord te creëen. Door de buitenste randen samen met de kleine blokjes in 1 mapje te zetten, kunnen wij nu het bord als 1 geheel bewegen. Bij het maken van ons schaakbord hebben wij er rekening mee gehouden dat de Back-end er makkelijk mee kan werken. Na het maken van ons schaakbord konden wij ons richten op de schaakstukken. Het maken van de schaakstukken in Unity werd te veel werk om zelf te maken is de beschikbare tijd. Daarom hebben we besloten om de schaakstukken te downloaden zodat we sneller konden werken. Wij hebben de schaakstukken op het schaakbord gezet in de opstelling van het spel. De schaakstukken staan opgesteld in het midden van het vakje. De bedoeling is dat de schaakstukken ook in het midden blijven staan als ze verzet worden. Dit is ook door gecomenuceerd aan de Back-end developer zodat hij ook met de schaakstukken bezig kan. Hierna zijn we bezig geweest met een rond pleintje om het schaakbord. Hier willen we een leukere omgeving mee creëren. Hierbij horen ook de bankjes en de prullenbakken die zich op het plein bevinden. Door gebrek aan tijd hebben wij ervoor gekozen om alle objecten en tegels uit de Assets-store te halen in plaats van het zelf maken.

Na een aantal lessen bezig geweest te zijn met de Front-end liepen wij tegen een probleem aan. Het probleem was dat wij thuis een nieuwe versie van Unity hebben geïnstalleerd. Door hier thuis op te werken was al onze progressie weg, omdat het github programma verschillende "commits" uit 2 verschillende versies van unity niet goed kan samenvoegen. Dit zorgde ervoor dat ons project crashte en alle progressie weg was. Gelukkig had Sil nog een oude versie van ons project op zijn eigen computer staan. Zo konden wij het probleem oplossen door de oudere versie te gebruiken en een nieuwe repository aan te maken. Door de nieuwe repository te koppelen aan de oudere versie van ons project konden we verder met het spel.

Inmiddels kunnen wij dus weer verder met ons project. Dit moment is dicht bij de deadline. Daarom proberen wij nu met zoveel mogelijk mensen uit ons groepje de Back-end te verbeteren.

**PROJECT PROGRESS BACK END:**

Hier beschrijven wij welke stappen we hebben gezet, hoe we die stappen hebben gezet en waarom we die stappen hebben gezet. Hier vindt je de progress van de Back-end.

Het eerste doel van onze Back-end was het kunnen verplaatsen van de pionen. Dit wouden wij op een logische manier doen door middel van het slepen met de muis. Omdat het erg lastig werd om per pion de verplaats-opties te laten zien, hebben wij ervoor gekozen dit niet te doen. We vertrouwen er dus op dat de spelers zelf de regels kennen en hun pionnen dus ook eerlijk verplaatsen. Een doel hierna was het draaien van de camera. Het leek ons leuk als de camera na elke zet zou draaien zodat je altijd het perspectief van de speler die aan de beurt is ziet. Verder wouden wij ook proberen op ervoor te zorgen dat je de stukken die gelsagen zijn naast het speelveld ziet staan. Ook leek het ons een goed idee om een soort start-scherm te maken waar je het spel kunt beginnen en een eventuele pauze knop kunt vinden. Het start-scherm, de camera en de geslagen stukken zijn allemaal ideeën voor de toekomst. Het bewegen en zetten van de stukken is ons eerste doel en daar gaan wij dus ook als eerste mee bezig.




