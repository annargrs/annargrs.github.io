---
layout: splash
author_profile: true
title: Lab
permalink: /lab/
toc: true
excerpt: "Research directions, outputs and open positions"
header:
  overlay_color: "#032539"
redirect_from: "/supervision/"
feature_title: "Research directions"
feature_row:
  - image_path: /assets/images/project_cards_transparency.png
#    title: "Placeholder 3"
    excerpt: "How can we tell _why_ a NLP system produces a certain output?"
    btn_label: "Research questions and outputs"
    btn_class: "btn--primary"
    onClick: "showBibtex('interpretability')"  
  - image_path: assets/images/project_cards_robustness.png
    alt: "placeholder image 1"
#    title: "Placeholder 1"
    excerpt: "How do we know and make sure that a NLP system will work well in the real world?"
    btn_label: "Research questions and outputs"
    btn_class: "btn--primary"
    onClick: "showBibtex('robustness')"  
  - image_path: /assets/images/project_cards_sustainability.png
#    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
#    title: "Placeholder 2"
    excerpt: "The current SOTA models are huge. How do we make them more efficient?"
    btn_label: "Research questions and outputs"
    btn_class: "btn--primary"
    onClick: "showBibtex('efficiency')"  
---

{% capture interpretability %}

## Explainable and transparent NLP

The NLP systems based on large language models are increasingly deployed in many real-world applications, and have real impact on the lives on many people. However, we still do not have reliable methods to explain the 'reasoning' backing their outputs, and many current systems also lack even the minimal transparency about their design and training data. 

My current work in this area is backed by 2024 Villum Young Investigator grant (see [upcoming positions](#phd-and-postdoc-positions)). It focuses on the problem of attribution of the output of generative language models to their training data. This project has planned collaborations with :us: [Allen Institute for AI](https://allenai.org/), :us: [Carnegie Mellon University](https://www.cmu.edu/), :us: :fr: [HuggingFace](https://huggingface.co/), and :jp: [RIKEN-CSS](https://www.r-ccs.riken.jp/en/).

Some relevant past work: 
{% bibliography --query @*[project=interpretability] %}

{% endcapture %}

<div id="interpretability" class="notice--primary project">{{ interpretability| markdownify }}</div>

{% capture robustness %}

## Safe and Robust NLP

I use "safety" in the engineering sense of the word: the NLP systems should actually do what their developers are promising, the same way as e.g. construction engineers ensure that the bridges they build withstand the target load. This is inextricably linked to the topic of robustness of generalization: the NLP systems are trained on some data, and to perform in the real world they need to generalize to the real-world data.

My current work in this area is backed by 2023 DFF Inge Lehmann grant (see [upcoming positions](#phd-and-postdoc-positions)). It focuses on the development of a benchmark that would reward systems for generalizing rather than memorizing their training data. This project has a planned collaboration with :us: [New York University](https://allenai.org/).

Some relevant past work: 
{% bibliography --query @*[project=robustness] %}

{% endcapture %}

<div id="robustness" class="notice--primary project">{{ robustness| markdownify }}</div>

{% capture efficiency %}

## Safe and Robust NLP

The current cutting-edge NLP systems are based on large language models, some with hundreds with billions of parameters. As they are increasingly embedded in everyday applications and used of millions of people, the carbon costs of their use are also skyrocketing. It is imperative that in the future we find more efficient methods to achieve the same or better levels of performance.

My current work in this area is backed by 2023 DFF Inge Lehmann grant (see [upcoming positions](#phd-and-postdoc-positions)). It focuses on the development of a benchmark suite that deliberately caps pre-training and test data, so as to encourage machine learning research on more efficient solutions. This project has a planned collaboration with :us: [New York University](https://allenai.org/).

Some relevant past work: 
{% bibliography --query @*[project=efficiency] %}

{% endcapture %}

<div id="efficiency" class="notice--primary project">{{ efficiency| markdownify }}</div>

# People

Initial recruiting just started! See [available and upcoming positions](#phd-and-postdoc-positions).

# Ph.D. and Postdoc Positions

{% capture notice-1 %}

**Current funded positions:**
  - Ph.D.: ["Linguistic competence of language models in prompt interpretation and text generation"](https://candidate.hr-manager.net/ApplicationInit.aspx?cid=119&ProjectId=181678&DepartmentId=3439&MediaId=5) 
  - postdoc: 1-year postdoc position focusing on development of a generalization benchmark
  - upcoming: PhD positions specializing in (a) influence functions for large language models, (b) semantic search over large databases. 
  - upcoming: 2-year postdoc specializing in reference identification, preferably with prior expertise in scholarly document processing or explainable fact-checking

**Getting your own funding** (if you have your own idea for a PhD or postdoc that you'd like to pursue with me):
  - Danish Data Science Academy funding opportunities (have a look at 2023 calls for [PhD](https://ddsa.dk/phdfellowshipprogramme/) and [postdoc](https://ddsa.dk/postdocfellowshipprogramme/) applications)
  - [Marie Curie postodcs](https://marie-sklodowska-curie-actions.ec.europa.eu/actions/postdoctoral-fellowships)

{% endcapture %}

<div class="notice--info">{{ notice-1 | markdownify }}</div>

If that sounds like you, please get in touch, including your CV and transcripts! Also check my [upcoming talks](https://annargrs.github.io/talks/#upcoming-talks), maybe there's an opportunity to meet at an upcoming conference.

<!-- **Winning your own grant:** if you have your own idea for a PhD or postdoc position that you'd like to pursue with me, have a look at the current DDSA funding opportunities ([PhD](https://ddsa.dk/phdfellowshipprogramme/), [postdoc](https://ddsa.dk/postdocfellowshipprogramme/)) and reach out. I can also host [Marie Curie postodcs](https://marie-sklodowska-curie-actions.ec.europa.eu/actions/postdoctoral-fellowships). -->

{% capture notice-2 %}
**Logistics:** 
- Generally, to be enrolled in the Ph.D. school in Denmark, you need to have a Master's degree. 
- The Danish visa process for non-EU citizens usually takes about 3 months (after you receive and accept the offer).
- You don't have to learn Danish.
- What would it be like to do a PhD in Denmark and ITU? Here's some [tips and reflections by NLPNorth PhD students](https://nlpnorth.github.io/content/phd-reflections.html) 
{% endcapture %}

<div class="notice--warning">{{ notice-2 | markdownify }}</div>

# Thesis and project supervision at ITU

If you're a B.Sc. or M.Sc. student at IT University of Copenhagen, and you would like to work with me, please: 

- reach out stating `[ITU M.Sc. thesis]`, `[ITU B.Sc. thesis]` or `[ITU research project]` at the start of the subject.
- introduce yourself and state:
  - a few concrete topics that you are interested in,
  - your background and any relevant experience. 

Here are some of the research directions that I would be interested in: 
- **Language model analysis**: identifying the types of knowledge acquired from language model pre-training
- **Language processing strategies**: do NLP models perform well for the right reasons? What strategies should they follow when solving reasoning tasks?
- **Robustness and generalization**: do NLP models reliably perform their tasks out of training distribution, and what can we do to help them?
- **NLP system auditing and documentation**: establishing the cases where a system is safe to deploy
- **NLP system interpretability**: how can we establish how a deep learning model arrives at its decisions?
- **Sustainable NLP**: how can we build systems that work well, but don't require billions of parameters and terabytes of data? 

Feel free to also look at my [publications](/publications) and see if there's anything you'd like to build on.