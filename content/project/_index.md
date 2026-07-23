---
title: "Research"
date: 2025-11-11
type: landing
widget: portfolio

design:
  spacing: "5rem"

sections:

  - block: markdown
    content:
      #title: '<div style="grid-column: 1 / -1; text-align:left; font-size:1rem;">MOFLab projects</div>'
      text: |
        <p style="color:white; font-size:1.6rem;">OFSLab explores state-of-the-art optical fiber design and fabrication, smart, low-cost and energy-efficient fiber sensors, and ultrafast nonlinear fiber dynamics.</p> 
    design:
      no_padding: true
      spacing:
        padding: ["1rem", 0, "1rem", 0]
        margin: [0, 0, 0, 0]
      column: "1"
      background:
        color: "#0A3452"
        #image:
          #filename: project.svg
          #filters:
            #brightness: 1
          #position: center
          #parallax: false
          #size: 55%
          #padding: ['420px', '0', '20px', '0']
        
      #spacing:
        #padding: ['20px', '0', '20px', '0']
        

  - block: collection
    content:
      #title: '<div style="grid-column: 1 / -1; text-align:left; font-size:2rem;">MOFLab projects</div>'
      text: |
      filters:
        folders:
          - project
    filter_button:
      - name: All
        tag: '*'
      - name: Advanced Fiber Modeling
        tag: Modeling
      - name: Advanced Fiber Fabrication
        tag: Fabrication
      - name: Smart Sensors
        tag: Sensor
      - name: Ultrafast Optics
        tag: UNO
    design:
      no_padding: true
      spacing:
        padding: ["2rem", 0, "2rem", 0]
        margin: [0, 0, 0, 0]
      view: showcase
      columns: 2
      background: 
        color: "white"
      show_date: false
      show_read_time: false
      show_read_more: false
  
    sort_by: 'Date'
    sort_ascending: false
    cascade:
      show_breadcrumb: true
      show_related: true
      commentable: true

---
