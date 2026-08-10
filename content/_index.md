---
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      username: admin
      text: ''
      button:
        text: Download CV
        url: uploads/cv.pdf
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

  - block: markdown
    content:
      title: 'About my research'
      subtitle: ''
      text: |-
        I am an ecologist looking at patterns of biodiversity and associated ecosystem services at different spatial and temporal scales. As a postdoctoral researcher in the Department of Community Ecology at the [Helmholtz Centre for Environmental Research (UFZ)](https://www.ufz.de/index.php?en=36737), I investigate how pollinators and the services they provide are influenced by landscape and land-use intensity.

        My main research interests focus on landscape ecology, macroecology, agro-ecology, pollination services and biological control. I use different approaches and methods to better understand the effects of landscape on communities and ecosystem services, both in temperate (Europe) and tropical regions (South-East Asia).

        Please reach out to collaborate 😃
    design:
      columns: '1'

  - block: collection
    id: papers
    content:
      title: Recent Publications
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation

  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - events
    design:
      view: card

  - block: collection
    id: news
    content:
      title: Outreach
      subtitle: 'Media interviews, press & blogs'
      text: ''
      filters:
        folders:
          - blog
      count: 10
      order: desc
    design:
      view: card
      spacing:
        padding: [0, 0, 0, 0]

  - block: collection
    id: projects
    content:
      title: Projects
      subtitle: 'Past & current'
      text: ''
      filters:
        folders:
          - project
    design:
      view: showcase
