---
date: YYYY-MM-DD
series: A
status: draft
tags: [series-a, systems-thinking, reframing, problem-solving, upstream]
lens: systems thinking (leverage points, upstream intervention)
word_count: ~250
---

<!--
HOOK OPTION 1:
We spent twenty minutes arguing about how to cool a rack of GPUs before someone asked the better question: why are we trying to cool six racks' worth of heat at all?

HOOK OPTION 2:
Two people taught me the same lesson on the same morning, and neither of them knew the other had.

ARC: situation (cooling debate + airline story) -> lesson (go upstream) -> implication (alerts/process) -> closing question
FACT NOTE (verified 2026-06): Cisco's Universal Quantum Switch is real, announced 2026-04-23, operates at room temperature over standard telecom fiber (avoids the cryogenic cooling most quantum hardware needs). Jamie's recollection was correct; the earlier "G300 liquid-cooling" correction was a reviewer error.
-->

We spent twenty minutes arguing about how to cool a rack of GPUs before someone asked the better question: why are we trying to cool six racks' worth of heat at all?

A few of us were talking about data center cooling. GPUs run hot, air only moves so much heat, and we went deep into the weeds on how to pull more of it out of the room. Then someone brought up the new Universal Quantum Switch that Cisco announced in April of this year that operates at room temperature. The whole question shifted. What if we didn't have to worry about cooling the room, what if the equipment changed to produce less heat in the first place?

That same morning, an exec told a story about an airline buried in lost luggage. For years they worked on finding lost bags faster. The breakthrough came when they stopped optimizing the search and started preventing bags from getting lost in the first place. The efficiency problem didn't get solved. It got eliminated.

Two unrelated conversations. Same lesson. We pour energy into doing a broken thing more efficiently when the better move is one step upstream.

I catch myself doing it constantly. Tuning the alert threshold instead of fixing the thing that trips it. We finally let the tooling correlate the noise, and half our alerts turned out to be one problem wearing forty hats.

Next time you're optimizing something, it's worth asking: am I making this faster, or am I just making peace with a problem I could remove?

Where have you seen real effort go into fixing something that should have been prevented?
