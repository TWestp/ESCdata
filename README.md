# ESCdata
Datensatz über den Eurovision Song Contest 2014-2019

PunkteGesamt: Gesamtpunktzahl des Beitrags beim Eurovision Song Contest (für die Jahre 2014 und 2015 in das Wertungssystem ab 2016 umgerechnet, fehlende Votingergebnisse mittels Referenzländerquerschnitte gebildet)

PunkteJury: Jurypunktzahl des Beitrags beim Eurovision Song Contest (für die Jahre 2014 und 2015 in das Wertungssystem ab 2016 umgerechnet, fehlende Votingergebnisse mittels Referenzländerquerschnitte gebildet)

PunkteTelevoting: Televotingpunktzahl des Beitrags beim Eurovision Song Contest (für die Jahre 2014 und 2015 in das Wertungssystem ab 2016 umgerechnet, fehlende Votingergebnisse mittels Referenzländerquerschnitte gebildet)

Jahr: Jahr der Teilnahme nach der Gregorianischen Zeitrechnung

Show: Chronologische Position der Show in den 18 Shows der Eurovision Song Contests 2014-2019 (1=1. Halbfinale 2014, ..., 18=Finale 2019)

Datum: Datum der Show nach ISO 8601 / DIN 5008

Semi: binäre Variable, ob es sich um ein Halbfinale handelt (1=ja)

Startnummer: Startnummer des Beitrags in der entsprechenden Show

Land: Nation, für die der Beitrag ins Rennen geschickt wurde

Interpret: Interpret des Beitrags

Songtitel: Songtitel des Beitrags

WoerterSongtitel: Anzahl Wörter im offiziellen Songtitel

Blasinstrument: binäre Variable, ob während des Liveauftritts mindestens ein Blasinstrument auf der Bühne zu sehen ist (1=ja)

Schlaginstrument: binäre Variable, ob während des Liveauftritts mindestens ein Schlaginstrument auf der Bühne zu sehen ist (1=ja)

Streichinstrument: binäre Variable, ob während des Liveauftritts mindestens ein Streichinstrument auf der Bühne zu sehen ist (1=ja)

Tasteninstrument: binäre Variable, ob während des Liveauftritts mindestens ein Tasteninstrument auf der Bühne zu sehen ist (1=ja)

Zupfinstrument: binäre Variable, ob während des Liveauftritts mindestens ein Zupfinstrument auf der Bühne zu sehen ist (1=ja)

ZahlGesamt: Anzahl an insgesamt während des Auftritts auf der Bühne sichtbaren Personen

ZahlHaupt: Anzahl an während des Auftritts auf der Bühne sichtbaren Personen ohne Backgroundsänger, -tänzer oder Ähnliche

ZahlmHaupt: Anzahl an männlichen während des Auftritts auf der Bühne sichtbaren Personen ohne Backgroundsänger, -tänzer oder Ähnliche

ZahlwHaupt: Anzahl an weiblichen während des Auftritts auf der Bühne sichtbaren Personen ohne Backgroundsänger, -tänzer oder Ähnliche

ZahlmGesamt: Anzahl an männlichen insgesamt während des Auftritts auf der Bühne sichtbaren Personen

ZahlwGesamt: Anzahl an weiblichen insgesamt während des Auftritts auf der Bühne sichtbaren Personen

Geschlecht1: Geschlechtsvariable nach Kategorisierung 1 (männlich = männlicher Solointerpret, weiblich = weibliche Solointerpretin, Gruppe = mehrere Interpreten)

Geschlecht2: Geschlechtsvariable nach Kategorisierung 2 (männlich = männlicher Solointerpret oder Gruppe mit ausschließlich männlichen Mitgliedern, weiblich = weibliche Solointerpretin oder Gruppe mit ausschließlich weiblichen Mitgliedern, gemischt = Gruppe mit mindestens einem männlichen und mindestens einem weiblichen Mitglied)

Geburtsdatum1, Geburtsdatum2, Geburtsdatum3, Geburtsdatum4, Geburtsdatum5, Geburtsdatum6: (soweit verfügbar) Geburtsdaten der zu ZahlHaupt zählenden Interpreten nach ISO 8601 / DIN 5008

Alter: durchschnittliches Alter der Interpreten des Acts zum Zeitpunkt des Auftritts in der jeweiligen Show in Jahren

Mitverfasser: binäre Variable, ob mindestens einer der Interpreten des Acts an der Entstehung von Musik und/oder Lyrics des Songs beteiligt war (1=ja)

Vorentscheid: binäre Variable, ob der ESC-Act durch einen öffentlichen nationalen Vorentscheid ausgewählt wurde (1=ja)

