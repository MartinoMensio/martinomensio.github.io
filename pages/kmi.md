---
layout: single
author_profile: true
permalink: /kmi/
title: Knowledge Media Institute
---

This page is about my work as Research Assistant in Knowledge Media Institute at The Open University, UK.

## Co-Inform (November 2018 - Current)

From November 2018 I have been working on Co-Inform, a EU-funded project. The objective is to create tools to foster critical thinking and digital literacy for a better-informed society. These tools will be designed and tested with policymakers, journalists, and citizens in 3 different EU countries.

The role of KMi in the project is to detect misinformation online and analyse how it spreads.

### MisinfoMe

My activity is focused on the development of [MisinfoMe](http://socsem.kmi.open.ac.uk/misinfo/), a tool that lets users analyse the interaction between their Twitter profiles (and the accounts followed) and known instances of misinformation.

The idea is, based on Twitter accounts, to have a platform where you can analyse yourself and your contacts to see from where you might be affected by misinformation. This corresponds to identifying profiles that share most misinforming content ans also identify where this content comes from.

This activity lets us explore the existing data sources for misinformation occurrences that have already been analysed by experts (e.g. fact-checkers and other organisations that for example rate the credibility of news sources).
During this activity, we found the material to compare different existing assessments of news sources, which is bringing to one publication in the [Conference for Truth and Trust Online](https://truthandtrustonline.com/).

## NLU (May 2018 - November 2018)

The topics covered in this period are a continuation of the work done for the [Master's Thesis](/master).

The main goal is to enable a voice interface on the robots in order to be able to receive commands and perform some actions.

The main challenges are related to:
- find and use a relevant dataset to train the NLU module
- perform the grounding of the objects mentioned
- analyze the feasibility of the actions required with respect to the abilities of the considered robot
- start the actions or suggest a simpler one in case the robot cannot perform the desired one

To tackle them, I have been experimenting with Neural Networks, Formal Concept Analysis, Knowledge Bases.

### Self-attention

We have been dealing with different datasets (HuRIC, FrameNet) and analyzing how a Deep Learning model can be interpreted (in terms of looking where the attention of the neural network is captured).

During this analysis we found that, using small datasets, the neural network is attending at some unexpected words: we would expect to have the highest values on the verb (that for verbal commands are the Lexical Units of the Frame Semantics Theory) and on some discriminative prepositions.
Adding more examples coming from FrameNet we are observing an alignment between the theory and the observed values.

### Explainability and trust

This study underlines how important it is to have explainable models. After seeing related work in explainability, we realised that the analysis of the self-attention weights could be used as our definition of "explainable model". When the values align with the linguistic theory, the model is behaving more similarly to how we would expect. In this case we define the explainability as the ability of the model to show up what words had the biggest contribution to provide the outputs.

On one side, an explainable model (in our case when the attention values align with the linguistic theory) brings more generalisability, that results in better performances with new samples.

On the other side, it leads to positive effects on the users, such as trust that may grow as an effect of knowing how the model is deciding internally (see the presentation at [HAI 2018](https://www.slideshare.net/MartinoMensio/trust-and-explainability-in-language-understanding)).

## Pointers

[http://www.open.ac.uk/research/people/mm34834](http://www.open.ac.uk/research/people/mm34834)
[http://kmi.open.ac.uk/people/member/martino-mensio](http://kmi.open.ac.uk/people/member/martino-mensio)