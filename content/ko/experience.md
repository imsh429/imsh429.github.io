---
title: 'Experience'
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: resume-experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: true
  - block: resume-languages
    content:
      title: 언어
      username: admin
  - block: resume-skills
    content:
      title: 기술
      username: admin
    design:
      show_skill_percentage: false
  - block: markdown
    id: certifications
    content:
      title: 자격증
      text: |
        - **TOEIC** - 915점
      design:
        columns: "1"
  - block: resume-awards
    content:
      title: 수상내역
      username: admin
  
---
