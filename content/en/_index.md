---
# Leave the homepage title empty to use the site title
title:
date: 2024-03-25
type: landing

sections: 
  - block: features
    content:
      title: <span style="font-size:70%">Welcome to Shin Seohyun's website.</span>
      text: <br><span style="font-size:125%">I am currently studying in the Department of Computer and Artificial Intelligence at Chonbuk National University, with a strong interest in the field of Artificial Intelligence (AI), particularly in machine learning and computer vision. I aspire to become a developer who continues to conduct in-depth research in the AI field and achieve significant accomplishments.</span> <br><br>
        {{% cta cta_link="./about/" cta_text="About me →" %}}


  - block: slider
    content:
      slides:
      - title: <span style="font-size:70%">AI</span>
        content: <span style="font-size:60%">A technology that mimics human intelligence to automatically perform tasks such as problem-solving, learning, and pattern recognition</span>
        align: center
        background:
          image:
            filename: image1_ai.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'

      - title: <span style="font-size:70%">Computer Vision</span>
        content: <span style="font-size:60%">An AI technology field that analyzes and understands images to process visual data, such as object recognition, scene interpretation, and motion tracking</span>
        align: left
        background:
          image:
            filename: image2_cv.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'

      - title: <span style="font-size:70%">Machine Learning</span>
        content: <span style="font-size:70%">AI technology that trains computers to learn patterns from data and make predictions</span>
        align: right
        background:
          image:
            filename: image3_ml.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'

      - title: <span style="font-size:70%">Development</span>
        content: <span style="font-size:70%">The process of technically implementing creative ideas, and designing, building, and maintaining software and systems</span>
        align: center
        background:
          image:
            filename: development.jpg
            filters:
              brightness: 0.5
          position: left
          color: '#333'

      - title: <span style="font-size:70%">Contact</span>
        content: <span style="font-size:70%">How to contact me...</span>
        align: center
        background:
          image:
            filename: contact.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
            icon: graduation-cap
            icon_pack: fas
            text: contact me
            url: ../contact/

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '400px'
      slide_width: '100px'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000

  - block: portfolio
    content:
      title: Projects
      filters:
        folders:
          - project
      default_button_index: 0
      buttons:
        - name: ALL
          tag: '*'
          type: project
        - name: Modified Cookie Run Game
          tag: CR
        - name: Creating a Website
          tag: HMP
        - name: Restaurant Discovery Service
          tag: MJ  
    design:
      columns: '1'
      view: custom_card
      flip_alt_rows: false
      spacing: { padding: [30, 0, 30, 0] }

  - block: collection
    content:
      title: notice
      subtitle:
      text:
      count: 3
      filters:
        folders:
          - notice
          - gallery
      offset: 0
      order: desc
      #page_type: publication
    design:
      view: community/custom_compact
      columns: '2'
    advanced:
      css_style: "text-align: center;"

  - block: collection
    content:
      title: Upcoming Events
      subtitle:
      text:
      count: 3
      filters:
        folders:
          - events
      offset: 0
      order: desc
      page_type: events
    design:
      view: masonry
      columns: '2'
    advanced:
      css_style: "text-align: center;"
---