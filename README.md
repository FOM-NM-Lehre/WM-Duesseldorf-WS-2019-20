## Willkommen zum Vorlesungs-Repository

In diesem **GitHub-Repository** finden Sie die in der Veranstaltung von mir erstellten R Markdown Dokumente. Da ich dieses Repository für meinen Austausch zwischen meinen Rechnern, u.a. dem Rechner in der Veranstaltung und meinem privaten Rechner zu Hause, verwende ist dieses Repository in der Regel immer auf dem aktuellen Stand der Veranstaltung.

Sie haben also die Möglichkeit hier meine jeweilige Fassung zu erhalten. -- Allerdings nur im **Lesezugriff**! 

Dieses Repository ist ein Arbeitswerkzeug. Ich erlaube mir also ohne weitere Ankündigung hier -- auch nach den Veranstalltungen -- Änderungen, Kürzungen, Erweiterungen oder Hinweise einzupflegen!

Einen Schreibzugriff kann ich Ihnen aus verständlichen Gründen natürlich **nicht** gewähren.


### Nutzung dieses Repositories

Sie können dieses Repository im Prinzip auf zwei Arten nutzen:

1. Als Archiv-Abzug via einer ZIP Datei
    Wenn Sie auf der GitHub-Seite rechts am  Button *Clone and download* die Option *Download ZIP* wählen, erhalten Sie einen aktuellen Abzug des Repositories als ZIP-Archiv und können diesen als lokalen Ordner nutzen.
    
2. Als *read-only* git working directory
    Sollten Sie sich mit `git` und `github` auskennen, so können Sie natürlich auch (regelmässig) das Projekt einfach aktuallisieren. -- Falls Sie es forken wollen, nur zu. So können Sie via *pull-request* regelmässig meine *master* Fassung in ihren Fork integrieren. (**EXPERTENMODUS!!** Sie bekommen hierzu keine Hilfestellung!)


**Mein Tipp:** Arbeiten Sie immer auf Ihren eigenen Daten, welche einen eigenen Dateinamen tragen sollten, und nutzen Sie meine Dateien nur als Vorlagen für Ihr eigenes Lernskript.


### RStudio Desktop Nutzer

Bitte geben Sie, um die Installation abzuschliessen, in der **Console** den folgenden Befehl ein:

```
install.packages(c("mosaic", "mosaicCalc", "rmarkdown"))
```

Um direkt mit *RStudio* die aktuelle Fassungen via `git` auf seinen Rechner zu bekommen, müssen Sie es ggf. erst einmal installieren. Hier sind ein paar Links die Ihnen ggf. weiter helfen mögen:

- Windows: https://git-scm.com/downloads
- macOS: https://git-scm.com/downloads
- Linux:
  - **Allgemein**: https://git-scm.com/downloads
  - **Debian/Ubuntu**: `sudo apt-get install git-core`
  - **Fedora/RedHat**: `sudo yum install git-core`

Zu Kompliziert? -- Dann nutzen Sie bitte die ZIP Dateien aus dem GitHub-Repository lokal bei sich auf dem Rechner in einem seperaten Verzeichnis/Ordner.


### RStudio Cloud Nutzer

Bitte geben Sie, um die Installation abzuschliessen, in der **Console** den folgenden Befehl ein:

```
install.packages(c("mosaic", "mosaicCalc", "rmarkdown"))
```

In der RStudio Cloud ist *git* in der Regel schon vorinstalliert.
