# Adaption der Bootstrap 4.5 Stylesheets für SoSci Survey

Auf Basis der `.scss`-Stylesheet-Dateien aus Bootstrap 4.5 werden hier Styles generiert, die ein einfaches Einbinden in SoSci Survey erlauben. Das ermöglicht einerseits die Nutzung bekannter Stylings im Fragebogen, andererseits ein vielfach getestetes responsives Design für optimale Fragebogengestaltung auch für mobile Endgeräte.

Details gibt es auch unter [getbootstrap.com](https://getbootstrap.com/) und [soscisurvey.de](https://www.soscisurvey.de/).

## Einbindung in SoSci

### Möglichkeit 1

Die [layout.bs.xml](dist/layout.bs.xml)-Datei herunterladen und im entsprechenden SoSci-Fragebogen unter [Fragebogen-Layouts](https://www.soscisurvey.de/admin/index.php?o=layout) ganz unten "aus Datei importieren". Fertig.

### Möglichkeit 2

Für etwas mehr Gestaltungsspielraum kann auch die [bootstrap4sosci.min.css](dist/bootstrap4sosci.min.css)-Datei heruntergeladen und als [Mediendatei](https://www.soscisurvey.de/admin/index.php?o=files) in SoSci hochgeladen werden. Im Layout des Fragebogens muss die Mediendatei dann noch eingebunden werden, indem in der "HTML-Vorlage für den Fragebogen" die folgenden zwei Code-Zeilen in den `head`-Bereich eingebunden werden:

```html
<meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
<link href="bootstrap4sosci.min.css" rel="stylesheet">
```

Fertig.

## Weiterenticklung

1. [nodejs](https://nodejs.org/en/download/) am Start haben
1. Repository klonen
1. im geklonten Verzeichnis `npm install` ausführen
1. Änderungen vornehmen
1. im geklonten Verzeichnis `npm run css` ausführen
1. testen und Änderungen wieder der Allgemeinheit zur Verfügung stellen

## Sonstiges
Gerne über die [Issues](https://github.com/MarHai/bootstrap4sosci/issues) oder via [haim.it](https://haim.it).

(c) 2020 Mario Haim
