# LB 324

## Aufgabe 2
Erklären Sie hier, wie man `pre-commit` installiert.

Schritt 1:   
Pip muss auf dem Gerät vorhanden sein, dies überprüft man in der Konsole mit:  
```bash
pip --version
```

Schritt 2:  
Alle dependencies aus requirements installieren, dies macht man mit folgendem Befehl:  
```bash
pip install -r requirements.txt
```

Schritt 3:  
Der Programmierer muss nur einmalig den folgenden Befehl ausführen, um die Pre-commit-Hooks zu initialisieren und zu installieren. 
Dies sollte zu Beginn des Projekts oder nach jeder Aktualisierung der .pre-commit-config.yaml-Datei erfolgen:  
```bash
pre-commit install
```


## Aufgabe 4
Erklären Sie hier, wie Sie das Passwort aus Ihrer lokalen `.env` auf Azure übertragen.  
https://brunokowskinielslb-324.azurewebsites.net

Schritt 1:  
Gehen Sie zur Seite Ihrer erstellten App Service-Instanz im Azure-Portal.

Schritt 2:  
Wählen Sie im linken Menü unter dem Abschnitt "Einstellungen" den Slot "Konfiguration" aus.

Schritt 3:  
Unter "Anwendungseinstellungen" können Sie geheime Umgebungsvariablen hinzufügen.  
Erstellen Sie eine Variable mit dem Namen "PASSWORD" und dem entsprechenden geheimen Passwortwert aus der lokalen .env-Datei.
