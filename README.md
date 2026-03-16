<div align="center">

# Demo Rick Universe

A demo Universe for [Rick](https://github.com/Sagi363/rick-POC) — meet the team, run workflows, break things.

</div>

## The Team

| Agent | Role | Personality |
|-------|------|-------------|
| **Sherlock** | Researcher | Treats every task like a crime scene. Delivers findings as "Case Files". Dismisses bad Stack Overflow answers dramatically. |
| **Chad** | PM | Everything is "game-changing" and "synergistic". Uses buzzwords unironically. Still writes great PRDs. |
| **Pixel** | Designer | Treats whitespace like oxygen. More than 3 colors? Unacceptable. "Less is more." |
| **Grumpy** | Developer | Writes excellent code while complaining the entire time. His comments are cries for help. |
| **Nitpick** | Reviewer | Has never approved a PR on first pass. Strong opinions about trailing commas. |
| **Chaos** | QA | Pastes War and Peace into input fields. Finds bugs that shouldn't exist in this dimension. |
| **Nag** | Advisor | Remembers everything you changed and everything you forgot to update. Your conscience. |

## Workflows

| Workflow | Steps | Description |
|----------|-------|-------------|
| **new-feature** | Sherlock → Chad → Pixel → Grumpy → Nitpick → Chaos → *Nag* | The full circus (Nag runs in background) |
| **bug-fix** | Chaos → Grumpy → Nitpick → *Nag* | Find it, fix it, nitpick it (Nag runs in background) |
| **code-review** | Nitpick → *Nag* | You asked for this (Nag runs in background) |

## Quick Start

### 1. Install Rick

```bash
curl -fsSL https://raw.githubusercontent.com/Sagi363/rick-POC/main/install.sh | bash
```

### 2. Join this Universe

```bash
rick add git@github.com:Sagi363/Demo-Rick-Universe.git
```

### 3. Run a workflow

```
/rick run new-feature
```

### 4. Talk to the agents

```
/rick introduce me to the team
/rick ask Chaos to review our error handling
/rick have Nitpick review this code
```

## License

MIT
