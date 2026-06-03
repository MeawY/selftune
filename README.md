# SelfTune

AI-assisted Self Health Design

SelfTune is an open-source toolkit for AI-assisted self-observation, wearable-data reflection, supplement tracking, nervous-system awareness, and lifestyle design.

This project is not a medical device, diagnostic system, treatment protocol, supplement protocol, or emergency-support tool. It is designed to help people organize daily signals, keep better records, and prepare practical questions for qualified professionals when needed.

## Why SelfTune Exists

Most self-tracking systems split life into separate pieces: sleep in one app, workouts in another, supplements in a notebook, mood in memory, and stress somewhere vague in the background.

SelfTune brings those pieces into one daily reflection workflow.

The goal is not to prove causation or diagnose anything. The goal is to make personal patterns easier to notice, review, and discuss.

## Default Workflow

The default SelfTune workflow combines:

1. A daily Garmin screenshot or wearable summary
2. A supplement log
3. A short subjective check-in
4. Nervous-system state notes
5. A non-medical AI review prompt

Start here:

- `docs/garmin-supplement-workflow.md`
- `docs/nervous-system-literacy.md`
- `docs/nervous-system-workflow.md`
- `templates/garmin-daily-screenshot.md`
- `templates/supplement-log.md`
- `templates/nervous-system-checkin.md`
- `prompts/garmin-supplement-review.md`
- `prompts/nervous-system-review.md`

## Daily 10-Minute Flow

1. Add one Garmin screenshot or wearable summary.
2. Record supplements, caffeine, alcohol, medication context if you choose to note it, and major meals.
3. Add a short subjective note: energy, mood, digestion, stress, focus, and body sensations.
4. Add a nervous-system note: activation, shutdown, steadiness, recovery, triggers, and supports.
5. Ask an AI assistant for a structured, non-medical review.
6. Choose one small observation or reversible routine experiment for tomorrow.

## Who It Is For

- Individuals who want a practical self-observation system
- Therapists, coaches, and wellness practitioners who support reflective lifestyle work
- Obsidian and Markdown users who want reusable self-tracking templates
- Developers and researchers exploring non-medical AI journaling workflows

## What SelfTune Can Do

- Organize wearable data, supplement context, mood, stress, sleep, activity, and subjective notes
- Provide daily and weekly reflection templates
- Offer AI prompts that avoid medical claims and causal overreach
- Support nervous-system awareness without diagnosing trauma, anxiety, depression, or autonomic conditions
- Help users prepare better questions for qualified professionals
- Keep personal records structured, portable, and reusable

## What SelfTune Does Not Do

- It does not diagnose illness.
- It does not replace medical, psychological, nutritional, or emergency care.
- It does not evaluate supplement safety or prescribe dosage.
- It does not promise specific health outcomes.
- It does not instruct users to start, stop, combine, or change supplements, medication, or treatment.
- It does not interpret symptoms, wearable metrics, or subjective notes as proof of a condition.

## Project Structure

```text
selftune/
  README.md
  AGENTS.md
  LICENSE
  CONTRIBUTING.md
  CODE_OF_CONDUCT.md
  SECURITY.md
  docs/
    garmin-supplement-workflow.md
    nervous-system-literacy.md
    nervous-system-workflow.md
    three-layer-model.md
    disclaimer.md
    privacy.md
    release-checklist.md
  prompts/
    garmin-supplement-review.md
    nervous-system-review.md
    nutrition-review.md
    weekly-pattern-review.md
  templates/
    garmin-daily-screenshot.md
    supplement-log.md
    nervous-system-checkin.md
    daily-checkin.md
    weekly-review.md
    monthly-review.md
    practitioner-intake.md
    obsidian-daily-note.md
  examples/
    garmin-supplement-day.md
    nervous-system-day.md
    sample-case.md
```

## Language Policy

SelfTune is developed in English first so it can be useful to a global open-source audience.

Japanese notes may exist during early prototyping, but durable project documentation, templates, prompts, issues, and pull requests should be written in English. Translations can be added later as separate localized files.

## Safety Principles

- Use cautious language.
- Treat records as subjective observations, not clinical evidence.
- Treat wearable metrics and supplement logs as context, not proof.
- Encourage qualified professional support for severe, sudden, persistent, worsening, or concerning symptoms.
- Avoid advice that implies diagnosis, treatment, medication changes, or supplement protocols.
- Prefer small, reversible lifestyle observations over broad recommendations.

## Roadmap

- Convert all remaining bilingual prototype files to English-first documentation
- Add an Obsidian vault starter kit
- Add a seven-day Garmin and supplement example
- Add a seven-day nervous-system pattern example
- Add weekly and monthly AI review workflows
- Add issue-based contribution tasks for template improvement
- Add versioned releases for stable template sets

## License

SelfTune is released under the MIT License. See `LICENSE`.

## Disclaimer

SelfTune is for self-observation, journaling, and reflection. It is not medical advice. See `docs/disclaimer.md` and `docs/privacy.md` before sharing personal records or using AI tools with sensitive notes.

## Contributing

Contributions are welcome when they improve clarity, safety, privacy, or practical usefulness. Please read `CONTRIBUTING.md`, `CODE_OF_CONDUCT.md`, and `SECURITY.md` before opening issues or pull requests.
