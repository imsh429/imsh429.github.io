---
title: Interests
type: landing

sections:
  - block: features
    content:
      title: My Interests
      subtitle: I am interested in...
    # text: 
      items:
        - name: AI
          # description: 90%
          icon: brain
          icon_pack: fas
        - name: Machine Learning
          # description: 100%
          icon: robot
          icon_pack: fas
        - name: Computer Vision
          # description: 10%
          icon: eye
          icon_pack: fas
        - name: Development
          # description: 10%
          icon: code
          icon_pack: fas
        - name: Data Science
          # description: 10%
          icon: magnifying-glass-chart
          icon_pack: fas
        - name: Natural Language Processing
          # description: 10%
          icon: language
          icon_pack: fas

  - block: slider
    content:
      slides:
      - title: Future Plans and Goals
        content: My goal is...
        align: center
        background:
          image:
            filename: goal.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: Advanced Learning and Project Development
        content: I plan to study frameworks like PyTorch to strengthen my tech stack and work on related projects.
        align: left
        background:
          image:
            filename: study.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: As an AI researcher and developer
        content: I aim to achieve academic success through research and, based on that, grow as an AI researcher and developer.
        align: right
        background:
          image:
            filename: mygoal.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000
---