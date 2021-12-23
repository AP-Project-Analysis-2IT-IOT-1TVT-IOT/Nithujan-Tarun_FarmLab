<div align="center" ><h1>FarmLab</div>
<br>
<br>
<div align="center" ><h1>Electronica-ICT</div>
<br>
<div align="center"><h1>Blueprint FarmLab</div>
<div align="center"><h4>Onderdeel van project analyse</div>
<br>
<div align="center"><h3>Nithujan Selvaratnam & Tarun Singh</div>
<div align="center"><h4>Traject IT&IOT AP Hogeschool</div>
<br>
<div align="center"><h3>Begeleider: Patrick Van Houtven <h3>Academiejaar 2021-2022 1ste semester</div>

# Inhoudstafel

[Versiebeheer](#versiebeheer)

[Termen en Afkortingen](#termen-en-afkortingen)

[Opdrachtgever](#opdrachtgever)

[Samenvatting](#samenvatting)

[Situatie As-Is](#situsasis)

[Situatie To-Be](#situstobe)

[Projectdefinitie](#projectdefinitie)

[Doelstelling](#doelstelling)

[Scope](#scope)

[Niet in Scope](#nietinScope)

[Planning](#planning)

[Hoofdlijnen](#hoofdlijnen)

[Functioneel design](#functioneeldesign)

[Technisch design](#technischdesign)

[Beschrijving van de mogelijke interfaces](#interfaces)

[Beschrijving van eventuele datamigratie](#datamigratie)

[Beschrijving van eventuele impact op de huidige infrastructuur](#infrastructuur)

[Analyse van security en eventuele autorisatierollen](#autorisatierollen)

[Documentatie](#documentatie)

[Bronvermelding](#bronvermelding)

# Versiebeheer <a id="versiebeheer">

| Nr.   | Datum      | Verspreiding                      | Status              | Wijziging                                                                                                                                                                           |
|-------|------------|-----------------------------------|---------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 0.01  | 2021-11-25 | Nithujan Selvaratnam, Tarun Singh | Git Aanmaak         | Aanmaken van GitHub repository + markdown geleerd                                                                                                                                   |
| 0.02  | 2021-12-02 | Nithujan Selvaratnam, Tarun Singh | Aanmaak structuur   | Maken van Git map structuur + GitHub Kanban planning                                                                                                                                |
| 0.1.0 | 2021-12-09 | Nithujan Selvaratnam, Tarun Singh | Eerste draft        | Probleemstelling verwerken + situatie as-is aanpassen + verder verwerken van planning + schema’s maken                                                                              |
| 0.1.1 | 2021-12-11 | Nithujan Selvaratnam, Tarun Singh | Aanpassingen        | Maken van User Stories in planning + aanpassen van situatie as-is                                                                                                                   |
| 0.1.2 | 2021-12-12 | Nithujan Selvaratnam, Tarun Singh | Verder werken       | Verwerken van situatie to-be + blok schema                                                                                                                                          |
| 0.2.0 | 2021-12-16 | Nithujan Selvaratnam, Tarun Singh | Tweede draft        | Maken van functionele design + analyseren van sensoren                                                                                                                              |
| 0.2.1 | 2021-12-17 | Nithujan Selvaratnam, Tarun Singh | Extra info          | Extra informatie aan de studenten van 3de jaar vragen + aanpassingen van situatie as-is + situatie to-be + blokdiagrammen                                                           |
| 0.2.2 | 2021-12-18 | Nithujan Selvaratnam, Tarun Singh | Verder aanpassingen | Aan de hand van de extra informatie die we hebben gekregen van de 3de jaar studenten, hebben we de functionele design, situatie as-is , situatie to-be en blokdiagrammen aangepast  |
| 0.3.0 | 2021-12-19 | Nithujan Selvaratnam, Tarun Singh | Derde draft         | Maken van technische design en blokdiagrammen + componenten opzoeken                                                                                                                |
| 0.3.1 | 2021-12-20 | Nithujan Selvaratnam, Tarun Singh | Aanpassingen        | Maken van interface + datamigiratie                                                                                                                                                 |
| 0.3.2 | 2020-12-21 | Nithujan Selvaratnam, Tarun Singh | Aanpassingen        | Werken aan elektrische schema’s + verder aanpassingen van blokdiagrammen van situatie to-be en situatie as-is + blokdiagram van technische design aangepast                         |

# Termen en Afkortingen <a id="termen-en-afkortingen">

| Term | Omschrijving                                                                                       |
|------|----------------------------------------------------------------------------------------------------|
| pH   | pH is een maat voor de zuurtegraad van een oplossing.                                              |
| pcb  | pcb is een printed circuit board. Hierop kunnen we verschillende elektrische componenten solderen. |
| AI   | AI betekent artificiële intelligentie.                                                             |
| lux  | Lux is een eenheid van lichtsterkte.                                                               |

# Opdrachtgever <a id="opdrachtgever">

| Naam                | Omschrijving                                                  |
|---------------------|---------------------------------------------------------------|
| Patrick Van Houtven | Hij is de projectbegeleider voor het project Farmlab.         |
| Maarten Luyts       | Hij is de productowner en de klant voor het project Farmlab.  |

# Samenvatting <a id="samenvatting">

Het project gaat over hydroponics. Hydroponics is een soort techniek om planten
te kweken in een pot met water. Het water bevat echter wel de nodige
voedingsstoffen om de planten goed te laten groeien. Met behulp van Farmlab gaan
we het concept van hydroponics verbeteren, automatiseren en gebruiksvriendelijk
maken. De slimme technologie van Farmlab zal dan in staat zijn om de gebruiker
zo veel mogelijk te helpen met het groeiproces van de plant.

# Situatie As-Is <a id="situsasis">

Onze huidige probleemstelling is als volgt:

*Het huidige modulaire systeem is nog niet gebruiksvriendelijk genoeg en niet
voldoende geautomatiseerd.*

Om deze probleemstelling te realiseren hebben de studenten van het derde jaar de
basis al opgelegd. Voor een duidelijke illustratie vindt u hieronder een schema
van het project Farmlab.

![](./../media/e92b01b5d8fbb38063b05aa57316389f.png) 

*Figuur 1: schematische voorstelling van Farmlab*

![Afbeelding met binnen, vloer Automatisch gegenereerde
beschrijving](./../media/37bb0c23488967967713c8f2a8271d44.png)

Het bovenstaande
diagram toont aan hoe alles in elkaar zit en welke componenten er gebruikt
worden. Deze componenten worden gemonteerd in de kast.

*Figuur 2: achterkant van de kasten* 

![Afbeelding met binnen, rommelig Automatisch gegenereerde beschrijving](./../media/c6da35064a3313353931e2899bd5e574.png)

*Figuur 3: voorkant van de kasten* 

![Afbeelding met binnen, rommelig Automatisch gegenereerde
beschrijving](./../media/c6da35064a3313353931e2899bd5e574.png)

Raspberry Pi is het hart van dit project. Hierop staat een MQTT-broker
geïnstalleerd die alle berichten van de controllers verzamelt of doorstuurt.
Verder wordt het project in verschillende onderdelen verdeelt, namelijk:

-   Waterpomp

    De waterpomp pompt het water door alle drie de buizen. Deze pomp wordt
    aangesloten met de pomp controller. Wanneer de Raspberry Pi een bericht
    doorstuurt aan de controller, dan zal deze met behulp van de waterpomp het
    water elke uur, vijf minuten laten doorvloeien.

-   Led lichten

    Om de planten s ’nacht ook goed te laten groeien en voldoende te belichten,
    maken we gebruik van de led lichten. Deze led lichten worden bestuurd door
    de led controller.

-   Lichtsensor

    Om de lichtinval van de planten te meten, gebruiken we een lichtsensor. Deze
    sensor stuurt een analoge signaal door aan de lichtsensor controller. Deze
    controller zorgt dan ervoor dat de informatie doorgestuurd wordt naar de
    Raspberry Pi.

-   Dashboard

    Op dit dashboard komt de informatie van de led lichten, de lichtsensor en
    van de pomp tevoorschijn. Een voorbeeld hiervan is het hoeveel licht dat er
    op de planten komt, of het licht aan of uit staat en hoeveel keer het water
    gepompt is geweest.

Dit systeem is echter nog niet helemaal geautomatiseerd en
gebruikersvriendelijk. Daarnaast zijn er nog andere aspecten die nog verwerkt en
verbeterd moeten worden. Dit komt verder nog aan bod.

# Situatie To-Be <a id="situstobe">

![](./../media/111e8dd6d3c096e3fdb9ecee88e9e5ac.png)Het onderstaande schema geeft een
duidelijke weergave van welke componenten er nog moeten bijkomen.

*Figuur 4: nieuwe schematische voorstelling van Farmlab*

Bij het verbeteren van het Farmlab gaan we eerst de bestaande pcb’s herwerken
zodat ze efficiënter en kleiner zijn. Bovendien gaan we de lichtsensoren en de
led lichten apart plaatsen bij elk niveau van de kast. Als volgt komt er ook nog
een extra voedingspomp bij. De voedingspomp zorgt dan ervoor dat de
voedingsmiddelen in het water terechtkomen. Volgende stukken die nog bijkomen
zijn:

-   Camera en motoren

    We plaatsen ook een camera en twee motoren. De camera zal op de loopband van
    de motoren gemonteerd worden. De motoren worden hier bestuurd met een motor
    driver. Daarna gaan de motoren rustig langs elke plant en vervolgens trekt
    de camera foto’s van de planten. Deze foto’s worden doorgestuurd naar de
    Raspberry Pi met een controller. Met deze afbeeldingen kunnen we ook een AI
    cluster bouwen. Hierdoor kunnen we met behulp van machine learning te weten
    komen of onze planten goed kweken.

-   Sensoren zoals pH-sensor, waterlevel sensor, temperatuursensor en
    lichtsensor

    De pH-sensor gaat meten hoe gezond het water is en hoeveel voedingstoffen in
    het water momenteel beschikbaar zijn. Om te meten hoeveel water in de buizen
    doorstroomt gebruiken we de waterlevel sensor. Vervolgens meten we ook de
    temperatuur van de omgeving waarin de platen zich bevinden aan de hand van
    een temperatuursensor. Als laatste gebruiken we ook een lichtsensor om de
    lichtinval te meten. Deze metingen gebeuren regelmatig op bepaalde
    tijdstippen en worden doorgestuurd naar de controller. De controller zorgt
    dan ervoor dat de data doorgestuurd wordt naar de Raspberry Pi.

Verder gaan we nog de bijkomende sensoren en componenten automatiseren. Ook
zullen we onze aandacht besteden aan het monteersysteem van de pcb’s en aan de
kabel management. Aangezien er nieuwe componenten bijkomen, gaan we onze
Node-RED interface ook moeten uitbreiden voor gebruiksvriendelijkheid.

## Projectdefinitie <a id="projectdefinitie">

## Doelstelling <a id="doelstelling">

Bij het maken van dit project willen we de volgende doelstellingen zeker
realiseren:

-   herwerken van pcb’s

    -   sturing van x-as en y-as motor en de camera

        -   pH-sensor, waterlevel sensor en temperatuursensor toevoegen

        -   voedingspomp toevoegen

        -   automatisatie van nieuwe bijkomende componenten

        -   interface uitbreiden

        -   betere behuizingen voor de pcb’s

## Scope <a id="scope">

Om onze scope realiseerbaar te maken, willen we alvast volgende punten bereiken
zodat we het Farmlab minstens drie maanden kunnen laten draaien en oogst kunnen
produceren:

-   schema’s voor de pcb’s opstellen met als hoogte 12 cm en als lengte 10 cm

    -   ESP32-chip op zelfgemaakte pcb plaatsen en programmeren met Arduino IDE
        software

        -   nieuwe bijgevoegde controllers laten werken met MQTT-berichten

        -   motoren in x-as en y-as laten bewegen met behulp van de Node-RED
            interface

        -   metingen door de lichtsensor tussen 0 lux en 40000 lux

        -   metingen door waterlevel sensor tussen 0 cm en 15 cm

        -   metingen door temperatuursensor tussen -16 graden en 42 graden

        -   meten van de zuurgraad tussen 0 en 14 met pH-sensor

        -   foto’s trekken met de camera met een resolutie van 1600 x 1200

        -   3D geprint monteer systeem voor pcb’s bouwen met Fusion 360

## Niet in Scope <a id="nietinScope">

De volgende punten vallen momenteel buiten het criteria van minimum viable
product. Maar als er nog genoeg tijd overschiet, zullen we ons best doen dat nog
realiseerbaar te maken.

-   AI cluster bouwen

    -   machine learning toepassen om te bepalen of de plant voldoende groeit

        -   Automatische aansturing van alle componenten afhankelijk van de
            plantensoort.

# Planning <a id="planning">

Bij het plannen van deze analyse maken wij gebruik van Kanban op GitHub. Aan het
begin van deze analyse hebben we de stukjes van deze blueprint tussen ons tweeën
verdeeld. Daarna hebben we die stukken verder naar de User Stories toe
uitgewerkt. Hieronder ziet u een momentopname van onze Kanban.

![](./../media/6610196603a6085a431aaf3a122915c7.png)

*Figuur 5: planning op Kanban*

![](./../media/579b25a713fa2fcf149b0d67a02f736e.png)Hieronder vindt u de planning van
het tweede semester. Tijdens het uitvoeren van het project kunnen er nog altijd
wijzigingen aangebracht worden in de planning. Daarom hebben we de planning
enkel voor de eerste vier maanden gemaakt, aangezien het onzeker is hoe ver we
zullen geraken tijdens het uitwerken van het project.

*Figuur 6: tijdlijn voor het IoT project*

## Hoofdlijnen <a id="hoofdlijnen">

De volgende delen zullen de grootste deadlines bevatten:

-   herwerking van de pcb’s (9 februari – 23 februari 2022)

-   vervanging van de Raspberry Pi door ESP32 (9 maart 2022)

-   toevoegingen van de nieuwe componenten (9 maart 2022 – 16 maart 2022) en (23
    maart 2022 – 13 april 2022)

-   uitbereiding van interface (13 april 2022 – 18 mei 2022)

-   automatisatie van de componenten (27 april 2022 – 18 mei 2022)

# Functioneel design <a id="functioneeldesign">

De planten die we in het Farmlab gaan proberen te kweken is bieslook, basilicum
en koriander. Op elk niveau van de kast zetten we een andere plantensoort. Dit
betekent dat de acties en de beslissingen die het Farmlab-systeem zal uitvoeren,
afhankelijk is van de plantensoort.

Door de buizen van het Farmlab vloeit er elke uur, vijf minuten water en
voedingsstoffen door met behulp van de water- en voedingspomp. We geven 5
mililiter voeding per 2 liter water. We kunnen dit ook bepalen door te kijken
naar de wortels van de plant. Ook controleert de pH sensor de zuurtegraad van
het water waardoor we de hoeveelheid voeding die in het water aanwezig is,
kunnen vastleggen. De meting gebeurt tussen de waarde van 0 en 14. Het
kraanwater heeft al een pH-waarde van 7.5.

De waterlevel sensor kijkt naar de niveau van het water in de buizen. Deze
meting is in centimeters. Onze buis, waarin de planten groeien heeft een
diameter van ongeveer 12 cm. Waterlevel tussen 9 en 8 cm zal het best zijn voor
de planten. Zo zitten de wortels van de planten zeker in het water.

Daarnaast hebben we ook een temperatuursensor, die de temperatuur van de
omgeving meet. Deze temperatuursensor moet zeker tussen -16 graden en 22 graden
kunnen meten. Deze kan de eindgebruiker helpen om te beslissen welke
plantensoort het best zal passen bij de gemeten temperatuur.

De lichtsensoren meten ook elke 5 minuten het licht. Deze meting is in lux
tussen 330 en 32000 lux. Bij het groei van de bieslook, basilicum en koriander
is blauw licht het meest geschikt aangezien de planten zich in het begin nog in
de groeifase zullen bevinden.

Bovendien draait de x-as motor in een horizontale richting en de y-as motor in
een verticale richting. Op deze manier kunnen de motoren in elke richting gaan
en kan de camera de foto’s trekken. Deze foto’s komen dan ook op de website
terecht.

Zoals al eerder gezegd worden alle soorten sensoren apart bestuurd door een
controller. Die controllers sturen dan de elke 10 minuten de nodige informatie
door naar de Raspberry Pi. Deze communicatie gebeurt via het MQTT-protocol. De
temperatuurmetingen, de pH-metingen, de waterlevelmetingen, lichtmeting en de
leds die aan of uit zijn, kunnen we allemaal besturen via de Node-RED interface.

Om de workflow duidelijker te illustreren, vindt u hieronder een
activiteitsdiagram.

*![](./../media/d705f94e8222cab76700fcf153226255.png)Figuur 7: activiteitsdiagram van
Farmlab*

# Technisch design <a id="technischdesign">

## **Smart Object (Hardware Analyse)**

Bij de hardware analyse overlopen we eerst elke deel van Farmlab apart en op het
einde voegen we alle delen samen in een blokdiagram.

## Blokdiagrammen <a id="blokdiagrammen">

Lichtsensor controller

![](./../media/f547b8197e202783acc683f9c202930e.png)

*Figuur 8: schema van lichtsensor controller*

| **Naam**                                                                                | **specificaties**                                                                                                                                                    | **argumentatie**                                                                                                                                                                                                                                  | **alternatieven**                        |
|-----------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------|
| TSL2561  (lichtsensor) ![](./../media/747a2da655d5f9f530f059afcc1c6530.png)                  |    Max lux = 40000 Temperatuur: -30 tot 70 Interface: I²C en SPI                                                                                                     | Deze component is zeer compact en kan tot 40000 lux meten. Ook kan deze component werken met I²C en SPI protocolen. Studenten van het derde jaar gebruiken deze sensor ook. Hierdoor wordt het makkelijker voor ons om hieruit verder te werken.  | Light Dependent Resistor, TSL235R, LM393 |
| ESP32-WROOM (lichtsensor controller)    ![](./../media/ac0117e4d3aecefba468f34e44683797.png) |    ROM: 448 KB SRAM : 520 KB 802.11 b/g/n Wi-Fi connectiviteit Bluetooth 4.2 18 ADC channels 16 PWM channels Serial connectivieit:  4 x SPI 2 x I²C 2 x I²S 3 x UART | ESP32 is een zeer krachtig microcontroller. Het is ook geschikt om te communiceren met andere modules. Onze opdrachtgever gaf immers aan dat we deze component moeten gebruiken.                                                                  | ESP8266, ESP12                           |

Ledlevel controller

![](./../media/366c3c8bdd591a87bfa15e55ec27f27f.png)

*Figuur 9: schema van ledlevel controller*

| **Naam**                                                                           | **specificaties**                                                                                                                                                    | **argumentatie**                                                                                                                                                                  | **alternatieven** |
|------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-------------------|
| led strips ![](./../media/2f41f422555483c68f7b0d95efff7b85.png)                         |  Led style: smd 5050 Kleur: rood en blauw Waterdichtheid: IP65/IP33                                                                                                  | De led strips hebben de kleur rood en blauw. Bovendien zijn ze waterdicht en zijn in verschillende lengtes beschikbaar.                                                           | Halogeen lampen,  |
| ESP32-WROOM (led level controller) ![](./../media/ac0117e4d3aecefba468f34e44683797.png) |    ROM: 448 KB SRAM : 520 KB 802.11 b/g/n Wi-Fi connectiviteit Bluetooth 4.2 18 ADC channels 16 PWM channels Serial connectivieit:  4 x SPI 2 x I²C 2 x I²S 3 x UART | ESP32 is een zeer krachtig microcontroller. Het is ook geschikt om te communiceren met andere modules. Onze opdrachtgever gaf immers aan dat we deze component moeten gebruiken.  | ESP8266, ESP12    |

Pomp controller

![](./../media/aaf825313bda5af33114e70bef05eb6e.png)

*Figuur 10: schema van pomp controller*

| **Naam**                                                                                        | **specificaties**                                                                                                                                                    | **argumentatie**                                                                                                                                                                           | **alternatieven**   |
|-------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------|
| ![](./../media/6020406f3227fa5da9da3e4a2b0a07d0.png)Barwig Typ 03 0333  (Waterpomp en voedingspomp)  |  Pompvermogen: 10l/min Persdruk: 0.6 max Transporthoogte: 6m                                                                                                         | Deze pomp kan op lage spanning werken. Het heeft ook voldoende kracht om het water in alle drie de niveau’s te laten doorstomen. De pomp gebruiken we dan ook voor onze vloeibare voeding. | peristaltische pomp |
| ESP32-WROOM (pomp controller) ![](./../media/ac0117e4d3aecefba468f34e44683797.png)                   |    ROM: 448 KB SRAM : 520 KB 802.11 b/g/n Wi-Fi connectiviteit Bluetooth 4.2 18 ADC channels 16 PWM channels Serial connectivieit:  4 x SPI 2 x I²C 2 x I²S 3 x UART | ESP32 is een zeer krachtig microcontroller. Het is ook geschikt om te communiceren met andere modules. Onze opdrachtgever gaf immers aan dat we deze component moeten gebruiken.           | ESP8266, ESP12      |

pH-, temperatuur- en waterlevel controller

![](./../media/43d725070882be4d66bb822ac0545356.png)

*Figuur 11: schema van pH-, temperatuur- en waterlevel controller*

| **Naam**                                                                  | **specificaties**                                                                                                                                                    | **argumentatie**                                                                                                                                                                                                    | **alternatieven**                                                                                                                                                                                                                              |
|---------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| DHT22 (temperatuursensor) ![](./../media/6631d5bb2d022fc7c36b4ff63d8700b8.png) |  Temperatuur: -40 tot 80 Celsius Accuraathied: +- 0.5 Celsius                                                                                                        | Volledig temperatuur gecompenseerd  Relatieve vochtigheid en temperatuurmeting Uitstekende stabiliteit op lange termijn Extra componenten niet nodig Laag stroomverbruik 4 pinnen verpakt en volledig uitwisselbaar | [HIH6130-021-001](https://sensing.honeywell.com/honeywell-sensing-humidicon-hih6100-series-product-sheet-009059-6-en.pdf), [SHT31-DIS-B](https://www.mouser.com/datasheet/2/682/Sensirion_Humidity_Sensors_SHT3x_Datasheet_digital-971521.pdf) |
| ESP32-WROOM  ![](./../media/ac0117e4d3aecefba468f34e44683797.png)              |    ROM: 448 KB SRAM : 520 KB 802.11 b/g/n Wi-Fi connectiviteit Bluetooth 4.2 18 ADC channels 16 PWM channels Serial connectivieit:  4 x SPI 2 x I²C 2 x I²S 3 x UART | ESP32 is een zeer krachtig microcontroller. Het is ook geschikt om te communiceren met andere modules. Onze opdrachtgever gaf immers aan dat we deze component moeten gebruiken.                                    | ESP8266, ESP12                                                                                                                                                                                                                                 |
| E-201C-BLUE (pH-sensor) ![](./../media/5d1e7f9dace8bb45a11bb1da382343d4.png)   |  pH range: 0- 14 accuraatheid: +-0.2pH meet temperatuur: 0°C – 60°C                                                                                                  | Deze component heeft een nauwkeurige accuraatheid. Het bereik van de meettemperuur is ook vrij groot. Bovendien heeft deze een uitstekende stabiliteit op lange termijn.                                            | niet van toepassing                                                                                                                                                                                                                            |

De waterlevel sensor gaan we zelf ontwerpen op een pcb.

Motor en camera controller

![](./../media/278bc343aa333176b009fdc64e1a6ffa.png)

*Figuur 12: schema van Motor en camera controller*

| **Naam**                                                                                        | **specificaties**                                                                                                                                                    | **argumentatie**                                                                                                                                                                 | **alternatieven**                       |
|-------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------|
| NEMA17 stappenmotor (x-as motor en y-as motor)  ![](./../media/3075d0183f21f6d678d126157a2e12f5.png) |  Stap hoek: 1.8° Nominale stroom: 1.2A As diameter: 5mm                                                                                                              | We hebben deze stappen motor gekozen omdat deze al gebruikt in het project.                                                                                                      | niet van toepassing                     |
| TB6612  (stepper motor driver)                                                                  |  Motoren aansturen tussen 4.5V en 13.5V                                                                                                                              | Hieraan moet nog verder gewerkt worden.                                                                                                                                          | Hieraan moet nog verder gewerkt worden. |
| ESP32-WROOM  ![](./../media/ac0117e4d3aecefba468f34e44683797.png)                                    |    ROM: 448 KB SRAM : 520 KB 802.11 b/g/n Wi-Fi connectiviteit Bluetooth 4.2 18 ADC channels 16 PWM channels Serial connectivieit:  4 x SPI 2 x I²C 2 x I²S 3 x UART | ESP32 is een zeer krachtig microcontroller. Het is ook geschikt om te communiceren met andere modules. Onze opdrachtgever gaf immers aan dat we deze component moeten gebruiken. | ESP8266, ESP12                          |

**![](./../media/e817d819f42b37b63bc887537f09c29e.png)**Volledige schema

*Figuur 13: volledige blokdiagram van Farmlab*

## [Elektrische schema](https://luytsm.github.io/iot-cursus/#/deliverables/analyse?id=elektrisch-schema)‘s

![](./../media/c799f9b31a59bfafe9d40080f9b4a947.png)![](./../media/6a781ec30c85b524383ceb6cdc662392.png)Ledlevel
controller schema

*Figuur 14: elektrisch schema van led level controller*

Lichtsensor controller schema

![](./../media/072558bc03aa75f21625fc4a69e8f2b2.png)

*Figuur 15: elektrisch schema van lichtsensor controller*

Waterpomp schema

![](./../media/a2927026bb1c3747477c384b9edd07eb.png)

*Figuur 16: elektrisch schema van waterpomp*

Voedingspomp schema

![](./../media/5dc6e9af06a75a2fcd10c01ec9998d97.png)

*Figuur 17: elektrisch schema van voedingspomp*

![](./../media/2efaf401e8fc6889b3cd6e174c048b42.png)![](./../media/558b5fa8f6a5664a719a732d1cb38dfc.png)Motoren
schema

*Figuur 18: elektrisch schema van motoren*

## [**Smart Object (Software Analyse)**](https://luytsm.github.io/iot-cursus/#/deliverables/analyse?id=smart-object-hardware-analyse)

In dit deel van het project analyse gaan we de datamigratie en de datastomen
proberen te analyseren.

#### [Data in / Out](https://luytsm.github.io/iot-cursus/#/deliverables/analyse?id=data-in-out) (voorbeeld)

De volgende tabel toont de data-uitwisselingen van de verschillende componenten.

| **Blok**                                   | **Data In**                                                                               | **Data Uit**                                                                                              |
|--------------------------------------------|-------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------|
| Raspberry Pi                               | MQTT-berichten ontvangen met MQTT-broker                                                  | MQTT-berichten verzenden via MQTT-broker                                                                  |
| led level controller                       | MQTT-berichten van Raspberry Pi                                                           | PWM-signaal naar de led lichten en MQTT-berichten naar de Raspberry Pi                                    |
| led lichten                                | PWM-signaal van led level controller                                                      | niet van toepassing                                                                                       |
| lichtsensor controller                     | MQTT-berichten van Raspberry Pi                                                           | MQTT-berichten naar de Raspberry Pi                                                                       |
| lichtsensoren                              | het licht                                                                                 | licht metingen doorsturen via I²C protocol naar de lichtsensor controller                                 |
| pH-, temperatuur- en waterlevel controller | pH-metingen, temperatuurmetingen en waterlevelmetingen en MQTT-berichten van Raspberry Pi | MQTT-berichten sturen naar Raspberry Pi                                                                   |
| pH sensor                                  | het voedingswater                                                                         | metingen van de pH-waarden via analoge signaal sturen naar de pH-, temperatuur- en waterlevel controller  |
| temperatuursensor                          | temperatuur van de omgeving                                                               | metingen van de temperatuur via analoge signaal sturen naar de pH-, temperatuur- en waterlevel controller |
| waterlevel sensor                          | het water en voedingswater                                                                | metingen van de waterlevel via analoge signaal sturen naar de pH-, temperatuur- en waterlevel controller  |
| Dashboard                                  | Json data of MQTT-berichten                                                               | MQTT-berichten naar de Raspberry Pi                                                                       |
| Pomp controller                            | MQTT-berichten                                                                            | PWM-signaal naar de waterpomp en naar de voedingspomp                                                     |
| waterpomp                                  | PWM-signaal                                                                               | niet van toepassing                                                                                       |
| voedingspomp                               | PWM-signaal                                                                               | niet van toepassing                                                                                       |
| camera                                     | MQTT-berichten                                                                            | MQTT-berichten naar Motor en camera driver                                                                |
| Motor en camera driver                     | MQTT-berichten                                                                            | PWM-signaal naar de x-as motor en y-as motor en MQTT-berichten naar de camera                             |
| x-as motor                                 | PWM-signaal                                                                               | niet van toepassing                                                                                       |
| y-as motor                                 | PWM-signaal                                                                               | niet van toepassing                                                                                       |

Flowchart

Hieronder vindt u de flowchart van Farmlab.

*![](./../media/0339f80520174d0249b8fee74c4534bd.png)*

*Figuur 19: flowchart van farmlab*

# Beschrijving van de mogelijke interfaces <a id="interfaces">

![](./../media/6cc2c9aa9907f3df9e52bfae0eba8b19.png)Om de verzamelde data weer te
geven en de componenten van Farmlab te besturen maken we gebruik van een
Node-RED interface. Deze interface is een webpagina. De communicatie tussen de
MQTT-broker die op de Raspberry Pi geïnstalleerd staat en webpagina, gebeurt met
behulp van MQTT-berichten. De volgende afbeelding geeft een beeld over hoe de
interface eruit zal zien.

*Figuur 20: interface voor Farmlab*

# Beschrijving van eventuele datamigratie <a id="datamigratie">

In het deel van software analyse kan men een beschrijving vinden over hoe de
datamigratie intern met elkaar gebeurt. Daarnaast wordt er geen externe data
geraadpleegd van de derde partij.

# Beschrijving van eventuele impact op de huidige infrastructuur <a id="infrastructuur">

De impact op de huidige infrastructuur zal niet enorm groot zijn. Uiteraard
zullen er wijzigingen aangebracht worden op het huidige systeem aangezien er
nieuwe componenten geïnstalleerd moeten worden. Die nieuwe componenten zijn in
het deel van de hardware analyse besproken.

# Analyse van security en eventuele autorisatierollen <a id="autorisatierollen">

De gebruiker van Farmlab moet alle data kunnen raadplegen. Ook al is onze data
niet zo zeer gevoelig, moeten we ervoor zorgen dat onze data beveiligd blijft.
Zoals al eerder aangekondigd, maken we gebruik van MQTT-communicatie. Deze
communicatie gebruikt TCP/IP protocollen om een betrouwbare verbinding te hebben
met de MQTT-broker. De controllers spreken enkel de MQTT-broker aan en blijven
van de andere controllers af. Hierdoor kan de MQTT-broker de berichten van alle
controllers ontvangen en dan aan de juiste controller doorsturen. Ook als een
nieuwe controller wil bijkomen, moet hij eerst een verbinding maken met
MQTT-broker. Om een verbinding te maken met de Raspberry Pi gecreëerde wifi, is
eerst een ssid en een wachtwoord noodzakelijk.

# Documentatie <a id="documentatie">

Als documentatie in code zorgen we ervoor dat er een commentaar bijstaat om de
functie van de code te verduidelijken. Bovendien zal er op het einde van het
IoT-project een handleiding ter beschikking gesteld worden, zodat de gebruiker
zijn weg kan vinden wanneer hij een probleem tegenkomt.

# Bronvermelding <a id="bronvermelding">

W.D.G.L.L.A.D. (z.d.). *Document*. GitHub. Geraadpleegd op 11 december 2021, van
[https://ap-it-gh.github.io/ssys21-docs-Farmlab/\#/README](https://ap-it-gh.github.io/ssys21-docs-labfarm/#/README)

*licht sensor*. (z.d.). [Foto]. Licht sensor.
<https://shop.mchobby.be/en/environnemental-press-temp-hum-gas/238--t-tsl2561-senseur-luxluminositelumiere-digital-3232100002388-adafruit.html>

*Led lichten*. (z.d.). [Foto]. Led.
<https://ledison-led-lights.co.uk/54watt-led-strip-light-5m-dual-colour-10-8w-meter.html>

VNG systems. (2019). *ESP8266* [Afbeelding].
<https://www.vngsystems.nl/ESP8266-ESP-12F-NodeMcu>

R.S. (z.d.). *Stepper motor* [Afbeelding].
<https://benl.rs-online.com/web/p/stepper-motors/8928732/?cm_mmc=BE-PLA-DS3A-_-google-_-CSS_BE_NL_Automation_%26_Control_Gear_Whoop-_-(BE:Whoop!)+Stepper+Motors-_-8928732&matchtype=&pla-334209672209&gclid=EAIaIQobChMIoZjgqpXc9AIVWJ3VCh2BdgchEAQYASABEgK7w_D_BwE&gclsrc=aw.ds>

Sain Smart. (2021). *Stepper motor driver* [Afbeelding].
<https://www.sainsmart.com/products/cnc-4-5a-micro-stepping-stepper-motor-driver>

Tinytronics. (z.d.). *ESP32 camera* [Afbeelding]. ESP32.
<https://www.tinytronics.nl/shop/nl/development-boards/microcontroller-boards/met-wi-fi/esp32-cam-wifi-en-bluetooth-board-met-ov2640-camera>

Amazon. (z.d.). *Water pomp* [Foto].
<https://www.amazon.nl/Peristaltische-Vloeistof-Chemische-Laboratorium-Bioengineering/dp/B09HGP3Z56/ref=asc_df_B09HGP3Z56/?tag=nlshogostdde-21&linkCode=df0&hvadid=534333884778&hvpos=&hvnetw=g&hvrand=7804092175412684042&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=1001021&hvtargid=pla-1462724910931&psc=1>

Node-RED. (z.d.). *Node-RED* [Foto].
<https://flows.nodered.org/node/node-red-dashboard>

Modulogy. (2021). *Temperatuur sensor* [Afbeelding].
<https://www.modulogy.com/en/products/mod-68-modulowo-humiditytemperature-i2c-explore-with-hih6130-2/>

KIWI electronics. (z.d.). *Water level sensor* [Afbeelding].
<https://www.kiwi-electronics.nl/nl/grove-water-level-sensor-10cm-voor-arduino-9912>

electronicscomp. (2021). *pH sensor* [Afbeelding].
<https://www.electronicscomp.com/analog-ph-sensor-kit-for-arduino>

Build native PowerPoint timelines online. (z.d.). Office Timeline Online.
Geraadpleegd op 15 december 2021, van
[https://online.officetimeline.com/app/\#/new-from-template](https://online.officetimeline.com/app/#/new-from-template)

Electronic, C. (2021). *Barwig Typ 04 0444 Laagspanning dompelpomp 600 l/h 6 m
\| Conrad.be*. Conrad. Geraadpleegd op 17 december 2021, van
<https://www.conrad.be/p/barwig-typ-04-0444-laagspanning-dompelpomp-600-lh-6-m-539090?WT.srch=1&gclid=EAIaIQobChMInMOvxrfr9AIVFuN3Ch3ebwEVEAQYAiABEgKBrPD_BwE&gclsrc=aw.ds&insert=8J&t=1&tid=13894944235_122657379817_pla-299684802862_pla-539090&utm_campaign=shopping-feed&utm_content=free-google-shopping-clicks&utm_medium=surfaces&utm_source=google&utm_term=539090&vat=true>

Santos, S. (2021, 17 augustus). *ESP32 Pinout Reference: Which GPIO pins should
you use?* Random Nerd Tutorials. Geraadpleegd op 17 december 2021, van
<https://randomnerdtutorials.com/esp32-pinout-reference-gpios/>

