---
title: 'Intention-Adaptive LLM Fine-Tuning for Text Revision Generation'
authors:
- Zhexiong Liu
- Diane Litman
date: '2026-02-04'
publishDate: '2025-12-28T20:14:50.841055Z'
publication_types: [1]
publication: 'Findings of Conference of the European Chapter of the Association for Computational Linguistics (EACL)'
links:
- name: PDF
  url_pdf: https://www.arxiv.org/pdf/2602.00477.pdf
abstract: "Large Language Models (LLMs) have achieved impressive capabilities in various context-based text generation tasks, such as summarization and reasoning; however, their applications in intention-based generation tasks remain underexplored. One such example is revision generation, which requires the generated text to explicitly reflect the writer's actual intentions. Identifying intentions and generating desirable revisions are challenging due to their complex and diverse nature. Although prior work has employed LLMs to generate revisions with few-shot learning, they struggle with handling entangled multi-intent scenarios. While fine-tuning LLMs using intention-based instructions appears promising, it demands large amounts of annotated data, which is expensive and scarce in the revision community. To address these challenges, we propose Intention-Tuning, an intention-adaptive layer-wise LLM fine-tuning framework that dynamically selects a subset of LLM layers to learn the intentions and subsequently transfers their representations to revision generation. Experimental results suggest that Intention-Tuning is effective and efficient on small revision corpora, outperforming several PEFT baselines."
---
