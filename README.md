# CIELAB_to_DIN99o_transformation_GER
Vergleich der Spektralkurvenzüge und Elementarfarben im CIELAB und DIN99o Farbenraum sowie Vergleich der Streuung eines Testdatensatzes in beiden Farbenräumen und statistische Auswertung. 

Dieses Projekt untersucht und vergleicht Farbmessdaten, die in verschiedene Farbräume
(hier: CIELAB, DIN99o) dargestellt, transformiert und anschließend statistisch ausgewertet werden.
Die Ergebnisse werden in verschiedenen Diagrammen dargestellt.

## 🔍 Ziele
Das Projekt besteht im wesentlichen aus vier teilen. 

- Darstellung der Elementarfarben in in der a-b Ebene der Farbenräume CIELAB und DIN99o  
- Transformation und Darstellung der Spektralkurvenzüge im CIELAB und DIN99o Farbenraum in form von 2 und 3-Dimensionalen Diagrammen
- Vergleich der Streuung (Punktewolke) eines gemessenen Testdatensatzes im (3D) CIELAB und DIN99o Farbenraum
- Berechnung der Farbabstände des Testdatensatzes und Statistische auswertung mit visueller Darstellung der Ergebnisse



## 📊 Datengrundlage
Die Daten für die Elementarfarben und Spektralkurvenzüge stammen aus Excel-Dateien mit Werten für die Lichtart und Normspektralwerte für Spektralkurven (Normwerte). Zur überprüfung der funktion wurden die Testdaten aus dem Anhang von ISO 18134-5 verwendet. 
Die Messdaten des Testdatensatzes stammen aus Labormessungen und wurden als Dataframe in den Code kopiert.

## 🧠 Auswertung
- Transformation mit Python (numpy, pandas)
- 2D und 3D-Visualisierung (matplotlib)
- Statistische Auswertung: ΔE-Abstände, Verteilungen/ Häufigkeiten (seaborn, distfit)

## 🧾 Lizenz
Dieses Projekt steht unter der MIT-Lizenz.
