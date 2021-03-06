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

De Back-end developer is verantwoordelijk voor de code achter ons spel. Hij zorgt dat de objecten van het spel een functie krijgen en dat er bepaalde regels aan die objecten vast zitten. Bij ons schaakspel is hij bijvoorbeeld verantwoordelijk voor de zetten die de speler met een schaakstuk kan doen. De Back-end developer zorgt ook dat de code overzichtelijk blijft, zo kunnen de andere teamleden hem makkelijk helpen.

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

Wij zijn begonnen met een leeg unity document. Hier hebben wij een landschap gecreëerd door een Terrain te maken met behulp van het kopje 3D-object en dan de optie "Terrain." Daarna wilden we een tafel maken en daarop een schaakbord zetten. Dit leuk ons een leuk idee om de opmaak wat aantrekkelijker te maken. Eerst hebben we een tafel gemaakt door 4 poten te maken en een tafelblad. Deze objecten kun je vinden onder het kopje: "Tafelblad." Daarna was ons doel om een schaakbord te maken met losse objecten, die uiteindelijk als 1 object kan bewegen. Om dit te bereiken hebben wij eerst de buitenste rand van het schaakbord gemaakt, om vervolgens met kleine vierkantjes het patroon van een schaakbord te creëen. Door de buitenste randen samen met de kleine blokjes in 1 mapje te zetten, kunnen wij nu het bord als 1 geheel bewegen. Bij het maken van ons schaakbord hebben wij er rekening mee gehouden dat de Back-end er makkelijk mee kan werken. Na het maken van ons schaakbord konden wij ons richten op de schaakstukken. Het maken van de schaakstukken in Unity werd te veel werk om zelf te maken is de beschikbare tijd. Daarom hebben we besloten om de schaakstukken te downloaden zodat we sneller konden werken. Wij hebben de schaakstukken op het schaakbord gezet in de opstelling van het spel. De schaakstukken staan opgesteld in het midden van het vakje. De bedoeling is dat de schaakstukken ook in het midden blijven staan als ze verzet worden. Dit is ook door gecommuniceerd aan de Back-end developer zodat hij ook met de schaakstukken bezig kan. Hierna zijn we bezig geweest met een rond pleintje om het schaakbord. Hier willen we een leukere omgeving mee creëren. Hierbij horen ook de bankjes en de prullenbakken die zich op het plein bevinden. Door gebrek aan tijd hebben wij ervoor gekozen om alle objecten en tegels uit de Assets-store te halen in plaats van het zelf maken.

Na een aantal lessen bezig geweest te zijn met de Front-end liepen wij tegen een probleem aan. Het probleem was dat wij thuis een nieuwe versie van Unity hebben geïnstalleerd. Door hier thuis op te werken was al onze progressie weg, omdat het github programma verschillende "commits" uit 2 verschillende versies van unity niet goed kan samenvoegen. Dit zorgde ervoor dat ons project crashte en alle progressie weg was. Gelukkig had Sil nog een oude versie van ons project op zijn eigen computer staan. Zo konden wij het probleem oplossen door de oudere versie te gebruiken en een nieuwe repository aan te maken. Door de nieuwe repository te koppelen aan de oudere versie van ons project konden we verder met het spel.

Inmiddels kunnen wij dus weer verder met ons project. De front-end is op dit moment zo goed als af. We hebben de opmaak die we voor ogen hadden. Omdat we de Front-end zo goed als af hebben proberen wij nu met zoveel mogelijk mensen uit ons groepje de Back-end te verbeteren.


**PROJECT PROGRESS BACK END:**

Hier beschrijven wij welke stappen we hebben gezet, hoe we die stappen hebben gezet en waarom we die stappen hebben gezet. Hier vindt je de progress van de Back-end.

Het eerste doel van onze Back-end was het kunnen verplaatsen van de pionnen. Dit wouden wij op een logische manier doen door middel van het slepen met de muis. Omdat het erg lastig werd om per pion de verplaats-opties te laten zien, hebben wij ervoor gekozen dit niet te doen. We vertrouwen er dus op dat de spelers zelf de regels kennen en hun pionnen dus ook eerlijk verplaatsen. Een doel hierna was het draaien van de camera. Het leek ons leuk als de camera na elke zet zou draaien zodat je altijd het perspectief van de speler die aan de beurt is ziet. Verder wouden wij ook proberen op ervoor te zorgen dat je de stukken die geslagen zijn naast het speelveld ziet staan. Ook leek het ons een goed idee om een soort start-scherm te maken waar je het spel kunt beginnen en een eventuele pauze knop kunt vinden. Het start-scherm, de camera en de geslagen stukken zijn allemaal ideeën voor de toekomst. Het bewegen en zetten van de stukken is ons eerste doel en daar gaan wij dus ook als eerste mee bezig.

