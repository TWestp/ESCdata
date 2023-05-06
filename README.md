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




################################################################################################################################################




Verwendete Quellen:

4lyrics - The Home Of Eurovision Lyrics, diverse Seiten. URL: https://4lyrics.eu/, [abgerufen August 2019 bis April 2020]. 

Adam, W.: wiwibloggs (2014). Eurovision odds: Sweden the favourite, Austria and the Netherlands narrowing. URL: https://wiwibloggs.com/2014/05/09/eurovision-odds-austria-netherlands-narrow-sweden/49961/ [abgerufen 22. Juli 2020, 21.49 Uhr].

Entfernungsrechner. URL: https://www.luftlinie.org/ [abgerufen 17. September 2020, 16.00 Uhr].

esckaz (2019). Eurovision 2019 - Carousel. URL: https://esckaz.com/2019/lat.htm [abgerufen 8. August 2020, 09.08 Uhr].

ESC kompakt, diverse Seiten. URL: https://esc-kompakt.de/ [abgerufen November 2019 bis März 2021]. 

ESC XTRA (2019). Analysing the patterns among 13 years of Eurovision semi-final draw allocation pots. URL: https://escxtra.com/2020/01/25/analysing-13-eurovision-semi-final-draw-pots/ [abgerufen 25. Januar 2020, 15.01 Uhr].

Eurofire.me, diverse Seiten. URL: https://www.eurofire.me/ [abgerufen November 2019 bis März 2021].

Eurovision Song Contest National Finals Homepage, diverse Seiten. URL: http://natfinals.50webs.com/ [abgerufen Januar 2021].

Eurovision.de, diverse Seiten. URL: https://www.eurovision.de/ [abgerufen November 2019 bis März 2021].

Eurovision.tv. Events. URL: https://eurovision.tv/events [abgerufen 15. März 2020, 16.24 Uhr].

Eurovisionworld.com, diverse Seiten. URL: https://eurovisionworld.com/odds/eurovision [abgerufen Juli 2021].

Famous Birthdays, diverse Seiten. URL: https://www.famousbirthdays.com/ [abgerufen August 2020]. 

Genius, diverse Seiten. URL: https://genius.com/ [abgerufen August 2019 bis April 2020].

Google. URL: https://translate.google.de/ [abgerufen 17. Juni 2020, 19.45 Uhr]. 

Hatari Translations. URL: https://hatari-translations.tumblr.com/post/187077969132/do-you-happen-to-know-when-einars-birthday-is-i [abgerufen 5. August 2020, 14.17 Uhr].

Info Channel (2015). Interview mit The Makemakes. URL: https://info-channel.raiffeisen-ooe.at/jugend/the-makemakes\_182 [abgerufen 7. August 2020, 17.46 Uhr].

Lamb, C.: wiwibloggs (2014). First semi-final odds: Armenia still the favourite, Sweden closer. URL: https://wiwibloggs.com/2014/04/21/first-semi-final-odds-armenia-sweden/47298/ [abgerufen 22. Juli 2020, 21.07 Uhr].

Lamb, C.: wiwibloggs (2014). Second semi-final odds: Norway the favourite, Romania a close second. URL: https://wiwibloggs.com/2014/04/23/second-semi-final-odds-favourite/47514/ [abgerufen 22. Juli 2020, 21.26 Uhr].

Minus One. URL: https://minusoneband.com/about/ [abgerufen am 8. August 2020, 19.11 Uhr].

Nicer Odds (2014). Eurovision Betting Odds. URL: https://www.nicerodds.co.uk/ [abgerufen 31. März 2014, 09.48 Uhr].

Peter: ESC kompakt (2019). Neue Verwirrung um die Jury-Punkte aus Weißrussland. URL: https://esc-kompakt.de/neue-verwirrung-um-die-jury-punkte-aus-weissrussland/ [abgerufen 24. September 2021, 23.33 Uhr].

songtexte.com, diverse Seiten. URL: https://www.songtexte.com/ [abgerufen August 2019 bis April 2020].

The World Bank, diverse Seiten. URL: https://data.worldbank.org/ [abgerufen am 13. September 2021].

Universal Music (2014). Eurovision Song Contest, Copenhagen 2014.

Universal Music (2015). Eurovision Song Contest, Vienna 2015.

Universal Music (2016). Eurovision Song Contest, Stockholm 2016.

Universal Music (2017). Eurovision Song Contest, Kyiv 2017.

Universal Music (2018). Eurovision Song Contest, Lisbon 2018.

Universal Music (2019). Eurovision Song Contest, Tel Aviv 2019.

We Transfer ESC. URL: https://eurovision.wetransfer.com/downloads/a1da4b5eb0395e58b71016dce076564a20170409152448/6754ae [abgerufen 16. August 2020, 17.03 Uhr].

Wikipedia, diverse Seiten. URL: https://de.wikipedia.org [abgerufen August 2019 bis November 2021].

Wikipedia. ISO-3166-1-Kodierliste. URL: https://de.wikipedia.org/wiki/ISO-3166-1-Kodierliste [abgerufen 27. April 2021, 10.54 Uhr].

Wikipedia. Liste der Amtssprachen. URL: https://de.wikipedia.org/wiki/Liste\_der\_Amtssprachen [abgerufen 16. Oktober 2019, 17.33 Uhr].

wiwibloggs, diverse Seiten. URL: https://wiwibloggs.com/ [abgerufen August 2019 bis Oktober 2020].

