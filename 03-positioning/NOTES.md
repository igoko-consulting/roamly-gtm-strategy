# Module 3 notes: Write Positioning That Survives a Teardown

Session 3, 9 Nov 2026. Sources: Module 3 slides and Lab Guide. Output: [positioning.md](positioning.md).

## The big idea

- **Positioning is an internal decision made before any message:** what the product is, who it's for and why it matters, settled once so every team tells the same story. Without it, sales, marketing and product each describe the product differently, and customers end up as confused as the people selling to them. Missed: Roamly Groups is product-led with no sales team, so the story first shows up in the product itself: the invite, the payment page, the shared plan. That is where Module 4 has to start.
- **Start with the person, not the product:** a persona is a specific person in a specific situation with a specific problem. If the details would fit anyone, they're the wrong details. In consumer products the friction is emotional: fear of the wrong choice, social risk, the effort of coordinating. Missed: I kept "For" as the segment, milestone celebrations, so every module reads the same. The person-level detail came from test A instead, where Claude played someone organising their sister's 40th.

## The six components

| Component | Question | Roamly Groups, in short |
|---|---|---|
| For | Who specifically is this for? | Organisers of milestone celebrations for 6–12 people |
| Who want / need | What problem, in their words? | One experience everyone will remember, without fronting the cost or chasing friends |
| We offer | What is it, so a stranger understands? | One person books a curated local experience for the group; each guest pays their own share |
| Because of | The outcome, not the feature | The organiser enjoys it too, without fronting or chasing |
| Despite | The honest shortcoming | Not every host takes groups of 6–12 |
| Better than | Why you, defensibly, for this person | One card and chasing friends, or marketplaces where one person still pays |

- **Work in order, and don't soften "Despite":** teams that start with the offering end up positioning the product, not the customer. The course's worked example, a faster alternative to Jira, names its weakness plainly: a newer entrant in a category of deeply embedded tools. Missed: my "Despite" turned out to be the most useful line. Test B showed that host availability, flipped into "a vetted local host who welcomes groups", is the part Airbnb can't copy.
- **Two-sided markets need one core truth:** sharpen for one side and you risk losing the other, so find the product truth both sides recognise (the example: developers and engineering leaders, both served by "the dev environment built natively for the AI era"). Missed: Roamly has two sides, travellers and hosts, and my statement speaks only to organisers. The truth hosts would recognise, a group that has committed and paid before the day, isn't written down yet.

## Overcoming the challenges

