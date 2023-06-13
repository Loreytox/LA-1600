# Projekt-Dokumentation

Lai, Warnebold, Oestrich, Veljkovic

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|09.05.2023| 0.0.1 |Wir haben einen ersten Prototyp der Website kreiert.|
|16.05.2023| 0.9.0 |Wir haben den grössten Teil unserer User Stories und mehr schon implementiert. (Julian Alexander Warnebold war nicht anwesend)|
|23.05.2023| 1.0.0 |Wir haben die erste Version unserer Website fertiggestellt. (Weil GitHub die Bilder nicht erkennen kann, sind ein paar Features "kaputt")|
|30.05.2023| 1.0.1 |Wir haben einen Teil unserer Zusatzfeatures/Verbesserungen implementiert.|
|06.06.2023| 1.9.0 |Wir haben den Handy Mode angepasst und Bugs gefixt.|
|13.06.2023| 2.0.0 |Wir haben unsere Website vollständig beendet und unsere Präsentation vorbereitet. Bezüglich Probleme haben wir den Dark-Mode und den Handy Mode verbessert und allfällige Störungen noch behoben.|

## 1 Informieren

### 1.1 Ihr Projekt

In diesem Projekt erstellen wir eine Webseite auf der Rezepte für verschiedene Pizzen gezeigt werden.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1 |  Muss  |  Funktional | Als User möchte ich ein Menu haben mit Optionen, z.B. Infos, Kontakt etc...
| 2 |  Kann  |  Qualität   | Als User möchte ich die Möglichkeit haben einen Dark-Mode anzuwählen, damit ich die Website auch in der Nacht ansehen kann.
| 3 |  Kann  |  Qualität   |  Als User möchte ich mit dem Mauszeiger über die gewollte Pizza fahren. Dabei sollten die benutzten Zutaten gezeigt werden, solange der Mauszeiger über die Pizza ist, damit ich weiss, wie die Pizza gemacht ist.  |
| 4 |  Muss  |  Funktional |  Als User möchte ich, dass man auch andere Sprachen auswählen kann, damit jeder die Webseite besuchen kann.  |
| 5 |  Kann  |  Funktional |  Als User möchte ich Informationen über die einzelnen Pizzen und die Firma lesen können, damit ich weiss, was ich überhaupt am Kaufen bin, um mehr Erfahrung darüber zu haben.  |
| 6 |  Muss  |  Qualität   |  Als User möchte ich, dass auf Mobilegeräten die Pizzen mittels flex-box geordnet werden.  |
| 7 |  Muss  |  Qualität   |  Als User möchte ich, dass die standardmässig verbleichten Pizzen beim Hovern farbig werden.  |
| 8 |  Muss  |  Qualität   |  Als User möchte ich, dass ich, wenn ich die Website auf dem Handy ansehen möchte, die Seite ansprechend gestaltet ist.  |
| 9 |  Kann  |  Funktional |  Als User möchte ich, dass wenn ich im Header auf eine bestimmte Kategorie klicke, ich direkt zu der entsprechenden Kategorie geschickt werde. (Website scrollt automatisch runter)
| 10 | Muss  |  Funktional |  Als User möchte ich, dass wenn der Filter aktiv ist, nur spezielle Pizzen gezeigt werden.  |

### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  |  Website geöffnet            |  Dropdown Liste sichtbar   |                                      |
| 2.1  |  Website geöffnet            |  Dark-Mode auswählen       |    Website wird dunkel               |
| 3.1  |  Website geöffnet            |  über Pizza fahren         |    Bild von Pizza                    |
| 4.1  |  Website geöffnet            |  Sprache auswählen         |    andere Sprache                    |
| 5.1  |  Website geöffnet            |  Anzahl Personen           |    Mengenangabe für Anzahl Personen  |
| 6.1  |  Website geöffnet            |  flex-box-Ordnung sichtbar |                                      |
| 7.1  |  Website geöffnet            |  über Pizza hovern         |    Pizza wird farbig                 |
| 8.1  |  Website auf Handy geöffnet  |  Website übersichtlich wie auf Desktop |                          |
| 9.1  |  Website geöffnet            |  Kategorie auswählen       |    Man landet automatisch bei der ausgewählten Kategorie  |
| 10.1 |  Website geöffnet            |  Filter aktivieren         |    nur spezielle Pizzen angezeigt    |


