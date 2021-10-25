---
abstract: Mixtures of experts (MoE) models are a ubiquitous tool for the analysis of heterogeneous data across many fields including statistics, bioinformatics, pattern recognition, economics, and medicine, among many others. They provide conditional constructions for regression in which the mixture weights, along with the component densities, are explained by the predictors, allowing for flexibility in the modeling of data arising from complex data generating processes. In this talk, we study the approximation capabilities and model estimation and selection properties, of a wide variety of mixture distributions, with a particular focus on a rich family of MoE models in a high-dimensional setting, including MoE models with Gaussian experts and soft-max or Gaussian gating functions, which are the most popular choices and are powerful tools for modeling complex non-linear relationships between responses and predictors that arise from different subpopulations. We consider both the theoretical statistical and methodological aspects, and the numerical tools, related to the conception of these models, as well as to their data-driven estimation and model selection. In this talk, we first review the universal approximation properties of classical mixture distributions in order to prepare the theoretical framework and to clarify some unclear and vague statements in the literature, before considering them in the context of MoE models. In particular, we prove that, to an arbitrary degree of accuracy, location-scale mixtures of a continuous probability density function (PDF) can approximate any continuous PDF, uniformly, on a compact set, and location-scale mixtures of an essentially-bounded PDF can approximate any PDF in Lebesgue spaces. Then, after providing improvements upon approximation results in the context of unconditional mixture distributions, we study the universal approximation capabilities of MoE models in a variety of contexts, including conditional density approximation and approximate Bayesian computation (ABC). Given input and output variables are both compactly supported, we provide denseness results in Lebesgue spaces for conditional PDFs. Next, we prove that the quasi-posterior distribution resulting from ABC with surrogate posteriors built from finite Gaussian mixtures using an inverse regression approach, converges to the true one, under standard conditions. Finally, we focus on high-dimensional predictors and responses. We introduce non-asymptotic model selection, joint rank and variable selection results for a variety of MoE regression models, including Gaussian-gated and softmax-gated Gaussian MoE, in high-dimensional regression scenarios, based on an inverse regression strategy or a Lasso penalization, respectively. In particular, these results provide a strong theoretical guarantee, a finite-sample oracle inequality satisfied by the penalized maximum likelihood estimator with a Jensen–Kullback–Leibler type loss, to support the slope heuristic criterion in a finite sample setting, compared to the classical asymptotic criteria. This allows the calibration of penalty functions, known up to a multiplicative constant, and to the complexity of the considered random (sub)collection of MoE models, including the number of mixture components, the amount of sparcity (the coefficients and ranks sparsity levels), the degree of polynomial mean functions, and the potential hidden block-diagonal structures of the covariance matrices of the multivariate predictor or response variable. To support our theoretical results and the statistical study of non-asymptotic model selection in a variety of MoE models, we perform numerical studies by considering simulated and real data, which highlight the performance of our finite-sample oracle inequality results.
address:
  city: 
  country: 
  postcode: ""
  region: 
  street: 
all_day: true
authors: [admin]
date: "2021-10-29T09:00:00Z"
date_end: "2021-10-30T00:00:00Z"
event: Jed 2021 Journée scientifique de l'École Doctorale 2021
event_url: https://jed2021.sciencesconf.org/
featured: true
image:
  caption: 'Image credit: **TrungTin Nguyen**'
  focal_point: Right
links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/TrungTinNGUYE10
  
location:  Laboratoire d'Ondes et Milieux Complexes, Le Havre, France

math: true
projects:
- Model selection in mixture of experts models
publishDate: "2021-09-24T10:30:00Z"
slides: 
summary: 
tags: []
title: Model Selection and Approximation in High-dimensional Mixtures of Experts Models From Theory to Practice
url_code: ""
url_pdf: ""
url_slides: "https://trung-tinnguyen.github.io/talks/OralPresentationJED2021.pdf"
url_video: ""
---
<!---
The program includes talks on statistical methods for mixture models, both from a theoretical and a practical point of view, so that the conference should gather specialists from the different communities. The participation of junior researchers as well as PhD students is particularly encouraged. This workshop is organized under the project [**SMILES**](https://smiles.lmno.cnrs.fr/index.html) (Statistical Modeling and Inference for unsupervised Learning at LargE-Scale) funded by the french National Research Agency (ANR). It is also connected to the ex-RIN project [**AStERiCS**](https://asterics.lmno.cnrs.fr/index.html) (Scaled Statistical Learning for Representation and Unsupervised Classification), which was funded by the region Normandy, and the final culmination of which MiMo2020 (cancelled due to Covid-19 crisis) should have been.

{{% alert note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /alert %}}

Slides can be added in a few ways:

- **Create** slides using Academic's [*Slides*](https://sourcethemes.com/academic/docs/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://sourcethemes.com/academic/docs/writing-markdown-latex/).

Further talk details can easily be added to this page using *Markdown* and $\rm \LaTeX$ math code.
-->