---
slug: ship-the-roadmap
title: Ship the roadmap
summary: Discovery that finds the problem, and roadmap talks that say what you will not build.
roles: [product manager, product, engineering manager, tech lead, founder]
kinds: [discovery, workshop, demo, status]
after: []
author: sidekick
version: 3
license: CC-BY-4.0
---

## Lens
Product meetings fail on politeness. Inquiry 4+ means asking what they did last time, what they use today and what
it costs, not whether they would like the feature; "would you use it?" is routine. Pushback 4+ means saying what
will not be built this quarter, and why. Influence 4+ means a decision argued from evidence the room can check. A
demo that ends with no reaction asked for and no next step is Closing 2.

## Focus tracks
- Problem, not feature: asks what they do today and what the problem costs before discussing solutions (Inquiry)
- Say what you won't build: names what is out of this quarter, and why (Pushback)
- Decide on evidence: argues the call from data or a user example, not opinion (Influence)
- Ask for their reaction: closes a demo by asking what they would change, and agrees the next step (Closing)

## Path
- [ ] Pin down the need in 3 discovery meetings  `skill:inquiry >= 4 x3 kind:discovery|demo`
- [ ] A no with a reason  `moments:great x1 skill:pushback kind:workshop|status`
- [ ] A call made on evidence  `moments:great x1 skill:influence kind:workshop|discovery`
- [ ] Three demos closed with a question  `skill:closing >= 4 x3 kind:demo|discovery`
- [ ] Pushback Proficient  `level:pushback >= 60`

## Achievements
- `found_the_problem` · Found the problem · `skill:inquiry >= 4 x5 kind:discovery|demo` · Five discovery rounds that got to the cost of the problem
- `said_not_now` · Said not now · `moments:great x3 skill:pushback kind:workshop|status` · Three times you named what is out, and why
- `evidence_won` · Evidence won · `moments:great x3 skill:influence kind:workshop|discovery` · Three calls the room accepted on evidence
- `demo_asked_back` · Demo asked back · `skill:closing >= 4 x5 kind:demo` · Five demos that ended with their reaction and a next step
- `shipped_on_time` · Shipped on time · `commitments:ontime x5` · Five product commitments done on time

## Drills
- Customer: "We'd love a dashboard. Everyone has one." (Inquiry)
- Sales lead: "If we don't build the export by Q2 we lose the deal." (Pushback)
- Engineering lead: "We think the rewrite is the right call. It just feels cleaner." (Influence)
- Customer: "Looks great, thanks for the demo." (Closing)
- Your CEO: "Why isn't this on the roadmap?" (Composure)
- Designer: "Users said they want it. We asked them." (Inquiry)
