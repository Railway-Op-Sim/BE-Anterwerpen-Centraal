# Antwerpen Centraal Zuid

Representation of the rail network south of the Belgian city of Antwerp. Includes full timetable with all classifications
of service. This simulation is as close to reality as possible information permitting, with the track diagram around Antwerpen-Centraal being
modelled off of Seinhuis (signalling centre) screens. The included timetable depicts a typical weekday operation with
local S-train, intercity (IC) and Thalys services.

Antwerpen-Centraal station has three level labelled NIV (niveau) -2, -1 and +1 respectively. Care should be taken to
ensure that trains are routed correctly to reach the allocated station region.

## Simulation

The simulation includes the following principal stations:

- Antwerpen-Centaal (NIV -2, -1 and +1)
- Antwerpen-Berchem
- Antwerpen-Zuid
- Mortsel
- Mortsel-Oude-God
- Mortsel-Deernesteenweg
- Mortsel-Lieresteenweg
- Boechout
- Lier
- Hove
- Kontich-Lint
- Duffel
- Sint-Katelijne-Waver

### Tips

- Although Belgium has bidirectional line capability, as this is not required for the simulation you should never need to route services in a wrong movement.
- Make sure to route services from Antwerpen-Berchem west sidings correctly, there is only a single line across to NIV -1, -2
- Prioritise services with earlier departure times.

### Services
The following are the main services in operation, some additional `P` services are also present, these are peak time
additional services.

|**ID**|**Exit/Entry**|**Description**|
|---|---|---|
|IC04| Beveren (Waas)|**Antwerpen-Centraal**, **Antwerpen-Berchem**, Gent, Kortrijk, Poperinge/Lille (F)|
|IC05| Luchtbal/Mechelen | Essen, **Antwerpen-Central**, **Antwerpen-Berchem**, Brussel, Charleroi|
|IC07| Mechelen | **Antwerpen-Centraal**, **Antwerpen-Berchem**, Mechelen, Brussel, Charleroi|
|IC08| Mechelen | **Antwerpen-Centraal**, **Antwerpen-Berchem**, Mechelen, Brussels Airport, Hasselt|
|IC09|  Berlaar | **Antwerpen-Centraal**, **Antwerpen-Berchem**, **Lier**, Aarschot, Leuven|
|IC10| Kessel | **Antwerpen-Centraal**, **Antwerpen-Berchem**, **Lier**, Herentals, Hamont/Hasselt|
|IC11| Mechelen/Kessel|  Binche, Brussel, Mechelen, **Lier**, Turnhout|
|IC22| Mechelen |  Brussel, Mechelen, **Antwerpen-Centraal**, **Antwerpen-Berchem** |
|IC30| Kessel | **Antwerpen-Centraal**, **Antwerpen-Berchem**, **Lier**, Herentals, Turnhout |
|IC31| Mechelen | Brussel, Mechelen, **Mortsel-Oude-God**, **Antwerpen-Berchem**, **Antwerpen-Centraal**|
|IC35| Luchtbal/Mechelen | Amsterdam (NL), **Antwerpen-Centraal**, **Antwerpen-Berchem**, Brussels Airport, Brussel|
|S1| Mechelen | **Antwerpen-Centraal**, **Antwerpen-Berchem**, **Mortsel**, **Mortsel-Lieresteenweg**, Mechelen, Brussel, Nijve|
|S32| Hoboken/Luchtbal | Puurs, **Antwerpen-Zuid**, **Antwerpen-Centraal**, Essen, Roosendaal|
|S33| Kessel | Mol, Herentals, **Lier**, **Boechout**, **Mortsel**, **Antwerpen-Berchem**, **Antwerpen-Centraal**|
|S34| Beveren (Waas) | Lokeren, **Antwerpen-Zuid**, **Antwerpen-Berchem**, **Antwerpen-Centraal**|
|Thalys 93| Mechelen/Luchtbal|Paris (F), **Antwerpen-Centraal**, Amsterdam (NL) |