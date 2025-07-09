# Klassifikation-mit-R
Assignment: Klassifikation mit R

In der Fallstudie IMG602 wird der Fahrradhersteller HaMa-Cycle vorgestellt, der erfolgreich 
Fahrräder produziert und verkauft. Dieser setzt zur Optimierung seiner Entscheidungen und 
Prozesse verschiedene Business-Intelligence-Datenanalysen ein. Dazu gehören auch statistische 
Datenanalysen (siehe hierzu auch Studienbrief IMG601). Nachfolgend dürfen Sie HaMa-Cycle bei 
einer Klassifikation von Kundendaten unterstützen. 
Aufgabe: 
In der Fallstudie IMG602 ist der Aufbau einer Big-Data-Umgebung bei HaMa-Cycle beschrieben. 
Dabei wird auch erläutert, welche Daten HaMa-Cycle bei externen Datenlieferanten einkauft, um 
Kundenmerkmale für ein besseres Marketing zu verwenden. Dies soll nachfolgend durch eine 
Klassifikationsanalyse unterstützt werden, in der Regeln gesucht werden, die anhand der 
Kundenmerkmale die Preiskategorie der gekauften Fahrräder (niedrig, mittel, hoch) vorhersagen 
können.  
Am Ende der Aufgabenstellung finden sich die Kundenmerkmale sowie die Preiskategorie 
gekaufter Räder in Tabellenform. Kopieren Sie diese Daten in eine Textdatei, diese kann dann als 
CSV-Datei in Ihr R-Programm geladen werden. 
a) Die Klassifikation soll nur auf 80 Prozent der Daten ausgeführt werden, die verbliebenen 20 
Prozent dienen zum Testen des ermittelten Klassifikators. Teilen sie die Daten 
entsprechend auf (sample-Funktion in R). 
b) Erstellen Sie mit den 80 Prozent Trainingsdaten einen Entscheidungsbaum zur Vorhersage 
der Preiskategorie. 
c) Testen Sie den Entscheidungsbaum anhand der Testdaten. Ermitteln Sie so die 
Vorhersagegenauigkeit des Entscheidungsbaums. 
d) Wiederholen Sie die vorherigen Schritte mit anderen Trainingsdaten mehrmals und prüfen 
Sie so die Stabilität der Regeln bei einer unterschiedlichen Auswahl der 80 Prozent an 
Trainingsdaten. 
e) Ermitteln Sie mit Hilfe des Entscheidungsbaums die Kunden, die sich atypisch verhalten 
haben. 

