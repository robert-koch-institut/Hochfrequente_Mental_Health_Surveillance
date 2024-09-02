### Variable specification for data file `frictionless_data_schema_high_frequency_mental_health_surveillance`

| Variable         | Typ     | Ausprägungen                                                                                                                                                                   | Beschreibung                                                                                                                                                                                                                                                                                                                                                                  |
|:-----------------|:--------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| model            | string  | Werte: `3_Monate_Mittelwerte`, `3_Monate_Anteile`, `Mittelwerte_smooth`, `Anteile_smooth`                                                                                      | Gibt an, welches Modell zur Schätzung genutzt wurde, eine lineare (3_Monate_Mittelwerte) bzw. logistische Regression (3_Monate_Anteile) für Drei-Monats-Fenster oder ein generalized additive model mit einem smoothing spline unter der Annahme einer Gaussverteilung (Mittelwerte_smooth) oder Binomialverteilung (Anteile_smooth) basierend auf wöchentlichen Datenpunkten |
| instrument       | string  | Werte: `SRMH`, `PHQ-2`, `GAD-2`                                                                                                                                                | Gibt das Instrument an, das genutzt wurde und für das der fit (Schätzer) berechnet wurde <br><br>`SRMH`: Self-rated mental health bzw. selbsteingeschätzte psychische Gesundheit<br><br> `PHQ-2`: (Kurzscreener “Patient Health Questionaire-2”): depressive Symptome,<br><br> `GAD-2` (Kurzscreener “Generalized Anxiety Disorder-2”): Angstsymptome                         |
| type             | string  | Werte: `Summenscore`, `kategorial`                                                                                                                                             | Gibt an, ob das Instrument als `Summenscore` oder aber `kategorial` mit einem Cut-Off-Wert genutzt wurde, um darüber und darunter liegende Anteile zu schätzen                                                                                                                                                                                                                |
| category         | string  | Werte: `gesamt`, `Altersgruppe`, `Bildungsgruppe`, `Geschlecht`                                                                                                                | Gibt an, nach welcher Kategorie stratifiziert wurde <br><br> `Bildungsgruppe`: Bildungsgruppe nach CASMIN <br><br> `Geschlecht`: wie bei Geburt zugewiesen                                                                                                                                                                                                                    |
| cat_value        | string  | Werte: `gesamt`, `18-29 Jahre`, `30-44 Jahre`, `45-64 Jahre`, `65+ Jahre`, `niedrige Bildungsgruppe`, `mittlere Bildungsgruppe`, `hohe Bildungsgruppe`, `männlich`, `weiblich` | Gibt an, für welche Subgruppe der fit (Schätzer) berechnet wurde                                                                                                                                                                                                                                                                                                              |
| standardized     | boolean | Werte: `TRUE`, `FALSE`                                                                                                                                                         | Gibt an, ob die Werte bei Stratifizierung für die anderen Kategorien standardisiert wurden                                                                                                                                                                                                                                                                                    |
| date             | date    | Format: `%Y-%m-%d`                                                                                                                                                             | Gibt die Mitte des Drei-Monats-Fensters bzw. der Woche an, für den der fit (Schätzer) berechnet wurde                                                                                                                                                                                                                                                                         |
| fit              | number  | Fehlende Werte: `NA`<br>Minimum: 0                                                                                                                                             | Gibt den geschätzten Bevölkerungsmittelwert des Summenscores bzw. den geschätzten Anteil der Bevölkerung an, der über bzw. unter dem Cut-Off-Wert liegt, wenn verfügbar bzw. berechenbar, alternativ NA                                                                                                                                                                       |
| se               | number  | Fehlende Werte: `NA`<br>Minimum: 0                                                                                                                                             | Gibt den Standardfehler an, wenn verfügbar, alternativ NA                                                                                                                                                                                                                                                                                                                     |
| lwr              | number  | Fehlende Werte: `NA`<br>Minimum: 0                                                                                                                                             | Gibt die untere Grenze des 95%-Konfidenzintervalls an, wenn verfügbar, alternativ NA                                                                                                                                                                                                                                                                                          |
| upr              | number  | Fehlende Werte: `NA`<br>Minimum: 0                                                                                                                                             | Gibt die obere Grenze des 95%-Konfidenzintervall an, wenn verfügbar, alternativ NA                                                                                                                                                                                                                                                                                            |
| period_duration  | string  | Werte: `3_Monate`, `2_Monate`, `1_Woche`                                                                                                                                       | Gibt an, auf welche Periode sich der fit bezieht, auf eine Woche (für Anteil_smooth und Mittelwerte_smooth) oder ob innerhalb des jeweiligen Drei-Monats-Fensters für zwei oder drei Monate Beobachtungen vorhanden waren                                                                                                                                                     |
| period_text      | string  | Fehlende Werte: `NA`<br>Werte: `Mitte <Monat> bis Mitte <Monat>`                                                                                                               | Beschreibt explizit das Drei-Monats-Fenster, für das die fits berechnet wurden                                                                                                                                                                                                                                                                                                |
| obs_month_period | integer | Fehlende Werte: `NA`<br>Minimum: 1                                                                                                                                             | Gibt die Anzahl der Beobachtungen im jeweiligen Drei-Monats-Fenster an, die in die Schätzung eingegangen sind. Die Beobachtungen können auch nur in zwei Monaten gemacht worden sein, siehe `period_duration`                                                                                                                                                                 |
| obs_timeseries   | integer | Minimum: 1                                                                                                                                                                     | Gibt die Anzahl aller Beobachtungen an, auf denen die jeweilige Zeitreihe beruht                                                                                                                                                                                                                                                                                              |

