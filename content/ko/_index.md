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
  - block: markdown
    content:
      title: ""
      text: |
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.css">
        <div class="swiper mySwiper" style="height: 75vh;">
          <div class="swiper-wrapper">
            <!-- Slide 1 -->
            <div class="swiper-slide relative">
              <!-- 배경 이미지 -->
              <img src="/media/image.jpg" alt="프로젝트 A" class="w-full h-full object-cover">
              <!-- 반투명 오버레이 -->
              <div class="absolute inset-0 bg-black/40"></div>
              <!-- 텍스트 오버레이 -->
              <div class="absolute inset-0 flex items-center justify-center text-center p-6">
                <div>
                  <h2 class="text-4xl md:text-5xl font-extrabold text-white mb-3">신서현의 포트폴리오</h2>
                  <p class="text-white/90 text-lg">연구 · 로보틱스 · 백엔드</p>
                </div>
              </div>
            </div>

            <!-- Slide 2 -->
            <div class="swiper-slide relative">
              <img src="/media/image2.jpg" alt="프로젝트 B" class="w-full h-full object-cover">
              <div class="absolute inset-0 bg-slate-900/40"></div>
              <div class="absolute inset-0 flex items-center justify-center text-center p-6">
                <div>
                  <h2 class="text-4xl md:text-5xl font-extrabold text-white mb-3">Autonomous Driving</h2>
                  <p class="text-white/90 text-lg">DDP · CDDP · ROS</p>
                </div>
              </div>
            </div>

            <!-- Slide 3 -->
            <div class="swiper-slide relative">
              <img src="/media/image.jpg" alt="프로젝트 C" class="w-full h-full object-cover">
              <div class="absolute inset-0 bg-emerald-900/35"></div>
              <div class="absolute inset-0 flex items-center justify-center text-center p-6">
                <div>
                  <h2 class="text-4xl md:text-5xl font-extrabold text-white mb-3">Semiconductor Memory</h2>
                  <p class="text-white/90 text-lg">1T DRAM · FBRAM · SiGeC</p>
                </div>
              </div>
            </div>

          </div>

          <!-- 네비/도트 -->
          <div class="swiper-pagination"></div>
          <div class="swiper-button-prev"></div>
          <div class="swiper-button-next"></div>
        </div>

        <script src="https://cdn.jsdelivr.net/npm/swiper@11/swiper-bundle.min.js"></script>
        <script>
          // 바꾸고 싶은 자동 전환 간격(ms)을 여기서 설정
          const SLIDE_INTERVAL_MS = 2000; // 예: 3초

          const swiper = new Swiper('.mySwiper', {
            loop: true,
            autoplay: { delay: SLIDE_INTERVAL_MS, disableOnInteraction: false, pauseOnMouseEnter: true },
            pagination: { el: '.swiper-pagination', clickable: true },
            navigation: { nextEl: '.swiper-button-next', prevEl: '.swiper-button-prev' },
            speed: 500, // 슬라이드 전환 애니메이션 속도(ms)
          });
        </script>
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
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - events
    design:
      view: card
  - block: collection
    id: news
    content:
      title: Recent News
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
      view: card
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
---
