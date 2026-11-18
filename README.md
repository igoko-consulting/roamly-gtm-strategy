# Roamly Groups: Go-To-Market Strategy, by Martin Cook

> My final project for Product School's **Go-To-Market** certification. A complete go-to-market strategy for **Roamly Groups**: a new group-booking feature, built across six in-class labs, no homework required.

**How to read this repo:** each module folder holds its deliverable and a `NOTES.md` with the module's ideas and my takeaways. [PROMPTS.md](PROMPTS.md) keeps every lab prompt, run word for word in GPT-6 and Claude, and how the replies differed; each module's `ai-replies/` folder holds both models' replies as evidence. [CLAUDE.md](CLAUDE.md) holds the working rules I set for Claude Code, which I used to run the labs, check facts and keep the repo consistent.

---

## Deliverables at a glance

| # | Deliverable | Module | Status | File |
|---|---|---|---|---|
| 1 | **GTM Strategy** (Discover Framework + motion + V1 one-pager) | M1 | ✅ | [`01-gtm-strategy/gtm-strategy.md`](01-gtm-strategy/gtm-strategy.md) |
| 2 | **Competitive Intelligence & Strategic Bet** (battlecard) | M2 | ✅ | [`02-competitive-intel/battlecard-and-bet.md`](02-competitive-intel/battlecard-and-bet.md) |
| 3 | **Positioning Statement** (framework + statement) | M3 | ✅ | [`03-positioning/positioning.md`](03-positioning/positioning.md) |
| 4 | **Messaging Pillars** | M4 | ✅ | [`04-messaging/messaging-pillars.md`](04-messaging/messaging-pillars.md) |
| 5 | **Pricing Recommendation** | M5 | ✅ | [`05-pricing/pricing-recommendation.md`](05-pricing/pricing-recommendation.md) |
| 6 | **Final Presentation** (your five deliverables + a reflection on the course) | M6 | ☐ | `final-presentation.html`, downloaded from the Final Project Deliverables Builder |

## The strategy in one sentence

A vetted local host who welcomes the group, and everyone pays their own share: Roamly Groups is for organisers of milestone celebrations, and the bet is Expand first, then Acquire through the guests.

## How the strategy changed

Each module tested an earlier answer, and all five changed one. Every change was carried back through the earlier modules in the same commit.

| Module | What changed | Why | Evidence |
|---|---|---|---|
| 1 | Primary goal from Acquire to Expand, with Acquire second, through the guests | Both models, as a sceptical CMO, pointed out that every signal came from existing users | [Pressure test](01-gtm-strategy/ai-replies/1-pressure-test.md) |
| 2 | Segment narrowed from occasion groups (hen, stag, milestone birthdays) to milestone celebrations | The battlecard showed a specialist already sells per-guest payment to hen and stag groups; the marketplaces milestone groups use don't | [Battlecard and bet](02-competitive-intel/battlecard-and-bet.md) |
| 3 | Positioning rebuilt around hosts who welcome groups | Playing Airbnb, both models said they could reuse the first draft; host opt-in, my "Despite" turned round, was the part they couldn't copy | [Pressure tests](03-positioning/ai-replies/2-pressure-test.md) |
| 4 | Copy now names the occasion and the experience; the organiser pillar adds the guarantee; a V2 ad shows what you'd book | Cold blind reads saw a payment tool, guessed hen parties and found little to trust | [Blind reads](04-messaging/ai-replies/3-blind-read.md) |
| 5 | The honoured guest's share, open since Module 3, is split across the paying guests and shown up front; Private celebration waits until hosts can deliver it; the assumption is tested at the price guests actually pay | GPT-6 argued the tiers and the premium weren't earned; Claude found the split lifts each guest's price to about £80 at a £56 usual price | [Recommendation replies](05-pricing/ai-replies/1-recommendation.md) |

___

## How to submit

- In Module 6, generate your presentation in the **[Final Project Deliverables Builder](https://product-school-platform.github.io/ps-content-library/certifications/gtmc/2026.1/Modules/Final%20Project%20Deliverables%20Builder.html)**. It pulls your deliverables from this repo, then you add your reflection and download `final-presentation.html`. Commit it to the root of this repo.
- You have 7 days from the day your cohort ends to submit your presentation and the link to this repo on the learning platform.

## Repo structure

```
roamly-gtm-strategy/
├── README.md                          ← this dashboard
├── PROMPTS.md                         ← every lab prompt, and how GPT-6 and Claude replied
├── CLAUDE.md                          ← my working rules for Claude Code
├── 01-gtm-strategy/
│   ├── gtm-strategy.md                ← M1: Discover Framework + motion    ★ Deliverable 1
│   ├── NOTES.md                       ← M1 class notes and takeaways
│   └── ai-replies/                    ← both models' replies, word for word
├── 02-competitive-intel/
│   ├── battlecard-and-bet.md          ← M2: competitive battlecard + bet   ★ Deliverable 2
│   ├── NOTES.md                       ← M2 class notes and takeaways
│   └── ai-replies/                    ← both models' replies, word for word
├── 03-positioning/
│   ├── positioning.md                 ← M3: positioning framework + stmt    ★ Deliverable 3
│   ├── NOTES.md                       ← M3 class notes and takeaways
│   └── ai-replies/                    ← both models' replies, word for word
├── 04-messaging/
│   ├── messaging-pillars.md           ← M4: messaging pillars + copy        ★ Deliverable 4
│   ├── visual-asset-v2.png            ← M4: the Instagram ad, ready to post
│   ├── visual-asset-v2-labelled.png   ← the same ad, with its three layers labelled
│   ├── NOTES.md                       ← M4 class notes and takeaways
│   └── ai-replies/                    ← both models' replies and visuals
├── 05-pricing/
│   ├── pricing-recommendation.md      ← M5: pricing model + recommendation  ★ Deliverable 5
│   └── ai-replies/                    ← both models' replies, word for word
└── final-presentation.html            ← M6: your final presentation         ★ Deliverable 6
```
