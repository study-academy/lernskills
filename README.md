# Lernskills — Öffentliche Skill-Sammlung

Eine öffentliche Sammlung von Lernskills, entwickelt von [Studyacademy](https://study-academy.de/lernsystem-aff).

Lernskills sind strukturierte Anleitungen die deinem AI-Assistenten genau sagen, wie er dich durch einen bestimmten Lernworkflow führen soll — Schritt für Schritt, ohne Inhalte vorwegzunehmen oder dich in die Irre zu führen.

---

## Was sind Lernskills?

Ein Lernskill ist eine Markdown-Datei (`SKILL.md`) die einem AI-Assistenten beibringt:
- **Wann** er aktiv wird (Trigger)
- **Wie** er den Studenten durch eine Methode führt (Workflow)
- **Was** er nie tun darf (Grenzen)

Der Assistent moderiert — der Student denkt. Das ist das Prinzip.

---

## Verfügbare Skills

| Skill | Was er macht |
|---|---|
| [Priming](priming/SKILL.md) | Baut vor der Informationsaufnahme ein kognitives Grundgerüst — aktiviert Vorwissen, erzeugt Neugier, schafft mentale Anker |
| [Feynman](feynman/SKILL.md) | Testet Verständnis durch Erklären — deckt Wissenslücken auf, vertieft durch Vertiefungsfragen und Analogien |

---

## Wie benutze ich einen Skill?

Du kannst die Skills direkt in deinen AI-Assistenten einbinden — zum Beispiel in Claude Code, Cursor oder einen eigenen GPT.

**In Claude Code:**

Kopiere den Inhalt der `SKILL.md` in eine Datei in deinem Projektverzeichnis und referenziere sie in deiner `CLAUDE.md`.

**Als System-Prompt:**

Kopiere den Inhalt der `SKILL.md` direkt als System-Prompt in deinen GPT oder API-Call.

---

## Das komplette System: Studymut

Diese Skills hier sind der öffentliche Ausschnitt. Das vollständige System heißt **Studymut** — ein AI-Lernbegleiter der komplett in Claude integriert ist und Studierende durch jede Phase des Lernprozesses führt.

Was Studymut zusätzlich kann:
- **Spaced Repetition** — berechnet automatisch wann welches Thema wiederholt werden muss und führt die Intervalle mit
- **Learner Profile** — merkt sich über Sessions hinweg Stärken, Schwächen, Prüfungsformate und SR-Status
- **Vollständiges 4-Phasen-System** — Priming, Informationsaufnahme, Encoding-Begleitung und Retrieval als aufeinander aufbauender Zyklus
- **Prüfungssimulation** — Mündlich, schriftlich, MC und OSCE-Format mit strukturiertem Feedback
- **Session-Logs** — jede Lernsession wird automatisch dokumentiert damit der nächste Chat nahtlos weitermacht
- **Lernproblem-Analyse** — wenn das Lernen nicht funktioniert, analysiert Studymut die Ursache und entwickelt mit dem Studenten konkrete Änderungen

Studymut ist Teil des **Lernsystem Neuro** der Studyacademy.

**[Zum Lernsystem Neuro](https://study-academy.de/lernsystem-aff)**

---

## Mitmachen

Hast du einen eigenen Lernskill entwickelt der anderen helfen könnte? Schick ihn uns — wir prüfen ihn und fügen ihn zur Sammlung hinzu.

Details: [CONTRIBUTING.md](CONTRIBUTING.md)
