---
title: 'Thinking While Speaking: Inference-Time Knowledge Transfer for Responsive and Intelligent Conversational Voice Agents'
authors: [srinivas, zacharye, patel, vikram]
coauthors: []
conference: arXiv preprint arXiv:2511.07397, 2025
date: 2025-11-10
award:
pdf: /pdfs/thinking_while_speaking.pdf
image: /images/pubs/placeholder.svg
thumbnail: /images/pubs/thinking_while_speaking.png
code_url: https://github.com/vysri/conversational-infill
video: 
abstract: |
    Voice agents face a fundamental tension: the reasoning, retrieval, and tool use that make foundation models capable are iterative and slow, while conversational interaction demands responses on a millisecond timescale. Smaller, real-time models meet the latency bar but cannot match foundation models on complex tasks, leaving current voice agents to trade away either responsiveness or capability. We introduce conversational infill, where a small talker model both immediately generates contextually grounded responses to hide the latency of an external reasoner model and fluently integrates streamed reasoner knowledge into its responses during inference. We curate a 290,571-example synthetic dataset spanning six domains and demonstrate that this task is learnable across seven widely used small language models ranging from 135M to 1.7B parameters. Our system implementation, ConvFill, sustains millisecond-level time-to-first-response while closing the accuracy gap to within 6.3% of the corresponding frontier reasoner performance. In a live user study (n=18) with talker deployments running on an Apple M2 SoC, participants rank ConvFill on par with frontier models overall, prefer it for retrieval-heavy tasks, and rate it significantly more responsive. These results show that conversational infill unlocks a new point on the latency-capability Pareto frontier, offering a practical path toward voice agents that are both responsive and highly capable. Code, models, and datasets are available at https://github.com/vysri/conversational-infill.
citation: |
    Vidya Srinivas, Zachary Englhardt, Shwetak Patel, and Vikram Iyer. 2025. Thinking While Speaking: Inference-Time Knowledge Transfer for Responsive and Intelligent Conversational Voice Agents. arXiv:2511.07397. https://doi.org/10.48550/arXiv.2511.07397
bibtex: |
    @misc{srinivas2025thinking,
    author = {Srinivas, Vidya and Englhardt, Zachary and Patel, Shwetak and Iyer, Vikram},
    title = {Thinking While Speaking: Inference-Time Knowledge Transfer for Responsive and Intelligent Conversational Voice Agents},
    year = {2025},
    eprint = {2511.07397},
    archivePrefix = {arXiv},
    primaryClass = {cs.CL},
    doi = {10.48550/arXiv.2511.07397},
    }

tag: ai
---
