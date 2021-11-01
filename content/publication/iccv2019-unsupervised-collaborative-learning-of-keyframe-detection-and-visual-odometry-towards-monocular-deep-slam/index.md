---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Unsupervised Collaborative Learning of Keyframe Detection and Visual Odometry towards Monocular Deep SLAM"
authors: ["Lu Sheng*, Dan Xu*, Wanli Ouyang, Xiaogang Wang"]
date: 2019-10-27
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-10-05T13:43:57+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE/CVF International Conference on Computer Vision"
publication_short: "ICCV"

abstract: "In this paper we tackle the joint learning problem of keyframe detection and visual odometry towards monocular visual SLAM systems. As an important task in visual SLAM, keyframe selection helps efficient camera relocalization and effective augmentation of visual odometry. To benefit from it, we first present a deep network design for the keyframe selection, which is able to reliably detect keyframes and localize new frames, then an end-to-end unsupervised deep framework further proposed for simultaneously learning the keyframe selection and the visual odometry tasks. As far as we know, it is the first work to jointly optimize these two complementary tasks in a single deep framework. To make the two tasks facilitate each other in the learning, a collaborative optimization loss based on both geometric and visual metrics is proposed. Extensive experiments on publicly available datasets (ie KITTI raw dataset and its odometry split) clearly demonstrate the effectiveness of the proposed approach, and new state-of-the-art results are established on the unsupervised depth and pose estimation from monocular videos."

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

url_pdf: "https://openaccess.thecvf.com/content_ICCV_2019/papers/Sheng_Unsupervised_Collaborative_Learning_of_Keyframe_Detection_and_Visual_Odometry_Towards_ICCV_2019_paper.pdf"
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
