I like deep diving into rabbit holes concering all sorts of OSS routing & navigation applications, and how they can be integrated in all sorts of environments & use cases. I do not truly enjoy working on closed-source software as much, however, I do it with an equivalent level of effort if compensated properly:)

This description's whole reason of existence: so I can separate my personal preferences from the shared, public projects I contribute to. I'm well known on the [valhalla repo](https://github.com/valhalla/valhalla) for fairly strict (I guess?) comments, mostly in order to protect myself. I try to be fair by explaining my reasoning, which I should maybe keep in a central place so I can save the time to write those loooong comments.

### My contribution tolerance

This is what I want to convey mainly. Spending one's main "working life" (or what people commonly think of as "8+ hours per day") writing code which is free to look at, download, compile & run, while at the same time making sure one can put food on the table; that's not a piece of cake. Do understand that up to 80 - 100 % of the overall time a OSS developer spends on developing/maintaining the project is not paid by anyone. In fact, for me, Valhalla is almost the only OSS project I ever got paid for by anyone, out of tens of which I maintain/created.

So, to protect myself (my mental health, my time etc), there are a few things I find to tolerate in contributions to projects I (co-)maintain:
- **AI stance**: I'm still fully aligned with https://github.com/valhalla/valhalla#generative-ai-usage.
- **wordy issues**: might be my/our fault for not guiding issue creation a bit better, but lengthy issues which could be boiled down to 1-2 single crisp sentence(s) or live examples are obnoxious to me and it's likely I'll ignore them.
- **no sign of self-help**: we/I try hard to keep good documentation in all my projects. However, getting docs right is hard work too if one wants to avoid staleness as much as possible but still be helpful enough. Asking for my help without showing me what was tried already or leaving some note to that effect: I see that as disrespectful of my (or any maintainer's) time. In case of trouble, the first instinct should be to google and look at the technical project docs, not ask for other people's (unpaid) time & expertise. I'm happy to untie any remaining knots. Using AI to explore and understand foreign code bases is IMHO the best way to make use of it.
- **text in screenshots**: OK, I admit, this is an irrational pet peeve of mine; it just drives me crazy quite regularly: pretty please do not ever make screenshots of _text_ and paste the screenshot instead of pasting, uh, the text. Not in comments, not in READMEs, not in anything that renders to a document on Github. My priority-ordered reasoning:
  - does a maintainer really, really, really have to manually type the command he/she sees a screenshot of, so it can be reproduced? Really? That's absolutely disrespectful and should be punishable under the law hahah
  - screenshots of text are unpredictable in UX/UI: please try to look at a screenshot of text on a mobile!
  - it's text. Copy/paste it. Everything's markdown, use it, it saves all of us time!

I think often enough people are not thinking about the consequences of their actions on other people. Not out of bad intentions necessarily, just out of mindlessness (as in opposite of mindfulness).

### About Valhalla ❤️

This deserves a few words on its own. I owe it and its authors so much!

I consider this my "first, real" OSS project in all the facets of software lifecycle/maintenance/development, despite having had a multi-year OSS maintenance track record even before. I got to Valhalla the hard, but at least memorable, way. Long long days and nights of the wild rollercoaster only frantic trial & error C++ novice debugging sessions could give me at the time. I was co-running a tiny FOSS4G consultation company in the OSS routing space, but never got my hands dirty on _actual_ routing engine code before. I got engaged with Valhalla for a commercial project which had some promise of becoming much more than initially contracted. Our usual projects were "custom" routing use cases, often in combination with a QGIS plugin. Before I really knew it, I was already fascinated by Valhalla's capabilities. So I completely over-sold my Valhalla prowess and got the quite sizable gig. After making the rounds to contact a few proven Valhalla experts to help me out on very short notice and getting only rejections, I _had to_ very quickly become a Valhalla & C++ expert myself. I already sold the project, I couldn't flunk out!

That's 7 years ago now and little did I know about Valhalla's capabilities, and even less, about Valhalla's _potential_ capabilities. This is the project and community which makes me a happier and I think in many ways better human being.

We (Kevin, Chris, me) try to meet twice per week to discuss all sorts of topics, often Valhalla related (PRs, features etc), equally often life or dev ethics etc. We also constantly have to communicate so we can align on our own interests and of the project as a whole. Maintaining such a complex software requires more work than one thinks, a bit more if you throw in (rarely) conflicting commercial or ethical interests among maintainers. It comes easier every day, as we continue to get to know each other better and evolve our workflows. Still, it's a lot of work/time, because we all want only the best possible path for the project!
