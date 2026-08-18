# AI医疗KOL内容策划 Skill

A portable Agent Skill for AI medical and healthcare KOL content strategy.

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

## Compatibility

This repository uses the standard Agent Skill shape:

- `SKILL.md` with YAML frontmatter
- supporting `references/` files
- reusable `templates/` files

It can be installed in tools that support Agent Skills or `SKILL.md`-based skill folders. The `agents/openai.yaml` file is optional OpenAI/Codex interface metadata; other tools can ignore it.

For tools that do not have a native skill system, including Workbubby-style domestic AI workspaces, you can still use this repository as a prompt/reference pack by attaching or importing `SKILL.md` plus the relevant files in `references/` and `templates/`.

## Universal Install

Install to the cross-runtime skills directory:

```bash
git clone https://github.com/tiana9888/ai-medical-kol-content-strategy.git
mkdir -p ~/.agents/skills
cp -R ai-medical-kol-content-strategy ~/.agents/skills/
```

Or use the install script:

```bash
git clone https://github.com/tiana9888/ai-medical-kol-content-strategy.git
cd ai-medical-kol-content-strategy
./install.sh
```

## App-Specific Install Paths

Use one of these paths if your AI tool requires an app-specific skills directory:

| Tool | Install path |
| --- | --- |
| Cross-runtime default | `~/.agents/skills/ai-medical-kol-content-strategy` |
| Codex | `~/.codex/skills/ai-medical-kol-content-strategy` |
| Claude Code | `~/.claude/skills/ai-medical-kol-content-strategy` |
| Copilot CLI / compatible agents | `~/.agents/skills/ai-medical-kol-content-strategy` |
| Gemini CLI / compatible agents | `~/.agents/skills/ai-medical-kol-content-strategy` |
| Workbubby / domestic AI workspaces | Use the tool's custom skill, knowledge base, or prompt-library import flow |

Manual Codex install example:

```bash
mkdir -p ~/.codex/skills
cp -R ai-medical-kol-content-strategy ~/.codex/skills/
```

## Invoke

```text
Use $ai-medical-kol-content-strategy to plan an AI medical KOL content strategy.
```

Chinese prompt example:

```text
用 $ai-medical-kol-content-strategy 帮我为一个 AI 医疗产品做视频号 KOL 内容策划。
```

If your tool does not support `$skill-name` invocation, import or paste `SKILL.md` as the main instruction, then add `references/` and `templates/` as supporting knowledge files.

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
