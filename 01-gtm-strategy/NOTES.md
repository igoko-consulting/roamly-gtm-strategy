# Module 1 notes: Choose the GTM Motion and the Goal

Session 1, 3 Nov 2026. Sources: Module 1 slides, class notes and Lab Guide. Output: [gtm-strategy.md](gtm-strategy.md).

## The big idea

- **A strategy happens whether you choose it or not:** Sonos ran the textbook launch, with press build-up and a CEO keynote, but shipped an app its engineers had flagged as unready to meet a hardware date. It lost about $500M in market value and its CEO. Lovable grew through its users, who shared what they built, and reached 10M projects in 8 months. Missed: Sonos was a release-readiness failure as much as a GTM one. No launch plan rescues a broken product; only the willingness to delay it does.
- **Launch thesis:** before any plan, one defensible bet on who, why now and why you. Missed: a thesis is only defensible if you name what would disprove it, which is why the Roamly one-pager carries decision rules.

## Spotting a GTM opportunity

| Signal | What it means | Roamly Groups |
|---|---|---|
| Strong retention, stalled growth | Value is proven; the strategy isn't scaling it | Partly: repeat booking at 3× the industry average, growth not stated |
| An underserved segment | The market exists; nothing reaches it | Groups who can't book together |
| Behavioural data showing unmet demand | Users work around gaps | Yes: bookings across separate accounts, payments split by hand |
| A competitor winning your customers | Someone else is moving faster | Unknown: the brief names no competitor |

- **Opportunity, not a product or pricing problem in disguise:** many GTM strategies fail because the team solved the wrong problem. Missed: Roamly Groups is arguably a product gap first, since the workaround exists because a feature is missing. The GTM opportunity is the reach the feature opens, through the guests.

## The Discover Framework

| Step | Question it answers |
|---|---|
| 1 · Align on the Goal | Is the problem real, and does it matter to where the business is going? |
| 2 · Do the Research | Is there enough evidence of demand: user data, market size, willingness to pay? |
| 3 · Build a Team | Who needs to shape this, not just execute it: finance, analytics, sales, CS, marketing |
| 4 · Form a Hypothesis | What are we building, for whom, and which motion fits? |

- **Order matters:** the motion is chosen in step 4, from the evidence, not guessed at the start. Missed: in practice the org chart often decides the motion first. A company with a large sales team defaults to SLG, and the framework is most useful for exposing that default.
- **Spotify Premium Duo:** subscribers grew while ARPU fell for three years, so growth and monetisation were separate problems. Research found couples sharing one account and Family plans with empty slots. A cross-functional team sized the two-person market. Duo gave two accounts on one bill, priced between Individual and Family, with Duo Mix as a reason to exist beyond price, and a name that avoided assuming a relationship. The job to be done: both people keep their own music identity without paying twice. Missed: Duo risked Family plans downgrading. "Without cannibalising" was a hypothesis that needed a guardrail metric, the same role solo-booking guardrails play for Roamly.
- **Duolingo, the contrast:** 135M monthly actives, 9% paying, ARPU shifting for four years. It has the same symptom as Spotify, but possibly a different cause, so a new tier isn't the automatic answer. Missed: my first research cut would be by geography and cohort, to find where payers come from, before designing any tier.

## Choosing the motion

| Input | PLG | SLG | CLG |
|---|---|---|---|
| Time to value | Minutes | Weeks | Months |
| Buyer and user | Same person | Different people | Peer-influenced |
| Annual contract value | Low to mid | Mid to high | Low |
| Sales cycle | Self-serve | Human-led | Community-led |
| Scales via | Product virality | Sales headcount | Network effects |

- **A diagnostic, not a checklist:** the fit doesn't need to be perfect.
- **The PM's job differs by motion:** in PLG the product sells, so time to value, virality and upgrade loops have to be designed, not hoped for. In SLG the PM makes the product sellable: positioning, battlecards, win/loss loops and an ICP backed by data, with the trap of losing direct customer contact. In CLG the community is the distribution channel; returns are slow and hard to attribute, so it gets cut under quarterly pressure.
- **ICP, not persona:** who has the most acute pain, the budget and the authority to buy. Missed: in a consumer marketplace those can split. Roamly's organiser has the authority, but the guests hold most of the budget, so "budget" has to be read per seat.
- **Hybrids:** most scaled products run one primary motion and layer a second as they mature. PLG + SLG converts self-serve users into enterprise contracts (Cursor); PLG + CLG lets community drive discovery while the product converts (Canva); SLG + CLG lets partners extend reach beyond sales (HubSpot). Missed: running two motions from day one splits effort and muddies metrics, which is why CLG waits until stage 3 for Roamly Groups.

