# LB 324

## Aufgabe 2
Erklären Sie hier, wie man `pre-commit` installiert.

Schritt 1:
Pip muss auf dem Gerät vorhanden sein, dies überprüft man in der Konsole mit:
pip --version

Schritt 2:
Alle dependencies aus requirements installieren, dies macht man mit folgendem Befehl:
pip install -r requirements.txt

Schritt 3:
Der Programmierer muss nur einmalig den folgenden Befehl ausführen, um die Pre-commit-Hooks zu initialisieren und zu installieren. 
Dies sollte zu Beginn des Projekts oder nach jeder Aktualisierung der .pre-commit-config.yaml-Datei erfolgen:
pre-commit install


## Aufgabe 4
Erklären Sie hier, wie Sie das Passwort aus Ihrer lokalen `.env` auf Azure übertragen.
