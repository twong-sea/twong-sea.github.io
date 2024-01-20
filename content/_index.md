---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "4rem"

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: biography
    content:
      username: admin
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download Resume
        url: uploads/trevor_wong_resume.pdf
    design:
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        #filename: kalen-emsley-Bkci_8qcdvQ-unsplash.jpg
        filename: weebly_header_obama_map.png
      biography:
        # Customize the style of your biography text
        style: 'text-align: justify; font-size: 0.8em;'
  - block: experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: '2006 January'
      # Education or Experience section first?
      is_education_first: false
  - block: skills
    content:
      title: Key Skills
      username: admin
  - block: awards
    content:
      title: Projects
      username: admin
  - block: awards
    content:
      title: Volunteering
      username: admin
  #- block: languages
   # content:
    #  title: Languages
    #  username: admin
---
