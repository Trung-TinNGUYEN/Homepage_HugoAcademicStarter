---
title: "Model Selection and Approximation in High-dimensional Mixtures of Experts Models: from Theory to Practice"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2021-12-14T14:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
#publication: In *Wowchemy Conference*
#publication_short: In *ICW*
publication: Ph.D. Thesis. Normandie Université. https://tel.archives-ouvertes.fr/tel-03524749

abstract: Mixtures of experts (MoE) models are a ubiquitous tool for the analysis of heterogeneous data across many fields including statistics, bioinformatics, pattern recognition, economics, and medicine, among many others. They provide conditional constructions for regression in which the mixture weights, along with the component densities, are explained by the predictors, allowing for flexibility in the modeling of data arising from complex data generating processes. In this thesis, we study the approximation capabilities and model estimation and selection properties, of a wide variety of mixture distributions, with a particular focus on a rich family of MoE models in a high-dimensional setting, including MoE models with Gaussian experts and softmax or Gaussian gating functions, which are the most popular choices and are powerful tools for modeling complex non-linear relationships between responses and predictors that arise from different subpopulations. We consider both the theoretical statistical and methodological aspects, and the numerical tools, related to the conception of these models, as well as to their data-driven estimation and model selection. More precisely, in this thesis, we first review the universal approximation properties of classical mixture distributions in order to prepare the theoretical framework and to clarify some unclear and vague statements in the literature, before considering them in the context of MoE models. In particular, we prove that, to an arbitrary degree of accuracy, location-scale mixtures of a continuous probability density function (PDF) can approximate any continuous PDF, uniformly, on a compact set; and location-scale mixtures of an essentially-bounded PDF can approximate any PDF in Lebesgue spaces. Then, after improving upon approximation results in the context of unconditional mixture distributions, we study the universal approximation capabilities of MoE models in a variety of contexts, including conditional density approximation and approximate Bayesian computation (ABC). Given input and output variables are both compactly supported, we provide denseness results in Lebesgue spaces for conditional PDFs. Moreover, we prove that the quasi-posterior distribution resulting from ABC with surrogate posteriors built from finite Gaussian mixtures using an inverse regression approach, converges to the true one, under standard conditions. Finally, we establish non-asymptotic risk bounds that take the form of weak oracle inequalities, provided that lower bounds on the penalties hold true, in high-dimensional regression scenarios for a variety of MoE regression models, including Gaussian-gated and softmax-gated Gaussian MoE, based on an inverse regression strategy or a Lasso penalization, respectively. In particular, our oracle inequalities show that the performance in Jensen–Kullback–Leibler type loss of our penalized maximum likelihood estimators are roughly comparable to that of oracle models if we take large enough the constants in front of the penalties, whose forms are only known up to multiplicative constants and proportional to the dimensions of models. Such theoretical justifications of the penalty shapes motivate us to make use of the slope heuristic criterion to select several hyperparameters, including the number of mixture components, the amount of sparsity (the coefficients and ranks sparsity levels), the degree of polynomial mean functions, and the potential hidden block-diagonal structures of the covariance matrices of the multivariate predictor or response variable. To support our theoretical results and the statistical study of non-asymptotic model selection in a variety of MoE models, we perform numerical studies by considering simulated and real data, which highlight the performance of our finite-sample oracle inequality results.
# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

#tags: []

# Display this page in the Featured widget?
#featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://trung-tinnguyen.github.io/files/PhDThesis2021_Manuscript_TrungTin_Nguyen.pdf'
url_code: 'https://github.com/Trung-TinNGUYEN'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://trung-tinnguyen.github.io/talks/Presentation_Soutenance_These_TrungTinNguyen.pdf'
url_source: ''
url_video: 'https://www.youtube.com/watch?v=aLwMzQkL4UU'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- Model selection in mixture of experts models

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---



