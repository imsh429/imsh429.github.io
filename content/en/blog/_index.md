---
title: Blog
date: 2025-10-17
type: landing

# View
design:
  spacing: '0'

sections:
  - block: github.imsh429.banner_blog
    content:
      image: "/media/banner5.jpg"
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
      title: 'Blog' 
      text: Recording daily life.
      count: 0
      filters:
        folders: [blog]        
      #sort_by: "Date"
      #sort_ascending: false
    design:
      view: card 
      fill_image: false 
      columns: 3
      show_date: true
      show_read_time: false
      show_read_more: false
---
