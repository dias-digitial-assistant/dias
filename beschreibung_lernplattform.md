# DIAS Lernsession Editor

Der **DIAS Lernsession-Editor** ist ein Werkzeug für Lehrende der Hochschule Ansbach, mit dem sie Lernsessions für Studierende erstellen können. Diese Sessions stehen anschließend über **DIAS Tutor** und **DIAS Quiz** zur Verfügung.

<img width="1016" height="838" alt="Screenshot-DIASPlattform" src="https://github.com/user-attachments/assets/6ec290d6-b07d-423a-b902-42f4335cde24" />

Link zum Repository: [Link](https://github.com/dias-digital-assistant/dias_backend_learnplatform)

## Erklärung und Anleitung

<img width="1772" height="931" alt="image" src="https://github.com/user-attachments/assets/d8aa61f1-8565-4a08-8aeb-f0c9f6595075" />

- Der Lern Session-Editor
Das Lern Session-Editor-Modell ermöglicht Lehrenden die vollständige Planung, Erstellung und Durchführung ganzer digitaler Unterrichtseinheiten auf Basis hochgeladener oder vorhandener Lernunterlagen. Es identifiziert automatisch passende Lernziele, generiert komplette Module mit strukturierten Fragen, Aufgaben, Zeitvorgaben und Abläufen sowie automatische Bewertungen und Lernfortschrittsanalysen.
Lehrende können so komplexe Präsenz-, Blended- oder Online-Veranstaltungen in einem Werkzeug vorbereiten, live steuern und auswerten. Studierende arbeiten selbstständig oder synchron in der vorgegebenen Struktur, erhalten sofortiges Feedback und dokumentieren ihren Fortschritt und Schwächen.
Die Echtzeit-Feedbackschleife (Live-Monitoring, Antwortstatistiken, Schwierigkeits-Heatmaps) fließt direkt an die Lehrenden zurück und dient der kontinuierlichen Optimierung der Lehrmodule, der gezielten Nachbereitung schwieriger Themen und der Anpassung kommender Vorlesungen und Übungen.
- Das Tutor-Modell nutzt hochgeladene Dokumenteninhalte und unterstützt durch interaktives, dialogorientiertes Lernen. Nach dem sokratischen Prinzip führt der virtuelle Tutor Studierende durch gezielte Gegenfragen und Denkanstöße zu eigenen Lösungen und fördert so kritisches Denken und tiefes Verständnis, um den eigenen Lernfortschritt zu reflektieren.
- Das Quiz-Modell identifiziert auf Grundlage bereitgestellter bzw. selbsthochgeladene Lernunterlagen automatisch relevante Lernziele und generiert passende Fragen mit anschließender Bewertung. Studierende können so ihre Wissenslücken erkennen, ihren Lernfortschritt dokumentieren und Karteikarten erstellen. Lehrende nutzen das System, indem sie eigene Lehrmodule durch die Generierung von Frage-Antwort-Paaren vorbereiten. Die Feedbackschleife der Studierenden an den Lehrenden dient der Optimierung der Lehrinhalte und der gezielten Wiederholungen in den Vorlesungen.


| Modell                  | Zielgruppe            | Hauptzweck                                      | Wichtigste Funktionen                                      |
|-------------------------|-----------------------|-------------------------------------------------|--------------------------------------------------------------------|
| **Lern Session-Editor** | **Lehrende**          | Komplette Unterrichtseinheiten digital planen, steuern und auswerten | - PDFs/Skripte hochladen<br>- Lernziele automatisch generieren<br>- Fragen & Aufgaben erstellen<br>- Module strukturieren & Ablauf steuern<br>- Live-Monitoring der Studierenden<br>- Ergebnis- & Schwachstellenanalyse |
| **Quiz-Modell**         | **Studierende**<br>(Lehrende zur Vorbereitung) | Automatische Wissensabfrage, Übung und Lernkontrolle | - MC-, offene, Zuordnungsfragen etc.<br>- Selbstlern- oder Prüfungsmodus<br>- Sofort-Feedback & Bewertung<br>- Karteikarten-Export<br>- Lernfortschritt & Wissenslücken sichtbar |
| **Tutor-Modell**           | **Studierende**       | Individuelle, dialogische Nachhilfe wie mit einem echten Tutor | - KI-Chat direkt mit deinen Dokumenten<br>- Sokratischer Dialog<br>- Schrittweise Erklärungen<br>- Keine fertigen Lösungen, sondern zum eigenen Denken anleiten<br>- 24/7 verfügbar |

### Kurze Merkhilfe
- **Lern Session-Editor** → der digitale Seminarraum der Lehrkraft  
- **Quiz-Modell** → der automatische Prüfer + Karteikarten-Trainer  
- **Tutor-Modell** → der persönliche 1:1-Nachhilfelehrer für jeden Studierenden



# 1. Der Lern Session-Editor für Lehrende

<img width="1797" height="975" alt="image" src="https://github.com/user-attachments/assets/5c13991d-2630-4b21-addd-a99621ad642b" />


Beschreibung: Erstelle als Lehrender / Dozent Lernmodule, generiere Ziele und Fragen, verwalte Lernfortschritte
Funktionen:

- PDF-Dokumente hochladen
- Lernziele generieren
- Fragen und Bewertungen erstellen
- Modulverwaltung

Bereich: KI-gestützte Autorenumgebung für Lehrkräfte und Ausbilder
Zweck: Schnelle Erstellung digitaler Lerninhalte durch automatisierte Generierung von Lernzielen, Fragen und Bewertungen aus hochgeladenen PDFs



# Modul erstellen

<img width="1457" height="978" alt="image" src="https://github.com/user-attachments/assets/8e454bb8-cc35-4455-903e-67196c07a13e" />

Auf dieser Seite legen Lehrende / Dozenten ein neues Lernmodul an.  
Die Plattform generiert anschließend automatisch Lernziele, Fragen und Lernsessions aus dem hochgeladenen Material.

## Felder und Einstellungen

| Feld                    | Beschreibung                                                                                 | Pflicht? |
|-------------------------|----------------------------------------------------------------------------------------------|----------|
| **Modulname**           | Kurzer, aussagekräftiger Titel des Moduls                                                    | Ja       |
| **Modulbeschreibung**   | Detaillierte Beschreibung, was die Lernenden im Modul lernen (z. B. Auszug aus dem Modulhandbuch) | Ja       |
| **PDF-Dokument hochladen** | Hochladen eines PDFs (Skript, Folien, Handout etc.)<br>• Max. 100 MB pro Datei<br>• Bilder und Formeln werden **nicht** verarbeitet<br>• Empfehlung: < 30 Seiten für schnellere Verarbeitung | Ja       |
| **Sichtbar für Studenten** | Checkbox – wenn angehakt, können Studierende das Modul sofort sehen und nutzen         | Optional (standardmäßig angehakt) |

## Buttons

- **Dateien durchsuchen** – öffnet den Datei-Dialog zum Auswählen der PDF
- **Abbrechen** – schließt das Fenster ohne zu speichern
- **Modul erstellen** – wird erst aktiv, wenn alle Pflichtfelder (Name, Beschreibung, PDF) ausgefüllt sind

## Ablauf in der Praxis

1. Modulname und Beschreibung eingeben  
2. PDF-Datei auswählen/highladen  
3. (Optional) Haken bei „Sichtbar für Studenten“ entfernen, wenn das Modul erst später freigegeben werden soll  
4. Auf **Modul erstellen** klicken  
   → Die Plattform analysiert das PDF und erzeugt automatisch Lernziele, Fragen, Erklärungen und Lernfortschritts-Tracking.

Danach kannst du im Reiter **Ziele verwalten** und **Fragen verwalten** alles weiter anpassen.


# Ziele verwalten

<img width="1420" height="950" alt="image" src="https://github.com/user-attachments/assets/03d4a9cc-c03e-4be1-85b1-5a450bf86e5f" />

**Modul für Zielverwaltung auswählen:**  
`Angewandte KI` ▼

**Zielerstellungsmethode wählen:**

- **KI-generierte Ziele**  
- Manuelle Zielerstellung


# 2. Das Quiz-Model für Studierende

<img width="1797" height="975" alt="image" src="https://github.com/user-attachments/assets/d7484863-1071-4666-bfce-a4d6db97f570" />

## Lehrenden-Modul – Übersicht & Erklärung

Der Bereich „Lehrenden-Modul verwenden“ ist exklusiv für Lehrende (Professor:innen, Dozent:innen, Tutor:innen, Lehrbeauftragte).
Hier geht es nicht darum, eigene Dokumente hochzuladen, sondern fertige, didaktisch geprüfte Lern- und Quizmodule direkt einzusetzen.

1.) Modul auswählen
Aus einer zentralen Bibliothek ein passendes Modul wählen (z. B. „BGB AT“, „Kostenrechnung“, „StrafrechtI“, „Organische Chemie“ usw.).

