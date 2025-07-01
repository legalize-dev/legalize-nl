---
title: "Regeling van de Staatssecretaris van Infrastructuur en Waterstaat, van 3 juni 2025, nr. IENW/BSK-2025/130201, houdende regels met betrekking tot de centrale database taxivervoer (Regeling centrale database taxivervoer) [KetenID WGK026754]"
identifier: "BWBR0051129"
country: "nl"
rank: "ministeriele_regeling"
publication_date: "2025-07-01"
last_updated: "2025-07-01"
status: "in_force"
source: "https://wetten.overheid.nl/BWBR0051129"
soort: "ministeriele-regeling"
stam_id: "17449233"
version_id: "30774072"
internal_id: "C44113781"
label_id: "17352174"
dtd_version: "2.0"
original_entry_into_force: "2025-07-01"
toestand_uri: "http://wetten.overheid.nl/id/BWBR0051129/2025-07-01/0"
intitule_bron: "Stcrt.2025-19143"
intitule_effect: "nieuwe-regeling"
intitule_signed: "2025-06-03"
intitule_published: "2025-06-20"
intitule_in_force: "2025-06-20"
intitule_status: "goed"
original_publication: "Stcrt.2025-19143"
original_signed_date: "2025-06-03"
original_published_date: "2025-06-20"
original_effect: "nieuwe-regeling"
original_url_id: "stcrt-2025-19143"
entry_into_force_date: "2025-07-01"
jci_1_3: "jci1.3:c:BWBR0051129&z=2025-07-01&g=2025-07-01"
jci_1_0: "1.0:c:BWBR0051129&g=2025-07-01"
citeertitel_status: "officieel"
short_title: "Regeling centrale database taxivervoer"
signed_date: "2025-06-03"
entry_into_force: "2025-07-01"
---
# Regeling van de Staatssecretaris van Infrastructuur en Waterstaat, van 3 juni 2025, nr. IENW/BSK-2025/130201, houdende regels met betrekking tot de centrale database taxivervoer (Regeling centrale database taxivervoer) [KetenID WGK026754]

