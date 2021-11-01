---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Visibility Constrained Generative Model for Depth-based 3D Facial Pose Tracking"
authors: ["Lu Sheng, Jianfei Cai, Tat-Jen Cham, Vladimir Pavlovic, King Ngi Ngan"]
date: 2018-10-23
doi: "10.1109/TPAMI.2018.2877675"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-10-05T14:18:01+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Pattern Analysis and Machine Intelligence"
publication_short: "IEEE TPAMI"

abstract: "In this paper, we propose a generative framework that unifies depth-based 3D facial pose tracking and face model adaptation on-the-fly, in the unconstrained scenarios with heavy occlusions and arbitrary facial expression variations. Specifically, we introduce a statistical 3D morphable model that flexibly describes the distribution of points on the surface of the face model, with an efficient switchable online adaptation that gradually captures the identity of the tracked subject and rapidly constructs a suitable face model when the subject changes. Moreover, unlike prior art that employed ICP-based facial pose estimation, to improve robustness to occlusions, we propose a ray visibility constraint that regularizes the pose based on the face model's visibility with respect to the input point cloud. Ablation studies and experimental results on Biwi and ICT-3DHP datasets demonstrate that the proposed framework is effective and outperforms completing state-of-the-art depth-based methods."

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

url_pdf: "https://arxiv.org/abs/1905.02114"
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
