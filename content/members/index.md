---
title: People
date: 2022-10-24

type: landing

sections:
  - block: hero
    content:
      title: ""
      subtitle: ""
      image:
        filename: "placeholder.png"
        focal_point: "center"
    design:
      background:
        color: "transparent"  # Makes the background behind the image transparent
        image:
          filename: "people.svg"
          size: cover  # Ensures full width
          position: center
          parallax: false
  - block: people
    content:
      title: ''
      user_groups:
          - Principal Investigator
          - Research Scientists
          - Research Trainees and Staff
          - Administration
          - Collaborators
          - Alumni
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true
---
