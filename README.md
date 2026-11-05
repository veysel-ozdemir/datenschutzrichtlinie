# Datenschutzerklärung
**Stand:** November 2026

Diese Datenschutzerklärung informiert Sie über die Art, den Umfang und den Zweck der Bearbeitung von Personendaten in unserer App.

## 1. Verantwortlicher
Verantwortlich für die Datenbearbeitung ist:  
**CorpoSana Gesundheitscenter AG**  
Münchensteinerstr. 220  
4053 Basel  
Schweiz  
E-Mail: info@corposana.ch

## 2. Bearbeitete Daten und Zwecke
Wir bearbeiten folgende Daten, um Ihnen die Funktionen der App bereitzustellen:

### a) Konto- und Profildaten
- **Welche Daten:** E-Mail-Adresse, Vor- und Nachname sowie die Benutzerrolle (Trainer oder Klient).
- **Zweck:** Anmeldung in der App mit E-Mail-Adresse und Passwort (Bestätigungscodes per E-Mail, z. B. beim Zurücksetzen des Passworts), Verwaltung Ihres Profils und sichere Zuordnung der Trainingsdaten.

### b) Gesundheits- und Fitnessdaten
- **Welche Daten:** Geburtsdatum, Geschlecht, Körpergrösse und -gewicht, Leistungsstufe, gesundheitliche Einschränkungen, Trainingseinheiten mit Übungen, Sätzen, Gewichten, Belastungsempfinden und Schmerzangaben, Notizen zu Übungen, Trainingspläne sowie Statistiken.
- **Zweck:** Der Kernzweck der App: die Steuerung, Erfassung und Auswertung Ihres Trainings. Trainer können auf die Daten ihrer Klienten zugreifen, um das Training zu betreuen und zu planen. Klienten sehen nur ihre eigenen Daten.

### c) Fotos und Videos von Übungen
- **Welche Daten:** Fotos und Videos der Übungsausführung, die Trainer oder Klienten in der App aufnehmen oder auswählen.
- **Zweck:** Dokumentation und Korrektur der Übungsausführung. Die Aufnahmen werden in Supabase gespeichert (siehe Ziffer 3) und sind nur für die Trainer und den betroffenen Klienten sichtbar.

### d) Geräte- und Nutzungsdaten
- **Welche Daten:** Gerätespezifische Informationen zur Darstellung und Fehlersuche (z. B. Plattform, Betriebssystemversion).
- **Zweck:** Sicherheit, Stabilität und Funktionsfähigkeit der App.

### e) Berechtigungen auf Ihrem Gerät
- **Dateien:** für den Export und Import von Trainingsdaten (z. B. Excel- oder PDF-Dateien).
- **Kamera und Fotomediathek:** für Fotos und Videos von Übungen.
- **Mikrofon:** für den Ton bei Übungsvideos und für das Diktieren von Nachrichten an den KI-Assistenten (siehe Ziffer 4). Die Spracherkennung läuft vollständig auf Ihrem Gerät: Die Aufnahme verlässt das Gerät nicht und wird nach der Erkennung gelöscht.

## 3. Supabase (Datenbank und Speicher)
- **Funktion:** Wir nutzen Supabase (Supabase Inc.) als Cloud-Dienstleister für die Datenbank, die Speicherung von Fotos und Videos sowie die Anmeldung.
- **Standort:** Die Server stehen in Frankfurt (Deutschland, EU).
- **Verarbeitete Daten:** Ihre Konto- und Profildaten sowie alle Fitness- und Gesundheitsdaten, Fotos und Videos werden verschlüsselt auf den Servern von Supabase gespeichert.
- **Schutz:** Zugriffsregeln auf Datenbankebene («Row Level Security») stellen sicher, dass Daten nur für Berechtigte abrufbar sind. Klienten können stets nur ihre eigenen Daten abrufen.

## 4. KI-Assistent für Trainingspläne
Trainer mit entsprechender Berechtigung können sich von einem KI-Assistenten einen Trainingsplan für einen Klienten vorschlagen lassen. Jeder Vorschlag ist ein Entwurf: Der Trainer prüft und bearbeitet ihn, bevor er gespeichert wird. Der KI-Assistent gibt keine medizinischen Ratschläge.

