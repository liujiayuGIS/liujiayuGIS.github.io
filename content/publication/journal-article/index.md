---
# 论文标题
title: "Deciphering the UAV-LIDAR contribution to vegetation classification using interpretable machine learning"

# 作者列表。这里假设您是 Xiping Yang，因此将您的名字映射为 `admin` (网站所有者)。
# 其他作者按原样列出。
authors:
- Tao Huang
- Lei Jiao
- Yingfei Bai
- Jianwu Yan
- admin # 对应 Xiping Yang
- Jiayu Liu
- Wei Liang
- Da Luo
- Liwei Zhang
- Hao Wang
- Zhaolin Li
- Zongshan Li
- Ni Ji
- Guangyao Gao

# 作者备注，如“同等贡献”。此论文无相关说明，故留空。
author_notes: []

# 论文的实际发表日期
date: "2025-04-09T00:00:00Z"
# DOI (数字对象标识符)
doi: "10.1016/j.compag.2025.110360"

# 此页面在您网站上的发布日期 (可以与论文发表日期不同)
publishDate: "2025-06-07T00:00:00Z"

# 出版物类型，"article-journal" 代表期刊文章
publication_types: ["article-journal"]

# 发表刊物名称
publication: "*Computers and Electronics in Agriculture, 235*, 110360"
# 发表刊物简称 (可选)
publication_short: "*Compag*, 235, 110360"

# 论文摘要
abstract: "Accurate classification of land cover types is a prerequisite for the protection of natural ecosystems. In particular, understanding the spatial distributions of different vegetation types is essential for the effective management, monitoring, and conservation of forest ecosystems. Satellite remote sensing uses rich spectral band information for land cover classification, but it is usually insufficient for high-precision vegetation classification work in small areas. However, the structure and vegetation information provided by Aerial LIDAR Scanning (ALS) can significantly increase the classification accuracy. To address these limitations, this study utilized high-resolution unmanned aerial vehicle (UAV) imagery and aerial LiDAR point cloud data to improve the accuracy of vegetation classification and plantation observation at the catchment scale. Using Google Earth Engine (GEE), spectral, textural, and LiDAR-derived topographic and vegetation features are extracted and integrated, followed by supervised classification using Random Forest (RF) and Support Vector Machine (SVM) models. This approach enhances the accuracy and efficiency of vegetation classification at the catchment scale. The classification results of SVM and RF demonstrated that incorporating LiDAR-derived topographic and vegetation features significantly improved the classification accuracy compared to using spectral and textural features only. Specifically, the overall accuracy (OA) of the RF classification increased from 94.37% to 99.36%, while the kappa coefficient improved from 91.08 % to 99.01 %. Moreover, the impact threshold analysis based on SHAP values showed that canopy height, tree density, and elevation were the top three key features driving the improvement in the classification performance. This study offers new insights and methods for vegetation classification in complex ecological environments."

# 论文的简短总结 (可选)
summary: "This study utilizes high-resolution UAV imagery and aerial LiDAR point cloud data to enhance vegetation classification accuracy. By integrating spectral, textural, and LiDAR-derived features with machine learning models (RF and SVM), the overall accuracy was significantly improved from 94.37% to 99.36%, demonstrating the critical contribution of LiDAR data."

# 标签，来自论文关键词
tags:
- LiDAR
- Random Forest
- GEE
- Vegetation classification
- SHAP
- Interpretable Machine Learning

# 是否在主页的“精选出版物”中突出显示
featured: true

# 相关链接。请在此处填入您自己的真实链接。
# 例如，如果您想提供一个公开的 PDF 版本，可以上传到 `static/uploads/` 目录，然后链接到 `uploads/mypaper.pdf`
url_pdf: ""
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# 特色图片
# 要使用，请将名为 `featured.jpg` 或 `featured.png` 的图片添加到此文章所在的文件夹中。
image:
  caption: '' # 图片说明 (可选)
  focal_point: "Smart" # 图片裁剪焦点 (Smart, Center, Top, etc.)
  preview_only: false

# 关联的项目 (可选)
# 如果您想将此出版物与您网站上的某个项目关联，请在此处填入项目文件夹的名称。
projects: []

# 关联的幻灯片 (可选)
# 如果您为此文章制作了幻灯片，请在此处填入幻灯片文件的名称。
slides: ""
---

{{% callout note %}}
访客可以点击上方的“引用 (Cite)”按钮，方便地将这篇出版物的元数据导入到他们的文献管理软件中。
{{% /callout %}}

您可以在这里添加关于这篇 **UAV-LiDAR 植被分类研究** 的补充说明、方法细节、更多图表或研究亮点。您可以使用丰富的格式，例如 [代码、数学公式和图片](https://docs.hugoblox.com/content/writing-markdown-latex/)。