2.) Alles ist bereits vorbereitet
- Klare Lernziele
- Geprüfte Fragen (MC, offene Fragen, Lückentexte, Zuordnungen)
- Karteikarten & Zusammenfassungen inklusive

3.) Modul der Lerngruppe zuweisen
- Mit einem Klick dem gesamten Kurs, einem Seminar oder einzelnen Studierenden freigeben.

4.) Fortschritt & Ergebnisse einsehen
- Live-Übersicht: Wer hat wie viel bearbeitet?
- Erfolgsquoten pro Thema
- Schwachstellen der Gruppe sofort erkennen → gezielt im Unterricht nachbereiten

Vorteile für dich als Lehrende:r

- Einheitlicher Wissensstand in der Gruppe
- Minimaler Vorbereitungsaufwand
- Datenbasierte Erkennung von Verständnisproblemen
- Module semesterübergreifend wiederverwendbar
- Hohe fachliche Qualität durch Experten-Check

Mit dem Lehrenden-Modul wählst du mit einem Klick ein fertiges, hochwertiges Lern- und Quizpaket aus, 
gibst es deinen Studierenden und behältst den gesamten Lernfortschritt im Blick – effizienter geht Unterricht kaum!


Beschreibung: Übe mit vorbereiteten Modulen oder erstelle deine eigenen Lernmaterialien

