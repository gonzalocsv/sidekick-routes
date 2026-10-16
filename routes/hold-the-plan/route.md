---
slug: hold-the-plan
title: Hold the plan
summary: Scope, dates and risks said out loud, and traded, never absorbed.
roles: [project manager, program manager, delivery, pmo, scrum master]
kinds: [status, workshop, negotiation, briefing]
after: []
author: sidekick
version: 3
license: CC-BY-4.0
---

## Lens
A plan survives when changes are traded, not absorbed. Pushback 4+ means a new request was named as a change, with
its cost in scope or date and a decision asked for, in the room. Clarity 4+ means risks and dates said as concrete
facts, not reassurance. Closing 4+ means a decision left with a name and a date. Saying "we'll find a way" to a new
request is Pushback 1.

## Focus tracks
- Trade scope for date: every new request gets a cost in scope or date, and a decision asked for (Pushback)
- Say the risk plainly: names the top risk as a fact, with what would trigger it (Clarity)
- Decision, name, date: asks who decides and by when, and gets it (Closing)

## Path
- [ ] A request traded, not absorbed  `moments:great x1 skill:pushback kind:status|workshop|negotiation`
- [ ] Speak in specifics in 3 meetings  `skill:clarity >= 4 x3 kind:status|briefing|workshop`
- [ ] Three decisions closed with a name and a date  `skill:closing >= 4 x3 kind:status|workshop`
- [ ] Five commitments closed on time  `commitments:ontime x5`
- [ ] Pushback Proficient  `level:pushback >= 60`

## Achievements
- `traded_not_given` · Traded, not given · `moments:great x3 skill:pushback kind:status|workshop|negotiation` · Three new requests that got a cost before a yes
- `saw_it_coming` · Plain facts · `skill:clarity >= 4 x5 kind:status|briefing` · Five rounds where risks and dates were said as plain facts
- `decided_in_room` · Decided in the room · `moments:great x3 skill:closing kind:workshop|status` · Three decisions that left with a name and a date
- `held_the_date` · Held the date · `commitments:ontime x10` · Ten commitments closed on time
- `calm_under_change` · Calm under change · `skill:composure >= 4 x5 kind:status|negotiation` · Five rounds where a change request did not rattle you

## Drills
- Sponsor: "Small thing: can we add the reporting module before launch? Same date." (Pushback)
- Steering group: "Just give us the status. Are we green or not?" (Clarity)
- Team lead: "The integration might slip, but let's not alarm anyone yet." (Clarity)
- Sponsor: "Let's decide on the vendor next time, when everyone is here." (Closing)
- Stakeholder: "Why wasn't this risk flagged earlier?" (Composure)
- Vendor: "We'll need two more weeks, but it won't affect your launch." (Inquiry)
