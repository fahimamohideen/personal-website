---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "2.5rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
    design:
      css_class: light
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['20px', '20px', '20px', '20px']

  - block: collection
    id: papers
    content:
      title: Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
      columns: 2
      spacing:
        # Customize the section spacing. Order is top, right, bottom, left.
        padding: ['50px', '20px', '0px', '20px']
      
---
