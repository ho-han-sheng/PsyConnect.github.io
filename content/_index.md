---
# Leave the homepage title empty to use the site title
title:
date: 2022-12-01
type: landing

sections:
  - block: hero
    content:
      title: PsyConnect
      image:
        filename: psyconnect-logo.png
      text: The student Psychology Interest Group of Singapore University of Social Sciences.
  - block: collection
    id: posts
    content:
      title: Recent Events
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - event
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'

---