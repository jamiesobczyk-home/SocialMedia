---
prepared: 2026-06-16
for_review: 2026-06-17 (Tuesday Series A slot)
series: A
status: ready-for-pick
---

# Series A — pick one for your next Tuesday post

Good morning. I developed your two saved Series A ideas into finished drafts, then
had a second agent review both against current IT news to make them more topical and
relatable. The big catch from that review: the GPU-cooling draft originally leaned on
a garbled version of Cisco's announcement, so I corrected the facts (details below).

Both are ready to post as-is. Pick one, or tell me to merge angles. Full draft files
live alongside this one in Posts/Drafts/.

Style is clean per CONTEXT.md: no em dashes, hashtags, emojis, or markdown inside the post.

---

## CANDIDATE 1 — "The Pause Before the Change"

Lens: systems thinking (quiet stoicism thread, respond vs react). ~250 words.
Topical angle: 2026 has been the year of change-induced outages (Cloudflare's Feb 20
BGP-withdrawal outage ran 6+ hours, most of it spent undoing the change), and the year
pipelines/agents push more change than ever. That makes the deliberate human pause feel
almost countercultural, which is what the added lines tap.

Hook A: My boss handed me a production problem and the exact change he wanted made. I didn't make it. Not right away.
Hook B: The most impressive thing I did early in my career was nothing. For about ten minutes.

Post:

My boss handed me a production problem and the exact change he wanted made. I didn't make it. Not right away.

This was early in my career. I could have pushed the change in two minutes. Instead I pulled out a piece of paper and drew the part of the network we were about to touch. Then I walked the change through on paper, one scenario at a time. What happens to this link. What happens to that route. What breaks if I'm wrong.

Once I was sure there were no surprises, I made the change. It worked.

What stuck with me wasn't the fix. It was what my boss said afterward. He told me he was impressed that I paused.

The impulse during an outage is to act immediately. Doing something feels like progress. But acting without thinking is how a thirty-minute outage becomes a four-hour one. We watched a big provider live that exact math this year. A fast change, then hours spent putting it back. The pause feels like it slows you down. It's usually the fastest path to a fix that actually holds.

With so much change pushed by pipelines now, I think about that moment more, not less. I ask people I interview how they approach making a change. Their answer tells me more than their resume does.

When you're under pressure to fix something fast, what makes you slow down before you touch it?

(Note: the "big provider" line is optional. Vaguer ages better than naming Cloudflare and dating the post. Cut it if you want it fully evergreen.)

---

## CANDIDATE 2 — "The Better Question Is Upstream"

Lens: systems thinking (leverage points, upstream intervention). ~255 words.
Topical angle: mid-2026's defining data center story has shifted from "can we cool it"
to "can we power it" — GPUs are available, megawatts aren't. And alert correlation /
AIOps killing alert fatigue is the single most-discussed practitioner topic right now.
Both land directly on this post's thesis.

Fact fix applied: Cisco's Feb 2026 Silicon One G300 win is liquid-cooled consolidation
(roughly six boxes' worth of work in one, ~70% efficiency gain), NOT "hardware that runs
cooler." Dense AI silicon runs hotter; the move is to cool it more efficiently and need
less of it. The draft now says that accurately, which keeps the sharpest readers nodding
instead of wincing.

Hook A: We spent twenty minutes arguing about how to cool a rack of GPUs before someone asked the better question: why are we trying to cool six racks' worth of heat at all?
Hook B: Two people taught me the same lesson on the same morning, and neither of them knew the other had.

Post:

We spent twenty minutes arguing about how to cool a rack of GPUs before someone asked the better question: why are we trying to cool six racks' worth of heat at all?

A few of us were talking about data center cooling. GPUs run hot, air only moves so much heat, and we went deep into the weeds on how to pull more of it out of the room. Then someone brought up the newer liquid-cooled gear that does six boxes' worth of work in one. The whole question shifted. We weren't trying to cool the room better. We were asking why we needed that much hardware running that hot in the first place.

That same morning, an exec told a story about an airline buried in lost luggage. For years they worked on finding lost bags faster. The breakthrough came when they stopped optimizing the search and started preventing bags from getting lost in the first place. The efficiency problem didn't get solved. It got eliminated.

Two unrelated conversations. Same lesson. We pour energy into doing a broken thing more efficiently when the better move is one step upstream.

I catch myself doing it constantly. Tuning the alert threshold instead of fixing the thing that trips it. We finally let the tooling correlate the noise, and half our alerts turned out to be one problem wearing forty hats.

Next time you're optimizing something, it's worth asking: am I making this faster, or am I just making peace with a problem I could remove?

Where have you seen real effort go into fixing something that should have been prevented?

(Note: the "forty hats" alert line is the most relatable beat for the Network Engineer
crowd, but it assumes you've actually deployed alert correlation. If that's not true for
your team, swap back to: "Tuning the alert threshold instead of fixing the thing that
trips it. Speeding up a process that shouldn't exist.")

---

## BONUS — two fresh Series A directions (not yet drafted)

If neither finalist is the one, here are two new angles I can draft on the same workflow.
Both avoid topics you've already covered (ownership, bad-news-early, one-on-ones, the
second outage, translation, listening).

1. "The runbook nobody opened." The outage where the documented fix existed and still
   didn't get used, because it was stale / no one trusted it / no one knew it was there.
   Lesson: documentation only counts if it survives contact with a 2am incident. Ties to
   the 2026 AIOps push toward automated, living runbooks. Lens: systems thinking (the gap
   between the stated system and the actual one).

2. "Hiring for the question, not the answer." You already ask interview candidates how
   they approach a change (Candidate 1). Spin that into its own post: the best technical
   hire you made gave a worse on-paper answer but asked better questions. Lens: Creighton
   "forming agents of change" / cura personalis, woven quietly. Topical hook: the 2026
   debate about what to hire for when AI handles more of the rote technical work.

---

## My recommendation

Lead with Candidate 2 ("The Better Question Is Upstream"). It's your most current angle
(GPU/power and alert fatigue are exactly what your Network Engineer audience is living
this quarter), it's the saved idea with the strongest built-in story, and the reframing
lesson travels well beyond IT. Candidate 1 is the safer, more evergreen pick and a great
follow-up the week after.

Reply with the one you want and I'll do a final line-level pass and set the post date.
