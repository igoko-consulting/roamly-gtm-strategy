# Refinement: both replies

> My [pushback and the refinement prompt](../../PROMPTS.md#2-refinement--same-chat-as-each-pressure-test), sent word for word to each model in the same chat as its [pressure test](1-pressure-test.md) on 3 Nov 2026. Each model's words are unchanged; headings, lists and tables are restored where copying from the chat flattened them. The comparison and the merge into section 5 of the deliverable are in [PROMPTS.md](../../PROMPTS.md#2-refinement--same-chat-as-each-pressure-test).

**Jump to:** [GPT-6](#gpt-6) · [Claude](#claude)

---

## GPT-6

Your pushback changes the recommendation materially. I would withdraw the suggestion that Roamly Groups needs further product validation before launch.

The distinction is now product readiness versus commercial validation. The product is built and hosts can support it. What remains unproven is which customer behaviours drive successful group bookings and whether those bookings generate incremental acquisition.

I’d retain your staged-launch approach, with one refinement: instrumented behaviour tells you where groups disengage; a small amount of targeted qualitative research helps explain why.

### Roamly Groups — V1 GTM Strategy

Roamly Groups: Go-to-Market Strategy — V1

**Strategic objective**

Expand revenue from Roamly’s existing customer base by converting group demand that currently fails at booking. Establish guest acquisition as a secondary growth opportunity through invitations and subsequent independent bookings.

**1. Problem and opportunity**

Groups already want to book experiences on Roamly, but the individual-account booking model creates friction around coordination, payment and commitment. Organisers work around these limitations using multiple accounts and manual payment collection, with bookings frequently abandoned.

Roamly Groups removes this friction through coordinated booking, split payments and shared itinerary planning.

The opportunity is to recover existing demand first, then turn successful group experiences into a repeatable acquisition channel.

**2. Target segment**

Beachhead: Occasion groups (6–12 people).

Hen and stag parties, milestone birthdays and similar occasions.

- Buyer: The organiser, who selects the experience and coordinates the booking.
- Users: Guests who confirm participation, pay their share and follow the shared itinerary.
- Pain: Coordinating availability, collecting money and securing commitment ahead of a fixed date.
- Why start here: Clear organising authority, defined deadlines and acute coordination requirements.

**3. Value proposition**

Organise one experience for the whole group, let everyone pay their share and keep the booking and itinerary in one place. No chasing payments, juggling accounts or managing separate arrangements.

**4. GTM motion and channels**

Primary motion: Product-Led Growth (PLG). Secondary: Community-Led Growth (CLG).

| Channel | Approach | Priority |
|---|---|---|
| In-product discovery | Identify existing users exhibiting multi-account booking behaviour. Introduce Groups through contextual prompts and targeted invitations. | Primary |
| CRM / lifecycle | Target existing organisers with relevant booking history. Use email and notifications to introduce group booking and encourage activation. | Primary |
| Guest invitation loop | Every group booking introduces Roamly to 5–11 potential new customers through invitations, payment links and shared itineraries. | Secondary growth loop |
| Travel communities | Test partnerships and organic discovery through wedding, hen, birthday and travel-planning communities. | Experimental |

The product should convert existing demand. Community channels should expand discovery, rather than become a dependency for launch.

**5. Launch approach**

Stage 1 — Controlled launch

Release to existing customers showing multi-account booking behaviour.

- Establish a baseline and, where practical, a comparable holdout group.
- Monitor the complete group journey: invitation accepted, date agreed, share paid and booking completed.
- Identify where groups disengage and use targeted feedback to understand why.
- Establish the payment default and liability rules before launch, particularly who is responsible when a guest does not pay.

Stage 2 — Optimise

Use behavioural evidence to improve invitation acceptance, group commitment and payment completion. Validate the strongest occasion-group use cases and host capacity.

Stage 3 — Expand

Broaden availability to additional customer segments and test community acquisition. Evaluate whether invited guests become independent Roamly customers.

**6. Success measures**

Primary metric: Incremental completed group bookings per eligible existing organiser.

Measure the change against a comparable holdout group over a defined period (initially 30 days).

Supporting metrics:

- Group booking completion rate.
- Invitation acceptance and date-agreement rates.
- Percentage of guests paying their share.
- Incremental revenue and group spend per booking.
- Percentage of invited guests making an independent subsequent booking.

Guardrails: Solo booking conversion, ratings and repeat booking rates must remain stable.

**7. Strategic assumptions to validate**

1. Existing multi-account behaviour identifies customers with genuine group-booking demand.
2. Split payments and shared coordination materially improve booking completion.
3. Occasion groups provide a commercially attractive initial segment.
4. Successful group bookings generate incremental guest acquisition.

Strategic principle: Expand existing customer value first. Use the group invitation loop to establish acquisition as the next source of growth.

### My three recommendations for refining V1

There are three decisions I’d make particularly carefully.

**1. Make the launch cohort behaviour-based, not demographic-based.**

Target existing users who exhibit multi-account booking patterns. This gives you a much stronger starting point than targeting everyone organising a hen party or birthday.

It also makes the initial experiment more commercially defensible.

**2. Distinguish funnel measurement from causal understanding.**

Your event instrumentation is a significant advantage.

| Event | What it tells you |
|---|---|
| Invite accepted | Guests are interested |
| Date agreed | The group has reached a coordination decision |
| Share paid | Financial commitment exists |
| Booking completed | Demand has converted |

However, an abandoned booking between date agreement and payment doesn’t necessarily mean payment is the problem. A short, contextual feedback prompt can help establish why.

**3. Be disciplined about the primary success metric.**

I’d resist using invitation acceptance or new account creation as your headline success metric.

The commercial objective is incremental completed bookings, not invitations sent.

The holdout comparison is important: some of these customers might have completed bookings anyway. You want to measure what Groups actually adds.

### My overall assessment

I’d now position the strategy as:

Expand → Prove the group experience → Acquire.

This is stronger than the original Acquire-first proposition because it follows the evidence Roamly already has, uses the product’s instrumentation to learn quickly and creates a natural path towards acquisition.

One particularly important point: protecting the existing solo experience is a launch requirement, not simply a later optimisation.

That gives you a clear commercial thesis, a controlled route to market and measurable criteria for expanding beyond the initial cohort.

---

## Claude

### Roamly Groups — V1 GTM Strategy (Draft)

3 Nov 2026 · @Martin

**Summary**

V1 moves existing users who already book in groups across separate accounts onto Roamly Groups, through a staged in-product launch that lifts group completion and shows why groups fail.

- Problem: group demand already on Roamly fails between invite and payment. We don't yet know whether money or commitment kills it.
- Goal: Expand (primary): convert existing multi-account groups to Groups. Acquire (secondary): prove the guest-to-booker loop.
- Motion: PLG only in V1, with in-product and lifecycle channels. Community-led discovery is a stage-3 test, gated on results.

**Refined strategic inputs**

Four inputs change and three are tightened. The rest of the Discover answers stand.

| Input | Refined position | Change |
|---|---|---|
| Business problem | Group demand already on Roamly fails between invite and payment. Groups records each step, so a staged launch shows whether money or commitment causes the failure. | Tightened |
| Primary goal | Expand: move existing multi-account groups onto Groups. Secondary: Acquire, proving the guest loop. | Changed from Acquire |
| Target segment | V1 audience: existing users with the multi-account pattern (3+ accounts booking the same experience and date within a short window). Hypothesis segment: occasion organisers of 6-12, validated by an occasion tag captured at group creation. | Split into audience and hypothesis |
| Value proposition | "Book once for the whole group. Everyone pays their own share. You never chase anyone." Backed by a published rule for unpaid shares. | Sharpened to the organiser's outcome |
| GTM motion | PLG only in V1. Community-led discovery moves to stage 3 as a gated test. | CLG deferred |
| Signals | Drop "3x repeat rate shows trust to try something new". Use it only to show the solo base carries low switching risk. | Reframed |
| Segments | Remove corporate offsites from V1 (different buyer, invoicing, sales-led). | Cut |
| Sizing | Lead with monthly GMV lost in abandoned multi-account sessions. Survey informs messaging only. | Reordered |
| Success | Numeric north star, loop metric and guardrails (see Success metric). Drop "where you plan a trip together" as a success measure. | Made measurable |

**Pre-launch decisions**

Three decisions gate stage 1. The unpaid-share rule is the long pole and needs payments, risk, legal and host ops to sign off.

Proposed rule for unpaid shares (V1 default, for sign-off):

1. Each guest's share is due by a payment deadline set at booking (for example, X days before the experience).
2. At the deadline, the organiser chooses to cover the unpaid shares or release those seats.
3. The host receives a confirmed headcount at the deadline. Roamly does not underwrite unpaid shares in V1.
4. The rule is shown to the organiser before they invite and to guests on the payment page.

- [ ] Unpaid-share rule signed off (payments, risk, legal)
- [ ] Host terms for group cancellations and seat releases agreed (host ops)
- [ ] Event tracking live for every step: group created, invite sent, invite accepted, date agreed, share paid, booking confirmed, plus occasion tag
- [ ] Baselines captured for multi-account completion rate, solo conversion and host cancellation rate
- [ ] Kill criteria agreed (see Decision rules)

**Staged launch plan**

V1 launches to existing multi-account users first and widens only when a gate's criteria are met. Solo booking stays untouched throughout.

_[A diagram in the original, "Each stage widens only when its gate is met", transcribed from Claude's doc. The same diagram appears in its infographic, [3-infographic-claude.pdf](3-infographic-claude.pdf), page 2.]_

| Stage | When | What happens |
|---|---|---|
| Pre-launch | Stage 0 · prep | Unpaid-share rule; host terms agreed; tracking and baselines live |
| Pilot | Stage 1 · weeks 1-4 | 5-10% of eligible users, 1-2 cities; in-product and CRM; guest loop measured |
| Expand | Stage 2 · weeks 5-10 | All eligible users; group size in search for every user; guest prompts tuned |
| Community test | Stage 3 · week 11+ | Seed occasion planning communities; organiser stories from stages 1-2 |

| Gate | Criteria |
|---|---|
| Gate 1: ready | Rule signed, tracking live, baselines captured |
| Gate 2: scale | Completion beats baseline, guardrails hold |
| Gate 3: widen | Completion holds and guest loop shows signal |

Stage 1 is the pilot that settles money versus commitment. Stage durations are proposals to test against host capacity and seasonality.

**Channel approach**

V1 uses owned channels only: users with the problem are already on Roamly, so paid reach adds cost before the mechanism is proven.

| Channel | Role | Trigger or placement | Stage |
|---|---|---|---|
| In-product prompts (primary) | Convert at the point of intent | Group size of 3+ in search; a second account joining the same experience and date; "invite your group" after an organiser starts checkout | 1 |
| Lifecycle CRM (email and push) | Re-engage known multi-account users | Users with the pattern in the last 12 months; abandoned multi-account sessions | 1 |
| Guest surfaces | Run the acquisition loop | Invite, share-payment page and shared itinerary, each with a light path to create an account and a post-trip "plan your own" prompt | 1 (measured), 2 (optimised) |
| Customer support | Route the original signal | Support macro pointing group-booking tickets to Groups; tag tickets for the feedback loop | 1 |
| Community seeding | Test discovery beyond the base | Hen, wedding and birthday planning communities, with organiser stories from stages 1-2 | 3, gated |

Out of V1: paid acquisition, influencer partnerships, corporate offsites and broad launch PR.

**Success metric**

North star: group booking completion rate. This is the share of Groups sessions created that reach a fully paid, confirmed booking, measured against the multi-account baseline. Target: baseline + X points by the end of stage 2 (set once the baseline is captured).

Diagnostic funnel. Each step's drop-off shows whether money or commitment causes the failure:

1. Group created
2. Invites accepted (headcount commitment)
3. Date agreed (availability commitment)
4. All shares paid by the deadline (money)
5. Booking confirmed

Secondary loop metric: % of guests who book on their own account within 90 days of their group trip.

Guardrails (hold within ±Z% of baseline):

- Solo conversion rate and solo ratings
- Host cancellation rate on group bookings
- Payment failures and chargebacks per group booking
- Support contacts per group booking

**Decision rules and open questions**

The funnel decides the next investment. Each outcome maps to a predefined move.

| If the data shows | Then |
|---|---|
| Completion beats baseline by X points and guardrails hold | Move to the next stage |
| Biggest drop at invites accepted or date agreed (commitment) | Prioritise availability polling and headcount locking ahead of payment features |
| Biggest drop at shares paid (money) | Tune the deadline, reminders and the organiser cover option |
| A guardrail breaches | Pause expansion, fix, then re-test at the same stage |
| Guest-to-own-booking is flat after 90 days | Reframe Acquire as unproven and justify Groups on recovered GMV alone |
| Occasion tag shows organisers are not the main users | Re-target V1 messaging to the segment the data shows |

Open questions

- [ ] Who owns the go/no-go call at each gate?
- [ ] Which cities have enough host capacity for stage 1?
- [ ] What payment deadline do hosts accept (X days before the experience)?
- [ ] Is seasonality strong enough (hen and stag peaks) to distort a 4-week stage-1 read?
