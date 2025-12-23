# DIAS Fortschrittsprognose / Study Progress Forecast

Die **DIAS Fortschrittsprognose** ist eine Analysator-Komponente des DIAS-Projekts (Digitales Intelligentes Assistenzsystem) der Hochschule Ansbach. Sie hilft Studierenden, die voraussichtliche Studiendauer basierend auf ihrem aktuellen Fortschritt einzuschätzen.


<img width="2560" height="1320" alt="image" src="https://github.com/user-attachments/assets/9d2420ad-fcad-451c-a0c7-4cf1646afc85" />

Link zum Repository: [Frontend](https://github.com/dias-digitial-assistant/dias_main_frontend?tab=readme-ov-file) und [Backend](https://github.com/dias-digitial-assistant/studienfortschrittsprognose)


Die Fortschrittsprognose kann innerhalb der DIAS-Plattform durch Eingabe von "Studienfortschrittsprognose" aufgerufen werden.

### Funktionsweise

Die API berechnet:
- **Verbleibende Semester** bis zum Studienabschluss
- **Voraussichtliches Endsemester** basierend auf der bisherigen Leistung
- **Personalisierte Empfehlungen** mit Hinweisen und Kontaktinformationen

Eingabeparameter:
| Parameter | Beschreibung | Beispiel |
|-----------|--------------|----------|
| `typeStudy` | "B" für Bachelor (210 ECTS) oder "M" für Master (90 ECTS) | "B" |
| `actualSemester` | Aktuelles Semester | 3 |
| `actualCredits` | Voraussichtlich erreichte ECTS zum Ende des aktuellen Semesters | 60 |
