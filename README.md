# Geospatial Data Analysis mit Python

## Zweck

Dies ist das Repository für **öffentliche** Skripte, die bei Geoinformation Winterthur im Bereich der **räumlichen Datenanalyse** und der **Datenbereitstellung** entstanden sind. Wenn also Aufträge im Bereich der räumlichen Datenanalyse oder der Datenbereitstellung erarbeitet werden, dann werden die dazugehörigen Skripte (und in geringem Umfang auch Geodaten) hier abgelegt. Dieses Repository ist speziell für Python-Skripte vorgesehen.

## Wie starten?

In den einzelnen Analysis-Projekten (Unterordnern wie z.B. `Amt für Städtebau/Gebäude_in_Pünten_als_SHP`) sind die Bibliotheken aus `requirements.txt` zu installieren. Dazu muss im jeweiligen Pipeline-Projekt-Ordner ein **Python Virtual Environment** (_venv_) installiert werden (dazu im Projekt-Verzeichnis also z.B. in `Amt für Städtebau/Gebäude_in_Pünten_als_SHP` aufzurufen):

- `python3 -m venv venv` (Linux)
- `python -m venv venv` (Windows)

Danach kann das neu erstellte _venv_ des Projekts aktiviert werden mit dem Befehl: 

- `source venv/bin/activate` (Linux)
- `source venv/Scripts/activate` (Windows)

Anschliessend können Bibliotheken in _venv_ installiert werden:

`pip install -r requirements.txt`

Ab jetzt können die Python-Skripte ausgeführt werden.

Nach der Ausführung sollte das _Virtual Environment_ beenden werden:

`deactivate`
