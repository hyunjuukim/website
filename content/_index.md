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
      title: Awards, Fellowships, Talks & Exhibitions
      text: |
        **[Peerbots Research Fellowship (2026)](https://peerbots.org/research/fellowship)**

        Replicating and extending the design space of rendered robot faces to study static and animated expressive cues.

        **[PiTech Fellowship: Activating Dance (AR)chives (2024)](https://www.pi.tech.cornell.edu/spotlight/activating-dance-archives-exploring-augmented-reality-with-the-repertoire-of-martha-graham)**

        Exploring augmented reality with the repertoire of Martha Graham.

        **Make My Body: Robot Design Workshop** · Cornell Bowers CIS · October 27–28, 2026

        Lead organizer of a hands-on workshop where participants co-designed a robot's body through conversation.

        **[NEW@Graham: Graham & Tech (2025)](https://www.dance.nyc/for-audiences/community-calendar/view/NEWGraham-Graham-and-Tech/2025-03-18/)** — Invited talk at Martha Graham School, New York, March 2025. Interactive 3D experiences of Martha Graham choreography.

        [![Art+Tech Exhibition](https://as.cornell.edu/sites/default/files/styles/6_4_large/public/2024-12/20241206-milstein-art-and-tech-112-small.jpeg?h=95857c9c&itok=yx14mE_K)](https://news.cornell.edu/stories/2024/12/exhibit-highlights-arttech-intersections-student-work)

        **[Art+Tech Exhibition (2024)](https://news.cornell.edu/stories/2024/12/exhibit-highlights-arttech-intersections-student-work)**

        Interactive XR installation of Martha Graham's dance archives at Cornell.

        [![Bechdel Day](https://img.koreatimes.co.kr/upload/newsV2/images/202109/8f00b5477e5f4b049d57df308b3faf86.jpg?w=728)](https://www.koreatimes.co.kr/www/art/2023/12/398_315108.html)

        **[Bechdel Day: Gender Representation Analysis in Korean Films (2021)](https://www.koreatimes.co.kr/www/art/2023/12/398_315108.html)**

        Frame-by-frame analysis of visual gender representation in Korean films.

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
---
