---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Cross-view Semantic Segmentation for Sensing Surroundings"
authors: ["Bowen Pan", "Jiankai Sun", "Ho Yin Tiga Leung", "Alex Andonian", "Bolei Zhou"]
date: 2020-06-18T00:06:23Z
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-06-18T00:06:23Z

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "IEEE International Conference on Intelligent Robots and Systems (IROS) 2020"
publication_short: "IROS2020"

abstract: "— Sensing surroundings plays a crucial role in human spatial perception, as it extracts the spatial configuration of objects as well as the free space from the observations. To facilitate the robot perception with such a surrounding sensing capability, we introduce a novel visual task called Cross-view Semantic Segmentation as well as a framework named View Parsing Network (VPN) to address it. In the cross-view semantic segmentation task, the agent is trained to parse the first-view observations into a top-down-view semantic map indicating the spatial location of all the objects at pixel-level. The main issue of this task is that we lack the real-world annotations of top-down view data. To mitigate this, we train the VPN in 3D graphics environment and utilise the domain adaptation technique to transfer it to handle real-world data. We evaluate our VPN on both synthetic and real-world agents. The experimental results show that our model can effectively make use of the information from different views and multi-modalities to understanding spatial information. Our further experiment on a LoCoBot robot shows that our model enables the surrounding sensing capability from 2D image input. Code and demo videos can be found at https://view-parsing-network.github.io."

# Summary. An optional shortened abstract.
summary: ""

tags: ["semantic-segmentation", "navigation", "machine-learning", "mobile-robots", "PyRobot"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://ras.papercept.net/proceedings/IROS20/2531.pdf"
url_code: "https://github.com/pbw-Berwin/View-Parsing-Network"
url_dataset:
url_poster: "https://decisionforce.github.io/VPN/"
url_project: "/project/Cross-view Semantic Segmentation for Sensing Surroundings/"
url_slides:
url_source:
url_video: "https://decisionforce.github.io/VPN/View_Parsing_Network_files/demo_video.m4v"

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
