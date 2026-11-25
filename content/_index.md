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
        <div style="display:grid;grid-template-columns:repeat(auto-fit,minmax(min(100%,280px),1fr));gap:24px;width:100%;max-width:1000px;margin:auto;">
        <article style="border:1px solid #d8d1ca;border-radius:16px;overflow:hidden;box-shadow:0 3px 8px #0000000a;"><a href="https://peerbots.org/research/fellowship" style="display:block;color:inherit;text-decoration:none;"><div style="padding:22px;"><small style="opacity:.75;">Fellowship · 2026</small><h3 style="font-size:1.15rem;margin:10px 0;">Peerbots Research Fellowship</h3><p style="font-size:.95rem;margin:0;">Replicating and extending the design space of rendered robot faces to study static and animated expressive cues.</p><p style="font-size:.85rem;margin:14px 0 0;">Learn more →</p></div></a></article>
        <article style="border:1px solid #d8d1ca;border-radius:16px;overflow:hidden;box-shadow:0 3px 8px #0000000a;"><div style="padding:22px;"><small style="opacity:.75;">Lead organizer · Cornell Bowers CIS · Oct 27–28, 2026</small><h3 style="font-size:1.15rem;margin:10px 0;">Make My Body: Robot Design Workshop</h3><p style="font-size:.95rem;margin:0;">Participants co-designed a robot’s physical body through conversation with the robot.</p></div></article>
        <article style="border:1px solid #d8d1ca;border-radius:16px;overflow:hidden;box-shadow:0 3px 8px #0000000a;"><a href="https://www.dance.nyc/for-audiences/community-calendar/view/NEWGraham-Graham-and-Tech/2025-03-18/" style="display:block;color:inherit;text-decoration:none;"><div style="padding:22px;"><small style="opacity:.75;">Invited talk · Martha Graham School · March 2025</small><h3 style="font-size:1.15rem;margin:10px 0;">NEW@Graham: Graham &amp; Tech</h3><p style="font-size:.95rem;margin:0;">Interactive 3D experiences of Martha Graham choreography.</p><p style="font-size:.85rem;margin:14px 0 0;">Learn more →</p></div></a></article>
        <article style="border:1px solid #d8d1ca;border-radius:16px;overflow:hidden;box-shadow:0 3px 8px #0000000a;"><a href="https://www.pi.tech.cornell.edu/spotlight/activating-dance-archives-exploring-augmented-reality-with-the-repertoire-of-martha-graham" style="display:block;color:inherit;text-decoration:none;"><div style="padding:22px;"><small style="opacity:.75;">Fellowship · 2024</small><h3 style="font-size:1.15rem;margin:10px 0;">PiTech Fellowship: Activating Dance (AR)chives</h3><p style="font-size:.95rem;margin:0;">Exploring augmented reality with the repertoire of Martha Graham.</p><p style="font-size:.85rem;margin:14px 0 0;">Learn more →</p></div></a></article>
        <article style="border:1px solid #d8d1ca;border-radius:16px;overflow:hidden;box-shadow:0 3px 8px #0000000a;"><a href="https://news.cornell.edu/stories/2024/12/exhibit-highlights-arttech-intersections-student-work" style="display:block;color:inherit;text-decoration:none;"><img src="https://as.cornell.edu/sites/default/files/styles/6_4_large/public/2024-12/20241206-milstein-art-and-tech-112-small.jpeg?h=95857c9c&amp;itok=yx14mE_K" alt="Art+Tech Exhibition" style="width:100%;height:220px;object-fit:contain;background:#fff;display:block;margin:0;"><div style="padding:22px;"><small style="opacity:.75;">Exhibition · Cornell · December 2024</small><h3 style="font-size:1.15rem;margin:10px 0;">Art+Tech Exhibition</h3><p style="font-size:.95rem;margin:0;">Interactive XR installation of Martha Graham’s dance archives.</p><p style="font-size:.85rem;margin:14px 0 0;">Learn more →</p></div></a></article>
        <article style="border:1px solid #d8d1ca;border-radius:16px;overflow:hidden;box-shadow:0 3px 8px #0000000a;"><a href="https://www.koreatimes.co.kr/www/art/2023/12/398_315108.html" style="display:block;color:inherit;text-decoration:none;"><img src="https://img.koreatimes.co.kr/upload/newsV2/images/202109/8f00b5477e5f4b049d57df308b3faf86.jpg?w=728" alt="Bechdel Day: Gender Representation Analysis in Korean Films" style="width:100%;height:220px;object-fit:contain;background:#fff;display:block;margin:0;"><div style="padding:22px;"><small style="opacity:.75;">Public engagement · 2021</small><h3 style="font-size:1.15rem;margin:10px 0;">Bechdel Day: Gender Representation Analysis in Korean Films</h3><p style="font-size:.95rem;margin:0;">Frame-by-frame analysis of visual gender representation in Korean films.</p><p style="font-size:.85rem;margin:14px 0 0;">Learn more →</p></div></a></article>
        </div>
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
