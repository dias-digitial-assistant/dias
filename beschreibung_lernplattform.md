# DIAS Lernsession Editor

Der **DIAS Lernsession-Editor** ist ein Werkzeug für Lehrende der Hochschule Ansbach, mit dem sie Lernsessions für Studierende erstellen können. Diese Sessions stehen anschließend über **DIAS Tutor** und **DIAS Quiz** zur Verfügung.

<img width="1016" height="838" alt="Screenshot-DIASPlattform" src="https://github.com/user-attachments/assets/6ec290d6-b07d-423a-b902-42f4335cde24" />

## Erklärung und Anleitung

- Das Tutor-Modell nutzt hochgeladene Dokumenteninhalte und unterstützt durch interaktives, dialogorientiertes Lernen. Nach dem sokratischen Prinzip führt der virtuelle Tutor Studierende durch gezielte Gegenfragen und Denkanstöße zu eigenen Lösungen und fördert so kritisches Denken und tiefes Verständnis, um den eigenen Lernfortschritt zu reflektieren.
- Das Quiz-Modell identifiziert auf Grundlage bereitgestellter bzw. selbsthochgeladene Lernunterlagen automatisch relevante Lernziele und generiert passende Fragen mit anschließender Bewertung. Studierende können so ihre Wissenslücken erkennen, ihren Lernfortschritt dokumentieren und Karteikarten erstellen. Lehrende nutzen das System, indem sie eigene Lehrmodule durch die Generierung von Frage-Antwort-Paaren vorbereiten. Die Feedbackschleife der Studierenden an den Lehrenden dient der Optimierung der Lehrinhalte und der gezielten Wiederholungen in den Vorlesungen.

<img width="1772" height="931" alt="image" src="https://github.com/user-attachments/assets/d8aa61f1-8565-4a08-8aeb-f0c9f6595075" />



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

- 🔘 **KI-generierte Ziele**  
- ⚪ Manuelle Zielerstellung

**Anzahl der Lernziele (3-10):**  
`6` (Schieberegler auf 6)





# 2. Das Quiz-Model für Studierende

<img width="1797" height="975" alt="image" src="https://github.com/user-attachments/assets/d7484863-1071-4666-bfce-a4d6db97f570" />


Beschreibung: Übe mit vorbereiteten Modulen oder erstelle deine eigenen Lernmaterialien

- Lernmodule durchsuchen - Zugriff auf eine umfangreiche Bibliothek vorbereiteter Quizmodule
- Selbstlern-Modus - Individuelles Lerntempo und wiederholtes Üben
- Beantworte Fragen und erhalte Feedback - Sofortige Rückmeldung zu Antworten mit detaillierten Erklärungen
- Lernfortschritt verfolgen - Tracking deiner Entwicklung und Identifikation von Wissenslücken

![Quizmodel](https://github.com/user-attachments/assets/2712ac76-970c-4d2d-94a5-667aa5f873d2)



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
