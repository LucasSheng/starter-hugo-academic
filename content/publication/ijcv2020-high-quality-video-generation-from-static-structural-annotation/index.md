---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "High Quality Video Generation From Static Structural Annotations"
authors: ["Lu Sheng, Junting Pan, Jiaming Guo, Jing Shao, Chen Change Loy"]
date: 2020-05-28
doi: "10.1007/s11263-020-01334-x"

# Schedule page publish date (NOT publication's date).
publishDate: 2021-10-05T13:27:29+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "International Journal of Computer Vision"
publication_short: "IJCV"

abstract: "This paper proposes a novel unsupervised video generation that is conditioned on a single structural annotation map, which in contrast to prior conditioned video generation approaches, provides a good balance between motion flexibility and visual quality in the generation process. Different from end-to-end approaches that model the scene appearance and dynamics in a single shot, we try to decompose this difficult task into two easier sub-tasks in a divide-and-conquer fashion, thus achieving remarkable results overall. The first sub-task is an image-to-image (I2I) translation task that synthesizes high-quality starting frame from the input structural annotation map. The second image-to-video (I2V) generation task applies the synthesized starting frame and the associated structural annotation map to animate the scene dynamics for the generation of a photorealistic and temporally coherent video. We employ a cycle-consistent flow-based conditioned variational autoencoder to capture the long-term motion distributions, by which the learned bi-directional flows ensure the physical reliability of the predicted motions and provide explicit occlusion handling in a principled manner. Integrating structural annotations into the flow prediction also improves the structural awareness in the I2V generation process. Quantitative and qualitative evaluations over the autonomous driving and human action datasets demonstrate the effectiveness of the proposed approach over the state-of-the-art methods."

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

url_pdf: "https://link.springer.com/content/pdf/10.1007/s11263-020-01334-x.pdf"
url_code: "https://github.com/junting/seg2vid"
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
