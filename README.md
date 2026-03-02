# Manus DRS Skills — Wade Ecosystem

This repository contains all shared Manus skills for the Wade Ecosystem. These skills are automatically installed and updated across all Manus sessions, ensuring continuity and persistence of capabilities.

## Available Skills

| Skill | Description |
|---|---|
| `skill-share` | Infrastructure for publishing and receiving skills via GitHub |
| `caroline-ai` | Interface for the Caroline AI companion (voice, RunPod, ElevenLabs) |
| `neurorank` | NeuroRank™ emotionally intelligent cognitive decision engine |
| `wade-telephony` | AI receptionist and smart in-call service for Wade Custom Carpentry |
| `centauri-os` | Centauri OS design and development (custom Android + Caroline AI) |
| `construct-ai` | Master construction business intelligence and project management |

## Installation

To install all skills in a new Manus session:

```bash
python3 /home/ubuntu/skills/skill-share/scripts/receive_skill.py tywade1980/manus-DRS-skills --force
```

To list available skills without installing:

```bash
python3 /home/ubuntu/skills/skill-share/scripts/receive_skill.py tywade1980/manus-DRS-skills --list
```

## Repository Structure

```
manus-DRS-skills/
├── README.md
└── skills/
    ├── skill-share/
    ├── caroline-ai/
    ├── neurorank/
    ├── wade-telephony/
    ├── centauri-os/
    └── construct-ai/
```

---
*Part of the Wade Ecosystem — Mini Me Technologies LLC*
