---
title: Contact
type: landing

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
              alt="Contact banner" loading="eager" decoding="async">
            <!-- 필요하면 오버레이 사용/삭제 -->
            <!-- <div class="absolute inset-0 bg-black/20 md:bg-black/25"></div> -->
          </section>
        </div>
  - block: markdown
    content:
      title: Contact Information
      text: |
        {{< icon name="envelope" pack="fas" >}} **EMAIL**: sh99429@naver.com  
        {{< icon name="phone" pack="fas" >}} **PHONE**: 010-2576-8297  
        {{< icon name="map-location-dot" pack="fas" >}} **ADDRESS**: (54896) College of Engineering, Building 7, Jeonbuk National University, 567 Baekje-daero, Deokjin-gu, Jeonju-si, Jeollabuk-do, Republic of Korea

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
