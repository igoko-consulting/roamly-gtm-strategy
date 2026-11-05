# Module 2 notes: Turn Competitor Signals Into a Battlecard

Session 2, 5 Nov 2026. Sources: Module 2 slides and Lab Guide. Output: [battlecard-and-bet.md](battlecard-and-bet.md).

## The big idea

- **Data says what happened; insight says why, and what to do:** Apple's iPhone launch named a problem people had stopped expecting anyone to solve: a phone, an iPod and a web browser carried as separate devices. The MacBook Air in an envelope showed that portability mattered more than the specs laptops were sold on. Missed: insights look obvious once they've worked. The hard part is choosing which signal to trust before launch, which is why the module ends in a bet that can be wrong.
- **Research only counts if it ends in a decision:** Data, Insight, Belief, Bet moves a team from "here's what we found" to "here's what we're committing to", the step most teams never take. Missed: a bet without a named sacrifice is a preference. Naming hen and stag weekends as what I'd give up is what made mine a bet.

## Four kinds of insight

| Type | What it reveals | Roamly Groups |
|---|---|---|
| Qualitative | The motives and frustrations behind behaviour | Support tickets: groups want to book on Roamly, and the product gets in the way |
| Quantitative | What happens at scale: friction, drop-off | The multi-account pattern and its drop-off before payment |
| Market | Shifts in what buyers expect | The marketplaces now court the organiser: GetYourGuide's "Holiday Hero or Zero" campaign, Airbnb adding Tripadvisor's supply |
| Competitive | Where rivals win and lose, and why | Specialists already sell per-guest payment to hen and stag groups |

- **Start inside the building:** before paying for outside research, mine the teams nearest the customer. Sales hold win/loss and objections; customer success, churn and the gap between promise and experience; marketing, how the market responds; product, behaviour, the most objective of the four. Missed: Roamly is a consumer marketplace with no sales team, so support tickets play the win/loss role. That is where the Groups signal came from.
- **The motion is the filter:** PLG asks whether value arrives fast enough to spread, so it prioritises time to value and activation (Slack's 2,000-messages threshold). SLG prioritises win/loss and deal velocity. CLG prioritises sentiment and referrals (Notion's template sharing). In a marketplace, research travellers and hosts separately and prioritise the side that limits growth. Missed: for Roamly Groups the limiting side may be hosts. My biggest threat is host fit, and I haven't researched hosts at all.

## Mapping the competition

- **The status quo is the biggest competitor:** more than half of buying processes end in no decision. Beating inertia takes a problem painful enough that changing feels cheaper than staying, and reaching the buyer when frustration peaks. Missed: for an organiser, frustration peaks when the first guest doesn't pay. That moment happens inside the booking flow, which suits a product-led motion.
- **Five sources:** customer conversations, review sites, SEO and AEO (asking AI tools "what's the best X"), analysts, and CRM win/loss. Missed: AEO is becoming a channel, not just a research method. Viator became Gemini's first connected app for travel experiences in July 2026, so the AI answer is also where a competitor can sit.

| Tier | Who | Response | Roamly Groups (my classification) |
|---|---|---|---|
| Primary | In buyers' decisions now | A battlecard and sharp answers | GoHen for the hen and stag groups I started with; the status quo for milestone celebrations |
| Secondary | Solve part of the problem, not yet in deals | Monitor positioning and overlap | Airbnb Experiences, GetYourGuide and Viator |
| Aspirational | A segment or scale I'm not in yet | Track their category moves | Team-building firms, Funktion's included, for when Groups reaches corporate offsites |

- Missed: my battlecard is against GoHen, but after narrowing the segment, the rival I most need to beat is the status quo. Its card is one line ("Why you?") for now.

**The battlecard's four sections:** know the landscape (overview, offerings, pricing); understand the battlefield (strengths, weaknesses); win the deal (why you win, why they win, and why you over doing nothing); handle the hard moments (quick dismiss, landmine questions, objection handling). It tests the strategy as well as arming sales: if you can't say when you lose, the strategy isn't ready.

- Missed: the section that is hardest to fill honestly is the signal. For me it was "Why they win", which only became uncomfortable once host fit and city coverage went in.

## Data, Insight, Belief, Bet

| Step | Question | Test |
|---|---|---|
| Data | What does the research show, and where do the signals conflict? | The three main findings, and where they disagree |
| Insight | Which pattern changes how I see the market? | The most surprising thing I learned |
| Belief | What am I now willing to say is true? | "I now believe that…", in one line |
| Bet | What will I commit to and defend? | What I'm changing, and what I'm giving up |

