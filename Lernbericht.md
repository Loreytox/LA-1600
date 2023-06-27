# Lern-Bericht
Goji (Pascal Oestrich, Simon Veljkovic, Julian Alexander.Warnebold, Lorenzo Lai)

## Einleitung

In diesem Projekt haben wir selbst eine Pizza Webseite erstellt, mit hilfe von HTML und CSS.

## Was habe ich gelernt?

Wir haben gelernt, wie man Flex-Boxen richtig verwenden kann und wo man sie anwenden kann.

## Beschreibung

`Flexbox` ist ein leistungsstarkes CSS-Layout-Modell, das uns ermöglicht, `Elemente` innerhalb eines `Containers` flexibel und effizient zu positionieren. Wir können die Ausrichtung, Reihenfolge und Grösse der Elemente mit Hilfe von Flex-boxen steuern, indem wir dem Container und den darin enthaltenen Elementen entsprechende `Eigenschaften` zuweisen. Mit Hilfe von Flex-Boxen können wir komplexe Layout-Herausforderungen meistern und gleichzeitig `responsives Design` erstellen, das sich an verschiedene Bildschirmgrössen anpasst und das ist alles möglich, ohne die anwendug von JS.

Um eine Flexbox zu erstellen, schreibt man im HTML einen Container, der eine bestimmte klasse wie `Flex-Box` hat. Danach kann man in dem Container weitere Container wie `Flex-Item` anlegen, die alle haben die gleiche klasse.

![image](https://github.com/Loreytox/LA-1600/assets/110892258/42ab7e9f-3f79-406f-9a48-ede1479bda61)

Um nun eine Flexbox zu erstellen muss man in CSS gewisse Codes verwenden.
```CSS
.Flex-Box {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
  align-items: stretch;
  border-radius: 10px;
  padding: 20px;
}
.Flex-Item {
  flex: 1;
  text-align: left;
  background-color: #1e1f26;
  letter-spacing: 0.5rem;
  box-shadow: 20px 20px 50px rgba(0, 0, 0, 0.5);
  min-height: 400px;
  margin: 20px;
}
```
Um jetzt eine Flexbox zu erstellen, schreibt man `display: flex;`. Das `display: flex;` sorgt dafür, dass alle direkten Nachkommende Container im Flexcontainer in einer Zeile oder Spalte geordnet werden. Danach kann man angeben, wie die Flexitems aufgerheit und sortiert werden. Im Containerr Flex-Item kann kann man nun die jeweiligen Items / Container nach aussehen, grösse definieren (z.B. man kann auch mit `box-shadow` wählen, ob es ein Schatteneffekt haben sollte).  Dazu dient auch das `flex: 1;`. im obrigen Beispiel dient dies für die Festlegung der Proportionen. Die Zahl dahinter bestimmt einen Modus. Bei 1 wird der Container im gleichen Verhälntis wie die Fenstergrösse verkleinert. Bei 0 , hat der Container keine startwerte und bei 3 nimmt der Container eine grösse von 33% von der Flexbox ein.

Das wäre das Endresultat:
![7qpmho](https://github.com/Loreytox/LA-1600/assets/110893594/7e5970ce-002f-4f3d-af0d-5d59d38be6b5)

## Verifikation

* Der Text erklärt, was eine Flexbox ist, für was sie gebraucht wird und wie man eine erstellt.
* Das Bild (HTML) und der Codeschnipsel (CSS) zeigt wie eine Flexbox in der Praxis aussieht.
* Das GIF zeigt, den HTML und CSS Code und die dazugehörende Website. Das GIF stellt dar, wie die Flexbox in unsere Website aussieht. 

# Reflexion zum Arbeitsprozess

👍 Überlegen Sie sich jeweils etwas, was gut an Ihrer Arbeit lief; 

👎 und etwas, was nicht gut lief.

**VBV**: ✍️ Formulieren Sie davon ausgehend einen *handelbaren* Verbesserungsvorschlag.
