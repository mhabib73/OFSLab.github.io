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
          <strong >What we do in our lab?</strong>
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
      columns: '1'
      text_align: left
      no_padding: true
      spacing:
        padding: ["1rem", 0, "1rem", 0]
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
  - block: markdown
    content:
      title: |
          
      text: |
        <style>
        .funding-logos {
          display: flex;
          justify-content: center;
          align-items: center;
          flex-wrap: wrap;
          gap: 50px;
          margin-top: 25px;
        }

        .funding-logos a {
          display: flex;
          align-items: center;
          justify-content: center;
          transition: transform 0.3s ease;
        }

        .funding-logos a:hover {
          transform: translateY(-4px);
        }

        .funding-logos img {
          height: 85px;
          max-width: 220px;
          object-fit: contain;
          filter: grayscale(100%) brightness(1.1);
          opacity: 0.9;
          transition: all 0.3s ease;
        }

        .funding-logos img:hover {
          filter: grayscale(0%);
          opacity: 1;
        }

        @media (max-width: 768px) {
          .funding-logos {
            gap: 25px;
          }

          .funding-logos img {
            height: 60px;
            max-width: 160px;
          }
        }
        </style>

        <div style="text-align: center;">
          <h2 style="
            margin-bottom: 15px;
            font-size: 2rem;
            font-weight: 700;
          ">
            Funding
          </h2>

<div class="funding-logos">

  <img src="NASA_logo.png" alt="NASA" style="height:90px; margin:20px;">

</div>

    design:
      css_class: hbx-bg-gradient
      no_padding: true
      spacing:
        padding: ["0.5rem", 0, "0.5rem", 0]
        margin: [0, 0, 0, 0]


---
