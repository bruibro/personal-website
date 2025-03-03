---
title: "Coded Distributed Computing for Sparse Functions With Structured Support"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Kai Wan
- Giuseppe Caire
- Petros Elia

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2023-04-23T00:00:00Z"
doi: "10.1109/ITW54588.2022.9965826"

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: 2023 IEEE Information Theory Workshop (ITW)
publication_short: 2023 IEEE Information Theory Workshop (ITW)

abstract: Coded distributed computing (CDC), originally proposed by Li et al., leverages coded multicast messages to exchange computed intermediate values among the distributed computing nodes, such that the overall communication load could be reduced by a factor of r, the number of input files assigned to each node. However, in the original CDC framework, each output function/task is composed of intermediate values from all input files. In this paper, we propose a new CDC problem for sparse functions with structured support, where each output function depends on a subset of the input files. For a symmetric structured support for which the input files are divided into G equal-length batches and each output function depends on the same number of G′ batches, we propose a novel CDC scheme that is strictly better by a factor G/G′ than directly employing the original CDC scheme in the considered problem. Furthermore, by proposing a new converse bound, we prove that the communication load of the proposed CDC scheme is order optimal within a constant multiplicative factor of 6.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
#links:
# - name: DOI
#   url: 'https://doi.org/10.1109/ISIT50566.2022.9834646'

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/10160235'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

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
#projects:
#- example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---
