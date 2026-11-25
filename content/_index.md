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
  - block: markdown
    id: work-in-progress
    content:
      title: Work in Progress
      text: |
        - **[Replicating the Design Space of Rendered Robot Faces](/website/projects/robot-faces/)**  
          *Under review, HRI 2027 Short Contributions*  
          Replicated a foundational robot-face perception study with 68 new participants, developing open-source face assets and a reusable web-based evaluation framework.
        
        - **[ProxyPilot: Context-Adaptive Delegation of Robot Body Control for Agentic Telepresence Collaboration](/website/projects/proxypilot/)**  
          *Manuscript in preparation*  
          Developed an AI-assisted telepresence system that enables remote users to delegate and reclaim robot body control, supporting transitions between user control and autonomous behavior.
        
        - **[WalkBeside: Designing Navigational Delegation for a Semi-Autonomous Robot in Embodied Telepresence](/website/publications/walking-together-remote-co-navigation-with-embodied-telepresence/)**  
          *Manuscript in preparation*  
          Developed a VR-mediated quadruped telepresence system that autonomously follows a local collaborator while allowing the remote user to control their relative position.
        
        - **[Make My Body: When a Robot Talks with Its Maker About Its Own Body](/website/projects/make-my-body/)**  
          *Manuscript in preparation*  
          Investigated human–robot co-design through workshops in which participants constructed a robot’s body while negotiating design decisions with a conversational robot agent.
  - block: markdown
    id: publications
    content:
      title: Publications
      text: |
        ### Peer-Reviewed Full Papers
        
        - **[DanXeReflect: Interacting with the Spatio-Temporal Past Movements for Embodied, Reflective Choreographic Collaboration](https://doi.org/10.1145/3772318.3790808)**  
          **Hyunju Kim**, François Guimbretière, Bokyung Lee  
          *CHI ’26 · Honorable Mention (Top 5%)*
        
        - **[Designing Embodied Telepresence for Remote Collaboration: A Comparative Study of Robots and Avatars](https://doi.org/10.1145/3816921)**  
          **Hyunju Kim**, Yeonju Jang, Mose Sakashita, Brandon Woodard, Yuki Suwabe, Danielle Ihechisim Imogu, Xiaozhen Liu, Guy Hoffman, François Guimbretière  
          *PACM HCI (CSCW ’26)*
        
        - **[The Effects of Avatar Gender on Ratings of Reconstructed Teaching](https://doi.org/10.1016/j.chbr.2026.101437)**  
          Yilu Sun, Yejoon Yoo, **Hyunju Kim**, Xianyi Li, Rimjhim Singh, Yuqing Wu, Wei Yang, Aleshia Hayes, Andrea Stevenson Won  
          *Computers in Human Behavior Reports · 2026*
        
        - **Providing Dual Awareness Using Multimodal Cues for Collaborative Manipulation in Virtual Environments**  
          **Hyunju Kim**, Jung-Min Park  
          *International Journal of Human–Computer Interaction · 2023*
        
        - **[VRoxy: Wide-Area Collaboration From an Office Using a VR-Driven Robotic Proxy](https://doi.org/10.1145/3586183.3606743)**  
          Mose Sakashita, **Hyunju Kim**, Brandon Woodard, Ruidong Zhang, François Guimbretière  
          *UIST ’23*
        
        - **ReMotion: Supporting Remote Collaboration in Open Space with Automatic Robotic Embodiment**  
          Mose Sakashita, Ruidong Zhang, Xiaoyi Li, **Hyunju Kim**, Michael Russo, Cheng Zhang, Malte F. Jung, François Guimbretière  
          *CHI ’23*
        
        - **[Human-Centered Dynamic Service Scheduling Approach in Multi-Agent Environments](https://www.mdpi.com/2076-3417/12/21/10850)**  
          Yunseo Jung, **Hyunju Kim**, Kyung-Duk Suh, Jung-Min Park  
          *Applied Sciences · 2022*
        
        - **[RealityBrush: An AR Authoring System that Captures and Utilizes Kinetic Properties of Everyday Objects](https://link.springer.com/article/10.1007/s11042-020-09332-4)**  
          **Hyunju Kim**, Sanghwa Hong, Junki Kim, Taesoo Jang, Woontack Woo, Seongkook Heo, Byungjoo Lee  
          *Multimedia Tools and Applications · 2021*
        
        ### Extended Abstracts & Posters
        
        - **[Reframing Wizard-of-Oz for Proxy-Mediated Interaction](https://doi.org/10.1145/3772363.3799017)**  
          Jieun Kim and **Hyunju Kim** (co-first authors)  
          *CHI EA ’26*
        
        - **[MRTransformer: Transforming Avatar Non-verbal Behavior for Remote MR Collaboration in Incongruent Spaces](https://www.microsoft.com/en-us/research/publication/mrtransformer-transforming-avatar-non-verbal-behavior-for-remote-mr-collaboration-in-incongruent-spaces/)**  
          Cheng Yao Wang, **Hyunju Kim**, Payod Panda, Eyal Ofek, Mar Gonzalez-Franco, Andrea Stevenson Won  
          *ISMAR-Adjunct ’24*
        
        - **[AvatarPilot: Decoupling One-to-One Motions from Their Semantics with Weighted Interpolations](https://ieeexplore.ieee.org/document/10765138)**  
          Cheng Yao Wang, Eyal Ofek, **Hyunju Kim**, Payod Panda, Andrea Stevenson Won, Mar Gonzalez-Franco  
          *ISMAR-Adjunct ’24*
        
        - **[Comparing the Impact of Professional and Automatic Closed Captions on Video-Watching Experience](https://dl.acm.org/doi/10.1145/3544549.3585634)**  
          **Hyunju Kim**, Yan Tao, Chuanrui Liu, Yuzhuo Zhang, Yuxin Li  
          *CHI EA ’23*
        
        - **[Button++: Designing Risk-aware Smart Buttons](https://dl.acm.org/doi/10.1145/3170427.3188645)**  
          Eunji Park, **Hyunju Kim**, Byungjoo Lee  
          *CHI EA ’18*
        
        ### Other Publications
        
        - **Who Moved the Robot? Contribution Dissolution in Agentic Telepresence**  
          **Hyunju Kim**  
          *Nobody Did This, CSCW ’26 Workshop*
        
        - **[SoundFleXR: Selectively Constraining Axes of Audio Rendering Presentations](https://arxiv.org/abs/2611.28020)**  
          Brandon Woodard, **Hyunju Kim**, Hyunsung Cho, David Lindlbauer, Rhonda Wilson, Joseph LaViola Jr.  
          *arXiv preprint · 2026*
  - block: markdown
    id: awards
    content:
      title: Awards, Fellowships, Talks & Exhibitions
      text: |
        <div class="activity-grid" style="display:grid;gap:18px;width:100%;margin:auto;">
        <article style="border:1px solid #d8d1ca;border-radius:16px;overflow:hidden;box-shadow:0 3px 8px #0000000a;"><a href="https://peerbots.org/research/fellowship" style="display:block;color:inherit;text-decoration:none;"><div style="padding:22px;"><small style="opacity:.75;">Fellowship · 2026</small><h3 style="font-size:1.15rem;margin:10px 0;">Peerbots Research Fellowship</h3><p style="font-size:.95rem;margin:0;">Replicating and extending the design space of rendered robot faces to study static and animated expressive cues.</p><p style="font-size:.85rem;margin:14px 0 0;">Learn more →</p></div></a></article>
        <article style="border:1px solid #d8d1ca;border-radius:16px;overflow:hidden;box-shadow:0 3px 8px #0000000a;"><a href="/website/projects/make-my-body/" style="display:block;color:inherit;text-decoration:none;"><img src="/website/media/make-my-body.png" alt="Make My Body workshop poster" style="width:100%;height:160px;object-fit:contain;background:#fff;"><div style="padding:22px;"><small style="opacity:.75;">Lead organizer · Cornell Bowers CIS · Oct 27–28, 2026</small><h3 style="font-size:1.15rem;margin:10px 0;">Make My Body: Robot Design Workshop</h3><p style="font-size:.95rem;margin:0;">Participants co-designed a robot’s physical body through conversation with the robot.</p></div><p style="padding:0 14px;font-size:.85rem;">Learn more →</p></a></article>
        <article style="border:1px solid #d8d1ca;border-radius:16px;overflow:hidden;box-shadow:0 3px 8px #0000000a;"><a href="https://www.dance.nyc/for-audiences/community-calendar/view/NEWGraham-Graham-and-Tech/2025-03-18/" style="display:block;color:inherit;text-decoration:none;"><div style="padding:22px;"><small style="opacity:.75;">Invited talk · Martha Graham School · March 2025</small><h3 style="font-size:1.15rem;margin:10px 0;">NEW@Graham: Graham &amp; Tech</h3><p style="font-size:.95rem;margin:0;">Interactive 3D experiences of Martha Graham choreography.</p><p style="font-size:.85rem;margin:14px 0 0;">Learn more →</p></div></a></article>
        <article style="border:1px solid #d8d1ca;border-radius:16px;overflow:hidden;box-shadow:0 3px 8px #0000000a;"><a href="https://www.pi.tech.cornell.edu/spotlight/activating-dance-archives-exploring-augmented-reality-with-the-repertoire-of-martha-graham" style="display:block;color:inherit;text-decoration:none;"><img src="https://images.squarespace-cdn.com/content/v1/64f7282ac7818a537fe9f402/0c1af8d2-ce93-42e9-bcf4-27a6ed43075e/image10.png" alt="Dance (AR)chive XR headset application" style="width:100%;height:160px;object-fit:contain;"><div style="padding:22px;"><small style="opacity:.75;">Fellowship · 2024</small><h3 style="font-size:1.15rem;margin:10px 0;">PiTech Fellowship: Activating Dance (AR)chives</h3><p style="font-size:.95rem;margin:0;">Exploring augmented reality with the repertoire of Martha Graham.</p><p style="font-size:.85rem;margin:14px 0 0;">Learn more →</p></div></a></article>
        <article style="border:1px solid #d8d1ca;border-radius:16px;overflow:hidden;box-shadow:0 3px 8px #0000000a;"><a href="https://news.cornell.edu/stories/2024/12/exhibit-highlights-arttech-intersections-student-work" style="display:block;color:inherit;text-decoration:none;"><img src="https://as.cornell.edu/sites/default/files/styles/6_4_large/public/2024-12/20241206-milstein-art-and-tech-112-small.jpeg?h=95857c9c&amp;itok=yx14mE_K" alt="Art+Tech Exhibition" style="width:100%;height:220px;object-fit:contain;background:#fff;display:block;margin:0;"><div style="padding:22px;"><small style="opacity:.75;">Exhibition · Cornell · December 2024</small><h3 style="font-size:1.15rem;margin:10px 0;">Art+Tech Exhibition</h3><p style="font-size:.95rem;margin:0;">Interactive XR installation of Martha Graham’s dance archives.</p><p style="font-size:.85rem;margin:14px 0 0;">Learn more →</p></div></a></article>
        <article style="border:1px solid #d8d1ca;border-radius:16px;overflow:hidden;box-shadow:0 3px 8px #0000000a;"><a href="https://www.koreatimes.co.kr/www/art/2023/12/398_315108.html" style="display:block;color:inherit;text-decoration:none;"><img src="https://img.koreatimes.co.kr/upload/newsV2/images/202109/8f00b5477e5f4b049d57df308b3faf86.jpg?w=728" alt="Bechdel Day: Gender Representation Analysis in Korean Films" style="width:100%;height:220px;object-fit:contain;background:#fff;display:block;margin:0;"><div style="padding:22px;"><small style="opacity:.75;">Public engagement · 2021</small><h3 style="font-size:1.15rem;margin:10px 0;">Bechdel Day: Gender Representation Analysis in Korean Films</h3><p style="font-size:.95rem;margin:0;">Frame-by-frame analysis of visual gender representation in Korean films.</p><p style="font-size:.85rem;margin:14px 0 0;">Learn more →</p></div></a></article>
        </div>
  - block: markdown
    id: teaching
    content:
      title: Teaching
      text: |
        **Cornell University — Teaching Assistant (2023–Present)**

        - [INFO 6520: Human–Computer Interaction Graduate Studio](https://classes.cornell.edu/browse/roster/FA25/class/INFO/6520)
        - [INFO 5321: Introduction to Rapid Prototyping and Physical Computing](https://classes.cornell.edu/browse/roster/FA26/class/INFO/5321)
        - [INFO 3450: Human–Computer Interaction Design](https://classes.cornell.edu/browse/roster/FA26/class/INFO/3450)
        - [INFO 2950: Introduction to Data Science](https://classes.cornell.edu/browse/roster/FA26/class/INFO/2950)

        **KAIST — Teaching Assistant (2017–2018)**

        - GCT 700: Research Methodology of Human Behavioral Science
        - CTP 471: Social Networks Theory
---
