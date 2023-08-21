# Ajokilsat

Tämä on Expolla toteutettu sovellus ajokilometrien keräämiseen.
Projektin tarkoitus on harjotella kännykkäsovelluksen ohjelmointia.
Expolla toteutettuna sovellus toimii Androidilla ja iOS:llä, mutta tähän menessä sovellusta on testattu vain Androidilla.

## Tietomallit
(*) = Pakollinen kenttä (muut ovat optionalisia)

### Trip (Matka) 
- `vehicle` - ajoneuvo, jolla matka tehtiin
- `dometerAtBegin`- matkamittarin lukema alussa
- `odometerAtEnd`- matkamittarin lukema lopussa
- `timestampAtEnd` - aikaleima matkan lopussa
- `description` - matkan kuvaus
- `track` - "jälki", johon talennetaan matkan GPS-koordinaatit 
 * Lista GPS-koordinateista ja alkaleimoista
 - `routedescription` - reitin kuvaus (tyyliin: "Turku-Raisio-Turku")

 ### Vehicle (Ajoneuvo)
 -`name` -nimi
 -`registrationNumber` - rekisterinumero
