========================
Lagerverwaltung
========================
Dieser Anleitungsbereich dient der Lagerleitung und Personen, welche für die Verwaltung der Lager in deiner Schar zuständig sind. Der erste Teil handelt davon, wie du ein neues Lager erstellen kannst. Der zweite Teil behandelt die Lageranmeldung. Dabei wird unterschieden, ob du als Lagerleiter die Kinder manuell hinzufügst oder sie über den ``Elternzugang`` durch ihre Eltern hinzufügen lässt. Über die Registerkarte ``Lager`` im Modul ``Gruppen`` gelangst du zur Übersicht aller erfassten Lager deiner Schar.

Lagerübersicht
==============

.. figure:: /media/lagerverwaltung/gruppe_lager_uebersicht.png
    :name: 
    
    Lagerverwaltung - Übersicht

Hier findest du verschiedene Schaltflächen zur Lagerverwaltung mit den folgenden Funktionen:

* **Lager erstellen**: Mit :guilabel:`Lager erstellen` öffnet sich ein neues Fenster, in dem ein neuer Anlass erstellt werden kann.  
* **Export**: Mit :guilabel:`Export` können die Lagerinformationen entweder im CSV-Dateiformat oder in einem Excel exportiert werden.
* **Kalender Export**: Mit :guilabel:`Kalender Export` wird das Lager automatisch in ein ICS-Dateiformat umgewandelt und im Browser heruntergeladen. Diese ICS-Datei kann schlussendlich in einen digitalen Kalender wieder importiert und eingefügt werden.
* **Historie & Filtern**: Die Filterfunktion oben links und die Historie oben rechts helfen dir dabei, ein bestimmtes Lager zu finden.

Lager erstellen
===============

Damit du ein neues Lager auf der Datenbank erstellen kannst, benötigst du die Rolle ``Lagerleitung`` oder ``Scharleitung``. Hast du eine dieser beiden Rollen, so kannst du durch das Anwählen von :guilabel:`Lager erstellen` ein neues Lager in der Datenbank erstellen und individuell konfigurieren. Die mit ***** markierten Felder müssen zwingend ausgefüllt werden. Die Anderen sind optional.

.. figure:: /media/lagerverwaltung/gruppe_lager_erstellen.png
    :name: 
    
    Lagerverwaltung - Lager erstellen

Allgemein
~~~~~~~~

Im Register ``Allgemein`` können Informationen wie **Name**, **Lagerart**, **Lagerbeschreibung**, **Motto**, **Kosten**, **Ort/Adresse** und **Coach** eingetragen werden.

.. figure:: /media/lagerverwaltung/lager-erstellen_uebersicht.png
    :name: 
    
    Lagerverwaltung - Allgemein

Zudem kann Folgendes definiert werden:

* **Nummer**: Hier kann die J+S‑Nummer eingetragen werden.
* **Kontaktperson**: Hier kann eine Kontaktperson für das Lager ausgewählt werden. Nach dem Auswählen öffnen sich Anzeigeoptionen, die festlegen, welche Informationen der Kontaktperson für die Lagerteilnehmenden angezeigt werden sollen.
* **Sichtbarkeit**: Mit dem Aktivieren von "Anlass ist für die ganze Datenbank sichtbar" ermöglichst du anderen Scharen, sich für euer Lager anzumelden.

Daten
~~~~~~

Unter ``Daten`` wird der Zeitraum des Lagers definiert.

.. figure:: /media/lagerverwaltung/lager-erstellen_daten.png
    :name: 
    
    Lagerverwaltung - Daten

