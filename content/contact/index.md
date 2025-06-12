---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: |-
        __You can find the #AfricanOpenScience community on Slack.__

        __💬 Please join us by clicking on [this invitation link](https://join.slack.com/t/openscienceafrica/shared_invite/zt-2zpbyubgn-lTf3VqWF83sb7qY710Ceew)!__

        ℹ️ For more information on Slack and how to get started, please visit the [Slack Resources pages](https://slack.com/resources/collections/slack-adoption-success-hub#new-user-onboarding).


        _This prototype website was developed by [Anelda van der Walt](mailto:anelda@talarify.co.za) (Talarify).
        We are currently exploring collaborations and seeking funding to add addtional data and enhance the technology of this directory._

        Feel free to leave a message!
    
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
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
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: contact.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
