---
title: 'Projects'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'
  
# banner:
  # image: 'sharing.png'

# Page sections
sections:
  - block: markdown
      content:
        title: ""
        text: |
          <section class="relative h-[60vh] flex items-center justify-center">
            <img src="/media/sharing.png" alt="Projects banner" class="absolute inset-0 w-full h-full object-cover">
            <div class="absolute inset-0 bg-black/40"></div>
            <div class="relative text-center text-white z-10">
              <h1 class="text-5xl font-bold mb-3">프로젝트</h1>
              <p class="text-lg opacity-90">제가 진행한 프로젝트들을 모아 소개합니다.</p>
            </div>
          </section>
  - block: collection
    content:
      title: 프로젝트
      text: 제가 진행한 프로젝트들을 모아 소개합니다. 학업과 개인적인 관심사를 바탕으로 다양한 개발 경험을 쌓았습니다.
      count: 0
      filters:
        folders:
          - projects
      sort_by: "weight"
    design:
      view: article-grid
      fill_image: false
      columns: 3
      show_date: false
      show_read_time: false
      show_read_more: false
---
