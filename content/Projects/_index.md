---
# Leave the homepage title empty to use the site title
title: Fabio Simoes
date: 2022-10-24
type: landing

sections:
  - block: Hero
    content:
      title: |
        Simoes Lab

      image:
        filename: Meet the team.jpg
      text: |
        <br>
        
        The **Simoes Research Group** is a new lab at BSMS focussing on the interactions between cancer cells and their microenvironemnt. 

  - block: markdown
    content:
      title: ''
      subtitle: ''
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
    background:
        filename: Meet the team.jpg
        filters:
          brightness: 1
        parallax: true
        position: center
        size: cover
        text_color_light: true
  
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
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

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
