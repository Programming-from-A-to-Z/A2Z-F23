# Regular Expressions

## Aside: DOM and ES6 Review

- 🍿 [Arrow Function video tutorial](https://youtu.be/mrYMzpbFz18)
- 🍿 [Promises videos](https://www.youtube.com/playlist?list=PLRqwX-V7Uu6bKLPQvPRNNE65kBL62mVfx)
- 🍿 [Word Interactor video and code example](https://thecodingtrain.com/challenges/38-word-interactor)

## Regex Notes and Videos

- 📚 [2016 Notes and Examples](https://shiffman-archive.netlify.app/a2z/regex)
- [Regular Expression Video Tutorials](https://www.youtube.com/watch?v=7DG3kCDx53c&list=PLRqwX-V7Uu6YEypLuls7iidwHMdCM6o2w)
  - 🚨 [Intro to Regex](https://youtu.be/7DG3kCDx53c?list=PLRqwX-V7Uu6YEypLuls7iidwHMdCM6o2w) - ~11 min
  - 🚨 [Meta-Characteres](https://www.youtube.com/watch?v=YTocEnDsMNw&list=PLRqwX-V7Uu6YEypLuls7iidwHMdCM6o2w&index=2) - ~16 min
  - 🚨 [Character Classes](https://www.youtube.com/watch?v=EfJU0Y9WAZ4&list=PLRqwX-V7Uu6YEypLuls7iidwHMdCM6o2w&index=3) - ~14 min
  - 🚨 [Capturing Groups](https://youtu.be/c9HbsUSWilw?list=PLRqwX-V7Uu6YEypLuls7iidwHMdCM6o2w) - ~13 min
  - 🍿 [Back References](https://youtu.be/Z66TeSTcP-Q?list=PLRqwX-V7Uu6YEypLuls7iidwHMdCM6o2w) - ~4 min
  - 🚨 [test() and match()](https://youtu.be/W7S_Vmq0GSs?list=PLRqwX-V7Uu6YEypLuls7iidwHMdCM6o2w) - ~17 min
  - 🍿 [exec()](https://youtu.be/t029QcVHtas?list=PLRqwX-V7Uu6YEypLuls7iidwHMdCM6o2w) - ~7 min
  - 🚨 [split()](https://youtu.be/fdyqutmcI2Q?list=PLRqwX-V7Uu6YEypLuls7iidwHMdCM6o2w) - ~9 min
  - 🍿 [replace()](https://youtu.be/7a-a6lKoyIQ?list=PLRqwX-V7Uu6YEypLuls7iidwHMdCM6o2w) - ~19 min
- 📕 [Chapter 9: Regular Expressions](https://eloquentjavascript.net/09_regexp.html) from [Eloquent JavaScript](https://eloquentjavascript.net/) by Marijn Haverbeke.
- 📚 [Introducing Regular Expressions: JavaScript and TypeScript](https://learning-oreilly-com.proxy.library.nyu.edu/library/view/introducing-regular-expressions/9781484225080/A434767_1_En_1_Chapter.html) by Jörg Krause. (This is the full book! If you prefer this to the videos I recommend chapters 1-3)

## JavaScript Regex functions

- 🔗 JavaScript Regex reference: [`test()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp/test), [`exec()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/RegExp/exec)
- 🔗 String: [`match()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/match)
- 🔗 Splitting with regex: [`split()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/split)
- 🔗 Replace with regex: [`replace()`](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/String/replace)

## Libraries and Games

- 🔗 [randexp.js](http://fent.github.io/randexp.js/)
- 🔗 [Regex Golf](https://alf.nu/RegexGolf)
- 🔗 [Regular Expression Crossword](https://regexcrossword.com/)

## Assignment

Design an exercise around regular expressions. Here are some ideas if you are feeling stuck! (To be clear, just do **one** thing, and writing code is not required for this assignment!)

### Regular Expressions Experiments

- Experiment with using Regular Expressions in a text editor. What new powers does this unlock in your workflow? Write up a post documenting your experiments. Ideas you can try:

  - Write a regular expression to find and remove all HTML tags.
  - Find all emails or phone numbers in a document.
  - Parse a markdown file and find all headers (h1, h2, h3, etc.).

- Play an [online Regular Expressions game like these two above](#libraries-and-games) or share any you find! Write up a post documenting your experience.

### Regular Expressions in JavaScript

- Chop up a text into words using `split()` and rebuild the text as separate `<span>` elements that you can interact with individually. [Here is example code](https://editor.p5js.org/codingtrain/sketches/Jr3zCQw-9) from [this video](https://thecodingtrain.com/challenges/38-word-interactor).
- Create a programmatic version of the algorithm you developed for the constrained writing exercise.
- The [Flesch Index](https://en.wikipedia.org/wiki/Flesch%E2%80%93Kincaid_readability_tests) is a "reading level" score for a passage in English. Here is a [p5 sketch that calculates the Flesch Index](https://editor.p5js.org/a2zitp/sketches/OQx3A3Sa0) for a body of text. How could this be improved / changed with regular expressions?
- Create a mad libs generator. For reference [here is a video about making Mad Libs with p5.js](https://thecodingtrain.com/challenges/39-madlibs-generator)!
- Create a "word replacer" (all words that start with E to words that start with A, all fruits with vegetables, etc.)

## Data and APIs

In preparation for next week, add a link to a data source or API (even just data that appears in raw form on a web page) that interests you! Don't worry about this too much, anything will do! I'll use this list to prepare examples for next week.

- add a link to your API / data source here
- Athena -- [The New York Times Developer Network](https://developer.nytimes.com)

## Add your assignment below via Pull Request

_(Please note you are welcome to post under a pseudonym and/or password protect your published assignment. Here is some [helpful information on privacy options for an NYU blog](https://nyu.service-now.com/sp?id=kb_article&sysparm_article=KB0012245&sys_kb_id=b2ddc9da004aa1002a5d036a271e5f70&spa=1). Finally, if you prefer not to post your assignment at all here, you may email the submission.)_

- Name -- [assignment title](assignment url)
- Jane -- [wk02hw](https://janecheng.notion.site/Week-2-Regular-Expressions-869134d190d04cd5bd56f98a038216d0?pvs=4)
- Lan -- [I MADE SOME CAKES!! 🍰](https://yichunlan.com/A2Z-Week-2)
- Athena -- [Word Interactor v1.2](https://www.notion.so/athenazhou/02-Regular-Expressions-91708407463842669e398221156765e8?pvs=4)
- Cindy -- [Pikachu](https://rhetorical-croissant-d02.notion.site/week2-Regex-Cindy-Wang-2d92de4e68f145e89b40df0cda28b97f?pvs=4)

## Emoji Key for Video Tutorials, Readings, and more

- 🚨 Watch this video tutorial! (this is technical info needed for the examples). Of course if you alreaddy know this material, you can skip.
- 🔢 This is found in a group, maybe pick just one to check out!
- 🍿 Additional video if you have a particular interest and want to do a deeper dive.
- 📕 Required reading! Let's make sure we all have read this.
- 📚 Optional additional reading for a deeper dive.
- 💻 Code examples here!
- 🔗 Extra reference material / link
