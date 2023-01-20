---
# Leave the homepage title empty to use the site title
title:
date: 2023-01-19
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: features
    content:
      title: Languages
      items:
        - name: Ruby
          description: Ruby on Rails, Sinatra
          icon: gem
          icon_pack: far
        - name: PHP
          description: Laravel
          icon: php
          icon_pack: fab
        - name: Javascript
          description: NodeJS, React
          icon: square-js
          icon_pack: fab
  - block: experience
    content:
      title: Professional Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Software Engineer II
          company: BigCommerce
          company_url: ''
          # company_logo: "bigcommerce-logo.png"
          location: Austin, Tx / Remote
          date_start: '2020-03-01'
          date_end: '2022-12-31'
          description: |2-
              * Led a team of 3 engineers through planning and execution of multiple new features to allow “private labeling” for resellers and enabled numerous +$1M partnerships
              * Helped design and implement a new, rescoped v2 API, transitioning from REST to RPC, allowing the company to resell services with any frontend
              * Acted as Product Owner and worked cross-departmentally to ensure project success
              * Built dashboards to identify attacks and implemented middleware to stop or throttle tens of thousands of requests per minute at peak
              * Served as On Call, Deploy Manager, and Production Support on rotation and developed internal, customer-friendly docs which reduced our weekly contacts by well over half
              * Stepped up to own, document, fix, and grow the abandoned Partner APIs after a shift in company vision and priority made them a focus for company performance and success in 2021
              * Worked heavily with product provisioning, which involves over 4 core systems and numerous secondary systems and libraries, spanning Ruby, PHP, Scala, and NodeJS services
        - title: Software Engineer I
          company: BigCommerce
          company_url: ''
          # company_logo: org-x
          location: Austin, Tx
          date_start: '2018-08-01'
          date_end: '2020-03-01'
          description: |2-
              * Setup and configured infrastructure for new services, including containerization, configuration of MySQL, Redis/Resque, RabbitMQ/Protorabbit, CircleCI, and deployment to GCS, AWS, and Heroku
              * Updated core legacy domains to extract billing logic and introduce new flexibility which empowered the pricing decisions that ultimately grew the company through IPO
              * Served as On Call, Deploy Manager, and Production Support on rotation
              * Participated in, and often led, all SCRUM ceremonies for a team of ~15 and was a top contributor to the internal knowledge base
        - title: Technical Support Manager
          company: BigCommerce
          company_url: ''
          # company_logo: "bigcommerce-logo.png"
          location: Austin, Tx
          date_start: '2015-06-01'
          date_end: '2018-08-31'
          description: |2-
              * Led a team of 15-20 front-line technical support agents and a team of 5 technical support leads
              * Built a PHP service to aggregate and present agent performance metrics, causing an immediate and sustained jump in CSAT
        - title: Technical Outsource Trainer
          company: BigCommerce
          company_url: ''
          # company_logo: "bigcommerce-logo.png"
          location: Austin, Tx
          date_start: '2014-08-01'
          date_end: '2015-06-30'
        - title: Technical Support Agent (Phone/Web and Escalations)
          company: BigCommerce
          company_url: ''
          # company_logo: "bigcommerce-logo.png"
          location: Austin, Tx
          date_start: '2013-02-01'
          date_end: '2014-08-31'
    design:
      columns: '2'
  # - block: accomplishments
  #   content:
  #     # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
  #     title: 'Accomplish&shy;ments'
  #     subtitle:
  #     # Date format: https://wowchemy.com/docs/customization/#date-format
  #     date_format: Jan 2006
  #     # Accomplishments.
  #     #   Add/remove as many `item` blocks below as you like.
  #     #   `title`, `organization`, and `date_start` are the required parameters.
  #     #   Leave other parameters empty if not required.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - certificate_url: https://www.coursera.org
  #         date_end: ''
  #         date_start: '2021-01-25'
  #         description: ''
  #         organization: Coursera
  #         organization_url: https://www.coursera.org
  #         title: Neural Networks and Deep Learning
  #         url: ''
  #       - certificate_url: https://www.edx.org
  #         date_end: ''
  #         date_start: '2021-01-01'
  #         description: Formulated informed blockchain models, hypotheses, and use cases.
  #         organization: edX
  #         organization_url: https://www.edx.org
  #         title: Blockchain Fundamentals
  #         url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
  #       - certificate_url: https://www.datacamp.com
  #         date_end: '2020-12-21'
  #         date_start: '2020-07-01'
  #         description: ''
  #         organization: DataCamp
  #         organization_url: https://www.datacamp.com
  #         title: 'Object-Oriented Programming in R'
  #         url: ''
  #   design:
  #     columns: '2'
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
  #     buttons:
  #       - name: All
  #         tag: '*'
  #       - name: Deep Learning
  #         tag: Deep Learning
  #       - name: Other
  #         tag: Demo
  #   design:
  #     # Choose how many columns the section has. Valid values: '1' or '2'.
  #     columns: '1'
  #     view: showcase
  #     # For Showcase view, flip alternate rows?
  #     flip_alt_rows: false
  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="demo" >}}
  #   design:
  #     columns: '1'
  # - block: collection
  #   id: featured
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     columns: '2'
  #     view: card
  # - block: collection
  #   content:
  #     title: Recent Publications
  #     text: |-
  #       {{% callout note %}}
  #       Quickly discover relevant content by [filtering publications](./publication/).
  #       {{% /callout %}}
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: true
  #   design:
  #     columns: '2'
  #     view: citation
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
  # - block: tag_cloud
  #   content:
  #     title: Popular Topics
  #   design:
  #     columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: 
      # Contact (add or remove contact options as necessary)
      # email: johnhebron@gmail.com
      # phone: 888 888 88 88
      # appointment_url: 'https://calendly.com'
      # address:
      #   street: 450 Serra Mall
      #   city: Stanford
      #   region: CA
      #   postcode: '94305'
      #   country: United States
      #   country_code: US
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      # office_hours:
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'
      # contact_links:
      #   - icon: twitter
      #     icon_pack: fab
      #     name: DM Me
      #     link: 'https://twitter.com/Twitter'
      #   - icon: skype
      #     icon_pack: fab
      #     name: Skype Me
      #     link: 'skype:echo123?call'
      #   - icon: video
      #     icon_pack: fas
      #     name: Zoom Me
      #     link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