### 1.4 Diagramme

![MicrosoftTeams-image](https://user-images.githubusercontent.com/110892495/237048334-93fceb6a-775d-4062-86c9-f0a18128ebb8.png)



![LA1600(2) drawio](https://github.com/Loreytox/LA-1600/assets/110893594/a0426691-258d-4309-8ea0-4f3796426064)



## 2 Planen
Geplante Zeit in Minuten.

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  |   09.05    |     Pascal      |      Menu programmieren (HTML)        |       45       |
| 1.B  |   09.05    |    Lorenzo/Alexander/Simon       |       Menu Design      |       30        |
| 1.C  |   09.05    |     Pascal      |      Menu implementieren/anpassen        |       15       |
| 2.A  |   16.05    |     Alexander/Lorenzo/Simon      |      Dark-Mode Design und Skizze        |       25        |
| 2.B  |   16.05    |     Pascal/Lorenzo      |       Dark-Mode programmieren       |       45        |
| 2.C  |   16.05    |     Pascal/Lorenzo      |       Dark-Mode implementieren       |       15        |
| 3.A  |   16.05    |     Alexander      |       Bildanimation Idee und Design       |       15        |
| 3.B  |   16.05    |     Pascal/Alexander      |       Bildanimation programmieren       |        45       |
| 3.C  |   16.05    |     Pascal/Alexander      |       Bildanimation implementieren       |        25       |
| 4.A  |   16.05    |     Lorenzo/Alexander/Simon     |       Sprachauswahl (Design und Skizze)       |        15       |
| 4.B  |   16.05    |     Pascal/Lorenzo      |       Sprachauswahl programmieren       |        45       |
| 4.C  |   16.05    |     Pascal/Lorenzo      |       Sprachauswahl implementieren (erweitern)       |       30       |
| 5.A  |   16.05    |     Simon      |       Informationen (Idee und Design)     |       10       |
| 5.B  |   16.05    |     Pascal/Alexander      |       Informationen programmieren       |        25       |
| 5.C  |   16.05    |     Pascal/Alexander      |      Informationen implementieren, anpassen     |        10       |
| 6.A  |   30.05    |     Lorenzo/Alexander/Simon    |       flex-box designen        |       10       |
| 6.B  |   30.05    |     Pascal/Lorenzo        |      flex-box programmieren         |       45       |
| 6.C  |   30.05    |     Pascal/Alexander      |      flex-box implementieren        |       20       |
| 7.A  |   06.06    |     Lorenzo/Alexander/Simon    |       Farbfilter designen      |       10       |
| 7.B  |   06.06    |     Pascal/Lorenzo        |      Farbfilter programmieren       |       45       |
| 7.C  |   06.06    |     Pascal/Alexander      |      Farbfilter implementieren      |       20       |
| 8.A  |   06.06    |     Lorenzo/Alexander/Simon    |       Handy Mode designen      |       10       |
| 8.B  |   06.06    |     Pascal/Lorenzo        |      Handy Mode programmieren       |       45       |
| 8.C  |   06.06    |     Pascal/Alexander      |      Handy Mode implementieren      |       20       |
| 9.A  |   06.06    |     Lorenzo/Alexander/Simon    |       automatisches Scrollen designen      |       10       |
| 9.B  |   06.06    |     Pascal/Lorenzo        |      automatisches Scrollen programmieren    |      45      |
| 9.C  |   06.06    |     Pascal/Alexander      |      automatisches Scrollen implementieren   |      20      |
| 10.A |   13.06    |     Lorenzo/Alexander/Simon    |       Spezialfilter designen               |       10       |
| 10.B |   13.06    |     Pascal/Lorenzo        |      Spezialfilter programmieren             |      45      |
| 10.C |   13.06    |     Pascal/Alexander      |      Spezialfilter implementieren            |      20      |
Total: 30 Arbeitspakete


## 3 Entscheiden

Wir haben uns entschieden eine Website mit Rezepten für Pizzen zu erstellen.
Wir machen es mit HTML und CSS.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  | 09.05 | Pascal    | 45 Min        | 60 Min             |
| 1.B  | 09.05 | Lorenzo, Alexander, Simon | 30 Min             | 30 Min             |
| 1.C  | 09.05 | Pascal    | 15 Min        | 20 Min             |
| 2.A  | 16.05 | Alexander, Lorenzo, Simon | 25 Min             | 25 Min             |
| 2.B  | 16.05 | Pascal, Lorenzo   | 45 Min               | 40 Min              |
| 2.C  | 16.05 | Pascal, Lorenzo   | 15 Min               | 30 Min              |
| 3.A  | 16.05 | Alexander | 15 Min        | 15 Min             |
| 3.B  | 16.05 | Pascal, Alexander | 45 Min               | 75 Min              |
| 3.C  | 16.05 | Pascal, Alexander | 25 Min               | 30 Min              |
| 5.A  | 16.05 | Simon     | 10 Min        | 20 Min             |
| 5.B  | 16.05 | Pascal, Alexander | 25 Min               | 15 Min              |
| 5.C  | 16.05 | Pascal, Alexander | 10 Min               | 10 Min              |
| 6.A  | 30.05 | Lorenzo, Alexander, Simon | 10 Min             | 30 Min              |
| 6.B  | 30.05 | Pascal, Lorenzo   | 45 Min               | 45 Min              |
| 6.C  | 30.05 | Pascal, Alexander | 20 Min               | 30 Min              |
| 7.A  | 06.06 | Lorenzo, Alexander, Simon | 10 Min             | 20 Min              |
| 7.B  | 06.06 | Pascal, Lorenzo   | 45 Min               | 30 Min              |
| 7.C  | 06.06 | Pascal, Alexander | 20 Min               | 20 Min              |
| 8.A  | 06.06 | Lorenzo, Alexander, Simon | 10 Min             | 10 Min              |
| 8.B  | 06.06 | Pascal, Lorenzo   | 45 Min               | 120 Min             |
| 8.C  | 06.06 | Pascal, Alexander | 20 Min               | 40 Min              |
| 9.A  | 06.06 | Lorenzo, ALexander, Simon | 10 Min             | 10 Min              |
| 9.B  | 06.06 | Pascal, Lorenzo   | 45 Min               | 45 Min              |
| 9.C  | 06.06 | Pascal, Alexander | 20 Min               | 20 Min              |
| 10.A | 13.06 | Lorenzo, Alexander, Simon | 10 Min             | 20 Min              |
| 10.B | 13.06 | Pascal, Lorenzo   | 45 Min               | 30 Min              | 
| 10.C | 13.06 | Pascal, Alexander | 20 Min               | 20 Min              |

*Arbeitspaket 4 haben wir nicht gemacht.


## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  | 13.06      | OK         | Simon       |
| 2.1  | 13.06      | OK         | Simon       |
| 3.1  | 13.06      | OK         | Simon       |
| 4.1  | 13.06      | NOK        | Simon       |
| 5.1  | 13.06      | OK         | Simon       |
| 6.1  | 13.06      | OK         | Simon       |
| 7.1  | 13.06      | OK         | Simon       |
| 8.1  | 13.06      | OK         | Simon       |
| 9.1  | 13.06      | OK         | Simon       |
| 10.1 | 13.06      | OK         | Simon       |



### 5.2 Exploratives Testen

| BR-№ | Ausgangslage | Eingabe | Erwartete Ausgabe | Tatsächliche Ausgabe |
| ---- | ------------ | ------- | ----------------- | -------------------- |
| I    |              |         |                   |                      |
| ...  |              |         |                   |                      |

✍️ Verwenden Sie römische Ziffern für Ihre Bug Reports, also I, II, III, IV etc.

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.
