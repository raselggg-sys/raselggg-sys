# Ruslan Osyka

I build the context layer my agents run on: one file-based system Claude Code and Codex share.
13 years in e-commerce, built and sold 3 businesses. Warsaw.

Models are good enough. Context breaks: agents forget between sessions, mix facts with guesses, drift on the third handoff.

## How it works

- **Typed context.** Frontmatter on every file: role, status, source of truth, when-to-read trigger. An index script validates IDs, roles, dates, links on every change (69 files).
- **Facts vs guesses.** Facts carry date, source, status; hypotheses are tagged, never silently promoted. One fact, one place; one writer per store.
- **Context passport.** Verbatim brief to every subagent, echo check first, cold reader last.
- **Codex harnesses.** Goal file, resumable supervisor loop, reviewer subagents, machine-checkable done criteria.
- **Adversarial decisions.** 8 generator angles → dedup → 3 independent judges per item (evidence, constraints, motivation) → writer in my voice → cold reader. Last run: 90 candidates → 21, each backed by a quote from my notes.
- **Skills.** Anything repeated twice becomes a skill. 21 so far.

## Where it runs

My research, operations and decisions. E-commerce validation: agent-built storefronts, 48-hour paid-traffic tests with pre-registered pass/fail thresholds. Negotiation prep: parallel-agent dossiers, every claim sourced.

**Compare notes on:** agent reliability across handoffs, evals for non-code work, memory that doesn't rot.

Code: 80+ private repos. Happy to demo live.
