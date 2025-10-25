---
title: 'Projects'
date: 2024-05-19
type: landing

design:
  spacing: '0'

sections:
  - block: github.imsh429.banner_pj
    content:
      image: "/media/banner1.jpg"
      alt: "Projects banner"
      overlay_opacity: "0.2"   # 배경 어둡게 안 하고 싶으면 0.0
    design:
      height:
        base: "14vh"
        md: "18vh"
      spacing:
        padding: [0,0,0,0]
        margin: [0,0,0,0]

  - block: collection
    content:
      title: 'Projects' 
      text: Here, I introduce a collection of projects I have completed. I have built diverse development experience based on my academic studies and personal interests.
      count: 0
      filters:
        folders: [projects]
      sort_by: "weight"
    design:
      view: article-grid
      fill_image: false
      columns: 3
      show_date: false
      show_read_time: false
      show_read_more: false
---
