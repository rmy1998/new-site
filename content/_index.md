---
# Leave the homepage title empty to use the site title
title: "Mingyuan Rong"
date: 2025-01-07
type: landing

design:
  # Default section spacing
  spacing: "5rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: /files/uploads/resume.pdf
    design:
      css_class: dark
      spacing:
        padding: ["0", "0", "5rem", "0"]
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: publication-columns
    content:
      title: Research
    design:
      spacing:
        padding: ['2.5rem', '0', '3.5rem', '0']
  - block: coauthors
    content:
      title: 'Co-authors'
    design:
      columns: '1'
      spacing:
        padding: ['2.5rem', '0', '2.5rem', '0']
---
