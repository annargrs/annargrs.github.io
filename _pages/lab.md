---
layout: splash
author_profile: true
title: Lab
permalink: /lab/
toc: true
redirect_from: "/supervision/"
feature_title: "Research directions"
feature_row:
  - image_path: assets/images/project_cards_robustness.png
    alt: "placeholder image 1"
#    title: "Placeholder 1"
#    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    btn_label: "Research outputs"
    btn_class: "btn--primary"
    url: "#test-link"    
  - image_path: /assets/images/project_cards_sustainability.png
#    image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
    alt: "placeholder image 2"
#    title: "Placeholder 2"
#    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    url: "#test-link"
    btn_label: "Research outputs"
    btn_class: "btn--primary"
  - image_path: /assets/images/project_cards_transparency.png
#    title: "Placeholder 3"
#    excerpt: "This is some sample content that goes here with **Markdown** formatting."
    btn_label: "Research outputs"
    btn_class: "btn--primary"
    url: "#test-link"
---



<!-- TODO splash project images with funder logos, and unfolding lists of references sorted by with project field -->

# People

<!--TODO current members - need to create a template for a person file, also with project tags -->

<!--TODO current external collaborations, also with project tags-->

# Ph.D. and Postdoc Positions

{% capture notice-1 %}

**Current funded positions:**
  - Ph.D.: ["Linguistic competence of language models in prompt interpretation and text generation"](https://candidate.hr-manager.net/ApplicationInit.aspx?cid=119&ProjectId=181678&DepartmentId=3439&MediaId=5) 
  - postdoc: 1-year postdoc position focusing on development of a generalization benchmark
  - upcoming: PhD positions specializing in (a) influence functions for large language models, (b) semantic search over large databases. 
  - upcoming: 2-year postdoc specializing in reference identification, preferably with prior expertise in scholarly document processing or explainable fact-checking

**Getting your own funding** (if you have your own idea for a PhD or postdoc that you'd like to pursue with me):
  - Danish Data Science Academy funding opportunities (have a look at 2023 calls for [PhD](https://ddsa.dk/phdfellowshipprogramme/) and [postdoc](https://ddsa.dk/postdocfellowshipprogramme/) applications)
  - [Marie Curie postodcs](https://marie-sklodowska-curie-actions.ec.europa.eu/actions/postdoctoral-fellowships).

{% endcapture %}

<div class="notice--info">{{ notice-1 | markdownify }}</div>

If that sounds like you, please get in touch, including your CV and transcripts! Also check my [upcoming talks](https://annargrs.github.io/talks/#upcoming-talks), maybe there's an opportunity to meet at an upcoming conference.

<!-- **Winning your own grant:** if you have your own idea for a PhD or postdoc position that you'd like to pursue with me, have a look at the current DDSA funding opportunities ([PhD](https://ddsa.dk/phdfellowshipprogramme/), [postdoc](https://ddsa.dk/postdocfellowshipprogramme/)) and reach out. I can also host [Marie Curie postodcs](https://marie-sklodowska-curie-actions.ec.europa.eu/actions/postdoctoral-fellowships). -->

{% capture notice-2 %}
**Logistics:** 
- Generally, to be enrolled in the Ph.D. school in Denmark, you need to have a Master's degree. 
- The Danish visa process for non-EU citizens usually takes about 3 months (after you receive and accept the offer).
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