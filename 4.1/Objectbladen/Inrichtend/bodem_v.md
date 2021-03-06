﻿## AREAALDATA.bodem_v

*Feature dataset: Inrichtend*


* __Areaaldata model versie:__ 4.1
* __BGT inhoud:__ Nee
* __Herkomst Definitie:__ PNH
* __Positionele nauwkeurigheid:__ 25 cm
* __SHAPE:__ Vlak
* __Definitie:__ Bodem van een waterdeel, hier worden de gegevens bijgehouden die van belang zijn voor o.a. baggeren


***

|KOLOM                               |TYPE                  |DEFINITIE|
|------                              |----                  |-----    |
|OBJECTID                            |OID(38,0,0)           |PNH; Intern ArcGIS Identificatienummer, aangemaakt door ArcGIS; Nullable: False; Default: None|
|GLOBALID                            |GlobalID(38,0,0)      |PNH; Global Unique Identifier,  aangemaakt door ArcGIS; Nullable: False; Default: None|
|AD_ID                               |String(255,0,0)       |PNH; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat in Areaaldata: in format 'AD.[GUID]'. Dit moet worden ingevuld door de aannemer; Nullable: False; Default: None|
|GISIB_ID                            |Integer(0,10,0)       |PNH; Uniek Identificatienummer beheer openbare ruimte (GISIB), wordt aangemaakt in GISIB en mag niet worden ingevuld door de aannemer; Nullable: True; Default: None|
|IDENTIFICATIE                       |String(255,0,0)       |BGT; Uniek identificatienummer voor het object dat onveranderlijk is zolang het object bestaat: bevat indien van toepassing BGT/IMKL ID in format 'nl.imgeo/imkl.bronhouderscode.LokaalID' of anders: '00000'.LokaalID; Nullable: True; Default: None|
|VERWERKINGSSTATUS                   |String(255,0,0)       |PNH; Status van de gegevens; keuzelijst [VERWERKINGSSTATUS]; Nullable: False; Default: Nieuw|
|OBJECTBEGINTIJD                     |Date(8,0,0)           |PNH; Datum waarop het object bij de bronhouder is ontstaan; Nullable: True|
|OBJECTEINDTIJD                      |Date(8,0,0)           |PNH; Datum waarop het object bij de bronhouder niet meer geldig is; Nullable: True|
|BEHEERDER                           |String(255,0,0)       |PNH; Beheerder van het object; keuzelijst [BEHEERDER]; Nullable: True; Default: None|
|ONDERHOUDER                         |String(255,0,0)       |PNH; Onderhouder van het object; keuzelijst [ONDERHOUDER]; Nullable: True; Default: None|
|EIGENAAR                            |String(255,0,0)       |PNH; Eigenaar van het object; keuzelijst [INSTANTIE]; Nullable: True; Default: None|
|DATALEVERANCIER                     |String(255,0,0)       |PNH; Leverancier van de data; Nullable: True; Default: None|
|TYPESPEC                            |String(255,0,0)       |PNH; Nadere typering van het object; keuzelijst [typeSpecBDM]; Nullable: True; Default: None|
|TYPEBAGGER                          |String(255,0,0)       |PNH; Type bagger; keuzelijst [TYPE_BAGGER]; Nullable: True; Default: None|
|BOVENKANTSLIB                       |Float(0,25,10)        |PNH; Is de diepte van de wateroppervlakte tot de bovenkant van het slib lichaam; Nullable: True; Default: None|
|OMSCHRIJVING                        |String(255,0,0)       |PNH; Extra toelichting; Nullable: True; Default: None|
|HMBEGIN                             |Float(0,25,10)        |PNH; Begin Hectometrering van Waterdeel; Nullable: True|
|HMEIND                              |Float(0,25,10)        |PNH; Eind Hectometrering van Waterdeel; Nullable: True|
|PEILJAAR                            |Date(8,0,0)           |PNH; Laatste jaar waarin gepeild is; Nullable: True; Default: None|
|JAAR_BAGGEREN                       |Date(8,0,0)           |PNH; Laatste jaar waarin gebaggerd is; Nullable: True; Default: None|
|JAAR_PLAATSING_AANLEG_GESCHAT       |String(1,0,0)         |PNH; Jaar plaatsing of aanleg is geschat: Ja/Nee; keuzelijst [jaNee]; Nullable: True; Default: N|
|ONDERKANTSLIB                       |Float(0,25,10)        |PNH; Is de diepte van de wateroppervlakte tot de onderkant van het slib lichaam; Nullable: True; Default: None|
|OPMERKING                           |String(255,0,0)       |PNH; Toevoeging van subjectieve informatie met betrekking tot opmerkelijke waarnemingen; Nullable: True; Default: None|
|VAARWEGDEELTRAJECT                  |String(255,0,0)       |PNH; FK naar vaarwegdeeltraject_v ; Nullable: True; Default: None|
|LENGTE                              |Float(0,25,10)        |PNH; Lengte van het bodemdeel in m; Nullable: True Default: None| Visible:Yes
|CREATED_USER                        |String(255,0,0)       |PNH; Naam van gebruiker die de rij heeft aangemaakt; Nullable: True; Default: None|
|CREATED_DATE                        |Date(8,0,0)           |PNH; Aanmaakdatum; Nullable: True|
|LAST_EDITED_USER                    |String(50,0,0)        |PNH; Naam van gebruiker die de laatste mutatie heeft doorgevoerd; Nullable: True; Default: None|
|LAST_EDITED_DATE                    |Date(8,0,0)           |PNH; Datum van de laatste mutatie; Nullable: True|
|SHAPE                               |Geometry              |PNH; Vlak|
|SHAPE_Length                        |Double(0,0,0)         |PNH; Omtrek in meters, 5 decimalen. Dit wordt automatisch gevuld; Nullable: False; Default: None|
|SHAPE_Area                          |Double(0,0,0)         |PNH; Oppervlakte in m2, 5 decimalen. Dit wordt automatisch gevuld; Nullable: False; Default: None|

***


