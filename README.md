# Rauchausbeuten
Ermittlung von Rauchausbeuten für Brandsimulationen

## FDS/Validate_EPUMO2

Begrifflichkeiten
- vc: ventilationsgesteuert (ventilation-controlled)
- wv: brandlastgesteuert (well-ventilated)

case | fuel                 | Formula             | HEAT_OF_COMBUSTION | SOOT_YIELD | CO_YIELD | HCN_YIELD |
-----| ---------------------|-------------------- | -------------------|------------|----------|-----------|
0_vc | Wood (redoak)        | C6.0H10.0O6.0N0.0   | 10880              | 0.028      | 0.145    | 0.0       |
0_wv | Wood (redoak)        | C6.0H10.0O6.0N0.0   | 12400              | 0.015      | 0.004    | 0.0       |
1_vc | PE foam (mean)       | C2.0H4.0O0.3N0.0    | 29135              | 0.124      | 0.338    | 0.0       |
1_wv | PE foam (mean)       | C2.0H4.0O0.3N0.0    | 34225              | 0.07625    | 0.02025  | 0.0       |
2_vc | PS                   | C8.0H7.9O1.0N0.0    | 20544              | 0.33       | 0.137    | 0.0       |
2_wv | PS                   | C8.0H7.9O1.0N0.0    | 27000              | 0.164      | 0.06     | 0.0       |
4_vc | PUR foam rgid (mean) | C6.2H7.1O2.3N1.1    | 7813               | 0.236      | 0.59     | 0.0472    |
4_wv | PUR foam rgid (mean) | C6.2H7.1O2.3N1.1    | 16925              | 0.118      | 0.0295   | 0.023599  |
## FDS/BBR

Brandszenarien zur Überprüfung des geänderten und erweiterten Konzeptes zur Quantifizierung der Ruß- und Schadstofffreisetzung bei Brandsimulationen für den *Leitfaden Ingenieurmethoden des Brandschutzes* des Referats 4 des Vereinigung zur Förderung des Deutschen Brandschutzes e.V. (vfdb). 

Das Modell basiert auf dem Anwendungsbeispiel für Ingenieurmethoden des Brandschutzes eines Bürogebäudes mit Atrium im "*Brandschutzleitfaden für Gebäude des Bundes*":

Zehfuß, Jochen; Siemon, Matthias: **Anwendungsbeispiel** *Anwendung von Ingenieurmethoden am Beispiel eines Bürogebäudes mit Atrium zum Nachweis der Personen- und Standsicherheit im Brandfall*. TU Braunschweig, Institut für Baustoffe, Massivbau und Brandschutz (iBMB), Januar 2015
