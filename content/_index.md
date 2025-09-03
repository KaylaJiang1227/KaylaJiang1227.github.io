---
# Leave the homepage title empty to use the site title
title: ""
date: 2025-09-03
type: landing

design:
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      username: admin
      text: |-
        Hi, I'm **Kayla Jiang**, a Master's student in **Environmental Engineering at Stanford University**.  

        My research focuses on **microbial ecology, antimicrobial resistance (AMR), and environmental health**.  
        I am passionate about exploring how environmental factors shape microbial communities and developing strategies to mitigate AMR spread in water systems.
      button:
        text: 📄 Download CV
        url: uploads/resume.pdf
    design:
      avatar:
        size: medium
        shape: circle
      background:
        color: ""
        image: ""
        css_style: "background: linear-gradient(to bottom, #e6e6fa, #ffffff);"

  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        I work at the intersection of **environmental microbiology** and **public health**, with current projects including:  
        - Hospital wastewater AMR surveillance  
        - DBP–gut microbiome interactions  
        - Air pollution and health modeling  

        I'm always open to collaborations and discussions!
    design:
      columns: '1'

  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      view: article-grid
      columns: 2

  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation

  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1

  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      page_type: post
      count: 5
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      offset: 0
      order: desc
    design:
      view: date-title-summary
      spacing:
        padding: [0, 0, 0, 0]
---

