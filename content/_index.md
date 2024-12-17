---
# Leave the homepage title empty to use the site title
title:
date: 2024-09-26
type: landing

sections:
  - block: hero
    content:
      title: |
        IDRA Research Group
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The **Interdepartmental Robotics Labs** (IDRA) is a strategic initiative of the University of Trento to combine expertise in different areas within the robotics research. It involves the Department of Industrial Engineering (DII) and the Department of Information Engineering and Computer Science (DISI).

        The [Department of Industrial Engineering (DII)](www.dii.unitn.it) performs research, training, and teaching  in the sectors of Industrial Engineering, in particular in mechanics, mechatronics, materials engineering, electronic-and micro-electronics systems, mananagerial information systems, and optimization methods and models to support decision making. 

        The [Department of Information Engineering and Computer Science (DISI)](www.disi.unitn.it) is a leading institution in research and development in the area of Information and Communication Technology (ICT), and in particular in the field of software engineering, signal processing, networks and sensing, machine learning, quantum computing, and human-computer interaction.

        Take a look to the latest videos of our research in our [YouTube page](https://www.youtube.com/@idra-unitninterdep.institu8477)!
  
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
  
  - block: collection
    content:
      title: Latest Events
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
      page_type: event
    design:
      view: card
      columns: '1'

  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.png
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         # size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen

  - block: collection
    content:
      title: Latest Articles
      text: ""
      count: 5
      filters:
        folders:
          - publication
        # publication_type: 'article-journal'
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
