---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About Me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
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
        - title: Quantitative Geospatial Data Researcher
          company: University of Minnesota
          company_url: ''
          company_logo: org-x
          location: Minneapolis, MN
          date_start: '2021-06-01'
          date_end: ''
          description: |2-
              * Led a data collection process from over 1000 users.
              * Applied data mining and statistical models to study gender mobility discrepancies.
              * Designed a new explainable AI algorithm to model health disparities in mobility.
              * Delivered a recommendation to stakeholder (MnDOT) for policy-making decisions.

        - title: Transportation Data Science Intern
          company: Metropolitan Council
          company_url: ''
          company_logo: org-x
          location: Saint. Paul, MN
          date_start: '2023-05-31'
          date_end: '2023-08-25'
          description: |2-
              * Designed a SQL pipeline to fetch and process real-time traffic data into an interactive web map dashboard.
              * Implemented a Generalized Additive Model (GAM) for traffic volume forecasting.
              * Conducted transit data QAQC and visualization and delivered insights to stakeholders.
        
        - title: Geospatial Data Analyst
          company: University of Minnesota
          company_url: ''
          company_logo: org-x
          location: Minneapolis, MN
          date_start: '2020-06-01'
          date_end: '2021-05-31'
          description: |2-
              * Created an R pipeline for GPS travel data quality control and trend pattern analysis.
              * Automated data quality checking of geo-data, achieving 100%+ efficiency improvement.
 
    design:
      columns: '2'
  - block: collection
    id: news
    content:
      title: News
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - news
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'
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
      buttons:
        - name: All
          tag: '*'
        - name: Mobility
          tag: Mobility
        - name: Machine Learning 
          tag: Machine Learning 
        - name: Data Pipeline
          tag: Data Pipeline
        - name: Research
          tag: Research
        - name: Demographics
          tag: Demographics
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      view: Card
      # For Showcase view, flip alternate rows?
      flip_alt_rows: true
  - block: collection
    id: publication
    content:
      title: Publications
      filters:
        folders:
          - publication
        exclude_featured: true
      text: |-
        {{% callout note %}}
        [Check more Yaxuan's published papers](./publication/).
        {{% /callout %}}
    design:
      columns: '2'
      view: citation
  - block: collection
    id: talks
    content:
      title: Talks
      filters:
        folders:
          - talks
    design:
      columns: '2'
      view: compact
  - block: contact
    id: contact
    content:
      title: Contact
      text: |-
          If you have job opportunities, collaborations, or insights to share, please don't hesitate to connect.
      subtitle:
      # Contact (add or remove contact options as necessary)
      email: zhan6322@umn.edu
      # Choose a map provider in `params.yaml` to show a map from these coordinates
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
