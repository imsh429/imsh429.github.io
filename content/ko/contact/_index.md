---
# 홈페이지의 한 섹션으로 Contact 위젯을 활성화합니다.
widget: contact
headless: true
active: true
# 홈페이지에서 보여질 순서 (숫자가 낮을수록 위)
weight: 100

title: Contact
subtitle:

content:
  # 연락처 정보
  email: tjgus8175@jbnu.ac.kr
  phone: 010-2576-8297
  address:
    street: "567 백제대로"
    city: "Jeonju-si"
    region: "전라북도"
    postcode: "54896"
    country: "South Korea"
    country_code: "KR"
  
  # 위도/경도 좌표. 주소만으로 위치가 정확하지 않을 때 사용합니다.
  coordinates:
    latitude: '35.8469'
    longitude: '127.1296'

  # 이메일, 전화번호 등에 자동으로 링크를 겁니다.
  autolink: true

  # 문의 양식 (필요 없다면 form 섹션 전체를 지워도 됩니다)
  form:
    provider: netlify
    netlify:
      captcha: false
---