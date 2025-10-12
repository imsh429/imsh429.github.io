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
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      css_class: hbx-bg-gradient
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded

  - block: slider
    content:
      slides:
      - title: <span style="font-size:70%">AI</span>
        content: <span style="font-size:60%">인간의 지능을 모방해 문제 해결, 학습, 패턴 인식 등의 작업을 자동으로 수행하는 기술</span>
        align: center
        background:
          image:
            filename: image1_ai.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
  - block: slider
    content:
      height: '70vh'        # 원하는 높이
      autoplay_ms: 2500     # 자동 전환 간격(ms)
      speed_ms: 500         # 전환 속도(ms)
      overlay: true         # 어두운 투명 레이어
      slides:
        - image: /media/slide1.jpg
          title: 신서현 포트폴리오
          subtitle: 연구 · 로보틱스 · 백엔드
        - image: /media/slide2.jpg
          title: Autonomous Driving
          subtitle: DDP · CDDP · ROS
        - image: /media/slide3.jpg
          title: Semiconductor Memory
          subtitle: DRAM · FBRAM · SiGeC
    design:
      spacing:
        padding: [0,0,0,0]  # 좌우 패딩 제거(가로 꽉 차게)
        
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: collection
    id: talks
    content:
      title: 뉴스
      filters:
        folders:
          - events
    design:
      view: community/card-wide
  - block: collection
    id: news
    content:
      title: 갤러리
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: blog
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ''
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: community/card-mini
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
---