- **Nur mit Ihrer Einwilligung:** Der KI-Assistent wird für einen Klienten nur genutzt, wenn dieser ausdrücklich eingewilligt hat. Die Einwilligung ist freiwillig und hat keinen Einfluss auf die übrige Nutzung der App. Ihr Trainer kann sie in Ihrem Auftrag erfassen, wenn Sie zugestimmt haben. Sie können sie jederzeit widerrufen, indem Sie sich an Ihren Trainer wenden. Wir speichern, wann, durch wen und unter welcher Textfassung eine Einwilligung erteilt oder widerrufen wurde.
- **Welche Daten an die KI gehen:** Alter (nicht das Geburtsdatum), Geschlecht, Leistungsstufe, Körpergewicht und -grösse, gesundheitliche Einschränkungen, der Trainingsverlauf der letzten Einheiten (Übungen, Sätze, Gewichte, Belastungsempfinden, Schmerzangaben), Notizen zu Übungen, die Titel geplanter Trainingspläne sowie die Nachricht des Trainers.
- **Welche Daten nicht an die KI gehen:** Ihr Name, Ihre E-Mail-Adresse, Ihr Geburtsdatum und Ihre Kundennummer. Ihr Name wird auch in freien Texten (Notizen, Nachrichten) automatisch durch einen Platzhalter ersetzt. Die Daten gehen damit ohne direkten Bezug zu Ihrer Person an die KI.
- **Empfänger:** Die Anfrage geht an OpenRouter (OpenRouter, Inc., USA). OpenRouter leitet sie an ein KI-Modell weiter, das ein Rechenzentrumsbetreiber ausführt. Derzeit sind dies DeepInfra, Together AI, Fireworks AI, DigitalOcean und Wafer in den USA sowie Nebius in den Niederlanden. Als KI-Modell dient derzeit DeepSeek V4.1 Flash, ersatzweise NVIDIA Nemotron 3 Ultra. Die Daten gehen nur an die genannten Betreiber, nicht an die Hersteller der Modelle; Betreiber in China sind ausgeschlossen.
- **Keine Speicherung:** OpenRouter und die Betreiber speichern Anfragen und Antworten nicht über die Bearbeitung hinaus («Zero Data Retention») und verwenden sie nicht zum Trainieren von KI-Modellen. Der Chatverlauf wird nicht gespeichert. Nur ein Plan, den der Trainer speichert, wird wie jeder andere Trainingsplan in Supabase abgelegt. Für die Kostenkontrolle speichern wir pro Anfrage nur technische Angaben (Zeitpunkt, Trainer, Modell, Umfang, Kosten), ohne Inhalte und ohne Bezug zum Klienten.
- **Bekanntgabe ins Ausland:** Für die USA besteht für OpenRouter kein vom Bundesrat anerkannter angemessener Datenschutz. Die Bekanntgabe stützt sich auf Ihre ausdrückliche Einwilligung (Art. 17 Abs. 1 lit. a DSG) sowie auf die Standardvertragsklauseln im Datenbearbeitungsvertrag von OpenRouter, die für die Schweiz angepasst sind. Die Niederlande verfügen als EU-Staat über einen angemessenen Datenschutz.

## 5. Datensicherheit
Wir treffen technische und organisatorische Sicherheitsmassnahmen nach dem Stand der Technik, um Ihre Daten gegen unbeabsichtigte oder unrechtmässige Veränderung, Verlust, Zerstörung oder unbefugten Zugriff Dritter zu schützen.

## 6. Ihre Rechte
Sie haben das Recht:
* Auskunft über die von uns bearbeiteten Personendaten zu erhalten.
* Die Berichtigung unvollständiger oder unrichtiger Daten zu verlangen.
* Die Löschung Ihrer bei uns gespeicherten Personendaten zu verlangen, sofern keine gesetzlichen Aufbewahrungspflichten entgegenstehen. Wenn Ihr Profil in der App gelöscht wird, werden Ihre Personendaten anschliessend sicher aus der Datenbank entfernt.
* Eine erteilte Einwilligung jederzeit mit Wirkung für die Zukunft zu widerrufen.
* Beim Eidgenössischen Datenschutz- und Öffentlichkeitsbeauftragten (EDÖB) Beschwerde einzureichen.

## 7. Kontakt
Wenn Sie Fragen zur Bearbeitung Ihrer Personendaten haben oder Ihre Rechte geltend machen möchten, können Sie uns jederzeit kontaktieren: per E-Mail an info@corposana.ch oder per Post an die Adresse unter Ziffer 1.

---

© CorpoSana Gesundheitscenter AG, alle Rechte vorbehalten.
