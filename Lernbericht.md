# Lern-Bericht
Goji (Pascal Oestrich, Simon Veljkovic, Julian Alexander.Warnebold, Lorenzo Lai)

## Einleitung

In diesem Projekt haben wir selbst eine Pizza Webseite erstellt, mithilfe von HTML und CSS.

## Was habe ich gelernt?

Wir haben gelernt, wie man Flex-Boxen richtig anwenden und verwenden können.

## Beschreibung

`Flexbox` ist ein leistungsstarkes CSS-Layout-Modell, das uns ermöglicht, `Elemente` innerhalb eines `Containers` flexibel und effizient zu positionieren. Wir können die Ausrichtung, Reihenfolge und Grösse der Elemente mithilfe von Flex-boxen steuern, indem wir dem Container und den darin enthaltenen Elementen entsprechende `Eigenschaften` zuweisen. Mithilfe von Flex-Boxen können wir komplexe Layout-Herausforderungen meistern und gleichzeitig `responsives Design` erstellen, das sich an verschiedene Bildschirmgrössen anpasst und das ist alles ohne die Anwendung von JS möglich.

Um eine Flexbox zu erstellen, schreibt man in HTML einen Container, der eine bestimmte Klasse wie `Flex-Box` hat. Danach kann man in dem Container weitere Container wie `Flex-Item` anlegen, die alle haben die gleiche klasse.

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
Um eine Flexbox zu erstellen, schreibt man `display: flex;`. Das `display: flex;` sorgt dafür, dass alle direkten nachkommenden Container im Flexcontainer in einer Zeile oder Spalte geordnet werden. Danach kann man angeben, wie die Flexitems aufgereiht und sortiert werden. Im Container Flex-Item kann man nun die jeweiligen Items / Container nach Aussehen und Grösse definieren (z.B. kann auch mit `box-shadow` wählen, ob es einen Schatteneffekt haben sollte).  Dazu dient auch das `flex: 1;`. Im obigen Beispiel dient dies für die Festlegung der Proportionen. Die Zahl dahinter bestimmt einen Modus. Bei 1 wird der Container im gleichen Verhältnis wie die Fenstergrösse verkleinert. Bei 0 hat der Container keine Startwerte und bei 3 nimmt der Container eine Grösse von 33% von der Flexbox ein.

Das wäre die Flexbox von unserer Website:

![7qpmho](https://github.com/Loreytox/LA-1600/assets/110893594/7e5970ce-002f-4f3d-af0d-5d59d38be6b5)

## Verifikation

* Der Text erklärt, was eine Flexbox ist, für was sie gebraucht wird und wie man eine erstellt.
* Das Bild (HTML) und der Codeschnipsel (CSS) zeigt, wie eine Flexbox in der Praxis aussieht.
* Das GIF zeigt den HTML und CSS Code und die dazugehörende Website. Das GIF stellt dar, wie die Flexbox in unserer Website aussieht. 

# Reflexion zum Arbeitsprozess

Obwohl es grosse Schwierigkeiten gab, konnten wir dennoch alle unsere Ziele erreichen. Es gab eine gute und geplante Koordination, bei der jeder seinen Auftrag hatte.

Es lief alles ziemlich gut, ausser bei einem von uns.

**VBV**: Obwohl wir dieses Mal gut zusammengearbeitet haben, bedeutet das nicht, dass wir uns nicht weiter verbessern können. Für das nächste Mal schlage ich vor, dass wir mehrmals pro Woche den Fortschritt aller Aufträge überprüfen, um den Überblick darüber zu behalten, wo wir stehen.
