---
title: 'Projects'
date: 2024-05-19
type: landing

design:
  spacing: '5rem'

sections:
  - block: markdown
    content:
      title: "" 
      text: |
        <section class="relative w-full h-[30vh] md:h-[42vh] overflow-hidden">
          <!-- 배경 이미지 -->
          <img
            class="absolute inset-0 w-full h-full object-cover object-center"
            src="/media/image.jpg"                      <!-- 이미지 경로 -->
            alt="Projects banner" loading="eager" decoding="async">

          <!-- 어둡게 오버레이 (공식 템플릿 느낌) -->
          <div class="absolute inset-0 bg-black/30 md:bg-black/35"></div>

          <!-- 콘텐츠 컨테이너 (공식 템플릿의 max-w + 좌우 패딩) -->
          <div class="relative z-10 flex h-full items-center">
            <div class="w-full max-w-screen-xl mx-auto px-6 md:px-8">
              <!-- 타이틀 -->
              <h1 class="text-white font-extrabold tracking-tight
                        text-3xl md:text-5xl lg:text-6xl drop-shadow-sm">
                프로젝트
              </h1>
              <!-- 서브텍스트 (원하면 지워도 됨) -->
              <p class="mt-2 md:mt-3 text-white/90 text-base md:text-xl max-w-3xl">
                제가 진행한 프로젝트들을 모아 소개합니다.
              </p>
            </div>
          </div>
        </section>
  - block: collection
    content:
      title: '' 
      text: 제가 진행한 프로젝트들을 모아 소개합니다. 학업과 개인적인 관심사를 바탕으로 다양한 개발 경험을 쌓았습니다.
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
