# GTM Strategy · Roamly Groups

## 1. Discover Framework

### Align on the Goal
- **Core business problem:** Groups want to book together on Roamly, but the product handles one traveller per account, so they coordinate across separate accounts, split payments by hand and drop off before paying. Roamly is losing bookings it already has the demand for.
- **What success looks like:** Groups complete bookings on Roamly instead of dropping off; invitees come back to book on their own accounts; hosts fill more seats per session; Roamly becomes where you plan a trip together, not only alone; solo ratings and repeat rates hold.

### Do the Research
- **Signals of a real opportunity:** Users raise it with support unprompted; they are already working around the gap across accounts, so the job is real; high drop-off shows demand failing at the point of payment; repeat booking at 3× the industry average shows the trust to try something new; hosts can already take groups.
- **Top 5 possible segments:** Occasion groups (hen and stag parties, milestone birthdays); friend groups of 4–8; families and multigenerational trips; corporate team offsites; community-led groups (travel clubs, creators, alumni).
- **How to size the opportunity:** From Roamly's data: sessions booked by several accounts within a short window, drop-off on those sessions, support ticket volume, and group size and spend per head against solo bookings. Externally: group travel market reports and a short survey of current users on group trips planned in the next 12 months. Host capacity per city caps what can be served.

### Build a Working Team
- **Cross-functional stakeholders:** Product, engineering, design, marketing, analytics, finance and customer support (who saw the signal first); payments, risk and legal for split payments; host operations for capacity and host terms.

### Form Your Hypothesis
- **Most valuable segment to target first, and why:** Milestone celebrations (big birthdays, anniversaries, reunions), narrowed in Module 2 from occasion groups that included hen and stag parties: the pain is most acute, with one organiser chasing money from 6–12 people against a fixed date, and that organiser chooses and books, so pain and buying authority sit with one person.
- **Core value proposition:** The organiser books one experience for the whole group, and everyone pays their own share and sees the same plan, so no one chases money or juggles accounts.

## 2. GTM motion
- **Chosen motion:** PLG for V1, adding community-led discovery (CLG) as a gated test in stage 3
- **Why:** The users with the problem are already on Roamly, time to value is minutes, the organiser books without talking to anyone and value per booking is low, so in-product prompts and lifecycle messages convert them at the point of intent; community seeding waits until stages 1–2 give real organiser stories to tell and the guest loop has shown it works.

## 3. Primary goal
**Expand.** The evidence comes from existing users: they already try to book in groups and drop off before paying. V1 moves those users onto Groups and measures completed group bookings against a holdout. Acquire is the secondary goal to prove: the share of guests who book on their own account within 90 days. PLG usually pairs with Acquire; here it serves expansion, because the users with the problem are already in the product.

## 4. The assumption I'm pushing back on
**That Roamly Groups needs proving before launch.** GPT-6 and Claude, both playing a sceptical CMO, said to diagnose abandoned group sessions before building. It is already built, and hosts can support it. Studying abandoned sessions after the fact is the slow way to learn why groups fail: Groups records every step (invite accepted, date agreed, share paid), so a staged launch to existing users who already show the multi-account pattern answers the money-versus-commitment question with better data, without disrupting solo booking.

I accepted the rest of the challenge: Expand as the primary goal, since the evidence comes from existing users, with guest acquisition as the secondary loop to prove; and a rule for who pays when a guest doesn't, set before launch.

Both models' replies, word for word: [pressure test](ai-replies/1-pressure-test.md) · [refinement](ai-replies/2-refinement.md).

## 5. V1 GTM strategy one-pager

**Thesis:** move existing users who already try to book in groups across separate accounts onto Roamly Groups through a staged in-product launch that lifts group completion and shows why groups fail. Expand first, prove the group experience, then Acquire.

