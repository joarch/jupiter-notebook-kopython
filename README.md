# Jupiter Notebook Beispiele

Die Daten werden beispielsweise per sqlalchemy aus einer Datenbank geladen.

## Installation

Eigene Umgebungsvariablen setzen (Datenbank Url und Python Virtual Environment) - cmd:
````
SET DATABASE_URL=...
SET VENV_PATH=...
````

Konfiguration einrichten - cmd:
````
md .config
echo SET database_url=%DATABASE_URL%>> .config/env.bat
echo SET venv=%VENV_PATH%>> .config/env.bat
````

Python VENV erstellen (python.exe ist im PATH oder kompletten Pfad zur exe angeben) - cmd:
````
python.exe -m venv %VENV_PATH%
````

Abhängigkeiten installieren - cmd:
````
%VENV_PATH%\Scripts\activate 
pip install -r requirements.txt
````

Starten:
````
start.bat
````
