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

  - block: markdown
    content:
      title: ""
      text: |
        <div class="swiper js-swiper" data-delay="2500">
          <div class="swiper-wrapper">

            <!-- Slide 1 -->
            <div class="swiper-slide relative">
              <img src="/media/slide1.jpg" alt="슬라이드 1" class="w-full h-[55vh] md:h-[70vh] object-cover">
              <div class="absolute inset-0 bg-black/40"></div> <!-- 투명도 오버레이 -->
              <div class="absolute inset-0 flex items-center justify-center text-center p-6">
                <div>
                  <h2 class="text-3xl md:text-5xl font-extrabold text-white">헤드라인 1</h2>
                  <p class="text-white/90 md:text-lg mt-2">서브텍스트 1</p>
                </div>
              </div>
            </div>

            <!-- Slide 2 -->
            <div class="swiper-slide relative">
              <img src="/media/slide2.jpg" alt="슬라이드 2" class="w-full h-[55vh] md:h-[70vh] object-cover">
              <div class="absolute inset-0 bg-black/40"></div>
              <div class="absolute inset-0 flex items-center justify-center text-center p-6">
                <div>
                  <h2 class="text-3xl md:text-5xl font-extrabold text-white">헤드라인 2</h2>
                  <p class="text-white/90 md:text-lg mt-2">서브텍스트 2</p>
                </div>
              </div>
            </div>

            <!-- Slide 3 -->
            <div class="swiper-slide relative">
              <img src="/media/slide3.jpg" alt="슬라이드 3" class="w-full h-[55vh] md:h-[70vh] object-cover">
              <div class="absolute inset-0 bg-black/40"></div>
              <div class="absolute inset-0 flex items-center justify-center text-center p-6">
                <div>
                  <h2 class="text-3xl md:text-5xl font-extrabold text-white">헤드라인 3</h2>
                  <p class="text-white/90 md:text-lg mt-2">서브텍스트 3</p>
                </div>
              </div>
            </div>

          </div>

          <!-- 네비/도트 -->
          <div class="swiper-pagination"></div>
          <div class="swiper-button-prev"></div>
          <div class="swiper-button-next"></div>
        </div>
    design:
      columns: 1


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