Terwijl Nico met onze Front-end bezig was, is Sil begonnen met het onderliggende principe van het schaakbord. We hebben een kader gemaakt in de code waarin het schaakbord gespeeld zou moeten worden. Dit kader kregen wij achter niet goed onder het schaakbord van Nico in de front-end. De groottes van de vakjes verschilden en we konden het kader niet gelijk krijgen met het schaakbord. Dit kwam ook door de cöordinaten. Hierdoor konden de schaakstukken niet passend op het schaakbord komen die de gebruiker ziet. Voor dat we dit konden gaan oplossen kregen we te maken met technische problemen. Aan het begin hadden we al vaak dat iemand niet kon pushen en dat we dus niet een gezamenlijke versie hadden waar we in konden werken. Toen dat eindelijk opgelost was, ging Sil er thuis mee bezig in een 2018 versie waardoor weer alles misging. We zijn weer terug gegaan naar een oudere versie en dat werkte weer. Totdat we op school ineens weer allemaal conflicten in de code kregen en meldingen van een 2018 versie, terwijl we die niet hadden gebruikt. Toen was ineens alles weg en we konden ook niet terug naar een oudere versie. Sil heeft met zijn nog kloppende oude versie die hij thuis had en waarmee hij de rest niet gepulled had een nieuwe repository opgezet. Nu werkte alles weer. Toen hebben we gekeken hoe je schaakstukken kon spawnen, maar geen  tutorial kon ons helpen. Toen is Sil gaan kijken hoe we de schaakstenen nou in beweging konden krijgen met cöordinaten. Allerlei tutorials gekeken, maar geen werkende. Daarna gekeken naar de mogelijkheden met het slepen met de muis, maar dit werkte ook niet. Vervolgens gekeken of je een bepaald vak begrensd door coordinaten een letter met cijfer kon geven om vervolgens met een tekst input een zet te kunnen doen. Wederom geen succes. Ook gekeken naar de optie om de stenen de eigenschappen van dammen te geven, maar dit kon weer niet met de cöordinaten. Als laatst hebben we nog van alles geprobeerd om op één of andere manier de schaakstenen te selecteren of te verplaatsen. We hebben ook geprobeerd om de muis te traceren en het dan te selecteren. We hebben allerlei tutorials gekeken en alle kleine onderdelen bekeken of we daar iets mee konden, maar het heeft niet tot succes geleidt, ondanks de vele tijd die we erin hebben gestoken. Ook hebben we geprobeerd om een uitgewerkte tutorial in te voegen om te laten zien hoe het had gemoeten, maar dit gaf aan dat er errors waren, maar kon ze niet geven. Daarom hebben we nog een beeld geschets door onze omgeving na te bootsen in het unity bestand van de uitgewerkte tutorial van het schaakspel. 

Door het veranderen van repository in de laatste week hebben wij weinig werkende commits in deze repository staan. Het is misschien toch handig om dit te bekijken omdat hier nog wel per toevoeging beschreven staan wat er is toegevoegd.
Al met al hebben wij dus in de beschikbare tijd geen goed werkende back-end kunnen schrijven. Dit tot onze grote spijt.

Hierboven valt het proces te lezen wat we hebben doorgemaakt. Hier nog even een kleine terugblik/conclusie, want ondanks dat het niet tot het gewenste resultaat geleverd heeft, hebben we er veel van geleerd en leerzame ervaringen opgedaan.
Conclusie
Het begon allemaal bij de rolverdeling. Die verliep zeer goed en iedereen had een passende rol. 
De opzet van het project en de visualisatie van het eindproduct waar we naartoe gingen werken was ook goed in kaart gebracht. Aan het begin hebben we ons niet goed genoeg verdiept in de nieuwe programmeertaal en mede hierdoor een verkeerde keuze gemaakt in het ontwikkelproces. De backend is begonnen met het creëren van schaakstukken en een schaakbord. We hadden het idee dat we die dan vervolgens script konden meegeven. Achteraf gezien hadden we eerst doormiddel van script de setting van het schaakbord moeten maken en dan had Nico daarna het met de front-end kunnen opmaken i.p.v. eerst met front-end een schaakbord maken en alles opmaken en dat vervolgens scripts mee te geven. Wij hebben het andersom gedaan en dat zorgde voor een hoop problemen bij het coderen. Buiten deze problemen hebben we ook veel te verduren gehad qua unity/GitHub. Hier hebben we veel tijd aan moeten besteden en dat heeft er ook voor gezorgd dat we daardoor qua code schaakmat stonden en we niet meer de problemen konden oplossen die we bij het coderen tegenkwamen. Ondanks dat het uiteindelijk dan niet wilde, hebben we wel met veel inzet en door creatief/probleem-/oplossingsgericht te denken geprobeerd om via de ingeslagen weg het eindproduct te bereiken. Soms dan maar met een omweg, maar niet de handdoek in de ring gooien als het via de hoofdweg die je in gedachten hebt niet lukt.



