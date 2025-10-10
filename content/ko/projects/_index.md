---
title: 'Projects'
date: 2024-05-19
type: landing

design:
  spacing: '0'

sections:
  - block: markdown
    content:
      title: ""
      text: |
        <div class="relative left-1/2 right-1/2 -ml-[50vw] -mr-[50vw] w-screen
                    -mt-24 md:-mt-28 lg:-mt-32">
          <section class="relative w-full h-[14vh] md:h-[18vh] overflow-hidden transform -translate-y-px">
            <img
              class="absolute inset-0 w-full h-full object-cover object-center"
              src="/media/image.jpg"  
              alt="Projects banner" loading="eager" decoding="async">
            <!-- 필요하면 오버레이 사용/삭제 -->
            <!-- <div class="absolute inset-0 bg-black/20 md:bg-black/25"></div> -->
          </section>
        </div>
  - block: collection
    content:
      title: '프로젝트' 
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
