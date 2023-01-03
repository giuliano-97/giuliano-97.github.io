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
  - block: portfolio
    id: projects
    content:
      title: Projects
      folders:
        - project
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: experience
    id: experience
    content:
      title: Experience
      date_format: Jan 2019
      items:
        - title: Computer Vision Engineer (Part-time)
          company: Scandit
          company_url: https://scandit.com
          date_start: '2021-10-01'
          date_end: '2022-04-30'
          description: |
            Software engineer in the Matrix Scan team of the Computer Vision Chapter working on AR.
              * Object detection
              * Multi-object tracking
              * AR
        - title: Computer Vision Intern
          company: Scandit
          company_url: https://scandit.com
          date_start: '2021-03-01'
          date_end: '2021-08-30'
          description: |
            Computer Vision Intern in the Matrix Scan team of the Computer Vision Chapter working:
              * Object detection
              * Multi-object tracking
              * AR
        - title: R&D Intern
          company: ABB Research
          company_url: https://abb.com
          date_start: '2020-10-15'
          date_end: '2021-02-28'
          description:
            R&D software engineering intern working on containerized deployment of hard-real time applications.


---
