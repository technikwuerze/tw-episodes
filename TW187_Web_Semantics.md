# Web Semantics

## Teilnehmer

* David Maciejewski
* Matthias Pfefferle

## Beschreibung

Microformats.org wird 7, Twitter veröffentlicht “Twitter Cards” und Google baut auf Schema.org... Aber was von den vielen Meta und Web-Semantiken braucht man nun wirklich?

## Überblick

* Mittwald-Vorstellung
* Staffel 5 – Warum dauert das immer so lange bei euch?
* Allgemeines
	* OpenWeb-Podcast nun Bestandteil von Technikwürze (Themen)
	* Technikwürze auf Github (neue Themen vorschlagen und an Folgen mitarbeiten)
* Einleitung
	* Instagram entfernt Twitter-Cards
		* Twitter Cards (Beispiel t3n.de)
* Überblick
	* Warum die eigenen Versionen und kein DC, MF oder klassische Meta-Tags?
	* Twitter Cards
	* Schema.org
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

== Alt ==

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

## Lose Ideen (in Form bringen)

* was ich mir zu dem semantik thema dachte: einen kleinen überblick geben, wie was funktioniert... was man einsetzen sollte (eine empfehlung) und was keinen sinn macht.
* also so in dem stil: microformats sind gut für semantisches html (sollten aber nicht für maschinenlesbare semantik benutzt werden, weil zu fehleranfällig), schema.org für suchmaschinen (microdata) und OGP für abstracts (google+ facebook, twitter)