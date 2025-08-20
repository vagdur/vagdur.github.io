---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: uppsala_graphs_bg2.png
          filters:
            brightness: 0.5
          size: cover
          position: center
          parallax: true
#          text_color_light: true
  - block: markdown
    content:
      title: '📚 My Work'
      subtitle: ''
      text: |-
        I am a mathematician by training, with a primary focus on community detection methods in graphs, from a combinatorial and algorithmic perspective. On September 19th, I will be defending a PhD thesis on this topic! 🤞

        During my PhD, I've done quite a bit of teaching, being the responsible lecturer for two different courses, developing the materials and structure for one of them. I also supervised two bachelor's theses.

        In my spare time from working on my research -- (as surprising as it is that I would have any) -- I have coded up a few hobby projects, mostly about processing or visualising data. Check out the projects section for a selection of that! 😃
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Publications
      filters:
        folders:
          - publication
        featured_only: false
    design:
      view: article-grid
      columns: 2
#  - block: collection
#    content:
#      title: Recent Publications
#      text: ""
#      filters:
#        folders:
#          - publication
#        exclude_featured: false
#    design:
#      view: citation
#  - block: collection
#    id: news
#    content:
#      title: Recent News
#      subtitle: ''
#      text: ''
#      # Page type to display. E.g. post, talk, publication...
#      page_type: post
#      # Choose how many pages you would like to display (0 = all pages)
#      count: 5
#      # Filter on criteria
#      filters:
#        author: ""
#        category: ""
#        tag: ""
#        exclude_featured: false
#        exclude_future: false
#        exclude_past: false
#        publication_type: ""
#      # Choose how many pages you would like to offset by
#      offset: 0
#      # Page order: descending (desc) or ascending (asc) date.
#      order: desc
#    design:
#      # Choose a layout view
#      view: date-title-summary
#      # Reduce spacing
#      spacing:
#        padding: [0, 0, 0, 0]
---
