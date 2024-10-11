---
title: 'Research'
date: 2024-05-19
type: landing

design:
  # Section spacing
  spacing: '4rem'

# Page sections
sections:
  - block: collection
    content:
      title: Peer-Reviewed Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: collection
    content:
      title: Under Review
      text: ""
      filters:
        folders:
          - underreview
        exclude_featured: false
    design:
      view: citation
  - block: collection
    content:
      title: Working Papers
      text: ""
      filters:
        folders:
          - workingpaper
        exclude_featured: false
    design:
      view: citation 
---