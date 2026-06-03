---
date: 2026-03-16
series: A
status: published
tags: [series-a, documentation, firewall, technical-debt, ownership]
---

Three active firewall rules. No documentation. No owner. No idea what would break if we removed them.

We found them last month during a routine audit. They were there. They were active. But no tickets referenced them, no documentation covered them, and the person who added them had left the team two years ago.

We spent half a day tracking down what they were for before we felt safe enough to touch them. Turns out two were for a project that had been decommissioned. The third was still needed, but we only figured that out by spending even more time on research.

Exceptions happen. A temporary rule for a vendor demo. A one-off port opening for a contractor. A quick bypass to unblock someone during an outage.

The problem isn't that we make exceptions. The problem is we don't document them the same way we document everything else.

I've been guilty of this more times than I want to admit. You make the change, it works, and you move on. Documenting it feels like extra work when the fire is out.

What we do now is simple. Every exception gets a ticket and a note in the change log with an expiration date. Even if it's supposed to be temporary. Especially if it's supposed to be temporary.

Because undocumented exceptions don't stay exceptions. They become landmines.

How does your team make sure temporary fixes don't turn into permanent mysteries?
