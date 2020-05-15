---
layout: single
author_profile: true
permalink: /master/
title: Deep Semantic Learning for Conversational Agents
---

I did my Master's Thesis under the supervision of [Giuseppe Rizzo](http://giusepperizzo.github.io/) (from [Istituto Superiore Mario Boella](http://www.ismb.it/)) and [Maurizio Morisio](https://softeng.polito.it/morisio/) (professor in [DAUIN](http://www.dauin.polito.it/it/)).
The thesis, [openly available](http://dx.doi.org/10.13140/RG.2.2.31318.34887/1), is centred on the topic of conversational agents and the task of Natural Language Understanding.

The main contribution of this work is a conversational model, that learns how to perform on a specific and narrow task, by taking into account the sentences from the users. The outputs of this work are:

- A seminar done with [HKNPolito](https://hknpolito.org/) to introduce Deep Learning for Natural Language [introductory event to Machine Learning](https://hknpolito.org/events/introduzione-al-machine-learning/). You can find the [slides](https://www.slideshare.net/MartinoMensio/deep-learning-per-la-comprensione-del-linguaggio-naturale-hkn-91564619)(italian) used for the presentation.
- Two papers accepted to workshops at The Web Conference 2018:
  - [Multi-turn QA: A RNN Contextual Approach to Intent Classification for Goal-oriented Systems](https://dl.acm.org/doi/10.1145/3184558.3191539): focused on the modification of the model to create context-aware responses
  - [The Rise of Emotion-aware Conversational Agents: Threats in Digital Emotions](https://dl.acm.org/doi/10.1145/3184558.3191607): describing the usage of emotions in conversational agents
- The release of the source code for the [Natural Language Understanding model](https://github.com/D2KLab/botcycle)

The defense of the thesis was held on 12 April 2018 ([slides](https://www.slideshare.net/MartinoMensio/deep-semantic-learning-for-conversational-agents-93694181), [video](https://youtu.be/OyJyip7_-yM)) leading to my graduation with full marks.

I've made available a set of repositories that can be used to reproduce experiments and know all the implementation details:
- [Bot Core and NLU](https://github.com/D2KLab/botcycle): this component has the implementation of the neural network, the dataset, together with the implementation of the logic of the bot prototype
- [Bot Server](https://github.com/MartinoMensio/botcycle-server): this component is the public endpoint and acts as a proxy between the different messaging platforms and the Bot Core (communication through a web socket)
- [Thesis source code](https://github.com/MartinoMensio/masters_thesis): this repository can be useful for people that want to write a thesis with LaTeX and want to have an example
- [Italian GloVe embeddings](https://github.com/MartinoMensio/it_vectors_wiki_spacy/): the release of the italian word embeddings that have been trained for the italian version of the bot


<!-- You can interact with the bot on the following platforms:

- Telegram:
  - [English](https://telegram.me/botcycle_bot)
  - [Italian](https://telegram.me/botcycle_it_bot)
- Facebook Messenger:
  - [English](https://m.me/BotCycleEn)
  - [Italian](https://m.me/BotCycleIt)
- Skype:
  - [English](https://join.skype.com/bot/2cb007d1-5dd5-441a-8503-23268e2df32d)
  - [Italian](https://join.skype.com/bot/db2aa777-2e46-40fc-9e49-9bc9d1db201b)
- Dedicated webserver:
  - [English](https://botcycle-server.herokuapp.com/) -->
