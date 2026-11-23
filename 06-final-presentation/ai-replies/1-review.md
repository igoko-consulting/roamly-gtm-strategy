# Final review: both replies

> The [review prompt](../../PROMPTS.md#1-review), sent word for word on 23 Nov 2026, with the downloaded presentation attached for GPT-6. Each model's words are unchanged; headings and lists are restored where copying from the chat flattened them. The comparison and what I did with it are in [PROMPTS.md](../../PROMPTS.md#1-review).
>
> *[GPT-6's reply follows an earlier run in the same chat, on the version with the name typo, which isn't recorded here; its file citations are kept as copied. Claude's reply comes from the Claude Code session that built this repo, not a memory-off chat, so it isn't a cold read.]*

**Jump to:** [GPT-6](#gpt-6) · [Claude](#claude)

---

## GPT-6

1. Audience, go-to-market and competitive advantage: Yes. I can now tell clearly who Roamly Groups is for: organisers of milestone celebrations involving 6–12 people. The go-to-market route is also credible: convert existing users showing group-booking intent through PLG first, then test community-led discovery once there is evidence and organiser stories to support it. The competitive bet is to own the experience rather than compete with GoHen on packaged hen and stag weekends. What remains unclear is the size of the milestone-celebration opportunity: you explain why the problem is acute, but not how much demand exists or how frequently it occurs.

2. Strategic coherence: The bet, positioning and messaging now tell a consistent story: choose something special, book the group once, and avoid the organiser having to front the bill or chase payments. Pricing supports that proposition through per-seat transactions, with no additional Groups fee. The weakest part remains the pricing proposition—not because the model is incoherent, but because the 25% private-session premium is still an assumption, and the tier structure introduces choices before you have demonstrated what customers actually prefer. Staging the premium celebration tier is the right response. One small messaging point: “everyone pays their own share” needs to be understood alongside the honoured guest’s share being redistributed across the group. You explain the mechanics later, but that distinction matters to the promise.

3. The one change I’d make: Add a single, compact commercial proof point for a group of eight: show the shared-session and private-session prices, how the honoured guest’s share is allocated, what each paying guest contributes, and what Roamly earns. You already have the ingredients and the arithmetic in the pricing assumption; bringing them together would make the commercial logic much easier to assess. I’d also want to see host coverage treated as a launch constraint, not just a positioning caveat. The reflection is strong, particularly its distinction between AI producing answers and you exercising judgement. final-presentation-new(1).html

Ready to submit — the previous name-rendering typo is fixed, and the presentation now reads as a coherent set of connected decisions rather than five separate course exercises. The remaining gaps are things to validate in market, not reasons to hold back the submission. final-presentation-new(1).html

---

## Claude

**Review, as VP of Product**

**1. Is it clear who it's for, how it goes to market and why it wins?** Who it's for and how it goes to market are clear. It's for organisers of milestone celebrations with groups of 6 to 12. It reaches them inside a product they already use, at the moment they try to book for a group. Why it wins is the gap. The competitor card names GoHen, and the bet then leaves GoHen's market alone, so the page never says who Roamly beats for a 40th birthday. Your own battlecard has the answer: milestone groups book on Airbnb Experiences and GetYourGuide, where no one offers per-guest payment. It just isn't on this page. Course labels are also doing work a general reader can't follow: "Expand first, then Acquire", "stage 3", "the guest loop" and "the multi-account baseline".

**2. Do the bet, positioning, messaging and pricing tell the same story?** The bet, positioning and pricing tell one story: a host who welcomes groups, one booking, each guest paying their own share, and the private session as the revenue lever. Messaging is the weakest part. Module 2 concluded that per-guest payment is table stakes, to be used as proof rather than the headline. Yet the in-app prompt and the email preview sell payment. The one claim Airbnb can't copy, hosts who said yes to groups, appears only in the social post, the surface you were least sure of. Pricing hangs together and names its riskiest bet honestly, the untested 25% premium.

**3. The one change that would make it stronger:** put the milestone competitor on the page. The competitor card should say that GoHen owns hen and stag weekends, while milestone groups book on Airbnb Experiences and GetYourGuide, where no one offers per-guest payment. Then the case for why Roamly wins takes one line.

Ready to submit: the story holds from segment to price, the risks are named rather than hidden, and the competitor fix is ten minutes' work, not a blocker.

**My notes on the file**

- **This isn't a cold read:** I helped build this project, so my review isn't independent. For an unbiased review, run the prompt in GPT-6's Temporary Chat and Claude's incognito chat.
- **Content:** every card matches the repo, and the three reflection cards match the approved draft word for word.
- **Fix in the builder before committing:**
  - **Name typo:** the name line reads "artin Cook", missing the M. It appears on the cover and in the footer.
  - **Title not trimmed:** the title still ends ", by Martin Cook", in both the heading and the browser tab, so the trimmed title you approved on 20 November wasn't applied.
  - **Month dropped:** "· November 2026" is missing from the cover line. I'd leave it off (75%), since "Nov 2026 weekdays cohort" already gives the month.
- **If you take the competitor change:**
  - I'd make it in the repo (80%). I'd change Module 2's "Competitor:" bullet to "GoHen, which owns hen and stag weekends; milestone groups book on Airbnb Experiences and GetYourGuide, where no one offers per-guest payment", then you pull again in the builder.
  - Editing only the builder card would leave the presentation and the repo saying different things.
- **Messaging point:** I'm not proposing a change, because it would reopen Module 4.
- **Status:** nothing is committed. I'll commit once you've downloaded the fixed file.

Shall I make the competitor change in the repo before you fix the name and title and download again, or should you only fix the name and title?
