---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '4rem'

sections:
  - block: resume-biography-3
    content:
      title: 'Bio'
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      show_education: false
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: https://drive.google.com/file/d/1EAAJJJcDQTBhOXAQih5BEIQyzSuKiKoe/view?usp=sharing
      headings:
        about: ''
        education: ''
        experience: ''
        interests: ''
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: lg # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: square # Options: circle (default), square, rounded

  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
      sort_by: weight
      order: asc
    design:
      view: article-grid
      columns: 2
      # Show whole image instead of cropping to 16:9
      fill_image: false
  - block: collection
    content:
      title: Publications
      text: ''
      count: 999
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
  - block: markdown
    id: awards
    content:
      title: Awards & Fellowships
      text: |
        - **CHI 2026 Honorable Mention Award (Top 5%)** — DanXeReflect (2026)
        - Peerbots Research Fellowship (2026)
        - Cornell Graduate School Conference Grant (2023, 2026)
        - [PiTech Fellowship: Activating Dance (AR)chives](https://www.pi.tech.cornell.edu/spotlight/activating-dance-archives-exploring-augmented-reality-with-the-repertoire-of-martha-graham) (2024)
        - Cornell Bowers CIS Dream Grant (2023–2024)
        - KAIST Support Scholarship and Graduate Student Fund (2017–2018)
        - SIGCHI Student Travel Grant (2018)
        - Excellence Award, Ewha Portfolio Competition (2017)
        - First Prize, Continental Automotive Innovation Contest (2016)
        - First Prize, Ewha Capstone Design Competition (2016)
        - Dean's List, Ewha Womans University (2014, 2015)
  - block: markdown
    id: teaching
    content:
      title: Teaching
      text: |
        **Cornell University — Teaching Assistant (2023–Present)**

        - INFO 6520: Human–Computer Interaction Graduate Studio
        - INFO 5321: Introduction to Rapid Prototyping and Physical Computing
        - INFO 3450: Human–Computer Interaction Design
        - INFO 2950: Introduction to Data Science

        **KAIST — Teaching Assistant (2017–2018)**

        - GCT 700: Research Methodology of Human Behavioral Science
        - CTP 471: Social Networks Theory
  - block: markdown
    id: service
    content:
      title: Academic Service
      text: |
        **Conference reviewing:** CHI (2024, 2026, 2027), HRI (2026, 2027), DIS (2025, 2026), VRST (2025).

        **Journal reviewing:** International Journal of Human-Computer Studies (2026).

        **Reviewer recognition:** Special Recognitions for Outstanding Reviews, CHI 2027 and DIS 2026.

        **Community organization:** Cornell HCI Korea Group (2023–2024).
  - block: markdown
    id: activities
    content:
      title: Invited Talks, Workshops & Exhibitions
      text: |
        ### Invited Talks

        - **Guest Lecture**, Underwood International College, Yonsei University (May 2025) — Dance (AR)chive and the convergence of cultural industries and technology.
        - **NEW@Graham: Graham & Tech**, Martha Graham School, New York (March 2025) — Interactive 3D experiences of Martha Graham choreography.
        - **XR Monthly: Augmented Reality+Dance**, Cornell Tech XR Collaboratory (September 2024).

        ### Workshops

        - **Make My Body: Robot Design Workshop**, Cornell Bowers CIS (Fall 2026) — Lead organizer.

        ### Exhibitions & Public Engagement

        - **Art+Tech Exhibit**, A.D. White House, Cornell (December 2024) — XR installation of Martha Graham archives. [Cornell Chronicle](https://news.cornell.edu/stories/2024/12/exhibit-highlights-arttech-intersections-student-work)
        - **Bechdel Day**, Directors Guild of Korea (2021) — Gender representation analysis in Korean films. [The Korea Times](https://www.koreatimes.co.kr/www/art/2023/12/398_315108.html)
        - **Creative Code Exhibition: Quiet Standing**, ArtCenter Nabi (2019).
---
