# gtm-pov

A Claude Code skill that refuses to give you a generic GTM playbook.

When you ask "what's the GTM for X?" / "how should I price this?" / "figure out my ICP" — it refuses, restates the surface ask as a belief question, drills until you own the belief in your own words (not a Lenny phrase, not a YC essay), then forces you to ship a working artifact this week instead of a 90-day plan.

The premise: GTM used to be downstream of org structure, tools, and budgets — the playbook followed, the hiring plan followed. AI collapsed that. GTM is now a function of what you actually believe about your customer, and the winners ship in days, not quarters.

## What it does

- **Refuses on first move.** No generic playbooks. The surface question gets restated as a belief question.
- **Maps three branches** — Bets, Beliefs, Assumptions — because they are not the same thing and most GTM advice mashes them together.
- **Drills one branch at a time.** No praise, no verdicts, no aphorisms. Quotes your own words back at you so the dodges become visible.
- **Outputs Your Playbook** — what you believe, the bets implied, the load-bearing assumptions, what you're NOT betting on, a ship list with dates and signals, open questions with re-open conditions.
- **Then offers 3 scaffolds** — concrete artifacts grounded in the playbook (tracking docs, drafted cold DMs, Codex prompts, vendor shortlists, weekly review prompts). The reward, not just the thinking.

## Install

```bash
mkdir -p ~/.claude/skills/gtm-pov && \
  curl -fsSL https://raw.githubusercontent.com/fvckprth/gtm-pov/main/SKILL.md \
    -o ~/.claude/skills/gtm-pov/SKILL.md
```

Restart Claude Code (or run `/skills`) so the skill is picked up. Then ask anything that smells like a GTM playbook.

## Trigger phrases

Anything in this shape will fire the skill:

- "help me with GTM"
- "what's the GTM for X"
- "how should I launch Y"
- "figure out my ICP"
- "pricing strategy"
- "positioning for Z"
- "cold outbound"
- "content strategy"
- "what's our funnel"
- "growth plan"

## License

MIT. See [LICENSE](./LICENSE).
