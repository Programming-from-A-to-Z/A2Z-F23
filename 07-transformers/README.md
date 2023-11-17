# Language Models

- [LLM / transformer slides](https://docs.google.com/presentation/d/1I3uq2EY8Kgl_NIPJ2PxOvxhQvsU-QXaph7QRilnzLCg/edit?usp=sharing)

## Sequential Data and Recurrent Neural Networks

- 📚 [The Unreasonable Effectiveness of RNNs](http://karpathy.github.io/2015/05/21/rnn-effectiveness/) and [Visualizing and Understanding Recurrent Networks](https://skillsmatter.com/skillscasts/6611-visualizing-and-understanding-recurrent-networks) by by Andrei Karpathy
- 🍿 [Sunspring](https://arstechnica.com/gaming/2016/06/an-ai-wrote-this-movie-and-its-strangely-moving/)
- 🎨 [Double Agent](http://littlepig.org.uk/installations/doubleagent/index.htm) by Simon Biggs (Drawing)
- 🎨 [Four Experiments in Handwriting with a Neural Network](https://distill.pub/2016/handwriting/) (Drawing)
- 📖 [10 things artificial intelligence did in 2018](http://aiweirdness.com/post/181621835642/10-things-artificial-intelligence-did-in-2018) by Janelle Shane (Text)
- 📖 [Writing with the Machine](https://www.robinsloan.com/notes/writing-with-the-machine/)
- 🍿 [Interactive Drawing with SketchRNN](https://youtu.be/ZCXkvwLxBrA)

## Transformers and Large Language Models

> among the reasons I use large pre-trained language models sparingly in my computer-generated poetry practice is that being able to know whose voices I'm speaking with is... actually important, as is being understanding how the output came to have its shape - [@aparrish](https://twitter.com/aparrish/), [full thread](https://twitter.com/aparrish/status/1286808606466244608)

- 📚 [Watch an A.I. Learn to Write by Reading Nothing but **\_\_\_\_**](https://www.nytimes.com/interactive/2023/04/26/upshot/gpt-from-scratch.html) by Aatish Bhatia
- 📚 [Attention is All You Need](https://arxiv.org/abs/1706.03762) - Original "Transformer" paper from 2017, also [Neural Machine Translation by Jointly Learning to Align and Translate](https://arxiv.org/abs/1409.0473) -- Attention paper from 2014
- 📚 [The Illustrated Transformer](https://jalammar.github.io/illustrated-transformer/)
- 📚 [What Are Transformer Models and How Do They Work?](https://docs.cohere.com/docs/transformer-models)

## LLM Training

- 🦙 [LLaMA: Open and Efficient Foundation Language Models](https://arxiv.org/pdf/2302.13971.pdf)
- 🦙 [Llama 2: Open Foundation and Fine-Tuned Chat Models](https://arxiv.org/pdf/2307.09288.pdf)
- 🦜 [On the Dangers of Stochastic Parrots: Can Language Models Be Too Big? 🦜](https://dl.acm.org/doi/10.1145/3442188.3445922)
- 🔍 [Introducing The Foundation Model Transparency Index](https://hai.stanford.edu/news/introducing-foundation-model-transparency-index)

### Datasets for LLMs

- 🔢 [Common Crawl](https://commoncrawl.org/)
- 🔢 [The Pile](https://pile.eleuther.ai/)

### Climate Impact

- 🌏 [The Internet’s Next Great Power Suck](https://www.theatlantic.com/technology/archive/2023/08/ai-carbon-emissions-data-centers/675094/)
- ⚡️ [Carbon Emissions and Large Neural Network Training ](https://arxiv.org/ftp/arxiv/papers/2104/2104.10350.pdf)

## Examples and Implementations

- More node.js
  - 🎥 [Server Side / Express with node.js](https://thecodingtrain.com/tracks/data-and-apis-in-javascript/data/2-data-selfie-app/1-server-side-with-node-js)
  - 🎥 [HTTP "POST" request with fetch](https://thecodingtrain.com/tracks/data-and-apis-in-javascript/data/2-data-selfie-app/3-http-post-request)
- 🎨 [Simpler p5.js + Replicate web app](https://github.com/Programming-from-A-to-Z/Replicate-p5js)
- 🕸 [Transformer.js Models Running in Browser](https://github.com/Programming-from-A-to-Z/transformers-js-examples)
- 💬 [ChatGPT Clone with OpenAI API](https://github.com/Programming-from-A-to-Z/ChatGPT-clone)
- 💬 [ChatBot with Llama via Replicate](https://github.com/Programming-from-A-to-Z/llama-chatbot-replicate)
- 💻 [Misc Models via Replicate](https://github.com/Programming-from-A-to-Z/Replicate-Examples)
- 🦙 [Ollama: Run Llama locally](https://ollama.ai/)

## Assignment

- Read [On the Dangers of Stochastic Parrots: Can Language Models Be Too Big? 🦜](https://dl.acm.org/doi/10.1145/3442188.3445922) and review the [The Foundation Model Transparency Index](https://hai.stanford.edu/news/introducing-foundation-model-transparency-index). What questions arise for you about using LLMs in your work at ITP?
- Experiment with prompting a large language model in some way other than the ChatGPT interface and document the results in a blog post. Consider how working with an LLM compares to generating text from the previous exerc ise working with markov chains and context free grammars. Here are some options:
    - Run the [ChatBot with Llama via Replicate](https://github.com/Programming-from-A-to-Z/llama-chatbot-replicate) example or [ChatGPT Clone with OpenAI API](https://github.com/Programming-from-A-to-Z/ChatGPT-clone) and adjust the prompts, interaction, or visual design of the examples. There is also a new [simpler Replicate + p5.js example](https://github.com/Programming-from-A-to-Z/Replicate-p5js) you can try.
    - Sign up for the [OpenAI API](https://openai.com/blog/openai-api) and [try creating a "custom assistant" with a system prompt and knowledge base](https://platform.openai.com/assistants).
    - If you have [the GPT Editor](https://chat.openai.com/gpts/editor) enabled in your OpenAI account, try making a custom chatbot.
    - Try running Llama locall with [Ollama](https://ollama.ai/)
    - Can you connect an LLM to a Discord Bot!?!
    - Invent your own idea!

## Add your assignment below via Pull Request

_(Please note you are welcome to post under a pseudonym and/or password protect your published assignment. Here is some [helpful information on privacy options for an NYU blog](https://nyu.service-now.com/sp?id=kb_article&sysparm_article=KB0012245&sys_kb_id=b2ddc9da004aa1002a5d036a271e5f70&spa=1). Finally, if you prefer not to post your assignment at all here, you may email the submission.)_

- Jane - [Markov+Replicate Anime Generation](https://janecheng.notion.site/Week-9-ML-Transformer-Models-66bfa171d12f4c11964da6c497313611?pvs=4)

- Lan - [Mountain again!](https://yclanlan.github.io/2023-Fall-Programming-A2Z/Week09/)
