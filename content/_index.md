---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing
summary: Bo Zhang is a Post-Doctoral Research Associate in the Scientific Computing and Imaging (SCI) Institute at The University of Utah. Bo is on the academic job market for tenure-track positions starting from Fall 2025. Feel free to reach out if your department has open positions.

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

  - block: features
    content:
      title: Skills
      items:
        - name: Coding
          description: "**C/C++**, Python, MPI, CUDA"
          icon: code
          icon_pack: fas
        - name: HPC Platforms
          description: "[Perlmutter@NERSC](https://www.nersc.gov/systems/perlmutter/), [Polaris@ALCF](https://www.alcf.anl.gov/polaris) <br> [Frontera/ Longhorn/ Lonestar6@TACC](https://www.tacc.utexas.edu/systems/frontera/) <br> [Casper/ Cheyenne@NCAR](https://www2.cisl.ucar.edu/computing-data/computing#compute)"
          icon: server
          icon_pack: fas
        - name: Languages
          description: "English, Chinese"
          icon: language
          icon_pack: fas
      # text: ''
      # # Choose a user to display skills from (a folder name within `content/authors/`)
      # username: admin
    # design:
    #   columns: '1'

  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Post-Doctoral Research Associate
          company: "Scientific Computing and Imaging Institute, The University of Utah"
          company_url: 'https://www.sci.utah.edu/'
          company_logo: "SCI-logo"
          location: "Salt Lake City, Utah"
          date_start: '2024-04-16'
          date_end: ''

        - title: Graduate Research Assistant
          company: "Scientific Computing and Imaging Institute, The University of Utah"
          company_url: 'https://www.sci.utah.edu/'
          company_logo: "UU-logo"
          location: "Salt Lake City, Utah"
          date_start: '2022-01-01'
          date_end: '2024-04-15'
          description: "Collaborate with Sandia National Lab, Oak Ridege National Lab and NASA."

        - title: "Intern, Neural Processor Lab Research Scientist"
          company: "Samsung Semiconductor, Inc."
          company_url: 'https://semiconductor.samsung.com/us/'
          company_logo: "Samsung-logo"
          location: "San Jose, California"
          date_start: '2023-05-15'
          date_end: '2023-08-04'

        - title: "Research Engineering/Scientist Professional"
          company: "Texas Advanced Computing Center"
          company_url: 'https://www.tacc.utexas.edu/'
          company_logo: "TACC-logo"
          location: "Austin, Texas"
          date_start: '2022-05-21'
          date_end: '2022-08-15'

        - title: "Summer Internships in Parallel Computational Science"
          company: "National Center for Atmospheric Research"
          company_url: 'https://ncar.ucar.edu/'
          company_logo: "CISL-logo"
          location: "Boulder, Colorado"
          date_start: '2021-05-21'
          date_end: '2021-07-31'

        - title: "Graduate Research Assistant"
          company: "Rutgers Discovery Informatics Institute, Rutgers University"
          company_url: 'https://www.researchwithrutgers.com/en/equipments/rutgers-discovery-informatics-institute'
          company_logo: "Rutgers-logo"
          location: "Piscataway, New Jersey"
          date_start: '2018-08-26'
          date_end: '2021-12-31'
          description: "Collaborate with Sandia National Lab. (Transfer to The University of Utah with my advisor, Dr. Manish Parashar.)"
    design:
      columns: '2'

  # - block: accomplishments
  #   content:
  #     # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
  #     title: 'Accomplish&shy;ments'
  #     subtitle:
  #     # Date format: https://docs.hugoblox.com/customization/#date-format
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
  #         icon: coursera
  #         organization: Coursera
  #         organization_url: https://www.coursera.org
  #         title: Neural Networks and Deep Learning
  #         url: ''
  #       - certificate_url: https://www.edx.org
  #         date_end: ''
  #         date_start: '2021-01-01'
  #         description: Formulated informed blockchain models, hypotheses, and use cases.
  #         icon: edx
  #         organization: edX
  #         organization_url: https://www.edx.org
  #         title: Blockchain Fundamentals
  #         url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
  #       - certificate_url: https://www.datacamp.com
  #         date_end: '2020-12-21'
  #         date_start: '2020-07-01'
  #         description: ''
  #         icon: datacamp
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

  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
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

  - block: collection
    id: publication
    content:
      title: Selected Publications
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation

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
      # subtitle:
      # text: |-
      #   Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: "bozhang AT sci.utah.edu"
      # phone: 888 888 88 88
      # appointment_url: 'https://calendly.com'
      address:
        street: 72 S Central Campus Drive, Room 2646
        city: Salt Lake City
        region: Utah
        postcode: '84112'
        country: United States
        country_code: US
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      # office_hours:
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '40.76761914225047'
        longitude: '-111.84483967593386'  
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
      autolink: false
      # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: false
    design:
      columns: '2'
---
