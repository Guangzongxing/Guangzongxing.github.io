---
title: ''
date: 2024-09-24
type: landing

sections:
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
          featured_only: true
    design:
      columns: '2'
      view: compact
  - block: collection
    content:
      title: Recent Publications
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation

header:
  caption: ''
  image: ''
  ---
        