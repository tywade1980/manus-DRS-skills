# Manus DRS Skills — Wade Ecosystem

The **complete, unified skill library** for the Wade Ecosystem. Every skill in this repository is a modular capability that plugs into the Centauri Interlock architecture, reads state from `caroline_neuro_memory.json`, and broadcasts results back to the Command Router.

## Quick Install (All Skills)

To install every skill in a new Manus session, run this single command:

```bash
python3 /home/ubuntu/skills/skill-share/scripts/receive_skill.py tywade1980/manus-DRS-skills --force
```

> **Note:** If `skill-share` is not yet installed, bootstrap with:
> ```bash
> git clone https://github.com/tywade1980/manus-DRS-skills.git /tmp/drs && \
>   python3 /tmp/drs/skills/skill-share/scripts/receive_skill.py tywade1980/manus-DRS-skills --force
> ```

## Available Skills (18 Total)

| Skill | Category | Description |
|---|---|---|
| `skill-share` | Infrastructure | Publish and receive skills via GitHub |
| `skill-creator` | Infrastructure | Guide for creating and updating skills |
| `wade-ecosystem` | Context | Persistent context about Wade, his business, and projects |
| `caroline-ai` | AI Core | Interface for Caroline AI (voice, RunPod, ElevenLabs) |
| `neurorank` | AI Core | NeuroRank™ emotionally intelligent cognitive decision engine |
| `centauri-interlock` | Architecture | Mandatory Centauri OS modular architecture standard |
| `centauri-connectors` | Architecture | Modular connectors for RunPod, OpenHands, Aider |
| `centauri-os` | Platform | Centauri OS design and development (custom Android + Caroline AI) |
| `runpod-connector` | Infrastructure | GPU pod management via RunPod API |
| `wade-telephony` | Business | AI receptionist and smart in-call service |
| `wade-custom-carpentry` | Business | Design-build remodel project management |
| `construct-ai` | Business | Master construction business intelligence |
| `rsmeans-cost-estimator` | Business | Industry-standard construction cost estimation |
| `excel-generator` | Productivity | Professional Excel spreadsheet creation |
| `gws-best-practices` | Productivity | Google Workspace best practices (Drive, Docs, Sheets, Slides) |
| `internet-skill-finder` | Productivity | Search and recommend skills from GitHub |
| `github-gem-seeker` | Productivity | Find battle-tested open-source solutions on GitHub |
| `bgm-prompter` | Creative | Background music prompt crafting for AI music generation |

## Install a Specific Skill

```bash
python3 /home/ubuntu/skills/skill-share/scripts/receive_skill.py tywade1980/manus-DRS-skills --skill caroline-ai
```

## List All Available Skills

```bash
python3 /home/ubuntu/skills/skill-share/scripts/receive_skill.py tywade1980/manus-DRS-skills --list
```

## Publish an Updated Skill

```bash
python3 /home/ubuntu/skills/skill-share/scripts/publish_skill.py <skill_name> tywade1980/manus-DRS-skills --tag v2.0.0
```

## Architecture — Centauri Interlock Standard

All skills follow the mandatory Centauri Interlock Standard:

1. **No Silos** — Every skill is a plug-and-play module, not a standalone script.
2. **State-Aware** — Modules read context from `caroline_neuro_memory.json` before executing.
3. **Closed-Loop** — Modules broadcast results back to the central Command Router.
4. **Voice-First** — All user-facing outputs support voice delivery via Caroline AI.

---

*Wade Ecosystem — Mini Me Technologies LLC | Centauri OS Project*
