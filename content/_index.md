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
        - title: Software Engineer II, Billing Platform Team
          company: BigCommerce
          company_url: ''
          company_logo: bigcommerce
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
        - title: Software Engineer I, Billing Platform Team
          company: BigCommerce
          company_url: ''
          company_logo: bigcommerce
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
          company_logo: bigcommerce
          location: Austin, Tx
          date_start: '2015-06-01'
          date_end: '2018-08-31'
          description: |2-
              * Led a team of 15-20 front-line technical support agents and a team of 5 technical support leads
              * Built a PHP service to aggregate and present agent performance metrics, causing an immediate and sustained jump in CSAT
        - title: Technical Outsource Trainer
          company: BigCommerce
          company_url: ''
          company_logo: bigcommerce
          location: Austin, Tx
          date_start: '2014-08-01'
          date_end: '2015-06-30'
        - title: Technical Support Agent (Phone/Web and Escalations)
          company: BigCommerce
          company_url: ''
          company_logo: bigcommerce
          location: Austin, Tx
          date_start: '2013-02-01'
          date_end: '2014-08-31'
    design:
      columns: '2'
  - block: accomplishments
    id: dei
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'DEI & Volunteer Work'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - date_end: '2021-12-31'
          date_start: '2018-07-01'
          description: "BProud, BigCommerce's LGBTQ+ and Allies employee resource group, represents the aspirations and spirit of many more LGBTQ+ BigCommerce employees than I could possibly count. 
          <br><br>
          Being a Co-Founder and Co-Chair of BProud started long before we wrote and signed our official formation papers in 2018. From the day I started at BigCommerce, I felt a passion to build a community amongst our LGBTQ+ employees (of whom there seemed to be very few at first). Over the years, we tried to form a group numerous times but found that it was a lot more work than we anticipated and there were a lot fewer people willing to take on extra work. 
          <br><br>
          It wasn't until 2018 that a fellow LGBTQ employee came to me with a design for what he thought would be an amazing t-shirt for the group we wanted to form. Turns out, it was, and we were able to secure funding from the Support and Engineering organizations to have shirts printed for anyone who wanted one. Once we opened the lid and finally put ourselves out there we were overwhelmed with the number of people interested in getting a shirt and the level of support we started to receive. 
          <br><br>
          After this amazing discovery, that so many people were out there who also wanted to support us, we finally had the steam to form and build our ERG! Over the years, BProud has provided social, educational, and inspirational events, talks, and more to BigCommerce employees about LGBTQ+ topics."
          organization: BProud @ BigCommerce
          organization_url: https://careers.bigcommerce.com/inside-bigcommerce/diversity-equity-inclusion/
          title: LGBTQ+ ERG Founder and Lead
          url: ''
        - certificate_url: 
          date_end: '2022-08-01'
          date_start: '2022-03-01'
          description: "BigCommerce served as a host/sponsor for 5 awesome applicants in both the H1 2022 TechWomen and the H2 2022 TechWomen conferences.
          <br><br>
          As part of their week at BigCommerce learning about all things from ecommerce to being a leader in tech, I was invited to speak about BigCommerce and BigCommerce Engineering (as I was a 9 year veteran at this point) as well as my background as an entrepreneur and creator.
          <br><br>
          Speaking to the TechWomen teams is one of the most amazing opportunities I have ever had and I am always so humbled and overwhelmed by the amazing work that these women do. I am honored that my company chooses to support them!"
          organization: TechWomen
          organization_url: https://www.techwomen.org/
          title: Guest Speaker
          url: 
        - certificate_url: 
          date_end: '2019-12-31'
          date_start: '2014-10-01'
          description: "Every holiday season from 2014 to 2019 (6 years!) I volunteered as lead of the BigCommerce Holiday Wishes Toy Drive in support of Partnerships for Children (PfC). 
          <br><br>
          Within BigCommerce, I would market the toy drive, facilitate communication between BigCommerce and PfC, and solicit and collect monetary donations. This would all culminate in our yearly shopping trip and toy drop off where employees would 'take over' local stores purchasing thousands of dollars of toys for donations and then would bring in those toys (along with the toys that colleagues had purchased separately) to load up our U-Haul and deliver to the *amazing* PfC warehouse! 
          <br><br>
          Each year we would 'sponsor' between 100-500 children with our largest year garnering over $10,000 in donations!"
          organization: Partnerships for Children
          organization_url: https://www.datacamp.com
          title: 'Toy Drive Organizer and Fundraiser'
          url: ''
        - certificate_url: 
          date_end: '2018-06-30'
          date_start: '2017-06-01'
          description: "In support of the 2017 and 2018 *Hackout*, Austin's first and only LGBTQIA+ entrepreneurship weekend, I secured corporate sponsorship from BigCommerce to support the event, encouraged participation resulting in multiple BigCommerce employee teams, and was lucky enough to participate in the weekend events as a member of my own team.
          <br><br>
          As an overlap between LGBTQIA+ and entrepreneurship, Hackout holds a special place in my heart. If you look closely, you can still see a number of past BigCommerce employees featured on the Hackout website and videos!"
          organization: Startout
          organization_url: https://swhackout.org
          title: 'Corporate Sponsorship/Participant'
          url: ''
        - certificate_url: 
          date_end: '2019-02-01'
          date_start: '2019-02-28'
          description: "I was invited to act as a mentor for the visiting students from the Anne Richards School for Future Women Leaders during their week long internship at BigCommerce.
          <br><br>
          During their time, the high schoolers worked with numerous BigCommerce employees to ideate, plan, and execute on an ecommerce business idea. The goal was to provide them with a super condensed look into the world of being an entrepreneur and working in ecommerce or tech.
          <br><br>
          I was lucky enough to be able to spend the week assisting the team with ecommerce/business guidance from my time running multiple online businesses, as well as design and coding advice for their project website.
          <br><br>
          To find out more about their visit, check out this blog post: https://www.bigeng.io/opening-the-door-for-future-women-leaders/"
          organization: Ann Richards School for Young Women Leaders
          organization_url: https://www.annrichardsschool.org/
          title: 'Mentor'
          url: ''
        - certificate_url: 
          date_end: '2019-03-31'
          date_start: '2015-02-01'
          description: "In support of the annual Texas Humane Heroes (THH) Chili Cookoff fundraiser, I would promote and organize participation and sponsorship of the fundraiser from BigCommerce.
          <br><br>
          Each Q1 from 2015-2019 (5 years!) I would support the THH Chili Cookoff by forming multiple BigCommerce sponsored cooking teams, securing BigCommerce sponsored participant tickets for employees, and negotiating financial sponsorship opportunities to allow BigCommerce to financially support the work of THH.
          <br><br>
          I'm proud to say that we adopted both of our beautiful pups from the amazing THH family, as well!"
          organization: Texas Humane Heroes
          organization_url: https://www.annrichardsschool.org/
          title: 'Corporate Sponsorship/Chili Cookoff Participant'
          url: ''
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
  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="demo" >}}
  #   design:
  #     columns: '1'
  - block: collection
    id: articles
    content:
      title: Articles
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: portfolio
    id: projects
    content:
      title: eCommerce Businesses
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      # default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      # buttons:
      #   - name: All
      #     tag: '*'
      #   - name: Deep Learning
      #     tag: Deep Learning
      #   - name: Other
      #     tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
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
