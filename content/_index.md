---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Visiting Student of Computer Science
          company: University of California, Berkeley
          company_url: 'https://www.berkeley.edu/'
          company_logo: UCB
          location: Berkeley, CA
          date_start: '2023-08-17'
          date_end: ''
        # - title: Research Assistant
        #   company: LumiAni
        #   company_url: ''
        #   company_logo: lumiani
        #   location: Shanghai, China
        #   date_start: '2022-03-01'
        #   date_end: ''
          # description: |2-
          #     Responsibilities include:

          #     * Analysing
          #     * Modelling
          #     * Deploying
        - title: Bachelor Student of Computer Science and Technology
          company: ShanghaiTech University
          company_url: 'https://www.shanghaitech.edu.cn/'
          company_logo: sht
          location: Shanghai, China
          date_start: '2021-09-01'
          date_end: ''
      
    design:
      columns: '2'
  # - block: collection
  #   id: posts
  #   content:
  #     title: Recent Posts
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - post
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: compact
  #     columns: '2'
  # - block: portfolio
  #   id: projects
  #   content:
  #     title: Projects
  #     filters:
  #       folders:
  #         - project
  #     # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  #     default_button_index: 0
  #     # Filter toolbar (optional).
  #     # Add or remove as many filters (`filter_button` instances) as you like.
  #     # To show all items, set `tag` to "*".
  #     # To filter by a specific tag, set `tag` to an existing tag name.
  #     # To remove the toolbar, delete the entire `filter_button` block.
  #     #buttons:
  #     #  - name: All
  #     #    tag: '*'
  #     #  - name: Animation
  #     #    tag: Animation
  #     #  - name: Other
  #     #    tag: Demo
  #   design:
  #     # Choose how many columns the section has. Valid values: '1' or '2'.
  #     columns: '1'
  #     view: showcase
  #     # For Showcase view, flip alternate rows?
  #     flip_alt_rows: false
  # - block: collection
  #   id: featured
  #   content:
  #     title: Projects
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     columns: '2'
  #     view: card
  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="demo" >}}
  #   design:
  #     columns: '1'


  # - block: tag_cloud
  #   content:
  #     title: Skills
  #   design:
  #     columns: '2'
---