Gelet op [artikel 83b, derde lid, van het Besluit personenvervoer 2000](https://wetten.overheid.nl/jci1.3:c:BWBR0011982&artikel=83b);

BESLUIT:

#### § 1. Begripsbepalingen

##### Artikel 1

In deze regeling wordt verstaan onder:

- **Besluit:** [Besluit personenvervoer 2000](https://wetten.overheid.nl/jci1.3:c:BWBR0011982);

- **centrale applicatie:** applicatie die taxivervoergegevens ontvangt van een of meerdere registratiemiddelen en deze aanlevert aan de CDT via de CDT meldingen API;

- **CDT:** centrale database taxivervoer;

- **CDT Meldingen API:** voorziening voor het uitwisselen van taxivervoergegevens tussen een centrale applicatie en de CDT;

- **gebeurtenis:** voorval dat plaatsvindt binnen het registratiemiddel, zijnde een melding, fout of storing;

- **ICT-oplossing:** het geheel aan digitale technieken en processen voor het registreren van taxivervoergegevens en het aanleveren van deze gegevens aan de CDT;

- **pauze:** een periode van tenminste 15 achtereenvolgende minuten waarin de bestuurder geen werkzaamheden verricht en vrijelijk over zijn tijd kan beschikken;

- **taxivervoergegevens:** gegevens als bedoeld in [artikel 83b, tweede lid, van het Besluit](https://wetten.overheid.nl/jci1.3:c:BWBR0011982&artikel=83b);

- **twee factor authenticatie:** methode waarbij de identiteit van een persoon wordt vastgesteld op basis van twee verschillende factoren.

#### § 2. Registratie en aanlevering van taxivervoergegevens

##### Artikel 2. (Registreren en aanleveren van taxivervoergegevens)

1. De centrale applicatie waarvan de vervoerder gebruik maakt, wordt aangesloten op de CDT als het registratiemiddel en de centrale applicatie voldoen aan de in deze regeling opgenomen voorwaarden.

2. Via de CDT Meldingen API meldt de vervoerder van welke ICT-oplossing gebruik wordt gemaakt.

3. De bestuurder maakt gebruik van het registratiemiddel, dat ter beschikking is gesteld door de vervoerder, om taxivervoergegevens te registreren.

4. De taxivervoergegevens worden door het registratiemiddel geregistreerd en via de centrale applicatie realtime aangeleverd aan de CDT Meldingen API, tenzij sprake is van omstandigheden ten gevolge waarvan deze gegevens niet realtime kunnen worden geregistreerd of aangeleverd.

5. De omstandigheden waaronder taxivervoergegevens niet realtime kunnen worden aangeleverd, bedoeld in het vijfde lid, zijn beperkt tot:

- a. het niet beschikbaar zijn van de CDT Meldingen API als gevolg van technische problemen of onderhoud;

- b. een verstoring van de gegevensoverdracht tussen centrale applicatie en CDT Meldingen API.

6. De niet tijdig aangeleverde taxivervoergegevens, bedoeld in het vierde lid, worden onverwijld aangeleverd aan de CDT Meldingen API zodra de omstandigheden, bedoeld in het vijfde lid, zich niet meer voordoen.

7. Het registreren en aanleveren van taxivervoergegevens vindt plaats aan de hand van de beschrijving, bedoeld in de bijlage.

##### Artikel 3. (Zorgplichten vervoerder)

1. De vervoerder stelt aan de bestuurder een deugdelijk registratiemiddel ter beschikking.

2. De vervoerder draagt er zorg voor dat de bestuurder een registratie bijhoudt van de gegevens als genoemd in [artikel 83b, tweede lid, van het Besluit](https://wetten.overheid.nl/jci1.3:c:BWBR0011982&artikel=83b).

3. Indien het registratiemiddel ondeugdelijk, defect of verloren gegaan is, zorgt de vervoerder binnen drie werkdagen voor herstel of een vervangend registratiemiddel.

4. De vervoerder draagt er zorg voor dat de gegevens, als bedoeld in [artikel 7, zesde lid](https://wetten.overheid.nl/jci1.3:c:BWBR0051129&paragraaf=2&artikel=7&z=2025-07-01&g=2025-07-01), onverwijld en waarheidsgetrouw worden aangeleverd aan de CDT Meldingen API.

5. De vervoerder draagt er zorg voor dat de aanlevering aan de CDT Meldingen API zonder foutmeldingen en waarschuwingsberichten verloopt.

6. Als foutmeldingen of waarschuwingsberichten worden ontvangen, verhelpt de vervoerder onverwijld de oorzaken ervan.

##### Artikel 4. (Validatie van de bestuurder)

1. De vervoerder valideert de gegevens van de bestuurder bij de CDT Meldingen API voordat de bestuurder voor de eerste keer met het registratiemiddel taxivervoer verricht voor de vervoerder.

2. Validatie vindt plaats door het aanleveren van het chauffeursnummer en de rijbewijsgegevens van de bestuurder zoals omschreven in de bijlage.

3. De bestuurder is gevalideerd als:

- a. de rijbewijsgegevens van een geldig rijbewijs zijn;

- b. het chauffeursnummer van een geldige bevoegdheid taxivervoer is; en

- c. het chauffeursnummer en het rijbewijs van dezelfde persoon zijn.

4. Een niet-gevalideerde bestuurder mag geen taxivervoer voor een vervoerder verrichten, tenzij de CDT Meldingen API niet beschikbaar is ten tijde van de validatiepoging.

5. Als sprake is van een situatie als bedoeld in het vierde lid, valideert de vervoerder de gegevens als bedoeld in het tweede lid, onverwijld, zodra de CDT Meldingen API weer beschikbaar is.

6. Als de bestuurder niet in het bezit is van een Nederlands rijbewijs, maar van een niet-Nederlands rijbewijs, valideert de vervoerder het chauffeursnummer van de bestuurder.

7. De bestuurder met een niet-Nederlands rijbewijs is gevalideerd als het chauffeursnummer van een geldige bevoegdheid taxivervoer is.

##### Artikel 5. (Validatie van de auto waarmee taxivervoer wordt verricht)

1. De vervoerder valideert een auto waarmee taxivervoer wordt verricht voordat deze voor de eerste keer voor de vervoerder met het registratiesysteem van de CDT wordt gebruikt en legt dit vast.

2. Validatie vindt plaats door het elektronisch valideren van het kentekenbewijs.

3. In een niet door de vervoerder gevalideerde auto waarmee taxivervoer wordt verricht, wordt door een bestuurder geen taxivervoer verricht.

##### Artikel 6. (Aanmelden van de bestuurder)

1. Bij aanvang van de werkzaamheden aan boord van een auto waarmee taxivervoer wordt verricht meldt de bestuurder zich aan op het registratiemiddel.

2. De bestuurder die in het bezit is van een Nederlands rijbewijs meldt zich aan door zijn Nederlands rijbewijs elektronisch te authentiseren op het registratiemiddel.

3. Als het Nederlands rijbewijs defect is, meldt de bestuurder zich gedurende een periode van maximaal tien aaneengesloten dagen aan door middel van twee factor authenticatie.

4. De bestuurder die niet in het bezit is van een Nederlands rijbewijs en wel in het bezit is van een niet-Nederlands rijbewijs meldt zich aan door middel van twee factor authenticatie.

5. Zonder aanmelden is het een bestuurder niet toegestaan om taxivervoer te verrichten.

##### Artikel 7. (Gebruik van het registratiemiddel door de bestuurder)

1. Indien de bestuurder, voorafgaand aan de melding, bedoeld in [artikel 6, eerste lid](https://wetten.overheid.nl/jci1.3:c:BWBR0051129&paragraaf=2&artikel=6&z=2025-07-01&g=2025-07-01), andere werkzaamheden heeft verricht na zijn laatste afmelding als bedoeld in het zevende lid van dit artikel, registreert hij de begin- en eindtijden van de andere werkzaamheden bij de melding als bedoeld in [artikel 6, eerste lid](https://wetten.overheid.nl/jci1.3:c:BWBR0051129&paragraaf=2&artikel=6&z=2025-07-01&g=2025-07-01).

2. De bestuurder meldt een rit aan op het registratiemiddel op het moment dat het vervoeren van personen aanvangt.

3. De bestuurder meldt een rit af op het registratiemiddel op het moment dat het vervoeren van personen is beëindigd.

4. Ingeval het registratiemiddel niet gekoppeld is aan de taxameter, bedoeld in [artikel 78 van het Besluit personenvervoer 2000](https://wetten.overheid.nl/jci1.3:c:BWBR0011982&artikel=78), voert de bestuurder handmatig de door de taxameter aangegeven totaalprijs in. Als voor het vervoer geen taxameter verplicht is en de volledige ritprijs direct na de rit wordt voldaan voert de bestuurder de door de reiziger verschuldigde vergoeding in.

5. Gedurende de periode dat er geen registratiemiddel beschikbaar is, als genoemd in [artikel 3, derde lid](https://wetten.overheid.nl/jci1.3:c:BWBR0051129&paragraaf=2&artikel=3&z=2025-07-01&g=2025-07-01), registreert de bestuurder zijn taxivervoersgegevens op een andere inzichtelijke en controleerbare wijze.

6. De bestuurder levert de registratie, genoemd in het vijfde lid, uiterlijk de derde werkdag als bedoeld in [artikel 3, derde lid](https://wetten.overheid.nl/jci1.3:c:BWBR0051129&paragraaf=2&artikel=3&z=2025-07-01&g=2025-07-01), aan bij de vervoerder.

7. Bij beëindiging van de werkzaamheden aan boord van een auto waarmee taxivervoer wordt verricht meldt de bestuurder zich af op het registratiemiddel.

8. De bestuurder meldt op het moment dat deze plaats vinden op het registratiemiddel het begin en einde van pauzes die hij tijdens zijn werkzaamheden aan boord van een auto waarmee taxivervoer wordt verricht geniet.

#### § 3. Techniek

##### Artikel 8. (Registratiemiddel)

1. Het registratiemiddel bevat of heeft de volgende eigenschappen:

- a. een bewegingsdetectie van het registratiemiddel;

- b. een locatiebepaling met een nauwkeurigheid van ten minste 25 meter;

- c. de functionaliteit om de laatst bekende locatie vast te houden;

- d. de functionaliteit om op basis van de locatiebepaling een afgelegde afstand te bepalen met een maximale afwijking van 15%;

- e. een tijdsbepaling met een nauwkeurigheid van ten minste 1 seconde en synchronisatie met een geijkte externe tijdfunctie;

- f. voorzieningen om de bestuurder te authentiseren als genoemd in [artikel 6](https://wetten.overheid.nl/jci1.3:c:BWBR0051129&paragraaf=2&artikel=6&z=2025-07-01&g=2025-07-01);

- g. de functionaliteit om unieke identificatiecodes van diensten, ritten, pauzes en gebeurtenissen te genereren;

- h. de functionaliteit om diensten, verrichtingen en andere werkzaamheden als genoemd in [artikel 83b, tweede lid, onderdeel l van het Besluit](https://wetten.overheid.nl/jci1.3:c:BWBR0011982&artikel=83b), aan en af te melden via de centrale applicatie;

- i. voorzieningen die taxivervoergegevens realtime doorsturen naar de centrale applicatie;

- j. voorzieningen die ervoor zorgen dat er geen taxivervoergegevens verloren kunnen gaan;

- k. de functionaliteit voor de bestuurder om alleen auto's te kunnen opgeven die de vervoerder voor hem heeft toegestaan;

- l. de functionaliteit voor de bestuurder om zich aan te kunnen melden voor vervoerders die hem dat toestaan.

2. Het is niet toegestaan het registratiemiddel op een wijze te gebruiken die maakt dat taxivervoergegevens kunnen worden gewijzigd of verwijderd voordat deze zijn aangeleverd in de CDT.

##### Artikel 9. (Centrale applicatie)

1. Het aanleveren van taxivervoergegevens vanaf het registratiemiddel aan de CDT vindt plaats via een centrale applicatie.

2. De centrale applicatie bevat of heeft de volgende eigenschappen:

- a. een functionaliteit om alle ontvangen gegevens direct en ongewijzigd door te sturen naar de CDT Meldingen API;

- b. een functionaliteit die ervoor zorgt dat berichten in chronologische volgorde van registratie tijdens de werkzaamheden aan boord van de auto waarmee taxivervoer wordt verricht worden aangeboden aan de CDT Meldingen API;

- c. een functionaliteit die maakt dat een volgend bericht aan de CDT Meldingen API pas wordt aangeboden als het voorgaande bericht succesvol is verwerkt.

##### Artikel 10. (Informatiebeveiliging)

1. De vervoerder maakt gebruik van een ICT-oplossing en een organisatie die zijn gecertificeerd voor ISO 27001. De certificatie wordt verricht door een certificerende instelling die is geaccrediteerd door de Raad voor Accreditatie of een andere accreditatie instelling die is erkend in een lidstaat van de Europese Unie.

2. De certificering, bedoeld in het eerste lid, heeft als werkingsgebied alle functionaliteit die gegevens levert aan de CDT Meldingen API. De functionaliteit omvat ten minste alle registratiemiddelen en de centrale applicatie.

#### § 4. Overgangs- en slotbepalingen

##### Artikel 11. (Inwerkingtreding)

Deze regeling treedt in werking met ingang van 1 juli 2025.

##### Artikel 12. (Citeertitel)

Deze regeling wordt aangehaald als: Regeling centrale database taxivervoer.

## Bijlage. Technische beschrijving van de berichtenuitwisseling voor het aanleveren van taxivervoergegevens aan de CDT Meldingen API (koppelvlakspecificatie CDT)

(bijlage als bedoeld in [artikel 2, zevende lid, van de Regeling centrale database taxivervoer](https://wetten.overheid.nl/jci1.3:c:BWBR0051129&paragraaf=2&artikel=2&z=2025-07-01&g=2025-07-01))

### 1. Inleiding

Deze koppelvlakspecificatie geeft een beschrijving van de volgende functies van de CDT-Meldingen-API:

### 1.1. Context

De chauffeur maakt gebruik van een Registratiemiddel Chauffeur om realtime relevante informatie over de uitvoering van taxivervoer te registreren voor de ondernemer in de centrale applicatie, die de gegevens realtime levert aan de CDT. Voor de uitwisseling van berichten met de ILT is de CDT-Meldingen-API (op basis van REST) ontwikkeld die aangeroepen dient te worden door de Centrale Applicatie.

### 1.2. Doel

Dit document is een bijlage bij de Regeling CDT. Het doel van dit document is om aan partijen die gebruik willen maken van de CDT Meldingen API inzicht te verschaffen in de functies en werking van de CDT-Meldingen-API.

### 2. Processen

In deze koppelvlakspecificatie wordt de term ‘dienst’ gebruikt zoals dat in het dagelijks spraakgebruik wordt gedaan. De betekenis van dienst in dit document is daardoor niet de definitie van Dienst in [art 1.7 eerste lid onder c van de Arbeidstijdenwet](https://wetten.overheid.nl/jci1.3:c:BWBR0007671&artikel=1:7). Met ‘dienst’ wordt in deze koppelvlakspecificatie ‘de werkzaamheden als taxichauffeur aan boord van de auto waarmee taxivervoer wordt verricht’ bedoeld.

De volgende processen zijn in scope voor de aanlevering bij de CDT:

### 2.1. Aanmelden dienst (relateren chauffeur, ondernemer en voertuig)

De ondernemer heeft ervoor gezorgd dat:

De chauffeur:

De aanmelding van de dienst is geregistreerd voor de chauffeur, het voertuig en de ondernemer in de centrale applicatie en in de CDT. De optionele aanmelding van de andere werkzaamheden is geregistreerd voor de chauffeur.

### 2.2. Aanmelden rit en aanmelden pauze

De aanmelding van de rit of pauze is geregistreerd binnen de dienst van de chauffeur in de centrale applicatie en de CDT.

### 2.3. Afmelden rit en afmelden pauze

De rit of pauze is geregistreerd in de centrale applicatie en de CDT.

De afmelding van de rit of pauze is geregistreerd binnen de dienst voor de chauffeur en de ondernemer in de centrale applicatie en de CDT.

### 2.4. Afmelden dienst

De dienst is geregistreerd en alle ritten en pauzes binnen de dienst zijn afgemeld in de centrale applicatie en de CDT.

De chauffeur meldt via het registratiemiddel chauffeur de dienst af bij de centrale applicatie, die vervolgens de dienst onmiddellijk afmeldt bij de CDT-Meldingen-API.

De afmelding van de dienst is geregistreerd in de centrale applicatie en de CDT.

### 2.5. Aanmelden ICT-dienstverlener

De ondernemer neemt een ICT-oplossing af bij de ICT-dienstverlener en heeft de ICT-dienstverlener niet aangemeld bij de CDT Meldingen API.

De centrale applicatie stuurt de aanmelding van de ondernemer voor de ICT-dienstverlener naar de CDT Meldingen API.

De ICT-dienstverlener is door de ondernemer aangemeld bij de CDT Meldingen API.

### 2.6. Afmelden ICT-dienstverlener

De ondernemer is gestopt met het afnemen van de ICT-oplossing van de ICT-dienstverlener en;

De ICT-dienstverlener is door de ondernemer aangemeld bij de CDT Meldingen API.

De centrale applicatie stuurt de afmelding van de ondernemer voor de ICT-dienstverlener naar de CDT Meldingen API.

De ICT-dienstverlener is door de ondernemer afgemeld bij de CDT Meldingen API.

### 2.7. Valideren van chauffeur

Ondernemer beschikt niet over de informatie of een chauffeur bevoegd is.

Ondernemer valideert via de Centrale applicatie de chauffeursgegevens bij de CDT.

NB: alleen bij validatiecode 0 worden de chauffeursgegevens als gevalideerd beschouwd.

Ondernemer beschikt over de informatie of de opgegeven chauffeursgegevens van een bevoegde chauffeur zijn.

### 2.8. Opvragen van openstaande diensten en verrichtingen

Centrale applicatie beschikt niet over de informatie welke diensten en verrichtingen langer dan een opgegeven duur open staan in de CDT.

Centrale applicatie vraagt diensten en verrichtingen op die langer dan een gespecificeerde tijdsduur (minimaal 24 uur) openstaan bij de CDT.

Centrale applicatie beschikt over de informatie met betrekking tot welke diensten en verrichtingen langer dan de gespecificeerde tijdsduur open staan in de CDT.

### 2.9. Melden van gebeurtenissen van het registratiemiddel chauffeur

Gebeurtenissen van het registratiemiddel chauffeur zijn meldingen (M). Een nadere toelichting hierop is te vinden in paragraaf 3.14 van dit document.

De dienst waaraan de gebeurtenis is gerelateerd, is aangemeld en geregistreerd in de centrale applicatie en de CDT.

Het registratiemiddel chauffeur meldt de gebeurtenis bij de centrale applicatie, die vervolgens de gebeurtenis onmiddellijk meldt bij de CDT-Meldingen-API.

De gebeurtenis is geregistreerd in de centrale applicatie en de CDT.

### 2.10. Opvragen chauffeursnummer

Het chauffeursnummer staat niet vermeld op de beschikking bij chauffeurskaarten die zijn uitgegeven voor 2025. Om het chauffeursnummer te achterhalen kan op basis van de gegevens van een Nederlands rijbewijs het chauffeursnummer opgevraagd worden bij de CDT Meldingen API.

Chauffeur en ondernemer beschikken niet over het chauffeursnummer en chauffeur heeft een geldig Nederlands rijbewijs en zijn BSN is geregistreerd bij Kiwa.

Ondernemer vraagt op basis van het Nederlandse rijbewijs van de chauffeur het chauffeursnummer op bij de CDT.

Indien de chauffeur beschikt over een geldige taxibevoegdheid, levert de CDT het chauffeursnummer terug aan de ondernemer.

NB: voor chauffeurs die geen Nederlands rijbewijs hebben of die bij KIWA niet met een BSN geregistreerd zijn is het niet mogelijk het chauffeursnummer op basis van rijbewijsgegevens op te vragen. Deze chauffeurs ontvangen het chauffeursnummer per brief van KIWA, en dienen het chauffeursnummer door te geven aan de ondernemer.

### 3. Berichten

Berichten bestaan uit generieke berichtgegevens (metagegevens) en de inhoud van het bericht zelf. ILT heeft ervoor gekozen om de metagegevens als headers in het bericht op te nemen.

### 3.1. Statusovergangen

De logische samenhang tussen de berichten en de status van een dienst en verrichting is in onderstaande figuur weergegeven. De berichten ‘opvragen openstaande diensten’ en ‘valideren chauffeurs’ komen niet voor in onderstaand figuur omdat ze geen invloed hebben op de status van diensten en verrichtingen.

Regels:

### 3.2. Generieke berichtgegevens in headers

De velden in de onderstaande tabel staan de bericht header.

1 Softwareversie-Registratiemiddel mag een empty string zijn als het bericht niet afkomstig is van een ‘registratiemiddel chauffeur’.

### 3.3. Functionele berichtgegevens

De velden in de onderstaande tabel kunnen op een bericht voorkomen (in de message body), per bericht is beschreven welke van deze velden voorkomen. Daarnaast staan in paragrafen 3.3.1 tot en met 3.3.7 objecten die in berichten kunnen voorkomen.

**Regels**:

Naast de velden in bovenstaande tabel kunnen ook objecten worden verstuurd. Deze staan in de volgende paragrafen beschreven.

### 3.3.1. Chauffeur

Voorbeeld:

### 3.3.2. Rijbewijs

Voorbeeld:

### 3.3.3. Authenticatie

Voorbeelden:

### 3.3.4. Ondernemer

Voorbeeld:

### 3.3.5. Voertuig

Voorbeeld:

### 3.3.6. Andere werkzaamheden

Voorbeeld:

### 3.3.7. Locatie

Voorbeeld:

### 3.4. Aanmelden dienst (relateren chauffeur, ondernemer en voertuig)

Use cases:

**Endpoint**: POST [https://[host]/v2/diensten](https://[host]/v2/diensten)

Bij aanmelden dienst bevat het bericht naast alle generieke berichtgegevens de volgende functionele berichtgegevens:

**Response sunny day**: ‘201 CREATED’

Velden in de response body:

Meldingen in de onderstaande tabel zijn mogelijk bij een '201 CREATED' resultaatcode.

Bij een afwijzing zijn de meldingen te vinden in paragraaf 3.16.

**Response bij openstaande diensten:** ‘201 CREATED’

gegevens van openstaande dienst(en) bij de inzendende ICT-dienstverlener staan in de message body.

Velden in de response body:

### 3.5. Afmelden dienst

Use cases:

**Endpoint**: POST [https://[host]/v2/diensten/{dienst.id}/afmelden](https://[host]/v2/diensten/{dienst.id}/afmelden)

Bij afmelden dienst bevat het bericht naast de generieke berichtgegevens in de header de volgende functionele berichtgegevens in de message body:

**Response sunny day**: ‘200 OK’

Velden in de response body:

Indien foutcode DF05 (zie paragraaf 3.15) wordt teruggegeven is de response: ‘400’.

Bij overige afwijzing zijn de meldingen te vinden in paragraaf 3.16.

### 3.6. Aanmelden rit

Use cases:

**Endpoint**: POST [https://[host]/v2/diensten/{dienst.id}/ritten](https://[host]/v2/diensten/{dienst.id}/ritten)

Bij aanmelden rit bevat het bericht naast alle generieke berichtgegevens de volgende functionele berichtgegevens:

**Response sunny day**: ‘201 CREATED’

Velden in de response body:

Bij een afwijzing zijn de meldingen te vinden in paragraaf 3.16.

### 3.7. Afmelden rit

Use cases:

**Endpoint**: POST [https://[host]/v2/diensten/{dienst.id}/ritten/{rit.id}/afmelden](https://[host]/v2/diensten/{dienst.id}/ritten/{rit.id}/afmelden)

Bij afmelden rit bevat het bericht naast alle generieke berichtgegevens de volgende functionele berichtgegevens:

NB. Bij contractvervoer en groepsvervoer is de prijs niet verplicht. In dat geval mag ritprijs 0 (nul) zijn.

**Response sunny day**: ‘200 OK’

Velden in de response body:

Bij een afwijzing zijn de meldingen te vinden in paragraaf 3.16.

### 3.8. Aanmelden pauze

Use cases:

**Endpoint**: POST [https://[host]/v2/diensten/{dienst.id}/pauzes](https://[host]/v2/diensten/{dienst.id}/pauzes)

Bij aanmelden pauze bevat het bericht naast alle generieke berichtgegevens de volgende functionele berichtgegevens:

**Response sunny day**: '201 CREATED'

Velden in de response body:

Bij een afwijzing zijn de meldingen te vinden in paragraaf 3.16.

### 3.9. Afmelden pauze

Use cases:

**Endpoint**: POST [https://[host]/v2/diensten/{dienst.id}/pauzes/{pauze.id}/afmelden](https://[host]/v2/diensten/{dienst.id}/pauzes/{pauze.id}/afmelden)

Bij afmelden pauze bevat het bericht naast alle generieke berichtgegevens de volgende functionele berichtgegevens:

**Response sunny day**: ‘200 OK’

Velden in de response body:

Bij een afwijzing zijn de meldingen te vinden in paragraaf 3.16.

### 3.10. Aanmelden ICT-dienstverlener

Use case:

**Endpoint:** POST [https://[host]/v2/ondernemers/aanmelden](https://[host]/v2/ondernemers/aanmelden)

In de message body worden de gegeven van de meldende ondernemer doorgegeven.

**Response sunny day**: ‘200 OK’

Velden in de response body:

Bij een afwijzing zijn de meldingen te vinden in paragraaf 3.16.

### 3.11. Afmelden ICT-dienstverlener

Use case:

**Endpoint:** POST [https://[host]/v2/ondernemers/{ondernemer.kiwaNummer}/afmelden](https://[host]/v2/ondernemers/{ondernemer.kiwaNummer}/afmelden)

**Response sunny day**: ‘200 OK’

Er is geen message body aanwezig.

Als de ondernemer onbekend is bij de ICT-dienstverlener wordt als response ‘404 – not found’ gegeven.

Bij een afwijzing zijn de meldingen te vinden te vinden in paragraaf 3.16.

### 3.12. Valideren chauffeur

Use cases:

**Endpoint:** POST [https://[host]/v2/chauffeurs/valideren](https://[host]/v2/chauffeurs/valideren)

In de message body wordt de te valideren chauffeur opgegeven met zijn chauffeursnummer en Nederlandse rijbewijs, en de ondernemer die de validatie uitvoert.

NB: het chauffeursobject heeft het onderdeel ‘gevalideerd’. De waarde hiervan moet false zijn bij deze opvraging.

**Response sunny day**: ‘200 OK’

Velden in de response body:

Als op deze validatie de validatiecode 0 is geretourneerd mag bij aanmelden dienst voor deze chauffeur met chauffeur.chauffeursnummer en chauffeur.rijbewijs.nummer chauffeur.gevalideerd op true worden gezet. Alle voorgaande gebruikte combinaties van chauffeur.chauffeursnummer met chauffeur.rijbewijs.nummer gelden vanaf dat moment niet meer als gevalideerd.

Bij een afwijzing zijn de meldingen te vinden in paragraaf 3.16.

### 3.13. Opvragen van openstaande diensten en verrichtingen

Use case:

Endpoint:

GET [https://[host]/v2/diensten/openstaand?ouderdan=24](https://[host]/v2/diensten/openstaand?ouderdan=24)

Deze aanvraag heeft geen message body.

Geeft alle niet-afgemelde diensten met eventueel niet-afgemelde verrichtingen met een aanmeldtijdstip langer dan x uur geleden voor ICT-dienstverlener Y, waarbij x een defaultwaarde heeft van 24, dus als ouderdan wordt weggelaten wordt 24 gebruikt. Een lagere waarde dan 24 wordt genegeerd, in plaats daarvan wordt 24 gebruikt.

Headers: Softwareversie-Registratiemiddel mag leeg (empty string) zijn indien de opvraging afkomstig is van centrale applicatie.

**Response sunny day**: ‘200 OK’

Velden in de response body:

Als er geen openstaande diensten zijn dan krijgt de aanroep een ‘204 No Content’ response zonder message body.

### 3.14. Melden van gebeurtenissen van het registratiemiddel chauffeur

Use case:

Endpoint: (alle gebeurtenissen worden als dienstgebonden beschouwd)

POST [https://[host]/v2/diensten/{dienstId}/gebeurtenissen](https://[host]/v2/diensten/{dienstId}/gebeurtenissen)

Velden:

1 zie tabel hieronder wanneer dit veld verplicht is.

De codes voor Meldingen zijn verplicht.

1 Melding doorgeven na de eerstvolgende geslaagde aanmelding dienst op het registratiemiddel chauffeur

2 Melding is normaliter afkomstig van de Centrale Applicatie.

NB: bij M101 en M104 dient het gebeurtenistijdstip het tijdstip te zijn waarop de fout voor het eerst is geconstateerd en het registratietijdstip het tijdstip waarop de fout is gemeld vanuit het detecterende apparaat.

**Response sunny day**: ‘201 OK’

Velden in de response body:

Bij een afwijzing zijn de meldingen te vinden in paragraaf 3.16.

### 3.15. Opvragen chauffeursnummer

Use case:

Endpoint:

POST [https://[host]/v2/chauffeursnummer/opvragen](https://[host]/v2/chauffeursnummer/opvragen)

Indien voor het opgegeven Nederlandse rijbewijs het chauffeursnummer kan worden gevonden wordt dit teruggegeven. Indien een niet-Nederlands rijbewijs wordt opgegeven zal geen chauffeursnummer worden gevonden.

Headers: Softwareversie-Registratiemiddel mag leeg (empty string) zijn indien de opvraging afkomstig is van centrale applicatie.

Velden:

**Response als gevonden**: ‘200 OK’

Velden in de response body:

Bij een afwijzing of geen gevonden resultaat zijn de meldingen te vinden in paragraaf 3.16.

### 3.16. Foutmeldingscodes

De CDT Meldingen API kent de onderstaande foutmeldingscodes. Bij iedere errorcode is de http-status code weergegeven en op welke aanroepen deze kan komen.

Codering error codes:

Fouten worden teruggegeven in de response body in het onderstaande format:

### 3.16.1. Foutmeldingen wegens headers

De onderstaande meldingen kunnen op alle aanroepen worden teruggegeven:

NB: Door de manier waarop de validaties worden uitgevoerd komen de header-foutmeldingen alleen voor op berichten die geen andere foutmeldingen geven.

Gegevens meldingen:

NB: ‘Opvragen openstaande diensten’ en ‘afmelden ICT-dienstverlener’ zijn niet opgenomen in de tabellen omdat deze beide geen message body bevatten waarop de foutcodes betrekking hebben.

### 3.16.2. Foutmeldingen wegens fouten in het bericht zelf

### 3.16.3. Foutmeldingen wegens verwerken inhoud

1 Bij deze code wordt ook de betreffende verrichting(en) teruggegeven in de response.

### 4. Technische eisen

### 4.1. Conventies

### 4.1.1. JSON conventies

De Centrale applicatie dient de berichten aan te bieden aan de endpoints van CDT-Meldingen-API door middel van JSON (JavaScript Object Notation) berichten en REST (Representational State Transfer).

Voor een complete technische specificatie van de JSON berichten kan de OpenAPI-specificatie geraadpleegd worden, dit is REF-1.

Velden die geen waarde hebben worden weggelaten.

### 4.1.2. Encoding

De character-encoding standaard van de berichten is UTF-8.

### 4.1.3. Hoofdlettergevoeligheid

De backend service CDT is WEL hoofdlettergevoelig.

### 4.1.4. Datum/tijd

Voor datum en tijd wordt IETF RFC 3339 standaard gehanteerd, specifiek de specificatie van de ‘date-time’ waarde. Alle tijdstippen zijn in UTC.

### 4.1.5. Berichtenverkeer

Het berichtenverkeer wordt synchroon afgehandeld. Indien er sprake is van een time-out dient de Centrale applicatie het bericht opnieuw aan te bieden. Een transactie is pas afgerond als een response is ontvangen.

De aanroeper van een transactie dient minimaal 15 seconden te wachten voordat de transactie als timed-out mag worden beschouwd.

### 4.1.6. Endpoints

Alle endpoints zijn gespecifieerd in de OpenAPI specificatie [REF-1].

### 4.2. Actualiteit van data

Berichten dienen zonder vertraging aangeleverd te worden aan de backend service CDT. Elk bericht bevat twee tijdstempels: het moment waarop het feit heeft plaatsgevonden (aanmeldtijdstip of afmeldtijdstip) en het moment waarop het bericht over deze actie wordt aangemaakt (registratietijdstip). In de header ‘verzendtijdstip’ staat het tijdstip waarop de centrale applicatie de aanroep naar de CDT Meldingen API doet.

De ICT-dienstverlener is ervoor verantwoordelijk dat berichten op chronologische volgorde van **registratietijdstip** worden aangeleverd.

### 4.3. Beschikbaarheid en performance

### 4.3.1. Beschikbaarheid

De API heeft een gegarandeerde beschikbaarheid van 98%.

### 4.3.2. Performance

De streeftijd voor het afhandelen van een bericht is < 2 seconden.

### 5. Logging en monitoring verbinding

### 5.1. Logging

Voor beheerdoeleinden verwacht ILT dat de ICT-dienstverlener alle transacties op de CDT-Meldingen-API logt, inclusief de response van ILT. Deze gegevens dienen minimaal 1 maand te worden bewaard.

### 5.2. Connectie-monitoring

Om te monitoren of verbinding tussen de ICT-dienstverlener en ILT mogelijk is, stuurt de ICT-dienstverlener als er langer dan 60 seconden geen andere melding is gestuurd een GET naar [https://[host]/v2/verbinding](https://[host]/v2/verbinding), waarop ILT een 200 OK zal terugsturen als teken dat de verbinding tot stand is gekomen. Op deze manier kunnen de beheerorganisaties van beide partijen monitoren of de connectie in orde is.

NB: indien de aanroep naar dit endpoint niet slaagt mogen andere transacties niet worden aangeroepen totdat deze aanroep weer slaagt.

### 6. Foutafhandeling

Het kan gebeuren dat er fouten optreden in één of meer berichten. Dit hoofdstuk beschrijft wat in welk geval moet gebeuren.

### 6.1. Algemeen

Als een bericht met betrekking op een dienst wordt afgewezen dienen berichten voor dezelfde dienst, die chronologisch na dat bericht moeten worden verstuurd, te worden vastgehouden totdat het afgewezen bericht (al dan niet gecorrigeerd) succesvol door de CDT-Meldingen-API is verwerkt.

Als het **/verbinding-endpoint** een 500-error geeft is er naar alle waarschijnlijkheid sprake van een verbindingsfout. Er dienen dan geen andere berichten verstuurd te worden naar de CDT Meldingen API en dient er in plaats hiervan iedere minuut een nieuwe oproep naar **/verbinding** gedaan te worden totdat deze oproep slaagt. Hierna kan het verzenden van de andere berichten weer hervat worden.

### 6.2. Error in aanroep dienstgerelateerde endpoints

Als in één van de aanroepen een foutsituatie optreedt dan worden acties aanbevolen zoals hieronder in de tabel beschreven.

### 6.3. Error in aanroep /verbinding

Het /verbinding endpoint wordt gebruikt om te controleren of de CDT Meldingen API operationeel is. Dit is een apart geval en is daarom apart behandeld. Als er andere berichten naar de CDT Meldingen API worden verstuurd dient het /verbinding endpoint niet aangeroepen te worden.

### 6.4. Duplicaat detectie

Er is geen duplicaat-detectie, een bericht dat voor de tweede keer wordt aangeboden wordt functioneel afgewezen.

### 7. Authenticatie en informatiebeveiliging

### 7.1. Authenticatie

### 7.1.1. PKI Certificaten

De informatie-uitwisseling met de CDT meldingen-API verloopt via de centrale API Security gateway van de ILT waarop alle ICT-dienstverleners aangesloten dienen te worden. Authenticatie door de ICT-dienstverleners vindt plaats met behulp van PKI overheid servercertificaten en clientcertificaten bij de ICT-dienstverlener. Voor meer informatie zie de website van Logius.

### 7.1.2. Authenticatie rijbewijs

Bij iedere dienst die wordt gestart dient het Nederlandse rijbewijs van de chauffeur elektronisch te worden geauthenticeerd via NFC. Dit wordt gedaan door de ‘Active Authentication’ van het rijbewijs uit te voeren zoals beschreven in [REF-2]. Als dit met succes is uitgevoerd wordt op het aanmelden dienst-bericht het authenticatie-object gevuld met authenticatie.middel: ‘RBNL’ en authenticatie.kenmerk: het uitgelezen rijbewijsnummer. Als de chauffeur niet beschikt over een Nederlands rijbewijs dient op één van de overige wijzen geauthenticeerd te worden. Deze zijn beschreven in paragraaf 3.3.3.

NB: voor het uitlezen van de specimen rijbewijzen die beschikbaar zijn dient u gebruik te maken van aparte certificaten die niet op de website van de RDW beschikbaar zijn. Deze kunt u verkrijgen bij de aansluitcoördinatoren van de ILT.

### 7.1.3. Authenticatie kentekenbewijs

Bij het aanmelden van een voertuig voor een vervoerder dient het kentekenbewijs van het voertuig te worden geauthenticeerd middels de ‘Active Authentication’ zoals beschreven in [REF-3]. Hierbij wordt het kenteken van het voertuig uitgelezen middels een smartcard-lezer. Hierna mag het kenteken worden gebruikt voor diensten en ritten van deze vervoerder.

Het is mogelijk dat een voertuig door verschillende vervoerders wordt gebruikt, voor iedere vervoerder dient het kentekenbewijs éénmalig te worden geauthenticeerd voor het in gebruik nemen van het voertuig.

NB: voor het uitlezen van de specimen kentekenbewijzen die beschikbaar zijn dient u gebruik te maken van aparte certificaten die niet op de website van de RDW beschikbaar zijn. Deze kunt u verkrijgen bij de aansluitcoördinatoren van de ILT.

### 7.2. Informatiebeveiliging

De informatie-uitwisseling gaat van de aanleverende ICT-dienstverleners via het openbare internet naar de beveiligde API-gateway. Alleen vooraf vrijgegeven IP-adressen kunnen berichten hierop aanbieden. De gateway bevindt zich binnen de overheidsinfrastructuur.

### 7.2.1. Transport Layer Security (TLS)

Het verkeer vindt plaats over TLS met certificaten aan verzendende en ontvangende zijde. Hiervoor wordt gebruik gemaakt van de actuele standaarden zoals voorgeschreven door Forum Standaardisatie. De certificaten aan ontvangende zijde zijn van de Certificate Authority (CA) van de Rijksoverheid, de certificaten aan verzendende zijde moeten van een publieke CA zijn; de meeste CA's zijn bij de Rijksoverheid bekend en worden geaccepteerd. Mocht er twijfel zijn over een CA neemt u dan contact op de ILT. De meest actuele richtlijnen zijn door het NCSC beschreven in het document ICT-beveiligingsrichtlijnen voor Transport Layer Security (TLS) v2.1.

NB: de acceptatie-omgeving wijkt af van de productieomgeving: in de acceptatieomgeving is geen client-certificaat vereist.

### 7.2.2. API-keys

De ILT geeft per ICT-dienstverlener een API-key (ext_key-header) uit, de ICT-dienstverlener gebruikt de API-key om zich bij de ILT API-gateway te identificeren.

### 7.3. Headers

De CDT-Meldingen API verwacht de volgende headers:

Zie ook paragraaf 3.2.

Deze regeling zal met de toelichting in de Staatscourant worden geplaatst.
