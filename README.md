# @gonzih/skills-pharmacy

Pharmacy skills for Claude Code — a collection of clinical pharmacy workflow tools.

## Skills

### `drug-interaction-brief`
Summarizes drug-drug interaction risks in plain language for a given medication list. Ranks interactions by severity (Major / Moderate / Minor) with mechanism, clinical consequence, and management recommendations.

### `patient-counseling-note`
Writes structured patient medication counseling notes suitable for pharmacy or clinical documentation. Covers indication, directions, expected effects, warnings, interactions, storage, and red-flag symptoms.

### `prior-auth-narrative`
Drafts prior authorization narratives for insurance submission. Structures clinical rationale, step therapy documentation, and supporting evidence to support PA approval.

### `formulary-summary`
Summarizes formulary coverage for a patient's medication list. Provides tier status, coverage restrictions, cost categories, and therapeutic alternatives for non-preferred agents.

## Installation

```bash
npx clawdhub@latest install @gonzih/skills-pharmacy
```

Or manually copy the `skills/` directory to your Claude Code skills location:

- **Global:** `~/.claude/skills/`
- **Project:** `.claude/skills/`

## Usage

In Claude Code, invoke any skill by name:

```
/drug-interaction-brief
/patient-counseling-note
/prior-auth-narrative
/formulary-summary
```

## Disclaimer

These skills are clinical decision-support tools intended to assist trained healthcare professionals. They do not replace professional clinical judgment, and all outputs should be verified against authoritative references and current clinical guidelines before use in patient care.

## License

MIT
