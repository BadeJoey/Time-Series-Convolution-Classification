# Time-Series-Convolution-Classification
### Deutsche Info 🇩🇪

Dies ist eine Implementierung eines Convolutional-Modells für eine Time-Series-Klassifzierung.

Es wird implementiert:
- Ein Logger, der die besten Hyperparameter für jeden Run speichert
- 3 verschiedene Modi: 
  - Normal
  - GridSearch
  - RandomSearch
- Einlesen des bisherigen besten Ergebnis und Vergleich mit aktuellem Run
- Ist der aktuelle Run besser, werden seine Hyperparameter in einer JSON-Datei gespeichert
- Speichern des besten Modells und einer visuellen Repräsentation des besten Modells

---

### English Info 🇺🇸

This is a Convolution Model for a Time Series Classification.

It implements:
- A logger that saves the best Hyperparameter of every run
- 3 modes of operation: 
  - Normal
  - GridSearch
  - RandomSearch
- Reading the best accuracy from a JSON File and compare it to current accuracy
- If current accuracy is better, than save its hyperparameter as JSON-File
- Saves the best model and a visual representation of the best model


