---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Back-tracing Representative Points for Voting-based 3D Object Detection in Point Clouds"
authors: ["Bowen Cheng, Lu Sheng#, Shaoshuai Shi, Ming Yang, Dong Xu"]
date: 2021-06-19
doi: 

# Schedule page publish date (NOT publication's date).
publishDate: 2021-10-04T22:11:31+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE/CVF Conference on Computer Vision and Pattern Recognition"
publication_short: "CVPR"

abstract: "3D object detection in point clouds is a challenging vision task that benefits various applications for understanding the 3D visual world. Lots of recent research focuses on how to exploit end-to-end trainable Hough voting for generating object proposals. However, the current voting strategy can only receive partial votes from the surfaces of potential objects together with severe outlier votes from the cluttered backgrounds, which hampers full utilization of the information from the input point clouds. Inspired by the back-tracing strategy in the conventional Hough voting methods, in this work, we introduce a new 3D object detection method, named as Back-tracing Representative Points Network (BRNet), which generatively back-traces the representative points from the vote centers and also revisits complementary seed points around these generated points, so as to better capture the fine local structural features surrounding the potential objects from the raw point clouds. Therefore, this bottom-up and then top-down strategy in our BRNet enforces mutual consistency between the predicted vote centers and the raw surface points and thus achieves more reliable and flexible object localization and class prediction results. Our BRNet is simple but effective, which significantly outperforms the state-of-the-art methods on two large-scale point cloud datasets, ScanNet V2 (+ 7.5% in terms of mAP@ 0.50) and SUN RGB-D (+ 4.7% in terms of mAP@ 0.50), while it is still lightweight and efficient."

# Summary. An optional shortened abstract.
summary: "Accepted by IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2021. A lightweight model with SOTA results on ScanNet V2 and SUN RGB-D datasets."

tags: []
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
- name: Ranks in Papers with Code
  url: https://paperswithcode.com/paper/back-tracing-representative-points-for-voting
  icon_pack: fab
  icon: hackerrank

url_pdf: "https://openaccess.thecvf.com/content/CVPR2021/papers/Cheng_Back-Tracing_Representative_Points_for_Voting-Based_3D_Object_Detection_in_Point_CVPR_2021_paper.pdf"
url_code: "https://github.com/cheng052/BRNet"
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
