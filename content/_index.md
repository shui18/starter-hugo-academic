---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?

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
        - title: Associate Professor
          company: Nanjing Audit University
          company_url: ''
          company_logo: ''
          location: Nanjing
          date_start: '2021-09-01'
          date_end: ''
          description: ''
        - title: Associate Professor
          company: Nanjing University of Finance and Economics
          company_url: ''
          company_logo: ''
          location: Nanjing
          date_start: '2019-06-01'
          date_end: '2021-08-01'
          description: ''
        - title: Lecturer
          company: Nanjing University of Finance and Economics
          company_url: ''
          company_logo: ''
          location: Nanjing
          date_start: '2015-06-01'
          date_end: '2019-05-01'
          description: ''    
    design:
      columns: '2'  
  - block: collection
    id: teaching
    content:
      title: Undergraduate Teaching
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - teaching
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
      view: list
      columns: '2'
  - block: portfolio
    id: publications
    content:
      title: Full list of publications
      filters:
        folders:
          - publication
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
        - name: Journal Papers
          tag: Journal Papers
        - name: Books Chapters
          tag: Books Chapters     
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'      
      view: citation
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  
  
  
  - block: markdown
    id: gallery
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'   
      
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle: ''   
      email: laukai520@163.com   
    design:
      columns: '2'
---
