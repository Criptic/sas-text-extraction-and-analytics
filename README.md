# Wie kann ich mit TEXT-Analytics Twitter Feeds vorsortieren, um Hinweise auf mögliche Katastrophenfälle zu erhalten?

Begleitend zu diesem Repository gibt es ein [Ask the Expert](https://www.sas.com/de_de/webinars/ask-the-expert-serie-wie-kann-ich-mit-text-analytics-twitter-feeds-vorsortieren.html) Seminar welches am 10.11.2022 gehalten wurde und jetzt On-Demand zur Verfügung steht.

Die Daten für dieses Beispiel können von kaggle heruntergeladen werden: https://www.kaggle.com/competitions/nlp-getting-started/data

Um das Beispiel zu nutzen bitte den folgenden vier Schritten folgen:

1. Im SAS Studio [Extract Text Features.step](./Extract Text Features.step) hochladen
2. Im SAS Studio [AtE Extra Text Features.flw](./AtE Extra Text Features.flw) hochladen
3. Im SAS Studio auf einen Pfad im Server-Datei-System *train.csv* von Kaggle hochladen
4. Im Flow, in dem SAS Programm *Daten bereinigen* den Pfad der in der Makrovariable *pathToTrain* steht entsprechend auf die eigene Umgebung anpassen
5. Laufen lassen hätte ich fast vergessen ;)
