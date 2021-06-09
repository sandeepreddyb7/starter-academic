---
title: "Assessment of unsteady flow predictions using hybrid deep learning based reduced-order models"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- R Gupta
- A R Magee
- R K Jaiman

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021-01-01T00:00:00Z"
doi: "https://doi.org/10.1063/5.0030137"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: In *Physics of Fluids*
publication_short: In *POF*

abstract: In this paper, we present two deep learning-based hybrid data-driven reduced-order models for prediction of unsteady fluid flows. These hybrid models rely on recurrent neural networks (RNNs) to evolve low-dimensional states of unsteady fluid flow. The first model projects the high-fidelity time series data from a finite element Navier–Stokes solver to a low-dimensional subspace via proper orthogonal decomposition (POD). The time-dependent coefficients in the POD subspace are propagated by the recurrent net (closed-loop encoder–decoder updates) and mapped to a high-dimensional state via the mean flow field and the POD basis vectors. This model is referred to as POD-RNN. The second model, referred to as the convolution recurrent autoencoder network (CRAN), employs convolutional neural networks (instead of POD) as layers of linear kernels with nonlinear activations, to extract low-dimensional features from flow field snapshots. The flattened features are advanced using a recurrent (closed-loop manner) net and up-sampled (transpose convoluted) gradually to high-dimensional snapshots. Two benchmark problems of the flow past a cylinder and the flow past side-by-side cylinders are selected as the unsteady flow problems to assess the efficacy of these models. For the problem of the flow past a single cylinder, the performance of both the models is satisfactory and the CRAN model is found to be overkill. However, the CRAN model completely outperforms the POD-RNN model for a more complicated problem of the flow past side-by-side cylinders involving the complex effects of vortex-to-vortex and gap flow interactions. Owing to the scalability of the CRAN model, we introduce an observer-corrector method for calculation of integrated pressure force coefficients on the fluid–solid boundary on a reference grid. This reference grid, typically a structured and uniform grid, is used to interpolate scattered high-dimensional field data as snapshot images. These input images are convenient in training the CRAN model, which motivates us to further explore the application of the CRAN-based models for prediction of fluid flows.
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Recurrent neural networks, Convolutional neural networks, autoencoders, DD-ROM, bluff body, wake]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

