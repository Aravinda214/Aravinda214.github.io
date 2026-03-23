---
title: 'Projects'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
  - block: collection
    content:
      title: Featured Projects
      text: Selected software, AI/ML, analytics, and distributed-systems work focused on real-world problem solving, strong technical execution, and product-minded system design.
      filters:
        folders:
          - project
        featured_only: true
    design:
      view: article-grid
      fill_image: false
      columns: 3
  - block: collection
    content:
      title: Project Archive
      text: Additional projects across forecasting, sports analytics, public-health analysis, blockchain applications, and large-scale exploratory data analysis.
      filters:
        folders:
          - project
        exclude_featured: true
    design:
      view: article-grid
      fill_image: false
      columns: 3
---
