---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: hero
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: Hugo Academic Theme
      image:
        filename: hero-academic.png
      cta:
        label: '**Get Started**'
        url: https://hugoblox.com/templates/
      cta_alt:
        label: Ask a question
        url: https://discord.gg/z8wNYzb
      cta_note:
        label: >-
          <div style="text-shadow: none;"><a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star Hugo Blox Builder</a></div><div style="text-shadow: none;"><a class="github-button" href="https://github.com/HugoBlox/theme-academic-cv" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star the Academic template</a></div>
      text: |-
        **Generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 500,000+ sites.**

        **Easily build anything with blocks - no-code required!**

        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.

        <!--Custom spacing-->
        <div class="mb-3"></div>
        <!--GitHub Button JS-->
        <script async defer src="https://buttons.github.io/buttons.js"></script>
    design:
      background:
        gradient_end: '#1976d2'
        gradient_start: '#004ba0'
        text_color_light: true
        
  - block: about.biography
    id: about
    content:
      title: About Me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
 
  - block: accomplishments
    id: awards
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'News'
      archive:
        enable: true
        text: See more news
        link: awards/
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006

      items:

        # - date_end: ''
        #   date_start: '2024-'
        #   icon: mdpi
        #   organization: MDPI Big Data and Cognitive Computing
        #   title: New Publication
        #   description: Main author of our paper [Comparing Hierarchical Approaches to Enhance Supervised Emotive Text Classification]() published in MDPI Big Data and Cognitive Computing's special issue Advances in Natural Language Processing and Text Mining.

        - date_end: ''
          date_start: '2024-04-20'
          icon: amwe24
          organization: Autonomy Mobility World Expo
          title: Autonomy Mobility World Expo 2024
          description: Attended the Autonomy Mobility World Expo in Paris, France.

        - date_end: ''
          date_start: '2024-02-28'
          icon: cisse
          organization: The Colloquium on Information Systems Security Education
          title: New Publication
          description: Main author of our paper [Leveraging Gamification and Game-based Learning in Cybersecurity Education - Engaging and Inspiring Non-Cyber Students](https://cisse.info/journal/index.php/cisse/article/view/186/186) published in the Journal of The Colloquium for Information Systems Security Education.

        - date_end: ''
          date_start: '2024-02-27'
          icon: cardiff
          organization: Cardiff University
          title: Funding Awarded
          description: Principle-investigator of a Cardiff University On-campus Summer Internship - Decoding Hate; Analysing Features that Amplify Online Hate Speech. Worth £3,000.          
       
      text: "[See all](/awards/)"       
    design:
      columns: '2'
      
  - block: collection
    id: publications
    content:
      title: Recent Publications
      archive:
        enable: true
        text: See all publications
        link: publication/
      filters:
        folders:
          - recent_publication
    design:
      columns: '2'
      view: card
    
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     columns: '2'
  #     view: compact
  
  - block: contact
    id: contact
    content:
      title: Contact
      email: WilliamsL10@cardiff.ac.uk
      address:
        street: School of Computer Science and Informatics, Cardiff University, Abacws, Senghennydd Road, Cardiff, CF24 4AG      
    design:
      columns: '2'
---
