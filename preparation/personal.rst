Vorbereitungen für Personal
===========================

(Optional) Qualifikationen anlegen
----------------------------------

Qualifikationen sind eine Untergruppierung einer Rolle. Angelegt werde diese über **Personal > Qualifikation**.

:Kartenlayout:
    Layout das beim Drucken von Teilnehmerkarten verwendet wird. Überschreibt das Layout der Rolle

(Optional) Erfahrungen anlegen
------------------------------

Sind Fertigkeiten (z.B. Technischer Funker), die ein Teilnehmer mitbringt und die später zur Filterung verwendet werde können. Angelegt werden diese über **Personal > Erfahrungen**.

(Optional) Sprachen anlegen
---------------------------

Gesprochene Sprachen eines Teilnehmers und die später zur Filterung verwendet werde können. Angelegt werden diese über **Personal > Sprachen**.

(Optional) Nachweis Kategorien anlegen
--------------------------------------

Kategorien die ein Teilnehmer beim Hochladen eines Nachweises auswählen kann. Angelegt werden diese über **Klassifizierung > Kategorien > Kategorie: Nachweise"**.

Schichten anlegen
-----------------

Schichten sind Zeitslots in dem ein Teilnehmer seiner Arbeit nachgeht. Während dieser Zeit kann ein Teilnehmer einen Ort zugewiesen sein.

.. _personal_shift:

Manuell
~~~~~~~

Die manuelle Anlage sollte nur in Ausnahmefällen oder zur Nachbearbeitung verwendet werden. In der Regel sollte mit der :ref:`personal_shift_batch` neue Schichten angelegt werden..

Unter **Personal > Schichten** kann eine neue Schicht angelegt werden.

:Rolle:
    Benötigte Rolle um diese Schicht zu absolvieren

:Startdatum:
    Erstes Datum für das eine Schicht angelegt werden soll.

:Enddatum:
    Letztes Datum an dem eine Schicht angelegt werden soll.

:Schichtanfang / -ende:
    Zeitpunkt an dem die Schicht stattfindet

:Anmeldung / Abmeldung:
    Werden hier eine Anfang und Ende Zeit ausgewählt, muss ein Teilnehmer sich zur erfolgreichen Ausführung der Schicht am Veranstaltungstag im System manuell anmelden. Wird hier keine Zeit ausgewähl, wird die Person automatisch als Angemeldet im System erkannt.

    Hier gilt die gleiche Logik für Tag und Uhrzeit wie bei dem Schichtanfang bzw. Schichtende.

:Soll:
    Wird nur in der Statistik als interner Merker angezeigt.

:Wünschbar:
    Legt fest, ob ein Teilnehmer diese bei der Anmeldung auswählen kann oder ob dieses nur durch einen Manager erfolgen kann.

:Wunschlimit:
    Legt fest wie viele Teilnehmer sich diese Schicht wünschen können. Kann verwendet werden um Überbelegungen einzelner Schichten zu vermeiden.

:Essenzeit:
    Zeiten in der die Kantine von einem Teilnehmer aufgesucht werden kann.

    .. note::

        Es sind noch weitere Schritte notwendig, damit der Teilnehmer auch ein Essen enhält. Weitere Informationen befinden sich im `Küchenmodul <kitchen>`_.

.. _personal_shift_batch:

Massenanlage
~~~~~~~~~~~~

Um mehrere gleichartige Schichten für eine Rolle anzulegen kann das **Batch Erstellung** Tool unter **Personal > Schichten** verwendet werden.

Beschreibung der einzelnen Felder, siehe :ref:`manuelle Anlage <personal_shift>`.

Neben den fachlichen Feldern gibt es für die Massenanlage zwei technische Felder:

:Tag:
    Relative Differenz zu dem Datum. Sollte in der Regel immer 0 sein, außer eine Schicht beginnt sehr spät oder erstreckt sich über mehrere Tage.

:Uhrzeit:
    Uhrzeit der Schicht

.. note::

    Wird als Startdatum der 01.08.2020, als Enddatum der 10.08.2020, als Schichtanfang Tag 0 und 20:00 und als Schichtende Tag 1 und 03:00 Uhr gewählt, so werden insgesamt 10 einzelne Schichten erstellt.

    Die erste Schicht beginnt am 01.08.2020 10:00 Uhr und endet am 02.08.2020 03:00 Uhr. Die letzte Schicht beginnt am 10.08.2020 10:00 Uhr und endet am 11.08.2020 03:00 Uhr.

.. _personal_shift_post_edit:

Schicht Nachbearbeitung
~~~~~~~~~~~~~~~~~~~~~~~

Sollen nach der Anlage Werte verändert werden, kann dieses über die Nachbearbeitung erfolgen. Im unteren Menü der Übersicht können eine oder mehrere Schichten bearbeitet werden.

.. image:: ../images/personal_shift_batch.png

Feldbeschreibung siehe :ref:`Manuelle Anlage von Schichten <personal_shift>`.

Organisationen anlegen
----------------------

Für eine Anmeldung zu einer Veranstaltung muss der Teilnehmer seine Organisation angeben, über die der Teilnehmer sich anmelden möchte.

Organisation sind in mehreren Hierarchiestufen abgebildet: **Organisationsart > Landesverband > Kreisverband > Organisation**

Organisationsart anlegen
~~~~~~~~~~~~~~~~~~~~~~~~

Eine Organisationsart ist die gröbste Einheit (z.B. DRK, DLRG). Angelegt werden diese über **Organisation > Organisationsarten**.

:Genehmigung erforderlich:
    Wird diese Option gewählt, muss ein Teilnehmer bei der Anmeldung bestätigen, dass er die Genehmigung seiner Organisation erhalten hat.

Landesverbände / Kresiverbände anlegen
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Sind Untergruppierung der Organisationsart.

Organisationen anlegen
~~~~~~~~~~~~~~~~~~~~~~

Eine Organisation ist das Element, dass ein Teilnehmer bei der Anmeldung auswählen kann.


