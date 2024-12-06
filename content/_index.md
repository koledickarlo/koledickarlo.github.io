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
        - title: Researcher
          company: Faculty of Electrical Engineering and Computing
          company_url: ''
          company_logo: FER
          location: Zagreb, Croatia
          date_start: '2021-03-01'
          date_end: ''
          description: Robotics and Computer Vision Researcher and a PhD candidate at the Laboratory for Autonomous Systems and Mobile Robotics (LAMOR). Research focused on deep learning applications for 3D Computer Vision, Sensor Fusion and SLAM.
        - title: Computer Vision Engineer
          company: Snap Inc.
          company_url: ''
          company_logo: snap
          location: Vienna, Austria
          date_start: '2024-06-01'
          date_end: '2024-09-01'
          description: PhD research internship - computer vision for augmented reality.

        - title: Junior R&D Engineer 
          company: Visage Technologies AB
          company_url: ''
          company_logo: ''
          location: Zagreb, Croatia
          date_start: '2020-08-01'
          date_end: '2021-03-01'
          description: Computer vision for autonomous driving with focus on multiple object tracking. 

        - title: Computer Vision Intern
          company: RealNetworks Inc.
          company_url: ''
          company_logo: ''
          location: Zagreb, Croatia
          date_start: '2018-07-01'
          date_end: '2019-07-01'
          description: Deep learning for face detection, face recognition, face spoofing detection. 



    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
    
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
