# Inventar archivalischer Quellen zur Geschichte des deutschen Buchhandels und Verlagswesens im 19. und 20. Jahrhundert
# Inhalt dieses Repositories

In den 1990er-Jahren wurden in mehreren durch die Deutsche Forschungsgemeinschaft gefördertern Projekten die Quellen der deutschen Buchhandelsgeschichte im 19. und 20. Jahrhundert inventarisiiert.

Die Ergebnisse wurden in einer Webanwendung mit einer proprietären SQL-Datenbank publiziert. Da die Langzeitverfügbarkeit der gewonnen Daten in diesem System nicht sichergestellt werden kann, wurden die Daten 2021 nach JSON migriert. Die mehr als 20 Jahre alte und bereits nicht mehr voll funktionsfähige Webanwendung wurde abgeschaltet.

In diesem Repository sind enthalten:
- Das gesamte Inventar im JSON-Format im Verzeichnis `./json`
- Aus diesem Datenbestand ausgelesene Verzeichnisse von Personen, Körperschaften, Orten, Titeln und Sachbegriffen als CSV im Verzeichnis `./csv`
- Die Rohdaten in einem veralteten Word-Format im Verzeichnis `./docx`
- Die Skripte als Jupyter Notebooks, mit denen das JSON-Inventar und die CSV-Verzeichnisse aus den Word-Dateien ausgelesen wurde im Verzeichnis `./scripte`
- Sämtliche auffindebaren Formatdokumentationen in diesem Verzeichnis

Die Verzeichnisse sind nicht fehlerfrei. Eine sehr komplexe Logik, mit der Personen, Körperschaften etc. in den Daten markiert werden konnten, hätte enorme Programmierarbeit erfordert, die zur Zeit nicht leistbar ist. In den Verzeichnissen dürften die meisten Angaben in einer brauchbaren Form vorliegen. Die Dateien sind klein genug, um händisch volltextdurchsuchbar zu sein. Sobald von den Bearbeitenden Personen offensichtliche aber nicht in der Vorlage enthaltene Daten ergänzt wurden, wurden diese mit `< und >` markiert. Diese Markierung behindert eine einfache Sortierung, weshalb diese Daten immer am Anfang der Verzeichnisse stehen.

Die verwendeten Rohdaten stellen nicht den letzten Stand des Projektes dar. Bei der Erstellung der Webanwendung wurden seinerzeit noch Datenkorrekturen durchgeführt, die nicht in die Rohdaten im Wordformat eingegangen sind. Diese lassen sich aus den SQL-Daten nicht mehr mit vertretbarem Aufwand rekonstruieren.

