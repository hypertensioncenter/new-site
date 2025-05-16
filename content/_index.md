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
#      image:
#        filename: welcome.jpg
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
      spacing:
        padding: ['20px', '0', '20px', '0']
  
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
      spacing:
        padding: ['20px', '0', '20px', '0']

sections:
  - block: portfolio
    id: projects
    content:
      title: Projects
      subtitle: []
      text: Current projects we are working on.
      filters:
        # Folders to display content from
        folders:
          - project
        # Only show content with these tags
        tags: []
        # Exclude content with these tags
        exclude_tags: []
        # Which Hugo page kinds to show (https://gohugo.io/templates/section-templates/#page-kinds)
        kinds:
          - page
      # Field to sort by, such as Date or Title
      sort_by: 'Date'
      sort_ascending: false
      # Default portfolio filter button
      # 0 corresponds to the first button below and so on
      # For example, 0 will default to showing all content as the first button below shows content with *any* tag
      default_button_index: 0
      # Filter button toolbar (optional).
      # Add or remove as many buttons as you like.
      # To show all content, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the button toolbar, delete the entire `buttons` block.
      #buttons:
      #  - name: All
      #    tag: '*'
      #  - name: Deep Learning
      #    tag: Deep Learning
      #  - name: Other
      #    tag: Demo
    design:
      # See Page Builder docs for all section customization options.
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      # Choose a listing view
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
      spacing:
        padding: ['20px', '0', '20px', '0']

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
      spacing:
        padding: ['20px', '0', '20px', '0']
---
