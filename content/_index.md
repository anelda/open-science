---
# Leave the homepage title empty to use the site title
title:
date: 2025-01-22
type: landing

sections:
  - block: hero
    content:
      title: |
        Welcome to 
        Open Science in Africa
        
      image:
        filename: frontpage.webp
      text: |
        <br>
        
        This site provides a collection of open science resources collated by the community for the community. If you would like to list your open science initiative, resource, or opportunity, please get in touch!

  - block: markdown
    content:
      title: "Please note: This website has been designed as a PROTOTYPE."
      subtitle: 'The site does not provide a comprehensive overview of the Open Science landscape in Africa. Information about initiatives and organisations have been collected from the Internet and should be checked with the individual organisations or initiatives.'
      text: ''
    design:
      columns: '1'
      background:
        colour: 

  - block: portfolio
    id: initiatives
    content:
      title: The African Open Science Ecosystem
      subtitle: Looking for a project, community, policymaker, funder, or collaborator? 
      text: 
      filters:
          # Folders to display content from
        folders:
          - project
        # Only show content with these tags
        tags: []
        # Exclude content with these tags
        exclude_tags: []
        # Which Hugo page kinds to show (https://gohugo.io/templates/section-templates/#page-kinds)
        kinds:
          - page
       # Field to sort by, such as Date or Title
      sort_by: 'Title'
      sort_ascending: true
        # Default portfolio filter button
        # 0 corresponds to the first button below and so on
        # For example, 0 will default to showing all content as the first button below shows content with *any* tag
      default_button_index: 0
        # Filter button toolbar (optional).
        # Add or remove as many buttons as you like.
        # To show all content, set `tag` to "*".
        # To filter by a specific tag, set `tag` to an existing tag name.
        # To remove the button toolbar, delete the entire `buttons` block.
      buttons:
        - name: All
          tag: '*'
        - name: Policy
          tag: 'Policy'
        - name: Community
          tag: 'Community'
        - name: Events organiser
          tag: 'Events'
        - name: Research
          tag: 'Research'
        - name: Funding
          tag: 'Funding'
        - name: Training
          tag: Training
        - name: Infrastructure
          tag: Infrastructure
    design:
        # See Page Builder docs for all section customization options.
        # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
        # Choose a listing view
      view: compact
        # For Showcase view, flip alternate rows?
  
  - block: collection
    content:
      title: Latest Publications
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

---


  # - block: collection
  #   content:
  #     title: Latest News
  #     subtitle:
  #     text:
  #     count: 5
  #     filters:
  #       author: ''
  #       category: ''
  #       exclude_featured: false
  #       publication_type: ''
  #       tag: ''
  #     offset: 0
  #     order: desc
  #     page_type: post
  #   design:
  #     view: card
  #     columns: '1'
  
