# Anpassungen

## Template-Dateien

Um Änderungen an einer Template-Datei durchzuführen, kopieren Sie diese von `email/html` nach `modified/email/html` und führen Sie die Änderungen in dieser Datei durch. So bleibt das Modul update-sicher.


### Beispiel:

Sie möchten die Produkt-Empfehlungs-Email ändern. Kopieren Sie die Datei `email/html/suggest.tpl` in den Ordner `modified/email/` und führen alle Änderungen dort durch.


## CSS-Anpassungen

Fügen Sie Ihren eigenen CSS-Code in der Datei `modified/email/css/styles.css` hinzu.

## CMS-Seiten

Einige Emails sind von OXID als CMS-Seite definiert. Sie können Sie wie gewohnt im Backend unter `Kundeninformationen → CMS-Seiten` anpassen.

## CMS-Snippets

In folgenden Emails wurden leere CMS-Snippets definiert:
- Bestellbestätigung (`order_cust.tpl`)
- Versandbestätigung (`ordershipped.tpl`)
Sie können diese Snippets im Backend unter `Kundeninformationen → CMS-Seiten` anpassen, und so Texte zu diesen Emails hinzufügen, ohne die `.tpl`-Datei bearbeiten zu müssen.
