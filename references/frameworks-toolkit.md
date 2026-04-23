# Frameworks Toolkit

The core frameworks used across any GTM strategy: Constants, Trust Ladder, Signal Metrics by motion, and Pricing patterns by motion.

---

## Table of Contents

1. [The Three Constants](#the-three-constants)
2. [The Trust Ladder](#the-trust-ladder)
3. [Signal Metrics by Motion](#signal-metrics-by-motion)
4. [Pricing Architecture by Motion](#pricing-architecture-by-motion)

---

## The Three Constants

**The idea:** Every business must rest on permanent human truths — things the customer has always wanted and will always want. Trends, technologies, and regulations change. Constants do not.

**The test:** Would this be true in 1995, 2010, and 2040? If yes, it's a constant. If it depends on a current trend, platform, regulatory moment, or technology being novel — it's not a constant.

**Examples:**

- **Amazon's constants:** More selection. Better prices. Faster delivery.
- **Google's constants:** Find the right answer. Find it fast. Trust the source.
- **Notion-like:** Organize my thinking. Share it with others. Change my mind without starting over.
- **Fitness app:** Look better. Feel better. Live longer.
- **Legal SaaS for lawyers:** Win the case. Save time. Don't get sued for malpractice.
- **Investment product:** Make more. Lose less. Understand what I own.

**How to find them:**

1. Ask: what frustration or aspiration does this product address at a human level?
2. Strip away the technology entirely. What remains?
3. Name each constant in 2–4 words. Then one paragraph explaining the permanent human truth behind it. Why does this exist? Why has it always existed? Why will it exist regardless of technology?

**Format for each constant in the strategy doc:**

```
### [Number] — [Constant Name]

[One paragraph explaining the permanent human truth. Specific to this user. Why has this always existed? Why will it always exist regardless of technology or trend? Should feel like an insight, not a platitude.]
```

**After all three:**

```
These three constants are [Company]'s North Star. When the team debates features, partnerships, or priorities — ask one question: does this serve [Constant 1], [Constant 2], or [Constant 3]? If the answer is no, deprioritise.
```

**The constants become the skeleton of everything downstream** — the positioning, the content strategy, the pricing tiers, even the investor update. Every tactic should trace to one of the three.

---

## The Trust Ladder

**Use when:** Story-Led, Sales-Led, or any trust-heavy category (legal, medical, financial, compliance, enterprise security, regulated industries, high-consequence B2B).

**Skip or abbreviate when:** Pure Ads-Led or Creative-Led consumer plays where the trust question is less load-bearing (low-stakes purchase, short time-to-value, returnable).

**The idea:** GTM staged by what must be proven at each growth stage, and to whom. Every tactic maps to current stage only. Premature scaling — spending on channels that expect trust you haven't earned — is the #1 reason early-stage growth fails.

**Default ladder:**

| Stage | What You Are Proving | To Whom |
|-------|---------------------|---------|
| 0 → 1 | The product actually works | Yourselves |
| 1 → 500 | [Specific proof point for this business at this stage] | Early community |
| 500 → 5,000 | [Specific proof point — often: it's worth paying for, at price] | The market |
| 5,000 → 50,000 | It spreads on its own | Growth engine |

**Adapt stage 1→500 and 500→5K language to the specific business:**

- PLG consumer: "It forms a daily habit" → "It converts free users to paid at 15%+"
- Sales-led enterprise: "5 named logos sign 6-figure contracts" → "repeatable sales motion with CAC payback < 18 months"
- Story-led fintech: "serious investors refer it unprompted" → "it's the default mention in the category"
- Creative-led DTC: "repeat purchase rate > 35%" → "brand search volume exceeds paid traffic"

**Rule: match every Year 1 tactic to the current stage only.** A founder at stage 1→500 running paid ads built for stage 500→5K is burning money. A founder at 500→5K still doing 20-minute onboarding calls is capping their own ceiling.

---

## Signal Metrics by Motion

**4 metrics max.** Each metric must answer: does this predict whether a user will still be here in 90 days AND does it predict revenue growth?

**Include a vanity-vs-signal table** calling out the specific tempting vanity metrics for this business — things that would feel good to report but tell you nothing.

**Include a retention interpretation table** (see below).

### Metrics by Motion

**Product-Led:**
- Activation rate (% of sign-ups reaching first value moment in Day 1)
- Day-30 retention of new cohorts
- Free-to-paid conversion
- Viral coefficient or referral rate

**Sales-Led:**
- Pipeline coverage (pipeline $ : quota × 3–5)
- Sales cycle length (trending down quarter over quarter)
- SQL-to-Closed-Won conversion
- Net Revenue Retention (110%+ healthy)

**Story-Led:**
- Qualified inbound citing content (the magic number — do inbound leads mention your content?)
- Newsletter/follower growth (but only from ICP)
- Category search volume trend
- Demo / trial requests per content piece

**Ads-Led:**
- CAC by channel AND by creative
- LTV:CAC (cohort-based, not blended)
- ROAS
- First-order profitability (are you profitable on first purchase?)

**Creative-Led:**
- Branded search volume trend
- Earned media impressions + sentiment
- Organic engagement per creative
- Repeat purchase rate (does the brand outlast the ad?)

**Model-Led:**
- Cohort unit economics proving the model works at scale
- % of users citing the model in NPS feedback
- Conversion from "surprised" to "convinced" (interview-based)

**Channel-Led:**
- % of new users from the dominant channel (>60% target)
- Channel-specific engagement (CTR, watch time, follow rate)
- CPA on the channel vs. alternatives

**Data-Led:**
- Cohort performance over time (cohort N outperforms cohort N-1)
- Data quality improvements (precision/recall, error rate)
- Usage-to-data conversion (how fast does usage improve the product?)

**Event/Community-Led:**
- Pipeline sourced from events (measured 60–90 days post-event)
- Community weekly active members
- Referral rate from community members
- Event-sourced vs. other-sourced retention (events usually retain 2–3× better)

### Vanity vs Signal Table (universal template)

```
| Vanity — Ignore | Signal — Track Instead |
|----------------|------------------------|
| Total downloads / sign-ups | Day-30 active rate of new cohorts |
| Social media followers (total) | Engagement rate from ICP specifically |
| Press mentions | Qualified inbound citing the story |
| App store rating | Qualitative: do users cite specific value? |
| Features shipped | Features used by >40% of paid users |
| Total addressable market | Serviceable obtainable market at current CAC |
| Revenue (without cohort view) | Cohort retention + net dollar retention |
```

**Customize to the specific business.** If they're a DTC brand, add "GMV" as vanity vs. "contribution margin" as signal. If they're enterprise, add "logos" as vanity vs. "logos with 6-month retention" as signal.

### Retention Curve Interpretation

Run a retention audit at Month 6 before accelerating acquisition.

| Day-90 Retention | What It Means | Action |
|-----------------|---------------|--------|
| > 70% | Exceptional. Real habit / repeat behavior formed. | Scale acquisition aggressively |
| 60% – 70% | Strong. Product is working. | Scale with optimization in parallel |
| 50% – 60% | Acceptable early signal. | Fix top churn reasons before scaling |
| < 50% | Product-market fit not yet proven. | Pause acquisition. Fix product first. |

**Retention threshold varies by category:**
- SaaS: Day-90 paid retention benchmarks above
- Consumer mobile: Day-30 retention > 25% is already very good; Day-90 > 15% is strong
- DTC: repeat purchase rate within 90 days > 30% for consumables; < 10% means subscription/bundle might be wrong
- Enterprise: annual retention; > 95% Gross Retention is healthy

---

## Pricing Architecture by Motion

**Pricing is not a decision made in isolation.** It's a function of motion, ACV, buyer, and stage.

### SaaS / Subscription (Product-Led)

3 tiers: Free → Pro → Power. Free should be generous enough to create habit, bounded enough to force upgrade.

```
| Tier | Price | Target | Key Features |
|------|-------|--------|--------------|
| Free | $0 | Curious / trial | Core feature, bounded usage, 1 user |
| Pro | $X/mo | Serious individual | Full feature set, unbounded single-user, integrations |
| Power | $Y/mo | Team / power user | Collab, admin, SSO, priority support |
```

- Annual pricing at 17–20% discount — available, not default. Convert to annual after habit forms.
- Don't launch with a discount. Launch at full price with waitlist / invite-only. Filters for serious users, anchors price.

### SaaS / Subscription (Sales-Led)

Usually 3 tiers but with "Contact Us" at the top and custom contracts. Procurement-friendly.

```
| Tier | Price | Target | Key Features |
|------|-------|--------|--------------|
| Starter | $X/mo (self-serve) | Team, 5–25 seats | Core features, email support |
| Growth | $Y/mo (sales-assisted) | 25–250 seats | SSO, advanced permissions, SLAs |
| Enterprise | Custom | 250+ seats | SOC2, dedicated CSM, custom integrations |
```

- Annual commits are the norm (monthly is the exception).
- Publish Starter/Growth pricing; keep Enterprise custom.
- Sales-assisted motion starts at tier 2. Discovery call is the product demo.

### Project / Services Hybrid (Build + Retain Model)

Common for agency-style, custom AI builds, integration services, or high-touch deployment products.

```
| Tier | Build Price | Monthly Retainer | Target | Scope |
|------|-------------|------------------|--------|-------|
| Starter | $X | $Y/mo | Single use case | Basic deployment |
| Core | $X | $Y/mo | Multi-use case | Deployment + ongoing ops |
| Power | $X | $Y/mo | Strategic partner | Custom + priority roadmap |
```

- Never quote fixed price without a discovery call — the discovery call IS the product demo.
- Retainer should feel like insurance against drift, not ongoing bill-by-hour.

### DTC / Consumer Physical

Usually one SKU or a small core line + upsells. Pricing = positioning.

- Premium vs. mid vs. mass positioning set by price, not by features
- Bundle / subscription to shift LTV upward
- Don't race to discount — if margin lets you advertise, premium price + distinctive creative beats commodity + price war

### Marketplace

Take-rate pricing (10–30% typical for services, lower for high-AOV goods). Sometimes listing fee.

- Which side pays? (Usually the side with more value capture — host not guest on Airbnb.)
- Test take-rate with the first 100 transactions; adjust fast.

### Usage-Based / Consumption

Pay-per-use (API calls, compute, GB, events). Common in dev tools, infra, AI inference.

- Low/free starter tier to hook usage
- Consumption ramps predictably with customer success
- Works when customer's own revenue scales with usage (you grow when they grow)

### Marketplace / Model-Led Pricing

Sometimes the pricing IS the product. (Robinhood's commission-free trading. Netflix's unlimited streaming. Warby Parker's $95 glasses.) When the model is the wedge:

- Pricing is the headline
- PR and positioning reinforce the model change
- Don't bury the price — lead with it

### AI Product Pricing (Usage-Based, Outcome-Based, Integration Tier)

AI products have three pricing patterns not captured by standard SaaS tiers:

**Usage-based (tokens / API calls / documents processed):**
- Best when usage scales naturally with customer success (their output grows → your revenue grows)
- Requires a free or starter tier to prove value before metered billing starts
- Risk: revenue unpredictability. Mitigate with usage minimums or committed tiers.
- Key question: at peak usage, what's the gross margin after inference costs? Price so that your best users aren't your most expensive.

```
| Tier | Price | Includes | Overage |
|------|-------|----------|---------|
| Free | $0 | [N] units/mo | Not available (upgrade to use more) |
| Pro | $X/mo | [N] units/mo included | $Y per additional unit |
| Team | $Z/mo | [N] units/mo + seat management | $Y per additional unit |
| Enterprise | Custom | Committed volume + SLA + SSO | Negotiated |
```

**Outcome-based (per contract reviewed, per lead generated, per hire made):**
- Best when the AI produces a measurable, attributable outcome the user pays money for otherwise
- The price is a fraction of the value delivered — not tied to compute
- Requires clear outcome tracking built into the product
- Risk: you need to be right enough that users feel the outcome was delivered. Hallucinations break this model fast.

**Integration tier (free core feature / paid for depth or volume inside host platform):**
- Best for Integration-Led products — the integration itself is free or freemium; revenue comes from depth of use, team-level plans, or enterprise features
- The host platform's marketplace often sets pricing norms (don't price far above or below the ecosystem average)
- Co-selling with the host platform (they upsell your product in their renewals) can happen at higher tiers

**Pricing test for AI products:** Can you be profitable per user at 10× current usage? If yes, growth is healthy. If no, the pricing model needs to change before you scale.

### Launch Rule (All Models)

**Do not launch with a discount.** Launch at full price with scarcity — invite-only, waitlist, founder-gated access. This:

- Filters for serious buyers
- Anchors price expectations early
- Signals category position (you are not competing on cost)
- Creates a natural content moment ("we opened access to the next 100 users")

Discounts pulled after launch are nearly impossible to reverse; they permanently anchor a lower expectation.
