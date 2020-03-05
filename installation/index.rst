Installation
============

.. contents::
   :depth: 2
   :local:

Anforderungen
-------------

Die Software ist komplett in PHP geschrieben und benötigt für die Speicherung der Daten eine Datenbank. Folgende Dinge sind zwingend für einen einwandfreien Betrieb notwendig:

- aktuelle PHP Version (PHP 7.4, Stand 02/2020)
- aktuelle MySQL bzw. Maria DB Datenbank
- 500 MB Speicherplatz, u.a. für hochgeladene Nachweis Dokumente
- E-Mail Konto zum versenden von Systemmails (Passwort vergessen, Registrierung, ...)
- SSH Zugriff für eine einfache Installation und Wartung des Systems

Berechtigungen
--------------

In der Verwaltung können Zugriffe auf einzelne Bereiche durch eine Zugriffssteuerung limitiert werden. Zugriffsberechtigungen lassen sich auf Gruppen und Personen anwenden.

.. hint::

    Für die bessere Übersicht und Transparenz werden Gruppen empfohlen.

Über **Benutzer > Gruppen** lassen sich neue Gruppen anlegen und verwalten und anschließend einem Benutzer über **Benutzer > Benutzer**  zugewiesen werden.

Pro (Teil)Bereich können mehrere Rechte über eine Matrix hinzugefügt werden:

:ALL:
    Vollzugriff

:CREATE:
    Erlaubt das Erstellen von neuen Objekten

:DELETE:
    Erlaubt das Löschen von Objekten

:EDIT:
    Erlaubt die Bearbeitung von Objekten

:EXPORT:
    Erlaubt es die Liste von Objekten als Excel oder CSV zu exportieren

:LIST:
    Erlaubt die Listenanzeige

:VIEW:
    Erlaubt das Lesen von Objekten

.. image:: ../images/user_role_matrix.png

Neben den allgemeinen Berechtigungen gibt es noch einige allgemeine Berechtigungen:

:ROLE_ADMIN:
    Erlaubt Zugriff auf die Verwaltung

:ROLE_ALLOWED_TO_SWITCH:
    Erlaubt das temporäre Anmelden als anderer Benutzer. Kann zum Nachstellen von Fehlern verwendet werden.

:ROLE_SUPER_ADMIN:
    Vollzugriff auf alle Bereiche in der Verwaltung inkl. aller Funktionen

:ROLE_USER:
    Keine besondere Behandlung
