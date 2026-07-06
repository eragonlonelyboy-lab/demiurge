<div align="center">

![The Demiurge: a house of gods keeping AI agents honest](assets/hero.png)

# DEMIURGE

**A house of gods, forged to keep your AI agents honest.**

![license](https://img.shields.io/badge/license-MIT-E8A23D)
![windows first](https://img.shields.io/badge/Windows-first-2C7A7B)
![deterministic](https://img.shields.io/badge/core-deterministic-E8A23D)
![honest numbers](https://img.shields.io/badge/honest__numbers-every%20repo-2C7A7B)

</div>

In Greek philosophy the Demiurge is the craftsman who does not argue about the world, he makes it. This is his house: a pantheon of small, sharp, mythology-named tools, each standing guard over one place AI agents actually fail. The lie at the finish line. The token bonfire. The memory rot. The same correction typed for the fifth week running.

Your agent is brilliant. Left alone, it is also a very confident intern. So the gods keep watch. Every one of them is a standalone tool with runnable benchmarks, an honest-numbers page, and a real MIT license, and every one of them would rather show you the receipt than take your word for it.

## The pantheon

| God | Repo | Day job |
|---|---|---|
| **HORKOS**, god of oaths | [horkos](https://github.com/eragonlonelyboy-lab/horkos) | Your agent swore it was done. HORKOS makes the artifact testify before the session may end |
| **MONETA**, goddess of the mint | [moneta](https://github.com/eragonlonelyboy-lab/moneta) | Minds the token spend: warnings before waste, a lower-bound savings ledger after, no fake numbers |
| **HYPNOS**, god of sleep | [hypnos](https://github.com/eragonlonelyboy-lab/hypnos) | Consolidates agent memory the way sleep consolidates yours: every change a diff, nothing ever deleted |
| **CHIRON**, trainer of heroes | [chiron](https://github.com/eragonlonelyboy-lab/chiron) | Trained Achilles; now trains your agents. Every correction becomes a permanent rule, across every agent you run |
| **ATHENA**, goddess of wisdom | [athena](https://github.com/eragonlonelyboy-lab/athena) | Does not say "great idea!". Puts your decisions on trial: one GO / RESHAPE / KILL verdict, on the record |
| **VERITAS**, goddess of truth | [veritas](https://github.com/eragonlonelyboy-lab/veritas) | Reads your AI's prose and reaches for the red pen. Strips the tells, keeps your voice, audits its own rewrite |
| **CALLIOPE**, chief of the Muses | [calliope](https://github.com/eragonlonelyboy-lab/calliope) | Runs a full design agency in your terminal, gated by a QA lead who does not accept "looks fine" |
| **MAAT**, goddess of order | [maat](https://github.com/eragonlonelyboy-lab/maat) | One local screen over every agent you run: each "done" gets weighed against the feather of truth |

More gods are ascending.

## The doctrine

Every god here obeys the same laws, and each repo states them as product law, not marketing:

1. **Evidence or it did not happen.** Self-report is not proof. Receipts, re-fetches, diffs, and ledgers are.
2. **The critical path is deterministic.** Audits, ledgers, compilers, and health scores never call an LLM. Their false positives are findable, fixable, and benchmarkable; a judge-model's mistakes are none of those things.
3. **Warn first, never trap.** Warn-mode defaults, dry-run defaults, bounded retries, archive-not-delete. You always see the plan, always restore, always leave.
4. **Honest numbers only.** Every repo ships `docs/HONEST-NUMBERS.md`: what the numbers cannot prove, when the tool is the wrong tool, and the one honest test. Every claimed number has a committed benchmark you rerun with `npm test`.
5. **Windows first, MIT always.** Tested on the OS most dev tools treat as an afterthought, licensed with the file actually in the repo.

## The stack

Each god works alone. Together they close loops no single tool can:

| You run | You get |
|---|---|
| HORKOS alone | phantom claims and silent write failures caught at the exit |
| MONETA + HORKOS | sessions stamped **cheaper AND provably not-worse**: a savings number means nothing if the work got worse, so the pair is the point |
| CHIRON + HORKOS | the failure HORKOS catches today becomes a rule your agents obey forever |
| HYPNOS + CHIRON | rules compile in clean and stay clean: contradictions surfaced, duplicates merged, budgets enforced |
| VERITAS + CALLIOPE | client-facing words gated twice: once for slop, once for craft |
| MAAT over all of it | one screen, every agent, receipts behind every status |

## Pick your god

Each repo installs in one or two commands, PowerShell shown first, re-run safe, zero config to start. Every repo carries a companion `CLAUDE.md`: open it in your agent, say "set this up for me", and the god explains itself step by step.

Start where it hurts most:

- Agent says "done" and it wasn't? **HORKOS.**
- Context window evaporating? **MONETA.**
- CLAUDE.md, AGENTS.md, and Cursor rules disagreeing? **HYPNOS.**
- Typing the same correction every week? **CHIRON.**
- About to build the wrong thing enthusiastically? **ATHENA.**
- Prose that smells like a model? **VERITAS.**
- Design work below the bar? **CALLIOPE.**
- Too many agents, one pair of eyes? **MAAT.**

## The fair trade

The house is open, the gods work for free, and every claim in every repo reruns on your machine. If one god catches one lie, one leak, or one week of repeated corrections, the star costs you a click. Fair trade. ⭐

MIT, every repo, no exceptions. The Demiurge forges; you own what you carry out of the house.
