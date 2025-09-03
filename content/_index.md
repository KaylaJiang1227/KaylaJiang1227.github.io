---
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

        My research focuses on **Environmental Epidemiology, Environmental Systems Analysis, Microbial Ecology, and Global Health**.    
         I am passionate about integrating **quantitative, data-driven approaches** with **experimental research** to better understand environmental systems and to contribute to the development of **sustainable technologies**.
      button:
        text: 📄 Download CV
        url: uploads/resume.pdf
    design:
      avatar:
        size: medium
        shape: circle
      background:
        css_class: "bg-gradient"

  - block: collection
    id: papers
    content:
      title: Papers
      filters:
        folders: ["publication"]
    design:
      view: citation

  - block: collection
    id: experience
    content:
      title: Experience
      filters:
        folders: ["experience"]
    design:
      view: article-grid
      columns: 1

  - block: collection
    id: projects
    content:
      title: Projects
      filters:
        folders: ["project"]
    design:
      view: article-grid
      columns: 2

  - block: markdown
    id: about
    content:
      title: "More About Me"
      text: |-
        Outside of research, I enjoy **design, photography, and organizing community events**.  
        I’m also passionate about **science communication** and building bridges between academia and the public.  
        Feel free to reach out if you'd like to connect!
    design:
      columns: "1"
---
