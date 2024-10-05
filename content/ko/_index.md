---
# Leave the homepage title empty to use the site title
title:
date: 2024-03-25
type: landing

sections:
  

  - block: features
    content:
      title: <span style="font-size:70%">Medical AI & Computational Science (Macs) Lab </span>
      text: <br><span style="font-size:125%">전북대학교 의료 AI 및 계산 과학 연구실 홈페이지에 오신 것을 환영합니다.</span> <br><br>
        {{% cta cta_link="./field/" cta_text="See Research Field →" %}}


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

      - title: <span style="font-size:70%">Computer Vision</span>
        content: <span style="font-size:60%">이미지를 분석하고 이해하여 객체 인식, 장면 해석, 동작 추적 등 시각적 데이터를 처리하는 AI 기술 분야</span>
        align: left
        background:
          image:
            filename: image2_cv.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'

      - title: <span style="font-size:70%">Machine Learning</span>
        content: <span style="font-size:70%">데이터로부터 패턴을 학습하고 예측을 수행하도록 컴퓨터를 훈련시키는 AI 기술</span>
        align: right
        background:
          image:
            filename: image3_ml.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'

      - title: <span style="font-size:70%">Development</span>
        content: <span style="font-size:70%">창의적인 아이디어를 기술적으로 구현하고, 소프트웨어와 시스템을 설계, 구축, 유지보수하는 과정</span>
        align: center
        background:
          image:
            filename: development.jpg
            filters:
              brightness: 0.5
          position: left
          color: '#333'

      - title: <span style="font-size:70%">Contact</span>
        content: <span style="font-size:70%">How to contact me...</span>
        align: center
        background:
          image:
            filename: contact.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
            icon: graduation-cap
            icon_pack: fas
            text: contact me
            url: ../contact/

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '350px'
      slide_width: '100px'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000


  - block: features
    id: features
    content:
      title: <span style="font-size:75%">Lab's Interests</span>
      text: 저희 연구실에서는 다음과 같은 연구/개발 분야에 관심을 쏟고 있습니다.<br><br><br><br>
      items:
        - name: 인공지능(AI)
          icon: code-branch
          icon_pack: fas
          description: <span style="font-size:90%">의료 (Medical), 항공우주 (Aerospace), 컨텐츠 (Contents) 등 다양한 특성화 분야에 적응형 AI 기술 적용.</span><br><br>
        - name: 멀티모달(Multi-modality)
          icon: globe
          icon_pack: fas
          description:  <span style="font-size:90%">Vision & Language 분야의 기반 AI 기술 개발 및 관련 응용 어플리케이션에 기술 적용.</span><br><br>
        - name: 의료수학(Medical Math)
          icon: calculator
          icon_pack: fas
          description:  <span style="font-size:90%">의료 분야에 대한 통계 분석 수행 및 의료 질병에 대한 수학적인 모델링 관련 연구 수행.</span><br><br>
        - name: 컨텐츠 (Contents)
          icon: comment-dots
          icon_pack: fas
          description:  <span style="font-size:90%">웹툰 및 미디어 컨텐츠와 관련된 AI 기반 기술 개발 및 고도화.</span><br><br>
        - name: 개발 (Development)
          icon: laptop
          icon_pack: fas
          description:  <span style="font-size:90%">Full-Stack 기반의 응용 어플리케이션 개발.</span><br><br>
        - name: 솔루션 (Solution)
          icon: app-store-ios
          icon_pack: fab
          description:  <span style="font-size:90%">AI 기반기술 및 관련 어플리케이션에 적용을 통한 통합 솔루션 개발!</span><br><br>


  - block: collection
    content:
      id: section-1
      title: Notifications & News
      subtitle:
      text:
      count: 3
      offset: 0
      order: desc
      filters:
        folders:
          - notification
          - post
          - event
    design:
      view: community/custom_card
      columns: '2'

  - block: collection
    content:
      title: Latest Publications
      subtitle:
      text:
      count: 3
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: publication
    design:
      view: community/custom_card
      columns: '2'
    advanced:
      css_style: "text-align: center;"

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./contact/" cta_text="Join team →" %}}
    design:
      columns: '1'
---