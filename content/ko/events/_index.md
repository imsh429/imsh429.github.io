---
title: Events
date: 2025-10-17
type: landing

# View
design:
  spacing: '0'

sections:
  - block: github.imsh429.banner_events
    content:
      image: "/media/banner4.jpg"
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
      title: '소식' 
      text: 새로운 소식을 알립니다.
      count: 0
      filters:
        folders: [events]        
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
