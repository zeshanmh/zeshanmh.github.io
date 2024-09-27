---
layout: about
title: about
permalink: /
subtitle: MD-PhD in <a href='https://www.hst.mit.edu'>HST</a>. MD Candidate at Harvard Medical School. PhD in <a href='https://www.eecs.mit.edu'>EECS</a> from MIT. 

profile:
  align: right
  image: zeshan_profile_pic_alternate.png
  image_circular: true # crops the image to make it circular
  more_info: >
    <p>📍Cambridge, MA</p>

news: true # includes a list of news items
selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page
--- 

Hello! I am an MD-PhD student in the Harvard-MIT Health, Sciences, and Technology (HST) program. I recently completed my PhD in Computer Science at MIT, working with [David Sontag](https://people.csail.mit.edu/dsontag/) in the [Clinical ML group](http://clinicalml.org/). 

My research broadly deals with developing machine learning methods to assist and improve clinical decision-making in healthcare settings, with the ultimate goal of deploying robust and scalable clinical decision support systems. I am specifically interested in deep generative models of clinical sequential data, causal inference, and physician-AI interaction. See below for further details.

Previously, I completed by B.S. and M.S. in Computer Science from Stanford University. I worked on deep learning for medical imaging and data augmentation methods with [Daniel Rubin](https://profiles.stanford.edu/daniel-rubin) and [Chris Re](https://cs.stanford.edu/~chrismre/). 

## Research
My work involves building out the machine learning and statistical methods forming the machinery for future clinical decision support systems that will be used to manage patients with chronic health conditions. During my PhD, I focused on [precision oncology](https://dspace.mit.edu/handle/1721.1/152693), but these ideas extend naturally to any disease process where there is uncertainty in therapeutic management as well as uncertainty in how patients respond to therapy. 

Thus far, I have pursued research along several themes: 

* **How will my patient respond holistically to a chosen therapeutic regimen?** – Oncologists, and physicians more generally, approach choosing a treatment for their patients multifactorially, e.g. maximizing patient survival, minimizing adverse events, improving quality of life, etc. I have looked at building predictive models of clinical temporal data both focused on particular tasks (e.g. biomarker forecasting, as in [\[ICML 2021\]](https://proceedings.mlr.press/v139/hussain21a.html)) and also general models that provide multitask predictions to enable holistic management [\[<i>npj</i> Digital Medicine\]](https://www.nature.com/articles/s41746-024-01189-3).
* **How can I ''sanity check'' predictive and causal estimates produced by ML models for my patients?** Additional context for predictions from ML models for a new patient or a specific patient population can help a physician better assess the reliability of the output. One approach for providing this context is through uncertainty quantification, where we use techniques from conformal inference to give valid confidence intervals of ML model predictions [\[AISTATS 2023\]](https://proceedings.mlr.press/v206/alaa23a.html). Another is by using experimental data as a means of assessing reliability of causal estimates inferred from observational data [\[NeurIPS 2022\]](https://proceedings.neurips.cc/paper_files/paper/2022/hash/28b5dfc51e5ae12d84fb7c6172a00df4-Abstract-Conference.html).
* **How will AI-based clinical decision support systems impact physician behavior?** I studied physician-AI interaction in clinical oncology, where I built a prototype of a clinical decision support system. With it, I ran user studies to assess how physicians interact with simulated versions of the above methods and how their decision-making was impacted [\[Preprint\]](http://arxiv.org/abs/2404.15187).


<!-- Write your biography here. Tell the world about yourself. Link to your favorite [subreddit](http://reddit.com). You can put a picture in, too. The code is already in, just name your picture `prof_pic.jpg` and put it in the `img/` folder.

Put your address / P.O. box / other info right below your picture. You can also disable any of these elements by editing `profile` property of the YAML header of your `_pages/about.md`. Edit `_bibliography/papers.bib` and Jekyll will render your [publications page](/al-folio/publications/) automatically.

Link to your social media connections, too. This theme is set up to use [Font Awesome icons](https://fontawesome.com/) and [Academicons](https://jpswalsh.github.io/academicons/), like the ones below. Add your Facebook, Twitter, LinkedIn, Google Scholar, or just disable all of them. -->
