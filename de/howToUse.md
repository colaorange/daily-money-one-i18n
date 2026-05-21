
[`Einführungsvideo auf YouTube ansehen`](https://youtu.be/uN3GkA_Afuw)
[`Online-Dokumentation`](https://colaorange.gitbook.io/daily-money-one-doc/eng)

## Konzepte

Die wichtigsten Konzepte von Daily Money sind sehr einfach. Es gibt nur drei:

> 1. Ein oder mehrere `Bücher`
> 2. Verschiedene `Konten` innerhalb der Bücher
> 3. Beträge zwischen verschiedenen Konten übertragen und diese `Buchungen` erfassen

## ![Books](icon:///notebook-multiple) Bücher

Mindestens ein Buch ist erforderlich. Die Konten darin verwenden dieselbe Währungseinheit. Sie können je nach Bedarf auch mehrere Bücher mit derselben Währungseinheit erstellen.

## ![Accounts](icon:///bookmark-multiple) Konten

Es gibt fünf verschiedene Kontotypen, die Sie in der Kontenverwaltung hinzufügen, bearbeiten oder löschen können.

> - `Einnahme`: Gehalt usw.
> - `Ausgabe`: Essen, Unterhaltung usw.
> - `Vermögen`: Bargeld, Bank usw.
> - `Verbindlichkeit`: Kreditkarten, Darlehen usw.
> - `Sonstiges`: ...

* Kontonamen können Punkte (.) zur Trennung verwenden (z. B. Essen.Restaurant, Essen.Treffen). Das ermöglicht eine bessere hierarchische Anzeige beim Auswählen von Konten oder beim Anzeigen von Bilanzen.
* Sie können Konten sortieren, um häufig genutzte Konten weiter oben anzuzeigen.

## ![Transactions](icon:///receipt) Buchungen

Wenn es eine Buchung zwischen Konten gibt, etwa eine Ausgabe, eine Umbuchung zwischen Konten oder eine Zahlung per Kreditkarte (z. B. 320 Yuan für ein Essen), verwenden Sie `Neue Buchung`, um eine neue Buchung zu erstellen.
> - `Datum & Uhrzeit` auswählen: Datum und Uhrzeit der Buchung.
> - `Quelle` auswählen: Bargeld
> - `Ziel` auswählen: Restaurant
> - `Betrag` eingeben: 320
> - `Notiz` eingeben: Treffen mit Freunden
> - `Erstellen` antippen

## Beispiele

### Gehalt auf Bankkonto übertragen

> `Einnahme`-Konto als Quelle: Gehalt
> `Vermögen`-Konto als Ziel: Bank

### Bargeld von der Bank abheben

> `Vermögen`-Konto als Quelle: Bank
> `Vermögen`-Konto als Ziel: Bargeld

### Telefon mit Kreditkarte kaufen

> `Verbindlichkeit`-Konto als Quelle: Kreditkarte
> `Ausgabe`-Konto als Ziel: Elektronik

### Kreditkartenrechnung mit Bankkonto bezahlen

> `Vermögen`-Konto als Quelle: Bank
> `Verbindlichkeit`-Konto als Ziel: Kreditkarte

## ![Balance Sheet](icon:///scale-balance)![Balance Chart](icon:///chart-pie) Bilanz & Diagramm

Durch sorgfältige Buchführung hilft die Anwendung dabei, alle Buchungsdetails zu erfassen und je nach Suchbedingungen eine Bilanz zu erstellen. Diese Bilanz zeigt die Salden von Vermögen und Verbindlichkeiten in unterschiedlichen Zeiträumen klar an, damit Sie Ihre finanzielle Lage besser verstehen. Zusätzlich kann die Anwendung verschiedene Diagramme erzeugen, die Einnahmen und Ausgaben visuell darstellen und Ihre Geldflüsse leichter verständlich machen.

## Anfangssalden von Konten

Wenn Sie die Anwendung zum ersten Mal verwenden, haben Sie möglicherweise bereits bestehende Konten mit realen Werten, etwa Bankguthaben, Bargeld oder Kreditkartenschulden. Damit die Bilanz genauere Ergebnisse liefert, können Sie die Initialisierung von Konten verwenden, um die korrekten Anfangssalden festzulegen. So spiegelt die Bilanz Ihre tatsächliche finanzielle Situation wider.

## Eins-zu-viele-Aufteilung (Erweitert)

Manchmal umfasst eine einzelne Ausgabe mehrere Ausgabenkategorien. Beim Einkauf im Supermarkt kaufen Sie zum Beispiel Lebensmittel, Haushaltsartikel und Elektronik auf einmal. Für solche Fälle bietet die Anwendung die erweiterte Erstellung und Bearbeitung von Buchungen, mit der eine einzelne Ausgabe auf mehrere Ausgabenkategorien verteilt werden kann. Anders gesagt: Sie können den Betrag einer Kreditkartenzahlung auf Kategorien wie Lebensmittel, Haushaltsartikel und Elektronik aufteilen. Hinweis: Bei Buchungen innerhalb desselben Buchs sind die Währungseinheiten gleich, daher muss der Gesamtbetrag der Quellen dem Gesamtbetrag der Ziele entsprechen. Andernfalls lehnt das Programm die Erstellung der Buchung ab.

## Übertragung zwischen Büchern

Das Programm erlaubt Übertragungen zwischen Konten in verschiedenen Büchern. Sowohl in der einfachen als auch in der erweiterten Buchungserstellung oder -bearbeitung können Sie beim Auswählen von Konten auch Konten aus anderen Büchern wählen. Da Währungswerte zwischen verschiedenen Büchern unterschiedlich sein können und der Wechselkurs nicht feststeht, etwa bei einer Übertragung von Neuen Taiwan-Dollar in US-Dollar, erzwingt das Programm nicht, dass der Gesamtbetrag der Quellen dem Gesamtbetrag der Ziele entspricht. Erstellen Sie solche Buchungen anhand der tatsächlichen Beträge und gehen Sie sorgfältig vor.

## Schnellansicht für Bilanz und Diagramme

Beim Durchsehen der Bilanz oder Diagramme können Sie bestimmte Kontoelemente zur Schnellansicht auf dem Startbildschirm hinzufügen [*1]. Wischen Sie einfach in der Bilanz auf dem Element nach rechts und tippen Sie auf `Zur Schnellansicht hinzufügen`, oder tippen Sie oben rechts auf der Diagrammkarte auf das Symbol "Zur Schnellansicht hinzufügen". Danach sehen Sie auf dem Startbildschirm den Saldo von Vermögen und Verbindlichkeiten für dieses Element, oder Sie können ihn auf der Diagrammseite des Startbildschirms ansehen. Außerdem können Sie diese Elemente unter `Einstellungen > Startbildschirm` sortieren oder entfernen.

[*1] Zu viele Schnellansicht-Elemente auf dem Startbildschirm können die Ladezeit des Startbildschirms beeinflussen.

## Vorlagen und wiederkehrende Zeitplanung

Sie können Buchungsvorlagen für häufige Buchführungsvorgänge einrichten, um Buchungen schneller hinzuzufügen. Außerdem können Sie wiederkehrende Zeitplanvorlagen für regelmäßig wiederkehrende Vorgänge einrichten. Das Programm benachrichtigt Sie bei Fälligkeit, sodass Sie die Buchung schnell hinzufügen können, und plant sie automatisch für den nächsten Fälligkeitstermin. Wischen Sie in der Buchungsliste einfach auf einem Element nach links, tippen Sie auf `Neue Vorlage`, geben Sie die Zeitplanung ein und erstellen Sie sie. Außerdem können Sie diese Elemente auf der Seite `Vorlagen` sortieren, bearbeiten oder entfernen.

## Budgeteinstellungen

Beim Durchsehen der Bilanz wischen Sie einfach auf einem Kontoelement nach rechts, tippen dann auf `Budget erstellen` und wählen den Modus. Nach der Erstellung können Sie den Budgetfortschritt in der Bilanz oder in der Schnellansicht auf dem Startbildschirm sehen. Außerdem können Sie diese Elemente auf der Seite `Budgets` sortieren, bearbeiten oder entfernen.
