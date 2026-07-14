---
date: 2026-07-14
series: A
status: draft
tags: [series-a, change-management, crowdstrike, vendor-risk, blind-spots, systems-thinking]
lens: systems thinking (the stated system vs the actual system)
word_count: ~245
---

<!--
HOOK OPTION 1:
Two years ago this week, a file none of us approved rebooted eight and a half million computers. The part that still bothers me isn't the outage.

HOOK OPTION 2:
We had change control. We had staging rings. We had approvals. None of it covered the thing that actually took everyone down.

CALENDAR PEG: July 19, 2026 = 2-year anniversary of the CrowdStrike/Windows outage (July 19, 2024).
FACT BASIS (verified): ~8.5M Windows machines BSOD'd; $5.4B est. losses for top-500 US firms; the key lesson was that sensor-version staging policies did NOT govern channel-file content updates.
PLACEHOLDERS FOR JAMIE: were you hit that day (you were at CRST then)? What did your own audit actually find? Swap the middle paragraph for your real moment.
ARC: hook (anniversary) -> the blind spot -> the audit story -> lesson -> closing question
-->

Two years ago this week, a file none of us approved rebooted eight and a half million computers. What still haunts me isn't the outage.

It's what it exposed. Most of us had change control. CAB meetings, approval gates, maintenance windows. And the update that caused the biggest IT outage in history didn't pass through any of it, because content updates from the vendor didn't count as changes in anyone's process. The stated system said nothing changes without approval. The actual system had a side door.

Afterward, we tried to make a list. Every agent on every endpoint that could receive an update without a ticket. Antivirus content. Management tools. Browser extensions pushed by vendors. Firmware that phones home. The list was nowhere near complete. It was still longer than I expected, and I've been doing this a long time.

We couldn't close every side door. Some updates need to be fast because that's where the protection comes from. But there's a difference between a door you've looked at and decided to leave open, and a door you didn't know was there.

Two years later, that's my anniversary question for any team that runs endpoints. Not "could CrowdStrike happen again." It could. The question is whether you know every path a change can take into your environment without passing through your process.

How many things on your network can update themselves without anyone approving it? Do you know the number? And is there anything you can do about it?
