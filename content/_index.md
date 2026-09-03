---
title: ''
summary: ''
date: 2022-10-24
type: landing
design: 
  spacing: "3rem"
sections:
  - block: resume-biography-3
    content:
      username: admin
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

  - block: stats
    content:
      title: Cited by
      subtitle: "from Google Scholar"
      items:
        - statistic: "750+"
          description: Citations
        - statistic: "25"
          description: Publications
        - statistic: "14"
          description: h-index
    design:
      layout: cards
      numbers_gradient: true

  - block: markdown
    content:
      title: 'Collaboration Map'
      text: |-
        <div style="text-align:center;">
          External network at the country level
        </div>
  
        <iframe
          src="/collaboration_map.html"
          style="display:block; width:100%; height:55vh; border:none; border-radius:8px;"
        ></iframe>
    design:
      css_class: 'collaboration-map-block'
  
  - block: collection
    content:
      title: Featured Publication
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 1
      fill_image: false
      
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
      default_button_index: 0
      buttons:
        - name: Current
          tag: Current
        - name: Past
          tag: Past
        - name: All
          tag: '*'
      archive:
        enable: false
    design:
      columns: 3

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
      text: Media interviews, press & blogs
      filters:
        folders:
          - blog
    design:
      view: article-grid
      columns: 2

  - block: gallery
    id: gallery
    content:
      title: Gallery
      subtitle: 'Fieldwork & stuff'
      items:
        - src: media/gallery/LEGATO_01.png
          caption: 'Rice terraces of Batad, Ifugao, Philippines (LEGATO 2012)'
        - src: media/gallery/LEGATO_03.jpg
          caption: 'Field crew in Banaue, Ifugao, Philippines (LEGATO 2014)'
        - src: media/gallery/LEGATO_04.jpg
          caption: 'Blow-Vac sampling for rice arthropods (LEGATO 2014)'
        - src: media/gallery/PoshBee_01.jpeg
          caption: 'Oilseed rape fields in Saxony-Anhalt, Germany (PoshBee 2019)'
        - src: media/gallery/PoshBee_03.jpg
          caption: 'Nectar extraction from bumblebees (PoshBee 2019)'
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
        **Office:** Room 3.13, Floor 3
        <iframe src="https://www.openstreetmap.org/export/embed.html?bbox=11.920%2C51.488%2C11.956%2C51.504&layer=mapnik&marker=51.4959%2C11.9379" style="width:100%;height:320px;border:0;border-radius:8px;margin-top:1rem;" loading="lazy"></iframe>
    design:
      columns: '1'
---