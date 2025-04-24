---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

My research focuses on **gender-inclusive machine translation**, and the papers below are my main contributions to this topic.
For a complete list of my publications check [my Google Scholar profile](https://scholar.google.com/citations?user=SceVs8kAAAAJ&hl=it).

* [An LLM-as-a-judge Approach for Scalable Gender-Neutral Translation Evaluation](https://arxiv.org/abs/2504.11934) – GITT 2025\
    🖋️**Andrea Piergentili**, Beatrice Savoldi, Matteo Negri, Luisa Bentivogli\
    📄 In this work we tackled the challenge of automatic evaluation of gender-neutral text and translation. We experimented with the _LLM-as-a-Judge_ approach, where an LLM is prompted to provide task-specific evaluations. We perform extensive experiments on multiple languages with five models, both open and proprietary, and show that LLMs can serve as evaluators of GNT. Moreover, we find that prompting for phrase-level annotations before sentence-level assessments consistently improves the accuracy of all models, providing a better and more scalable alternative to current solutions. 

* [Enhancing Gender-Inclusive Machine Translation with Neomorphemes and Large Language Models](https://aclanthology.org/2024.eamt-1.25/) – EAMT 2024\
    🖋️**Andrea Piergentili**, Beatrice Savoldi, Matteo Negri, Luisa Bentivogli\
    📄 With this work we look at **gender-inclusive neomorphemes**, neologistic elements that avoid binary gender markings as an approach towards fairer MT. In this direction, we explore prompting techniques with LLMs to translate from English into Italian using neomorphemes. So far, this area has been under-explored due to its novelty and the lack of publicly available evaluation resources. We fill this gap by releasing [Neo-GATE](https://huggingface.co/datasets/FBK-MT/Neo-GATE), a resource designed to evaluate gender-inclusive en-it translation with neomorphemes. With Neo-GATE, we assess four LLMs of different families and sizes and different prompt formats.\
    🌌 [EAMT 2024 poster](https://drive.google.com/file/d/1aXmjviVJgYAkeugv77R1iiLy5lsnDxaI/view?usp=sharing)

* [A _Prompt_ Response to the Demand for Automatic Gender-Neutral Translation](https://aclanthology.org/2024.eacl-short.23/) – EACL 2024\
    🖋️ Beatrice Savoldi, **Andrea Piergentili**, Dennis Fucci, Matteo Negri, Luisa Bentivogli\
    📄 In this work we explore the **automation of GNT**. We compare the performance of traditional, commercial MT systems. i.e. Google Translate and DeepL, to GPT-4. We manually evaluate the neutrality and acceptability of their output. We find that GPT-4, when duly prompted, demonstrates a surprising ability to generate gender-neutral translations, significantly outperforming conventional MT systems. GPT-4’s generalization potential from limited examples holds promise for GNT tasks. We also highlight the subjectivity of evaluating gender-neutral translations and make our manual annotations publicly available to foster future research in the field.

* [_Hi Guys_ or _Hi Folks_? Benchmarking Gender-Neutral Machine Translation with the GeNTE Corpus](https://aclanthology.org/2023.emnlp-main.873/) – EMNLP 2023 \
    🖋️ **Andrea Piergentili**, Beatrice Savoldi, Dennis Fucci, Matteo Negri, Luisa Bentivogli\
    📄 This paper introduces [GeNTE](https://huggingface.co/datasets/FBK-MT/GeNTE), a bilingual test set created to **benchmark GNT** from English to Italian. The corpus is informed by a survey on the perception and usage of gender-neutral language. Experimenting with different ways to evaluate with GeNTE, we identify the shortcomings of existing reference-based evaluation protocols for neutral translation, proposing instead a reference-free method as a better alternative for evaluating such task.

* [Gender Neutralization for an Inclusive Machine Translation: from Theoretical Foundations to Open Challenges](https://aclanthology.org/2023.gitt-1.7/) – GITT 2023\
    🖋️ **Andrea Piergentili**, Dennis Fucci, Beatrice Savoldi, Luisa Bentivogli, Matteo Negri\
    📄 This paper addresses the challenge of gender bias in MT, specifically between English and Italian. We **propose gender-neutral translation** (GNT) as a way to promote inclusivity by avoiding gendered language when it is not explicitly necessary. We review institutional guidelines for gender-inclusive language and analyze how such principles can be applied to MT. We identify three key desiderata for GNT: avoiding gender marking when it is unspecified, correctly reflecting gender when inferred from context, and preventing the propagation of masculine generics. We discuss the technical challenges involved in implementing GNT, such as dynamic gender neutralization, the lack of appropriate training data, and the complexities of evaluating gender-neutral outputs.
