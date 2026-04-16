---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: large # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: square # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        My research lies on the theoretical side of applied mathematics: I mainly work with abstract models to study their properties in terms of control theory. Are they controllable? Stabilizable? Why? What if we add constraints? What if we are looking for optimal controls?

        My background makes me a thoroughly theoretical researcher, and I try to let that shape how I look at practical problems. Conversely, I try to let practical considerations shape my theoretical problem solving. In that spirit, I have been looking into constructive methods for some time now: in control theory, there are situations and methods that allow us to complement classical existence results with some information on the solutions. These can lead to strong characterisations and/or numerical approximations.

        In stabilisation, my co-authors and I have contributed several key insights to extend the constructive method that is backstepping, to general control systems in infinite dimension. This method consists in solving a more complex problem than stabilisation, which requires more work but rewards us with more information on the feedback law, in the best cases an explicit expression.

        In controllability and reachability analysis, our use of duality theory leads to constructive characterizations of admissible controls or certificates of non-reachability. This allows for their numerical approximation, and sometimes even their numerical certification in the case of non-reachability.

    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
  # - block: collection
  #  id: talks
   # content:
  #  title: Recent & Upcoming Talks
   #   filters:
  #      folders:
   #       - events
  # design:
  #    view: card
 
---
