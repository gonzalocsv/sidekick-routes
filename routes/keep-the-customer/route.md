---
slug: keep-the-customer
title: Keep the customer
summary: Renewals and reviews that find the risk early, own the escalation, and earn the expansion.
roles: [customer success, csm, account manager, support, onboarding]
kinds: [status, one_on_one, briefing, discovery]
after: []
author: sidekick
version: 3
license: CC-BY-4.0
---

## Lens
A customer rarely says they are leaving; they say "fine". Inquiry 4+ means follow-ups until a real risk or need came
out, past "fine". Composure 4+ means an escalation taken with an apology, a short factual explanation and a fix with
a date; blaming others or arguing the facts is Composure 1. Closing 4+ means both sides leave with a dated next
step. Asking what would make them renew is a good habit, not a score.

## Focus tracks
- Ask the renewal question: asks what would make them renew, and what would not (Inquiry)
- Own the escalation: acknowledges the problem, explains briefly without blame, commits to a fix and a date (Composure)
- Two next steps: ends with their next step and yours, both dated (Closing)
- Name the win: states the one result they got, in their words (Clarity)

## Path
- [ ] Find the real issue in 3 customer reviews  `skill:inquiry >= 4 x3 kind:status|one_on_one|briefing`
- [ ] An escalation owned calmly  `moments:great x1 skill:composure kind:status|one_on_one`
- [ ] Three reviews closed with next steps both ways  `skill:closing >= 4 x3 kind:status|briefing`
- [ ] Five commitments to customers kept on time  `commitments:ontime x5`
- [ ] Composure Proficient  `level:composure >= 60`

## Achievements
- `renewal_question` · Past "fine" · `skill:inquiry >= 4 x5 kind:status|one_on_one|briefing` · Five reviews where you followed up until the real risk or need came out
- `owned_it` · Owned it · `moments:great x3 skill:composure kind:status|one_on_one` · Three escalations owned without blame, with a fix and a date
- `both_ways` · Both ways · `skill:closing >= 4 x5 kind:status|briefing` · Five reviews that ended with next steps on both sides
- `their_words` · In their words · `skill:clarity >= 4 x5 kind:status|briefing` · Five reviews said in their numbers and names
- `kept_every_promise` · Kept every promise · `commitments:ontime x10` · Ten customer commitments done on time

## Drills
- Customer: "Honestly, everything is fine. No complaints." (Inquiry)
- Customer: "Your outage cost us a day. I want to know what you're going to do about it." (Composure)
- Customer: "We're reviewing all our vendors this quarter." (Inquiry)
- Customer champion: "My boss is asking why we pay for this." (Clarity)
- Customer: "Can you just throw in the extra seats? We've been with you for years." (Pushback)
- Customer: "Thanks for the update. Talk next quarter?" (Closing)
