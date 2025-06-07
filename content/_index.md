---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: CV/CV-JiayuLiu.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: background.png
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        My recent research focuses on optimizing urban traffic networks using deep reinforcement learning. Additionally, our team, led by Associate Professor Xiping Yang (xpyang@snnu.edu.cn), works in the areas of trajectory representation and prediction, urban transportation and sustainable development.
        
        Please reach out to collaborate 😃
    design:
      columns: '1'
 
  - block: markdown
    content:
      title: Recent Publications
      text: |-
       •<b>Liu Jiayu</b>, Yang Xiping*, Huang Xiaoyan, Li Jiyuan, Li Junyi, Chen Hongfei, An Rui, Song Yongyong. Introducing street view into node-place model for evaluating transit-oriented development[J]. Journal of Transport Geography. (2025, Major and Revised for review)
        
        •<b>Liu Jiayu</b>, Yang Xiping*, Luo Lin, Li Junyi, Chen Hongfei, An Rui, Li Jiyuan. Inspecting urban transit-oriented development from perspectives of human activity[J]. Journal of Transport Geography. (2025, Major and Revised for review)
        
        •Yang Xiping, <b>Liu Jiayu</b>, Tu Wei*, Zhao Zhiyuan, An Rui, Li Jiyuan. A multi-objective optimization framework for locating metro stations by integrating travel demand, accessibility and land use intensity[J]. Computers, Environment and Urban Systems. (2025, Under Review)
        
        •Yang Xiping*, Luo Lin, <b>Liu Jiayu</b>, Chen Hongfei, Li Junyi. Evaluating the Improvement of Healthcare Accessibility for Urban Residents via the Construction of New Hospitals: A Case Study of Xi’an, China[J]. Applied Spatial Analysis and Policy, 18(5)（2025）.
        
        •Luo Lin, Yang Xiping, Chen Xueye*, <b>Liu Jiayu</b>, An Rui, Li Jiyuan. Nonlinear Influence of the Built Environment on the Attraction of the Third Activity: A Comparative Analysis of Inflow from Home and Work[J]. ISPRS International Journal of Geo-Information, 13(9): 337（2024）.
        
        •Huang Tao, Jiao Lei*, Bai Yingfei, Yan Jianwu, Yang Xiping, <b>Liu Jiayu</b>, Liang Wei, Luo Da, Zhang Liwei, Wang Hao, Li Zhaolin, Li Zongshan, Ji Ni, Gao Guangyao. Enhancing vegetation fine-scale classification accuracy in complex topography via machine learning: An approach that fuses UAV-LiDAR and high-resolution imagery[J]. Computers and Electronics in Agriculture. 235,110360(2025).
    design:
      columns: '1'
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1
  
---
