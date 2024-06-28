---
layout: single
author_profile: true
permalink: /phd/
title: PhD
---

Between 2019 and 2023 I did my PhD at the [Knowledge Media Institute](https://kmi.open.ac.uk/) (Open University) under the supervision of [Harith Alani](http://people.kmi.open.ac.uk/harith/) and [Alistair Willis](http://mcs.open.ac.uk/agw96/).

In my work I propose a methodology to automatically compare persuasion means in news articles across different political orientations.
This lies at the intersection between multiple research areas: corroboration and omission analysis, persuasion techniques extraction (propaganda and sentiment), political leaning and topic analysis.

In my work I make use of several NLP techniques and tools, such as document embeddings, clustering algorithms, transformer models for sequence tagging, supervised learning through neural networks.

The following materials are publicly available:

- The full text of the thesis: https://oro.open.ac.uk/98145/ (and the [latex source](https://github.com/MartinoMensio/phd-thesis))
- Presentation: [slideshare](https://www.slideshare.net/slideshow/persuasion-across-the-political-spectrum-quantifying-differences-in-parallel-news-reports/269941090)
- Source code of the experiments: [main repository](https://github.com/MartinoMensio/phd-project)
- Additional tooling developed during/for the PhD project:
  - [SpaCy + USE](https://github.com/MartinoMensio/spacy-universal-sentence-encoder): SpaCy wrapper to embed sentences with Universal Sentence Embeddings
  - [SpaCy + Sentence BERT](https://github.com/MartinoMensio/spacy-sentence-bert): SpaCy wrapper to embed sentences with Sentence BERT
  - [SpaCy + DBpedia](https://github.com/MartinoMensio/spacy-dbpedia-spotlight): NER and linking to DBpedia
  - [AllSides](https://github.com/MartinoMensio/allsides-headlines): to collect data from AllSides
  - [Google News](https://github.com/MartinoMensio/google-headlines): to collect data from Google News
  - [SentenceTree parser for coreNLP](https://github.com/MartinoMensio/corenlp-sentiment-tree-parser): parse the annotation of sentiment SentenceTree from CoreNLP
  - [TextRazor bulk annotate](https://github.com/MartinoMensio/textrazor-bulk-annotate)
  [Formal Writing Checker](https://github.com/MartinoMensio/formal-writing-checker): a small tool to warn you if your text is using passive voice or long sentences
- Data: I cannot share the data of the experiments because of licensing issues

## Step By Step

The direction for the thesis was refined during the years.

In my first year I focused on analysing of how different articles present the same events, by using different emphasis and selecting different details, aiming to produce a comparative analysis. You can see more in the video below or take a look at [the poster](/assets/docs/2020_OU_poster_competition.pdf) sent to the OU poster competition 2020.
A more detailed explanation of the initial objectives can be seen in the [position paper](http://ceur-ws.org/Vol-2593/paper11.pdf) that has been presented at the [*Text2Story*](http://text2story20.inesctec.pt/) workshop.

<p><iframe src="https://www.youtube-nocookie.com/embed/8FiQmzG0Zfs" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></p>

This direction can be seen in the [Upgrade Report](/assets/docs/phd_upgrade_report.pdf)

Then in my second year I shifted my goals more towards the automatic detection of propaganda techniques, and how different news sources use them in specific ways.

And in my third year I analysed how these techniques vary across topics and how the current approaches for propaganda detection are specifically targeting extreme-right propaganda.

In my fourth year, my main activity was to refine the analyses and to report everything in the PhD Thesis.
