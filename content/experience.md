---
title: 'Experience'
date: 2025-12-10
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: resume-experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'
      # Education or Experience section first?
      is_education_first: false
      spacing:
        # Order: [Top, Right, Bottom, Left]
        padding: ['5rem', '0', '0', '0']

  # Button to download Resume
  - block: markdown
    content:
      text: '{{< button url="/uploads/Triet_resume.pdf" new_tab="true" icon="arrow-down-tray" style="primary" size="xl" align="center" >}}Download Resume{{< /button >}}'
    design:
      columns: '1'
      css_class: 'text-center'
      spacing:
        # Order: [Top, Right, Bottom, Left]
        padding: ['0', '0', '0', '0']

  - block: resume-skills
    content:
      title: Skills & Hobbies
      username: admin
    design:
      show_skill_percentage: false
      spacing:
        # Order: [Top, Right, Bottom, Left]
        padding: ['5rem', '0', '0', '0']
  - block: resume-awards
    content:
      title: Awards
      username: admin
#   - block: resume-languages
#     content:
#       title: Languages
#       username: admin
---
