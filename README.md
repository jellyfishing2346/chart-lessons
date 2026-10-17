# Good Charts vs Bad Charts

An interactive lesson that teaches students how to spot misleading, confusing and cluttered charts, and how to fix them.

**Live site:** https://jellyfishing2346.github.io/chart-lessons/

## What's inside

- **Three levels** (🌱 Beginner, 🌿 Intermediate, 🌳 Advanced): a picker at the top changes how many stories, checks and quiz questions students see, adds "Go deeper" notes at Advanced, and links each level's own worksheet.
- **How to read any chart**: think like a reporter (notice, wonder, write a headline), then check whether the chart's story is true.
- **Spot the mistake**: five everyday stories (a student council election, screen time, school lunch, a basketball team, a class survey). Each is drawn twice from the same numbers, with the headline each chart tells and why one is misleading.
- **Quiz**: 4 questions with hints (Beginner), 8 (Intermediate) or 11 (Advanced, including three where breaking a rule might be OK), with a score at the end.
- **Tell your own story**: five steps for turning a question into an honest chart with a headline.
- **Your turn**: a real-world activity with a printable worksheet.
- **All the mistakes**: a searchable list of 17 common chart mistakes, why each is a problem, and how to fix it.
- **Great charts, further reading and a word list** of chart terms in plain English.

## Files

| File | What it is |
|------|------------|
| `index.html` | The whole website: page, charts, quiz and data. |
| `d3.min.js` | The charting library (D3 v7.8.5), stored here so the site doesn't depend on another server. |
| `worksheet-beginner.pdf`, `worksheet-intermediate.pdf`, `worksheet-advanced.pdf` | Printable student worksheets, one per level, linked from the "Your turn" section. |
| `README.md` | This file. |

The teacher answer key is kept out of this repository on purpose, because anyone can see the files in a public repo.

## Updating the site

Replace a file by uploading a new version with the same name (**Add file → Upload files**), then commit. GitHub Pages republishes within a minute or two.

## Sources and credits

- Sarah Leo, ["Mistakes, we've drawn a few"](https://medium.com/the-economist/mistakes-weve-drawn-a-few-8cdd8a42d368), *The Economist*, 2019. Several of the mistakes follow her redesigns.
- The "notice, wonder, headline" approach is inspired by The New York Times Learning Network's [What's Going On in This Graph?](https://www.nytimes.com/column/whats-going-on-in-this-graph)
- Further examples from the Financial Times Visual Vocabulary, Claus Wilke's *Fundamentals of Data Visualization*, the Datawrapper blog, Edward Tufte, Alberto Cairo and others listed on the site.
- All chart numbers on the site are made up for practice and are not real data.
- Charts drawn with [D3](https://d3js.org/) (ISC licence).
