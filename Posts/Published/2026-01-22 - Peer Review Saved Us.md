---
date: 2026-01-22
series: A
status: published
tags: [series-a, peer-review, change-management, fundamentals, discipline]
---

We were getting ready to push a routing configuration update to every office switch.

We had tested it in the lab. We felt good about the underlying design. Confidence was high.

The part that almost got us wasn't the routing logic.

It was a subnet mask typo in the deployment script.

The engineer driving the change wasn't sold on the peer review step. He felt like it would slow things down. And honestly, he also felt like "I know what I'm doing." The process felt to him like a signal that management didn't trust the engineers.

He submitted it anyway.

The reviewing engineer pulled the script and caught it right away.

Here's the scary part.

The config would have worked when deployed. Nothing would have immediately failed. We probably would have celebrated and moved on.

But that one mask value would have created future routing conflicts because it would have made our address space look like it overlapped between sites. The kind of problem that shows up later, under pressure, and takes way longer to unwind.

That review didn't just catch a typo.

It protected the future.

It reminded me that fundamentals are not busywork. They're how you keep today's change from becoming next month's incident.

What's one "simple discipline" your team uses that saves you from problems you never have to see?
