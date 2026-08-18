# AI医疗KOL内容策划 Skill

A Codex skill for AI medical and healthcare KOL content strategy.

It supports:

- benchmark research
- KOL account analysis
- creator brief writing
- title and script ideation
- draft review
- cover recommendations
- multi-KOL differentiation
- AI medical and health communication compliance checks
- brand-context collection

## Install

Copy this folder into your Codex skills directory:

```bash
mkdir -p ~/.codex/skills
cp -R ai-medical-kol-content-strategy ~/.codex/skills/
```

Then invoke it in Codex:

```text
Use $ai-medical-kol-content-strategy to plan an AI medical KOL content strategy.
```

Chinese prompt example:

```text
用 $ai-medical-kol-content-strategy 帮我为一个 AI 医疗产品做视频号 KOL 内容策划。
```

## Structure

```text
ai-medical-kol-content-strategy/
├── SKILL.md
├── agents/
│   └── openai.yaml
├── references/
│   ├── benchmark.md
│   ├── brand-context-template.md
│   ├── cover-guidelines.md
│   ├── medical-compliance.md
│   └── review-checklist.md
└── templates/
    ├── brief-template.md
    ├── kol-profile.md
    └── review-scorecard.md
```

## Note

The compliance guidance is a planning aid, not legal, regulatory, or medical advice. Regulated campaigns should still be reviewed by qualified brand, legal, medical, or compliance reviewers.
