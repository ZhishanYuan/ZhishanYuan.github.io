---
title: "Diagnosis Before Treatment? Investigating Intermediate-Variable Reasoning in LLMs"
collection: publications
category: conferences
permalink: /publication/2026-10-24-diagnosis-before-treatment
excerpt: "A controlled study of whether medical LLMs rely on diagnosis as an intermediate variable when selecting treatments."
date: 2026-10-24
venue: "Findings of EMNLP 2026"
paperurl: "https://openreview.net/forum?id=hBtILJu0Lk"
citation: "Zhishan Yuan, Tiago Almeida, Shudong Hao, Zining Zhu, Nickolas Elias Dawlabani, Ghazia Pervaiz, and Yue Ning. 2026. Diagnosis Before Treatment? Investigating Intermediate-Variable Reasoning in LLMs. Findings of EMNLP 2026."
---

We study whether medical LLMs rely on diagnosis as an intermediate variable when selecting treatments. We construct a controlled phenotype--disease--drug benchmark and evaluate six 7B--8B LLMs using behavioral diagnosis interventions, held-out QLoRA path supervision, external validation, and auxiliary layer-wise localization.

**Key results:** Providing the gold diagnosis improves average treatment accuracy from 49.9% to 84.9%, while incorrect predicted diagnoses reduce accuracy from 85.5% to 23.1%. A shuffled-diagnosis control yields 18.2% accuracy, suggesting that the effect depends on diagnosis correctness rather than merely adding disease-like text.
