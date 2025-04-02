Datensatzdokumentation
# Hochfrequente Mental Health Surveillance 
*Hochfrequente Beobachtung der psychischen Gesundheit der erwachsenen Bevölkerung in Deutschland*  

<br>
<br>
<br>

[**Stephan Junker**](https://orcid.org/0000-0001-8612-9347)&sup1;, [**Stefan Damerow**](https://orcid.org/0000-0002-7265-1123)&sup2;, [**Lena Walther**](https://orcid.org/0000-0002-2703-5022)&sup1; und [**Elvira Mauz**](https://orcid.org/0000-0003-1988-9789)&sup1;    

<br>

&emsp;&emsp;&sup1; [Robert Koch-Institut](https://rki.de) | [Fachgebiet 26](https://www.rki.de/DE/Institut/Organisation/Abteilungen/Abteilung-2/FG26/fg26-psychische-gesundheit-node.html)  
&emsp;&emsp;&sup2; [Robert Koch-Institut](https://rki.de) | [Fachgebiet 21](https://www.rki.de/DE/Institut/Organisation/Abteilungen/Abteilung-2/FG21/fg21-epidemiologisches-daten-und-befragungszentren-node.html)  

<br> 

---

**Zitieren**  
<!-- CITATION_START: {"citation_style": "apa"} -->
Junker, S., Damerow, S., Walther, L., & Mauz, E. (2024). Hochfrequente Mental Health Surveillance [Data set]. Zenodo. [https://doi.org/10.5281/zenodo.14261164](https://doi.org/10.5281/zenodo.14261164)
<!-- CITATION_END -->


## Einleitung

Im Rahmen der Mental Health Surveillance (MHS) am Robert Koch-Institut (RKI) werden für eine Auswahl an Indikatoren der psychischen Gesundheit von Erwachsenen basierend auf Surveydaten Zeitreihen bestehend aus gleitenden Drei-Monats-Schätzern und Glättungskurven berechnet. Dadurch sollen Entwicklungen in der psychischen Gesundheit der erwachsenen Bevölkerung in Deutschland mit möglichst geringem Zeitverzug beobachtet und insbesondere negative Entwicklungen frühzeitig erkannt werden. Diese hochfrequente Surveillance wurde ursprünglich vor dem Hintergrund neuer Informationsbedarfe zur Entwicklung der psychischen Gesundheit der Bevölkerung in der COVID-19-Pandemie entwickelt.


## Datensatz und Entstehungskontext

Im Datensatz „Hochfrequente Mental Health Surveillance“ werden aktuelle Zeitreihen bestehend aus gleitenden Drei-Monats-Schätzern samt Konfidenzintervallen sowie wöchentlichen Schätzern für die Glättungskurven zu den folgenden Indikatoren der psychischen Gesundheit Erwachsener bereitgestellt: 
- depressive Symptome
- Angstsymptome
- selbsteingeschätzte psychische Gesundheit

Der Datensatz umfasst je Indikator sowohl Schätzer für die kategoriale Auswertung der entsprechenden Messinstrumente als auch Mittelwerte von Summenwerten. Neben den Schätzern für die erwachsene Gesamtbevölkerung sind auch Schätzer für Bevölkerungsgruppen stratifiziert (aufgeteilt) nach Geschlecht (wie bei Geburt zugewiesen), Alter und Bildung enthalten. Für die Bevölkerungsgruppen werden standardisierte (nach den jeweiligen anderen beiden Charakteristika aus Geschlecht, Alter und Bildung) und nicht standardisierte Schätzer angegeben.

Die 2019 bzw. 2021 beginnenden Zeitreihen werden in der Regel monatlich aktualisiert, sobald neue Daten aus der [GEDA-Studie](https://www.geda-studie.de/deutsch/home.html) (siehe Datenerhebung) verfügbar sind. 



### Administrative und organisatorische Angaben

Die Veröffentlichung der Daten, die Datenkuration sowie das Qualitätsmanagement der (Meta-) Daten erfolgen durch das RKI-Fachgebiet [MF 4 | Fach- und Forschungsdatenmanagement](https://www.rki.de/DE/Institut/Organisation/Abteilungen/MFI/MF4/mf4-fach-und-forschungsdatenmanagement-node.html). Fragen zum Datenmanagement und zur Publikationsinfrastruktur können an das Open Data Team des Fachgebiets MF4 unter [OpenData@rki.de](mailto:OpenData@rki.de) gerichtet werden.

## Datenerhebung und Datenauswertung  

Die Datengrundlage der Zeitreihen sind vor allem verschiedene Erhebungswellen der im Rahmen des Gesundheitsmonitorings durchgeführten Studie [„Gesundheit in Deutschland aktuell (GEDA)“: GEDA/EHIS 2019-2020, GEDA 2021, GEDA 2022 und GEDA 2023](https://www.geda-studie.de/deutsch/home.html). Eine Erhebungslücke in 2021 konnte mit Daten des „[COVID-19 Impfquoten-Monitoring in Deutschland (COVIMO)](https://www.rki.de/DE/Themen/Infektionskrankheiten/Impfen/Forschungsprojekte/abgeschlossene-Projekte/COVIMO/covimo_studie.html)“ geschlossen werden. Alle Studien wurden durch das Bundesministerium für Gesundheit beauftragt und für die Auswertungen zusammengeführt. Diese repräsentativ angelegten telefonischen Gesundheitssurveys umfassen monatliche Erhebungen in Zufallsstichproben von zunächst jeweils ca. 1.000 in Deutschland lebenden Erwachsenen (2019-2021), dann von ca. 3.000 Erwachsenen (2022-2023) und aktuell von ca. 1.000 bzw. für depressive Symptome 2.000 Erwachsenen (ab Mitte April 2023). Die Stichprobenziehung erfolgte in diesen Studien über ein sogenanntes Dual-Frame-Verfahren, das eine Mobilfunk- und eine Festnetzgesamtheit als Auswahlgesamtheiten nutzt ([Allen et al., 2021](https://doi.org/10.25646/8460.2)).

Zur Durchführung der telefonischen Befragungen arbeitet das RKI mit einem externen Markt- und Sozialforschungsinstitut (USUMA GmbH) zusammen, welches im Auftrag des Epidemiologischen Daten- und Befragungszentrums der Abteilung 2 des Robert Koch-Instituts die Daten erhebt und unter Einhaltung der Datenschutz- und Sicherheitsbestimmungen anonymisiert zur Verfügung stellt. Bevor die Daten für Auswertungen bereitgestellt werden, findet eine standardisierte Datenaufbereitung inklusive Datenqualitätssicherung statt. So werden z.B. unplausible Angaben identifiziert, Fälle bereinigt oder Variablen generiert ([Allen et al., 2021](https://doi.org/10.25646/8460.2)). Nach der Bereitstellung der Daten für die MHS erfolgt eine inhaltliche Datenprüfung bezügliche der Angaben zur psychischen Gesundheit und es werden Gewichtungsfaktoren berechnet, die unterschiedliche Teilnahmebereitschaften in verschiedenen Bevölkerungsgruppen sowie die verschiedenen Auswahlwahrscheinlichkeiten der befragten Personen berücksichtigen. Nähere Studieninformationen sind abrufbar unter:

“Gesundheit in Deutschland aktuell - European Health Interview Survey” | GEDA-EHIS 2019-2020, GEDA 2021, GEDA 2022, GEDA 2023:
[https://www.rki.de/DE/Themen/Nichtuebertragbare-Krankheiten/Studien-und-Surveillance/Studien/GEDA/Geda_2024_inhalt.html?nn=16780210](https://www.rki.de/DE/Themen/Nichtuebertragbare-Krankheiten/Studien-und-Surveillance/Studien/GEDA/Geda_2024_inhalt.html?nn=16780210)

COVIMO-Studie: Impfverhalten, Impfbereitschaft und -akzeptanz in Deutschland:
[https://www.rki.de/DE/Themen/Infektionskrankheiten/Impfen/Forschungsprojekte/abgeschlossene-Projekte/COVIMO/covimo_studie.html](https://www.rki.de/DE/Themen/Infektionskrankheiten/Impfen/Forschungsprojekte/abgeschlossene-Projekte/COVIMO/covimo_studie.html)


### Untersuchungszeitraum  

Die Untersuchungszeiträume unterscheiden sich für die verschiedenen Indikatoren. Dies ergibt sich aus Unterschieden zwischen den Datengrundlagen mit Blick auf die eingesetzten Messinstrumente. Depressive Symptome werden seit April 2019 beobachtet; Angstsymptome und die selbsteingeschätzte psychische Gesundheit seit März 2021.

### Grundgesamtheit  

Die Grundgesamtheit der GEDA- und COVIMO-Erhebungen umfasst die deutschsprachige, in Privathaushalten lebende Bevölkerung ab 15 Jahren (GEDA-EHIS 2019/2020), 16 Jahren (GEDA 2021, 2022) bzw. 18 Jahren (GEDA 2023, COVIMO), deren üblicher Aufenthaltsort zum Zeitpunkt der Datenerhebung in Deutschland liegt. Hierbei sind sowohl Einpersonen- als auch Mehrpersonenhaushalte inbegriffen, die eigenständig wirtschaften und sich selbständig mit für den Lebensunterhalt notwendigen Dingen versorgen. Diese Definition umfasst keine kollektiven Haushalte wie Krankenhäuser, Pflege- oder Wohnheime, Gefängnisse, Kasernen, religiöse Einrichtungen, Pensionen oder Wohnheime. "Üblicher Aufenthaltsort" beschreibt den Ort, an dem eine Person normalerweise lebt oder ihren Lebensmittelpunkt sieht – ungeachtet vorübergehender Abwesenheit zu Zwecken der Erholung, der beruflichen Tätigkeit, der medizinischen Behandlung oder ähnlichem.

Die Auswertungen für den vorliegenden Datensatz wurden mit GEDA- und COVIMO-Daten von Erwachsenen (ab 18 Jahren) durchgeführt, weil die Entwicklung der psychischen Gesundheit Erwachsener im Fokus stehen. Ab 2022 sind die untersuchten Indikatoren außerdem nicht mehr bei unter 18-Jährigen abgefragt worden.


### Erhebungsinstrumente  

Der vorliegende Datensatz enthält aggregierte Daten aus den Studien GEDA/EHIS 2019-2020, COVIMO, GEDA 2021, GEDA 2022 und GEDA 2023 zu drei Indikatoren: 

#### Indikator „selbsteingeschätzte psychische Gesundheit“

Der Indikator „selbsteingeschätzte psychische Gesundheit“ beinhaltet eine Selbsteinschätzung der eigenen psychischen Gesundheit im Allgemeinen. Die Messung erfolgt über ein etabliertes Einzelitem ([Ahmad et al., 2014](https://doi.org/10.1186/1472-6963-14-398)):

>„Wie würden Sie Ihren psychischen Gesundheitszustand im Allgemeinen beschreiben?“ 


Antwortoptionen: `ausgezeichnet` = 5, `sehr gut` = 4, `gut` = 3, `weniger gut` = 2, `schlecht` = 1  

Der Datensatz enthält Schätzer zum Bevölkerungsmittelwert sowie zum Anteil mit einem Wert ≥ 4, also dem Anteil in Deutschland lebender Erwachsener mit einer sehr guten bis ausgezeichneten selbsteingeschätzten psychischen Gesundheit.

#### Indikator "depressive Symptome"

Der Indikator “depressive Symptome” wird mit dem validierten Messinstrument „Patient Health Questionnaire-2“ (PHQ-2) erfasst ([Löwe et al., 2005](C:\Users\persekek\AppData\Local\Microsoft\Windows\INetCache\Content.Outlook\HKNYBDLS\10.1016\j.jpsychores.2004.09.006)). Der PHQ-2 fragt:

> „Wie oft fühlten Sie sich im Verlauf der letzten 2 Wochen durch die folgenden Beschwerden beeinträchtigt“: 
> 1) „Wenig Interesse oder Freude an Ihren Tätigkeiten“
> 2) „Niedergeschlagenheit, Schwermut oder Hoffnungslosigkeit“ 


Antworten und Punktzahlen jeweils:`überhaupt nicht` = 0, `an einzelnen Tagen` = 1, `an mehr als der Hälfte der Tage` = 2, `beinahe jeden Tag` = 3

Der Summenwert des PHQ-2 beträgt 0 (min) bis 6 (max) und weist auf keine bis sehr starke Belastung durch depressive Symptome hin. Werte ≥3 deuten darauf hin, dass eine auffällige Belastung durch depressive Symptome vorliegt. Der Datensatz enthält Schätzer zum Bevölkerungsmittelwert sowie zum Bevölkerungsanteil im auffälligen Wertebereich.

#### Indikator "Angstsymptome"

Der Indikator “Angstsymptome” wird mit dem validierten Messinstrument „Generalized Anxiety Disorder-2“ (GAD-2) erfasst ([Kroenke et al., 2007](https://doi.org/10.7326/0003-4819-146-5-200703060-00004)). Der GAD-2 fragt: 
>„Wie oft fühlten Sie sich im Verlauf der letzten 2 Wochen durch die folgenden Beschwerden beeinträchtigt“:
> 1) „Nervosität, Ängstlichkeit oder Anspannung“ 
> 2) „Nicht in der Lage sein, Sorgen zu stoppen oder zu kontrollieren“ 

Antworten und Punktzahlen jeweils: `überhaupt nicht` = 0, `an einzelnen Tagen` = 1, `an mehr als der Hälfte der Tage` = 2, `beinahe jeden Tag` = 3

Der Summenwert des GAD-2 beträgt 0 (min) bis 6 (max) und weist auf keine bis sehr starke Belastung durch Angstsymptome hin. Werte ≥3 deuten darauf hin, dass eine auffällige Belastung durch Angstsymptome vorliegt. Der Datensatz enthält Schätzer zum Bevölkerungsmittelwert sowie zum Bevölkerungsanteil im auffälligen Wertebereich.


### Datenauswertung  

Um die Entwicklung mehrerer Indikatoren der psychischen Gesundheit der in Deutschland lebenden erwachsenen Bevölkerung über die Zeit zu untersuchen, werden Zeitreihen bestehend aus monatlichen geschätzten Werten samt Konfidenzintervallen sowie Glättungskurven berechnet.

#### Gleitende Drei-Monats-Schätzer

Bei den monatlichen Schätzern handelt es sich um gleitende Drei-Monats-Schätzer: Sie beruhen jeweils auf Daten aus drei aufeinanderfolgenden Befragungsmonaten und rücken stets um einen Monat weiter. Der erste Drei-Monats-Schätzer der berechneten Zeitreihen zu depressiven Symptomen umfasst zum Beispiel Daten aus dem Zeitraum Mitte April bis Mitte Juli 2019. Der nächste Drei-Monats-Schätzer umfasst dann die Monate Mitte Mai bis Mitte August. Alle Drei-Monats-Fenster beginnen und enden mit einer Monatsmitte, weil die monatlichen Erhebungswellen der ausgewerteten Surveys meist etwa zur Monatsmitte begannen. In der zeitlichen Umgebung von Datenlücken werden teilweise Schätzer basierend auf Daten aus zwei Monaten innerhalb eines Drei-Monats-Fensters berechnet, niemals jedoch werden Schätzer basierend auf Daten aus nur einem Monat berechnet.

Vorteil der Verwendung von Drei-Monats-Schätzern: Durch die Berechnung von gleitendenden monatlichen Schätzern von Indikatoren der psychischen Gesundheit basierend auf Daten aus jeweils drei (oder zwei) Monaten werden die Stichprobengrößen je Schätzer erhöht und somit auch eine höhere statistische Genauigkeit der Schätzer erreicht. Außerdem trägt dieser Ansatz zur Glättung der Zeitreihen bei, indem zufällige, Stichprobengrößen-bedingte Schwankungen reduziert werden. Bei Ein-Monats-Schätzern käme es zu größeren Fluktuationen durch zufällige Abweichungen zwischen Schätzern, wodurch Trends weniger gut erkennbar bzw. interpretierbar wären. Dies kann besonders bei Indikatoren mit einer geringen Prävalenz und entsprechend geringen Fallzahlen in den Stichproben zum Problem werden sowie bei nach Geschlecht, Alter oder Bildung stratifizierten Zeitreihen.

#### Glättungskurven

Obwohl die gleitenden Drei-Monats-Schätzer bereits geglättete Zeitreihen bilden, kann es dennoch zu Fluktuationen kommen, die die Interpretation der Zeitreihen erschweren. Damit die allgemeinen Verläufe in den Indikatoren der psychischen Gesundheit besser erkennbar sind, werden daher zusätzlich zu den Drei-Monats-Schätzern Glättungskurven berechnet. Diese beruhen auf „Generalized Additive Models“, die sogenannte „Smoothing Splines“ als Terme enthalten ([Wood, 2003](https://doi.org/10.1111/1467-9868.00374)). Sie sollen den zeitlichen Verlauf der Mittelwert- und Anteilsschätzungen kontinuierlich und geglättet approximieren. Die Modellierung basiert hierbei auf wöchentlichen Datenpunkten und resultiert in wöchentlichen Schätzern, durch die eine Kurve gezogen wird. Diese wöchentlichen Schätzer sind im vorliegenden Datensatz enthalten. Nach der aktuellen Methode können die Glättungskurven nur für längere Zeitreihen geschätzt werden. Es können keine Konfidenzintervalle berechnet werden, die die statistische Unsicherheit der Glättungskurven quantifizieren würden. Auch deshalb sollten die Glättungskurven gemeinsam mit den gleitenden Drei-Monats-Schätzern und ihren Konfidenzintervallen betrachtet werden.

#### Gewichtung

Die Drei-Monats-Schätzer werden unter Berücksichtigung von Stichprobengewichten mit Surveyprozeduren berechnet (siehe [Allen et al., 2021](https://doi.org/10.25646/8460.2)). Die Stichprobengewichte berücksichtigen in der sogenannten Designgewichtung die unterschiedlichen Ziehungswahrscheinlichkeiten der Teilnehmenden im Rahmen des telefonischen Dual-Frame-Verfahrens (Festnetz, Mobilfunk). Darauf aufbauend wird die Stichprobe aus den RKI-Studien GEDA-EHIS, GEDA und COVIMO an öffentliche Bevölkerungsstatistiken (d.h., aktuelle Bevölkerungsstruktur und Zusammensetzung) nach Alter, Geschlecht, Bildung und Region angepasst. Die Gewichtungsfaktoren werden vom Epidemiologischen Daten- und Befragungszentrum (EDZ) des RKI bereitgestellt.

#### Standardisierung

Zusätzlich standardisiert wird in den Berechnungen der Drei-Monats-Schätzer und Glättungskurven nach Alter, Geschlecht und Bildung gemäß CASMIN-Klassifikation ([Brauns et al., 2003](https://doi.org/10.1007/978-1-4419-9186-7_11)). Damit werden Abweichungen in der Stichprobenzusammensetzung zwischen den Erhebungszeitpunkten ausgeglichen. Diese Standardisierung erfolgt unter Einbeziehung des Mikrozensus (Schwarz, 2001) von 2018 als Standardbevölkerung. Als Grundlage für diese Standardisierung werden die Schätzer anhand von Geschlecht, Alter und Bildung modelliert: Drei-Monats-Schätzer und Konfidenzintervalle, die Bevölkerungsmittelwerte von Skalen (z.B. PHQ-2-Mittelwerte) abbilden, beruhen auf linearen Regressionen, die die analysierten Indikatoren der psychischen Gesundheit innerhalb von jedem Drei-Monats-Fenster auf Geschlecht, Alter und Bildung regressieren. Bei dichotomen Merkmalen (z.B. Bevölkerungsanteil mit oder ohne Belastung durch depressive Symptome im auffälligen PHQ-2-Wertebereich) werden äquivalent logistische Regressionen geschätzt. In den linearen Regressionen werden alle Drei-Weg-Interaktionen zwischen Geschlecht, Alter und Bildung berücksichtigt. In den logistischen Regressionen werden dagegen nur Zwei-Weg-Interaktionen berücksichtigt, weil es durch teilweise niedrige Fallzahlen in den Stichproben oder einzelnen Stichproben-Subgruppen bei Drei-Weg-Interaktionen häufiger zu leeren Interaktionszellen käme. Die Berechnung der Glättungskurven über „Generalized Additive Models“ mit „Smoothing Splines“ basiert ebenfalls auf nach Geschlecht, Alter, Bildung und Region gewichteter Modellierung sowie um Geschlecht, Alter und Bildung standardisierten Vorhersagen.

Diese Berechnungsweise ermöglicht bei Stratifizierung der Zeitreihen nach Geschlecht, Alter und Bildung eine weitere Form der Standardisierung: Die jeweiligen Bevölkerungssubgruppen werden einander mit Blick auf die anderen beiden Charakteristika angeglichen. Für Geschlechtervergleiche wird die Alters- und Bildungsverteilung bei Frauen und Männern in der Berechnung angeglichen, für Altersvergleiche die Geschlechter- und Bildungsverteilung und für Bildungsvergleiche die Geschlechter- und Altersverteilung. So kann ausgeschlossen werden, dass sich Unterschiede aus ungleichen Verteilungen der jeweiligen anderen Charakteristika ergeben. Bei der Interpretation standardisierter Schätzer ist zu beachten, dass sie wegen dieser Angleichungen zwischen Gruppen nicht als repräsentative Schätzer für die tatsächlichen Mittelwerte und Anteile der jeweiligen Bevölkerungsgruppen mit ihren realen Zusammensetzungen interpretiert werden können. Der Datensatz enthält neben standardisierten Schätzern daher auch nicht standardisierte Schätzer. Diese lassen sich als repräsentative Schätzer interpretieren. Allerdings ist bei nicht standardisierten Schätzern nicht auszuschließen, dass sich Unterschiede zwischen Bevölkerungsgruppen aus ungleichen Verteilungen von Alter, Geschlecht oder Bildung ergeben. 

#### Fehlende Werte und fehlende Schätzer

Bei fehlenden Werten in den Indikatoren psychischer Gesundheit werden Beobachtungen fallweise ausgeschlossen. Bei fehlenden Angaben zur Bildung wird das mittlere Bildungsniveau (CASMIN-Klassifikation) zugewiesen. Fehlende Angaben zu Geschlecht oder Alter kommen nicht vor.

Zu Lücken in den Zeitreihen kommt es hauptsächlich wegen Unterbrechungen in der Datenerhebung. Es kann jedoch vor allem in der Schätzung von Bevölkerungsanteilen auch zu fehlenden Drei-Monats-Schätzern kommen, wenn sich wegen zu geringer Fallzahlen in den Interaktionen in den unter „Standardisierung“ beschriebenen Regressionsmodellen leere Zellen ergeben. Wenn zum Beispiel in einem Drei-Monats-Fenster keine 18-29-Jährigen der niedrigen Bildungsgruppe mit Angstsymptomen im auffälligen Wertebereich des GAD-2 vorkommen, dann fehlt der Schätzer für die Anteile mit Angstsymptomen im auffälligen Wertebereich in diesem Zeitraum vollständig und wird im Datensatz mit NA („not available“) ausgewiesen. Da Schätzungen vor und nach Datenlücken häufig auf Daten aus nur zwei Monaten beruhen, kann es wegen geringerer Fallzahlen vor allem in diesen Fällen zu fehlenden Schätzern kommen.

**Eine ausführliche Beschreibung dieser Methodik ist hier zu finden:**
 
Junker S, Damerow S, Walther L, Mauz E. Development of a prototype for high-frequency mental health surveillance in Germany: data infrastructure and statistical methods. Front Public Health. 2023; 11:1208515. doi: [10.3389/fpubh.2023.1208515](https://doi.org/10.3389/fpubh.2023.1208515).

## Aufbau und Inhalt des Datensatzes

Der Datensatz enthält aggregierte Daten aus den Studien GEDA/EHIS 2019-2020, COVIMO, GEDA 2021, GEDA 2022 und GEDA 2023, wie sie in der hochfrequenten Mental Health Surveillance aufbereitet wurden. Im Datensatz enthalten sind:

- Daten der hochfrequenten Mental Health Surveillance
- Datensatzdokumentation in deutscher Sprache
- Lizenz-Datei mit der Nutzungslizenz des Datensatzes in Deutsch und Englisch
- Metadaten zur automatisierten Weiterverarbeitung


### Daten der hochfrequenten Mental Health Surveillance

Die Daten der hochfrequenten Mental Health Surveillance zu drei Indikatoren der psychischen Gesundheit Erwachsener in Deutschland sind bereitgestellt als:

> [high_frequency_mental_health_surveillance.tsv](/high_frequency_mental_health_surveillance.tsv])

#### Variablen und Variablenausprägungen  

<!-- DATA_SCHEMA_SPECIFICATION_START: {"id": "high_frequency_mental_health_surveillance", "lang": "de"} -->

Die Datei [high_frequency_mental_health_surveillance.tsv](https://github.com/robert-koch-institut/Hochfrequente_Mental_Health_Surveillance/blob/main/high_frequency_mental_health_surveillance.tsv) enthält die in der folgenden Tabelle abgebildeten Variablen und deren Ausprägungen. Ein maschinenlesbares Datenschema ist im [Data Package Standard](https://datapackage.org/) in [tableschema_high_frequency_mental_health_surveillance.json](https://github.com/robert-koch-institut/Hochfrequente_Mental_Health_Surveillance/blob/main/Metadaten/schemas/tableschema_high_frequency_mental_health_surveillance.json) hinterlegt:
> [tableschema_high_frequency_mental_health_surveillance.json](https://github.com/robert-koch-institut/Hochfrequente_Mental_Health_Surveillance/blob/main/Metadaten/schemas/tableschema_high_frequency_mental_health_surveillance.json)

<!-- DATA_SCHEMA_TABLE_START -->
| Variable         | Typ     | Ausprägungen                                                                                                                                                                                                                                                        | Beschreibung                                                                                                                                                                                                                                                                                                                                                                  |
|:-----------------|:--------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| model            | string  | Werte: `3_Monate_Mittelwerte`, `3_Monate_Anteile`, `Mittelwerte_smooth`, `Anteile_smooth`                                                                                                                                                                           | Gibt an, welches Modell zur Schätzung genutzt wurde, eine lineare (3_Monate_Mittelwerte) bzw. logistische Regression (3_Monate_Anteile) für Drei-Monats-Fenster oder ein generalized additive model mit einem smoothing spline unter der Annahme einer Gaussverteilung (Mittelwerte_smooth) oder Binomialverteilung (Anteile_smooth) basierend auf wöchentlichen Datenpunkten |
| instrument       | string  | Werte: `SRMH`, `PHQ-2`, `GAD-2`                                                                                                                                                                                                                                     | Gibt das Instrument an, das genutzt wurde und für das der fit (Schätzer) berechnet wurde <br><br>`SRMH`: Self-rated mental health bzw. selbsteingeschätzte psychische Gesundheit<br><br> `PHQ-2`: (Kurzscreener “Patient Health Questionaire-2”): depressive Symptome,<br><br> `GAD-2` (Kurzscreener “Generalized Anxiety Disorder-2”): Angstsymptome                         |
| type             | string  | Werte: `Summenscore`, `kategorial`                                                                                                                                                                                                                                  | Gibt an, ob das Instrument als `Summenscore` oder aber `kategorial` mit einem Cut-Off-Wert genutzt wurde, um darüber und darunter liegende Anteile zu schätzen                                                                                                                                                                                                                |
| category         | string  | Werte: `gesamt`, `Altersgruppe`, `Bildungsgruppe`, `Geschlecht`                                                                                                                                                                                                     | Gibt an, nach welcher Kategorie stratifiziert wurde <br><br> `Bildungsgruppe`: Bildungsgruppe nach CASMIN <br><br> `Geschlecht`: wie bei Geburt zugewiesen                                                                                                                                                                                                                    |
| cat_value        | string  | Werte: `gesamt`, `18-29 Jahre`, `30-44 Jahre`, `45-64 Jahre`, `65+ Jahre`, `niedrige Bildungsgruppe`, `mittlere Bildungsgruppe`, …                                                                                                                                  | Gibt an, für welche Subgruppe der fit (Schätzer) berechnet wurde                                                                                                                                                                                                                                                                                                              |
| standardized     | boolean | Werte: `TRUE`, `FALSE`                                                                                                                                                                                                                                              | Gibt an, ob die Werte bei Stratifizierung für die anderen Kategorien standardisiert wurden                                                                                                                                                                                                                                                                                    |
| date             | date    | Format: `YYYY-MM-DD`                                                                                                                                                                                                                                                | Gibt die Mitte des Drei-Monats-Fensters bzw. der Woche an, für den der fit (Schätzer) berechnet wurde                                                                                                                                                                                                                                                                         |
| fit              | number  | Werte: `≥0`<br>Fehlende Werte: `NA`                                                                                                                                                                                                                                 | Gibt den geschätzten Bevölkerungsmittelwert des Summenscores bzw. den geschätzten Anteil der Bevölkerung an, der über bzw. unter dem Cut-Off-Wert liegt, wenn verfügbar bzw. berechenbar, alternativ NA                                                                                                                                                                       |
| se               | number  | Werte: `≥0`<br>Fehlende Werte: `NA`                                                                                                                                                                                                                                 | Gibt den Standardfehler an, wenn verfügbar, alternativ NA                                                                                                                                                                                                                                                                                                                     |
| lwr              | number  | Werte: `≥0`<br>Fehlende Werte: `NA`                                                                                                                                                                                                                                 | Gibt die untere Grenze des 95%-Konfidenzintervalls an, wenn verfügbar, alternativ NA                                                                                                                                                                                                                                                                                          |
| upr              | number  | Werte: `≥0`<br>Fehlende Werte: `NA`                                                                                                                                                                                                                                 | Gibt die obere Grenze des 95%-Konfidenzintervall an, wenn verfügbar, alternativ NA                                                                                                                                                                                                                                                                                            |
| period_duration  | string  | Werte: `3_Monate`, `2_Monate`, `1_Woche`                                                                                                                                                                                                                            | Gibt an, auf welche Periode sich der fit bezieht, auf eine Woche (für Anteil_smooth und Mittelwerte_smooth) oder ob innerhalb des jeweiligen Drei-Monats-Fensters für zwei oder drei Monate Beobachtungen vorhanden waren                                                                                                                                                     |
| period_text      | string  | Werte: `Mitte April bis Mitte Juli`, `Mitte August bis Mitte November`, `Mitte Dezember bis Mitte März`, `Mitte Februar bis Mitte Mai`, `Mitte Januar bis Mitte April`, `Mitte Juli bis Mitte Oktober`, `Mitte Juni bis Mitte September`, …<br>Fehlende Werte: `NA` | Beschreibt explizit das Drei-Monats-Fenster, für das die fits berechnet wurden                                                                                                                                                                                                                                                                                                |
| obs_month_period | integer | Werte: `≥1`<br>Fehlende Werte: `NA`                                                                                                                                                                                                                                 | Gibt die Anzahl der Beobachtungen im jeweiligen Drei-Monats-Fenster an, die in die Schätzung eingegangen sind. Die Beobachtungen können auch nur in zwei Monaten gemacht worden sein, siehe `period_duration`                                                                                                                                                                 |
| obs_timeseries   | integer | Werte: `≥1`                                                                                                                                                                                                                                                         | Gibt die Anzahl aller Beobachtungen an, auf denen die jeweilige Zeitreihe beruht                                                                                                                                                                                                                                                                                              |

<!-- DATA_SCHEMA_TABLE_END -->

<!-- DATA_SCHEMA_SPECIFICATION_END -->


<!-- FOOTER_START: {"lang": "de"} -->



### Metadaten  

Zur Erhöhung der Auffindbarkeit sind die bereitgestellten Daten mit Metadaten beschrieben. Über GitHub Actions werden Metadaten an die entsprechenden Plattformen verteilt. Für jede Plattform existiert eine spezifische Metadatendatei, diese sind im Metadatenordner hinterlegt:  

> [Metadaten/](https://github.com/robert-koch-institut/Hochfrequente_Mental_Health_Surveillance/tree/main/Metadaten/) 

Versionierung und DOI-Vergabe erfolgt über [Zenodo.org](https://zenodo.org). Die für den Import in Zenodo bereitgestellten Metadaten sind in der [zenodo.json](https://github.com/robert-koch-institut/Hochfrequente_Mental_Health_Surveillance/blob/main/Metadaten/zenodo.json) hinterlegt. Die Dokumentation der einzelnen Metadatenvariablen ist unter https://developers.zenodo.org/#representation nachlesbar.
 
> [Metadaten/zenodo.json](https://github.com/robert-koch-institut/Hochfrequente_Mental_Health_Surveillance/blob/main/Metadaten/zenodo.json)  

In der zenodo.json ist neben dem Publikationsdatum (`"publication_date"`) auch der Datenstand in folgendem Format enthalten (Beispiel):  

```
  "dates": [
    {
      "start": "2023-09-11T15:00:21+02:00",
      "end": "2023-09-11T15:00:21+02:00",
      "type": "Collected",
      "description": "Date when the Dataset was created"
    }
  ],
```    


Zusätzlich beschreiben wir tabellarische Daten mithilfe des [Data Package Standards](https://datapackage.org/).
Ein Data Package ist eine strukturierte Sammlung von Daten und zugehörigen Metadaten, die den Austausch und die Wiederverwendung von Daten erleichtert. Es besteht aus einer datapackage.json-Datei, die zentrale Informationen wie die enthaltenen Ressourcen, ihre Formate und Schema-Definitionen beschreibt.

Der Data Package Standard wird von der [Open Knowledge Foundation](https://okfn.org/) bereitgestellt und ist ein offenes Format, das eine einfache, maschinenlesbare Beschreibung von Datensätzen ermöglicht.

Die Liste der in diesem Repository enthaltenen Daten ist in folgender Datei hinterlegt:

> [datapackage.json](https://github.com/robert-koch-institut/Hochfrequente_Mental_Health_Surveillance/tree/main/datapackage.json)

Für tabellarische Daten definieren wir zusätzlich ein [Table Schema](https://datapackage.org/standard/table-schema/), das die Struktur der Tabellen beschreibt, einschließlich Spaltennamen, Datentypen und Validierungsregeln. Diese Schema-Dateien finden sich unter:

> [Metadaten/schemas/](https://github.com/robert-koch-institut/Hochfrequente_Mental_Health_Surveillance/tree/main/Metadaten/schemas) 



## Hinweise zur Nachnutzung der Daten  

Offene Forschungsdaten des RKI werden auf [Zenodo.org](http://Zenodo.org/), [GitHub.com](http://GitHub.com/), [OpenCoDE](https://gitlab.opencode.de) und [Edoc.rki.de](http://Edoc.rki.de/) bereitgestellt:  

- https://zenodo.org/communities/robertkochinstitut  
- https://github.com/robert-koch-institut  
- https://gitlab.opencode.de/robert-koch-institut  
- https://edoc.rki.de/  
 
### Lizenz  

Der Datensatz "Hochfrequente Mental Health Surveillance" ist lizenziert unter der [Creative Commons Namensnennung 4.0 International Public License | CC-BY 4.0 International](https://creativecommons.org/licenses/by/4.0/deed.de).  

Die im Datensatz bereitgestellten Daten sind, unter Bedingung der Namensnennung des Robert Koch-Instituts als Quelle, frei verfügbar. Das bedeutet, jede Person hat das Recht die Daten zu verarbeiten und zu verändern, Derivate des Datensatzes zu erstellen und sie für kommerzielle und nicht kommerzielle Zwecke zu nutzen. Weitere Informationen zur Lizenz finden sich in der [LICENSE](https://github.com/robert-koch-institut/Hochfrequente_Mental_Health_Surveillance/blob/main/LICENSE) bzw. [LIZENZ](https://github.com/robert-koch-institut/Hochfrequente_Mental_Health_Surveillance/blob/main/LIZENZ) Datei des Datensatzes.  
<!-- FOOTER_END -->


## Literatur

[Ahmad F, Jhajj AK, Stewart DE, Burghardt M, Bierman AS. Single item measures of self-rated mental health: a scoping review. BMC Health Serv Res. 2014; 14:398. ](https://doi.org/10.1186/1472-6963-14-398)

[Allen J, Born S, Damerow S, Kuhnert R, Lemcke J, Müller A et al. German Health Update (GEDA 2019/2020-EHIS) – Background and Methodology. J Health Monitor. 2021; 6:66–79.](https://doi.org/10.25646/8559)

[Brauns H, Scherer S, Steinmann S. The CASMIN Educational Classification in International Comparative Research. In: Hoffmeyer-Zlotnik, J.H.P., Wolf, C. (eds) Advances in Cross-National Comparison. 2003. Springer, Boston, MA. 
Kroenke K, Spitzer RL, Williams JBW, Monahan PO, Löwe B. Anxiety disorders in primary care: prevalence, impairment, comorbidity, and detection. Ann Intern Med. 2007; 146:317–25.](https://doi.org/10.1007/978-1-4419-9186-7_11)

[Löwe B, Kroenke K, Gräfe K. Detecting and monitoring depression with a two-item questionnaire (PHQ-2). J Psychosom Res. 2005; 58:163–71.](https://doi.org/10.1016/j.jpsychores.2004.09.006)

[Schwarz N. The German Microzensus. Schmollers Jahrbuch/J Appl Soc Sci. 2001. 121:649-654](https://www.ratswd.de/download/schmollers/Schwarz.pdf)

[Wood SN. Thin Plate Regression Splines. JR Stat Soc, B Stat Methodol. 65(1):95–114.](https://doi.org/10.1111/1467-9868.00374)