- **Spotify's Summer Rewind:** "Your Top Songs" was shared more than anything else on Spotify, because it said something about the listener. To test that, Spotify tried three playlists. A birthday playlist failed (people gave false birthdays, and the songs had nothing to do with their taste). A city playlist failed (where you live isn't who you are). Summer throwbacks held, because past summers carry real memories. Surveys then chose "Your Summer Rewind" over "Throwback" or "Nostalgia" because it signalled both personal and past. The bet on personalisation ran through Daily Mixes, Discover Weekly and Blend into Wrapped, with no paid media. Missed: the two failures did as much work as the winner, because each one narrowed what "personal" meant. Hen and stag weekends played that role for my segment.

## Labs

- **Research:** both models named GoHen as the competitor I hadn't considered, and the status quo (WhatsApp, one card, bank transfers) as where most drop-off goes. Prompts, comparisons and my checks: [PROMPTS.md](../PROMPTS.md); the replies, word for word: [ai-replies/](ai-replies/).
- **Decision, primary competitor: GoHen.** It already sells "everyone pays their own share, no chasing" to hen organisers: my value proposition, in my segment. Airbnb Experiences is better known and the likelier fast follower, but it doesn't split payments yet. Missed: GoHen sells packaged UK and European weekends, so it only ever threatened the hen and stag part of my segment.
- **Insight, from checking rather than prompting:** live sources showed that GoHen's owner, Groupia, went into administration in June 2026 and that Funktion Leisure bought GoHen and StagWeb out of it. They also showed that the £50 deposit both models quoted isn't on GoHen's site. I corrected the battlecard before the clean-up. Missed: I checked the claims that drove decisions, not every line, so details such as GoHen's AI hen planner remain unverified.
- **Battlecard:** I used Claude's as the base, because its "Why they win" named Roamly's own gaps: no protection badge, no live unpaid-share rule, unknown in the category. I added two risks neither model raised (hosts may not want hen groups; Roamly's 40 cities may not cover the hen towns) and GPT-6's best landmine question: "what's still the hardest part?" Claude changed only what I asked; GPT-6 added an unsourced claim and a launch plan nobody asked for. Missed: GPT-6's card was fuller on objection handling, which is more useful to a sales team than to me.
- **Decision, segment: milestone celebrations.** The battlecard left me less confident in my segment and more confident in the product. I narrowed from occasion groups to big birthdays, anniversaries and reunions, and carried the change back into Module 1 and the README pitch. Missed: no data yet shows that Roamly's demand comes from birthdays rather than hens. The occasion tag at group creation is still the test.
- **Decision, bet:** own milestone celebrations with one standout experience from a vetted local host, booked for the whole group in minutes, with every guest paying their own share. To make it, I'm deprioritising hen and stag weekends as a target and anything packaged. Missed: hen weekends are the higher-spend groups, so the bet gives up revenue per booking for a position no one else holds.
- **What AI cracked open:** two models agreeing isn't two reviews when both remember me. Both drew on my Module 1 chats, and GPT-6 repeated my own "Expand, prove, acquire" sequence back to me. The ownership change and the wrong deposit came from checking, not from either model. From Module 3, both run in memory-off chats. Missed: memory made the replies more relevant, because they knew the strategy. The trade is relevance against independence.

## What this means for Roamly Groups

- **Insight, per-guest payment is table stakes, not the edge:** it is standard where the specialists sell, and missing where milestone groups book. Lead with the curated experience, and use payment as proof that no one gets chased. Missed: in milestone celebrations, per-guest payment is still a differentiator until Airbnb adds it, so it shouldn't be dropped from the message, only demoted.
- **Biggest open risk, host fit:** the bet rests on hosts accepting groups of 6–12 on the dates groups want. Hosts need their own research before stage 1, as the motion slide says for any marketplace, and Module 1's stage 0 gate now requires host opt-in for groups of 6–12. Missed: hosts may welcome groups if the price per head works, so Module 5's pricing partly answers this.
- **The unpaid-share rule is now competitive, not just operational:** organisers will compare it with GoHen's familiar deposit structure, and until it is live and visible, GoHen wins on certainty. Missed: a visible guarantee on payments and cancellations matters as much as the rule itself, since that is what ABTA protection gives GoHen. Module 1's stage 0 gate now requires one.
- **Module 3 carries the change:** the README pitch now leads with the experience, but the Module 1 value proposition still leads with "everyone pays their own share". Positioning is where that gets fixed. Missed: the segment change rests on one competitor's evidence. Module 3's persona work should test whether milestone organisers recognise the pain as sharply as hen organisers do.
- **Watch list:** Airbnb (Tripadvisor supply on the way, private groups of up to 30, no per-guest payment yet), GetYourGuide (marketing to the organiser), Viator (inside Gemini).
