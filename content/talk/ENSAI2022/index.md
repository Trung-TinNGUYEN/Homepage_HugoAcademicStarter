---
abstract: 	Mixture of experts (MoE), originally introduced as a neural network, is a popular class of statistical and machine learning models that has gained attention over the years due to its flexibility and efficiency. They provide conditional constructions for regression in which the mixture weights, along with the component densities, are explained by the predictors, allowing for flexibility in the modeling of data arising from complex data generating processes.  We have shown in previous studies that such models had a good approximation ability provided the number of experts was large enough. More precisely, to an arbitrary degree of accuracy, given input and output variables are both compactly supported, we have provided denseness results in Lebesgue spaces for conditional probability density functions. In this work, we consider Gaussian-gated localized MoE (GLoME) and block-diagonal covariance localized MoE (BLoME) regression models to present nonlinear relationships in heterogeneous data with potential hidden graph-structured interactions between high-dimensional predictors. These models pose difficult questions in statistical estimation and model selection, both from a computational and theoretical perspective. This talk is devoted to the study of the problem of model selection among a collection of GLoME or BLoME models characterized by the number of mixture components, the complexity of Gaussian mean experts, and the hidden block-diagonal structures of the covariance matrices, in a penalized maximum likelihood estimation framework. In particular, we establish non-asymptotic risk bounds that take the form of weak oracle inequalities, provided that lower bounds of the penalties hold. Their good empirical behavior is then demonstrated on synthetic and real datasets. 	
address:
  city: 
  country: 
  postcode: ""
  region: 
  street: 
all_day: false
authors: [admin]
date: "2022-03-18T11:00:00Z"
date_end: "2022-03-18T12:00:00Z"
event: Séminaire de Statistique Rennais
event_url: https://irmar.univ-rennes1.fr/seminars
featured: true
image:
  caption: 'Image credit: **TrungTin Nguyen**'
  focal_point: Right
links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/TrungTinNGUYE10
  
location:  ENSAI École Nationale de Statistique et Analyse de l'Information, France

math: true
projects:
- Model selection in mixture of experts models
publishDate: "2022-03-15T10:30:00Z"
slides: 
summary: 
tags: []
title: A non-asymptotic model selection in mixture of experts models
url_code: ""
url_pdf: ""
url_slides: "https://trung-tinnguyen.github.io/talks/SeminaireENSAI2022_BLoME_Supp.pdf"
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