# DIAS Lernsession Editor

Der **DIAS Lernsession-Editor** ist ein Werkzeug für Lehrende der Hochschule Ansbach, mit dem sie Lernsessions für Studierende erstellen können. Diese Sessions stehen anschließend über **DIAS Tutor** und **DIAS Quiz** zur Verfügung.

## Navigation
- Navigiere zu DIAS Lernplattform
- Lehrende: Wähle "Lernsession Editor" (Berechtigung notwendig)
- Studierende: Wähle nach dem Login entweder "Quiz-Model für Stuiderende" oder "Tutor-Model für Studierende"
- Du kannst dir bevor du eine Entscheidung triffst zu den drei Modellen noch ein Tutorial anschauen.

<img width="1016" height="838" alt="Screenshot-DIASPlattform" src="https://github.com/user-attachments/assets/6ec290d6-b07d-423a-b902-42f4335cde24" />

Link zum Repository: [Frontend](https://github.com/dias-digitial-assistant/dias_main_frontend) und [Backend](https://github.com/dias-digitial-assistant/lernplattform_backend)

## Erklärung und Anleitung

<img width="1772" height="931" alt="image" src="https://github.com/user-attachments/assets/d8aa61f1-8565-4a08-8aeb-f0c9f6595075" />

- Der Lern Session-Editor ermöglicht Lehrenden die Erstellung und Durchführung von Lerneinheiten auf Basis hochgeladener oder vorhandener Lernunterlagen. Es generiert automatisch passende Lernziele und strukturierte Frage- Antwortpaare.
Lehrende können so Lerneinheiten in einem Werkzeug vorbereiten und durch Feedback der Studierenden in der Plattform auswerten. Studierende arbeiten selbstständig in der vorgegebenen Struktur, erhalten sofortiges Feedback und dokumentieren ihre Fortschritte und Schwächen. Die Echtzeit-Feedbackschleife fließt direkt an die Lehrenden zurück und dient der kontinuierlichen Optimierung der Lehrmodule, der gezielten Nachbereitung schwieriger Themen und der Anpassung kommender Vorlesungen und Übungen.
- Das Tutor-Modell nutzt hochgeladene Dokumenteninhalte und unterstützt durch interaktives, dialogorientiertes Lernen. Nach dem sokratischen Prinzip führt der virtuelle Tutor Studierende durch gezielte Gegenfragen und Denkanstöße zu eigenen Lösungen und fördert so kritisches Denken und tiefes Verständnis, um den eigenen Lernfortschritt zu reflektieren.
- Das Quiz-Modell identifiziert auf Grundlage bereitgestellter bzw. selbsthochgeladene Lernunterlagen automatisch Lernziele und generiert passende Fragen mit anschließender Bewertung. Studierende können so ihre Wissenslücken erkennen, ihren Lernfortschritt dokumentieren und Karteikarten erstellen. Lehrende nutzen das System, indem sie eigene Lehrmodule durch die Generierung von Frage-Antwort-Paaren vorbereiten. Die Feedbackschleife der Studierenden an den Lehrenden dient der Optimierung der Lehrinhalte und der gezielten Wiederholungen in den Vorlesungen.

### Kurze Übersicht
- **Lern Session-Editor** → der digitale Vorbereitungsraum der Lehrkraft  
- **Quiz-Modell** → der automatische Prüfer + Feedbackloop
- **Tutor-Modell** → der persönliche 1:1-Tutor für jeden Studierenden

| Modell                  | Zielgruppe            | Hauptzweck                                      | Wichtigste Funktionen                                      |
|-------------------------|-----------------------|-------------------------------------------------|--------------------------------------------------------------------|
| **Lern Session-Editor** | **Lehrende**          | - Lerneinheiten vorbereiten | - PDFs/Skripte hochladen<br>- Lernziele automatisch generieren<br>- Fragen & Aufgaben erstellen<br>- Module strukturieren <br>- Ergebnis- & Schwachstellenanalyse durch Studierenden Feedback|
| **Quiz-Modell**         | **Studierende**<br> | Wissenslücken erkennen - Automatische Wissensabfrage, Übung und Lernkontrolle | - offene Zuordnungsfragen <br>- Vorbereitete Lerneinheiten durch Lehrende <br>- Selbstlernmodus <br>- Sofort-Feedback & Bewertung<br>- Karteikarten |
| **Tutor-Modell**           | **Studierende**       | Lernfortschritt reflektieren - Individuelle, dialogische Lernsession wie mit einem echten Tutor | - KI-Chat direkt mit deinen Dokumenten<br>- Sokratischer Dialog<br>- Schrittweise Erklärungen<br>- Keine direkten Lösungen, sondern zum eigenen Denken anleiten<br>- 24/7 verfügbar |


# Anleitung für Nutzer

# 1. Der Lern Session-Editor für Lehrende

<img width="1797" height="975" alt="image" src="https://github.com/user-attachments/assets/5c13991d-2630-4b21-addd-a99621ad642b" />


Beschreibung: Erstelle als Lehrender Lernmodule, generiere Ziele und Frage- Antwortpaare, verwalte Lernfortschritte
Funktionen:

- PDF-Dokumente hochladen
- Lernziele generieren
- Fragen und Antworten erstellen
- Modulverwaltung

Bereich: KI-gestützte Autorenumgebung für Lehrkräfte und Ausbilder
Zweck: Schnelle Erstellung digitaler Lerninhalte durch automatisierte Generierung von Lernzielen, Fragen und Bewertungen aus hochgeladenen PDFs



# Modul erstellen

<img width="1457" height="978" alt="image" src="https://github.com/user-attachments/assets/8e454bb8-cc35-4455-903e-67196c07a13e" />

Auf dieser Seite legen Lehrende ein neues Lernmodul an.  
Die Plattform generiert anschließend automatisch Lernziele, Fragen und Antworten aus dem hochgeladenen Material.

## Felder und Einstellungen

| Feld                    | Beschreibung                                                                                 | Pflichtfeld? |
|-------------------------|----------------------------------------------------------------------------------------------|----------|
| **Modulname**           | Kurzer, aussagekräftiger Titel des Moduls                                                    | Ja       |
| **Modulbeschreibung**   | Beschreibung, was die Lernenden im Modul lernen (z. B. Auszug aus dem Modulhandbuch) | Ja       |
| **PDF-Dokument hochladen** | Hochladen eines PDFs (Skript, Folien, Handout etc.)<br>• Max. 100 MB pro Datei<br>• Bilder und Formeln werden **nicht** verarbeitet<br>• Empfehlung: < 30 Seiten für schnellere Verarbeitung | Ja       |
| **Sichtbar für Studenten** | Checkbox – wenn angehakt, können Studierende das Modul sofort sehen und nutzen         | Optional (standardmäßig angehakt) |

## Buttons

- **Dateien durchsuchen** – öffnet den Datei-Dialog zum Auswählen der PDF
- **Abbrechen** – schließt das Fenster ohne zu speichern
- **Modul erstellen** – wird erst aktiv, wenn alle Pflichtfelder (Name, Beschreibung, PDF) ausgefüllt sind

## Ablauf in der Praxis

1. Modulname und Beschreibung eingeben  
2. PDF-Datei auswählen/hochladen  
3. (Optional) Haken bei „Sichtbar für Studenten“ entfernen, wenn das Modul erst später freigegeben werden soll  
4. Auf **Modul erstellen** klicken  
   → Die Plattform analysiert das PDF und erzeugt automatisch Lernziele, Fragen und Antworten.

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

Der Bereich „Lehrenden-Modul verwenden“ basiert auf Modulen vorbereitet von Lehrenden für Studierende.
Hier geht es nicht darum, eigene Dokumente hochzuladen, sondern fertige, geprüfte Lern- und Quizmodule direkt als Studierender zu nutzen.

1.) Modul auswählen
Aus einer zentralen Bibliothek ein passendes Modul wählen (z. B. „BGB AT“, „Kostenrechnung“, „Strafrecht“, „Organische Chemie“ usw.).

