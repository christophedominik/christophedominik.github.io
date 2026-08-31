---
title: ''
summary: ''
date: 2022-10-24
type: landing

sections:
  - block: resume-biography-3
    content:
      username: admin
      button:
        text: Download CV
        url: uploads/cv.pdf
    design:
      background:
        gradient_mesh:
          enable: true
     
  - block: stats
    content:
      title: Research at a glance
      items:
        - statistic: "792"
          description: Citations
        - statistic: "24"
          description: Publications
        - statistic: "~14"
          description: h-index
    design:
      layout: cards
      numbers_gradient: true
      
  - block: collection
    id: publications
    content:
      title: Recent Publications
      filters:
        folders:
          - publications
    design: 
      view: citation

  - block: portfolio
    id: projects
    content:
      title: Projects
      subtitle: 'Past & current'
      filters:
        folders:
          - project
      default\_button\_index: 1
      buttons:
        - name: Current
          tag: Current
        - name: Past
          tag: Past
        - name: All
          tag: '*'
    design:
      view: compact

  - block: collection
    id: talks
    content:
      title: Presentations
      subtitle: 'Selected Presentations'
      filters:
        folders:
          - events
      count: 3
      sort_by: Date
      sort_ascending: false
    design:
      view: date-title-summary

  - block: collection
    id: posts
    content:
      title: Outreach
      subtitle: 'Media interviews, press & blogs'
      filters:
        folders:
          - blog
    design:
      view: article-grid
      columns: 2
      fill_image: false
      show_date: true
      show_read_time: false
      show_read_more: false
      
  - block: gallery
    id: gallery
    content:
      title: Gallery
      subtitle: 'Fieldwork & stuff'
      items:
        - src: media/gallery/LEGATO_01.png
          caption: 'Rice terraces of Batad, Ifugao, Philippines (LEGATO 2012)'
        - src: media/gallery/LEGATO_03.jpg
          caption: 'A Banaue inhabitant, crew helpers and myself (LEGATO 2014)'
        - src: media/gallery/PoshBee_01.jpeg
          caption: 'Oilseed rape fields in Saxony-Anhalt, Germany (PoshBee 2019)'
        - src: media/gallery/PoshBee_03.jpg
          caption: 'Extraction of nectar from bumblebee individuals (PoshBee 2019)'
        - src: media/gallery/PoshBee_02.jpeg
          caption: 'Osmia bicornis saying hello! (PoshBee 2019)'
        - src: media/gallery/PoshBee_05.jpg
          caption: 'Bumblebee colony assessment (PoshBee 2019)'
        - src: media/gallery/Safeguard_02.jpg
          caption: 'Aporia crataegi (Safeguard 2022)'
    design:
      layout: masonry
      columns: 4
      gap: sm
      lightbox: true
      hover_zoom: true
      caption_position: hover
      
  
---
