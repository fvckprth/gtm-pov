# gtm-pov

A Claude Code skill that refuses to give you a generic GTM playbook.

When you ask "what's the GTM for X?" / "how should I price this?" / "figure out my ICP" — it refuses, restates the surface ask as a belief question, drills until you own the belief in your own words (not a Lenny phrase, not a YC essay), then forces you to ship a working artifact this week instead of a 90-day plan.

Built on the thesis of Nicolas Sharp's [*GTM is a Creative Act*](https://atlas.attio.com/gtm-is-a-creative-act): GTM used to be downstream of org structure, tools, and budgets — the playbook followed, the hiring plan followed. AI collapsed that. Now GTM is a function of what you actually believe about your customer, and the winners ship in days, not quarters.

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

## Verifying it works

The skill is working if it:

1. Refuses to hand you a list, framework, or phased plan on the first turn.
2. Quotes your own words back ("you said three channels — name them").
3. Asks one question at a time, closed-form when possible.
4. Produces a Bets / Beliefs / Assumptions map before drilling.
5. Ends with Your Playbook + 3 scaffold offers grounded in your specific session.

It's failing if it:

- Gives you a generic GTM checklist on the first ask.
- Stacks multiple questions per turn.
- Delivers verdicts or aphorisms ("you don't have 20, you have a wish").
- Skips the Assumptions section in the Playbook.
- Stops at strategy without producing scaffolds.

## Credit

Built on the thesis of Nicolas Sharp, [*GTM is a Creative Act*](https://atlas.attio.com/gtm-is-a-creative-act) — Attio Atlas. If you adapt or share this skill, credit the source.

## License

MIT. See [LICENSE](./LICENSE).
