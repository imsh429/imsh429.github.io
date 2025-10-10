---
title: 'Projects'
date: 2024-05-19
type: landing

design:
  spacing: '5rem'

sections:
  - block: markdown
    content:
      title: "프로젝트" 
      text: |
        <section class="relative w-full h-[28vh] md:h-[36vh] overflow-hidden">
          <img class="absolute inset-0 w-full h-full object-cover object-center"
               src="/media/image.jpg" alt="프로젝트 배너" loading="eager" decoding="async">
          <div class="absolute inset-0 bg-black/20"></div>
          <div class="relative z-10 flex h-full w-full items-center justify-center px-6 md:px-10">
            <h1 class="text-2xl md:text-4xl font-extrabold text-white drop-shadow-sm">프로젝트</h1>
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
