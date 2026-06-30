---
# Leave the homepage title empty to use the site title
title: ''
date: 2025-12-04
type: landing

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ''
      headings:
        about: 'Non-Professional Summary'
        education: ''
        interests: ''
    design:
      avatar:
        size: medium
        shape: circle
      spacing:
        padding: ["0", "0", "0", "0"]
  - block: markdown
    id: highlights
    content:
      title: Highlights
      text: |
        {{< highlightgallery >}}
    design:
      css_class: "bg-gray-100 dark:bg-gray-800"
      spacing:
        padding: ["5rem", "0", "5rem", "0"]
---
