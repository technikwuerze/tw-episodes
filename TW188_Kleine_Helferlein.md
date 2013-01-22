# Technikwürze 187 - Die Lieblings-Tools der Frontend-Entwickler

Wir nehmen die Sendung am 21.1. um 20 Uhr auf.

## Teilnehmer

* David Maciejewski
* Matthias Pfefferle
* Jens Grochtdreis

## Beschreibung

Immer wieder fragen uns die Zuhörer, welche Programme, Editoren und Helferlein wir als Frontend-Entwickler einsetzen. In dieser Sendung geben wir die Antwort!

## Überblick

### Wahl des Betriebssystems

* Mac, Windows oder Linux?
* Viele Kleinigkeiten scheinen in letzter Zeit vor allem Mac-only aber vor allem Mac-first zu erscheinen.
  * [ImageOptim](http://imageoptim.com/)
* Vernünftiges Screenshot-Tool für Mac? PC? 
* Farbpicker

### Welche IDE oder Editoren

Task-spezifische IDEs oder Alleskönner? Sind grosse IDEs, wie NetBeans, PHPStorm oder WebStorm auch auch für Frontend-Entwickler interessant?

* [Textmate](http://macromates.com)
* [Emmet](http://emmet.io) (ehemals Zen-Coding)
* [NetBeans](http://netbeans.org/)
* [Sublime Text 2](http://www.sublimetext.com) – Was taugt es?
* [PHPStorm](www.jetbrains.com/phpstorm/)
[WebStorm](http://www.jetbrains.com/webstorm/)

### Das Projekt aufsetzen

Viele Projekte haben die gleiche Basis und viele Arbeitsschritte wiederholen sich immer wieder. Diese Tools können helfen, das zu optimieren:

#### [Yeoman](http://yeoman.io)

* init: yeoman init backbone 
* models erstellen: yeoman init backbone:model modelName
* build: JS und CSS optimieren, validieren und minifien
* außerdem: Testsystem, Paket-Management, Task-Management, uvm.

#### Paketmanagement mit [Bower](https://github.com/twitter/bower) (ähnlich wie npm oder RubyGems)

* Pakete installieren: bower install jquery
* Pakete updaten: bower update jquery-ui

#### Taskmanagmenet mit [Gruntjs](http://gruntjs.com/)

* Immer wiederkehrende Tasks definieren: minify, test, compile (sass/less), lint, ...

### Nutzliche Frameworks

Frameworks helfen beim besseren Umgang mit Formaten und bieten Möglichkeiten, die das Format nicht selbst unterstützt.

* [Sass](http://sass-lang.com/)
* [Compass](compass-style.org)
* [Less](http://lesscss.org/)
* [Coffeescript](http://coffeescript.org/)

### Nützliche Libraries

Klassiker:

* CSS Grid-Systeme
* jQuery
* [YAML](http://yaml.de)
* usw.

#### Erwähnenswert:

* [Twitter Bootstrap](http://twitter.github.com/bootstrap/) (pro und contra) (zusätzliche Ressourcen)
* [Foundation](http://foundation.zurb.com) (vor allem die ganzen zusätzlichen Ressourcen)
* [HTML5 Boilerplate](http://html5boilerplate.com/)

### Templating Engines

Wo macht templating im Frontend Sinn? Macht es überhaupt Sinn?

* [mustache](http://mustache.github.com/)
* [Handlebars](http://t3n.de/news/ansatze-client-side-templating-435518/)

### Grafiken und Icons

#### Sprites

Pro/Contra

* Nur eine Grafik
* besseres Caching
* geringere Ladezeiten

#### Icon Fonts

Pro/Contra

* "beliebig" skalierbar
* über "color:" farblich beliebig anpassbar
* verläufe auch über CSS möglich
* nur einfarbig

Tools

* [Font Awesome](http://fortawesome.github.com/Font-Awesome/)
* [We Love Icon Fonts](http://weloveiconfonts.com/)
* [Font-Custom](https://github.com/endtwist/fontcustom)

### Browser

* Welche kleinen Helfer haben wir in unseren Browsern?
  * [TinyPNG](http://tinypng.org/)
  * [Closure Compiler](http://closure-compiler.appspot.com/home)
* Haben wir einen Arbeitsbrowser? Oder mehrere?


### Hilfeseiten

* [Can I Use](http://caniuse.com/)
* [HTML5Please](http://html5please.com/)
* [CSS3 Click Chart](http://css3clickchart.com/)
* [rgba für oldIE wandeln](http://beijingyoung.com/articles/rgba-argb-converter/)

### lokal oder cloud?

* Arbeiten wir immer mehr in der Cloud?
* Was passiert auf alle Fälle lokal?

### Tools für RWD

Nutzt jemand spezielle Tools für Responsive Webdesign? Es gibt da einige Bookmarklets.
Ich nutze nur die neuen Entwicklertools von Firefox und echte Testgeräte. Adobe Edge Inspect habe ich nicht mehr angefasst, seit es nicht mehr Shadow heisst. Zu eingeschränkt. 
