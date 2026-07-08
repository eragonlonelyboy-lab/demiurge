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
| **HORKOS**, god of oaths | [horkos](https://github.com/eragonlonelyboy-lab/horkos) | **Guardrails for AI agents.** Your agent swore it was done; HORKOS makes the artifact testify before the session may end |
| **MONETA**, goddess of the mint | [moneta](https://github.com/eragonlonelyboy-lab/moneta) | **AI FinOps.** Minds the token spend: warnings before waste, a lower-bound savings ledger, no fake numbers |
| **HYPNOS**, god of sleep | [hypnos](https://github.com/eragonlonelyboy-lab/hypnos) | **The memory layer.** Consolidates agent memory the way sleep consolidates yours: every change a diff, nothing ever deleted |
| **CHIRON**, trainer of heroes | [chiron](https://github.com/eragonlonelyboy-lab/chiron) | **The self-improving loop.** Trained Achilles; now trains your agents: every correction becomes a permanent rule across every agent you run |
| **ATHENA**, goddess of wisdom | [athena](https://github.com/eragonlonelyboy-lab/athena) | **Red-team your decisions.** A wise war council with Sun Tzu's terrain read: one GO / RESHAPE / KILL verdict, on the record |
| **VERITAS**, goddess of truth | [veritas](https://github.com/eragonlonelyboy-lab/veritas) | **Kill the AI slop.** Reads your AI's prose with a red pen: strips the tells, keeps your voice, audits its own rewrite |
| **CALLIOPE**, chief of the Muses | [calliope](https://github.com/eragonlonelyboy-lab/calliope) | **The agentic design agency.** A full design studio in your terminal, gated by a QA lead who does not accept "looks fine" |
| **MAAT**, goddess of order | [maat](https://github.com/eragonlonelyboy-lab/maat) | **The Agentic OS.** One local screen over every agent you run: each "done" weighed against the feather of truth |
| **ZOILUS**, scourge of Homer | [zoilus](https://github.com/eragonlonelyboy-lab/zoilus) | **The merciless critic.** He found fault in Homer; now a blind panel judges your artifact against a world-class bar, and rejects on doubt |
| **PEITHO**, goddess of persuasion | [peitho](https://github.com/eragonlonelyboy-lab/peitho) | **Go-to-market.** Positioning, angles, offers, and the assets to run them, behind a gate that refuses to let any of it sound generic |
| **PYRRHO**, founder of skepticism | [pyrrho](https://github.com/eragonlonelyboy-lab/pyrrho) | **The skeptic.** Suspends judgment until the data earns it: sampling, bias, and every claim weighed against the evidence behind it |

More gods are ascending.

## The doctrine

Every god here obeys the same laws, and each repo states them as product law, not marketing:

1. **Evidence or it did not happen.** Self-report is not proof. Receipts, re-fetches, diffs, and ledgers are.
2. **The critical path is deterministic.** Audits, ledgers, compilers, and health scores never call an LLM. Their false positives are findable, fixable, and benchmarkable; a judge-model's mistakes are none of those things.
3. **Warn first, never trap.** Warn-mode defaults, dry-run defaults, bounded retries, archive-not-delete. You always see the plan, always restore, always leave.
4. **Honest numbers only.** Every repo ships `docs/HONEST-NUMBERS.md`: what the numbers cannot prove, when the tool is the wrong tool, and the one honest test. Every claimed number has a committed benchmark you rerun with `npm test`.
5. **Windows first, MIT always.** Tested on the OS most dev tools treat as an afterthought, licensed with the file actually in the repo.
6. **Verify at the layer of the claim, and prefer an outside check.** "Done" is proven where the claim lives: the re-fetched page, the rendered screen, the counted rows, not the layer below it. A check run by something other than the maker beats self-review, because the maker leans toward the conclusion it already built. And every lesson worth keeping is written down, so the next run starts where the last one ended. The gods are how a house makes those habits automatic instead of optional.

## The stack

Each god works alone. Together they close loops no single tool can:

| You run | You get |
|---|---|
| HORKOS alone | phantom claims and silent write failures caught at the exit |
| MONETA + HORKOS | sessions stamped **cheaper AND provably not-worse**: a savings number means nothing if the work got worse, so the pair is the point |
| CHIRON + HORKOS | the failure HORKOS catches today becomes a rule your agents obey forever |
| HYPNOS + CHIRON | rules compile in clean and stay clean: contradictions surfaced, duplicates merged, budgets enforced |
| VERITAS + CALLIOPE | client-facing words gated twice: once for slop, once for craft |
| HORKOS + ZOILUS | both halves of trust: HORKOS proves the work landed, ZOILUS proves it was worth keeping |
| ZOILUS + CHIRON | the rejection ZOILUS names once becomes a rule the producer can no longer break |
| PEITHO + PYRRHO | no conversion number reaches a landing page before the data has earned it |
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
- Shipping work that is merely fine? **ZOILUS.**
- Launch copy that sounds like every other launch? **PEITHO.**
- A number in a slide nobody has audited? **PYRRHO.**

## The fair trade

The house is open, the gods work for free, and every claim in every repo reruns on your machine. If one god catches one lie, one leak, or one week of repeated corrections, the star costs you a click. Fair trade. ⭐

MIT, every repo, no exceptions. The Demiurge forges; you own what you carry out of the house.
