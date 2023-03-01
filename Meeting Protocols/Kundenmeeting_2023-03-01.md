# Meeting Protocol template

**Datum:** 01.03.2023

## Teilnehmer
Inf Unibe:
- Kaspar Riesen
- Thomas Studer

Assistenten:
- Dominik Fischli
- Sascha Künzle

Entwicklerteam:
- Luca D'Arcangelo
- Michael Kaiser
- Ramon Näf

**Sitzungsleiter:** Michael Kaiser

**Protkollführung:** Ramon Näf

## Traktanden
1. Vorstellungsrunde
2. Anforderung Erwartung an das Endprodukt
    - User Stories
    - Funktionalitäten
    - Lieferungsform/Lieferungserwartungen
    - Neuentwicklung oder Aufbau auf CMS (Open Source)
3. Bereitgestellte Hardware 
    - Welche Informtionen werden für die Maschine benötigt
    - Hardware Specs
    - Allfälliges Realtime Monitoring (z.B. UpTime Kuma)
4. weitere Meeting Termine/Zyklus
5. allfällige Planung der Releases/Schritt 1
6. Organisatorisch mit Prof. Studer:
    - Fehlendes Teammitglied
    - Klare Trennung, wann als Kunde und wann als Anspruchsperson.


## Beschlüsse
1. Vorstellung


2. Anforderungen:
    - Anwendung in Kursen für Pharmazeuten und Biologen
        - Anwendung an Gymnasien 
        - Evtl. ausbaubar für Anwendung an Mittelschulen für obligatorisches Fach Informatik.
        - Lieber stabile und gut erweiterbare Grundfunktonen, an Stelle von wielen Features!
    - OpenSource als Basis gut geeignet.
        - Vorschlag unserer Seits: CMS, da basierend auf Python und JavaScript, somit gut erweiterbar.
        - 
    - Für 1. Iteration: 
        - Login-Feld
        - Input-Feld
        - Feedbacks:
            - Orange: 
                - Timelimit exeeded.
            - Grün: 
                - compiles
                - All workes well.
            - Rot: 
                - Can't compile
        - Funktioinalität über Aussehen.
            - CMS zum Laufen bringen
        
    - Frontend evtl. in nächster Iteration
        - Interface evtl. in CMS vorhanden (z.B. für Kontests, Admin Logins, etc.)
            - "Uni Bern Theme" steht nicht dringend im Vordergrund.
        - Usability steht im Vordergrund.
        - Kontests sollten anklickbar bleiben, auch nach Abschluss.

    - Dokumentation:
        - Evtl. Dokumentation für zukünftiger Gebrauch von "Nicht-Informatikern".
        - Für Moment, auf CMS-Dokumentation basieren.

    - Evtl. in nächster Iteration einfache Erweiterungen einführen 
        - Feedback 
        - Tags für nötiges Wissenslevel
        - Access (z.B. Felder nur für Admins)
        - möglichkeiten Hilfe zu erhalten)


    - Lizenz:
        - Public Repo. ist in Ordnung

    - User Stories:
        - Code upload --> Basic Feedback
        - Grundfunktionalität
    - Aufwand:
        - Grösserer Aufwand: Änderung an Grundstruktur
        - Rest: kleiner bis mittlerer Aufwand 

    - Gamification
        - kleine Sachen wie Video bei Erfolg

    - Für Korrektur Divs verwenden kann einfacher sein, als mit Unittests. (Fürs ignorieren von kleinen Sachen, wie WhiteSpaces, Kommafehler, etc.)
        - Erleichtert das potentielle Erweitern
        - Verkleinert Frustniveau 

3. 
    - Server: 
        - Kontaktperson: Peppo Brambilla
        - Zu Beginn ca. 150 Concurrent Users sollten möglich sein.

4. Meetings:
    - Tendentiell erst, wenn etwas läuft.
    - Pro Woche ein Update-Mail an Kunden
    - Nächstes Meeting: in 2 Wochen, gleicher Ort, gleiche Zeit. (15.03.2023)

5. (Siehe oben)

6. Besprechung mit Prof. Studer
    - Fehlender Teammate: Freiwillige Personen fragen
