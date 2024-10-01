---
title: Contact
type: landing

sections:
  - block: hero
    content:
      title: "Get in Touch"
      subtitle: "We'd love to hear from you."
      text: "Fill out the form or contact us directly at the details below."
      cta:
        label: "Learn More"
        url: "#contact-form"
        #수정 필요
  
  - block: contact
    id: contact-form
    content:
      title: "Contact"
      email: tjgus8175@jbnu.ac.kr
      phone: "123-456-7890"
      address:
        street: "567 Baekje-daero"
        city: Jeonju-si
        region: Jeollabuk-do
        postcode: "54896"
        country: South Korea
        country_code: KR
      coordinates:
        latitude: '35.8469'
        longitude: '127.1296'

      autolink: true

      form:
        provider: netlify
        netlify:
          captcha: false

    design:
      columns: '2'
---
