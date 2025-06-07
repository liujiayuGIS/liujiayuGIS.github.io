---
title: "Deciphering the UAV-LiDAR contribution to vegetation classification using interpretable machine learning"
authors:
- Tao Huang
- Lei Jiao
- Yingfei Bai
- Jianwu Yan
- Xiping Yang
- admin # This is you (Liu, Jiayu)
- Wei Liang
- Da Luo
- Liwei Zhang
- Hao Wang
- Zhaolin Li
- Zongshan Li
- Ni Ji
- Guangyao Gao
# author_notes:
# - "Equal contribution" # 如果有需要，可以取消注释并添加
# - "Equal contribution"
date: "2025-08-01T00:00:00Z"
doi: "10.1016/j.compag.2025.110360"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-06-07T00:00:00Z"

# Publication type.
# Enters a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Computers and Electronics in Agriculture, 235*, 110360"
publication_short: "*Comp. Electron. Agric., 235*, 110360"

abstract: "Accurate classification of land cover types is a prerequisite for the protection of natural ecosystems. In particular, understanding the spatial distributions of different vegetation types is essential for the effective management, monitoring, and conservation of forest ecosystems. Satellite remote sensing uses rich spectral band information for land cover classification, but it is usually insufficient for high-precision vegetation classification work in small areas. However, the structure and vegetation information provided by Aerial LiDAR Scanning (ALS) can significantly increase the classification accuracy. To address these limitations, this study utilized high-resolution unmanned aerial vehicle (UAV) imagery and aerial LiDAR point cloud data to improve the accuracy of vegetation classification and plantation observation at the catchment scale. Using Google Earth Engine (GEE), spectral, textural, and LiDAR-derived topographic and vegetation features are extracted and integrated, followed by supervised classification using Random Forest (RF) and Support Vector Machine (SVM) models. This approach enhances the accuracy and efficiency of vegetation classification at the catchment scale. The classification results of SVM and RF demonstrated that incorporating LiDAR-derived topographic and vegetation features significantly improved the classification accuracy compared to using spectral and textural features only. Specifically, the overall accuracy (OA) of the RF classification increased from 94.37 % to 99.36 %, while the kappa coefficient improved from 91.08 % to 99.01 %. Moreover, the impact threshold analysis based on SHAP values showed that canopy height, tree density, and elevation were the top three key features driving the improvement in the classification performance. This study offers new insights and methods for vegetation classification in complex ecological environments."

# Summary. An optional shortened abstract.
summary: "This study utilizes high-resolution UAV imagery and aerial LiDAR point cloud data to improve the accuracy of vegetation classification. The results demonstrate that incorporating LiDAR-derived features significantly improved classification accuracy from 94.37% to 99.36%."

tags:
- UAV
- LiDAR
- Machine Learning
- Vegetation Classification
- Remote Sensing

# I've set this to `true` to feature it on your homepage. Change to `false` if not needed.
featured: true

links:
- name: "View at Publisher"
  url: "https://linkinghub.elsevier.com/retrieve/pii/S0168169925004661"
url_pdf: '' 
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: '' # Optional image caption.
  focal_point: "Smart" # Options: Smart, Center, Top, Right, Left, Bottom
  preview_only: false

# Associated Projects (optional).
# Associate this publication with one or more of your projects.
# Simply enter your project's folder or file name without extension.
# E.g. `projects: ["internal-project"]` references `content/project/internal-project/index.md`.
# Otherwise, set `projects: []`.
projects: []

# Slides (optional).
# Associate this publication with Markdown slides.
# Simply enter your slide deck's filename without extension.
# E.g. `slides: "example"` references `content/slides/example/index.md`.
# Otherwise, set `slides: ""`.
slides: ""
---


Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
