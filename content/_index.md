---
# Leave the homepage title empty to use the site title
title:
date: 2025-05-14
type: landing

sections:
  - block: hero
    content:
      title: |
        Turku Hypertension Center
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The **Turku Hypertension Center** is a team of scientists at the University of Turku performing multi-disciplinary research ranging from classical epidemiology to multi-omics analysis. In addition to general cardiovascular epidemiology, our research focuses on the epidemiology of hypertension in large scale population cohorts.
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
#  - block: markdown
#    content:
#      title: Projects
#      subtitle: ''
#      text:
#    design:
#      columns: '1'
#      background:
#        image: 
#          filename: coders.jpg
#          filters:
#            brightness: 1
#          parallax: false
#          position: center
#          size: cover
#          text_color_light: true
#      spacing:
#        padding: ['20px', '0', '20px', '0']
#      css_class: fullscreen

  - block: collection
    content:
      title: Selected Publications
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article-journal'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
