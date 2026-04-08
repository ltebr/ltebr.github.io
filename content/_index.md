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
        style: 'text-align: justify; font-size: 0.8em;'
      # Avatar customization
      avatar:
        size: medium  # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: Research Interests
      text: My research focuses on how digital platforms shape social relationships and everyday life. I am particularly interested in the ways platform use intersects with social environments, including family, community, and broader cultural contexts.
    design:
     spacing:
        padding: [0, 0, '3rem', 0]
    style: 'text-align: justify; font-size: 0.8em;'
  - block: collection
    content:
      filters:
        folders:
          - blog
    design:
      spacing:
        padding: ['3rem', 0, '6rem', 0]
---
