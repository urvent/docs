Vorbereitung einer Veranstaltung
================================

Allgemein
---------

Veranstaltung anlegen
~~~~~~~~~~~~~~~~~~~~~

Veranstaltungen bieten die Grundlage für alle weiteren Komponenten. Damit eine neue Veranstaltung zur Verfügung steht muss zunächst eine neue unter **Veranstaltung > Themen** erstellt werden.

:Anfang / Ende:
    Der Zeitraum an dem die Veranstaltung stattfindet und im System verwaltet werden soll

:Archiv:
    Blendet die Veranstaltung an diversen Stellen aus

:Registrierung:
    :Anfang / Ende:
        Zeitraum in dem sich Teilnehmer für eine Veranstaltung als Interessent anmelden können

    :AGB:
        Hinweistext der bei der Veranstaltungsanmeldung angezeigt werden soll

.. note::

    Nachdem eine Veranstaltung angelegt wurde, kann diese jederzeit in der Verwaltung gewechselt werden. Hierfür gibt es ein Dropdown in der oberen rechten Ecke der Navigation.

    .. image:: ../images/event_picker.png

Rollen anlegen
~~~~~~~~~~~~~~

Für eine Veranstaltung können mehrere Personengruppen (z.B. Ärzte, Helfer, Lager) unter **Veranstaltung > Rollen** erstellt werden.

:Farbe:
    Kann z.B. für den Druck von Kartenlayouts verwendet werden

:Kartenlayout:
    Layout das beim Drucken von Teilnehmerkarten verwendet wird

:Nummerierung:
    Teilnehmer erhalten automatisch eine interne Rollennummer

    :Start:
        Erste Nummer die für diese Gruppe verwendet werden soll

    :Schritt:
        Abstand zwischen den Nummern

:Qualifikationen:
    Mögliche Qualifikationen für diese Rolle (z.B. Rettungssanitäter, Fahrer). Kann als weitere Untergruppierung eines Teilnehmers verwendet werden. Nur eine pro Teilnehmer ist möglich.

:Registrierung:
    :Anfang / Ende:
        Zeitraum in dem sich Teilnehmer für eine Veranstaltung als Interessent anmelden können. Muss zwingend im Bereich der Registrierung der Veranstaltung liegen.

    :Genehmigung durch die Organisation:
        Legt fest, ob ein Teilnehmer die Bestätigung durch seine Organisation (z.B. Rotes Kreuz) einholen muss. Wird bei der Anmeldung durch eine zusätzliche Checkbox angezeigt. Hat keine weitere fachliche Auswirkung auf das System.

    :Bearbeitung:
        Steuert, ob ein Teilnehmer im Nachhinein seine Anmeldung bearbeiten kann

    :Nachweise:
        Diese Nachweise (z.B. Gesundheitszeugnis) muss ein Teilnehmer zwingend hochgeladen haben, damit die Anmeldung zur Veranstaltung als gültig anerkannt werden kann.

(Optional) Kartenlayout anlegen
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Für Teilnehmer können Chipkarten über einen Kartendrucker gedruckt werden. Diese werden für mehrere Prozesse an Scanner Terminal verwendet. Unter **Veranstaltung > Kartenlayout** können Layouts für diesen erstellt werden.

:Übergeordnet:
    Wenn keine Angaben für Style oder Layout angeben wurden, wird die Werte des hier angebenen Layouts verwendet.

:Layout:

    :Format:
        Spezifiziert das Format der Karte.

    :CSS Klasse:
        Technischer Name kann im HTML als ``{{ class }}`` verwendet werden

    :Style:
        CSS Styling der Karte

    :Layout:
        HTML Layout der Karte


Einsatzorte anlegen
~~~~~~~~~~~~~~~~~~~

Um Personen später einen Ort zuzuweisen können mehrere Einsatzorte unter **Veranstaltung > Einsatzorte** angelegt werden.

Module
------

.. toctree::
   :maxdepth: 1

   Personal <personal>
   Küche <kitchen>
   Verleih <rental>
