---
title: 'Home'
date: 2026-04-07
type: landing
sections:
  - block: resume-biography
    content:
      # Author slug (data/authors/<slug>.yaml)
      username: me
    design:
      spacing:
        padding: ['6rem', 0, '12rem', 0]
      biography:
        style: 'text-align: center; font-size: 0.8em'
      # Avatar customization
      avatar:
        size: medium  # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: Research Interests
      text: 
        My research broadly focuses on media platforms and their role in shaping communication and social interaction, with a particular interest in media dependency in everyday life. Within this, I am especially interested in fandom activities on social media and in hyper-local communities, examining how people engage, interact, and build relationships across digital and immediate social contexts.

    design:
      spacing:
        padding: [0, 0, '3rem', 0]
      css_style: "text-align: center; font-size: 1.5em !important;"
  - block: collection
    content:
      filters:
        folders:
          - blog
    design:
      spacing:
        padding: ['3rem', 0, '6rem', 0]
---
