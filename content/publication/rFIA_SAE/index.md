---
title: "Simplifying small area estimation with rFIA: a demonstration of tools and techniques"
authors:
- Hunter Stanke
- Andrew O. Finley
- Grant M. Domke

date: "2021-09-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2020-04-27T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Simplifying small area estimation with rFIA: a demonstration of tools and techniques"
publication_short: ""

abstract: "The United States (US) Department of Agriculture Forest Service Forest Inventory and Analysis (FIA) program operates the national forest inventory of the US. Traditionally, the FIA program has relied on sample-based approaches - permanent plot networks and associated design-based estimators - to estimate forest variables across large geographic areas and long periods of time. These approaches generally offer unbiased inference on large domains but fail to provide reliable estimates for small domains due to low sample sizes. Rising demand for small domain estimates will thus require the FIA program to adopt non-traditional estimation approaches that are capable of delivering defensible estimates of forest variables at increased spatial and temporal resolution, without the expense of collecting additional field data. In light of this challenge, the development of small area estimation (SAE) methods - estimation techniques that support inference on small domains - for FIA data has become an active and highly productive area of research. Yet, SAE methods remain difficult to apply to FIA data, due in part to the complex data structures and inventory design used by the FIA program. Thus, we argue that a new suite of estimation tools (i.e., software) will be required to accommodate shifts in demand for inference on large geographic areas and long time periods to inference on small spatial and/or temporal domains. Herein, we present rFIA, an open-source R package designed to increase the accessibility of FIA data, as one such tool. Specifically, we present two case studies chosen to demonstrate rFIA's potential to simplify the application of a broad suite of SAE methods to FIA data: (1) estimation of contemporary county-level forest carbon stocks across the conterminous US using a spatial Fay-Herriot model; and (2) temporally-explicit estimation of multi-decadal trends in merchantable wood volume in Washington County, Maine using a Bayesian mixed-effects model. In both cases, we show that the application of SAE techniques offers considerable improvements in precision over FIA's traditional, post-stratified estimators. Finally, we offer a discussion of the potential role that rFIA and other open-source tools may play in accelerating the adoption of SAE techniques among users of FIA data."

# Summary. An optional shortened abstract.
summary: 

tags:
#- Source Themes
featured: false

links:
#- name: Custom Link
#  url: http://example.org
url_pdf: https://arxiv.org/abs/2109.03863
url_code: https://github.com/hunter-stanke/FGC_rFIA_SAE
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
