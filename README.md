# IoT

Kurs-Repository für die Lehrveranstaltung
IoT bei Jörn Schlingensiepen.
Alle Kurse im Überblick: [lehre](https://github.com/schlingensiepen/lehre)

## So bleiben Sie auf dem Laufenden

Diese Seite wird im Semester laufend ergänzt.
Neuigkeiten kommen als Ankündigung. Damit Sie sie
mitbekommen:

1. Melden Sie sich bei GitHub an (ein kostenloses
   Konto genügt).
2. Klicken Sie oben rechts auf **Watch** → **Custom**.
3. Haken Sie **Discussions** und **Releases** an →
   **Apply**.

Benachrichtigungen kommen dann per E-Mail oder in der
GitHub-App.

Ohne GitHub-Konto können Sie die Ankündigungen per
Feed verfolgen — tragen Sie diese Adresse in einen
Feed-Reader ein:
`https://github.com/schlingensiepen/kurs-iot/discussions.atom`
Änderungen an dieser Seite selbst:
`https://github.com/schlingensiepen/kurs-iot/commits/main.atom`

[Alle Ankündigungen](https://github.com/schlingensiepen/kurs-iot/discussions/categories/announcements)

Fragen zum Kurs stellen Sie unter
[Discussions → Q&A](https://github.com/schlingensiepen/kurs-iot/discussions/categories/q-a).

## Hinweis: Google Gemini für Studierende

Google bietet Studierenden und Auszubildenden ab 18
das Plus-Abo von Gemini **1 Jahr lang kostenlos** an:
[gemini.google/students](https://gemini.google/students/)

Bitte beachten Sie: Das Angebot gilt nur bis
**31.12.2026**. Bei der Anmeldung ist ein
Zahlungsmittel nötig. Ohne Kündigung verlängert sich
das Abo später automatisch kostenpflichtig (laut
Angebotsseite 21,99 €/Monat, monatlich kündbar). Die
genauen Bedingungen stehen auf der Angebotsseite.

## Arbeitsumgebung

- [clawbook-lehre](https://github.com/schlingensiepen/clawbook-lehre) —
  fertig eingerichteter Arbeitsrechner für die Arbeit
  mit KI-Agenten. Dort steht, wie Sie ihn starten.
- [tmux-helper](https://github.com/schlingensiepen/tmux-helper) —
  tmux-Sitzungen bequem aus dem Windows Terminal
  verwalten (englischsprachig).

### Lokale Umgebung für die Umsetzung

clawbook-lehre nutzen Sie vor allem für die
systematische Produktentwicklung. Programmiert und
geflasht wird in einer zweiten, lokalen Umgebung: Das
ESP32-Board hängt per USB an Ihrem Rechner, deshalb
muss diese Umgebung nativ installiert sein.

1. **VS Code als portable Version** einrichten
   ([Anleitung](https://code.visualstudio.com/docs/setup/portable);
   ZIP- bzw. tar.gz-Download, nicht der Installer).
   So bleibt sie getrennt von clawbook-lehre und von
   einem lokal installierten VS Code, und Sie können
   sie mitnehmen – etwa auf einen Rechner im
   i2cm-Labor.
2. **PlatformIO IDE** in der portablen Version
   installieren
   ([Anleitung](https://docs.platformio.org/en/latest/integration/ide/vscode.html)).
3. **GitHub Copilot** in der portablen Version
   einrichten
   ([Anleitung](https://code.visualstudio.com/docs/copilot/setup)) –
   mit dem GitHub-Konto, für das Sie die
   Studierendenversion beantragt haben.
4. **USB-Treiber CH340:** unter Windows und macOS vom
   Hersteller WCH
   ([Windows](https://www.wch-ic.com/downloads/CH341SER_EXE.html),
   [macOS](https://www.wch-ic.com/downloads/CH34XSER_MAC_ZIP.html));
   unter Linux ist der Treiber dabei, nötig sind die
   [udev-Regeln von PlatformIO](https://docs.platformio.org/en/latest/core/installation/udev-rules.html).

Alle Anleitungen sind englischsprachig. PlatformIO
lädt seine Werkzeuge auf jedem Rechner beim ersten
Projekt herunter; das dauert beim ersten Mal länger.

Wie Sie Ihre Arbeit zwischen clawbook-lehre und der
lokalen Umgebung austauschen, erklärt ein eigenes
Tutorial, das noch folgt.

## Wintersemester 2026/27

_Inhalte folgen wöchentlich._

## Verwendete Repositories

_Die Liste wächst im Lauf des Semesters._

---

Inhalte unter [CC BY 4.0](LICENSE), Jörn Schlingensiepen.