- **Three category plays:** compete on the criteria buyers already use, reframe what matters within the category, or create a new one and educate the market first. Missed: Roamly Groups reframes. It stays in the experiences category but shifts the criterion from breadth of choice to certainty for the group. Reframing costs education, and the marketplaces will answer "we do groups too".
- **Three gaps:** language (internal labels customers never use), promise (the product doesn't deliver what the positioning claims) and consistency (each team tells a different story). The test is to ask five customers for one sentence and see whether any two match. Missed: my biggest risk is a promise gap. "A vetted local host who welcomes groups" and the rule on unpaid places are true only if Module 1's stage 0 gate holds.
- **Drift happens one reasonable compromise at a time:** longer descriptions, a widening audience, sounding like rivals, customers who can't say why they chose you. The fix is to ask, at every launch, whether it serves the audience you positioned for. Missed: my own statement grew from 68 to 77 words across three tests, each fix reasonable. That is exactly how drift starts.
- **Anthropic's Claude:** in a market where speed and features were table stakes, Anthropic reframed on trust and defined its audience as people solving hard problems. Two campaigns made it visible: "Keep Thinking" said who Claude is for, and "A Time and Place" said what it refuses to become (no ads). Missed: a refusal is ownable when a rival's business model makes it costly to copy. Claude's test-B critique made the same point about Airbnb: groups will always be a side feature in a stays-led app.

## From framework to statement

- **The statement elevates two parts, the core offering and the core value proposition:** Loom's names the offering (video messaging for teams) and the value (communicating clearly without being in the same place at the same time) in one sentence. Missed: Loom's statement is about 20 words; mine is 77 across two sentences. The course allows two sentences, but the drift warning applies.

| Mistake | Did my statement make it? |
|---|---|
| Positioning against a competitor, not for a customer | No: the competitors sit in "Better than", not in the statement |
| A feature as positioning | Yes, in the first draft: it led with per-guest payment. Test B caught it |
| True but not ownable | Yes, in the first draft: "curated local experience" is the category's default claim. Test B caught it |
| Positioning for the loudest internal voice | Not applicable: I'm the only voice, though two models pull in different directions |
| A tagline as the statement | No, but the README pitch is closer to a tagline, which is its job |

- **Three pressure tests, each tied to a component:** if the audience doesn't recognise itself, rewrite For and Need; if a competitor could use it word for word, sharpen Better than; if a stranger needs context, sharpen the offering and value. All three can run with an AI role-playing the person. Missed: an AI persona built from my own "For" text is the model reading my answer back. It can find gaps, such as the honoured guest, but it can't confirm that real organisers feel the pain.
- **Positioning is internal and rarely changed; messaging is external and iterated:** teams that rewrite positioning with every campaign end up with a strategy that shifts with every launch. Missed: the rule on unpaid places is now in my statement because every tester asked about it. Strictly, it's an objection answered, which is messaging, and Module 4 may move it out.

## Labs

- **Framework:** six components drafted from the Module 2 bet, in order. Prompts, comparisons and all four tests: [PROMPTS.md](../PROMPTS.md); the replies, word for word: [ai-replies/](ai-replies/).
- **Decision, For: the Module 2 wording.** I kept "organisers of milestone celebrations" so the segment reads the same in every module, over a version describing one person in a moment. Missed: the course asks for the person, and pressure test A would have role-played a sharper one.
- **Decision, first draft: Claude's.** It named the occasion and the outcome; GPT-6's could have described any experiences site. Missed: both drafts left out "vetted local host", the defensible part of my "Better than".
- **Decision, test B against Airbnb, not GoHen:** the Lab Guide fills in my Module 2 competitor, but GoHen doesn't serve milestone celebrations. Both models, playing Airbnb, said it could use my draft almost word for word. Missed: this broke the Lab Guide's word-for-word prompt to make the test useful. I recorded why in PROMPTS.md.
- **Insight, the weakness became the position:** only two things proved ownable: hosts who have opted in to groups, which is my "Despite" turned round, and a plain promise on unpaid places. The final statement is built on both. Missed: both are promises the product has to keep; if host opt-in fails at stage 0, the statement is false.
- **Tests C and A, in place of the skipped blind read:** both strangers named the product, the person and the benefit in their own words. All four replies asked what happens to an unpaid place, so the final statement now says it plainly. Missed: an AI stranger isn't a classmate's cold read. The blind read is still worth doing with a real person.
- **What AI cracked open:** with memory off, the two models disagreed in useful ways. On "enjoying the day as a guest", GPT-6 called it an overclaim and Claude's persona called it the line that lands. Claude's persona also found something no framework field asked about: the birthday person who doesn't pay. Missed: disagreement is only useful if I decide. I softened the line to "with everyone else", close to the version Claude's persona suggested ("like everyone else").

## What this means for Roamly Groups

- **Insight, the honoured guest is a product gap, not a wording gap:** birthdays and anniversaries nearly always have someone who doesn't pay, and per-guest payment doesn't cover them. The product needs an answer (cover or split the honoured guest's share) before Module 4 can promise it, and it feeds "who pays" in Module 5. Missed: the specialists may already offer it (GoHen's "pay for someone else" is unverified), in which case it's table stakes.
- **Guest friction is the next objection after money:** if guests need an account or an app to pay, the organiser is back to chasing. Module 1's guest surfaces offer "a light path to an account", so paying without one should be possible. Missed: Module 4 should say so only if it's true at launch.
- **One occasion or three:** Claude's persona said anniversaries and reunions dilute the message, because their payment dynamics differ (children paying for their parents' anniversary). I've kept the segment. Missed: leading Module 4's copy with big birthdays would be a messaging choice, not a segment change, and the occasion tag will show which occasion converts.
- **Hosts need their own line:** the statement speaks to organisers only. Missed: Module 4's audience step is where to decide whether hosts get their own message, and the core truth both sides share is a group that has committed and paid.
