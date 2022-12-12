# IBSYS2-Frontend / Bike2B

Das Projekt wurde erstellt mit [Angular CLI](https://github.com/angular/angular-cli) Version 15.0.0.

## Notwendige Vorarbeiten

Installieren Sie NPM auf ihrem Rechner.
Legen Sie sich (falls nötig) einen git Account an.

## Webserver installieren

Gehen Sie in der Konsole in den gewünschten Ordner, indem Sie das Projekt speichern und ausführen möchten.
Geben Sie den Befehl `git clone Repo` ein oder nutzen Sie die mitgelieferte .Zip Datei, indem Sie diese im gewünschten Ordner ausgepacxkt haben.
Anschließend geben Sie `npm install` ein.

## Webserver aufrufen

Geben Sie den Befehl `ng serve --open` ein und es wird nach einem erfolgreichen build Prozess, der WEbserver automatisch gestartet und es öffnet sich der Browser mit unserer integrierten SCM-Weblösung.
FYI: Dabei wird automatisch zur Seite `http://localhost:4200/` navigiert.

## Webserver nutzen

Nachdem unsere integrierte SCM-Weblösung sich im Browser geöffnet hat, können Sie über den Reiter Simulation ihre XML-Datei hochladen und mit der optimierten Produktionsplanung starten. Nach der Produktionsplanung stehen ihre Ergebnisse ihnen als XML-Datei zur Verfügung.

## Viel Spaß bei der Nutzung unserer integrierten SCM-Weblösung!

## IBSYS2-Frontend / Bike2B (Entwickler Spezifikationen)

### Repository

Achten Sie darauf, wenn Sie Änderungen am Projekt vornehmen, immer einen Branch für ihr neues Feature zu nutzen. Wir achten auf gute Code-Qualität. Vielen Dank.

### Webserver

Den Webserver starten Sie wie oben beschrieben.

### Build

Geben Sie den Befehl `ng build` in ihre Konsole ein, um ein build-Job des Projekts auszuführen. Die Build-Artefakte werden im Verzeichnis `dist/` gespeichert.

### Code Erweiterungen

Zur Generierung einer neuen Komponente, geben Sie den Befehl `ng generate component component-name` in die Konsole ein.
Sie können außerdem folgende Befehle nutzen, um weitere Inhalte im PRojekt zu generieren: `ng generate directive|pipe|service|class|guard|interface|enum|module`.

### Support

Haben Sie Probleme mit Angular CLI Befehlen, geben Sie den Befehl `ng help`ein und es werden ihnen alle mögliche Befehle von ANgular angezeigt. Benötigen Sie weitere Hilfe bzgl. Angular CLI besuchen Sie die folgende Seite [Angular CLI Overview and Command Reference](https://angular.io/cli).
