---
title: "Unselfish Coded Caching can Yield Unbounded Gains over Symmetrically Selfish Caching"

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

date: "2021-05-10T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: Submitted to *IEEE Transactions on Information Theory*
publication_short: Submitted to *IEEE Transactions on Information Theory*

abstract: The original coded caching scenario assumes a content library that is of interest to all receiving users. In a realistic scenario though, the users may have diverging interests which may intersect to various degrees. What happens for example if each file is of potential interest to, say, $40 \\%$ of the users and each user has potential interest in $40 \\%$ of the library? In this work, we investigate the so-called *symmetrically selfish coded caching scenario*, where each user only makes requests from a subset of the library that defines its own *File Demand Set (FDS)*, each user caches selfishly only contents from its own FDS, and where the different FDSs symmetrically overlap to some extent. In the context of various traditional prefetching scenarios (prior to the emergence of coded caching), selfish approaches were known to be potentially very effective. On the other hand &#151 with the exception of some notable works &#151 little is known about selfish coded caching. We here present a new information-theoretic converse that proves, in a general setting of symmetric FDS structures, that selfish coded caching, despite enjoying a much larger local caching gain and a much smaller set of possible demands, introduces an unbounded load increase compared to the unselfish case. In particular, in the $K$-user broadcast channel where each user stores a fraction $\gamma$ of the library, where each file (class) is of interest to $\alpha$ users, and where any one specific file is of interest to a fraction $\delta$ of users, the optimal coding gain of symmetrically selfish caching is at least $(K - \alpha)\gamma + 1$ times smaller than in the unselfish scenario. This allows us to draw the powerful conclusion that the optimal selfish coding gain is upper bounded by $1/(1 - \delta)$, and thus does not scale with $K$. These derived limits are shown to be exact for different types of demands.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2109.04807.pdf'
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