2.) Alles ist bereits vorbereitet
- Klare Lernziele
- Geprüfte Fragen mit Antworten
- Karteikarten

3.) Fortschritt & Ergebnisse einsehen
- Studierende schicken nach ihrer Lerneinheit ein Feedback (optional: mit Name oder anonymisiert)
- Schwächen und Stärken werden anonymisiert dem Lehrenden gezeigt

Mit dem Lehrenden-Modul wählst du mit einem Klick ein Lern- und Quizpaket aus, 
gibst es deinen Studierenden und behältst den gesamten Lernfortschritt im Blick.

Tipp für Studierende:
Im Reiter „SELBSTLERNMODUS“ (nebenan) kannst du als Studierender eigene Karten und Module erstellen – hier im Lehrenden-Modul nutzt du ausschließlich die vorgefertigten Inhalte deiner Lehrenden.

## Lehrenden-Modul verwenden

![Quizmodel](https://github.com/user-attachments/assets/2712ac76-970c-4d2d-94a5-667aa5f873d2)


## Selbstlernmodus
<img width="1618" height="967" alt="image" src="https://github.com/user-attachments/assets/352cd78e-46bc-4e1a-b7b9-97c8f73c543a" />

Was ist der Selbstlernmodus?
Der Selbstlernmodus ist eine KI-gestützte Funktion in der Lernplattform, der es Studierenden ermöglicht, 
aus eigenen Lernunterlagen automatisch Lernziele, Quizfragen, Bewertungen und Karteikarten generieren zu lassen.

## So funktioniert der Selbstlernmodus

1.) Dokument hochladen
- Du lädst deine eigenen PDFs hoch (Vorlesungsskripte, Seminarunterlagen, Gesetzestexte, Buchkapitel etc.)
Empfehlung: PDFs < 30 Seiten für schnellere Verarbeitung
Maximale Dateigröße: 80 MB