- Lernmodule durchsuchen - Zugriff auf eine umfangreiche Bibliothek vorbereiteter Quizmodule
- Selbstlern-Modus - Individuelles Lerntempo und wiederholtes Üben
- Beantworte Fragen und erhalte Feedback - Sofortige Rückmeldung zu Antworten mit detaillierten Erklärungen
- Lernfortschritt verfolgen - Tracking deiner Entwicklung und Identifikation von Wissenslücken

## Lehrenden-Modul verwenden

![Quizmodel](https://github.com/user-attachments/assets/2712ac76-970c-4d2d-94a5-667aa5f873d2)

# Anleitung: Lehrenden-Modul in Quiz-Model verwenden (für Studierende)
So nutzt du die fertigen Quiz- und Lernmodule deiner Dozent:innen:

1.) Einloggen
Melde dich wie gewohnt in Quiz-Model an (du bist bereits angemeldet, siehe rechts oben).
2.) Zum Bereich „Lehrenden-Modul verwenden“ gehen
Du bist bereits richtig: Der blaue Tab „LEHRENDEN-MODUL VERWENDEN“ muss aktiv sein (wie im Screenshot).

3.) Ein Modul auswählen
Klicke auf den großen blauen Button „Module auswählen“.

4.) Gewünschtes Modul aus der Liste wählen
Klicke auf das Dropdown-Feld „Modul auswählen…“.
Es öffnet sich eine Liste mit allen Modulen, die deine Dozent:innen für dich/die Veranstaltung freigegeben haben.
Wähle das gewünschte Modul aus (z. B. „Anatomie Vorlesung WS 25/26“, „Strafrecht BT Übung“ etc.).

5.) Lern-/Quiz-Sitzung starten
Nach der Auswahl des Moduls wirst du automatisch weitergeleitet und kannst direkt mit dem Üben/Quiz beginnen.

