# SelfTune

SelfTune is an open-source toolkit for AI-assisted self-health reflection, daily observation, and lifestyle review.

SelfTune は、AIを活用した自己観察、日々の記録、生活習慣レビューのためのオープンソース・テンプレート集です。

This project is not a medical device, diagnostic system, or treatment protocol. It is designed to support structured reflection, better record keeping, and practical conversations between individuals and qualified professionals when appropriate.

このプロジェクトは、医療機器、診断システム、治療プロトコルではありません。自己観察、記録、内省、必要に応じた専門家との対話を支援するための実用的なツールキットです。

## Purpose / 目的

SelfTune helps people organize signals from daily life, including sleep, meals, mood, energy, stress, routines, body sensations, and environmental context.

The aim is to make self-observation easier, more consistent, and more useful without turning personal experience into a diagnosis.

SelfTune は、睡眠、食事、気分、エネルギー、ストレス、習慣、身体感覚、環境要因などを整理し、自分の状態を継続的に観察しやすくすることを目的としています。

## Who It Is For / 対象者

- Individuals who want a practical self-observation system
- Therapists, coaches, and wellness practitioners who support reflective lifestyle work
- Researchers, educators, and builders interested in non-medical AI journaling workflows
- Obsidian or Markdown users who want reusable templates for personal review

- 自主的に体調や生活習慣を観察したい個人
- 内省や生活改善を支援するセラピスト、コーチ、ウェルネス実践者
- 非医療領域のAIジャーナリングに関心のある研究者、教育者、開発者
- Obsidian や Markdown で記録テンプレートを使いたい人

## What SelfTune Can Do / できること

- Provide daily check-in templates
- Help organize nutrition, sleep, stress, mood, and nervous-system observations
- Offer prompt templates for AI-assisted review
- Support weekly or monthly reflection
- Create a shared language for discussing patterns with a professional
- Keep personal records structured and reusable

- 毎日のチェックイン用テンプレートを提供する
- 栄養、睡眠、ストレス、気分、神経系の状態に関する観察を整理する
- AIにレビューを依頼するためのプロンプトを提供する
- 週次・月次の振り返りを支援する
- 専門家と状態を共有するときの共通言語を作る
- 個人の記録を再利用しやすい形で残す

## What SelfTune Does Not Do / しないこと

- It does not diagnose illness.
- It does not replace medical, psychological, nutritional, or emergency care.
- It does not promise specific health outcomes.
- It does not instruct users to start, stop, or change medication or treatment.
- It does not interpret symptoms as proof of a condition.

- 病気の診断はしません。
- 医療、心理支援、栄養指導、緊急対応の代替にはなりません。
- 特定の健康効果を保証しません。
- 薬や治療の開始・中止・変更を指示しません。
- 症状を特定疾患の証拠として扱いません。

## Project Structure / 構成

```text
selftune/
  README.md
  AGENTS.md
  LICENSE
  CONTRIBUTING.md
  docs/
    three-layer-model.md
    disclaimer.md
    privacy.md
  prompts/
    nutrition-review.md
    nervous-system-review.md
    weekly-pattern-review.md
  templates/
    daily-checkin.md
    weekly-review.md
    monthly-review.md
    practitioner-intake.md
    obsidian-daily-note.md
  examples/
    sample-case.md
```

## How To Use / 使い方

1. Copy a template from `templates/`.
2. Fill it in with your own observations.
3. Use a prompt from `prompts/` to ask an AI assistant for a structured, non-medical review.
4. Look for patterns, questions, and next small experiments.
5. Bring relevant notes to a qualified professional when needed.

1. `templates/` からテンプレートを選びます。
2. 自分の観察内容を記入します。
3. `prompts/` のプロンプトを使い、AIに非医療的な整理を依頼します。
4. パターン、問い、小さな生活実験の候補を確認します。
5. 必要に応じて、専門家との相談材料として活用します。

## Safety Principles / 安全原則

- Use cautious language.
- Treat records as subjective observations, not clinical evidence.
- Encourage professional support for persistent, severe, or worrying symptoms.
- Avoid advice that implies diagnosis, treatment, or medication changes.
- Prefer small, reversible lifestyle experiments.

- 断定を避けた表現を使う。
- 記録は臨床的証拠ではなく、主観的な観察として扱う。
- 強い症状、長引く不調、不安がある場合は専門家への相談を促す。
- 診断、治療、服薬変更を示唆する助言を避ける。
- 小さく、元に戻せる生活上の試行を優先する。

## Roadmap / ロードマップ

- Add bilingual core documentation
- Expand Obsidian-specific templates
- Add Obsidian vault examples
- Add sample workflows for AI-assisted reflection
- Add release checklist and versioning guidance

- 日英併記の基本ドキュメントを追加
- 日次、週次、月次テンプレートを拡充
- 実践者向けのヒアリングテンプレートを追加
- Obsidian Vault のサンプルを追加
- AIを使った振り返りワークフローを追加
- コントリビューションガイドラインを追加
- プライバシーとデータ取り扱い方針を追加

## License / ライセンス

SelfTune is released under the MIT License. See `LICENSE`.

SelfTune は MIT License で公開されています。`LICENSE` を参照してください。

## Disclaimer / 免責

SelfTune is for self-observation, journaling, and reflection. It is not medical advice. See `docs/disclaimer.md` and `docs/privacy.md` before sharing personal records or using AI tools with sensitive notes.

SelfTune は自己観察、記録、内省のためのものです。医療助言ではありません。個人記録の共有やAIツールでの利用前に、`docs/disclaimer.md` と `docs/privacy.md` を確認してください。
