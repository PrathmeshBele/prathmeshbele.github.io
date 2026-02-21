---
title: ''
summary: ''
date: 2022-10-24
type: landing

design:
  spacing: '6rem'

sections:
# --- ADDED: Under Construction Banner ---
  - block: markdown
    content:
      text: |-
        > [!WARNING]
        > **Work in Progress:** This website is currently under construction. Pardon the dust while I update my portfolio!
    design:
      columns: '1'
      spacing:
        padding: ['3rem', '0', '0', '0']
  # ----------------------------------------
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle
  
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
  
  - block: collection
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
---