* **von**/**bis**: Start- und Enddatum des Lagers
* **Bezeichung**: zum Beispiel Sommerlager
* **Ort**: Adresse vom Lagerplatz
* **Eintrag hinzufügen**: Falls dein Lager in zwei Abschnitte aufgeteilt ist, kann mit ``Eintrag hinzufügen`` eine weitere Zeitspanne definert werden.

Anmeldung
~~~~~~~~~~

Im Register ``Anmeldung`` definierst du alles Organisatorische für deine Lageranmeldung.

.. figure:: /media/lagerverwaltung/lager-erstellen_anmeldung.png
    :name: 
    
    Lagerverwaltung - Anmeldung

* **Anmeldebeginn/Anmeldeschluss**: Hier kannst du den Anmeldezeitraum bestimmen.
* **Aufnahmebedingungen**: Falls dein Lager Anforderungen an die Teilnehmenden stellt, wie zum Beispiel ein Mindestalter, kannst du diese hier definieren.
* **Teilnehmendenzahl**: Mit den Feldern ``Maximale-/Minimale Teilnehmendenzahl`` kann die Personenanzahl gesteuert werden. Wenn die maximale Anzahl bereits vor dem ``Anmeldeschluss`` erreicht wird, so wird das Anmeldefenster automatisch vorzeitig geschlossen.
* **Externe Anmeldungen**: Wenn aktiviert, können sich auch Personen, welche noch kein Profil auf der jubla Datenbank haben, für diesen Anlass anmelden. Falls die Eltern ihre Kinder über den ``Elternzugang`` selbst anmelden, empfiehlt sich, dieses Feld zu deaktivieren. So wird sichergestellt, dass die Eltern sich mit dem richtigen Profil anmelden.
* **Teilnehmersichtbarkeit**: Hier kann festgelegt werden, ob die Teilnehmenden sehen können, wer sich für das Lager angemeldet hat.
* **(Zweit)Unterschrift erforderlich**: ??✏️
* **Abmeldung**: Die Teilnehmenden können sich selbst abmelden. Diese Funktion wird nicht empfohlen.
* **Anmeldebemerkungen**: Hier können Einverständnisabklärungen eingefügt werden (Datenschutz, Bildrechte etc.). Vorschläge findest du auf `jubla.netz/Lageranmeldung <https://jubla.atlassian.net/wiki/spaces/WISSEN/pages/1478819847/Lageranmeldung>`_ unter "Kleingedrucktes".

Anmeldeangaben
~~~~~~~~~~

Unter ``Anmeldeangaben`` kannst du hilfreiche und lagerrelevante Informationen über die Teilnehmenden einholen wie zum Beispiel, das Schwimmniveau, Essgewohnheiten, T-Shirt-Grösse etc. Durch Klicken auf ``Eintrag hinzufügen`` kannst du neue Fragen hinzufügen, welche die Teilnehmenden bei der Anmeldung beantworten müssen. Auf `jubla.netz/Lageranmeldung <https://jubla.atlassian.net/wiki/spaces/WISSEN/pages/1478819847/Lageranmeldung>`_ unter "Allgemeine Angaben" findest du Empfehlungen dazu, welche Informationen du dir einholen solltest.

.. figure:: /media/lagerverwaltung/lager-erstellen_anmeldeangaben.png
    :name: 
    
    Lagerverwaltung - Anmeldeangaben

* **Frage**: Definiere die Frage.
* **Antwortmöglichkeiten**: Durch ``Antwortmöglichkeit hinzufügen``, können Antworten vorgegeben werden. Für Freitextantworten keine Antwortmöglichkeiten hinzufügen. Wenn mehrere Antworten möglich sein sollen, ``Mehrfachauswahl`` aktivieren.
* **Obligatorisch**: Durch das Anwählen muss diese Frage zwingend beantwortet werden.
* **Sichtbar für**: Hier kannst du festlegen, welche Personen Zugriff auf die Antworten der Teilnehmenden zu dieser Frage haben.

Administrationsangaben
~~~~~~~~~~~~~~~~~~~~~~

??✏️

Kontaktangaben
~~~~~~~~~~~~~~

Hier kannst du wählen, welche Kontaktangaben der Teilnehmenden bei der Anmeldung abgefragt werden sollen. Es gibt die Möglichkeit, zwischen ``Obligatorisch``, ``Optional`` und ``Nicht anzeigen`` zu wählen.

.. important:: Die folgenden Angaben sind obligatorisch für die NDS: **Name**, **Vorname**, **Geburtsdatum**, **Geschlecht** (nur weiblich oder männlich zulässig auf der NDS), **AHV Nr**, **Nationalität**, **Muttersprache**, **Strasse**, **Hausnummer**, **PLZ**, **Ort**, **Land**

Anleitungsvideo
~~~~~~~~~~~~~~~~~~

Falls du bei der Lagererstellung lieber einem Video folgst, kannst du dir dieses :fa:`video` `Anleitungsvideo <https://jubla.atlassian.net/wiki/spaces/WISSEN/pages/1122467867/Jubla-Datenbank#Lagererfassung-auf-der-jubla.db>`_ anschauen. Hier wird dir Schritt für Schritt erklärt, wie die Lagererfassung in der jubla.db-Datenbank funktioniert.

Lageranmeldung
==============

Generell gibt es zwei Möglichkeiten, die Lagerteilnehmer*innen auf der jubla.db anzumelden. Entweder du lässt die Lagerteilnehmer/Eltern die Anmeldung analog per Post ausfüllen und fügst die Teilnehmenden anschliessend selbst in der Datenbank hinzu, oder du lässt die Anmeldung durch die Erziehungsberechtigten in der Datenbank vornehmen. Im Folgenden werden beide Methoden erklärt.

Teilnehmende als Lagerleiter*in hinzufügen
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

In der Registerkarte ``Teilnehmende`` deines Lagers, kannst du mit der Schaltfläche :guilabel:`Person hinzufügen` manuell Personen hinzufügen und ihre Rolle im Lager definieren. Wichtig ist, dass die Personen bereits ein Profil auf der ``jubla.db`` haben.

.. figure:: /media/lagerverwaltung/lageranmeldung_teilnehmende.png
    :name: 
    
    Lageranmeldung - Übersicht

Im Feld ``Person suchen`` kannst du mit dem Namen nach einer Person suchen und sie hinzufügen.

.. figure:: /media/lagerverwaltung/lageranmeldung_tn-erstellen.png
    :name: 
    
    Lageranmeldung - Teilnehmende hinzufügen

Wenn du beim Lagererstellen ``Anmeldeangaben`` definiert hast, so kannst du als Nächstes die Fragen für die Person beantworten und unter ``Bemerkungen`` weitere relevante Informationen ergänzen. Wenn du alles eingetragen hast, kannst du die Anmeldung abschliessen durch das Drücken von ``speichern``.

.. figure:: /media/lagerverwaltung/lageranmeldung_anmeldeangaben_ausfüllen.png
    :name: 
    
    Lageranmeldung - Anmeldeangaben

In diesem :fa:`video` `Anleitungsvideo <https://jubla.atlassian.net/wiki/spaces/WISSEN/pages/1122467867/Jubla-Datenbank#Teilnehmerverwaltung-f%C3%BCrs-Lager-via-jubla.db>`_ wird dir Schritt für Schritt gezeigt, wie du die Teilnehmenden für das Lager verwalten kannst.

Lageranmeldung über den Elternzugang
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Je grösser ein Lager ist, desto mehr Aufwand entsteht durch das manuelle Hinzufügen der Teilnehmenden. Um den Aufwand zu reduzieren, kannst du den ``Elternzugang`` für deine Schar einrichten. Dadurch können die Eltern die Profile ihrer Kinder verwalten und diese selbstständig für euer Lager anmelden. Wie du den ``Elternzugang`` einrichten kannst, wird dir unter ``Elternzugangsverwaltung`` erklärt. Im folgenden Abschnitt wird erklärt, wie die Eltern nach dem Einrichten des Zugangs ihre Kinder selbstständig auf der Datenbank anmelden können.

Damit es für die Eltern möglichst einfach ist, das Lager auf der Datenbank zu finden, kannst du auf ``Direktlink kopieren`` klicken und diesen Link mit den Eltern teilen.

.. figure:: /media/lagerverwaltung/lageranmeldung_elternzugang_link.png
    :name: 
    
    Lageranmeldung - Link

Wenn die Eltern den Link öffnen, landen sie direkt auf der Übersichtsseite des Lagers. Durch klicken auf ``Anmelden`` können die Eltern jetzt ganz einfach ihre Kinder anmelden.

.. figure:: /media/lagerverwaltung/lageranmeldung_elternzugang_kind_auswahl.png
    :name: 
    
    Lageranmeldung - Anmeldung

Anschliessend können die Eltern die Anmeldung ausfüllen und speichern. In diesem :fa:`video` `Anleitungsvideo <https://jubla.atlassian.net/wiki/spaces/WISSEN/pages/1122467867/Jubla-Datenbank#Lageranmeldung-f%C3%BCr-Eltern-und-Kinder-via-jubla.db>`_ wird dir Schritt für Schritt gezeigt, wie die Eltern ihre Kinder anmelden können.

.. figure:: /media/lagerverwaltung/lageranmeldung_elternzugang_kontaktangaben.png
    :name: 
    
    Lageranmeldung - Anmeldung
