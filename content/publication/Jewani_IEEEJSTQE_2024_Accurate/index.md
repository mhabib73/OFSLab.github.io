---
title: "Accurate loss prediction of realistic hollow-core anti-resonant fibers using machine learning"
authors:
- Y. Jewani
- M. Petry
- R. Sanchez-Arias
- Admin

#- Robert Ford
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2024-02-15T00:00:00Z"
doi: 10.1109/JSTQE.2024.3366476

# Schedule page publish date (NOT publication's date).
publishDate: "2023-10-01T00:00:00Z"


# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["featured-article"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Journal of Selected Topics in Quantum Electronics **6**, 1 (2024)"
publication_short: ""

abstract: Hollow-core anti-resonant fibers (HC-ARFs) have proven to be an indispensable platform for various emerging applications due to their unique and extraordinary optical properties. However, accurately estimating the propagation loss of nested HC-ARFs remains a challenging task due to their complex structure and the lack of precise analytical and theoretical models. To address this challenge, we propose a supervised machine-learning framework that presents an effective solution to accurately predict the propagation loss of a 5-tube nested HC-ARF. Multiple supervised learning models, including random forest, logistic regression, quadratic discriminant analysis, tree-based methods, extreme gradient boosting, and K-nearest neighbors are implemented and compared using a simulated dataset. Among these methods, the random forest algorithm is identified as the most effective, delivering accurate predictions. Notably, this study considers the impact of random structural perturbations on fiber geometry, encompassing random variations in tube wall thicknesses and tube gap separations. In particular, these perturbations involve randomly varying outer and nested tube wall thicknesses, tube angle offsets, and randomly distributed non-circular, anisotropic shapes within the cladding structure. It is worth noting that these specific perturbations have not been previously investigated. Each tube exhibits its unique set of random values, leading to longer simulation times for combinations of these values compared to regular random variables in HC-ARFs with similar tube characteristics. The comprehensive consideration of these factors allows for precise predictions, significantly contributing to the advancement of HC-ARFs for many emerging applications.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Hollow-core fibers
- Low-loss fibers
- Machine learning

featured: true

#hugoblox:
 # ids:
  #  arxiv: 1512.04133v1

links:
#- type: preprint
 # provider: arxiv
  #id: 1512.04133v1
#- type: code
 # url: https://github.com/HugoBlox/hugo-blox-builder
#- type: slides
 # url: https://www.slideshare.net/
#- type: dataset
 # url: "#"
#- type: poster
 # url: "#"
#- type: source
 # url: "#"
#- type: video
 # url: https://youtube.com
#- type: link
 - name: link
   url: https://ieeexplore.ieee.org/abstract/document/10437998
  #url_source: https://opg.optica.org/optica/fulltext.cfm?uri=optica-10-10-1253

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
  #caption: 'SEM image and transmission loss of anti-resonant hollow-core fiber'
  #focal_point: "TopRight"
  #preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- HCARF_modeling
- HCARF_fabrication

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""


---
