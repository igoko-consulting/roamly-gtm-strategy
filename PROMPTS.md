# Prompts

Every lab prompt I ran, word for word. Each one went to Claude and GPT-6 in fresh chats, identical in both, so the replies can be compared. Follow-up prompts ran in the same chat as the prompt before them.

- **Why two models:** it's how I work in practice. A second model is a cheap second reviewer: where both agree, the point carries more weight; where they differ, I look harder before deciding. Missed: two models reading the same prompt aren't fully independent, so agreement is a signal, not proof.
- **Evidence:** every reply is kept word for word in each module's `ai-replies/` folder, linked under each step, so each comparison below can be checked against its source.

---

## Module 1 · GTM strategy

### 1. Pressure test

```text
I am a Senior Product Manager at Roamly. I am developing a GTM strategy for Roamly Groups, a new feature enabling coordinated group booking, split payments and shared itinerary planning.

Here are my Discover Framework answers and strategic inputs:
- Business problem: Groups want to book together on Roamly, but the product handles one traveller per account, so they coordinate across separate accounts, split payments by hand and drop off before paying. Roamly is losing bookings it already has the demand for.
- What success looks like: Groups complete bookings on Roamly instead of dropping off; invitees come back to book on their own accounts; hosts fill more seats per session; Roamly becomes where you plan a trip together, not only alone; solo ratings and repeat rates hold.
- Signals of a real opportunity: Users raise it with support unprompted; they are already working around the gap across accounts, so the job is real; high drop-off shows demand failing at the point of payment; repeat booking at 3x the industry average shows the trust to try something new; hosts can already take groups.
- Segments I considered: Occasion groups (hen and stag parties, milestone birthdays); friend groups of 4-8; families and multigenerational trips; corporate team offsites; community-led groups (travel clubs, creators, alumni).
- How I'd size the opportunity: From Roamly's data: sessions booked by several accounts within a short window, drop-off on those sessions, support ticket volume, and group size and spend per head against solo bookings. Externally: group travel market reports and a short survey of current users on group trips planned in the next 12 months. Host capacity per city caps what can be served.
- Stakeholders I'd involve: Product, engineering, design, marketing, analytics, finance and customer support (who saw the signal first); payments, risk and legal for split payments; host operations for capacity and host terms.
- Target segment: Organisers of occasion trips (hen and stag parties, milestone birthdays) for groups of 6-12. Acute pain: one person chases money from everyone, juggles separate accounts and syncs availability against a fixed date, and the booking often falls through. Buying authority: the organiser chooses the experience and books it; guests pay their share but rarely choose.
- Value proposition: The organiser books one experience for the whole group, and everyone pays their own share and sees the same plan, so no one chases money or juggles accounts.
- GTM motion: Hybrid, PLG primary and CLG secondary. Time to value is minutes, the organiser books without talking to anyone, value per booking is low, and every booking puts Roamly in front of 5-11 guests, so the product does the converting; occasion planners gather in hen, wedding and birthday planning communities, and Roamly's users already find it through travel communities, so community drives discovery.
- Primary goal: Acquire

Play the role of a skeptical CMO who has reviewed dozens of GTM plans. Tell me: (1) which of my inputs is the weakest and why, (2) the assumption I am most likely not seeing because I am too close to it, and (3) what you would cut or sharpen. Be direct.
```

**How the two replies compared** · both replies, word for word: [1-pressure-test.md](01-gtm-strategy/ai-replies/1-pressure-test.md)

| Point | GPT-6 | Claude |
|---|---|---|
| Weakest input | Acquire: the evidence is from existing users; make Expand primary, Acquire secondary | Acquire: my own problem statement describes a conversion leak; make "Convert" primary, Acquire secondary |
| Blind spot | Payment friction may really be commitment or coordination friction | Same, plus: who pays when guest 9 of 12 doesn't? That answer is the product |
| Cut or sharpen | Fewer success metrics; 3x repeat rate shows loyalty, not demand; CLG experimental | Cut corporate offsites and CLG for v1; lead with lost GMV; occasion organisers book rarely, so the case rests on the guest loop |
| Verdict | Approve discovery, not the strategy | Test before you build |

