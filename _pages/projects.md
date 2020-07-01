---
#title: "Splash Page"
#layout: splash
#permalink: /splash-page/
#date: 2016-03-23T11:48:41-04:00
#header:
#  overlay_color: "#000"
#  overlay_filter: "0.5"
#  overlay_image: /assets/images/unsplash-image-1.jpg
#  actions:
#    - label: "Download"
#      url: "https://github.com/mmistakes/minimal-mistakes/"
#  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
#excerpt: "Bacon ipsum dolor sit amet salami ham hock ham, hamburger corned beef short ribs kielbasa biltong t-bone drumstick tri-tip tail sirloin pork chop."
#intro: 
#  - excerpt: 'Nullam suscipit et nam, tellus velit pellentesque at malesuada, enim eaque. Quis nulla, netus tempor in diam gravida tincidunt, *proin faucibus* voluptate felis id sollicitudin. Centered with `type="center"`'
#feature_row2:
#    overlay_color: "#000"
#    overlay_filter: "0.5"
#  - image_path: /assets/images/aro.jpg
#    alt: "placeholder image 2"
#    image_max_size: 150px
#    title: "Anna Rogers"
#    excerpt: 'I am a post-doctoral associate at the University of Copenhagen, working with the research groups in the [Center for Social Data Science](https://sodas.ku.dk/) and [Machine Learning section](https://di.ku.dk/english/research/groups/nlp/). My main research area is Natural Language Processing. I work on interpretability and evaluation of deep learning models, as well as computational social science. <br/> Before moving to Denmark, I was a postdoctoral research associate in the University of Massachusetts, working with [Anna Rumshisky](http://text-machine.cs.uml.edu/) on sentiment analysis, temporal annotation, question answering and analysis of meaning representations. I hold a Ph.D. degree from the [Department of Language and Information Sciences](https://www.c.u-tokyo.ac.jp/eng_site/info/academics/grad/lis/) at the University of Tokyo (Japan).'
#    url: "#test-link"
#    btn_label: "Read More"
#    btn_class: "btn--primary"
#feature_row3:
#  - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
#    alt: "placeholder image 2"
#    title: "News"
#    excerpt: 'This year I serve as publicity chair for [EMNLP](https://2020.emnlp.org/) and [COLING 2020](https://coling2020.org/)<br/>>'
#    url: "#test-link"
---


---
layout: splash
permalink: /
hidden: true
header:
  overlay_color: "#5e616c"
#  overlay_image: /assets/images/mm-home-page-feature.jpg
  actions:
    - label: "<i class='fas fa-download'></i> Install now"
      url: "/docs/quick-start-guide/"
excerpt: >
  A flexible two-column Jekyll theme. Perfect for building personal sites, blogs, and portfolios.<br />
  <small><a href="https://github.com/mmistakes/minimal-mistakes/releases/tag/4.19.3">Latest release v4.19.3</a></small>
feature_row:
  - image_path: /assets/images/mm-customizable-feature.png
    alt: "customizable"
    title: "Super customizable"
    excerpt: "Everything from the menus, sidebars, comments, and more can be configured or set with YAML Front Matter."
    url: "/docs/configuration/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: /assets/images/mm-responsive-feature.png
    alt: "fully responsive"
    title: "Responsive layouts"
    excerpt: "Built with HTML5 + CSS3. All layouts are fully responsive with helpers to augment your content."
    url: "/docs/layouts/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: /assets/images/mm-free-feature.png
    alt: "100% free"
    title: "100% free"
    excerpt: "Free to use however you want under the MIT License. Clone it, fork it, customize it... whatever!"
    url: "/docs/license/"
    btn_class: "btn--primary"
    btn_label: "Learn more"      
---

{% include feature_row %}


{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}
