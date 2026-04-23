# Brian Balfour GTM Strategy Skill

A Claude Code skill that acts as a Head of Growth for any founder — diagnosing the business with Brian Balfour's Four Fits Framework and prescribing a specific, opinionated Year 1 growth plan.

Built by [Anant Mendiratta](https://github.com/anantmendiratta). Core frameworks from [Brian Balfour](https://brianbalfour.com).

---

## What it does

Drop this skill into Claude Code and it becomes a diagnosis-driven growth strategist. It works for any business type — B2B SaaS, consumer apps, fintech, healthtech, DTC, AI products, marketplaces, hardware.

Trigger it by asking anything about:
- How to go to market or get first users
- Which channels to use and in what order
- What metrics actually matter (vs. vanity)
- How to price for the chosen motion
- How to handle investor or customer objections
- Year 1 execution planning with quarterly investor updates

The skill adapts to narrow questions too — ask about channels only, ask about one objection, ask how to get the first 1,000 users. It won't force a 12-section document on you when you just need one answer.

---

## The Frameworks

### Brian Balfour's Four Fits (the diagnostic core)

Every strategy starts with diagnosing which of four fits is working, broken, or unknown:

| Fit | Question |
|-----|----------|
| **Market–Product** | Does the market actually have the problem, and does the product solve it for the specific ICP? |
| **Product–Channel** | Is the product designed to ride the planned channels — or is it being forced into them? |
| **Channel–Model** | Do the channel costs and ARPU mathematically work together? |
| **Model–Market** | Is the market large enough to support a real business at current pricing? |

The broken or unknown fit is what Year 1 must prove. Everything else is downstream.

> Balfour's original essays: [brianbalfour.com/four-fits-growth-framework](https://brianbalfour.com/four-fits-growth-framework)

### Ten Growth Motions

Growth is a muscle, not a motion. The skill selects one primary and one or two supporting motions:

1. **Product-Led** — the product sells itself (Figma, Notion, Slack)
2. **Sales-Led** — humans sell; high ACV, committee buyer (Salesforce, Rippling)
3. **Story-Led** — narrative and category creation pull demand (HubSpot, Drift)
4. **Ads-Led** — performance marketing is the engine; creative + math (DTC, mobile)
5. **Creative-Led** — brand and distinctive creative are the moat (Liquid Death, Duolingo)
6. **Model-Led** — the pricing/delivery model is the wedge (Airbnb, Warby Parker)
7. **Channel-Led** — dominate one channel competitors can't match (Glossier, Notion SEO)
8. **Data-Led** — more users → better product → more users (TikTok, Ramp, Scale AI)
9. **Event/Community-Led** — trust travels through rooms and relationships (Dreamforce, INBOUND)
10. **Integration-Led** — embed into tools users already live in (GitHub Copilot, Notion AI, Grammarly)

### AI Era Overlays

Built directly from Balfour's 2025 essay ["The Four Fits: A Growth Framework for the AI Era"](https://blog.brianbalfour.com/p/the-four-fits-a-growth-framework), the skill applies updated overlays to each fit:

**Market–Product:** PMF is now an inflection point, not a gradual journey. Companies can find and lose it in months (the Chegg precedent: $1.2B → $150M in nine months after ChatGPT launched). The skill distinguishes novelty sign-ups from retained PMF — Day-30 is the signal, not Day-1.

**Product–Channel:** The SEO/UGC channel that built TripAdvisor, Pinterest, Quora, and G2 is structurally at risk. The skill flags AEO (AI Engine Optimization — being findable inside ChatGPT and Perplexity) as the emerging first-mover channel, alongside integration ecosystems and the AI demo as a sales motion.

**Channel–Model:** Three new mechanisms break this fit — rising inference costs (some AI products run at 35% gross margin vs. 70%+ SaaS norm), channel collapse forcing expensive paid alternatives, and the Danger Zone where ARPU is too low for human sales but too complex for viral. The skill diagnoses which zone you're in and prescribes the exit.

**Model–Market:** AI expands and contracts markets simultaneously. The skill uses Christoph Janz's five pathways to $100M (Elephants/Moose/Rabbits/Mice/Flies) to identify which pathway AI pushes you toward, and the commoditization pressure test to identify whether your moat is real.

**Smooth Sailers vs. Tugboats:** When all four fits align, companies grow despite organizational chaos. When they misalign, every result requires exceptional execution. The skill is designed to find the misalignment before it shows up in the numbers.

---

## What it outputs

A complete GTM Strategy Document with:

1. **Founder Inputs & Research Summary** — what was learned before prescribing anything
2. **Four Fits Diagnostic** — table with status (Working / Unknown / Broken) and implications
3. **The Growth Motion** — named primary motion + what is explicitly NOT being done in Year 1
4. **The Constants** — 3 permanent human truths the product is built on
5. **Category & Positioning** — the category being owned or created, plus positioning statement
6. **Trust / Activation / Conviction Ladder** — staged by what must be proven and to whom
7. **Signal Metrics** — 4 metrics max, motion-matched, with vanity-vs-signal comparison table
8. **Channel Strategy** — sequenced, motion-matched, trust-filtered
9. **Pricing & Model** — architecture specific to the chosen motion
10. **Year 1 Execution Plan** — 4 themed quarters with actions, success criteria, and past-tense investor updates
11. **Objection Handling** — 3 objections with full response + one-liner each
12. **The Commitment** — the founder's promise tied back to the 3 constants

Tone is declarative and opinionated throughout. No hedging. Every action has an actor. Every claim has a number.

---

## Skill structure

```
gtm-strategy-skill/
├── SKILL.md                          # Skill instructions + 5-step workflow
├── assets/
│   └── gtm-output-template.md        # Output scaffold (motion-adaptive)
├── references/
│   ├── four-fits-diagnostic.md       # Full Four Fits diagnostic with AI-era overlays
│   ├── growth-motions.md             # Deep playbook for all 10 motions + selection tree
│   ├── channel-playbooks.md          # Channels by motion, trust-by-category matrix
│   ├── frameworks-toolkit.md         # Constants, Trust Ladder, Signal Metrics, Pricing
│   ├── objection-reframing.md        # Reframe patterns + 12 worked objections
│   ├── example-clartha.md            # Worked example: trust-led B2B SaaS
│   └── example-plg.md               # Worked example: PLG consumer product
└── scripts/
    └── export_docx.py               # Export strategy as formatted .docx
```

---

## Installation

This is a Claude Code skill. Place the `gtm-strategy-skill/` folder in your skills directory, or install it via the Claude Code skill manager.

Once installed, the skill triggers automatically when you ask growth or GTM questions. You can also invoke it explicitly:

```
/gtm-strategy
```

---

## Credits

**Skill creator:** [Anant Mendiratta](https://linkedin.com/in/anantmendiratta) — founder of [Fractics](https://fractics.com)

**Frameworks:** This skill is built on Brian Balfour's Four Fits Growth Framework. Brian is the founder of Reforge and one of the most rigorous thinkers on sustainable company growth. The Four Fits framework — Market-Product, Product-Channel, Channel-Model, Model-Market — is the diagnostic backbone of every strategy this skill produces.

- [brianbalfour.com](https://brianbalfour.com)
- [Four Fits Growth Framework](https://brianbalfour.com/four-fits-growth-framework) — original essay
- [The Four Fits: A Growth Framework for the AI Era](https://blog.brianbalfour.com/p/the-four-fits-a-growth-framework) — 2025 update, the primary source for the AI-era overlays in this skill
- [Reforge](https://www.reforge.com)

Additional frameworks adapted from first-principles thinking on growth motions, trust ladders, and signal metrics. All worked examples are original.

**Built with:** [Claude Code](https://claude.ai/code) and the Claude Code Skills SDK.
