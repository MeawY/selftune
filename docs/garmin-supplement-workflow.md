# Garmin and Supplement Workflow

This workflow uses a daily Garmin screenshot, a short supplement log, and a subjective check-in as the default SelfTune input.

Garmin data can provide a consistent external record of sleep, heart rate, activity, stress, Body Battery, recovery, and movement. Supplement logs add context about what changed in the day. Subjective notes add the part wearable data cannot know: how the day actually felt.

The goal is not to prove that one variable caused a change. The goal is to make daily review easier and help you notice patterns worth tracking.

For a deeper framework on interpreting Garmin metrics as nervous-system context, see `docs/garmin-nervous-system-integration.md`.

## Daily Inputs

Use these three inputs:

1. Garmin daily screenshot or wearable summary
2. Supplement log
3. Short subjective check-in

## 10-Minute Daily Flow

1. Save or paste one Garmin daily screenshot.
2. Fill in `templates/garmin-daily-screenshot.md`.
3. Fill in `templates/supplement-log.md`.
4. Add a short note about mood, energy, digestion, stress, and anything unusual.
5. Add a nervous-system note if activation, shutdown, steadiness, or recovery feels relevant.
6. Use `prompts/garmin-supplement-review.md` for a non-medical AI review.

## What To Track From Garmin

Track only what is useful. Do not try to capture everything.

- Sleep score and sleep duration
- HRV or HRV status, if available
- Resting heart rate, if visible
- Heart rate range or notable spikes
- Body Battery, if visible
- Stress or recovery indicators
- Activity type, duration, and distance
- Steps or movement summary
- Notes about timing, such as late workouts, short sleep, caffeine, or delayed meals

## Supplement Tracking

Track supplements as context, not as proof of effect.

Useful fields:

- Name
- Amount, if known
- Time taken
- Reason for taking it
- With food or without food
- Any noticeable subjective changes
- Any discomfort or reason to pause and ask a professional

## Weekly Review

At the end of the week, combine daily Garmin notes, supplement logs, subjective notes, and nervous-system check-ins.

Avoid asking:

- "Which supplement fixed this?"
- "What condition do I have?"
- "What dose should I take?"

Prefer asking:

- "What patterns are worth tracking?"
- "What context is missing?"
- "What supports helped steadiness or recovery?"
- "Am I treating wearable data as a helpful signal rather than a grade?"
- "What should I discuss with a qualified professional?"
