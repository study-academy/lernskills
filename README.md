# Lernskills — Öffentliche Skill-Sammlung

Eine öffentliche Sammlung von Lernskills für AI-Assistenten wie Claude, entwickelt von [Studyacademy](https://studyacademy.de).

Lernskills sind strukturierte Anleitungen die einem AI-Assistenten genau sagen, wie er einen Studenten durch eine bestimmte Lernmethode führen soll — Schritt für Schritt, sokratisch, ohne Inhalte vorwegzunehmen.

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

---

## Wie benutze ich einen Skill?

Du kannst die Skills direkt in deinen AI-Assistenten einbinden — zum Beispiel in Claude Code, Cursor oder einen eigenen GPT.

**In Claude Code:**

Kopiere den Inhalt der `SKILL.md` in eine Datei in deinem Projektverzeichnis und referenziere sie in deiner `CLAUDE.md`.

**Als System-Prompt:**

Kopiere den Inhalt der `SKILL.md` direkt als System-Prompt in deinen GPT oder API-Call.

---

## Mitmachen

Hast du einen eigenen Lernskill entwickelt der anderen helfen könnte? Schick ihn uns — wir prüfen ihn und fügen ihn zur Sammlung hinzu.

Details: [CONTRIBUTING.md](CONTRIBUTING.md)
