---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "3DVG-Transformer: Relation Modeling for Visual Grounding on Point Clouds"
authors: ["Lichen Zhao*, Daigang Cai*, Lu Sheng#, Dong Xu"]
date: 2021-10-11
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-10-05T22:32:42+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE/CVF International Conference on Computer Vision"
publication_short: "ICCV"

abstract: "Visual grounding on 3D point clouds is an emerging vision and language task that benefits various applications in understanding the 3D visual world. By formulating this task as a grounding-by-detection problem, lots of recent works focus on how to exploit more powerful detectors and comprehensive language features, but (1) how to model complex relations for generating context-aware object proposals and (2) how to leverage proposal relations to distinguish the true target object from similar proposals are not fully studied yet. Inspired by the well-known transformer architecture, we propose a relation-aware visual grounding method on 3D point clouds, named as 3DVG-Transformer, to fully utilize the contextual clues for relation-enhanced proposal generation and cross-modal proposal disambiguation, which are enabled by a newly designed coordinate-guided contextual aggregation (CCA) module in the object proposal generation stage, and a multiplex attention (MA) module in the cross-modal feature fusion stage. We validate that our 3DVG-Transformer outperforms the state-of-the-art methods by a large margin, on two point cloud-based visual grounding datasets, ScanRefer and Nr3D/Sr3D from ReferIt3D, especially for complex scenarios containing multiple objects of the same category."

# Summary. An optional shortened abstract.
summary: "Accepted by IEEE/CVF International Conference on Computer Vision (ICCV), 2021. **1st place** (up to Oct. 10, 2021) in the [ScanRefer Benchmark](http://kaldir.vc.in.tum.de/scanrefer_benchmark/), **winner** for the 3D Object Localization Challenge at the [CVPR 2021, 1st Workshop on Language for 3D Scenes](https://language3dscenes.github.io/)."

tags: []
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: Ranks in ScanRefer Benchmark
  url: http://kaldir.vc.in.tum.de/scanrefer_benchmark/
  icon_pack: fab
  icon: hackerrank

url_pdf: "http://openaccess.thecvf.com/content/ICCV2021/papers/Zhao_3DVG-Transformer_Relation_Modeling_for_Visual_Grounding_on_Point_Clouds_ICCV_2021_paper.pdf"
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
