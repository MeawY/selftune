# Garmin and Supplement Workflow / Garmin とサプリのワークフロー

This workflow uses a daily Garmin screenshot, a short supplement log, and a subjective check-in as the default SelfTune input.

このワークフローでは、毎日の Garmin スクリーンショット、短いサプリ記録、主観的なチェックインを SelfTune の標準入力として使います。

## Why This Is Useful / なぜ役立つか

Garmin data can provide a consistent external record of sleep, heart rate, activity, stress, Body Battery, recovery, and movement. Supplement logs can add context about what changed in the day. Subjective notes add the part wearable data cannot know: how the day actually felt.

Garmin のデータは、睡眠、心拍、活動量、ストレス、Body Battery、回復、運動などを継続的に見せてくれます。サプリ記録は、その日に何を入れたかという文脈を追加できます。主観メモは、ウェアラブルでは分からない「実際どう感じたか」を補います。

The goal is not to prove that one variable caused a change. The goal is to make daily review easier and help you notice patterns worth tracking.

目的は、ある要素が変化の原因だと証明することではありません。毎日の振り返りを楽にし、追跡する価値がありそうなパターンに気づきやすくすることです。

## Daily Inputs / 毎日の入力

Use these three inputs:

1. Garmin daily screenshot
2. Supplement log
3. Short subjective check-in

この3つを使います。

1. Garmin の毎日スクリーンショット
2. サプリ記録
3. 短い主観チェックイン

## 10-Minute Daily Flow / 10分の毎日フロー

1. Save or paste one Garmin daily screenshot.
2. Fill in `templates/garmin-daily-screenshot.md`.
3. Fill in `templates/supplement-log.md`.
4. Add a short note about mood, energy, digestion, stress, and anything unusual.
5. Use `prompts/garmin-supplement-review.md` for a non-medical AI review.

1. Garmin の毎日スクリーンショットを保存または貼り付ける。
2. `templates/garmin-daily-screenshot.md` を記入する。
3. `templates/supplement-log.md` を記入する。
4. 気分、エネルギー、消化、ストレス、いつもと違うことを短く書く。
5. `prompts/garmin-supplement-review.md` を使って、非医療的なAIレビューを行う。

## What To Track From Garmin / Garmin から見る項目

Track only what is useful. Do not try to capture everything.

必要なものだけを記録します。すべてを記録しようとしなくて大丈夫です。

- Sleep score and sleep duration
- Resting heart rate, if visible
- Heart rate range or notable spikes
- Body Battery, if visible
- Stress or recovery indicators
- Activity type, duration, and distance
- Steps or movement summary
- Notes about timing, such as late workouts or short sleep

- 睡眠スコアと睡眠時間
- 表示されていれば安静時心拍
- 心拍の範囲や目立つ上昇
- 表示されていれば Body Battery
- ストレスや回復の指標
- 運動の種類、時間、距離
- 歩数や活動量の概要
- 遅い時間の運動、短い睡眠などタイミングのメモ

## Supplement Tracking / サプリ記録

Track supplements as context, not as proof of effect.

サプリは効果の証明ではなく、文脈として記録します。

Useful fields:

- Name
- Amount, if known
- Time taken
- Reason for taking it
- With food or without food
- Any noticeable subjective changes
- Any discomfort or reason to pause and ask a professional

記録するとよい項目:

- 名前
- 分かれば量
- 飲んだ時間
- 飲んだ理由
- 食事あり・なし
- 主観的に気づいた変化
- 違和感や、専門家に相談したほうがよさそうな点

## Weekly Review / 週次レビュー

At the end of the week, combine daily Garmin notes and supplement logs. Ask AI to look for repeated patterns, missing context, and safer next observations.

週末に、日々の Garmin メモとサプリ記録をまとめます。AIには、繰り返し見えるパターン、足りない文脈、次に安全に観察できる点を整理してもらいます。

Avoid asking:

- "Which supplement fixed this?"
- "What condition do I have?"
- "What dose should I take?"

避ける問い:

- 「どのサプリがこれを治した？」
- 「私は何の病気？」
- 「どの量を飲めばいい？」

Prefer asking:

- "What patterns are worth tracking?"
- "What context is missing?"
- "What should I discuss with a qualified professional?"

おすすめの問い:

- 「追跡する価値がありそうなパターンは？」
- 「足りない文脈は？」
- 「専門家に相談するとよさそうな問いは？」
