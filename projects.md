---
layout: single
title: "Projects"
excerpt: What we do?
header:
  overlay_image: /assets/images/banner.jpg
  overlay_filter: 0.5 # same as adding an opacity of 0.5 to a black background
  caption: "Photo credit: [**Pixabay**](https://pixabay.com/photos/bali-nature-mountain-pond-volcano-1674192/)"
---

# On-going Projects

## NusaCrowd
We will initiate a hackathon to centralize many NLP datasets in Indonesian and local languages. Indonesian languages are diverse and scattered, so a unified location that joins multiple sources while preserving the data closest to the original form can greatly help accessibility. We propose a unified schema for dataset extraction to implement as many datasets as possible to enable reproducibility in data processing. Stay tuned for the next update!

# Past Projects
Currently, we have built **5 new benchmarks** to support NLP research on Indonesian languages and published papers in top NLP conferences. You can check this page for more details.

* [2022](https://indonlp.github.io/projects#2022)
    * [NusaX](https://indonlp.github.io/projects#nusax)
* [2021](https://indonlp.github.io/projects#2021)
    * [IndoNLG](https://indonlp.github.io/projects#indonlg)
    * [IndoNLI](https://indonlp.github.io/projects#indonli)
* [2020](https://indonlp.github.io/projects#2020)
    * [IndoNLU](https://indonlp.github.io/projects#indonlu)
    * [IndoLEM](https://indonlp.github.io/projects#indolem)

## 2022

### NusaX

NusaX is a high-quality multilingual parallel corpus for Indonesian local languages elicited by native speakers. NusaX covers 12 languages, Indonesian, English, and 10 Indonesian local languages, namely Acehnese, Balinese, Banjarese, Buginese, Madurese, Minangkabau, Javanese, Ngaju, Sundanese, and Toba Batak.

<i class="fas fa-book" aria-hidden="true"></i> **Paper:** NusaX: Multilingual Parallel Sentiment Dataset for 10 Indonesian Local Language [Preprint arXiv 2022](https://arxiv.org/pdf/2205.15960.pdf){: .btn .btn--info .btn--small } 
{: .notice}

<i class="fas fa-at" aria-hidden="true"></i> **Authors:** Genta Indra Winata\*, Alham Fikri Aji\*, Samuel Cahyawijaya\*, Rahmad Mahendra\*, Fajri Koto\*, Ade Romadhony\*, Kemal Kurniawan\*, David Moeljadi, Radityo Eko Prasojo, Pascale Fung, Timothy Baldwin, Jey Han Lau, Rico Sennrich, Sebastian Ruder  (* equal contribution)
{: .notice--warning}

<i class="fas fa-database" aria-hidden="true"></i> **Dataset:** [https://github.com/IndoNLP/nusax](https://github.com/IndoNLP/nusax) 
{: .notice--info}

## 2021

### IndoNLG

IndoNLG is the first benchmark to measure natural language generation (NLG) progress in three low-resource—yet widely spoken—languages of Indonesia: Indonesian, Javanese, and Sundanese. Altogether, these languages are spoken by more than 100 million native speakers, and hence constitute an important use case of NLG systems today. Concretely, IndoNLG covers six tasks: summarization, question answering, chit-chat, and three different pairs of machine translation (MT) tasks. We collate a clean pretraining corpus of Indonesian, Sundanese, and Javanese datasets, Indo4B-Plus, which is used to pretrain our models: IndoBART and IndoGPT. 

<i class="fas fa-book" aria-hidden="true"></i> **Paper:** IndoNLG: Benchmark and Resources for Evaluating Indonesian Natural Language Generation [EMNLP 2021](https://aclanthology.org/2021.emnlp-main.699.pdf){: .btn .btn--info .btn--small } 
{: .notice}

<i class="fas fa-at" aria-hidden="true"></i> **Authors:** Samuel Cahyawijaya\*, Genta Indra Winata\*, Bryan Wilie\*, Karissa Vincentio\*, Xiaohong Li\*, Adhiguna Kuncoro\*, Sebastian Ruder, Zhi Yuan Lim, Syafri Bahar, Masayu Leylia Khodra, Ayu Purwarianti, Pascale Fung (\* equal contribution)
{: .notice--warning}

<i class="fas fa-database" aria-hidden="true"></i> **Dataset:** [https://github.com/IndoNLP/indonlg](https://github.com/IndoNLP/indonlg) 
{: .notice--info}

### IndoNLI

IndoNLI is the first human-elicited Natural Language Inference (NLI) dataset for Indonesian. IndoNLI is annotated by both crowd workers and experts. The expert-annotated data is used exclusively as a test set. It is designed to provide a challenging test-bed for Indonesian NLI by explicitly incorporating various linguistic phenomena such as numerical reasoning, structural changes, idioms, or temporal and spatial reasoning.

<i class="fas fa-book" aria-hidden="true"></i> **Paper:** IndoNLI: A Natural Language Inference Dataset for Indonesian [EMNLP 2021](https://aclanthology.org/2021.emnlp-main.821.pdf){: .btn .btn--info .btn--small } 
{: .notice}

<i class="fas fa-at" aria-hidden="true"></i> **Authors:** Rahmad Mahendra, Alham Fikri Aji, Samuel Louvan, Fahrurrozi Rahman, Clara Vania
{: .notice--warning}

<i class="fas fa-database" aria-hidden="true"></i> **Dataset:** [https://github.com/IndoNLP/indonli](https://github.com/IndoNLP/indonli) 
{: .notice--info}

## 2020

### IndoNLU

IndoNLU is the first-ever vast resource for the training, evaluating, and benchmarking on Indonesian natural language understanding (IndoNLU) tasks. IndoNLU includes twelve tasks, ranging from single sentence classification to pair-sentences sequence labeling with different levels of complexity. The datasets for the tasks lie in different domains and styles to ensure task diversity. We also provide a set of Indonesian pre-trained models (IndoBERT) trained from a large and clean Indonesian dataset Indo4B collected from publicly available sources such as social media texts, blogs, news, and websites. We release baseline models for all twelve tasks, as well as the framework for benchmark evaluation, and thus it enables everyone to benchmark their system performances. 

<i class="fas fa-book" aria-hidden="true"></i> **Paper:** IndoNLU: Benchmark and Resources for Evaluating Indonesian Natural Language Understanding [AACL 2020](https://aclanthology.org/2020.aacl-main.85.pdf){: .btn .btn--info .btn--small } 
{: .notice}

<i class="fas fa-at" aria-hidden="true"></i> **Authors:** Bryan Wilie\*, Karissa Vincentio\*, Genta Indra Winata\*, Samuel Cahyawijaya\*, Xiaohong Li, Zhi Yuan Lim, Sidik Soleman, Rahmad Mahendra, Pascale Fung, Syafri Bahar, Ayu Purwarianti (\* equal contribution)
{: .notice--warning}

<i class="fas fa-database" aria-hidden="true"></i> **Dataset and Code:** [https://github.com/IndoNLP/indonlu](https://github.com/IndoNLP/indonlu) 
{: .notice--info}

### IndoLEM
IndoLEM dataset comprising seven tasks for the Indonesian language, spanning morpho-syntax, semantics, and discourse. We additionally release IndoBERT, a new pre-trained language model for Indonesian, and evaluate it over IndoLEM, in addition to benchmarking it against existing resources. Our experiments show that IndoBERT achieves state-of-the-art performance over most of the tasks in IndoLEM.

<i class="fas fa-book" aria-hidden="true"></i> **Paper:** IndoLEM and IndoBERT: A Benchmark Dataset and Pre-trained Language Model for Indonesian NLP [COLING 2020](https://aclanthology.org/2020.coling-main.66.pdf){: .btn .btn--info .btn--small } 
{: .notice}

<i class="fas fa-at" aria-hidden="true"></i> **Authors:** Fajri Koto, Afshin Rahimi, Jey Han Lau, Timothy Baldwin
{: .notice--warning}

<i class="fas fa-database" aria-hidden="true"></i> **Dataset:** [https://github.com/indolem/indolem](https://github.com/indolem/indolem) 
{: .notice--info}