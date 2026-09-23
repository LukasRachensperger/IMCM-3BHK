# IMCM-3BHK

## Einleitung 

### Markdown 

_Markdown_ ist eine Auszeichnungssprache (_Markup Language_). Mit Auszeichnungssprachen wird Text strukturiert. Einige Markup-Languages sind z.B.:

- HTML (_Hypertext Markup Language_)
- XML (_Extensible Markup Language_)
- MD (_Markdown_)
- YAML (_Yet Another Markup Language_ bzw. _YAML Ain´t Markup Language_)

Markdown ist heutzutage eine der beliebtesten Auszeichnnungssprachen. 
Wenn eine README.md-Datei in einem Git-Repository vorhanden ist, wird sie in der Regel auf der Hauptseite des Repositories angezeigt. Die README-Datei ist also die erste Anlaufstelle für Informationen über das Projekt. Um ein Git-Repository zu erstellen, sind folgende Schritte notwendig:

- im gewünschten Verzeichnis im Terminal (bzw. CLI - _Command Line Interface_) den Befehl `git init` ausführen



> **Einschub zur Installation von Git:**
>Falls bei der Eingabe von git init die Meldung _"command not found"_ erscheint, ist Git nicht installiert und der Befehl wird nicht erkannt. Bei der Installation wird der Befehl der Umgebungsvariable **PATH** hinzugefügt. Darin sind die Bezeichnungen aller Programme enthalten, die im Terminal aufgerufen werden können.
- dann in GitHub-Desktop das lokale Repository hinzufügen (_File > Add Local Repository..._)
- nun kann über die Schaltflächen **Commit to master** und **Push origin** der aktuelle Stand des Projekts in das GitHub-Repository hochgeladen werden.

# Mitschrift IMCM 
## Statische und dynamische Websites
**Ablauf Anfragen**
1. DNS-Request (johak.at???)
2. DNS-Response (162.259.134.42)
3. HTTP-Request (GET /index.html)
4. HTTP-Response (index.html)



In den 1990er Jahren wurden Websites überwiegend statisch erstellt. Inhalte wurden als html-File auf einen Webserver hochgeladen. Bei jedem Aufruf der Website wurde das html-File vom Server an den Browser des Nutzers übertragen. Die Inhalte waren also immer glich, unabhängig davon, wer die Website aufrief.

![Funktionsweise von statischen Websites](image.png "Ablauf der DNS- und HTTP-Anfragen")

Die Abbildung zeigt die Funktionsweise von statischen Websites. Zuerst muss der Domain-Name über das DNS in die IP-Adresse des Webservers aufgelöst werden (Schritt 1 und 2 in der Abbildung). Danach schickt der Cleint eine HTTP-Anfrage an den entsprechenden Webserver und erhält von diesem eine HTTP-Antwort, die üblicherweise zuerst die `index.html` enthält (Schritt 3 und 4)