## A complete GTM strategy: four decisions

**1 · A goal that fits the motion.** Acquire reaches people before they've had value; Expand reaches those who have and are ready for more; Retain protects relationships at risk. Pick one.

| | Acquire | Expand | Retain |
|---|---|---|---|
| PLG | Natural fit | Requires intent | Works against it |
| SLG | Works against it | Natural fit | Natural fit |
| CLG | Natural fit | Works against it | Requires intent |

- Missed: "requires intent" isn't "wrong". PLG for Expand works when the in-product triggers are designed deliberately, which is what the Roamly channel plan does.

**2 · A specific audience.** For non-users: roles, industries or regions, and their current alternative. For existing users: active or lapsed, tenure, and use of the relevant features. A vague audience produces a strategy that resonates with no one.

**3 · Metrics committed before launch.**

| Motion | Leading indicator | Success signal | Warning signal |
|---|---|---|---|
| PLG | Time to first value, DAU/MAU | Free-to-paid conversion, PQLs | High signups, low activation |
| SLG | Sales-cycle length, pipeline coverage | NRR, MRR | High pipeline, low close rate |
| CLG | Referral rate, active community members | Advocate-sourced pipeline, referral signups | High engagement, low conversion |

- Missed: these are SaaS metrics. A transactional marketplace like Roamly has no free-to-paid step, so the PLG equivalents are booking completion and repeat booking.

**4 · An investment tier, scored on reach, impact and the risk of saying nothing.** Tier 1 gets a full strategy, Tier 2 a focused plan, Tier 3 a release. Treating every launch as Tier 1 exhausts the organisation and trains the audience to ignore you; defaulting to Tier 3 leaves value on the table.

## Labs

- **Discover Framework:** chose occasion groups (hen and stag parties, milestone birthdays), because the most acute pain and the authority to book sit with one person. Module 2 narrowed this to milestone celebrations, because specialists already sell per-guest payment to hen and stag groups.
- **V1 strategy:** PLG + CLG and Acquire went into the pressure test. GPT-6 and Claude, each as a sceptical CMO, both called Acquire the weakest input and asked whether payment friction was really commitment friction. I accepted Expand and a rule for unpaid shares, and pushed back on "prove it before you build": the product is built, so a staged launch is the faster test. Prompts and both models' replies compared: [PROMPTS.md](../PROMPTS.md); the replies, word for word: [ai-replies/](ai-replies/).
- **Infographic:** each model turned its one-pager into a visual ([GPT-6](ai-replies/3-infographic-gpt6.pdf) · [Claude](ai-replies/3-infographic-claude.pdf)). I chose Claude's for Slack because it matches the agreed motion and shows the gates. Missed: GPT-6's was the cleaner single image, and in a busy channel a visual that reads faster can matter more than a more complete one.
- **What AI cracked open:** I picked my goal from the motion table instead of my own evidence. Every signal came from existing users, yet I chose Acquire because PLG pairs with it. Missed: both models pushed the same way, and neither knew the product was built. Two models agreeing on the same thin prompt isn't independent evidence.

## What this means for Roamly Groups

- **Tier 1:** reach grows from multi-account users to every user and their guests; the impact is a new revenue line and an acquisition loop; saying nothing leaves users on the workaround. Missed: the staged launch can look like Tier 2. The tier sets the GTM investment, not how fast access widens.
- **No competitor signal yet:** the brief names none. Module 2 has to find who wins these groups today, even if it's WhatsApp and a bank transfer. Module 2 found it: GoHen for hen and stag groups, the status quo for milestone celebrations.
- **Segment evidence is the open risk:** the signals probably come from friend groups, not milestone celebrations. The occasion tag at group creation is how I'll find out.