| | V1 position |
|---|---|
| **Problem** | Group demand already on Roamly fails between invite and payment. Whether money or commitment kills it is not yet known; Groups' event tracking will show which. |
| **Goal** | Expand (primary): move existing multi-account groups onto Groups. Acquire (secondary): prove guests go on to book on their own accounts. |
| **Audience** | Stage 1: existing users showing the multi-account pattern (3+ accounts booking the same experience and date within a short window). Segment hypothesis: organisers of milestone celebrations for 6–12, checked by an occasion tag at group creation. |
| **Value proposition** | Book once for the whole group. Everyone pays their own share. You never chase anyone. |
| **Motion** | PLG in V1. Community-led discovery is a gated stage-3 test. |

**Before launch**
- **Unpaid-share rule (proposed V1 default):** each guest pays by a deadline set at booking; at the deadline the organiser covers unpaid shares or releases the seats; the host gets a confirmed headcount. Roamly does not underwrite unpaid shares in V1. The rule is shown to the organiser before inviting and to guests at payment. Needs payments, risk and legal sign-off.
- **Host terms:** opt-in to groups of 6–12, group cancellations and released seats, agreed with host ops.
- **Tracking:** every step live, from group created to booking confirmed, plus the occasion tag.
- **Baselines:** multi-account completion rate, solo conversion and host cancellation rate captured; holdout group set.

**Channel approach: owned channels only in V1**

| Channel | Role | Stage |
|---|---|---|
| In-product prompts | Convert at the point of intent: group size 3+ in search, a second account joining the same experience and date, "invite your group" at checkout | 1 |
| Lifecycle email and push | Users with the multi-account pattern in the last 12 months; abandoned group sessions | 1 |
| Guest surfaces | Invite, payment page and shared itinerary, each with a light path to an account and a post-trip "plan your own" prompt | 1 measured, 2 optimised |
| Customer support | Group-booking tickets routed to Groups and tagged | 1 |
| Community seeding | Birthday, anniversary and reunion planning communities, using organiser stories from stages 1–2 | 3, gated |

Out of V1: paid acquisition, influencers, corporate offsites and launch PR.

**Success metric**
- **North star:** group booking completion rate, the share of Groups sessions that reach a fully paid, confirmed booking, against the multi-account baseline and a holdout. Target set once the baseline is in.
- **Diagnostic funnel:** group created → invites accepted → date agreed → all shares paid → booking confirmed. The biggest drop at invites or date points to commitment; at payment, to money.
- **Loop metric:** share of guests who book on their own account within 90 days.
- **Guardrails:** solo conversion, ratings and repeat booking, host cancellation rate, payment failures and chargebacks, and support contacts per group booking.

**Launch plan**
- **Type:** closed beta, widening by stage. Timings and percentages are placeholders, like the X and Z targets, until baselines are in.
- **Stage 0, before launch:** gate on the unpaid-share rule signed, host terms agreed, tracking live and baselines captured.
- **Stage 1, closed beta (weeks 1–4):** 5–10% of eligible multi-account users in 1–2 cities with spare host capacity, the rest of the eligible users as the holdout; owned channels only. Gate: completion beats baseline and guardrails hold.
- **Stage 2, widen (weeks 5–10):** all eligible existing organisers, and group size in search for every user; fix the step where groups drop most. Gate: completion holds and an early read of the guest loop shows signal.
- **Stage 3, launch (week 11 on):** in-product promotion to all users and the community seeding test. The full 90-day guest-loop read follows as a checkpoint.
- **Enablement order:** leadership (metrics and a 30-day monitoring plan), then support (unpaid-share rule, FAQs, escalation path), then host ops (host terms), then marketing last, once positioning is locked.
- **Decision rules:** a commitment drop moves availability polling and headcount locking ahead of payment features; a money drop tunes the deadline, reminders and organiser cover; a guardrail breach pauses expansion; a flat guest loop means Groups is justified on recovered bookings alone.

**Open questions:** who owns go/no-go at each gate; which cities have host capacity for stage 1; what payment deadline hosts accept; whether seasonality distorts a 4-week read.

Both models' visual versions: [GPT-6](ai-replies/3-infographic-gpt6.pdf) · [Claude](ai-replies/3-infographic-claude.pdf).
