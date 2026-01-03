---
title: Blog
type: landing

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
      show_read_time: true
      show_date: true
      show_read_more: true
      columns: 1
---



{{< cards >}}
  {{< card url="category-test" title="Get Started" icon="document-text" subtitle="Setup your new site in just 5 minutes!" >}}
{{< /cards >}}
