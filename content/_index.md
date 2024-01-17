---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
      # - title: 👋 <large>PETAL Lab <large> 
      #   content: <small>The <b>P</b>ittsburgh <b>E</b>duca<b>T</b>ional <b>A</b>nd <b>L</b>anguage technology lab at the University of Pittsburgh focuses on Speech and Natural Language Technology for Educational Applications. Led by [Prof. Diane Litman](https://people.cs.pitt.edu/~litman/), our NLP research currently focuses on argument mining, multi-party dialogue, revision analysis, and summarization, applied to educational applications such as writing evaluation systems, dialogue tutors, and teacher dashboards. </small>
      #   align: left
      #   background:
      #     # image: upitt.jpg
      #     position: right
      #     color: '#1976d2'
      #     filters:
      #         brightness: 0.7
      #     # iage: 
      - title: 👋 <large>PETAL Lab <large> 
        content: '<small>The <b>P</b>ittsburgh <b>E</b>duca<b>T</b>ional <b>A</b>nd <b>L</b>anguage technology lab <br> at the University of Pittsburgh focuses on Speech and Natural Language Technology for Educational Applications. Led by [Prof. Diane Litman](https://people.cs.pitt.edu/~litman/), our NLP research currently focuses on argument mining, multi-party dialogue, revision analysis, and summarization, applied to educational applications such as writing evaluation systems, dialogue tutors, and teacher dashboards. </small>'
        align: center
        background:
          image:
            filename: pitt_symbol.jpg
            filters:
              brightness: 0.4
          position: bottom
          color: '#555'
      - title: Learn with each other ☕️
        content: 'Share your knowledge with the group and explore exciting new topics together! Feel free to reach out to the group memebers for collaboration'
        align: left
        background:
          image:
            filename: upitt.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      # - title:  Lab
      #   content: 'Just opened last month!'
      #   align: right
      #   background:
      #     image:
      #       filename: welcome.jpg
      #       filters:
      #         brightness: 0.5
      #     position: center
      #     color: '#333'
      #   link:
      #     icon: graduation-cap
      #     icon_pack: fas
      #     text: Contact Us
      #     url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '550px'
      # is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 5000
  # - block: hero
  #   content:
  #     title: 
  #       <large>PETAL Research Lab <large> 
  #     text: 
  #       <small>The <b>P</b>ittsburgh <b>E</b>duca<b>T</b>ional <b>A</b>nd <b>L</b>anguage technology lab at the University of Pittsburgh focuses on Speech and Natural Language Technology for Educational Applications. Led by [Prof. Diane Litman](https://people.cs.pitt.edu/~litman/), our NLP research currently focuses on argument mining, multi-party dialogue, revision analysis, and summarization, applied to educational applications such as writing evaluation systems, dialogue tutors, and teacher dashboards. </small>
    # design:
    #   background:
    #     gradient_end: '#1976d2'
    #     gradient_start: '#004ba0'
    #     text_color_light: false

    #   caption: Another caption  # only shown when zoom out  
  - block: collection
    content:
      title:  Recent News
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
      view: compact # list,
      columns: '2'
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle: ''
  #     text:
  #   design:
  #     columns: '1'
  #     background:
  #       image: 
  #         filename: coders.jpg
  #         filters:
  #           brightness: 1
  #         parallax: false
  #         position: center
  #         size: cover
  #         text_color_light: true
  #     spacing:
  #       padding: ['20px', '0', '20px', '0']
  #     css_class: fullscreen
  
  # - block: markdown
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
  #   design:
  #     columns: '2'

---