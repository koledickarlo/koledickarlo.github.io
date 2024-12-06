---
# Leave the homepage title empty to use the site title
title: ''
date: 2023-12-19
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: <span style="color:#8e1919">About me</span>
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin

  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many experience `items` below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: CEO
          company: GenCoin
          company_url: ''
          company_logo: org-gc
          location: California
          date_start: '2021-01-01'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Analysing
              * Modelling
              * Deploying
        - title: Professor of Semiconductor Physics
          company: University X
          company_url: ''
          company_logo: org-x
          location: California
          date_start: '2016-01-01'
          date_end: '2020-12-31'
          description: Taught electronic engineering and researched semiconductor physics.
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
    
  - block: collection
    id: featured
    content:
      title: <span style="color:#8e1919">Publications</span>
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
      color: "#8e1919"

  - block: markdown
    id: teaching
    content:
      title: <span style="color:#8e1919">Teaching</span>
      text: "I am currently a teaching assistant for the following courses at the Faculty of Electrical Engineering and Computing:<br>  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- **Estimation Theory**<br>  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- **Machine Learning**<br>  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- **Autonomous Mobile Robots**<br>  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- **3D Vision**<br>  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;- **Robotic Sensing, Perception, and Actuation**;.<br>Additionally, I have mentored students on 6 master theses and 7 bachelor theses."
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: <span style="color:#8e1919">Contact</span>
      subtitle:
      email: kkoledic@gmail.com
      address:
        street: Unska ulica 3
        city: Zagreb
        postcode: '10000'
        country: Croatia
        country_code: HR
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
    design:
      columns: '2'

---
