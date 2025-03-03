---
title: "Multi-Access Distributed Computing"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Petros Elia

# Author notes (optional)
#author_notes:
#- "Equal contribution"
#- "Equal contribution"

date: "2024-03-04T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: IEEE Transactions on Information Theory
publication_short: IEEE Transactions on Information Theory

abstract: Coded distributed computing (CDC) is a new technique proposed with the purpose of decreasing the intense data exchange required for parallelizing distributed computing systems. Under the famous MapReduce paradigm, this coded approach has been shown to decrease this communication overhead by a factor that is linearly proportional to the overall computation load during the mapping phase. Nevertheless, it is widely accepted that this overhead remains a main bottleneck in distributed computing. To address this, we take a new approach and we explore a new system model which, for the same aforementioned overall computation load of the mapping phase, manages to provide astounding reductions of the communication overhead and, perhaps counterintuitively, a substantial increase of the computational parallelization. In particular, we propose multi-access distributed computing (MADC) as a novel generalization of the original CDC model, where now *mappers* (nodes in charge of the map functions) and *reducers* (nodes in charge of the reduce functions) are distinct computing nodes that are connected through a multi-access network topology. Focusing on the MADC setting with combinatorial topology, which implies $\Lambda$ mappers and $K$ reducers such that there is a unique reducer connected to any $\alpha$ mappers, we propose a novel coded scheme and a novel information-theoretic converse, which jointly identify the optimal inter-reducer communication load, as a function of the computation load, to within a constant gap of $1.5$. Additionally, a modified coded scheme and converse identify the optimal max-link communication load across all existing links to within a gap of $4$. The unparalleled coding gains reported here should not be simply credited to having access to more mapped data, but rather to the powerful role of topology in effectively aligning mapping outputs. This realization raises the open question of which multi-access network topology guarantees the best possible performance in distributed computing.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2206.12851.pdf'
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
