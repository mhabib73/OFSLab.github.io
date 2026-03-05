---
title:
date: 2025-10-12
#type: widget_page  # it will be controlled from the home folder
type: landing # if you want to control _index.md

#spacing: "0.5rem"


sections:

  - block: markdown
    content:
      title: |
        <span style="font-size: 3rem; color: white; white-space: nowrap; text-align: left; display: block;">
        Welcome to Microstructure Optical Fiber Lab </span>
      
      text: |
        <span style="font-size: 2rem; color: white; white-space: nowrap; text-align: left; display: block;">
        advancing science of light for all </span>
        
    design:
      column: "1"
      alignment:
        horizontal: center
        vertical: middle
      background:
        color: ""
        image:
          filename: fiber_3D_final.png
          filters:
            brightness: 1
          position: center
          parallax: true
          size: cover
      css_class: hero-section 
      #spacing:
        #padding: ["0rem", 0, "0em", 0]

  - block: hero
    content:
      title: |
      image:
        filename: HCARF_12tube_trans.gif
      text: |
        <div style="text-align: left; max-width: 1500px; margin: 0 auto;">
          <strong >What we do in our lab:</strong>
          <br>
          <ul style="list-style-type: disc; padding-left: 50px;">
            <li style="font-size: 23px;">Computational photonics</li>
            <li style="font-size: 23px;">Advanced fiber design and characterization</li>
            <li style="font-size: 23px;">Energy-efficient and low-cost fiber sensors</li>
            <li style="font-size: 23px;">Smart fiber-based nonlinear devices</li>
            <li style="font-size: 23px;">Extreme light-matter interactions in fibers</li>

          </ul>
        </div>

    design:
      css_class: "custom-hero-size"
      background:
        color: white
      columns: '1'
      text_align: left
      no_padding: true
      spacing:
        padding: ["1rem", 0, "0rem", 0]
        margin: [0, 0, 0, 0]

  - block: markdown
    content:
      title: |
          
      text: |
        We investigate next-generation optical fiber technologies that redefine how light travels. Our work centers on innovative hollow-core fibers: engineered with microscopic air channels that let light propagate
        faster, over longer distances, and with exceptionally low loss. Through advanced microstructured designs, we aim to achieve ultra-low transmission loss, minimal latency, and broad bandwidth, opening new
        possibilities for the future of high-speed communication, data networks, and beyond.
        <br><br>
        By combining theory, simulation, and experimental fabrication, we aim to understand the underlying physics of light propagation in complex fiber geometries. Our insights drive the development of practical fiber
        designs with transformative applications in AI data centers, quantum communication, ultrafast data transmission, advanced laser systems, fiber-optic sensing, and biomedical imaging.
        <br><br>
        We welcome collaborations with academic groups, industry partners, and students interested in shaping the next generation of photonic technologies.
        <br>
    design:
      css_class: hbx-bg-gradient
      no_padding: true
      spacing:
        padding: ["1rem", 0, "1rem", 0]
        margin: [0, 0, 0, 0]

  - block: portfolio
    content:
      title: '<div style="text-align: left; color: black;">Research</div>'
      text: ""
      filters:
        folders:
          - project
       
    design:
      view: showcase
      columns: '1'
      text_align: left
      no_padding: true
      spacing:
        padding: ["1rem", 0, "1rem", 0]
        margin: [0, 0, 0, 0]

  - block: collection
    content:
      title: '<div style="text-align: left; color: black;">Latest news</div>'
      text: ""
      count: 5
      filters:
        folders:
          - news

        
    design:
      # Section background color (CSS class)
      css_class: "bg-primary-700"
      view: compact
      columns: '1'
      text_align: left
      no_padding: true
      spacing:
        padding: ["1rem", 0, "1rem", 0]
        margin: [0, 0, 0, 0]

  
  - block: collection
    content:
      title: '<div style="text-align: left; color: black;">Featured journal articles</div>'
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'featured-article'
    design:
      view: citation
      columns: '1'
      text_align: left
      no_padding: true
      spacing:
        padding: ["1rem", 0, "1rem", 0]
        margin: [0, 0, 0, 0]
---
