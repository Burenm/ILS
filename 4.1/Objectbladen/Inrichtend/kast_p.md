## AREAALDATA.kast_p

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.1
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ 15 cm
* __Geometrie:__ Punt
* __Definitie:__ Object met een permanent karakter dat dient om iets in te bergen en te beschermen. __LET OP:__ OVL- en VRI-Kasten worden apart geadministreerd.


***

|KOLOM                             |TYPE          	       |DEFINITIE|
|------                            |----          	       |-----    |
|OBJECTID                          |OID(38,0,0)            |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; Nullable: False; Default: None|
|GLOBALID                          |GlobalID(38,0,0)       |PNH; Global Unique Identifier,  aangemaakt door ArcGIS; Nullable: False; Default: None|
|AD_ID                             |String(255,0,0)        |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; Nullable: False; Default: None|
|GISIB_ID                          |Integer(0,10,0)        |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; Nullable: True; Default: None|
|IDENTIFICATIE                     |String(255,0,0)        |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; Nullable: True; Default: None|
|VERWERKINGSSTATUS                 |String(255,0,0)        |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw|
|STATUS                            |String(10,0,0)         |BGT; BGT status van het object; keuzelijst [status]; Nullable: False; Default: bestaand|
|OBJECTBEGINTIJD                   |Date(8,0,0)            |PNH; Datum waarop het object bij de bronhouder is ontstaan; Nullable: True|
|OBJECTEINDTIJD                    |Date(8,0,0)            |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; Nullable: True|
|RELATIEVEHOOGTELIGGING            |SmallInteger(0,10,0)   |BGT; Aanduiding voor de relatieve hoogte van het object; Nullable: False; Default: 0|
|BEHEERDER                         |String(255,0,0)        |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None|
|ONDERHOUDER                       |String(255,0,0)        |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None|
|EIGENAAR                          |String(255,0,0)        |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None|
|BRONHOUDER                        |String(5,0,0)          |BGT; De bronhoudercode van het object; keuzelijst [bronhouder]; Nullable: False; Default: None|
|BGTPLUSTYPE                       |String(50,0,0)         |BGT; Nadere type omschrijving in de BGT; keuzelijst [typeKST]; Nullable: False; Default: None|
|TYPESPEC                          |String(255,0,0)        |PNH; Nadere typering van het object; keuzelijst [typeSpecKST]; Nullable: True; Default: None|
|DATALEVERANCIER                   |String(255,0,0)        |PNH; Leverancier van de data; Nullable: True; Default: None|
|ZIJDE                             |String(10,0,0)         |PNH; Zijde; keuzelijst [ZIJDE]; Nullable: True; Default: None|
|OMSCHRIJVING                      |String(255,0,0)        |PNH; Omschrijving; Nullable: True; Default: None|
|HECTOMETER                        |String(255,0,0)        |PNH; Hectometrering; Nullable: True; Default: None|
|FABRIKANT                         |String(255,0,0)        |PNH; Fabrikant; Nullable: True; Default: None|
|ENERGIELEVERANCIER                |String(255,0,0)        |PNH; Energieleverancier (opmerking: attribuut wordt nog niet gevuld); Nullable: True; Default: None|
|DATUMGARANTIE                     |Date(8,0,0)            |PNH; Datum en jaartal tot wanneer de garantie geldig is; Nullable: True; Default: None|
|DATUMPLAATSING                    |Date(8,0,0)            |PNH; Datum plaatsing; Nullable: True|
|SIMNUMMER                         |String(20,0,0)         |PNH; Nummer van de SIM kaart; Nullable: True; Default: None|
|RELHOOGTELIGGING                  |Integer(0,10,0)        |BGT; Aanduiding voor de relatieve hoogte van het object; Nullable: False; Default: 0|
|AANTALLUSSEN                      |String(255,0,0)        |PNH; Aantal lussen dat in het asfalt is aangelegd voor verkeertellingen; Nullable: True; Default: None|
|DATATRANSPORT                     |String(255,0,0)        |PNH; Manier van datatransport. Keuze uit:Vaste lijn (KPN lijn), GSM; Nullable: True; Default: None|
|GSMNUMMER                         |String(255,0,0)        |PNH; GSM nummer dat gekoppeld is aan de betreffende SIM kaart; Nullable: True; Default: None|
|TELPUNTCODE                       |String(255,0,0)        |PNH; Administratieve code om de ligging van de telkast/telpaal aan te duiden; Nullable: True; Default: None|
|NDW_CODE                          |String(255,0,0)        |PNH; Administratieve code van het NDW; Nullable: True; Default: None|
|VOEDING                           |String(255,0,0)        |PNH; Manier van energieverzorging. Keuze uit:220, Zonne-energie; Nullable: True; Default: None|
|MATERIAALTYPE                     |String(255,0,0)        |PNH; Type materiaal; keuzelijst [MATERIAALTYPE]; Nullable: True; Default: None|
|ADRES                             |String(255,0,0)        |PNH; FK naar adres_tbl; Nullable: True; Default: None|
|INNETWERK                         |String(255,0,0)        |PNH; FK naar utiliteitsNet_tbl; Nullable: True; Default: None|
|TRAJECT                           |String(255,0,0)        |PNH; FK naar traject_v; Nullable: True; Default: None|
|INONDERZOEK                       |String(1,0,0)          |BGT; Een aanduiding waarmee wordt aangegeven dat een onderzoek wordt uitgevoerd naar de juistheid van een of meer gegevens van het betreffende object: Ja/Nee; keuzelijst [jaNee]; Nullable: False; Default: N; Visible:No|
|TIJDSTIPREGISTRATIE               |Date(8,0,0)            |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen door de bronhouder. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|EINDREGISTRATIE                   |Date(8,0,0)            |BGT; Datum en tijdstip waarop deze instantie van het object niet meer geldig is bij de bronhouder. Wanneer deze waarde niet is ingevuld is de instantie nog geldig. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|LV_PUBLICATIEDATUM                |Date(8,0,0)            |BGT; Datum en tijdstip waarop deze instantie van het object is opgenomen in de Landelijke Voorziening. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|BERICHT_ID                        |String(128,0,0)        |BGT; Nummer van het bericht dat PNH heeft verzonden naar LV. Dit mag niet worden ingevuld door de aannemer; Nullable: True; Default: None; Visible:No|
|CREATED_USER                      |String(255,0,0)        |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None|
|CREATED_DATE                      |Date(8,0,0)            |PNH; Aanmaakdatum; Nullable: True|
|LAST_EDITED_USER                  |String(50,0,0)         |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None|
|LAST_EDITED_DATE                  |Date(8,0,0)            |PNH; Datum van de laatste mutatie; Nullable: True|
|SHAPE                             |Geometry(0,0,0)        |PNH; Punt|


***
