# Metainformationen / Semantisches Web

## Teilnehmer

* David Maciejewski
* Matthias Pfefferle

## Beschreibung

Microformats.org wird sieben, Twitter veröffentlicht die „Twitter Cards“, Google baut auf Schema.org und Facebook auf das Open Graph Protocol. Aber was von den vielen Meta- und Websemantiken braucht man nun wirklich? Wir sagen es euch!

## Überblick

* Kurzer Themenüberlick
* Vorstellung Matthias / OpenWeb-Podcast
* Neue Folgen von Technikwürze, Vorstellung Mittwald, Themen und Ideen auf GitHub
 * "Alle neuen Folgen, Behind the Scenes":https://github.com/technikwuerze/folgen
 * "Pool zum Sammeln von Ideen und Themen":https://github.com/technikwuerze/themen

* Einleitung
	* Instagram entfernt Twitter-Cards
		* Twitter Cards (Beispiel t3n.de)
* Überblick
	* Warum die eigenen Versionen und kein DC, MF oder klassische Meta-Tags?
	* Twitter Cards
	* Open Graph
* Open Graph sollte als Meta-Information ausreichen
* Schema.org macht auch sinn, aber aufpassen bei Google+ (Google nimmt immer das erste Objekt
* Suchmaschinenoptimierung
	* Schema.org macht für Suchen sinn (Google, Yahoo, Bing)
* Überblick über sonstige Formate
	* Microformats v2
	* Microdata/RDFa und Schema.org
	* OpenGraph Protocol (Artikel auf t3n.de / SocialMediaEnhancer )
	* Dublin Core
	* klassische Meta-Tags
* Fazit
	* OpenGraph für Social Networks
	* Schema.org für Suchmaschinen (vorsicht mit Google+)
	* (optional Microformats für semantisches HTML)

## Lose Ideen (in Form bringen)

* was ich mir zu dem semantik thema dachte: einen kleinen überblick geben, wie was funktioniert... was man einsetzen sollte (eine empfehlung) und was keinen sinn macht.
* also so in dem stil: microformats sind gut für semantisches html (sollten aber nicht für maschinenlesbare semantik benutzt werden, weil zu fehleranfällig), schema.org für suchmaschinen (microdata) und OGP für abstracts (google+ facebook, twitter)

* Unterschied Websemantiken und Meta-Informationen
	* Websemantiken
		* Microformats und Schema.org zeichnen “sichtbare” Informationen aus
		* Hauptsächlich von Suchmaschinen benutzt
	* Meta-Informationen
		* Sprechen meist für die ganze Seite und müssen nicht im direkten Verhältnis zum Text stehen
		* klassiche Meta-Informationen & Dublin Core von Suchmaschinen
		* OGP und Twitter Cards von Social Networks.
	* Was braucht man und warum
		* Meta-Tags
			* Twitter Cards sind proprietär und Twitter, Google und Facebook unterstützen auch OGP
			* OpenGraph vs. Meta Tags
				* Meta-Tags/Dublin Core meistens SEO versäucht
				* OGP meist für Social-Networks um mehr über einen Link zu erfahren (Bild und Beschreibung)
		* Websemantics
			* Da Google, Yahoo und Microsoft Microdata/RDFa und Schema.org vorschlagen sollte man sich daran orientieren
			* Microformats “erziehen” Webentwickler, semantisches HTML zu schreiben und können ruhig auch zusätzlich zu Schema.org eingesetzt werden, sind aber zu fehleranfällig um noch ernsthaft mit Microdata und RDFa konkurrieren zu können
	* Empfehlungen
		* Meta-Tags wie gewohnt beibehalten (SEO)
		* Für Social-Networks das OpenGraph Protocol
		* Für Suchmaschinen Schema.org
		* Für schönes HTML Microformats
