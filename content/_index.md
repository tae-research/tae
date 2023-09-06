---
# Leave the homepage title empty to use the site title
title:
date: 2023-09-05
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      
  - block: collection
    content:
      title: Publications
      text: ''
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: citation

  - block: collection
    content:
      title: Working Papers
      text: ''
      filters:
        folders:
          - workingpaper
        exclude_featured: false
    design:
      columns: '2'
      view: citation      
      
  - block: experience
    content:
      title: Position
      date_format: 2006
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Assistant Professor of Management
          company: The Hong Kong University of Science and Technology
          company_url: 'https://mgmt.hkust.edu.hk/homepage'
          location: Hong Kong
          date_start: '2023-07-03'
          date_end: ''
          description: ''
    design:
      columns: '2'

---
