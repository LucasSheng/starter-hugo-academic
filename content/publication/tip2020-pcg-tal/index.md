---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "PCG-TAL: Progressive Cross-Granularity Cooperation for Temporal Action Localization"
authors: ["Rui Su, Dong Xu, Lu Sheng, Wanli Ouyang"]
date: 2020-12-17
doi: "10.1109/TIP.2020.3044218"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-10-04T22:54:17+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Image Processing"
publication_short: "IEEE TIP"

abstract: "There are two major lines of works, i.e., anchor-based and frame-based approaches, in the field of temporal action localization. But each line of works is inherently limited to a certain detection granularity and cannot simultaneously achieve high recall rates with accurate action boundaries. In this work, we propose a progressive cross-granularity cooperation (PCG-TAL) framework to effectively take advantage of complementarity between the anchor-based and frame-based paradigms, as well as between two-view clues (i.e., appearance and motion). Specifically, our new Anchor-Frame Cooperation (AFC) module can effectively integrate both two-granularity and two-stream knowledge at the feature and proposal levels, as well as within each AFC module and across adjacent AFC modules. Specifically, the RGB-stream AFC module and the flow-stream AFC module are stacked sequentially to form a progressive localization framework. The whole framework can be learned in an end-to-end fashion, whilst the temporal action localization performance can be gradually boosted in a progressive manner. Our newly proposed framework outperforms the state-of-the-art methods on three benchmark datasets the THUMOS14, ActivityNet v1.3 and UCF-101-24, which clearly demonstrates the effectiveness of our framework."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: 
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
