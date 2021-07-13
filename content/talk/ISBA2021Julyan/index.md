---
abstract: A key ingredient in approximate Bayesian computation (ABC) procedures is the choice of a discrepancy that describes how different the simulated and observed data are, often based on a set of summary statistics when the data cannot be compared directly. Unless discrepancies and summaries are available from experts or prior knowledge, which seldom occurs, they have to be chosen and this can affect the approximations. Their choice is an active research topic, which has mainly considered data discrepancies requiring samples of observations or distances between summary statistics, to date. In this work, we introduce a preliminary learning step in which surrogate posteriors are built from finite Gaussian mixtures using an inverse regression approach. These surrogate posteriors are then used in place of summary statistics and compared using metrics between distributions in place of data discrepancies. Two such metrics are investigated, a standard $L_2$ distance and an optimal transport-based distance. The whole procedure can be seen as an extension of the semi-automatic ABC framework to functional summary statistics. The resulting ABC quasi-posterior distribution is shown to converge to the true one, under standard conditions. Performance is illustrated on both synthetic and real data sets, where it is shown that our approach is particularly useful when the posterior is multimodal.
address:
  city: 
  country: Virtually
  postcode: ""
  region: 
  street: 
all_day: true
authors: [Julyan Arbel]
date: "2021-06-28T00:00:00Z"
date_end: "2021-07-02T23:59:00Z"
event: 2021 World Meeting of the International Society for Bayesian Analysis
event_url: https://events.stat.uconn.edu/ISBA2021/
featured: true
image:
  caption: 'Image credit: **Florence Forbes**'
  focal_point: Right
links:
- icon: wordpress
  icon_pack: fab
  name: Follow
  url: https://events.stat.uconn.edu/ISBA2021/
  
location:  Virtually, Earth

math: true
projects:
- Approximate_Bayesian_computation
publishDate: "2021-06-28T10:30:00Z"
slides: 
summary: 
tags: []
title: Approximate Bayesian computation with surrogate posteriors
url_code: ""
url_pdf: ""
url_slides: "https://trung-tinnguyen.github.io/slides/GLLiM-ABC-ISBA2021.pdf"
url_video: "https://www.youtube.com/watch?v=fXfeJCnRmOM&ab_channel=JulyanArbel"
---
<!---
Machine learning is changing the world we live in at a break neck pace. From image recognition and generation, to the deployment of recommender systems, it seems to be breaking new ground constantly and influencing almost every aspect of our lives. In ths seminar series we ask distinguished speakers to comment on what role Bayesian statistics and Bayesian machine learning have in this rapidly changing landscape. Do we need to optimally process information or borrow strength in the big data era? Are philosophical concepts such as coherence and the likelihood principle relevant when you are running a large scale recommender system? Are variational approximations, MCMC or EP appropriate in a production environment? Can I use the propensity score and call myself a Bayesian? How can I elicit a prior over a massive dataset? Is Bayes a reasonable theory of how to be perfect but a hopeless theory of how to be good? Do we need Bayes when we can just A/B test? What combinations of pragmatism and idealism can be used to deploy Bayesian machine learning in a large scale live system? We ask Bayesian believers, Bayesian pragmatists and Bayesian sceptics to comment on all of these subjects and more.

{{% alert note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /alert %}}

Slides can be added in a few ways:

- **Create** slides using Academic's [*Slides*](https://sourcethemes.com/academic/docs/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://sourcethemes.com/academic/docs/writing-markdown-latex/).

Further talk details can easily be added to this page using *Markdown* and $\rm \LaTeX$ math code.
-->