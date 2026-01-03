---
title: Blog
type: landing
toc: true

design:
  # Section spacing
  spacing: '2rem'

sections:
  - block: collection
    spacing: '2rem'
    content:
      title: Data science
      filters:
        folders: 
            - blog
        count: 3

    design:
      view: article-grid
      show_read_time: false
      show_date: false
      show_read_more: false
      columns: 1
      
  - block: collection
    content:
      title: Visual
      filters:
        folders: 
            - blog
        count: 3

    design:
      view: citation
      show_read_time: false
      show_date: false
      show_read_more: false
      columns: 1
---
