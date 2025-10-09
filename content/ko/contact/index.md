---
title: Contact
type: landing

sections:
  # 1️⃣ 연락처 정보 블록
  - block: features
    id: contact-info
    content:
      title: 연락처
      text: |
        문의나 협업 제안이 있으신 경우 아래 정보를 통해 연락주세요.
      items:
        - icon: envelope
          icon_pack: fas
          name: 이메일
          description: '[sh99429@naver.com](mailto:sh99429@naver.com)'
        - icon: phone
          icon_pack: fas
          name: 전화번호
          description: '010-2576-8297'
        - icon: map-marker-alt
          icon_pack: fas
          name: 주소
          description: '(54896) 전라북도 전주시 덕진구 백제대로 567, 전북대학교 공과대학 7호관'
    design:
      columns: 3
      icon_style: circle
      background:
        color: light

  # 2️⃣ 지도 블록 (Tailwind 공식 map 블록)
  - block: map
    id: location
    content:
      title: 위치
      text: 전북대학교 공과대학 7호관 (College of Engineering Building 7)
      map:
        provider: mapnik   # 또는 'google' / 'mapbox' 중 하나
        coordinates:
          latitude: 35.84633
          longitude: 127.12987
        zoom: 17
        height: 500
    design:
      full_width: true
---
