# Kein-PV-Überschuss
Ein System-Design das hilft PV-Einspeisung ins Netz so gering wie möglich zu halten, indem die Energie lokal verwendet wird

# Vorwort
Die Energie-Produktion von PV-Generatoren(PV-Panele) ist gebunden an die Sonneneinstrahlung und daher mehr oder weniger vorhersagbar. Den erzeugten Strom so viel wie möglich selbst zu nutzen und daher den Export in das Netz zu minimiern ist Ziel dieses Repositories.

# Lösungsansätze
Um das zuvor genannte Ziel, die maxinale Reduktion des Exports, zu erreichen gibt es mehrere Lösungsansätze. Diese werden hier im folgenden Aufgelistet. Die Reihenfolge der Auflistung spiegelt nicht die prevalenz einzelner Lösungsansätze wieder. Hier erfolgt nur eine Auflistung von Ideen. Eine genauer Analyse der Vor- und Nachteile bzw. limitierender Faktoren erfolgt gesondert zu einem späteren Zeitpunkt.

* Überschuss in Batterie speichern für Nachtstunden/als Backup
* E-Auto mit Überschuss laden
* Überschuss in thermische Energie wandeln(WP/Heizpatrone) und für Warmwasser/Heizung verwenden

# Anforderungen
Unabhängig von der jeweiligen Lösung sind einige Dinge immer zu erfüllen. Hierzu zählen die folgenden Punkte. Dabei handelt es sich um grundlegende Anforderungen sowie "weiche" Anforderungen. Die Reihenfolge der Anforderungen spiegelt nicht deren Wichtigkeit wieder.

1. Messen der aktuellen Produktion, des lokalen Verbrauchs und des Exports in das Netz
2. Vorausberechnung des kurzzeit (1-Minute) und mittelzeits(1-Stunde) Export in das Netz
3. Ansteuern "fester" Lasten (Ein/Aus)
4. Regeln variabler Lasten (0-100%)
5. Entgegennehmen von zu verbrauchenden Last-Werten in W bzw. kW über Schnittstelle-Extern, um diese im folgenden zu steuern bzw. zu regeln
6. Aufzeichnen aller Mess-, Steuer- & Regelwerte für eine nachgelagerte Visualisierung und Langzeitanalyse
7. Visualisierung der Mess-, Steuer- & Regelwerte sowie der Langzeitanalyse

# PV-System sizing
* https://globalsolaratlas.info/map?s=47.967586,12.596563&m=site&c=47.958548,12.526817,12

# Monitoring von Verbrauch für statistische Auswertung
* https://www.german-metering.de/auslesekopf-produkte.html


# Hersteller
Liste an Herstellern für Komponenten und Systeme.

## Carlo Gavazzi
* https://www.mouser.de/datasheet/2/1032/SSR_NRGC-2525226.pdf
* https://www.gavazzionline.com/pdf/SSR_RG_CM_N.pdf

## Chiemtronic
* https://www.chiemtronic.de/prod_kat/chiemtronic/thyristorsteller/

## SmartFox
* https://www.smartfox.at/smartfox-pro.html

## Technische Alternative
* https://www.ta.co.at/x2-energiemanagement/aton-power-to-heat/

## Victron Energy
* https://www.victronenergy.com/upload/documents/MultiPlus-II_GX/MultiPlus-II_GX-de.pdf
