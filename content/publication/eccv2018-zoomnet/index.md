---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Zoom-Net: Mining Deep Feature Interactions for Visual Relationship Recognition"
authors: ["Guojun Yin, Lu Sheng, Bin Liu, Nenghai Yu, Xiaogang Wang, Jing Shao, Chen Change Loy"]
date: 2018-09-08
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-10-05T14:11:55+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "European Conference on Computer Vision"
publication_short: "ECCV"

abstract: "Recognizing visual relationships< subject-predicate-object> among any pair of localized objects is pivotal for image understanding. Previous studies have shown remarkable progress in exploiting linguistic priors or external textual information to improve the performance. In this work, we investigate an orthogonal perspective based on feature interactions. We show that by encouraging deep message propagation and interactions between local object features and global predicate features, one can achieve compelling performance in recognizing complex relationships without using any linguistic priors. To this end, we present two new pooling cells to encourage feature interactions:(i) Contrastive ROI Pooling Cell, which has a unique deROI pooling that inversely pools local object features to the corresponding area of global predicate features.(ii) Pyramid ROI Pooling Cell, which broadcasts global predicate features to reinforce local object features. The two cells constitute a Spatiality-Context-Appearance Module (SCA-M), which can be further stacked consecutively to form our final Zoom-Net. We further shed light on how one could resolve ambiguous and noisy object and predicate annotations by Intra-Hierarchical trees (IH-tree). Extensive experiments conducted on Visual Genome dataset demonstrate the effectiveness of our feature-oriented approach compared to state-of-the-art methods (Acc@ 1 11.42% from 8.16%) that depend on explicit modeling of linguistic interactions. We further show that SCA-M can be incorporated seamlessly into existing approaches to improve the performance by a large margin."

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

url_pdf: "https://openaccess.thecvf.com/content_ECCV_2018/papers/Guojun_Yin_Zoom-Net_Mining_Deep_ECCV_2018_paper.pdf"
url_code: "https://github.com/gjyin91/ZoomNet"
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
