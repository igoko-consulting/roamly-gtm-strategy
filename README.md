# Roamly Groups: Go-To-Market Strategy, by Martin Cook

> A go-to-market strategy for **Roamly Groups**, a fictional group-booking feature on a fictional curated-experiences platform. Each of the five chapters draws on one module of a Product School go-to-market course and settles one area: strategy, competition, positioning, messaging and pricing. In each, a test, mostly run in two AI models, changed an earlier answer. Roamly's own figures belong to the scenario; competitor facts are real and dated where checked.

**How to read this repo:** each module folder holds its deliverable and a `NOTES.md` with the module's ideas and my takeaways. [PROMPTS.md](PROMPTS.md) keeps every prompt, run word for word in GPT-6 and Claude, and how the replies differed; each module's `ai-replies/` folder holds both models' replies as evidence. [CLAUDE.md](CLAUDE.md) holds the working rules I set for Claude Code, which I used to run the prompts, check facts and keep the repo consistent.

---

## Deliverables at a glance

| # | Deliverable | Module | Status | File |
|---|---|---|---|---|
| 1 | **GTM Strategy** (Discover Framework + motion + V1 one-pager) | M1 | ✅ | [`01-gtm-strategy/gtm-strategy.md`](01-gtm-strategy/gtm-strategy.md) |
| 2 | **Competitive Intelligence & Strategic Bet** (battlecard) | M2 | ✅ | [`02-competitive-intel/battlecard-and-bet.md`](02-competitive-intel/battlecard-and-bet.md) |
| 3 | **Positioning Statement** (framework + statement) | M3 | ✅ | [`03-positioning/positioning.md`](03-positioning/positioning.md) |
| 4 | **Messaging Pillars** | M4 | ✅ | [`04-messaging/messaging-pillars.md`](04-messaging/messaging-pillars.md) |
| 5 | **Pricing Recommendation** | M5 | ✅ | [`05-pricing/pricing-recommendation.md`](05-pricing/pricing-recommendation.md) |
| 6 | **Final Presentation** (the five chapters in one page, and what I learned) | M6 | ✅ | [`final-presentation.html`](final-presentation.html) |

## The strategy in one sentence

A vetted local host who welcomes the group, and everyone pays their own share: Roamly Groups is for organisers of milestone celebrations, and the bet is Expand first, then Acquire through the guests.

## How the strategy changed

Each module tested an earlier answer, and all five changed one. Every change was carried back through the earlier modules, so each file shows the current decision.

| Module | What changed | Why | Evidence |
|---|---|---|---|
| 1 | Primary goal from Acquire to Expand, with Acquire second, through the guests | Both models, as a sceptical CMO, pointed out that every signal came from existing users | [Pressure test](01-gtm-strategy/ai-replies/1-pressure-test.md) |
| 2 | Segment narrowed from occasion groups (hen, stag, milestone birthdays) to milestone celebrations | The battlecard showed a specialist already sells per-guest payment to hen and stag groups; the marketplaces milestone groups use don't | [Battlecard and bet](02-competitive-intel/battlecard-and-bet.md) |
| 3 | Positioning rebuilt around hosts who welcome groups | Playing Airbnb, both models said they could reuse the first draft; Claude named host opt-in, my "Despite" turned round, as the part Airbnb couldn't copy | [Pressure tests](03-positioning/ai-replies/2-pressure-test.md) |
| 4 | Copy now names the occasion and the experience; the organiser pillar adds the guarantee; a V2 ad shows what you'd book | Cold blind reads saw a payment tool, guessed hen parties and found little to trust | [Blind reads](04-messaging/ai-replies/3-blind-read.md) |
| 5 | The honoured guest's share is split across paying guests and shown up front; Private celebration waits for hosts who can deliver it; Private session gets a host-set minimum; the premium is tested at the price guests pay, and the result sets the default tier; drop-out rules cover guests who pay and then leave | GPT-6 argued the tiers and premium weren't earned; Claude showed the split takes each guest from £56 to about £80; my own run through each tier found the pricing covered only guests who never pay | [Recommendation replies](05-pricing/ai-replies/1-recommendation.md) · [Drop-out rules](05-pricing/pricing-recommendation.md#what-each-guest-pays) |

**What this does not show:** every test is AI role-play or my own working, not customers, so it finds gaps but can't confirm demand; two models reading the same prompt aren't independent reviewers; Roamly's data belongs to the scenario, so every target here is unmeasured.

___

## Final presentation

[`final-presentation.html`](final-presentation.html) brings the five chapters into one page, with what I learned: where it was hardest, what I'll keep doing and the moment my thinking changed.

## Repo structure

```
roamly-gtm-strategy/
├── README.md                          ← this dashboard
├── PROMPTS.md                         ← every prompt, and how GPT-6 and Claude replied
├── CLAUDE.md                          ← my working rules for Claude Code
├── 01-gtm-strategy/
│   ├── gtm-strategy.md                ← M1: Discover Framework + motion    ★ Deliverable 1
│   ├── NOTES.md                       ← M1 notes and takeaways
│   └── ai-replies/                    ← both models' replies, word for word
├── 02-competitive-intel/
│   ├── battlecard-and-bet.md          ← M2: competitive battlecard + bet   ★ Deliverable 2
│   ├── NOTES.md                       ← M2 notes and takeaways
│   └── ai-replies/                    ← both models' replies, word for word
├── 03-positioning/
│   ├── positioning.md                 ← M3: positioning framework + statement ★ Deliverable 3
│   ├── NOTES.md                       ← M3 notes and takeaways
│   └── ai-replies/                    ← both models' replies, word for word
├── 04-messaging/
│   ├── messaging-pillars.md           ← M4: messaging pillars + copy        ★ Deliverable 4
│   ├── visual-asset-v2.png            ← M4: the Instagram ad (V2), built after the blind reads
│   ├── visual-asset-v2-labelled.png   ← the same ad, with its three layers labelled
│   ├── NOTES.md                       ← M4 notes and takeaways
│   └── ai-replies/                    ← both models' replies and visuals
├── 05-pricing/
│   ├── pricing-recommendation.md      ← M5: pricing model + recommendation  ★ Deliverable 5
│   ├── NOTES.md                       ← M5 notes and takeaways
│   └── ai-replies/                    ← both models' replies, word for word
└── final-presentation.html            ← M6: the five chapters in one page   ★ Deliverable 6
```