weitere Informationen auch auf dem [Blog der Deutschen Nationalbibliothek](https://blog.dnb.de/digitale-daten-restaurieren/)

# Lizenz

Alle Daten werden unter [CC.0-Lizenz](https://creativecommons.org/publicdomain/zero/1.0/deed.de) zur Verfügung gestellt.

# Das Projekt im Überblick
## Förderung

Das Projekt "Inventar archivalischer Quellen zur Geschichte des deutschen Buchhandels und Verlagswesens im 19. und 20. Jahrhundert" wurde innerhalb des Programms "Erschließung buch- und bibliotheksgeschichtlicher Quellenbestände" von der Deutschen Forschungsgemeinschaft gefördert. Der Börsenverein des Deutschen Buchhandels e. V. beteiligte sich durch Übernahme von Reisekosten der Projektbereiche Nord und Süd an der Finanzierung. Die online-Verfügbarkeit wurde gleichfalls von der Deutschen Forschungsgemeinschaft im Programm "Überregionale Erschließungsvorhaben der Archive" gefördert.

## Projektziel
Ziel des Projektes war die Erarbeitung eines Gesamtverzeichnisses, das einen Nachweis der in den deutschen Archiven vorhandenen themenrelevanten Quellen liefert. Beabsichtigt war,

- alle Archive zu verzeichnen, die über einschlägige Quellenbestände verfügen;
- Bestellsignaturen, Aktentitel, Laufzeit und soweit möglich, Enthältvermerke und Umfang der Dokumente zu nennen;
- Auskunft über Verfügbarkeit und Benutzungsmöglichkeiten zu erteilen; die gesammelten Informationen durch Register zu erschließen.

## Zielgruppe
Das Inventar soll in erster Linie der buchgeschichtlichen Forschung einen Überblick über die Quellenlage für allgemeine und spezielle Untersuchungen zur Verlags- und Buchhandelsgeschichte des 19. und 20. Jahrhunderts verschaffen. Insbesondere die Historische Kommission des Börsenvereins des Deutschen Buchhandels hat dieses Desiderat mehrfach benannt. Darüber hinaus bietet das Inventar einer Reihe anderer Disziplinen Zugriff auf Archivbestände für Forschungsvorhaben der politischen Geschichte ebenso wie der Literatur-, Kultur-, Wirtschafts- und Rechtsgeschichte. Firmen-, familien- und personengeschichtliche Vorhaben finden ebenfalls Ansatzpunkte.
Das Inventar richtet sich an Archivbenutzer mit Grundkenntnissen des Archivwesens und archivischer Erschließung.

## Gegenstand
Ausgewertet wurden alle erreichbaren archivalischen Quellen zur Buchhandels- und Verlagsgeschichte im umfassenden Sinn mit allen sachlichen Querverbindungen zur Kultur-, Wirtschafts-, Rechts- und Literaturgeschichte. Auch Randgebiete wie Leihbibliotheken, Lesezirkel, Zensur sowie der Themenbereich Presse wurden in das Erschließungskonzept aufgenommen.
Nicht berücksichtigt wurden die Bereiche Druckindustrie und Bibliothekswesen.

## Methodisches Vorgehen
### AUSGEWERTETE ARCHIVE
#### 1. Allgemeines

Die Recherche erstreckte sich auf alle staatlichen, auf ausgewählte kommunale und auf die kirchlichen Archive der obersten Verwaltungsebene. Pfarrarchive wurden partiell aufgenommen, sofern ihre Findmittel als Deposita im jeweils auszuwertenden Archiv zur Verfügung standen.
Andere öffentlich zugängliche Bestände in Archiven, die nicht zu den oben beschriebenen Archivtypen gehören, in Bibliotheken und in Museen waren nicht Gegenstand des Projekts (z. B. das Deutsche Literaturarchiv Marbach, das Historische Archiv des Börsenvereins des Deutschen Buchhandels).

#### 2. Bundesarchiv

Hier wurden nur die Standorte in Berlin und Koblenz berücksichtigt.
Der ab 1996 erfolgte Umzug nach Berlin-Lichterfelde zog massive Veränderungen in der Tektonik und in den Signaturen nach sich. Die vor dieser Zeit bereits aufgenommenen Daten wurden größtenteils korrigiert. Der Benutzer muss jedoch die noch nicht abgeschlossene Neuordnung des Archivs berücksichtigen.

#### 3. Staatliche Archive

Es wurden alle staatlichen Archive ausgewertet. Die Recherche fand generell "vor Ort" durch die Projektmitarbeiter statt.
Viele staatliche Archive, z. B. die thüringischen, das LHA Schwerin oder das Generallandesarchiv Karlsruhe erarbeiteten neue Bestandsübersichten. Die Veränderungen in Tektonik und Signaturgebung wurden nachträglich berücksichtigt, soweit dies im Rahmen der Projektzeit zu leisten war.

#### 4. Kommunale Archive

Die kommunalen Archive stellen die Mehrzahl der in das Inventar aufgenommenen Archive. Zunächst wurden alle Archive schriftlich nach dem Vorhandensein von relevanten Beständen befragt. Eigene Recherchen "vor Ort" wurden aus zeitlichen Gründen bei ca. einem Drittel der auszuwertenden Archive vorgenommen. Weitere Angaben wurden auf der Grundlage der von den Archiven auf Anfrage selbst zusammengestellten Inventare übernommen (ca. 15%).
Etwa 25% der kommunalen Archive gaben an, kein themenrelevantes Material zu besitzen.
Archive, die auf die Befragung nicht reagierten (ca. 30%), wurden nicht weiter berücksichtigt. Die kommunalen Archive in Berlin (Stadtbezirksarchive) wurden nicht in das Erschließungskonzept einbezogen.

#### 5. Kirchenarchive

Grundsätzlich galt der Hauptanteil der Erschließung den Archiven der obersten kirchlichen Verwaltungsebene der evangelischen und der katholischen Kirche. Deposita kirchlicher Archivalien in staatlichen Archiven sind an den entsprechenden Stellen beim jeweiligen Archiv vermerkt.
Aus unterschiedlichen Gründen war nicht in allen kirchlichen Archiven eine Recherche möglich. So befanden sich zum Zeitpunkt der Bearbeitung die Bistumsarchive in Görlitz, Magdeburg, Essen und Schwerin noch in der Aufbauphase.
Pfarrarchive fanden Berücksichtigung, wenn sie in den Archiven der obersten kirchlichen Verwaltungsebene als Deposita vorhanden waren. Ausnahmen wurden z. B. im LKA Dresden oder dem Diözesanarchiv Osnabrück gemacht, wo fast der gesamte Bestand der Generalia im Krieg vernichtet wurde und die fehlende Überlieferung durch die Kirchgemeinden bzw. Pfarrarchive teilweise ausgeglichen werden konnte.
Häufiger als in den staatlichen und kommunalen Archiven sind Aktentitel sehr allgemein und knapp formuliert. Autopsie der Faszikel konnte jedoch nur bedingt vorgenommen werden. Der Benutzer, durch Hinweise des Inventars an die relevanten Bestände herangeführt, muss weiterführend eigene Erfahrungen und Suchstrategien einbringen.
Zu beachten sind die abweichenden Sperrfristen in den Archiven der katholischen Kirche von 40 bzw. von 60 Jahren für bischöfliche Nachlässe und Handakten. Personenbezogene Akten sind hier 30 Jahre nach dem Tod bzw. 120 Jahre nach der Geburt gesperrt. Eine Benutzung ist mit Sondergenehmigungen möglich.
Einige Archive gewährten Einblick in die Findmittel neuerer Bestände, ließen jedoch eine Titelaufnahme auf Grund der Sperrfristen nicht zu. Hinweise auf themenrelevantes Material findet der Benutzer in den Kommentaren zu den entsprechenden Archiven bzw. Beständen.

### AUSGEWERTETE BESTÄNDE
#### 1. Bestände von Verlagen

Schriftgut aus der unmittelbaren Tätigkeit von Verlagen und Buchhandlungen ist, oft auch als Depositum, eher selten. Eine größere Anzahl von derartigen Beständen (ca. 70) verwahrt das Sächsische Staatsarchiv Leipzig.

#### 2. Bestände von Behörden mit Zuständigkeit für Verlage und Buchhandlungen

Grundsätzlich ausgewertet wurden die Ministerien des Innern, des Kultus, der Justiz, des Äußeren und diesen nachgeordnete Behörden. In deren Zuständigkeit gehören beispielsweise alle Zensurvorgänge, beginnend mit dem Erlassen von Gesetzen und Verordnungen, deren Ausführung, ihrer Kontrolle und weiterführenden Maßnahmen.

#### 3. Bestände, die häufig verlags- und buchhandelsgeschichtliche Quellen enthalten

Hier handelt es sich vorwiegend um Provenienzen aus den Bereichen "Handel und Gewerbe". Auch die Handelsregisterakten der Amtsgerichte, deren Einträge die Einrichtung und teilweise den Konkurs regionaler buchhändlerischer Firmen widerspiegeln, wurden berücksichtigt.

#### 4. Bestände zu wirtschaftlichen Belangen von Buchhandel und Verlagswesen

Hier wurden hauptsächlich die Akten der Finanzministerien und der diesen untergeordneten Behörden ausgewertet.

#### 5. Sonstige Bestände

Eine wichtige Quelle stellen Nachlässe von Personen und Organisationen dar. Das Schriftgut von Vereinen, wie von Bibel- oder Borromäusvereinen spielt beim kirchlichen Buchhandel eine grosse Rolle. Sammlungen kamen partiell in Betracht.
Auch Bestände von Behörden wie beispielsweise Forst- oder Landwirtschaftsministerien enthalten themenrelevante Angaben, auf die die Bearbeiter bei der Durchsicht der Findmittel, insbesondere von Spezialinventaren bzw. Registern stießen. Ihr Umfang ist abhängig von der vorgefundenen archivischen Erschließung.

### AUSWERTUNGSKRITERIEN
#### 1. Archivische Findmittel als Grundlage des Inventars

Die Aufnahme der Dokumente erfolgte auf der Basis der jeweiligen archivischen Findmittel. Die Spanne der Findmittel reichte von älteren, handschriftlichen Repertorien über maschinenschriftliche Karteien und Repertorien bis zu neu erstellten, rechnergestützten Findbüchern. Bei neu in ein Archiv übernommenen und noch nicht erschlossenen Beständen können der Erfassung auch Abgabelisten zugrunde liegen.

#### 2. Übernahme des Aktentitels

Grundprinzip der Aktenaufnahme war, den vorgefundenen Aktentitel genau zu übernehmen, einschließlich der vorgefundenen Begrifflichkeit und Orthographie. Diskrepanzen können auftreten bei Neuformulierungen in überarbeiteten Findmitteln bzw. bei Ansicht der Akte, da es sich bei den Findmitteleinträgen oft um verknappte Titel handelt. Oft spiegelt der Eintrag den eigentlichen Akteninhalt nur sehr ungenau wider, teilweise sind themenrelevante Akten nicht über den Aktentitel erkennbar. Hier erhält der Benutzer einen Bearbeiterhinweis im Autopsievermerk auf Faszikelebene.

#### 3. Autopsie als Ausnahmefall

Autopsie erfolgte

- bei ungenauen bzw. zu allgemein formulierten Aktentiteln;
- bei unleserlichen Angaben im Aktentitel, z. B. bei Eigennamen;
- bei wichtigen, themenrelevanten Beständen, die nicht über Findmittel erschlossen waren.

#### 4. Angaben zur Aktenlaufzeit

Angaben zur Laufzeit einer Akte sind vermerkt. Das Fehlen in den Findmitteln wurde im Kommentar vermerkt ("o. J.", "o. D." o. ä.). Die Laufzeit kann im letzteren Fall nur durch Autopsie ermittelt werden. Bei Angabe nur eines Datums ist zu beachten, dass damit oft lediglich der Beginn der Laufzeit einer Akte angegeben wird, der behandelte Vorgang sich jedoch auf viele Folgejahre erstrecken kann.

#### 5. Aktualität der erfassten Daten

Angaben zum Zeitpunkt der Recherche im jeweiligen Archiv findet der Benutzer im Kommentar. Die starke Bewegung der letzten Jahre in der Archivlandschaft, besonders in den neuen Bundesländern, ließ manche Angabe bereits während der Laufzeit der Bearbeitung veralten.
Oft führten neue Bestandsübersichten der Archive zu massiven Veränderungen in deren Tektonik und in den Signaturen. Solche Präzisierungen in den Angaben bereits ausgewerteter Archive wurden vorgenommen, soweit dies im Rahmen der Projektzeit zu leisten war.

#### 6. Registerrelevante Angaben der Bearbeiter

Eine inhaltliche Auswertung der aufgenommenen Faszikel durch die Projektbearbeiter erfolgte nach einem für alle Projektbereiche einheitlichen Erschließungskonzept und verbindlichen Erfassungsregeln. Die Daten sind über sechs Register erschlossen, die auch eine kombinierte Suche zulassen. Die Registerbegriffe sind ebenso wie die Aufnahme der Aktentitel quellennah und tragen damit eher Stichwortcharakter. Eine durchgehende Vereinheitlichung oder gar Normierung war nicht vorgesehen.

Erfassungszeitraum
Der zeitliche Rahmen des Inventars erstreckt sich von 1800 bis in die Gegenwart. In einzelnen Fällen sind Akten vor 1800 erfasst worden, wenn inhaltlich zusammenhängende Vorgänge vor diesem Datum einsetzten. Die Akten reichen abhängig von ihrer Verfügbarkeit in den einzelnen Archiven bis zwischen ca. 1952 und 1990.

### PROJEKTORGANISATION, MITARBEITER
#### 1. Laufzeit

Mit einer Umfrage unter staatlichen und kommunalen Archiven zum Vorhandensein buchhandelsgeschichtlicher Quellen startete die Herzog August Bibliothek Wolfenbüttel bereits 1985 Vorarbeiten zum Projekt. Das Inventar in der nun vorliegenden Form entstand zwischen 1992 und 1999.

#### 2. Projektphasen

Die Erschließungs- und Erfassungsarbeiten umfassten zwei Projektphasen:

Projektphase I: Staatliche und kommunale Archive
Staatliche und kommunale Archive	Nord	1989–1990 1991–1992
Kommunale Archive	Nord	1995–1996
Staatliche und kommunale Archive	Süd	1992–1995
Staatliche Archive (Abschlussbearbeitung des Projektbereiches Nord)	Süd	1997–1998
Staatliche und kommunale Archive	Ost	1992–1995
Staatliche Archive (Abschlussbearbeitung des Projektbereiches Nord)	Ost	1997–1998

Projektphase II: Kirchliche Archive
Süd	1995–1997
Ost	1995–1997
