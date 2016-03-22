# Installation

## zu kopierende Dateien

Kopieren Sie erst den Inhalt des Ordners `copy_this` auf Ihren Server, dann den Inhalt des Ordners `changed_full`.


## Datenbankeinträge

### CMS-Seiten
Einige OXID-Emails sind als CMS-Seiten definiert. Diese müssen geupdatet werden, damit die Texte im neuen Design erschienen..

**Bitte beachten Sie**: Dabei werden diese CMS-Seiten überschrieben. Wenn Sie Änderungen an diesen CMS-Seiten vorgenommen haben, die Sie übernehmen möchten, so sichern Sie diese bitte vorher und übernehmen Sie diese manuell.

Gehen Sie in den Admin-Bereich Ihres Shops und führen Sie dort unter `Service → Tools` die Datei `sql/install.sql` aus (über `Durchsuchen` auswählen). Klicken Sie dann auf `Update starten` und warten Sie, bis alle SQL-Abfragen abgeschlossen wurden.

### CMS-Snippets

Das Modul fügt in einigen Emails, z.B. der Bestellbestätigungsemail an den Kunden, leere Snippets hinzu. So können Sie einfach und ohne Templateanpassungen Inhalt hinzufügen. Die Snippets sind in der Datei `sql/snippets.sql` enthalten. Installieren Sie diese, wie im obigen Abschnitt beschrieben.


## Modul aktivieren

Das Modul ist nun fertig installiert. Zur Inbetriebnahme aktivieren brauchen Sie es nur noch unter `Erweiterungen > Module` zu aktivieren.
