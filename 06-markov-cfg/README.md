# Markov Chains and Context Free Grammars

## [Markov and CFG slides](https://docs.google.com/presentation/d/1M8zwy7yKA7G6EzSYS8qnYRNuQ8KJkoo-M5YG6OM4vKk/edit?usp=sharing)

## Markov Chains

- 📕 [Markov Chains](http://setosa.io/blog/2014/07/26/markov-chains/) by Victor Powell and Lewis Lehe
- 🚨 [Markov Chain Coding Challenge](https://thecodingtrain.com/challenges/42-markov-chain-name-generator)
- 💻 [Markov Chain p5.js code examples](https://editor.p5js.org/a2zitp/collections/WEXEPRHuE)
- 💻 [Markov Chain node.js example](https://github.com/Programming-from-A-to-Z/Markov-Node)
- 📚 [N-Grams and Markov Chains by Allison Parrish](http://www.decontextualize.com/teaching/rwet/n-grams-and-markov-chains/)
- 📚 [2016 Markov Chains notes from A2Z](https://shiffman-archive.netlify.app/a2z/markov/)

### Markov Project References

- 🎨 [ITP Course Generator by Allison Parrish](http://static.decontextualize.com/toys/next_semester)
- 🎨 [WebTrigrams by Chris Harrison](http://www.chrisharrison.net/index.php/Visualizations/WebTrigrams)
- 📈 [Google N-Gram Viewer](https://books.google.com/ngrams), [google blog post about n-grams](http://googleresearch.blogspot.com/2006/08/all-our-n-gram-are-belong-to-you.html)
- 🎨 [King James Programming](http://kingjamesprogramming.tumblr.com/)
- 🎨 [Gnoetry](http://www.beardofbees.com/gnoetry.html)

## CFG Resources

- 🚨 [CFG with Tracery](https://youtu.be/C3EwsSNJeOE?list=PLRqwX-V7Uu6YrbSJBg32eTzUU50E2B8Ch), [Tracery by Kate Compton](http://tracery.io/)
- 📕 [Tracery: An Author-Focused Generative Text Tool](https://www.researchgate.net/profile/Quinn_Kybartas/publication/300137911_Tracery_An_Author-Focused_Generative_Text_Tool/links/5ed3c8c14585152945220c14/Tracery-An-Author-Focused-Generative-Text-Tool.pdf)
- 📚 [Context-Free Grammars by Allison Parrish](http://www.decontextualize.com/teaching/rwet/recursion-and-context-free-grammars/)
- 🍿 [CFG Coding Challenge "from scratch" with p5.js](https://thecodingtrain.com/challenges/43-context-free-grammar)
- 🍿 Additional: [Intro to CFG](https://youtu.be/Rhqk9HYiB7Q), [CFG with RiTa](https://youtu.be/VaAoIaZ3YKs)
- 💻 [CFG p5.js code examples](https://editor.p5js.org/a2zitp/collections/5IFiJuQZa)
- 💻 [RiGrammer](https://rednoise.org/rita/reference/RiTa/grammar/index.html) from RiTa library, [RiGrammar example](https://editor.p5js.org/rita-examples/sketches/7vWYB1HEn)
- 📚 [2016 Notes on Context-Free Grammar](https://shiffman-archive.netlify.app/a2z/cfg/)

## CFG Project References

- 🤖 [Art Assignment Bot](https://twitter.com/artassignbot?lang=en)
- 👹 [Monstr (a dating website, but for monsters)](http://www.plusultra.ninja/monstr.html)
- 👗 [What color is this dress?](http://www.galaxykate.com/dress/)
- 💖 [Happy Valentine's Day](http://www.galaxykate.com/apps//vday/vday.html?s=HEJ8)
- 🔬 [SCIgen - An Automatic CS Paper Generator](https://pdos.csail.mit.edu/archive/scigen/) -- _no longer working_ 😢
- 🎨 [ContextFree GenGen by Allison Parrish](http://cfgg.decontextualize.com) based off of [GenGen by Darius Kazemi](http://tinysubversions.com/gengen/) -- _no longer working_ 😢

## CFG Visual Art

- 📚 [Algorithmic Beauty of Plants](http://algorithmicbotany.org/papers/abop/abop.pdf)
- 💻 [Nature of Code L-System Chapter](https://nature-of-code-2nd-edition.netlify.app/fractals/#l-systems)
- 🍿 [L-System Coding Challenge Video](https://thecodingtrain.com/challenges/16-l-system-fractal-trees)

## Reading

These readings are background material to help you think about text data for the upcoming weeks where I plan to move towards using ML models. These readings are from several years ago, but I believe the themes and questions raised are even more relevant today in the landscape of large language models.

- 📕 [What Can Machine Learning Teach Us About Ourselves?](https://medium.com/processing-foundation/what-can-machine-learning-teach-us-about-ourselves-65b268431890), Interview with Emily Martinez, ml5.js Fellow 2020
- 📕 [The Subtext of a Black Corpus](https://medium.com/ml5js/the-subtext-of-a-black-corpus-4440de02eb32), In conversation with ITP research fellows Nikita Huggins & Ayodamola Okunseinde by Ashley Lewis

## Assignment

Try using markov chains or context free grammars. Feel free to pick just one or try both!

_(It is not required to write any new code for this assignment. You are welcome to run one or more of the provided examples with your own data. You can document the results in a blog post (or link to a web page where the text is generated). I'll include some other ideas below in case you are feeling ambitious.)_

### Markov Chains

Use one of the [existing examples](https://editor.p5js.org/a2zitp/collections/WEXEPRHuE) to generate text with your own input data. Experiment with the "order" and "maximum" length variables. Try mixing multiple texts. Copy paste your favorite outputs from the browser and document in a blog post.

Emily Martinez proposes a [series of questions to ask related to working with a corpus of text data](#emily-martinez-questions). Reflect on these questions and how they played into your process working with source texts in your documentation post.

It is not required to write any new code for this assignment, however I'll include some ideas for further exploration below.

- Design a webpage that displays the output of a markov generator a la [Allison Parrish's ITP course creator](http://static.decontextualize.com/toys/next_semester).
- Create a bot that generates its output based on a markov chain.
- Use a markov chain on something other than text. Record your own sequence of daily habits. Try musical notes. Could colors or shapes be generated with a markov chain? What else? You can find examples for [musical markov chains](https://luisaph.github.io/the-code-of-music-2018/#Markov) from Luisa Pereira's [Code of Music materials](https://luisaph.github.io/the-code-of-music-2018/).
- Thinking back to [the word counting material](https://github.com/shiffman/A2Z-F23/tree/main/04-word-counting), visualoze n-gram frequencies and/or markov probabilities.

### Context-Free Grammars

Invent your own grammar and generate text. I suggest using [Tracery](http://tracery.io/) but [you can base your code on any of my examples](https://editor.p5js.org/a2zitp/collections/5IFiJuQZa), or try [RiGrammer](https://rednoise.org/rita/reference/RiTa/grammar/index.html) from the RiTa library.

Getting results from a context-free-grammar can be tricky. Short and sweet, highly structured ideas tend to work well. For example.

- A coffee drink order generator.
- An apology generator.
- An ITP project idea generator.
- A knock knock joke generator.

Something you might consider is pulling the "terminal" words for your grammar from an API or other data source. You are also welcome to explore generative visual art with Context Free Grammars basing your exercise off of the L-System material described above. Or what else can you generate from a Context-Free Grammar? Music?

### Add your assignment below via Pull Request

_(Please note you are welcome to post under a pseudonym and/or password protect your published assignment. Here is some [helpful information on privacy options for an NYU blog](https://nyu.service-now.com/sp?id=kb_article&sysparm_article=KB0012245&sys_kb_id=b2ddc9da004aa1002a5d036a271e5f70&spa=1). Finally, if you prefer not to post your assignment at all here, you may email the submission.)_

- Name - [post title](post url)
- Athena - [06 Markov/CFG](https://www.notion.so/athenazhou/06-Markov-Chains-bd1e96a03e604a7f9a000c6bba54e805?pvs=4)
- Cindy Wang -[Markov and CFG](https://rhetorical-croissant-d02.notion.site/Cindy-Wang-Markov-cfg-e18b2bbed8784b6998735398f5196e7f?pvs=4)
- Mica -[WikiHow Generator](https://editor.p5js.org/mll9041/sketches/5vK9ScF2f)
- Kay - [Scream Movie Plot Generator](https://kayitp.wordpress.com/2023/11/09/markov-chains-scream-movie-plot-generator/)
- Mathew - [Vexations + Markov](https://www.virtualvector.xyz/programming-a2z-week-9-3/)
- Lan - [Mix News](https://yclanlan.github.io/2023-Fall-Programming-A2Z/Week06/Markov/) / [Taiwan bubble Tea Menu](https://yclanlan.github.io/2023-Fall-Programming-A2Z/Week06/RitaGrammer/)
- Jane - [Anime Generator](https://www.notion.so/janecheng/Week-8-Markov-Chains-CFGs-1cfa2b1fd5be46f185c4c9f9208ff21b)
- Lan - [Mix News](https://yclanlan.github.io/2023-Fall-Programming-A2Z/Week08/Markov/) / [Taiwan bubble Tea Menu](https://yclanlan.github.io/2023-Fall-Programming-A2Z/Week08/RitaGrammar/)
- Daniel Wai - [CFG & L-Systems](https://rough-buffer-c0b.notion.site/Week-7-CFG-and-Markov-1defe70395ef480986ec72359d7a4345?pvs=4)
- 
## Emoji Key for Video Tutorials, Readings, and more

- 🚨 Watch this video tutorial! (this is technical info needed for the examples). Of course if you alreaddy know this material, you can skip.
- 🔢 This is found in a group, maybe pick just one to check out!
- 🍿 Additional video if you have a particular interest and want to do a deeper dive.
- 📕 Required reading! Let's make sure we all have read this.
- 📚 Optional additional reading for a deeper dive.
- 💻 Code examples here!
- 📈 Class presentation slides
- 🔗 Extra reference material / link

## Emily Martinez Questions

- How can we be more intentional about what we build given the current limitations, problems, and constraints of ML algorithms?
- How do we prepare datasets and set up guidelines that protect the bodies of knowledge of our communities, that honors lineage, that upholds ethical frameworks rooted in shared, agreed-upon values?
- How do we work in consensual and respectful ways with texts by marginalized authors that are not as well-represented, and by virtue of that fact alone, much more likely to be misrepresented, misappropriated, or misunderstood if we are not careful?
- How well can we ensure that the essence of these texts doesn’t dissolve into a word-soup that gets misconstrued?
- Given that so many of the existing “big data” language models are trained with Western texts and proprietary datasets, what does it even mean to try to decolonize AI?
- Who do we entrust to do this work?
- How do we deal with credit and attribution of our new creations?
- How do we really do ethics with machine learning?
- How do we get through this whole list of concerns and still build AI that is fun, respectful, tender, pleasurable, kind?
