# Social Coach Template

Privacy-first prompt pack for AI-assisted social, work, and relationship coaching.

This repository is designed to be public and forkable. It contains generic playbooks,
scripts, templates, and reusable prompt skills. It should not contain your private
history, private relationships, real names, employer details, medical details, or live
conflicts.

This is not therapy, legal advice, medical advice, or emergency support. It is a decision
support system for moments where emotion, ambiguity, conflict, or social friction makes
the next move expensive to compute.

## What This Is For

- Regulate before replying.
- Convert emotional charge into scripts, boundaries, repairs, or decisions.
- Separate facts, interpretations, threat-stories, and recommended action.
- Reduce repetitive social deliberation.
- Preserve relationships without over-explaining.
- Protect credibility in work contexts.
- Keep personal context private while maintaining reusable public tools.

## Privacy Model

Public, tracked files:

- Generic playbooks such as `CODEX.md`, `STATE_CHECK.md`, and `SCRIPT_BANK.md`.
- Fill-in templates under `templates/`.
- Reusable prompt skills under `skills/`.

Private, ignored files:

- Personal context copied into `private/`.
- Relationship maps with real names.
- Sensitive background, health details, trauma history, or live conflict notes.
- Scenario folders containing real people, workplaces, screenshots, quotes, or dates.

Before publishing, run through `PRIVACY_CHECKLIST.md`.

## Quick Start

1. Fork or copy this repository.
2. Keep the public playbooks generic.
3. Copy the templates you need into `private/` and fill them in locally.
4. Ask your AI assistant to load `AGENTS.md` first.
5. For personal sessions, explicitly load relevant files from `private/`.

Suggested private files:

- `private/STABLE_CONTEXT.md` from `templates/STABLE_CONTEXT.template.md`.
- `private/RELATIONSHIP_MAP.md` from `templates/RELATIONSHIP_MAP.template.md`.
- `private/CURRENT_STRESSORS.md` from `templates/CURRENT_STRESSORS.template.md`.
- `private/SENSITIVE_BACKGROUND.md` from `templates/SENSITIVE_BACKGROUND.template.md`.

## Load Order For AI Agents

Start with `AGENTS.md` for coaching style.

For a general social decision, load:

- `CODEX.md`
- `SCRIPT_BANK.md`
- `private/STABLE_CONTEXT.md`, if present
- `private/RELATIONSHIP_MAP.md`, if relevant

For a heated work reply or active conflict, load:

- `STATE_CHECK.md`
- `REGULATION_PLAYBOOK.md`
- `WORK_OPERATING_MANUAL.md`
- `SCRIPT_BANK.md`
- Any relevant private scenario notes

For sensitive background, load only when it changes the next move:

- `private/SENSITIVE_BACKGROUND.md`
- `TRIGGER_MAP.md`

For post-incident learning, load:

- `AFTER_ACTION_REVIEW_TEMPLATE.md`
- `TRIGGER_MAP.md`
- Relevant private scenario notes

## Core Files

- `AGENTS.md`: instructions for how an AI should coach from this repo.
- `CODEX.md`: social triage system, invite rules, counter-offers, and trapped-event protocol.
- `STATE_CHECK.md`: fast pre-reply state check for activated moments.
- `REGULATION_PLAYBOOK.md`: green/yellow/red regulation ladder.
- `TRIGGER_MAP.md`: generic map for recurring activation patterns.
- `SCRIPT_BANK.md`: reusable social, work, boundary, repair, and delay scripts.
- `WORK_OPERATING_MANUAL.md`: generic work-conflict operating rules.
- `AFTER_ACTION_REVIEW_TEMPLATE.md`: structured post-incident debrief.
- `PRIVACY_CHECKLIST.md`: publication safety checklist.

## Skill Prompts

`skills/` contains reusable task modes for AI sessions. They are prompt specs, not
automatically installed agent skills.

- `skills/social-coach.md`: social decisions and scripts.
- `skills/deescalator.md`: heated message cleanup.
- `skills/conflict-debrief.md`: structured debrief after a charged event.
- `skills/boundary-script.md`: clean no, redirect, or enforceable boundary.
- `skills/evidence-log.md`: neutral evidence entries.
- `skills/repair.md`: short repairs that preserve the underlying point.

## Operating Principles

- Regulate first, optimize second.
- Protect tomorrow's credibility over today's satisfying reply.
- Do not litigate identity when the fix is process.
- Person and format are different ratings.
- Ambiguous requests need written expected behavior, owner, deadline, and acceptance criteria.
- Anger is data, not a command.
- Scripts beat essays.
- Boundaries should be clear enough to enforce and short enough to send.
- Private context belongs in ignored files, not public commits.
