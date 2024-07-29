
[`Einführungsvideo auf YouTube ansehen`](https://youtu.be/uN3GkA_Afuw)

## Konzepte

Die Hauptkonzepte von Daily Money sind sehr einfach, es gibt nur drei:

> 1. Ein oder mehrere `Kontenbücher`
> 2. Verschiedene `Konten` innerhalb der Kontenbücher
> 3. Beträge zwischen verschiedenen Konten übertragen und diese `Transaktionen` aufzeichnen

## ![Kontenbücher](icon:///notebook-multiple) Kontenbücher

Mindestens ein Kontenbuch ist erforderlich, wobei die Konten die gleiche Währungseinheit haben. Sie können auch mehrere Kontenbücher mit der gleichen Währungseinheit nach Bedarf erstellen.

## ![Konten](icon:///bookmark-multiple) Konten

Es gibt fünf verschiedene Arten von Konten, die Sie auf dem Kontenverwaltungsbildschirm hinzufügen, bearbeiten oder löschen können.

> - `Einnahmen`: Gehalt usw.
> - `Ausgaben`: Essen, Unterhaltung usw.
> - `Vermögenswerte`: Bargeld, Bank usw.
> - `Verbindlichkeiten`: Kreditkarten, Darlehen usw.
> - `Andere`: ...

* Kontonamen können Punkte (.) zur Trennung verwenden (z.B. Essen.Dining, Essen.Treffen), was eine bessere hierarchische Anzeige beim Auswählen von Konten oder beim Betrachten von Bilanzen ermöglicht.
* Sie können Konten sortieren, um häufiger verwendete Konten zu priorisieren.

## ![Transaktionen](icon:///receipt) Transaktionen

Wenn es eine Transaktion zwischen Konten gibt, wie z.B. Ausgaben, Abhebungen, Einzahlungen oder Kreditkartenabrechnungen (z.B. Sie haben 320 Yuan für eine Mahlzeit ausgegeben), verwenden Sie `Neue Transaktion`, um eine neue Transaktion zu erstellen.
> - Wählen Sie `Datum und Uhrzeit`: Datum und Uhrzeit der Transaktion.
> - Wählen Sie `Ausgangskonto`: Bargeld
> - Wählen Sie `Eingangskonto`: Dining
> - Geben Sie `Betrag` ein: 320
> - Geben Sie `Notiz` ein: Treffen mit Freunden
> - Klicken Sie auf `Erstellen`

## Beispiele

### Gehaltsüberweisung auf Bank

> Ausgangs-`Einnahmen`-Konto: Gehalt
> Eingang-`Vermögenswerte`-Konto: Bank

### Bargeldabhebung von Bank

> Ausgangs-`Vermögenswerte`-Konto: Bank
> Eingang-`Vermögenswerte`-Konto: Bargeld

### Kauf eines Telefons mit Kreditkarte

> Ausgangs-`Verbindlichkeiten`-Konto: Kreditkarte
> Eingang-`Ausgaben`-Konto: Elektronik

### Kreditkartenrechnung mit Bank bezahlen

> Ausgangs-`Vermögenswerte`-Konto: Bank 
> Eingang-`Verbindlichkeiten`-Konto: Kreditkarte

## ![Bilanz](icon:///scale-balance)![Bilanzdiagramm](icon:///chart-pie) Bilanz & Diagramm

Durch sorgfältige Buchführung hilft Ihnen die Anwendung, alle Transaktionsdetails aufzuzeichnen und eine Bilanz nach Abfragebedingungen zu erstellen. Diese Bilanz zeigt klar das Verhältnis von Vermögenswerten und Verbindlichkeiten in verschiedenen Zeiträumen, sodass Sie Ihre finanzielle Situation besser verstehen können. Darüber hinaus kann die Anwendung verschiedene Diagramme erstellen, um Ihre Einnahmen und Ausgaben visuell darzustellen, was es Ihnen erleichtert, Ihren Finanzfluss zu verstehen.

## Anfangswerte der Konten

Wenn Sie die Anwendung zum ersten Mal verwenden, haben Sie möglicherweise bereits einige bestehende Konten mit tatsächlichen Werten, wie Bankguthaben, Bargeld oder Kreditkartenschulden. Um sicherzustellen, dass die Bilanz genauere Berechnungsergebnisse liefert, können Sie die Funktion zur Initialisierung der Konten verwenden, um die korrekten Anfangswerte dieser Konten festzulegen. Auf diese Weise kann die Bilanz die tatsächliche finanzielle Situation widerspiegeln.

## One-to-Many-Aufteilung

Manchmal kann eine einzelne Ausgabe mehrere Kategorien von Ausgaben umfassen. Zum Beispiel, wenn Sie im Supermarkt einkaufen, können Sie Lebensmittel, Haushaltswaren und Elektronik auf einmal kaufen. Um mit dieser Situation umzugehen, bietet die Anwendung eine erweiterte Transaktionserstellung und -bearbeitung, die es ermöglicht, eine einzelne Ausgabe auf mehrere verschiedene Ausgabenkategorien aufzuteilen. Mit anderen Worten, Sie können den Betrag einer einzelnen Kreditkartenzahlung auf mehrere Kategorien wie Lebensmittel, Haushaltswaren und Elektronik verteilen. Bitte beachten Sie: Bei Transaktionen innerhalb desselben Kontenbuchs, da die Währungseinheiten gleich sind, muss der insgesamt ausgegebene Betrag dem insgesamt erhaltenen Betrag entsprechen, ansonsten lehnt das Programm die Erstellung der Transaktion ab.

## Übertragung zwischen Kontenbüchern

Das Programm ermöglicht es Ihnen, zwischen Konten in verschiedenen Kontenbüchern zu übertragen. Sowohl im Basis- als auch im erweiterten Transaktionserstellungs- oder -bearbeitungsbildschirm können Sie Konten aus anderen Kontenbüchern auswählen. Da die Währungswerte zwischen verschiedenen Kontenbüchern unterschiedlich sein können und der Wechselkurs momentan nicht festgelegt ist, wie z.B. bei der Übertragung von New Taiwan Dollars zu US Dollars, wird das Programm Sie nicht einschränken, eine Transaktion zu erstellen, bei der der insgesamt ausgegebene Betrag dem insgesamt erhaltenen Betrag entsprechen muss. Bitte erstellen Sie Transaktionen basierend auf den tatsächlichen Beträgen und seien Sie vorsichtig.

## Schnellansicht von Bilanz und Diagrammen

Beim Durchsuchen der Bilanz oder der Diagramme können Sie bestimmte Kontoartikel zur Schnellansicht auf dem Startbildschirm hinzufügen [*1]. Wischen Sie einfach rechts über den Artikel in der Bilanz und klicken Sie auf `Zur Schnellansicht hinzufügen`, oder klicken Sie auf das "Zur Schnellansicht hinzufügen"-Symbol in der oberen rechten Ecke der Bilanzdiagrammkarte. Auf dem Startbildschirm sehen Sie dann die Bilanz der Vermögenswerte und Verbindlichkeiten für diesen Artikel, oder Sie können sie auf der Diagrammseite des Startbildschirms anzeigen. Darüber hinaus können Sie diese Artikel in `Einstellungen > Startbildschirmeinstellungen` sortieren oder entfernen.

[*1] Übermäßige Schnellansichten auf dem Startbildschirm können die Ladezeit des Startbildschirms beeinträchtigen.

## Transaktionsvorlagen und wiederkehrende Zeitplanung

Sie können Transaktionsvorlagen für häufige Buchungsvorgänge einrichten, sodass Sie schnell Transaktionen hinzufügen können. Sie können auch wiederkehrende Zeitplanvorlagen für regelmäßig wiederkehrende Buchungsvorgänge einrichten. Das Programm benachrichtigt Sie, wenn es fällig ist, sodass Sie die Transaktion schnell hinzufügen und automatisch für die nächste Fälligkeit planen können. Wischen Sie einfach nach links über das Element in der Transaktionsliste, tippen Sie dann auf `Vorlage erstellen` und geben Sie die Planungszeit ein, und erstellen Sie es dann. Zusätzlich können Sie diese Elemente auf der Seite `Transaktionsvorlagenverwaltung` sortieren, bearbeiten oder entfernen.