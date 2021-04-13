---
abstract: Approximate Bayesian computation (ABC) has become an essential part of the Bayesian toolbox for addressing problems in which the likelihood is prohibitively expensive or entirely unknown, making it intractable. ABC defines a pseudo-posterior by comparing observed data with simulated data, traditionally based on some summary statistics, the elicitation of which is regarded as a key difficulty. Recently, using data discrepancy measures has been proposed in order to bypass the construction of summary statistics. Here we propose to use the importance-sampling ABC (IS-ABC) algorithm relying on the so-called two-sample energy statistic. We establish a new asymptotic result for the case where both the observed sample size and the simulated data sample size increase to infinity, which highlights to what extent the data discrepancy measure impacts the asymptotic pseudo-posterior. The result holds in the broad setting of IS-ABC methodologies, thus generalizing previous results that have been established only for rejection ABC algorithms. Furthermore, we propose a consistent V-statistic estimator of the energy statistic, under which we show that the large sample result holds, and prove that the rejection ABC algorithm, based on the energy statistic, generates pseudo-posterior distributions that achieves convergence to the correct limits, when implemented with rejection thresholds that converge to zero, in the finite sample setting. Our proposed energy statistic based ABC algorithm is demonstrated on a variety of models, including a Gaussian mixture, a moving-average model of order two, a bivariate beta and a multivariate g-and-k distribution. We find that our proposed method compares well with alternative discrepancy measures.
address:
  city: 
  country: France, Australia
  postcode: ""
  region: 
  street: 
all_day: true
authors: [Hien Duy Nguyen]
date: "2021-04-12T06:00:00Z"
date_end: "2021-04-13T16:30:00Z"
event: ABC in Svalbard$:$ A workshop on approximate Bayesian methods
event_url: https://sites.google.com/view/abcinsvalbard/home?authuser=0
featured: true
image:
  caption: 'Image credit: **Hien Duy Nguyen**'
  focal_point: Right
links:
- icon: wordpress
  icon_pack: fab
  name: Follow
  url: https://xianblog.wordpress.com/2020/12/16/abc-in-svalbard-update/
  
location:  ABC in Svalbard (Grenoble, Melbourne and Brisbane)

math: true
projects:
- Approximate_Bayesian_computation
publishDate: "2020-04-12T10:30:00Z"
slides: 
summary: 
tags: []
title: Distance-based ABC procedures
url_code: ""
url_pdf: ""
url_slides: "https://bit.ly/3a3LZMr"
url_video: "" 
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