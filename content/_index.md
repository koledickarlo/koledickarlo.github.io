---
# Leave the homepage title empty to use the site title
title: ''
date: 2023-12-19
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: <span style="color:blue">some *blue* text</span>.
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: featured
    content:
      title: Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
      color: "#8e1919"

  - block: contact
    id: contact
    content:
      title: Contact
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
