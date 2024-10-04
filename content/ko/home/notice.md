---
# A section created with the Slider widget.
widget: slider

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 30

content:
  slides:
    - title: 👋 Interests
      content: I am interested in ...
      align: center
      background:
        image:
          filename: image1.jpg
          filters:
            brightness: 0.7
        position: right
        color: '#666'
    - title: AI ☕️
      content: 'Share your knowledge with the group and explore exciting new topics together!'
      align: left
      background:
        image:
          filename: image2.jpg
          filters:
            brightness: 0.7
        position: center
        color: '#555'
    - title: Machine Learning
      content: 'Just opened last month!'
      align: right
      background:
        image:
          filename: image1.jpg
          filters:
            brightness: 0.5
        position: center
        color: '#333'
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Join Us
        url: ../contact/

design:
  slide_height: ''
  is_fullscreen: true
  loop: true
  interval: 2000
---
