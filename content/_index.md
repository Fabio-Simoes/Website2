---
# Leave the homepage title empty to use the site title
title: Simoes 
date: 2022-10-24
type: landing

sections:
  - block: Hero
    content:
      title: |
      text: |
        <br>
        
        The **Simoes Lab** is a new lab at Brighton and Sussex Medical School focusing on the interactions between cancer cells and their microenvironment.
    design:
      columns: '1'
      background:
        image: 
          filename: Banner.png
          filters:
            brightness: 1
          parallax: False
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: ''

  - block: markdown
    content:
      title: ''
      subtitle: ''
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
  
  - block: collection
    content:
      title: What we do
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
  
  - block: collection
    content:
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'



---
