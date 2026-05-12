---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      username: admin
      text: ''
      button:
        text: Download CV
        url: uploads/portfolio.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      css_class: hbx-bg-gradient
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded

  #- block: github.imsh429.slider
  #  content: {} #layouts/partials/hbx/blocks/github.imhsh429.slider/block.html에서 설정 가능
  #  design:
  #    spacing:
  #      padding: [0,0,0,0]  # 좌우 패딩 제거(가로 꽉 차게)

  #- block: collection
  #  id: projects
  #  content:
  #    title: 대표 프로젝트
  #    filters:
  #      folders:
  #        - projects
  #      featured_only: true
  #  design:
  #    view: article-grid
  #    columns: 2
---
