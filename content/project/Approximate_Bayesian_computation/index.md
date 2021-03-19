---
title: Approximate Bayesian computation
summary: Approximate Bayesian computation with finite Gaussian mixtures.
tags:
- Approximate Bayesian computation
date: "2021-02-12T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

#image:
#  caption: Photo by rawpixel on Unsplash
#  focal_point: Smart

links:
#- icon: twitter
#  icon_pack: fab
#  name: Follow
#  url: https://twitter.com/TrungTinNGUYE10
url_code: ""
url_pdf: "https://hal.archives-ouvertes.fr/hal-03139256/"
url_slides: ""
url_video: "https://www.youtube.com/watch?v=dNFUWvg1AQU&t=139s&ab_channel=CriteoEng"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
#   slides: example
---
A key ingredient in approximate Bayesian computation (ABC) procedures is the choice of a discrepancy that describes how different the simulated and observed data are, often based on a set of summary statistics when the data cannot be compared directly. Unless discrepancies and summaries are available from experts or prior knowledge, which seldom occurs, they have to be chosen and this can affect the approximations. Their choice is an active research topic, which has mainly considered data discrepancies requiring samples of observations or distances between summary statistics, to date. In this work, we introduce a preliminary learning step in which surrogate posteriors are built from finite Gaussian mixtures using an inverse regression approach. These surrogate posteriors are then used in place of summary statistics and compared using metrics between distributions in place of data discrepancies. Two such metrics are investigated, a standard L2 distance and an optimal transport-based distance. The whole procedure can be seen as an extension of the semi-automatic ABC framework to functional summary statistics. The resulting ABC quasi-posterior distribution is shown to converge to the true one, under standard conditions. Performance is illustrated on both synthetic and real data sets, where it is shown that our approach is particularly useful when the posterior is multimodal.
