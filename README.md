# FreeGPT WebUI v2

**Ich habe dieses Repository so lange wie möglich gepflegt.  
Aufgrund der Verschlechterung der verfügbaren Methoden zur Nutzung von GPT 3.5 / 4.0 archiviere ich dieses Repository.  
Das g4f-Projekt ist instabil geworden und hat weniger Anbieter.  
Ich bin jedoch dankbar für die Existenz dieses Projekts, da es mir viele neue Erfahrungen gebracht hat.  
In Zukunft plane ich, ein Textneuronales Netzwerk auf meiner Website zu starten: [vadimboev.ru/gpt](https://vadimboev.ru/gpt)**

____

Mit einigen UI-Verbesserungen 😄

Desktop  
<img src="https://github.com/VadimBoev/freegpt-webui-v2/blob/main/webui-gpt.png" width="1000" />

Mobilgerät  
<img src="https://github.com/VadimBoev/freegpt-webui-v2/blob/main/mobile-ui.png" width="30%" />

## GPT 3.5/4

<strong>KEIN API-SCHLÜSSEL ERFORDERLICH</strong> ❌🔑

Dieses Projekt bietet eine WebUI, die die [G4F API](https://github.com/xtekky/gpt4free) nutzt.  
Erleben Sie die Kraft von ChatGPT mit einer benutzerfreundlichen Oberfläche, verbesserten Jailbreaks und völlig kostenlos.

**Wichtig!** Scheuen Sie sich nicht, eine Frage zu stellen oder ein Problem im "Issue" zu melden.  
Wir werden die Frage oder das Problem gemeinsam lösen! 🌍

Sie können mir [hier einen Kaffee kaufen](https://www.donationalerts.com/r/vadimboevdev) ☕🤎

## Bekannte Fehler 🚧
- Kopieren von markiertem Text funktioniert nicht.

## Funktionen v2 📢
- Aktualisiertes g4f
- Fehlerbehebungen, um alles funktionsfähig zu machen

## Projekt-Hosting und Demonstration 🌐🚀
Das Projekt ist auf mehreren Plattformen gehostet, um getestet und modifiziert zu werden.
|Plattform|Status|API-Schlüssel|Kostenlos|Repo|Demo|
|--|--|--|--|--|--|
|[Meine Seite](http://vadimboev.ru:1338/)|![Aktiv](https://img.shields.io/badge/Active-brightgreen)|◼️|☑️|[FreeGPT WebUI](https://github.com/VadimBoev/freegpt-webui-v2)|[Chat](http://vadimboev.ru:1338/)

## Inhaltsverzeichnis
- [To-Do-Liste](#to-do-list-%EF%B8%8F)  
- [Erste Schritte](#erste-schritte-white_check_mark)  
  - [Repository klonen](#repository-klonen-inbox_tray)  
  - [Abhängigkeiten installieren](#abhängigkeiten-installieren-wrench)  
- [Anwendung ausführen](#anwendung-ausführen-rocket)
- [Integrierte Projekte](#integrierte-projekte-busts_in_silhouette)
  - [WebUI](#webui) 
  - [API FreeGPT](#api-g4f)
- [Sternhistorie](#sternhistorie)
- [Rechtlicher Hinweis](#rechtlicher-hinweis)

## Erste Schritte :white_check_mark:  
Um mit diesem Projekt zu beginnen, müssen Sie das Repository klonen und [Python](https://www.python.org/downloads/) auf Ihrem System installiert haben.  
(Version 3.10+ wird empfohlen. Es funktioniert auch mit 3.9.2 unter Debian 11).

### Repository klonen :inbox_tray:
Führen Sie den folgenden Befehl aus, um das Repository zu klonen:

```
git clone https://github.com/VadimBoev/freegpt-webui-v2.git
```

### Abhängigkeiten installieren :wrench:
Navigieren Sie zum Projektverzeichnis:
```
cd freegpt-webui-v2
```

Installieren Sie die Abhängigkeiten:
```
pip install -r requirements.txt
```

## Anwendung ausführen :rocket:
Um die Anwendung auszuführen, verwenden Sie den folgenden Befehl:
```
python3 run.py
```

Zugriff auf die Anwendung über Ihren Browser mit der URL:
```
http://127.0.0.1:1338
```
oder
```
http://localhost:1338
```

## Docker 🐳
### Voraussetzungen
Bevor Sie beginnen, stellen Sie sicher, dass Sie [Docker](https://www.docker.com/get-started) auf Ihrem Rechner installiert haben.

### Docker ausführen
Dockerfile zum Erstellen eines Docker-Images  
Dann können wir ein Image mit den folgenden Befehlen erstellen:
```
git clone https://github.com/VadimBoev/freegpt-webui-v2.git cd freegpt-webui-v2
```

Image erstellen:
```
docker build -f Dockerfile -t freegpt-webui-v2 .
```

Führen Sie die Anwendung mit Docker aus:
```
docker run -p 1338:1338 freegpt-webui-v2:latest
```

Zugriff auf die Anwendung über Ihren Browser mit der URL:
```
http://127.0.0.1:1338
```
oder
```
http://localhost:1338
```

Wenn Sie mit der Nutzung der Anwendung fertig sind, stoppen Sie die Docker-Container mit dem folgenden Befehl:
```
docker stop <container-id>
```

## Integrierte Projekte :busts_in_silhouette:
Ich empfehle dringend, beide Projekte zu besuchen und zu unterstützen.

### WebUI
Die Anwendungsoberfläche wurde aus dem Repository [chatgpt-clone](https://github.com/xtekky/chatgpt-clone) übernommen.

### API G4F
Die kostenlose GPT-4-API wurde aus dem Repository [GPT4Free](https://github.com/xtekky/gpt4free) übernommen.

<br>

## Sternhistorie
[![Sternhistorie-Diagramm](https://api.star-history.com/svg?repos=VadimBoev/freegpt-webui-v2&type=Timeline)](https://star-history.com/#VadimBoev/freegpt-webui-v2&Timeline)

<br>

## Rechtlicher Hinweis
Dieses Repository ist _nicht_ mit den Anbietern der in diesem GitHub-Repository enthaltenen APIs verbunden oder wird von ihnen unterstützt. Dieses Projekt ist ausschließlich **für Bildungszwecke** gedacht. Es handelt sich lediglich um ein kleines persönliches Projekt. Websites können mich kontaktieren, um ihre Sicherheit zu verbessern oder die Entfernung ihrer Website aus diesem Repository zu beantragen.

Bitte beachten Sie Folgendes:

1. **Haftungsausschluss**: Die in diesem Repository erwähnten APIs, Dienste und Marken gehören ihren jeweiligen Inhabern. Dieses Projekt beansprucht keinerlei Rechte an ihnen und steht in keiner Verbindung zu den genannten Anbietern und wird nicht von ihnen unterstützt.

2. **Verantwortung**: Der Autor dieses Repositories ist _nicht_ verantwortlich für etwaige Folgen, Schäden oder Verluste, die aus der Nutzung oder dem Missbrauch dieses Repositories oder der Inhalte der Drittanbieter-APIs entstehen. Die Benutzer sind allein verantwortlich für ihre Handlungen und etwaige Konsequenzen, die daraus entstehen können. Wir empfehlen den Benutzern dringend, die AGB der jeweiligen Websites zu befolgen.

3. **Nur für Bildungszwecke**: Dieses Repository und seine Inhalte werden ausschließlich zu Bildungszwecken bereitgestellt. Durch die Nutzung der bereitgestellten Informationen und des Codes erkennen die Benutzer an, dass sie die APIs und Modelle auf eigenes Risiko verwenden und sich verpflichten, alle geltenden Gesetze und Vorschriften einzuhalten.

4. **Urheberrecht**: Alle Inhalte in diesem Repository, einschließlich, aber nicht beschränkt auf Code, Bilder und Dokumentation, sind das geistige Eigentum des Autors dieses Repositories, sofern nicht anders angegeben. Das unerlaubte Kopieren, Verteilen oder Verwenden von Inhalten aus diesem Repository ist ohne ausdrückliche schriftliche Zustimmung des Autors strengstens untersagt.

5. **Entschädigung**: Die Benutzer erklären sich damit einverstanden, den Autor dieses Repositories von jeglichen Ansprüchen, Verbindlichkeiten, Schäden, Verlusten oder Ausgaben, einschließlich Anwaltskosten, freizustellen, die sich aus der Nutzung oder dem Missbrauch dieses Repositories, seiner Inhalte oder der zugehörigen Drittanbieter-APIs ergeben.

6. **Aktualisierungen und Änderungen**: Der Autor behält sich das Recht vor, Inhalte, Informationen oder Funktionen in diesem Repository jederzeit ohne vorherige Ankündigung zu ändern, zu aktualisieren oder zu entfernen. Die Benutzer sind dafür verantwortlich, die Inhalte regelmäßig zu überprüfen und sich über Änderungen in diesem Repository zu informieren.

Durch die Nutzung dieses Repositories oder eines damit verbundenen Codes stimmen Sie diesen Bedingungen zu. Der Autor ist nicht verantwortlich für etwaige Kopien, Forks oder erneute Uploads, die von anderen Benutzern erstellt wurden. Dies ist das einzige Konto und Repository des Autors. Um Nachahmungen oder unverantwortliche Handlungen zu verhindern, halten Sie sich bitte an die GNU GPL-Lizenz, die dieses Repository verwendet.
