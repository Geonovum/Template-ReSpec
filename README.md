# Template-ReSpec

Dit is de ReSpec template voor Geonovum publicaties. 
Deze template is in beheer bij d.hup@geonovum.nl

Dit is een standaard template en kan worden aangepast aan verschillende Documenttypen. 
Hiervoor moet de config.js worden aangepast. Hoe dat moet lees je hieronder.



Om gebruik te maken van de het specStatus en specType moeten in config.js de 
schuine strepen voor het betreffende type worden weggehaald. 

In het voorbeeld hieronder zijn 
'specStatus: "GN-WV",                  // Werk Versie'geselecteerd en
'specType: "BD",                       // Beheer Documentatie' geselecteerd.

Het ReSpec document wordt nu dus als een werk versie van het type Beheer Documentatie vormgegeven.

![image](https://user-images.githubusercontent.com/77289333/112480805-ab07bb00-8d76-11eb-8fc4-ffff9e4cff23.png)



var respecConfig = 
	                 {
	                  //-- specStatus is verplicht! (activeer 1 van de volgende) --------------------------
	                  //specStatus: "GN-BASIS",             // Basis Document
	                  specStatus: "GN-WV",                  // Werk Versie
	                  //specStatus: "GN-CV",                // Consultatie Versie
	                  //specStatus: "GN-VV",                // Vaststellings Versie
	                  //specStatus: "GN-DEF",               // Definitieve Versie
	                  //-- specType is verplicht bij alle andere dan BASIS ---------------------------------
	                  //specType: "NO",                     // Norm
	                  //specType: "ST",                     // Standaard
	                  //specType: "IM",                     // Informatie Model
	                  //specType: "PR",                     // Praktijkrichtlijn
	                  //specType: "HR",                     // HandReiking
	                  //specType: "WA",                     // Werkafspraak
	                  specType: "BD",                       // Beheer Documentatie
