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

Diese Skills hier sind ein öffentlicher Ausschnitt. Das vollständige System heißt **Studymut** — ein vollständiger AI Agent (ähnlich wie Openclaw) der komplett in dein Claude oder bestehendes Agent-Setup integriert ist und dich durch jede Phase des Lernprozesses führt.

Studymut ist kein Chatbot der Fragen beantwortet. Er ist ein eigenständiger Agent mit Gedächtnis, Lernlogik und einem klaren Auftrag: dass du prüfungsbereit bist — nicht dass du das Gefühl hast, gelernt zu haben.

**Was Studymut für dich tut:**

- **Kein Neustart jede Session** — Studymut erinnert sich an deine Themen, deinen Fortschritt, deine Schwächen und wo du aufgehört hast. Jeder Chat setzt nahtlos fort.
- **Automatisches Spaced Repetition** — Studymut berechnet wann welches Thema wiederholt werden muss und erinnert dich aktiv daran. Kein manuelles Planen, kein Vergessen.
- **Prüfungssimulation auf Prüfungsniveau** — Mündlich, schriftlich, MC, OSCE. Studymut übernimmt die Prüferrolle, stellt Folgefragen, bewertet strukturiert und sagt dir direkt was fehlt.
- **Lernproblem-Diagnose** — Wenn das Lernen nicht funktioniert, analysiert Studymut die Ursache und erarbeitet mit dir konkrete Änderungen. Nicht motivieren — verstehen warum es hakt.
- **Vollständiges 4-Phasen-System** — Priming, Informationsaufnahme, Encoding-Begleitung und Retrieval als aufeinander aufbauender Zyklus, abgestimmt auf dein Fach und deine Prüfungsformate.
- **Professionelles Feedback ohne Floskeln** — Studymut sagt dir was falsch ist, warum es falsch ist, und was du konkret ändern musst. Kein Mitleid, keine Aufmunterungen, kein Herumreden.

Studymut ist Teil des **Lernsystem Neuro** der Studyacademy.

**[Zum Lernsystem Neuro](https://study-academy.de/lernsystem-aff)**

---

## Mitmachen

Hast du einen eigenen Lernskill entwickelt der anderen helfen könnte? Schick ihn uns — wir prüfen ihn und fügen ihn zur Sammlung hinzu.

Details: [CONTRIBUTING.md](CONTRIBUTING.md)
