---
widget: slider  # Use the Slider widget as this page section
weight: 10  # Position of this section on the page
active: true  # Publish this section?
headless: true  # This file represents a page section.

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: '500px'
  is_fullscreen: false
  # Automatically transition through slides?
  loop: true
  # Duration of transition between slides (in ms)
  interval: 5000

content:
  slides:
    - title: ''
      content: "紙飛行機の設計システム"
      align: right
      background:
        color: '#666'
        media: slider_plane.png
        brightness: 0.5  
    - title: ''
      content: "吹奏楽器の設計システム"
      align: right
      background:
        color: '#555'
        media: slider_ocarina.png
        brightness: 0.5
    - title: ''
      content: "服飾パータンの設計システム"
      align: right
      background:
        color: '#333'
        media: slider_clothpattern.png
        brightness: 0.5
    - title: ''
      content: "研究室の様子"
      align: right
      background:
        color: '#333'
        media: slider_lab.png
        brightness: 0.5  
---