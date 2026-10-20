# Before the site goes public

A checklist for the people working on this site. Everything here should be done, or
consciously decided against, before the link goes beyond the working group. Tick items
off by changing `[ ]` to `[x]` and committing.

## Must do

- [x] **"Take the survey" buttons linked.** All four (top bar, hero, "Tell us your
      thoughts" section and its record) open the Microsoft Forms survey in a new tab
      (search `index.html` for `data-survey`).
- [ ] **Check the survey does what the page says.** The page says the survey takes only
      a few minutes, the email is used only to verify the respondent, and answers remain
      private with all data anonymized. Make sure the form's settings match, or change
      the text.
- [x] **Ledger link removed.** The page no longer links to or names the faculty Ledger; its figures
      (≈240–250 tenure lines, ≈$208,000 per line) remain and are attributed to a faculty financial
      analysis.
- [ ] **Confirm nothing from the administration's internal planning site is on the page.**
      Everything was rebuilt from public sources on 16 October; the Sources record says
      so in its first sentence. If anyone adds material later, keep that rule: the page
      can refer to the internal site's existence but must not quote or paraphrase it.
- [ ] **Re-read every "faculty have been told" claim.** The self-support passages in
      "The bill" rest on what faculty were told, not on a public document, and the page
      says so. Make sure the people who were told are comfortable with how it is stated,
      and that the sentence about the Academic Senate ("raised but not fully discussed,
      nor is it clear all faculty have been told") is still accurate on the day of launch.
- [ ] **Confirm the standing statement in the hero.** "Academic Senate reports from every
      college on campus were uniformly and overwhelmingly against YRO and the rush to
      implement it." Someone who was in the room should sign off on "every college" and
      "uniformly."
- [ ] **Decide the byline.** The page says "Prepared by Cal Poly faculty" and the footer
      says it is not a university publication. Decide whether to name a group, an
      address for questions, or individual authors, and whether the survey tool needs a
      contact for privacy questions.

## Check the facts one more time

- [ ] The two Pittsburgh figures taken from the collaborator's slide (the $15M deficit and
      "most would not have come on a summer track"), cited to the 1971 Hofstra review
      (ERIC ED 056 646) and the 1965 Michigan Daily. The texts were not read for this
      page; verify the wording against the originals or soften the cells.
- [ ] The 1997 estimate on the history chart (≈2,100 students, derived as 15 percent of
      the 1998–99 full-time-equivalent enrollment). Replace with a real figure from
      Institutional Research if one can be found, and if possible fill the 2007–2024 gap
      in the same chart.
- [ ] The 20–25 percent "away each fall and spring" figure, which comes from the
      60 / 20–25 / 20–25 track split reported by Mustang News (October 2025). If the
      administration has published a different split, the ring, the matrix row and the
      Notes all change.
- [ ] The ≈240 new tenure lines, ≈$208,000 per line and ≈$50M a year, which are the
      figures from the faculty financial model at the time of writing. Recompute before launch.
- [ ] The dates on the two timelines (application opens October 2027, offers March 2028,
      commitment May 1, new faculty hired January 2028, first classes August 2028).
      The admissions dates are the standard Cal State calendar; the hiring date is an
      estimate. Adjust if the campus publishes its own.
- [ ] "Figures current to 16 October 2026" in the footer and "Read 16 October 2026" in
      the hero. Update both on the day of launch.

## Nice to have

- [ ] A short "About this page" or "Who we are" section, if the byline decision calls
      for one.
- [ ] A link checker pass: every URL in the Sources record should resolve. The Cal Poly
      Academic Affairs YRO page is already a placeholder; the Sources entry says so.
- [ ] A phone pass: open the page on a phone and tap through all five records and the
      chart popovers (they open on tap).
- [ ] Open Graph image, so the link unfurls with a picture when shared in Slack, email
      or on social media. The title and description tags are already in the `<head>`.
- [ ] A custom domain, if `slowyro.netlify.app` is not the address you want on flyers.

## How to publish a change

Edit `index.html`, commit, push to `main`. Netlify redeploys within about a minute.
