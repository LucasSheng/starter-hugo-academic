---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Morphing and Sampling Network for Dense Point Cloud Completion"
authors: ["Minghua Liu, Lu Sheng, Sheng Yang, Jing Shao, Shi-Min Hu"]
date: 2020-02-17
doi: "10.1609/aaai.v34i07.6827"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-10-05T13:38:21+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Thirty-Fourth AAAI Conference on Artifical Intelligence"
publication_short: "AAAI"

abstract: "3D point cloud completion, the task of inferring the complete geometric shape from a partial point cloud, has been attracting attention in the community. For acquiring high-fidelity dense point clouds and avoiding uneven distribution, blurred details, or structural loss of existing methods' results, we propose a novel approach to complete the partial point cloud in two stages. Specifically, in the first stage, the approach predicts a complete but coarse-grained point cloud with a collection of parametric surface elements. Then, in the second stage, it merges the coarse-grained prediction with the input point cloud by a novel sampling algorithm. Our method utilizes a joint loss function to guide the distribution of the points. Extensive experiments verify the effectiveness of our method and demonstrate that it outperforms the existing methods in both the Earth Mover's Distance (EMD) and the Chamfer Distance (CD)."

# Summary. An optional shortened abstract.
summary: "AAAI 2019"

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

url_pdf: "https://ojs.aaai.org/index.php/AAAI/article/view/6827"
url_code: "https://github.com/Colin97/MSN-Point-Cloud-Completion"
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
