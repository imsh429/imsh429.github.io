---
title: Events
date: 2025-10-17
type: landing

# View
design:
  spacing: '0'

sections:
  - block: collection
    content:
      # 섹션의 제목과 설명
      title: 'Events' 
      text: 새로운 소식을 알립니다.
      
      # 가져올 콘텐츠의 개수 (0은 모두 가져오기)
      count: 0
      
      # 필터링: 'talk' 폴더 안에 있는 콘텐츠만 가져오기 (가장 중요)
      filters:
        folders: [talk]
        
      # 정렬 순서: 날짜 내림차순 (최신순)
      #sort_by: "Date"
      #sort_ascending: false
      
    design:
      # 보여주기 방식: card, article-grid, compact 등 선택 가능
      view: card 
      # 카드 이미지 채우기 여부
      fill_image: true 
      # 한 줄에 표시할 개수
      columns: 2
      # 추가 정보 표시 여부 (날짜, 읽는 시간 등)
      show_date: true
      show_read_time: false
      show_read_more: true
---
