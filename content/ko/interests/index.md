---
title: My page
type: landing

sections:
  - block: features
    content:
      title: My Interests
      subtitle: Section subtitle
      text: Section text
      items:
        - name: R
          description: 90%
          icon: r-project
          icon_pack: fab
        - name: Statistics
          description: 100%
          icon: chart-line
          icon_pack: fas
        - name: Photography
          description: 10%
          icon: camera-retro
          icon_pack: fas
          
  - block: slider
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
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000
---