6.) Bereits gestartete Sitzungen anschauen (optional)
Klicke stattdessen auf den grauen Button „Lernsitzungen“, um deine bisherigen Versuche, Ergebnisse und offenen Sitzungen dieses Moduls anzusehen.

Tipp:
Im Reiter „SELBSTLERNMODUS“ (nebenan) kannst du eigene Karten und Module erstellen – hier im Lehrenden-Modul nutzt du ausschließlich die vorgefertigten Inhalte deiner Lehrenden.

## Selbstlernmodus
<img width="1618" height="967" alt="image" src="https://github.com/user-attachments/assets/352cd78e-46bc-4e1a-b7b9-97c8f73c543a" />

Was ist der Selbstlernmodus?
Der Selbstlernmodus ist eine KI-gestützte Funktion auf Lernplattformen, der es Studierenden ermöglicht, 
aus eigenen Lernunterlagen automatisch personalisierte Quizfragen, Karteikarten und Übungen generieren zu lassen.

## So funktioniert der Selbstlernmodus

1.) Dokument hochladen
- Du lädst deine eigenen PDFs hoch (Vorlesungsskripte, Seminarunterlagen, Gesetzestexte, Buchkapitel etc.)
Empfehlung: PDFs < 30 Seiten für schnellere Verarbeitung
Maximale Dateigröße: 80 MB

2.) KI analysiert den Inhalt
Die KI liest und versteht das gesamte Dokument

3.) Automatische Generierung von Lernmaterialien
- Multiple-Choice-Fragen
- Offene Fragen
- Karteikarten (Flashcards)
- Lückentexte
- Zusammenfassungen
- Lernziele

4.) Selbstständiges Lernen & Testen
- Du beantwortest die generierten Fragen
- Automatische Bewertung (bei MC sofort, bei offenen Fragen oft mit KI-Feedback)
- Direkte Verlinkung zur richtigen Stelle im Originaldokument bei Fehlern

5.) Wiederholung mit System
- Falsch beantwortete Fragen kommen häufiger wieder (Spaced Repetition)
- Schwache Themen werden automatisch intensiver trainiert


Vorteile auf einen Blick

- 100 % passend zu deinem individuellen Stoff (keine generischen Fragen)
- Spart enorm viel Zeit bei der Erstellung von Karteikarten & Übungsfragen
- Fördert aktives Lernen (Active Recall – wissenschaftlich bewährte Methode)
- Ideal für Klausur- und Examensvorbereitung mit eigenen Uni-Unterlagen

Der Selbstlernmodus macht aus deinen PDFs in wenigen Minuten ein intelligentes, interaktives Quiz- und Karteikartensystem – perfekt abgestimmt auf genau deinen Lernstoff.

# 3. Tutor-Model für Studierende

<img width="1797" height="975" alt="image" src="https://github.com/user-attachments/assets/963bec0b-94c5-4ed2-a96a-3cea30c39f61" />


Beschreibung: Interaktive KI-gestützte Nachhilfe mit Dokumentkontext

- Lade deine eigenen Dokumente hoch - PDFs, Vorlesungsfolien, Skripte und Lehrbücher
- Chatte mit Dokumentinhalten - Stelle Fragen direkt zu hochgeladenen Materialien
- RAG-gestützte Generierung - Retrieval-Augmented Generation für präzise, kontextbasierte Antworten
- Lernreflexion Unterstützung - Sokratischer Dialog zur Vertiefung des Verständnisses

![Tutor Model](https://github.com/user-attachments/assets/63b1b920-1a3b-46c9-89d6-8364cb25ea11)


## Schnellstart
- Öffne: DIAS Overview
- Melde dich mit deiner Mailadresse oder ggf. mit deinem Hochschulaccount an.
- Wähle nach dem Login entweder "Quiz-Model für Stuiderende" oder "Tutor-Model für Studierende"
- Du kannst dir bevor du eine Entescheidung triffst zu den beiden Modellen noch ein Tutorial anschauen.
