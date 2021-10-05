# Werkstattauftrag W07 Webmin

## 1. Autoren, Versionierung des Dokumentes
Autor: Janis Müller
Version: 

## 2. Einfuehrung 
   - Beschreibung: Welche Funktionen wird der Service erfuellen
   - Vorgesehener Zeitaufwand für die Realisierung
   - Stolpersteine

## 3. Benoetigte Hard- und Software
   - Hardware (Materialliste, Funktionalitaet)
   - Software (Anforderungen, Firmware, OS-Image, ergaenzende SW-Packages, Ab-
	hängigkeiten, Funktionalitaet)

## 4. Installationsanleitung (Didaktisch reduzierte Anleitung. Lernende sollen eine eigene Lösungswege realisieren)
   - Anweisungen verstaendlich und nachvollziehbar
   - Keine fertigen Loesungsschritte aufzeigen
   - Hilfestellung (Tipps, Quellen...)

### Start der Anleitung 
In diesem Projekt werden wir das Webmin auf einem Raspberry Pi Aufsetzen.

1. Um das Webmin installieren zu können musst du zerst das ZIP file herunterladen.
> wget http://prdownloads.sourceforge.net/webadmin/webmin-1.941.tar.gz
2. Anschliessend must du das zip file entzippen 
> tar -zxvf webmin-1.941.tar.gz

Dieses Repo ist das offizielle repo von webmin.

3. Nun musst du das setup script ausführen 
> cd webmin-1.941
> sudo ./setup

![image](https://user-images.githubusercontent.com/63262820/135911599-49aa90f9-7d7d-4d1c-ab7b-dbad5e720215.png)

4. Anschliessend musst du die Einstellungen für das Webmin vonehmen.

![image](https://user-images.githubusercontent.com/63262820/135912830-c3cac8aa-1cfc-4c6a-bf0c-ea1ffc8c802e.png)

5. Nachdem die installation kannst du über die ip addresse aufrufen.
> http://piaddress:10000/

6. Wenn du dieser ip folgst gelangst du auf das Dasboard.

![image](https://user-images.githubusercontent.com/63262820/135913169-6a3c0869-2780-4877-843e-a1234fee094c.png)

7. Dort solltest du zuerst das Tool erforschen bebvor du weiter fährst mit dieser anleitung.

8. Um die Konfiguration zu prüfen habe ich ein FTP Server.

![image](https://user-images.githubusercontent.com/63262820/135914601-be83f342-2d96-4d4e-af6a-226dadbc1b81.png)

Dieser findest du im Hamburger Menue unter "Un-user modules" mit dem namen "ProFTP Server".

9. Ich habe nach der installation, des FTP servers, ein verzeichniss erstellt:
> /home/pi/Desktop/
Dieses Verzeichniss kannst du natürlich auch an jedem anderen ort erstellen.

![image](https://user-images.githubusercontent.com/63262820/135915732-fb9dda94-0c32-4951-b2e8-c556a2563e52.png)

![image](https://user-images.githubusercontent.com/63262820/135915797-1bfbe3f5-3126-4613-a691-47512b75fa79.png)

Nach der Installation kann ich über File zilla oder ähnlichen Programmen diesen FTP Server aufrufen.

![image](https://user-images.githubusercontent.com/63262820/135916454-6b8dc5af-0d52-46ea-acc4-0167347c9d37.png)





## 5. Qualitaetskontrolle (Pruefen der Funktionalitaet mit Ablauf von Kommandos und entsprechenden Outputs)

## 6. Error-Handling 

## 7. Quellen

## 8. OpenSource Lizenz

---

<a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/"><img alt="Creative Commons Lizenzvertrag" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-nd/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" href="http://purl.org/dc/dcmitype/Text" property="dct:title" rel="dct:type">M306-Services</span> von <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/Ga1i130/M306-Services" property="cc:attributionName" rel="cc:attributionURL">Ga1i130</a> ist lizenziert unter einer <a rel="license" href="http://creativecommons.org/licenses/by-nc-nd/4.0/">Creative Commons Namensnennung - Nicht kommerziell - Keine Bearbeitungen 4.0 International Lizenz</a>.