- **They agreed on everything material.** Claude went further on the payment shortfall, the segment evidence and lifetime value.
- **Both missed that the product is built.** The prompt doesn't say so, and both pushed for discovery before build.

### 2. Refinement · same chat as each pressure test

```text
Here is my pushback on one of your assumptions: You assume Roamly Groups still needs proving before launch. It doesn't: it's built and hosts can support it. I accept Expand as the primary goal, with guest acquisition as the secondary loop to prove, and I accept that the rule for who pays when a guest doesn't must be set before launch. But studying abandoned sessions after the fact is the slow way to learn why groups fail. Groups records every step (invite accepted, date agreed, share paid), so a staged launch to existing users who already show the multi-account pattern answers the money-versus-commitment question with better data, without disrupting solo booking.

Based on this, refine my strategic inputs and generate a V1 GTM strategy one-pager that includes: a recommended channel approach and a suggested success metric for this motion. Keep it concise and actionable. This is a first draft I will refine over the coming weeks.
```

**How the two one-pagers compared** · both replies, word for word: [2-refinement.md](01-gtm-strategy/ai-replies/2-refinement.md)

| Point | GPT-6 | Claude |
|---|---|---|
| Accepted the pushback | Yes: product readiness versus commercial validation | Yes: a staged launch settles money versus commitment |
| Launch audience | By behaviour (multi-account users), not demographics | Same, defined as 3+ accounts on the same experience and date; occasion tag tests the segment |
| Primary metric | Incremental completed group bookings per organiser, against a holdout | Group booking completion rate, against the multi-account baseline |
| Motion | PLG, CLG still called secondary but run as an experiment | PLG only in V1; CLG a gated stage-3 test |
| Unpaid shares | Named as a rule to set | Proposed one: payment deadline, organiser covers or releases seats, Roamly doesn't underwrite |
| Launch gates | Three stages, no timings or gates | Four stages with timings and three gates, a pre-launch checklist, and decision rules per funnel outcome |

- **Claude's was the stronger base.** It made every decision the CMO had asked for. GPT-6 added the holdout, which measures what Groups adds rather than what would have happened anyway.
- **Section 5 of the deliverable merges the two:** Claude's structure, unpaid-share rule, channels and decision rules, with GPT-6's holdout and "Expand, prove the group experience, then Acquire".

### 3. Infographic · same chat as each refinement

```text
Now take the GTM strategy one-pager you just created and turn it into a clean, visual one-page summary I can share with my team. Use clear sections, short punchy headers, and make it scannable. Format it as if it were a real internal strategy document.
```

**How the two infographics compared** · both, as delivered: [GPT-6 (PDF)](01-gtm-strategy/ai-replies/3-infographic-gpt6.pdf) · [Claude (PDF export of the Claude Docs page)](01-gtm-strategy/ai-replies/3-infographic-claude.pdf)

| Point | GPT-6 (one-page PDF) | Claude (Claude Docs page with two diagrams) |
|---|---|---|
| Headline | "Expand, prove, acquire" as a three-step strip | "Win back group demand we already have, then let guests spread it", over six cards |
| Motion | Labels CLG "secondary", then calls communities "experimental" | Product-led; community a gated stage-3 test, as agreed |
| Launch | Three steps, no timings or gates | Four stages with timings (pilot weeks 1–4 at 5–10% of eligible users in 1–2 cities; widen weeks 5–10; community from week 11) and three gates |
| North star | Incremental completed group bookings per eligible organiser, against a holdout, over 30 days | Group booking completion rate, against the multi-account baseline |
| Guardrails | Solo conversion, ratings and repeat booking | Solo, host, payment and support health |
| Open decisions | Unpaid-share rule named as a must-have, not decided | Five decisions with owners and proposals |

- **GPT-6's is the better single image:** one page, scannable, and the three-step strip carries the thesis at a glance. It reverts to "CLG secondary", which contradicts the agreed motion.
- **Claude's is the better plan:** it is the only one with stage timings and gates, the same rollout as its one-pager. Gate 3 asks only for an early guest-loop signal by week 11, before a 90-day read is possible.
- **Neither filled the X and Z targets.** Both still need Roamly's baseline data.
