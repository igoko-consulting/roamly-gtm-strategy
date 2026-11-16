# Module 4 notes: Turn Positioning Into a Message That Ships

Session 4, 16 Nov 2026. Sources: Module 4 slides and Lab Guide. Output: [messaging-pillars.md](messaging-pillars.md).

## The big idea

- **Great messaging is simple, and traceable to positioning:** Airbnb's "Belong Anywhere" is two words that state the value, use no jargon and stay the same on every surface. Slack's redesign launch did the opposite: it described a product decision rather than a human one, called a rearranged workspace "a bit of polish", and gave users no reason to trust the change before living with it. Missed: Slack's was also a change-management failure for existing users. Roamly's equivalent risk is solo bookers seeing Groups prompts as clutter, which is why solo conversion is a guardrail.
- **Three ingredients: positioning, specificity, consistency:** every message traces back to the positioning, speaks to a precise person with a precise problem, and says the same thing on every surface. Messaging is the bridge from positioning (internal) to activations (marketing copy, in-product copy, sales assets, demos). Missed: consistency was the hardest of the three in my own repo. Changing the statement in Module 3 meant the README pitch, Module 1's value proposition and the framework all had to follow.

## Building the message

- **Fro/To:** before any pillar, describe what changed in the world that made the product necessary, not a feature. Peloton moved fitness from a studio's timetable to any time at home; Shop Pay moved checkout from hunting for your wallet to details filled in for you. It may never appear in copy, but it shapes all of it. Missed: my From ("one person carries the celebration") did appear once, as the social post's hook about chasing eleven friends, and it was the line that stopped both cold readers.
- **How many audiences:** split only when one message would miss someone. The course's tests are role or buying position, use case, sophistication, journey stage, geography and price sensitivity. Missed: I split on role. The organiser chooses and books; the guest pays through a link they didn't choose. That is the consumer version of buyer versus user. Hosts got no message, though they are the biggest threat.
- **The pillar pyramid:** the value prop leads, capabilities make it real, evidence proves it. Cursor runs two pillars, for developers and for engineering leaders, with the same three layers written for each. Missed: my evidence layer is weak by construction. Before launch, Roamly Groups has platform figures and beta targets, nothing about groups.
- **Evidence rules:** specific beats vague, authentic beats polished, named beats anonymous; "customers love it" proves nothing. Missed: the one piece of evidence I can create before launch is a promise, a refund or cancellation guarantee, which is the trust line every blind reader asked for.
- **Four craft filters:** be human, use fewer words, use the customer's words, be specific. Missed: "use their words" means interviews, reviews and support tickets. Mine came from AI role-play, which is the model's language, not the customer's.

## Activating it

| Surface | Why it matters | Roamly Groups |
|---|---|---|
| Marketing copy | The widest reach, and the first place consistency breaks | The social post: a stage-3 community surface |
| In-product copy | The highest-leverage surface for a product-led motion | The in-app notification at the moment of intent |
| Sales assets | For buyers who never use the product | None: no sales team |
| Interactive demos | Converts when the product speaks for itself | Not in V1 |

- Missed: for a product-led launch, the in-app line matters most, yet I spent most of the lab on the social post and its visual, a stage-3 surface.
- **Shop Pay's landing page:** the value prop leads ("the best-converting accelerated checkout"), capabilities follow for each kind of merchant, and evidence closes with a specific conversion figure. Missed: a specific number does the selling. Mine can't until the beta produces one.
- **AI is the execution layer, not the judgement:** it drafts copy across surfaces, prototypes visuals, monitors the market (Klue, Crayon) and flags which variants convert. It can't replace customer language or positioning judgement. Missed: AI blind reads only work if they're blind, and context leaks more easily than I expected.
- **Is it working?** Watch conversion by surface, win/loss themes, in-product engagement and language drift. Missed: for Roamly Groups, language drift is the test that matters. Do organisers call it "a way to book something together" or "a bill-splitting tool"? The cold reads already said the second.

## Labs

- **Pillars:** both pillars and the copy are in the deliverable. Prompts, comparisons and every reply: [PROMPTS.md](../PROMPTS.md); the replies and visuals, word for word: [ai-replies/](ai-replies/).
- **Decision, From/To:** from "one person carries the celebration" to "the group carries it together". Missed: "commits" in the To sets up the unpaid-place rule, but no reader saw commitment as a benefit.
- **Decision, two audiences, organisers and guests:** the organiser's pillar answers the unpaid-place rule that Module 3 handed on, and labels the beta figures as targets. The guest pillar is mine, since only Audience 1 gets AI copy. Missed: the guest pillar carries claims I can't yet confirm, such as paying "in a minute" and the light path to an account.
- **Decision, surfaces: in-app, email and social,** with social as the uncertain one. All three lines are Claude's; GPT-6's social post implied every host takes groups, which contradicts my "Despite". Missed: GPT-6's in-app line named a birthday, the occasion the cold readers later couldn't find.
- **Decision, visual: Claude's,** for keeping the reviewed copy word for word, over my recommendation of GPT-6's photo version. Missed: cold readers saw a payment tool in it. But Claude read GPT-6's photo as generic stock and still asked what an experience is, so the choice held up.
- **Insight, the blind reads:** all four reads, each model on each visual, found the organiser and the mechanism. Trust was the weakest layer every time, and both readers of my visual guessed hen parties. The V2 shows the experience, says what Roamly is, names the occasion and adds a refund or cancellation promise.
- **What AI cracked open:** getting a cold read took three rounds. GPT-6's first chat had context, Claude's image didn't upload, and GPT-6 was then given the wrong visual. A blind read is only as good as its blindness. Missed: the two-by-two that came out of the mix-up separated the reader from the visual, and showed that neither model favoured its own work.

## What this means for Roamly Groups

- **Insight, without the experience it reads as a payment tool:** cold readers reduced Roamly Groups to split payment, the table-stakes framing Module 2 moved away from. The V2 has to show and name what you'd book. Missed: this is partly true of the feature itself. Groups is booking plus payment; the experience comes from Roamly's hosts, so the message has to borrow it.
- **Trust needs a promise that exists before launch:** say what "vetted" means, and publish the refund or cancellation guarantee that Module 1's stage 0 gate already requires. Missed: an organiser's own story from the beta will beat any promise, so the social post should be retested with one.
- **Price is the question every reader asked next:** what it costs, whether there's a fee, when the organiser is charged and what happens below six people. That is Module 5. Missed: "what happens if fewer than six pay" is a product rule that isn't set yet, a minimum group size.
- **Name the occasion:** both readers of my visual guessed hen parties. The hook should name a big birthday. Missed: naming one occasion narrows the message, the trade Claude's Module 3 persona argued for.
