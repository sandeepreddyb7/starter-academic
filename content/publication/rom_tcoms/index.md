---
title: "Reduced order model for nonlinear multi-directional ocean wave propagation"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Y.Z.Law
- H Magee
- E.S.Chan

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

abstract: In this paper, we introduce a reduced order model (ROM) for the propagation of nonlinear multi-directional ocean wave-fields. The ROM relies on Galerkin projection of Zakharov equations embedded in the high-order spectral (HOS) method, which describes the evolution of nonlinear waves. The dominant flow features of wave evolution are computed from proper orthogonal decomposition (POD) and these modes are used for the projection. The HOS scheme to compute the vertical velocity is treated in a novel way for an efficient implementa- tion of POD-based ROM. We refer to this alternative formalism of HOS as HOS-simple. The final reduced order model (ROM) is derived from the Galerkin projection of HOS-simple. For the case of irregular waves, where the number of modes required are in the range of 200, the ROM has no significant advantage since both HOS and HOS-simple are much faster than real-time. The real advantage is demon- strated in multi-directional (or short-crested) irregular waves, where the ROM is the only model capable of achieving real-time computa- tion, a major improvement to the standard HOS method. The potential use of the ROM in propagating short-crested waves from far-field to near-field for real-world applications involving wave probes in a wave tank/controlled environment as well as X-band radar in open ocean is also demonstrated.
# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Reduced order modelling, POD, Nonlinear Ocean Waves, Higher Order Spectral method]

# Display this page in the Featured widget?
#featured: 

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