2.) KI analysiert den Inhalt
Die KI liest das gesamte Dokument

3.) Automatische Generierung von Lernmaterialien
- Lernziele
- Frage-Antwortpaare

4.) Selbstständiges Lernen & Testen
- Du beantwortest die generierten Fragen
- Automatische Bewertung mit Feedback
- Überarbeitung der Antwort und iterative Bewertung

5.) Lernsession Historie
- Lernsessions können dokumentiert und nur vom Nutzer reflektiert werden


Vorteile auf einen Blick

- Passend zu deinem individuellen Stoff (keine generischen Fragen)
- Spart Zeit bei der Erstellung von Übungsfragen und Bewertung
- Aktives strukturiertes Lernen durch Lernziele
- Für Klausur- und Examensvorbereitung mit eigenen Uni-Unterlagen

# 3. Tutor-Model für Studierende

<img width="1797" height="975" alt="image" src="https://github.com/user-attachments/assets/963bec0b-94c5-4ed2-a96a-3cea30c39f61" />


Beschreibung: Interaktive KI-gestützte Lernsession mit Dokumentkontext

- Lade deine eigenen Dokumente hoch - PDFs, Vorlesungsfolien, Skripte und Lehrbücher
- Chatte mit Dokumentinhalten - Stelle Fragen direkt zu hochgeladenen Materialien
- RAG-gestützte Generierung - Retrieval-Augmented Generation für präzise, kontextbasierte Antworten
- Lernreflexion Unterstützung - Sokratischer Dialog zur Vertiefung des Verständnisses

![Tutor Model](https://github.com/user-attachments/assets/63b1b920-1a3b-46c9-89d6-8364cb25ea11)


