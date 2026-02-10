---
title: 'Efficient Layer-wise LLM Fine-tuning for Revision Intention Prediction'
authors:
- Zhexiong Liu
- Diane Litman
date: '2025-11-04'
publishDate: '2025-09-28T20:14:50.841055Z'
publication_types: [1]
publication: 'Findings of Conference on Empirical Methods in Natural Language Processing (EMNLP)'
links:
url_pdf: https://aclanthology.org/2025.findings-emnlp.829.pdf
abstract: "Large Language Models (LLMs) have shown extraordinary success across various text generation tasks; however, their potential for simple yet essential text classification remains underexplored, as LLM pre-training tends to emphasize generation over classification. While LLMs with instruction tuning can transform classification into a generation task, they often struggle to categorize nuanced texts. One such example is text revision, which involves nuanced edits between pairs of texts. Although simply fine-tuning LLMs for revision classification seems plausible, it requires a large amount of revision annotations, which are exceptionally expensive and scarce in the community. To address this issue, we introduce a plug-and-play layer-wise parameter-efficient fine-tuning (PEFT) framework, i.e., IR-Tuning, which fine-tunes a subset of important LLM layers that are dynamically selected based on their gradient norm distribution, while freezing those of redundant layers. Extensive experiments suggest that IR-Tuning surpasses several layer-wise PEFT baselines over diverse text revisions, while achieving fast convergence, low GPU memory consumption, and effectiveness on small revision corpora."
---
