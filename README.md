# EHReader: A Medical Healthcare Question Answering System

## Introduction

Question answering (QA) is a prominent challenge in natural language processing research that requires machines to
predict the correct answer to a posed question by extracting it from a given context. In some cases, QA tasks also
involve determining "answerability": whether the answer is present at all in the passage. Recent research has begun to
explore domain-specific QA systems, such as for usage in medical contexts. The growing adoption of electronic health
records (EHR) in the healthcare system poses a specific QA challenge: retrieving answers from clinical notes to inform
medical decisions. This paper introduces the EHReader model based on the Retrospective Reader architecture. The EHReader
model incorporates quick reading and deep reading modules, enabling it to evaluate answerability and then verify the
answer more comprehensively quickly. We compare EHReader to baseline DistilBERT and BioBERT models for medical QA tasks.
The proposed model incorporating only the QuickReader module achieves state-of-the-art results on the benchmark EmrQA
medical dataset and outperforms the baseline DistilBERT and BioBERT models.

## Links

[Report](https://github.com/lcwong0928/ehreader/blob/main/results/report.pdf) \
[Presentation](https://github.com/lcwong0928/ehreader/blob/main/results/presentation.pdf)
