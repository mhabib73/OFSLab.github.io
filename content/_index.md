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
        Welcome to the Optical Fiber Science Lab </span>
      
      text: |

        
    design:
      column: "1"
      alignment:
        horizontal: center
        vertical: middle
      background:
        color: ""
        image:
          filename: fiber_3D_final_v2.png
          filters:
            brightness: 1
          position: center
          parallax: true
          size: cover
      css_class: hero-section
      #css_class: fullscreen
      #spacing:
        #padding: ["0rem", 0, "0em", 0]

  - block: hero
    content:
      title: |
      image:
        filename: modes.gif
      text: |
        <div style="text-align: font-size: 20px; left; max-width: 1500px; margin: 0 auto;">
          <strong >What we do in OFS lab?</strong>
          <br>
          <ul style="list-style-type: disc; padding-left: 50px;">
            <li style="font-size: 22px;">Computational fiber photonics</li>
            <li style="font-size: 22px;">Advanced fiber design and characterization</li>
            <li style="font-size: 22px;">Energy-efficient and low-cost fiber sensors</li>
            <li style="font-size: 22px;">Smart fiber-based nonlinear devices</li>
            <li style="font-size: 22px;">Extreme light-matter interactions in fibers</li>

          </ul>
        </div>

    design:
      css_class: "custom-hero-size"
      background:
        color: ""
      columns: '2'
      text_align: left
      no_padding: true
      spacing:
        padding: ["1rem", 0, "1rem", 0]
        margin: [0, 0, 0, 0]

  - block: hero
    content:
      title: |
      image:
        filename: HCARF_detection.gif
      text: |
        <div style="text-align: font-size: 20px; left; max-width: 1500px; margin: 0 auto;">
          <strong >Physics-based AI modeling</strong>
          <br>
          <ul style="list-style-type: disc; padding-left: 50px;">
            <li style="font-size: 22px;">Physics-informed AI for light propagation</li>
            <li style="font-size: 22px;">Physics-guided machine learning</li>
            <li style="font-size: 22px;">AI-driven fiber geometry optimization</li>
            <li style="font-size: 22px;">Simulation and experimental validation</li>
            <li style="font-size: 22px;">Inverse design of hollow-core fibers</li>

          </ul>
        </div>

    design:
      css_class: "custom-hero-size"
      background:
        color: ""
      columns: '2'
      text_align: right
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
      columns: '2'
      text_align: left
      no_padding: true
      spacing:
        padding: ["1rem", 0, "1rem", 0]
        margin: [0, 0, 0, 0]


---
