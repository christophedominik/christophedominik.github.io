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
          
  - block: gallery
    content:
      title: ''
      items:
        - src: media/gallery/LEGATO_01.png
          caption: 'Rice terraces of Batad, Philippines'
        - src: media/gallery/PoshBee_01.jpeg
          caption: 'Oilseed rape fields, Saxony-Anhalt'
        - src: media/gallery/Safeguard_02.jpg
          caption: 'Aporia crataegi, Safeguard 2022'
    design:
      layout: carousel
      aspect_ratio: landscape
      lightbox: true
      caption_position: overlay

  - block: collection
    id: featured
    content:
      title: Featured Publication
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 1
      
  - block: stats
    content:
      title: Research at a glance
      items:
        - statistic: "24"
          description: Publications
          icon: hero/document-text
        - statistic: "~15"
          description: h-index
          icon: hero/chart-bar
        - statistic: "8"
          description: Funded projects
          icon: hero/beaker
        - statistic: "10+"
          description: Years of research
          icon: hero/academic-cap
    design:
      layout: cards
      numbers_gradient: true
      
  - block: collection
    id: Publications
    content:
      title: Recent Publications
      filters:
        folders:
          - publications
      count: 5
      sort_by: Date
      sort_ascending: false
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

  - block: portfolio
    id: posts
    content:
      title: Outreach
      subtitle: 'Media interviews, press & blogs'
      filters:
        folders:
          - blog
    design:
       columns: 2
     
  - block: gallery
    id: gallery
    content:
      title: Gallery
      subtitle: 'Fieldwork & research'
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

  - block: markdown
    id: contact
    content:
      title: 'Contact'
      text: |-
        **Dr. Christophe Dominik**  
        Department of Community Ecology (BZF)  
        Helmholtz Centre for Environmental Research - UFZ  
        Theodor-Lieser-Strasse 4, D-06120 Halle (Saale), Germany  

        **Email:** [christophe.dominik@ufz.de](mailto:christophe.dominik@ufz.de)  
        **Phone:** +49 341 6025 4318  
        **Office:** Room 3.23, Floor 3  

        <iframe src="https://www.openstreetmap.org/export/embed.html?bbox=11.920%2C51.488%2C11.956%2C51.504&layer=mapnik&marker=51.4959%2C11.9379" style="width:100%;height:320px;border:0;border-radius:8px;margin-top:1rem;" loading="lazy"></iframe>
    design:
      columns: '1'
---
