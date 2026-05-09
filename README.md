# gtm-pov

It won't give you a GTM playbook.

You ask something normal — "how should I price this?" or "what's the GTM for the launch?" — and it refuses. Throws the question back as a belief question. Then it grills you until you can say what you actually think in your own words. Not the Lenny line you half-remembered. After that it makes you ship something. A landing page. A cold email. Something. By Friday.

For ten years GTM was just downstream of whatever org and tools and budget you had. You hired the head of marketing, they ran the playbook everyone else was running. That ended. AI ate that gap. You can ship a real test of an idea in a day, so GTM is now whatever you actually believe about the people you're selling to and how fast you can put that belief on a page.

## What it does

Refuses on the first turn. Whatever you asked gets handed back as a belief question.

Maps three things separately. Bets. Beliefs. Assumptions. Most GTM thinking smashes these together and that's where it goes soft. A bet is a wager. Belief is what you think is true about the customer. Assumption is the load-bearing thing the whole approach is sitting on, usually invisible until it breaks.

Drills one of those at a time. No praise. Quotes your own words back at you so the hedge becomes obvious.

When you call it, you get Your Playbook: what you believe, the bets that implies, the assumptions sitting under it, what you're explicitly not doing, a ship list with dates and signals, plus the questions you're parking with conditions for reopening.

Then it offers three scaffolds you can use this week. A tracking doc. A draft of the DM you said you'd send. A Codex prompt for the page. A vendor shortlist if a bet has tooling in it. A Friday review prompt. It picks three that fit the playbook you just wrote, you pick one or two, it builds them.

## Install

```bash
mkdir -p ~/.claude/skills/gtm-pov && \
  curl -fsSL https://raw.githubusercontent.com/fvckprth/gtm-pov/main/SKILL.md \
    -o ~/.claude/skills/gtm-pov/SKILL.md
```

Restart Claude Code (or hit `/skills`). Then go ask it something GTM-shaped.

## Trigger phrases

Anything that sounds like one of these:

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