VETeilnehmer: Anzahl an geschlagenen beim Vorentscheid angetretenen Acts

Veroeffentlichung: Datum der Veröffentlichung des Songs nach ISO 8601 / DIN 5008

Dauer: Anzahl Tage zwischen dem Datum der Veröffentlichung des Songs und dem Datum der Show

Kuerzel: eindeutiges achtstelliges Kürzel für alle Beobachtungen

Englisch: binäre Variable, ob überwiegende Teile der Lyrics des Liedes in englischer Sprache präsentiert werden (1=ja)

Landessprache: binäre Variable, ob überwiegende Teile der Lyrics des Liedes in mindestens einer im jeweiligen Land genutzten offiziellen Landessprache präsentiert wird (1=ja)

Liebe: binäre Variable, ob Lyrics des Songs romantische und/oder sexuelle Liebe thematisieren (1=ja)

Krieg: binäre Variable, ob Lyrics des Songs Krieg oder Frieden thematisieren (1=ja)

Gleichberechtigung: binäre Variable, ob Lyrics des Songs Gleichberechtigung thematisieren (1=ja)

Woerterzahl: Gesamtzahl der im gesungenen Liedtext vorhandenen Wörter 

WoerterHaupt: Gesamtzahl der von unter ZahlHaupt fallenden Interpreten gesungenen im Liedtext vorhandenen Wörter

WoerterNeben: Differenz von Woerterzahl und WoerterHaupt

Titelzahl: Häufigkeit des Auftretens des Songtitels im präsentierten Liedtext

TitelHaupt: Häufigkeit des Auftretens des Songtitels im durch unter ZahlHaupt fallenden Interpreten präsentierten Liedtext

TitelNeben: Differenz von Titelzahl und TitelHaupt

RaengeQuoten: Position des Beitrags in den Wettquoten der entsprechenden Show auf Sieg (für Semi=0) bzw. Finalqualifikation (für Semi=1) nach BETFAIR SPORTS (bzw. PaddyPower für 2014) unmittelbar vor den entsprechenden Shows

normiert: Wettquote des Beitrags auf Sieg des Eurovision Song Contests nach bet365, Stand anderthalb bis zwei Monate vor den entsprechenden Shows, umgerechnet in normierte Wahrscheinlichkeiten auf Sieg

WettquoteFinale: Hilfsvariable für RaengeQuoten. Wettquote des Beitrags auf Finalsieg nach BETFAIR SPORTS (bzw. PaddyPower für 2014) unmittelbar vor der entsprechenden Show. Nur für Semi=0 verfügbar

WettquoteSemi: Hilfsvariable für RaengeQuoten. Wettquote des Beitrags auf Finalqualifikation nach BETFAIR SPORTS (bzw. PaddyPower für 2014) unmittelbar vor der entsprechenden Show. Nur für Semi=1 verfügbar

Finalquoten: Hilfsvariable für normiert. Wettquote des Beitrags auf Sieg des Eurovision Song Contests nach bet365, Stand anderthalb bis zwei Monate vor den entsprechenden Shows

letztesJahrFinale: binäre Variable, ob Land im Vorjahr am Finale des Eurovision Song Contests teilnahm (1=ja)

AbstimmendeLaender: um Eins verringerte Anzahl wertender Nationen in der jeweiligen Show

Grenznachbarn: Anzahl an für ein Land stimmberechtigter Grenznachbarn in der jeweiligen Show

Sprachnachbarn: Anzahl an für ein Land stimmberechtiger Nationen in der jeweiligen Show, in denen mindestens eine Übereinstimmung bei den offiziellen Landessprachen vorliegt

Flaeche: Oberfläche des Landes in Quadratkilometer

Einwohner: Schätzung der Einwohnerzahl des Landes zur Jahresmitte

BIP: Pro-Kopf-Bruttoinlandsprodukt des Landes in US-Dollar

Frauenquote: prozentualer Anteil an Sitzen im nationalen Parlament des Landes, die im entsprechenden Jahr von Frauen besetzt waren

Touristen: Anzahl an ausländischen Übernachtungsgästen des Landes, die weder aus beruflichen Gründen reisten noch über zwölf Monate im Land blieben

TouriproEinw: Touristen in Relation zur Einwohnerzahl

Festnetzanschluesse: Summe an aktiven festen Telefonleitungen, VoIP-Abonnements, WLL-Abonnements, ISDN-Sprachkanaläquivalenten und öffentlichen Münztelefonen eines Landes

Mobilfunkvertraege: Anzahl im jeweiligen Jahr aktiver Prepaid-Konten und Postpaid-Abonnements eines Landes
