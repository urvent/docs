Vorbereitung einer Veranstaltung
================================

Allgemein
---------

.. _general_topic:

Veranstaltung anlegen
~~~~~~~~~~~~~~~~~~~~~

Veranstaltungen bieten die Grundlage für alle weiteren Komponenten. Damit eine neue Veranstaltung zur Verfügung steht muss zunächst eine neue unter **Veranstaltung > Themen** erstellt werden.

:Anfang / Ende:
    Der Zeitraum an dem die Veranstaltung stattfindet und im System verwaltet werden soll

:Archiv:
    Blendet die Veranstaltung an diversen Stellen aus, z.B. Darstellung für den Nutzer als historische Veranstaltung

:Automatische Kartennummern:
    Wenn ausgewählt, wird für jeden Teilnehmer eine automatische Identifikationsnummer generiert. Diese wird u.A. für die Scanner Terminals verwendet. Wenn vorkodierte Aufkleber / Karten mit QR Codes verwendet werden, sollte diese Option nicht ausgewählt werden.

:Registrierung:
    :Anfang / Ende:
        Zeitraum in dem sich Teilnehmer für eine Veranstaltung als Interessent anmelden können

    :AGB:
        Hinweistext der bei der jeder Anmeldung für einen Teilnehmer angezeigt werden soll

.. note::

    Nachdem eine Veranstaltung angelegt wurde, kann diese jederzeit in der Verwaltung gewechselt werden. Hierfür gibt es ein Dropdown in der oberen rechten Ecke der Navigation.

    .. image:: ../images/event_picker.png

Rollen anlegen
~~~~~~~~~~~~~~

Für eine Veranstaltung können mehrere Personengruppen (z.B. Ärzte, Helfer, Lager) unter **Veranstaltung > Rollen** erstellt werden.

:Farbe:
    Kann z.B. für den Druck von Kartenlayouts verwendet werden

:Kartenlayout:
    Layout das beim Drucken von Teilnehmerkarten verwendet wird (siehe :ref:`Kartenlayout anlegen <general_cardlayout>`)

:Nummerierung:
    Teilnehmer erhalten automatisch eine interne Rollennummer zur einfacheren Identifikation.

    :Start:
        Erste Nummer die für diese Gruppe verwendet werden soll

    :Schritt:
        Abstand zwischen den Nummern

:Funktionen:
    Mögliche Funktionen (siehe :ref:`Funktion anlegen <personal_qualification>`) für diese Rolle (z.B. Rettungssanitäter, Fahrer). Dient zur weiteren Unterteilung der Rolle.

    .. note:: Ein Teilnehmer kann nur eine Funktion und Rolle haben.

:Registrierung:
    :Anfang / Ende:
        Zeitraum in dem sich Teilnehmer für eine Veranstaltung als Interessent anmelden kann.

        Der Bereich muss im Zeitraum der Registrierung der Veranstaltung (siehe :ref:`Anfang / Ende der Veranstaltung <general_topic>`) liegen.

    :Genehmigung durch die Organisation:
        Legt fest, ob ein Teilnehmer die Bestätigung durch seine Organisation (z.B. Rotes Kreuz) einholen muss. Wird bei der Anmeldung durch eine zusätzliche Checkbox angezeigt. Hat keine weitere fachliche Auswirkung auf das System.

    :Bearbeitung:
        Steuert, ob ein Teilnehmer im Nachhinein seine Anmeldung bearbeiten kann

    :Nachweise:
        Diese Nachweise (z.B. Gesundheitszeugnis) muss ein Teilnehmer zwingend hochgeladen haben, damit die Anmeldung zur Veranstaltung als gültig anerkannt werden kann.

.. _general_cardlayout:

(Optional) Kartenlayout anlegen
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Für Teilnehmer können Chipkarten (oder auch einfache Zettel) über einen Kartendrucker gedruckt werden. Diese werden für mehrere Prozesse an Scanner Terminal verwendet. Unter **Veranstaltung > Kartenlayout** können Layouts für diesen erstellt werden.

:Übergeordnet:
    Wenn keine Angaben für Style oder Layout angeben wurden, wird das Layout der hier ausgewählten Layouts verwendet.

:Layout:

    :Format:
        Spezifiziert das Format (z.B. Chipkarte, DIN A5, ...) der Karte.

    :CSS Klasse:
        Technischer Name kann im HTML als ``{{ class }}`` verwendet werden

    :Style:
        CSS Styling der Karte

    :Layout:
        HTML Layout der Karte


Einsatzorte anlegen
~~~~~~~~~~~~~~~~~~~

Unter **Veranstaltung > Einsatzorte** können neue Orte hinzugefügt werden an den Teilnehmer später Ihre Schicht absolvieren können.

Module
------

.. toctree::
   :maxdepth: 1

   Personal <personal>
   Küche <kitchen>
   Verleih <rental>
