# Contributing a route

Thank you. A good route turns what one person learned the hard way into a path anyone can walk.

## The rules

1. **Situations, not titles.** "Hold the number" beats "CFO". Put roles in `roles:` so the recommender can find it.
2. **Everyone can earn every achievement.** Achievement and path rules may only use the six dimensions (clarity,
   inquiry, influence, pushback, closing, composure), grades, meeting kinds, goals, commitments, accuracy and levels.
   Never `track:`: a personal track only exists for the people who follow your route.
3. **The lens nudges, it never re-grades.** At most 80 words that explain how to read the anchors in these meetings
   ("a recommendation that names its trade-off is Influence 4+"). Do not invent new scores.
4. **No real people, no real meetings.** Use roles ("Their CFO", "Procurement"). Every example is invented.
5. **Small and checkable.** 0-4 focus tracks, 3-6 path steps, 1-8 achievements, 3-12 drills, under 8 KB.
   Title a step by the habit ("Push back with evidence in 3 meetings"), not the score: the app spells out the rule.
6. **Grade what research supports.** A lens line that says "is Inquiry 4+" must describe a behaviour with research
   behind it: follow-up questions until something is pinned, numbers and names instead of adjectives, actions that
   leave with an owner and a date, concessions only with a condition or a trade, pushback that acknowledges the point
   and then gives the fact or the alternative, and when you chair a group decision, the question first and your view
   last. A habit without that evidence (a fixed opening ritual, a question count, a talk ratio, silence for its own
   sake) is welcome as a habit: say "a good habit, not a score", or put it in a track or a drill. Sidekick's list of
   claims and sources is `docs/EVIDENCE.md` in the app repository.

## The rule grammar

```
skill:<dimension> >= <1-5> x<n>         n rounds where that dimension scored at least that
moments:<grade> x<n> [skill:<dimension>] n moments of that grade (brilliant, great, good, routine, inaccuracy,
                                         mistake, missed, blunder)
goal:achieved x<n>                       n meeting goals achieved
goal:streak <n>                          a goal streak of n weeks
commitments:ontime x<n>                  n of your commitments closed on time
accuracy >= <0-100> x<n>                 n rounds at that accuracy or better
level:<dimension> >= <1-100>             a skill level
band:<dimension> <= <5-30>               a calibrated skill (narrow uncertainty band)
achievement:<id>                         another achievement
```

Counting rules (`skill`, `moments`, `goal:achieved`, `commitments`, `accuracy`) take qualifiers after the rule:

```
kind:<kind>[|<kind>...]   negotiation, discovery, briefing, status, one_on_one, demo, interview, workshop, social, test
attendees>=<n>            meetings with at least n people
lang:<xx>                 meetings held in one language (es, en, pt, …)
```

Example: `moments:great x3 skill:influence kind:workshop|briefing attendees>=6`.

## The pull request

- Add `routes/<slug>/route.md`; the folder name and `slug:` must match.
- Paste it into the [submit form](https://learnwithsidekick.com/community/submit), which lints as you type, until
  it shows no errors (or submit it there: the form opens the pull request for you).
- In the description: which meetings you tested it in, and one invented example for each achievement.
- A maintainer lints and reads every line before merging; a route with a lint error is not merged.
- Bump `version:` when you change a route that is already merged.

Exported your own Growth from Sidekick (Settings › Growth › Export my Growth as a route)? Rename it, re-read every
line for names, and send it.
