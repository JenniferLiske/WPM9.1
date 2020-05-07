# Datenintensive Prozesse im Stadtarchiv Wuppertal

Author: Jennifer Liske

## Das Stadtarchiv – eine kurze Vorstellung

Das [Stadtarchiv Wuppertal](https://www.friedrich-engels-haus.de/stadtarchiv/was-wir-tun) bewahrt rund 6,5 Regalkilometer archivwürdiger Dokumente aus städtischen und privaten Akzessionen. Weitere Bestände bilden historische Zeitungen sowie eine Karten-, Plakat- und Fotosammlung. Darüber hinaus führt das Stadtarchiv eine Präsenzbibliothek, in der über 6000 Titel für Benutzer zur Verfügung stehen. Teile dieser Bestände werden in Word-, PDF- und Excel-Dokumenten gepflegt. Im Archivprogramm [Augias](https://www.augias.de) werden hauptsächlich städtische Bestände sowie die Zeitgeschichtliche Sammlung gepflegt.

## Ausgangssituation

Im Stadtarchiv Wuppertal gibt es verschiedenste Datenintensive Prozesse, in die unterschiedliche Mitarbeiter eingebunden sind. Eine besondere Herausforderung ist durch die analoge Prägung vieler Prozesse gegeben. Im Folgenden sollen die Prozesse kurz erörtert werden:

**Pflege der Besucherinformationen im Lesesaal**

-	Im Lesesaal wird handschriftlich ein Besucherbuch geführt. In diesem werden Name, Thema des Besuchs und benutzte Archivalien notiert
-	Eine separate Akte mit Besucheranträgen wird ebenfalls geführt. Die Informationen aus den Anträgen (Name, Adresse, Thema und genutzte Archivalien) werden händisch in der Benutzerverwaltung von Augias eingetragen und durch Informationen zu entrichteten Entgelten ergänzt.
-	Über die genutzten Archivalien wird, aufgeschlüsselt nach Urkunde, Akte, Fotografie, Zeitung und Zeitungskopie, eine Strichliste geführt. Diese wird jeden Monat in eine Excel-Tabelle zusammen mit Besuchertagen eingetragen.

**Recherchen mittels Informationssammlungen auf dem Laufwerk**

-	Das Stadtarchiv pflegt eine Stadtchronik. In dieser sind seit 1929 lokalgeschichtliche Ereignisse mit Datum, Ereignis und Zeitungsartikel eingetragen. Hier muss mit einer Volltextrecherche gesucht werden. Ergebnisse dieser Recherchen werden derzeit in Word oder handschriftlich notiert und als Liste an den Benutzer weitergegeben.
-	Die Präsenzbibliothek des Stadtarchivs wird derzeit neu verzeichnet. Dazu werden die Buchbestände aus dem Karteisystem in eine Access Datenbank eingetragen.

**Städtische Aussonderungen**

-	Eine zentrale Aufgabe des Stadtarchivs ist die Übernahme von Schriftgut aus den Leistungseinheiten der Stadtverwaltung, das als archivwürdig eingestuft wurde. Für diesen formalisierten Prozess ist unter anderem die Datenpflege besonders wichtig, da übernommene Akten nicht direkt verzeichnet werden können. Die abgebende Stelle nutzt ein Formular zur Prüfung des Archivguts, dieses wird von den Archivaren bearbeitet und mit der Einstufung der Akten als *archivwürdig* oder *kassabel* zurückgesendet. Die relevanten Informationen werden in Excel Tabell nachgehalten. Wenn die Akten als *archivwürdig* eingestuft wurden, werden die Zugangsinformationen in einer weiteren Excel Liste abgelegt.

**Private Übernahmen**

-	private Übernahmen werden in einem Excel Dokumenten aufgenommen. Hier werden abgebende Stelle oder Person mit Kontaktdaten, Titel, Thema, Akzessionsnummer (Zugangsnummer) und Bestandssignatur erfasst. 

**Verzeichnung von Akten**

-	Im Stadtarchiv wird nach Beständen verzeichnet, mehrere Zugänge können einen Bestand bilden. Die Definition von Beständen ergibt sich aus dem Organigramm der Stadtverwaltung, so gibt es beispielsweise den Bestand *Jugend* für das Jugendamt oder *Von der Heydt-Museum* für das städtische Kunstmuseum in Wuppertal.
-	Akten werden als Datensatz in Augias eingepflegt. Dazu werden strukturelle und inhaltliche Metadaten aufgenommen, wie Zugang, Titel, Laufzeit, Inhalt und Umfang der Akte. Jedem Datensatz wird eine Signatur zugeordnet.

## Beispielprozess: Städtische Übernahmen

Die Akzession von städtischem Schriftgut ist, wie zuvor erwähnt, eine zentrale Aufgabe des Stadtarchivs. Der Prozess soll zunächst erläutert werden, um dann mögliche Potentiale für den Einsatz von Software oder Skripten herauszuarbeiten.
Wenn die Aufbewahrungsfrist gemäß der Schriftgutordnung der Stadt abgelaufen ist, füllt die entsprechende Leistungseinheit (LE) die „Mitteilung an das Stadtarchiv über ausgesondertes Schriftgut“ aus und schickt diese an das Stadtarchiv. Hier werden folgende Informationen erfasst:
* die Leistungseinheit
* das Datum
* der Ansprechpartner
* die Kontaktinformationen
* der Umfang
* das Aktenzeichen
* die Laufzeit
*die Aufbewahrungsfrist
* eine inhaltliche Beschreibung
Anhand dieser Angaben entscheidet der Archivar ob die Akten *archivwürdig* oder *kassabel* sind (hier wird der Regelprozess abgebildet. In ca. 30% der Fälle erfolgt eine Vorortprüfung der Akten. Dieser Zwischenschritt hat keine Auswirkung auf die entstehenden Daten und wird daher nicht abgebildet). Nachdem die Akten mit einem *a* für *archivwürdig* oder einem *k* für *kassabel* gekennzeichnet wurde, trägt der Archivar Name, Datum und Durchwahl ein und sendet das Formular zurück an die Leistungseinheit, gegebenenfalls mit der Bitte die Akten dem Stadtarchiv zukommen zu lassen. Wenn alle Akten als *kassabel* eingestuft wurden, können diese von der Leistungseinheit vernichtet werden. 
Der Archivar füllt im Anschluss immer unabhänging von der Entscheidung eine Excel Liste aus (Tabelle 1):

| Datum | LE | Menge | Art der Unterlagen | Bewertung | Begründung | eingetroffen |
| ----- | -- | ----- | ------------------ | ----------| -----------| ------------ |
| 01.02.20|  Ressort 103 | 10 Akten | Planung und Karten des Skulpturenparks | A | erheblicher Evidenzwert | Nr. 05/2020 | 


Sofern Akten als archivwürdig eingestuft wurden, wird nach dem Eintreffen der Akten im Archiv eine weitere Excel Liste befüllt (Tabelle 2):

| Zugangsnr | Typ | Zugangsdatum | Provenienz | Inhalt | Laufzeit | Menge | Art | Lagerort | Karton | Mappe | Entmetallisiert|
| --------- | --- | ------------ | ---------- | ------ | -------- | ----- | --- | -------- | ------ | ----- | -------------- |
| 05/2020 | Akten | 01.03.2020 | Ressort 103 | Planung und Karten des Skulpturenparks | 2000-2005 | 0,7 lfm | Akten | EG Regal 28 | nein | nein | nein |

Diese beiden Tabellen existieren parallel. Zum einen ist dies ein unnötiger Arbeitsaufwand, da die Daten teilweise identisch sind (LE und Provenienz, Menge, Art der Unterlage und Inhalt, eingetroffen und Zugangsnummer). Zum anderen wird bei Recherchen in diesen nicht verzeichneten Beständen das Durchsuchen beider Excel Dateien nötig. Recherchen fallen bei jeder potentiellen Übernahme an, um eine Kontinuität zu gewährleisten, sowie bei entsprechenden Anfragen. 
Durch teilweise lange Zeiträume zwischen Anbietung der Akten und dem Zugang dieser im Archiv, hat es sich nicht ergeben, beide Informationen zusammen in einer Datei zu pflegen. Die Excel Listen werden seit teilweise 6 Jahren geführt, daher ist eine Übertragung und Zusammenbringung der beiden Dateien nur mit erheblichen Arbeitsaufwand zu leisten. Es erscheint daher sinnvoll, diese Dateien abzuschließen und neu zu beginnen. Bei der Gestaltung einer neuen Excel Tabelle müsste berücksichtigt werden, dass nicht bei jeder Aktenanbietung Akten als *archivwürdig* eingestuft und übernommen werden. Um die Tabelle möglichst übersichtlich zu gestalten, könnte sie chronolgisch aufgebaut werden. 
Für die Bearbeitung der Excel Datei zur Anbietung der Akten durch eine Leistungseinheit (Tabelle 1) würde der Datenimport aus dem Formular „Mitteilung an das Stadtarchiv über ausgesondertes Schriftgut“ eine Optimierung darstellen. Datum, Inhalt, Umfang, LE und Laufzeit könnten direkt übernommen werden. Beim Inhalt müssten gegebenenfalls kleinere Nachbesserungen erfolgen, da dies von der abgebenden LE häufig nur oberflächlich ausgefüllt wird. Beim Ausfüllen der Excel Datei zum Archivzugang (Tabelle 2) könnten wiederum Daten aus der Exceltabelle zur Anbietung der Akten (Tabelle 1) direkt übernommen werden, wenn die Dateien nicht zusammengeführt würden.

Eine Herausforderung ist, dass viele LE *archivwürdig* gekennzeichnete Akten oft erst Monate später an das Stadtarchiv schicken. Daher müssen die Excellisten regelmäßig kontrolliert werden. Eine Optimierung wäre durch eine Software oder ein Skript denkbar, das eine automatische Erinnerung in Outlook erstellen würde. Wenn *archivwürdige* Akten nach einem Monat noch nicht in der Zugangsliste vermerkt wurden, könnte beispielsweise ein Pop-Up mit einer Erinnerung kommen.
Für die Recherche wäre eine Art Verknüpfung der Dateien, oder ein Skript das die Dateien gleichzeitig durchsucht und Ergebnisse direkt in eine Textdatei gibt wünschenswert. Besonders das gleichzeitige Durchsuchen und die Ausgabe in eine Textdatei würde den Prozess für alle Mitarbeiter transparenter gestalten. Die Benutzerbetreuung recherchiert ebenfalls in den Excel Dateien, hier fällt die Orientierung oft schwer, da die Kollegen nicht mit der Thematik vertraut sind.

Es ergeben sich, wie dargestellt, im Prozess Potentiale, insbesondere jedoch auch bei der Nachnutzung der eingetragenen Daten. Auch andere Prozesse bieten Optimierungspotentiale. So könnten beispielsweise bei Recherchen in der Stadtchronik mittels eines Skriptes Ergebnisse in einer Textdatei ausgegeben werden. Eine genauere Betrachtung der Prozesse scheint daher lohnenswert.

**Verweise**

* [Stadtarchiv Wuppertal](https://www.friedrich-engels-haus.de/stadtarchiv/was-wir-tun)

* [Augias](https://www.augias.de)

* [Kleines Glossar](https://www.bundesarchiv.de/DE/Navigation/Benutzen/Hilfe/Glossar/glossar.html)
