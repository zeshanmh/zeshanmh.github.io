---
layout: about
title: about
permalink: /
subtitle: >
  Internal Medicine Resident, <a href='https://www.brighamandwomens.org'>Brigham and Women's Hospital</a>.
  MD–PhD, <a href='https://hst.mit.edu'>Harvard Medical School</a> · <a href='https://www.eecs.mit.edu'>MIT EECS</a>.

profile:
  align: right
  image: zeshan_profile_pic_alternate.png
  image_circular: true # crops the image to make it circular
  more_info: >
    <p>📍Boston, MA</p>

news: true # includes a list of news items
selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page
---

Hello! I am an internal medicine resident at Brigham and Women's Hospital and an MD–PhD graduate of the [Harvard–MIT Health Sciences and Technology (HST)](https://www.hst.mit.edu) program. I completed my PhD at MIT EECS with the [Clinical ML group](http://clinicalml.org/), advised by [David Sontag](https://people.csail.mit.edu/dsontag/).

My research develops machine learning methods at the intersection of representation learning, large language models, causal inference, and physician–AI interaction, with a primary clinical focus in oncology. Current directions include improving sample efficiency for LLM-based clinical prediction, integrating real-world evidence with experimental data for reliable causal effect estimation, and studying how physicians interact with AI-based recommendations in practice.

Previously, I completed my B.S. and M.S. in Computer Science from Stanford University, where I worked on deep learning for medical imaging and data augmentation with [Daniel Rubin](https://profiles.stanford.edu/daniel-rubin) and [Chris Ré](https://cs.stanford.edu/~chrismre/).

## Research

My work focuses on building ML methods that are both statistically rigorous and clinically deployable, with [precision oncology](https://dspace.mit.edu/handle/1721.1/152693) as the primary application. I have pursued research along three themes:

* **How will my patient respond holistically to a chosen therapeutic regimen?** Oncologists approach treatment selection multifactorially — maximizing survival, minimizing adverse events, improving quality of life. I have built predictive models of longitudinal patient trajectories that provide multitask predictions to support this kind of holistic management [\[<i>npj</i> Digital Medicine, 2024\]](https://www.nature.com/articles/s41746-024-01189-3). A key bottleneck is labeled data scarcity; more recently, I have studied how LLMs can construct powerful clinical representations to dramatically improve sample efficiency for downstream prediction tasks [\[arXiv, 2026\]](https://arxiv.org/pdf/2603.11679).

* **How can I trust the causal and predictive estimates my model produces?** Observational data is pervasive in oncology, but estimates derived from it are often seen as unreliable without validation. I have developed falsification methods that use RCT data to detect and characterize bias in observational studies [\[NeurIPS 2022\]](https://proceedings.neurips.cc/paper_files/paper/2022/hash/28b5dfc51e5ae12d84fb7c6172a00df4-Abstract-Conference.html) [\[AISTATS 2023\]](https://proceedings.mlr.press/v206/hussain23a/hussain23a.pdf) [\[ICML 2026\]](https://arxiv.org/pdf/2506.01191), and uncertainty quantification methods that produce valid confidence intervals for ML model predictions [\[AISTATS 2023\]](https://proceedings.mlr.press/v206/alaa23a/alaa23a.pdf).

* **How will AI-based decision support change how physicians make decisions?** Deploying AI in the clinic requires understanding how physicians actually use model outputs. I built a prototype clinical decision support system and ran user studies examining how AI recommendations shape physician decision-making in simulated multiple myeloma patients [\[ACM Transactions on Computing for Healthcare, 2026\]](https://arxiv.org/submit/7603311/view).
