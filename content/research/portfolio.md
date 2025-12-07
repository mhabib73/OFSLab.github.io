---
# A section created with the Portfolio widget.
# This section displays content from `content/project/`.
# See https://docs.hugoblox.com/widget/portfolio/
type: landing

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


widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 100


title: '<div style="grid-column:1 / -1; text-align:center; font-size:2rem; margin-top:20px; margin-bottom:20px;">Research areas</div>'
subtitle: ''

content:
  # Page type to display. E.g. project.
  page_type: project

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove the toolbar, delete the entire `filter_button` block.
  filter_button:
    - name: All
      tag: '*'
    - name: Modeling
      tag: Modeling
    - name: Characterization and fabrication
      tag: Fabrication
    - name: Sensor
      tag: Sensor
    - name: Ultrafast nonlinear optics
      tag: UNO

design:
  columns: '1'
  background:
    color: ''
  view: masonry
  card:
    image:
      height: 100
  flip_alt_rows: true
  background: {}
  spacing: {padding: [0, 0, 0, 0]}
---
