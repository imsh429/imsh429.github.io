---
title: Contact
type: landing

sections:
  - block: github.imsh429.banner_contact
    content:
      image: "/media/banner2.jpg"
      alt: "Projects banner"
      overlay_opacity: "0.2"
    design:
      height:
        base: "14vh"
        md: "18vh"
      spacing:
        padding: [0,0,0,0]
        margin: [0,0,0,0]

  - block: markdown
    content:
      title: 연락처
      text: |
        {{< icon name="envelope" pack="fas" >}} **이메일**: sh99429@naver.com  
        {{< icon name="phone" pack="fas" >}} **전화**: 010-2576-8297  
        {{< icon name="map-location-dot" pack="fas" >}} **주소**: (54896) 전라북도 전주시 덕진구 백제대로 567, 전북대학교 공과대학 7호관 

    design:
      columns: 1

  - block: markdown
    content:
      title: 위치
      text: |
        <iframe
          src="https://www.google.com/maps?q=전라북도+전주시+덕진구+백제대로+567+전북대학교+공과대학+7호관&z=17&output=embed"
          width="100%"
          height="400"
          style="border:0"
          loading="lazy"
          referrerpolicy="no-referrer-when-downgrade">
        </iframe>
    design:
      columns: 1
      full_width: true
---
