---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "VoteHMR: Occlusion-Aware Voting Network for Robust 3D Human Mesh Recovery from Partial Point Clouds"
authors: ["Guanze Liu, Yu Rong, Lu Sheng#"]
date: 2021-10-20
doi: "10.1145/3474085.3475309"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-10-05T22:33:01+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the 29th ACM international Conference on Multimedia"
publication_short: "ACM MM"

abstract: "3D human mesh recovery from point clouds is essential for vari- ous tasks, including AR/VR and human behavior understanding. Previous works in this field either require high-quality 3D human scans or sequential point clouds, which cannot be easily applied to low-quality 3D scans captured by consumer-level depth sensors. In this paper, we make the first attempt to reconstruct reliable 3D human shapes from single-frame partial point clouds. To achieve this, we propose an end-to-end learnable method, named VoteHMR. The core of VoteHMR is a novel occlusion-aware voting network that can first reliably produce visible joint-level features from the input partial point clouds, and then complete the joint-level features through the kinematic tree of the human skeleton. Compared with holistic features used by previous works, the joint-level features can not only effectively encode the human geometry information but also be robust to noisy inputs with self-occlusions and missing areas. By exploiting the rich complementary clues from the joint-level features and global features from the input point clouds, the proposed method encourages reliable and disentangled param- eter predictions for statistical 3D human models, such as SMPL. The proposed method achieves state-of-the-art performances on two large-scale datasets, namely SURREAL and DFAUST. Further- more, VoteHMR also demonstrates superior generalization ability on real-world datasets, such as Berkeley MHAD."

# Summary. An optional shortened abstract.
summary: "Accepted by ACM international Conference on Multimedia (ACM MM), 2021, as **Oral presentation**. "

tags: []
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: YouTube
#   url: https://twitter.com
#   icon_pack: fab
#   icon: youtube

url_pdf: "https://arxiv.org/pdf/2110.08729"
url_code: "https://github.com/hanabi7/VoteHMR"
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
  focal_point: "center"
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
