---
date: 2026-04-04
series: A
status: published
tags: [series-a, incidents, follow-through, lessons-learned, accountability]
---

We had the same outage twice in a year because we didn't follow through on the lesson the first time.

A year ago, a chiller went down at one of our colo data centers. Storage overheated and took down our monitoring server. No alerts went out because the thing that sends alerts was offline.

The chiller was fixed. We wrote down what was impacted. We talked about diversifying monitoring to other data centers so a failure in one location wouldn't blind us everywhere.

And then we moved on to the next thing.

Last month, the chiller went down again. Same data center. Same cascade. Same result. No alerts because the monitoring server was sitting in the room that overheated.

The first time was bad luck. The second time was on us.

I know how it happened. After an outage, you fix what broke and you're exhausted. Writing up lessons learned feels like the finish line. But the writeup isn't the work. The follow-through is.

What we do now is treat post-incident action items like any other project. They get assigned, they get scheduled, and someone owns making sure they actually happen.

Because if you don't change anything after an incident, you didn't learn anything. You just survived it.

How does your team make sure the lessons from an outage actually turn into changes instead of just turning into documentation?
