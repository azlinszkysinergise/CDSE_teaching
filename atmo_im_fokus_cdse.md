5 minuten über CDSE

 - Datenvolumen, Cloudverarbeitung, Öffentliche Infrastruktur
 
 - Browser, Jupyter Lab, GitHub
 
 - Sentinel Hub und openEO API-s

Intro zum Hands-on:

drei Teile:
 - Copernicus Browser kennenlernen - was kann man alles im Browser machen
 
 - Relevante Datensätze für Klimaforschung, Wettermonitoring und Gesundheit im Copernicus Browser

 - Einleitung zur Datenanalyse im CDSE
 
** Teil 1: Copernicus Browser kennenlernen **

DWD-Standort - Offenbach am Main - Sentinel-2 Mosaic: https://link.dataspace.copernicus.eu/gt7c 
  - gleich Sprache wählen, zoom, pan, layer/ebene verändern
  
  - Sentinel-2 (Datensets - Sentinel-2 - aktuellstes Datum anzeigen (14 November 2026) https://link.dataspace.copernicus.eu/61ey
  Untersuchungsgebiete 
  - Laubwald {"type":"Polygon","coordinates":[[[8.724775,50.079919],[8.724775,50.081049],[8.727479,50.081049],[8.727479,50.079919],[8.724775,50.079919]]]} 
  - Nadelwald {"type":"Polygon","coordinates":[[[8.72735,50.077413],[8.72735,50.078515],[8.729496,50.078515],[8.729496,50.077413],[8.72735,50.077413]]]} 
  - Gebäude {"type":"Polygon","coordinates":[[[8.746362,50.084188],[8.745933,50.08361],[8.747134,50.083252],[8.747778,50.083912],[8.746362,50.084188]]]}
  
  - NIR Infrarot komposit https://link.dataspace.copernicus.eu/udd4
  
  - SWIR komposit https://link.dataspace.copernicus.eu/fxkp
  
  - Scene Classification Layer - Wolkenmaske/Bodenbedeckung/Datenqualität für einzelnen Pixel https://link.dataspace.copernicus.eu/mlid
  
  - Feuchtigkeitsindex https://link.dataspace.copernicus.eu/41vt
  
  - Kalenderfeld - Bewölkungsgradschwellenwert
  
  - Vergleich zwischen Sentinel-2 Feuchtigkeitsindex November 14 /Juni 27 https://link.dataspace.copernicus.eu/3yca
  
  - Zeitreihen berechnen bzw. Exportieren: Datenebene wählen (zB Feuchtigkeitsindex), Untersuchungsgebiet zeichnen bzw. Hochladen, Statistik-tool wählen, Zeitraum und Wolkenmaske einstellen
  - Histogramm
  
  - Daten herunterlanden (Basic, für Datenanalyse, Hochauflösend)
  
  - Zeitrafferanimation
  
  - Teilen - Kurz-URL generieren
  
** Teil 2: Datensätze für Klima, Wetter, Gesundheit (kurzer Überblick) **

- Sentinel-2 zeigt Waldbrände - Waldbrand Hürtgenwald, 14 August 2026 https://link.dataspace.copernicus.eu/zx2v

- Sentinel-2 Mosaics dienen als Hintergrund - und zeigen Ereignisse, die große Flächen und längere Zeiträume betreffen:  Dürre in Frankreich 2026 https://link.dataspace.copernicus.eu/rd0y

- Sentinel-3 zeigt Staubtransport und Oberflächentemperatur
  - Staubwolke aus der Sahara 15 März 2022 https://link.dataspace.copernicus.eu/eheb (Frankreich, Spanien) bzw 
  - 8 April 2024 https://link.dataspace.copernicus.eu/rcte (Italien, Schweiz, auch Süddeutschland)
  - Oberflächentemperatur 29 Juli 2026, Frankfurt und Umgebung https://link.dataspace.copernicus.eu/3gif (Temperaturskala im Menu beim Ebene)
  
- Sentinel-5P
  - Aerosolkonzentration Sahara Staubtransport 8 April 2024 https://link.dataspace.copernicus.eu/dru6
  - Methan über Braunkohletagebaustellen Garzweiler Inden, 5 März 2026 https://link.dataspace.copernicus.eu/odc1
  - Wolken - zB Höhe der Wolkenobergrenze, 28 August 2026 https://link.dataspace.copernicus.eu/tfxb (dient nicht als Wettersatellit, Wolkendaten werden für atmosphärische Korrekturprozesse gesammelt)
  - Kohlenmonoxid - Ruhrgebiet, Stahlwerke 13 August 2026   
    - https://link.dataspace.copernicus.eu/9mk4 
    - Waldbrand Hürtgenwald 14 August https://link.dataspace.copernicus.eu/tn8x
  - NO2 Stickstoffdioxid - Luftkurort St. Blasien im Schwarzwald, Vergleich 5 Juni 2019 vs 7 Juni 2019 (Anfang der Sommerferien) https://link.dataspace.copernicus.eu/74zl
  - NO2 Stickstoffdioxid Monatsdurchschnitt (Custom script) Vergleich Oktober 2018 vs Oktober 2025 https://link.dataspace.copernicus.eu/bm7x
  
- Copernicus Land Monitoring Service - abgeleitete Daten für Monitoring - kalibrierte Werte statt optischen Daten von Pixel
  - Flächendeckung - Land Cover and Land Use Corine Land Cover Plus 100 m, München, 2023 https://link.dataspace.copernicus.eu/7e6m
  - Flächendeckung - Land Cover and Land Use in Priority Areas - Urban Atlas (Vektordaten!) München 2021 https://link.dataspace.copernicus.eu/7i24
  - Bedeckungsgrad von Bäumen - Tree Cover Density - Hamburg 2024 https://link.dataspace.copernicus.eu/bbdv
  
  - Bio-geophysical parameters/Soil Moisture Bodenfeuchtigkeit (aus Radardaten) - 2 October 2026 https://link.dataspace.copernicus.eu/bm7w
  - Oberflächentemperatur (aus geostationären Satellitendaten) [[zeitpunkt genau einstellen] - 3km 27 Mai 2026 https://link.dataspace.copernicus.eu/0sp6
  
- Copernicus Contributing Missions - Hochauflösende Daten im Intervall von 3 Jahren (2018, 2021, 2024) - nur für öffentliche Behörden. Für Zugang muss ein Formular ausgefüllt werden im Userprofil
  - CCM VHR 2024 Mosaic - Neubrandenburg https://link.dataspace.copernicus.eu/vpgc
  
- Complementary Data - Landsat
  - Hochauflösende Thermaldaten - Berlin 02 Juli 2025 https://link.dataspace.copernicus.eu/k6jv
  . Historisches Archiv 2-Monatskompositdaten für Landsat - Schönefeld 1997 vs 2026 link.dataspace.copernicus.eu/ikg6  

- WMS
  - 20 cm Luftbilder für Schleswig-Holstein https://service.gdi-sh.de/WMS_SH_DOP20col_OpenGBD?SERVICE=WMS&VERSION=1.1.1&REQUEST=GetCapabilities  kann als Pin geteilt werden: https://browser.dataspace.copernicus.eu/?sharedPinsListId=6c0a5f22-8bee-48a6-a712-0bd2778c9308 (Strandsauna Rantum, Sylt)
  
  
  
** Teil 3: Arbeiten mit CDSE **

- Eigene Scripts erstellen und anwenden - Deep Moist Convection (https://custom-scripts.sentinel-hub.com/sentinel-2/deep_moist_convection/)
  - "hochreichende Feuchtkonvektion" in Franken, Sentinel-2 L1C 29 Juni 2026 https://link.dataspace.copernicus.eu/icix oder Thüringen/Franken 14 Juli 2026: Echtfarben: https://link.dataspace.copernicus.eu/g9x6;  "Deep Moist Convection script" https://link.dataspace.copernicus.eu/y5u3

- Konfigurationen
  - Eigene Konfiguration erstellen - auch aus eigenen Scripts: https://shapps.dataspace.copernicus.eu/dashboard/#/configurations (config Atmosphäre im Fokus - LST)
  
- Jupyter Lab
  - Sentinel Hub API-s kennenlernen: https://github.com/eu-cdse/notebook-samples/blob/main/sentinelhub/getting_started/introduction_to_SH_APIs.ipynb
  - Luftverschmutzungsstatistiken berechnen für europäische Städte: https://github.com/eu-cdse/notebook-samples/blob/main/sentinelhub/use_cases/air_pollution_statistics.ipynb
