# Prompts

Every lab prompt I ran, word for word. Each one went to GPT-6 and Claude in new chats, identical in both, so the replies can be compared. Follow-up prompts ran in the same chat as the prompt before them. From Module 3 the chats keep no memory (ChatGPT's Temporary Chat, Claude's incognito chat), because both models' Module 2 replies drew on earlier chats.

- **Why two models:** it's how I work in practice. A second model is a cheap second reviewer: where both agree, the point carries more weight; where they differ, I look harder before deciding. Missed: two models reading the same prompt aren't fully independent, so agreement is a signal, not proof.
- **Evidence:** every reply is kept word for word in each module's `ai-replies/` folder, linked under each step, so each comparison below can be checked against its source.

**Contents**

- [Module 1 · GTM strategy](#module-1--gtm-strategy): [1. Pressure test](#1-pressure-test) · [2. Refinement](#2-refinement--same-chat-as-each-pressure-test) · [3. Infographic](#3-infographic--same-chat-as-each-refinement)
- [Module 2 · Battlecard and bet](#module-2--battlecard-and-bet): [1. Research](#1-research) · [2. Battlecard](#2-battlecard--same-chat-as-each-research-reply) · [3. Corrections](#3-corrections--same-chat-as-each-battlecard) · [4. Clean-up](#4-clean-up--same-chat-as-each-correction)
- [Module 3 · Positioning](#module-3--positioning): [1. Generation](#1-generation) · [2. Pressure test](#2-pressure-test--same-chat-as-each-statement) · [3. Stranger clarity](#3-stranger-clarity--same-chat-as-each-pressure-test) · [4. Audience recognition](#4-audience-recognition--same-chat-as-each-stranger-test)
- [Module 4 · Messaging](#module-4--messaging): [1. Copy generation](#1-copy-generation) · [2. Visual asset](#2-visual-asset--same-chat-as-each-set-of-copy) · [3. Blind read](#3-blind-read--new-memory-off-chats-the-image-attached)
- [Module 5 · Pricing recommendation](#module-5--pricing-recommendation): [1. Recommendation](#1-recommendation)

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

---

## Module 2 · Battlecard and bet

### 1. Research

```text
I am a Senior Product Manager at Roamly, a platform that connects travelers to curated local experiences hosted by vetted local experts across 40 cities. We are launching Roamly Groups, a new feature enabling coordinated group booking, split payments and shared itinerary planning.

My target segment is: Occasion groups (hen and stag parties, milestone birthdays): the pain is most acute, with one organiser chasing money from 6–12 people against a fixed date, and that organiser chooses and books, so pain and buying authority sit with one person.
My value proposition for them is: The organiser books one experience for the whole group, and everyone pays their own share and sees the same plan, so no one chases money or juggles accounts.

Identify my top 3 competitors, including at least one I might not have considered, and for each, tell me: who they primarily serve, how they position themselves, where they win, and where they are most vulnerable.

Also tell me what the status quo alternative is for a buyer who chooses none of them.
```

**How the two replies compared** · both replies, word for word: [1-research.md](02-competitive-intel/ai-replies/1-research.md)

| Point | GPT-6 | Claude |
|---|---|---|
| The one I hadn't considered | GoHen and StagWeb, hen and stag specialists, "now under Funktion Leisure" | GoHen, under "Groupia" |
| The other two | The Stag Company; Airbnb Experiences | Airbnb Experiences; GetYourGuide and Viator |
| Status quo | WhatsApp, spreadsheets and bank transfers; Splitwise settles up but doesn't book | The same, plus the organiser carries any dropouts; most of Roamly's drop-off probably goes here |
| Main challenge | "Everyone pays their own share" is a feature, not a differentiator | Split payment is table stakes; the edge is curated hosts, booked self-serve in minutes |
| Fast follower | Not named | Airbnb, with Tripadvisor supply on the way |

**Checked against live sources, 5 Nov 2026:**

- **GoHen's owner:** GPT-6 was right. Groupia went into administration in June 2026, and Funktion Leisure bought GoHen and StagWeb out of it ([Funktion](https://www.funktionevents.co.uk/hen-party/blog/funktion-leisure-acquires-gohen-stagweb), [Travel Weekly](https://travelweekly.co.uk/all-content/stag-and-hen-tour-operator-bought-out-of-adm)). Claude named the failed owner. Neither said that Funktion Events, the buyer, also sells hen and stag trips where "everyone pays their own share".
- **GoHen's payments:** guests pay GoHen directly, from a £25 deposit, and an app tracks who has paid; packages start at £59 a head. GoHen is ABTA-protected, not ABTOT as Claude said ([GoHen](https://www.gohen.com/)).
- **The Stag Company:** a £50 deposit secures the group, then each guest pays at least £30 within 14 days through the Party Hub, with the balance due 42 days before ([FAQ](https://static.thestagcompany.com/frequently-asked-questions)).
- **Airbnb:** I found no per-guest payment for Experiences. The Tripadvisor partnership was announced on 11 August 2026 and launches later this year ([Tripadvisor](https://tripadvisor.mediaroom.com/2026-08-11-Tripadvisor-Group-and-Airbnb-Announce-Experiences-Partnership)). Claude's "new shared itinerary feature" is unverified.
- **GetYourGuide and Viator:** "Holiday Hero or Zero" was a UK campaign in summer 2026 aimed at the group's organiser ([Creative Salon](https://creative.salon/articles/work/getyourguide-holiday-hero-or-zero-ace-of-hearts)). Viator became Gemini's first connected app for travel experiences on 30 July 2026 ([Tripadvisor](https://tripadvisor.mediaroom.com/2026-07-30-Viator-Becomes-Googles-First-Connected-App-for-Travel-Experiences)).

- **They agreed on what matters:** specialists already sell my value proposition to my segment, so split payment is the entry ticket, not the edge, and the status quo is where most drop-off goes.
- **Claude's was the more useful research:** it found GoHen's rule for unpaid places, GetYourGuide's campaign aimed at the organiser, and Airbnb's new supply. GPT-6 got the ownership right and had the clearer capability table.
- **Neither reply is context-free:** GPT-6 quoted my "Expand, Prove, Acquire" sequence and the multi-account pattern, which aren't in the prompt. Claude's mentions of Roamly's drop-off and an unset rule for unpaid shares suggest it drew on earlier chats too.

### 2. Battlecard · same chat as each research reply

```text
Using the research above, generate a competitive battlecard for GoHen with the following sections and components:

Know the Landscape: Competitor Overview, Key Offerings, Pricing
Understand the Battlefield: Key Strengths, Key Weaknesses
Win the Deal: Why You Win, Why They Win, Why You
Handle the Hard Moments: Quick Dismiss, Landmine Questions, Objection Handling

Be direct and specific. Where Roamly loses, say so honestly. Where it wins, explain why the advantage is defensible.
```

**How the two battlecards compared** · both, word for word: [2-battlecard.md](02-competitive-intel/ai-replies/2-battlecard.md)

| Point | GPT-6 | Claude (a Claude Docs page) |
|---|---|---|
| Why they win | When the organiser wants a whole weekend, human help or flexible instalments: GoHen's strengths, framed as the buyer's choice | Whole weekend, financial protection, proven payment rules, a human planner, the category brand: framed as Roamly's gaps, "We lose these deals today" |
| Why we win | Curated local experts, starting from one experience, discovery and payment in one flow | The same, plus guests who come back and booking one experience onto a trip already planned |
| Landmine questions | Six, plus the best one: "If you've already solved collecting everyone's money, what's still the hardest part?" | Five, plus where not to set one: payment certainty, protection and human support |
| Pricing | £59, £69 and £229 a head from GoHen's site; a £50 deposit | A £50 deposit from the organiser and £50 a head from guests; no package prices |
| Open item | None | The protection and non-payer answers wait on the unpaid-share rule |

**Checked against GoHen's site, 5 Nov 2026:** the organiser pays one small deposit (the homepage shows £25) and each guest pays their own within four weeks ([how payments work](https://www.gohen.com/planning-tips/how-do-payments-work.asp)). Neither model's £50 appears there, and the site doesn't say what happens to a guest who doesn't pay, so Claude's "unpaid places released" is unverified. Claude still has the old owner, Groupia, and ABTOT bonding; GoHen is now Funktion Leisure's and states ABTA.

- **Claude's is the more honest card:** its "Why they win" names what Roamly lacks, which is what the lab asks for. GPT-6's reads as GoHen's sales strengths.
- **GPT-6 adds the best single question:** "what's still the hardest part?" moves the talk off payments, the feature GoHen already has.
- **Both missed two uncomfortable points:** whether Roamly's hosts want hen and stag groups at all, and whether Roamly's 40 cities include the towns where hen weekends happen.

### 3. Corrections · same chat as each battlecard

My tweaks before the clean-up, as the Lab Guide asks: the facts the checks above corrected, the two missed points, and GPT-6's best landmine question. I chose Claude's card as the base.

```text
Before we format it, correct and add to the battlecard:

- Ownership: Groupia went into administration in June 2026, and Funktion Leisure bought GoHen and StagWeb out of it. GoHen states ABTA protection, not ABTOT.
- Pricing: GoHen's site shows packages from £59 a head (Liverpool) to £229 (HenFest). The organiser pays one small deposit (the homepage shows £25), and each guest pays their own deposit within four weeks. I can't verify a £50 deposit or what happens to a guest who doesn't pay, so don't state either as fact.
- Why they win, add these if you agree they belong:
  - Host fit: GoHen's suppliers are chosen for hen and stag groups. Roamly's curated hosts, such as food tours and workshops, may not want a loud group of 12, and if they opt out, the curated-experience edge disappears for this segment.
  - City coverage: hen weekends cluster in UK party towns such as Liverpool, Newcastle, Bath and Brighton, and a few European cities. Roamly's 40 cities may not include them, and where they don't, there is no deal to win.
- Landmine questions, add: "If you've already solved collecting everyone's money, what's still the hardest part of organising the experience?"

Keep everything else as it is.
```

Neither model pushed back, so their replies aren't kept: the clean versions below include every change.

### 4. Clean-up · same chat as each correction

```text
Now format the completed battlecard as a clean, structured document I can save and share. Use Markdown, clear section headers, and keep each field concise and scannable.
```

**How the two clean versions compared** · both, word for word: [4-clean-up.md](02-competitive-intel/ai-replies/4-clean-up.md)

| Point | GPT-6 | Claude |
|---|---|---|
| Corrections | All taken, plus a new, unsourced claim that ABTOT "relates to arrangements for certain bookings made with the previous Groupia operator" | All taken, word for word; nothing else changed |
| Host fit and city coverage | Added as reasons they win, and again as checks to run before scaling | Added as two rows, each ending in an action: confirm host opt-in; map our cities against hen destinations |
| Scope | Grew into a rollout plan, success measures and a "CPO verdict" drawn from Module 1 | Stayed a battlecard |

- **Claude edited like a careful colleague:** it changed only what I asked, and turned the two new risks into actions a team can take.
- **GPT-6 kept adding:** a new unsourced claim, and a launch plan the battlecard didn't ask for. Its checks before scaling are still worth keeping for Lab 2.

---

## Module 3 · Positioning

From this module, both models run in memory-off chats: ChatGPT's Temporary Chat and Claude's incognito chat.

### 1. Generation

```text
I have completed a positioning framework for a new feature called Roamly Groups, a coordinated group booking feature on a curated travel experience platform.

Here are my six components:
- For: Organisers of milestone celebrations (big birthdays, anniversaries, reunions) booking one standout experience for 6–12 people.
- Who want / need: To give everyone one experience they'll remember, without fronting the whole cost or chasing friends for their share.
- We offer: Roamly Groups lets one person book a curated local experience, such as a food tour or a cooking class, for a group of up to 12, with each guest paying their own share and everyone seeing the same plan.
- Because of: The organiser books something memorable in minutes and then gets to enjoy it as a guest, without fronting the cost or chasing anyone.
- Despite: Not every Roamly host takes groups of 6–12, so the experience the organiser wants may not be bookable for their group on their date.
- Better than: Paying on one card and chasing friends, or booking on Airbnb Experiences or GetYourGuide where one person still pays for everyone: Roamly pairs vetted local hosts with each guest paying their own share.

Using these inputs, write a sharp positioning statement of one to two sentences that leads with the core product offering and then follows with the core value proposition. Keep it specific, clear, and free of jargon.
```

**How the two statements compared** · both, word for word: [1-generation.md](03-positioning/ai-replies/1-generation.md)

| Point | GPT-6 | Claude |
|---|---|---|
| Who it's for | Not named: "organisers" | Named: "anyone organising a big birthday, anniversary or reunion" |
| For a stranger | No examples | "such as a food tour or cooking class" |
| Outcome | "a memorable experience to look forward to" | "booking something memorable in minutes, then enjoying it as a guest" |
| Length | Two sentences, 48 words | Two sentences, 68 words |

- **Claude's is my first draft:** it names the occasion and the outcome; GPT-6's could describe any experiences site.
- **Both left out the defensible part:** neither says "vetted local host", and both put per-guest payment, the feature Airbnb could copy, in the first sentence. The pressure test checks whether that matters.

### 2. Pressure test · same chat as each statement

Test B, competitor discomfort, run on my first draft (Claude's statement) in both chats. The Lab Guide fills in my Module 2 competitor, GoHen; I swapped in Airbnb Experiences, because GoHen doesn't serve milestone celebrations and Airbnb is the likelier copier.

```text
Now role-play as a product leader at Airbnb Experiences. Read the following positioning statement for Roamly Groups. Could your company use this statement word for word without anyone noticing? If yes, what specifically makes it too generic? If no, what makes it ownable to Roamly specifically?

Roamly Groups lets one person book a curated local experience, such as a food tour or cooking class, for up to 12 people, with each guest paying their own share and everyone seeing the same plan. For anyone organising a big birthday, anniversary or reunion, that means booking something memorable in minutes, then enjoying it as a guest instead of fronting the bill or chasing friends to pay.
```

**How the two pressure tests compared** · both replies, word for word: [2-pressure-test.md](03-positioning/ai-replies/2-pressure-test.md)

| Point | GPT-6 | Claude |
|---|---|---|
| Could Airbnb use it? | "most of this word for word" | "almost word for word"; only per-guest payment gives it pause, and that goes "on our roadmap" |
| What's ownable | One booking, per-guest payment and vetted hosts, together | Hosts who have opted in to groups, a plain promise on unpaid seats, proof from Roamly's base, and a product built for groups |
| Its rewrite leads with | The payment mechanism | A vetted local host who welcomes groups |
| Its caveat | Benchmark the guest-payment journey against Airbnb and GetYourGuide | Confirm host opt-in and the payment rule are true at launch |

- **They agreed the draft wasn't ownable:** both flagged the category's default words, and both called per-guest payment something Airbnb could copy.
- **Claude turned my weakness into the position:** host opt-in, my "Despite", becomes a promise Airbnb can't make across mass supply, and Module 1's stage 0 gate already requires it. GPT-6's rewrite leads with payment, the part it had just said Airbnb could build.
- **Unverified in Claude's role-play:** that Airbnb has launched a shared itinerary, the same claim I couldn't verify in Module 2.

### 3. Stranger clarity · same chat as each pressure test

Test C, run on the final statement in place of the blind read, which I skipped.

```text
Now role-play as someone who has never heard of Roamly or Roamly Groups. Read the following positioning statement and explain back in your own words: what is this product, who is it for, and why would someone choose it over the alternatives? Do not use any words from the statement itself.

Roamly Groups lets one person book an experience with a vetted local host who welcomes groups, such as a chef's table or a private food tour, for 6–12 people, with each guest paying their own share by a set deadline. For anyone organising a big birthday, anniversary or reunion, that means enjoying the day as a guest, never covering a seat you didn't choose to.
```

**How the two strangers compared** · both replies, word for word: [3-stranger-clarity.md](03-positioning/ai-replies/3-stranger-clarity.md)

| Point | GPT-6 | Claude |
|---|---|---|
| What it is | "A group reservation service for activities run by local professionals" | "Some sort of reservation app", run by "screened residents, happy taking on bigger parties" |
| Who it's for | Someone arranging "a significant birthday, wedding anniversary or family gathering" | Whoever's planning "turning 40, marking years of marriage, catching up after ages apart" |
| Why choose it | The organiser doesn't subsidise everyone; hosts take larger parties | Every invitee pays directly before a cutoff, so the organiser joins in |
| What tripped it | What happens if someone misses the payment deadline | "Chef's table" reads two ways; the last clause is a double negative; no sign of where it works |

- **The statement passes:** both strangers named the product, the person and the main benefit in their own words.
- **Both stumbled on the same clause:** "never covering a seat you didn't choose to" hints at dropouts without saying what happens. Module 1's unpaid-share rule has the answer; the statement should say it plainly.

### 4. Audience recognition · same chat as each stranger test

Test A, on the final statement, to complete all three tests.

```text
Now role-play as this person: Organisers of milestone celebrations (big birthdays, anniversaries, reunions) booking one standout experience for 6–12 people. Read the following positioning statement and react honestly: do you immediately recognize yourself in it? Does it speak directly to your situation, or does it feel too broad, too vague, or pointed at someone else? Be direct.

Roamly Groups lets one person book an experience with a vetted local host who welcomes groups, such as a chef's table or a private food tour, for 6–12 people, with each guest paying their own share by a set deadline. For anyone organising a big birthday, anniversary or reunion, that means enjoying the day as a guest, never covering a seat you didn't choose to.
```

**How the two organisers compared** · both replies, word for word: [4-audience-recognition.md](03-positioning/ai-replies/4-audience-recognition.md)

| Point | GPT-6 | Claude |
|---|---|---|
| Recognises itself? | "Yes" | "Partly": playing someone organising their sister's 40th, it says the statement "reads like a product spec, not like my problem" |
| "Enjoying the day as a guest" | Overclaims: the organiser still chooses and coordinates | "Really lands": "what I want and never get" |
| The deadline | "What does the deadline mean in practice? … This matters enormously." | "Sounds like admin"; the double negative raises a worry it didn't have |
| New gaps | Choice beyond two food examples | The birthday person doesn't pay; guests may need an account; anniversaries and reunions dilute it |

- **The deadline came up in all four replies to tests C and A:** the statement has to say what happens to an unpaid place, in plain words.
- **Claude's persona found what the framework missed:** the honoured guest. Birthdays and anniversaries nearly always have someone who doesn't pay, which per-guest payment doesn't cover. That's a product question before it's a message, and an input to who pays in Module 5.
- **They disagreed on "as a guest":** GPT-6 called it an overclaim; Claude's persona called it the line that lands. A role-played persona is still the model reading my own "For" text back, so neither is evidence about real organisers.

---

## Module 4 · Messaging

Both models run in memory-off chats: ChatGPT's Temporary Chat and Claude's incognito chat.

### 1. Copy generation

```text
I am building messaging for Roamly Groups, a coordinated group-booking feature on a curated travel experience platform.

Here is my full messaging pillar for Organisers of milestone celebrations:
- Value prop: Pick something special for the big day and enjoy it with everyone else, without fronting the bill or chasing anyone.
- Capabilities: One booking for 6–12 people with a vetted local host who has opted in to groups; each guest pays their own share through a link by a deadline; at the deadline, the organiser decides whether to cover or release any unpaid place; everyone sees one shared plan.
- Evidence: Repeat booking at 3× the industry average and 12,000+ vetted hosts; group proof comes from the stage 1 beta: completion rate against the multi-account baseline and organisers' own stories (targets, not yet results).

Generate one copy variation for each of these three surfaces, written entirely from the pillar above. Keep each one human, specific, and free of jargon:
1. In-app notification
2. Email subject line
3. Social post

For each, tell me which part of the pillar it leads with and why.
```

**How the two sets of copy compared** · both replies, word for word: [1-copy-generation.md](04-messaging/ai-replies/1-copy-generation.md)

| Surface | GPT-6 | Claude |
|---|---|---|
| In-app notification | "Planning a big birthday? …": names an occasion the in-app user may not have | "Booking for 6 or more?": capability at the moment of intent, with a trigger (group size 6+ or group checkout) |
| Email subject line | "Your celebration, your friends, one less bill to worry about": money-led | "Book the big day, then enjoy it like everyone else", with preview text carrying the payment proof |
| Social post | Occasions, then capabilities, then "12,000+ vetted local hosts … plenty to discover" | Pain first ("weeks chasing eleven friends"), the unpaid-share rule in the middle, hosts last |
| Evidence | Platform figures used as proof; warns that beta figures are targets | Keeps evidence out of the lead, because group proof doesn't exist yet |

- **Claude's copy stays on the pillar:** it leads with the outcome where the reader isn't booking yet, and with the mechanism where they are. It also answers the objection the unpaid-share rule settles in the social post, the job Module 3 handed to Module 4.
- **GPT-6's social post overclaims:** "12,000+ vetted local hosts … plenty to discover" implies they all take groups, which my "Despite" says they don't.

### 2. Visual asset · same chat as each set of copy

The Lab Guide gives no prompt for this step, so I wrote one and sent it identically to both. It uses my chosen social post (Claude's), not each model's own.

```text
Turn this social post into a single standalone visual for Instagram (a 4:5 portrait image). Keep the copy as written, and make three things clear at a glance to someone who has never heard of Roamly: who it's for, what Roamly Groups does, and why they should trust it. Don't add statistics, testimonials or logos that aren't in the copy.

You picked the date. You found something special. Then you spent weeks chasing eleven friends for their share.
Roamly Groups sorts the last bit. Book one experience for 6–12 people with a vetted local host who's said yes to groups. Send everyone a link and each person pays their own share by the deadline. Anyone who hasn't paid? Your call: cover them or free up the place.
Pick something special. Then enjoy it with everyone else.
Hosted by locals from Roamly's 12,000+ vetted hosts.
```

**How the two visuals compared** · both, as delivered: [GPT-6 (PDF)](04-messaging/ai-replies/2-visual-asset-gpt6.pdf) · [Claude (PDF)](04-messaging/ai-replies/2-visual-asset-claude.pdf)

| Point | GPT-6 | Claude |
|---|---|---|
| Look | A photo of friends laughing over dinner at sunset in a hilltop town | Type only: a dark panel for the pain, three icon rows for the mechanism, a yellow band for the payoff |
| Copy | All of it, plus three new labels: "For you", "What it does", "Why trust it" | All of it, word for word, nothing added |
| Who it's for | Named: "Big birthdays, anniversaries and reunions", in a label it wrote itself | Implied by "eleven friends" and eleven empty circles; no occasion named |
| What it does | Shown as an experience (the dinner) and told in the copy | Told as three payment steps; no experience shown |
| Why trust it | "A vetted local host who's happy to host groups", and the 12,000+ hosts line | A shield beside the 12,000+ hosts line |

- **GPT-6's shows the experience; Claude's shows the payment.** A blind reader of Claude's could say "a bill-splitting app", the table-stakes framing Modules 2 and 3 moved away from.
- **Claude's kept the brief; GPT-6's wrote the test onto the poster.** Its "For you / What it does / Why trust it" labels answer the blind-read questions by quoting my prompt, and the occasion line isn't in the reviewed copy.
- **I chose Claude's:** it keeps the reviewed copy word for word. The cost is that it shows payment steps rather than the experience, which the blind read would test.

### 3. Blind read · new memory-off chats, the image attached

In place of a classmate's blind read: each model sees only my chosen visual (Claude's) and the Lab Guide's three questions, with no other context.

```text
Look at this image for about a minute, as if it had appeared in your social feed. Without any other context, answer three questions:
1. Who is it built for?
2. What does the product do, based on what you can see?
3. What makes you trust it?
Answer in your own words, and say where the image left you unsure.
```

**How the blind reads compared** · all the replies, word for word: [3-blind-read.md](04-messaging/ai-replies/3-blind-read.md)

It took three rounds to get clean reads: in the first, GPT-6's chat had context and Claude's image didn't upload; in the second, GPT-6 was given its own visual. By the end, each model had read each visual cold.

| Reader | My chosen visual (Claude's) | GPT-6's visual |
|---|---|---|
| GPT-6 | Who: "a birthday, hen or stag party". What: "less about discovering experiences and more about … getting everyone committed". Trust: specificity and the unpaid-share rule | Who: the occasions, from its own label. What: "the photograph suggests dining". Trust: "photography feels authentic" |
| Claude | Who: "the birthday, hen do or reunion". What: "really it's a split-payment and commitment tool". Trust: "moderate" | Who: "the birthday dinner or reunion trip". What: "group booking with split payment built in". Trust: "not much"; the labels feel "like filler" |

- **All four reads got the organiser and the mechanism; trust was the weakest layer in every one.** "Vetted" is never explained, and there's no rating, review, refund or cancellation promise. The course says evidence is usually the weakest layer.
- **My visual reads as a payment tool, and both readers guessed hen and stag parties,** the segment I deprioritised in Module 2. Without an occasion named, "eleven friends" reads as a hen do as easily as a birthday.
- **The photo helps less than I expected:** GPT-6 read dining from it, but Claude called it generic stock and still asked what an experience is. The copy has to name the experience, not just the picture.
- **No sign of a model favouring its own work:** Claude was the harsher reader of both visuals.
- **What I changed after the blind reads:** the social post's opening now names the occasion and the experience, and the organiser pillar lists the guarantee. The visual is unchanged.

---

## Module 5 · Pricing recommendation

Both models run in memory-off chats, ChatGPT's Temporary Chat and Claude's incognito chat, with `battlecard-and-bet.md`, `positioning.md` and `messaging-pillars.md` attached, as the Lab Guide asks.

### 1. Recommendation

```text
You are a senior product manager preparing a pricing recommendation for Roamly Groups, a coordinated group-booking feature on a curated travel experience platform. It has no price yet.

My pricing plan:
- Pricing goal: Grow revenue from a known audience: existing users who already book in groups across separate accounts and drop off before paying, matching my Module 1 goal (Expand) and my Module 2 bet on milestone celebrations.
- Pricing model: Transaction-based: Roamly earns its standard commission on every seat in a group booking, with no separate fee for using Groups. Who pays, and for what: Each guest pays their own share of the per-person price through a link; the organiser pays only their own place and any unpaid place they choose to cover; the honoured guest's share is split across the paying guests by default; hosts pay the standard commission on more seats.
- Tiers: Good: Join a session, for groups of 6–12 happy to share a host's scheduled session, at the host's usual price (about £40–£70 a head); Better ★: Private session, for milestone celebrations of 6–12 who want the host to themselves, about 25% above the usual price (about £55–£90 a head); Best: Private celebration, a private session built around the occasion (a toast, photos, a menu or route the group chooses) plus one free date change, for the biggest milestones (about £110–£150 a head).
- The assumption I'd test before launch: Guests at a milestone celebration will pay about 25% more a head for a private session, so most organisers choose Private session over joining a scheduled one.

My earlier work is attached: battlecard-and-bet.md (my strategic bet), positioning.md (my positioning statement) and messaging-pillars.md (my audiences). Use them.

Write a one-page pricing recommendation for Finance, Sales Leadership and Product Marketing. Use clear section headers, and for each stakeholder name what they most need to hear. Keep it concise and scannable. End with which research method would best test my assumption: Van Westendorp, Max-Diff or Conjoint.
```

**How the two recommendations compared** · all three replies, word for word: [1-recommendation.md](05-pricing/ai-replies/1-recommendation.md)

GPT-6 took two runs. The first couldn't find the three files and drew on older work in my ChatGPT Library, so it brought back hen and stag. The second read the files, but it also knew the first ("the previous recommendation"), so it wasn't fully cold.

| Point | GPT-6 (rerun, with the files) | Claude |
|---|---|---|
| Fee and model | No Groups fee; standard commission on paid seats | Same |
| Tiers | Against launching three tiers: one proposition at the host's usual price, private only where hosts already offer it | Kept all three: Private session as the default, Private celebration as the anchor |
| The 25% premium | "No evidence yet that privacy drives willingness to pay" | Kept, and showed the honoured guest's split lifts each guest's price to about £80 at a £56 usual price, 43% more |
| Honoured guest | Make it explicit; don't assume a free place is covered | Split by default, with each guest's real share shown before they pay |
| Sales Leadership | Sell the experience, not the payment feature; check host inventory | Recast as host supply, since there's no sales team: the host pitch and a minimum price for private sessions |
| Finance | Count only incremental bookings; contribution margin | A revenue formula and illustrative value per booking: £448, £560, £1,040 |
| Research method | Behavioural first: interviews, then live price tests; Conjoint later | Choice-based Conjoint, confirmed by beta take-up |

- **Claude's became the one-pager:** it works from my plan, its figures check out, and its £80 finding changed my assumption. Its one slip: "our £55–£150 range fits the category" leaves out Join a session at £40, and compares experiences with GoHen's packages.
- **GPT-6's was the stronger challenge:** it questioned whether the tiers and the premium were earned at all. I kept the tiers but staged them, and took its incremental-revenue rule, the package-price warning, the guarantee as a commercial priority and its interviews before the Conjoint.
- **Both ended on Conjoint, and both wanted the honoured guest's split made explicit.** Missed: Claude cited Airbnb's private groups for host controls but didn't draw the conclusion. Airbnb already sells privacy, so privacy isn't Roamly's edge; per-guest payment and hosts who welcome groups are.
