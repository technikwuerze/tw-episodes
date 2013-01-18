# Kleine Helferlein

Wir nehmen die Sendung am 17.1. um 20 Uhr auf.

## Teilnehmer

* David Maciejewski
* Matthias Pfefferle
* Jens Grochtdreis

## Beschreibung

Die Frontend-Entwicklung macht dank vieler kleiner "Helferlein" immer mehr Spaß!

## Überblick

### Wahl des Betriebssystems

* Vorteil Mac gegenüber Linux/Windows
* Viele Kleinigkeiten scheinen in letzter Zeit vor allem Mac-only aber vor allem Mac-first zu erscheinen.
* Vernünftiges Screenshot-Tool für Mac? PC? 
* Farbpicker

### Welche IDE oder Editoren

* Textmate
* Emmet (ehemals Zen-Coding)
* was taugt Sublime Text 2?

### Das Projekt aufsetzen

Viele Projekte haben die gleiche Basis und viele Arbeitsschritte wiederholen sich immer wieder. Diese Tools können helfen, das zu optimieren:

Yeoman: http://yeoman.io
* init: yeoman init backbone 
* models erstellen: yeoman init backbone:model modelName
* build: JS und CSS optimieren, validieren und minifien
* außerdem: Testsystem, Paket-Management, Task-Management, uvm.

Paketmanagement mit Bower: https://github.com/twitter/bower (ähnlich wie npm oder RubyGems)
* Pakete installieren: bower install jquery
* Pakete updaten: bower update jquery-ui

Taskmanagmenet mit Gruntjs: http://gruntjs.com/
* Immer wiederkehrende Tasks definieren: minify, test, compile (sass/less), lint, ...

### Nutzliche Frameworks

Frameworks helfen beim besseren Umgang mit Formaten und bieten Möglichkeiten, die das Format nicht selbst unterstützt.

* SASS/LESS
* Coffeescript

### Nützliche Libraries

Klassiker:

* CSS Grid-Systeme
* jQuery
* YAML
* usw.

Erwähnenswert:

* Twitter Bootstrap (pro und contra)
* HTML5 Boilerplate

### Templating Engines

Wo macht templating im Frontend Sinn? Macht es überhaupt Sinn?

* mustache http://mustache.github.com/
* Handlebars http://t3n.de/news/ansatze-client-side-templating-435518/

### Grafiken und Icons

Klassisch: Sprites
* Nur eine Grafik
* besseres Caching
* geringere Ladezeiten

Neu: Icon Fonts
* "beliebig" skalierbar
* über "color:" farblich beliebig anpassbar
* verläufe auch über CSS möglich
* nur einfarbig

### Browser

* Welche kleinen Helfer haben wir in unseren Browsern?
* Haben wir einen Arbeitsbrowser? Oder mehrere?
