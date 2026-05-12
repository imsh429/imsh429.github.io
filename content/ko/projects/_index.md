---
title: 'Projects'
date: 2024-05-19
type: landing

sections:
  - block: github.imsh429.banner_pj
    content:
      image: "/media/banner1.jpg"
      alt: "Projects banner"
      overlay_opacity: "0.2"
    design:
      height:
        base: "14vh"
        md: "18vh"
      spacing:
        padding: [0,0,0,0]
        margin: [0,0,0,0]

  # 🌐 섹션 1: 메인 프로젝트
  - block: collection
    content:
      title: '🌐 메인 프로젝트' 
      text: "진행한 주요 프로젝트들을 소개합니다. 상세한 구현 과정과 기술 스택은 각 항목의 GitHub 저장소(README)에서 확인하실 수 있습니다."
      filters:
        folders: [projects]
        tags: ['Main']  # 각 프로젝트의 index.md에 'tags: ["Main"]'이 있어야 함
      sort_by: "weight"
    design:
      view: article-grid
      columns: 3

  # 🤖 섹션 2: AI & 데이터 분석
  - block: collection
    content:
      title: '🤖 인공지능 & NLP' 
      #text: Python과 PyTorch를 이용한 모델링 및 데이터 사이언스 프로젝트입니다.
      filters:
        folders: [projects]
        tags: ['AI']   # 각 프로젝트의 index.md에 'tags: ["AI"]'가 있어야 함
      sort_by: "weight"
    design:
      view: article-grid
      columns: 3

  # 🎨 섹션 3: 사이드 프로젝트
  - block: collection
    content:
      title: '🎨 사이드 프로젝트' 
      #text: 개인적인 흥미로 진행한 다양한 사이드 프로젝트들입니다.
      filters:
        folders: [projects]
        tags: ['Side'] # 'tags: ["Side"]'가 있는 것들
      sort_by: "weight"
    design:
      view: article-grid
      columns: 3
---