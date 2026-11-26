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
      text: |
        Hello! I am a Ph.D. candidate in [**Information Science**](https://infosci.cornell.edu/) at Cornell University, advised by [**François Guimbretière**](https://infosci.cornell.edu/people/francois-guimbretiere). My research explores how embodied technologies can support collaborative activities across distance. I build and study telepresence robots, XR avatars, and AI agents that act on people’s behalf, focusing on how these technologies enable people to coordinate, communicate, and reflect together.
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
          enable: false

      # Name heading sizing to accommodate long or short names
      name:
        size: lg # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: square # Options: circle (default), square, rounded

  - block: markdown
    id: papers
    content:
      title: Featured Publications
      text: |
        <div class="featured-research-list">
        <article class="featured-research-row"><div class="featured-research-image"><img src="/website/publications/comparative-study-of-robots-and-avatars/Moneyshot.png" alt="Designing Embodied Telepresence for Remote Collaboration: A Comparative Study of Robots and Avatars" loading="lazy"></div><div class="featured-research-copy"><div class="featured-research-label">CSCW 2026</div><h3>Designing Embodied Telepresence for Remote Collaboration: A Comparative Study of Robots and Avatars</h3><div class="featured-research-authors"><strong>Hyunju Kim</strong>, Yeonju Jang, Mose Sakashita, Brandon Woodard, Yuki Suwabe, Danielle Ihechisim Imogu, Xiaozhen Liu, Guy Hoffman, François Guimbretière</div><details style="margin-top:12px;"><summary style="display:flex;justify-content:flex-start;align-items:center;gap:8px;flex-wrap:wrap;list-style:none;cursor:pointer;"><span style="display:inline-flex;align-items:center;gap:6px;padding:6px 12px;border:1px solid #d6b89f;border-radius:5px;color:#805a40;background:white;font-size:14px;font-weight:600;text-decoration:none;cursor:pointer;line-height:1.4;"><svg style="display:inline-block;flex:none;margin:0;width:15px;height:15px;" aria-hidden="true" viewBox="0 0 24 24" width="15" height="15" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M6 3h9l3 3v15H6z M9 10h6 M9 14h6 M9 17h4"/></svg>ABS</span><a style="display:inline-flex;align-items:center;gap:6px;padding:6px 12px;border:1px solid #d6b89f;border-radius:5px;color:#805a40;background:white;font-size:14px;font-weight:600;text-decoration:none;cursor:pointer;line-height:1.4;" href="https://dl.acm.org/doi/10.1145/3816921" target="_blank" rel="noopener"><svg style="display:inline-block;flex:none;margin:0;width:15px;height:15px;" aria-hidden="true" viewBox="0 0 24 24" width="15" height="15" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M10 13a4 4 0 0 0 6 0l4-4a4 4 0 0 0-6-6l-2 2 M14 11a4 4 0 0 0-6 0l-4 4a4 4 0 0 0 6 6l2-2"/></svg>ACM DL</a><a style="display:inline-flex;align-items:center;gap:6px;padding:6px 12px;border:1px solid #d6b89f;border-radius:5px;color:#805a40;background:white;font-size:14px;font-weight:600;text-decoration:none;cursor:pointer;line-height:1.4;" href="https://youtu.be/uBqfn0VkqQ8" target="_blank" rel="noopener"><svg style="display:inline-block;flex:none;margin:0;width:15px;height:15px;" aria-hidden="true" viewBox="0 0 24 24" width="15" height="15" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="5" width="18" height="14" rx="3"/><path d="m10 9 5 3-5 3z" fill="currentColor"/></svg>Video</a></summary><div style="border:1px solid #d6b89f;border-radius:5px;padding:12px;margin-top:10px;"><p style="margin:0;">Telepresence systems enable remote collaboration through physical robots or virtual avatars, yet prior comparisons have focused on technical capabilities and affordances from remote users. This overlooks how local collaborators interpret and respond to embodied actions. We conducted a within-subjects study in which participants collaborated with a remote partner embodied as either a robot or avatar across various tasks. Both embodiments supported functionally equivalent actions: navigation, gesture, object referencing, and digital tool use. Despite this parity of system functions and tasks, participants consistently interpreted and organized collaboration differently: robots invited spatially grounded coordination and were framed as assistants requiring accommodation, while avatars invited engaged discussion and were framed as active collaborators capable of reciprocal interaction. We discuss design implications for aligning embodiment choices with the relational and task-specific demands of remote collaboration.</p></div></details></div></article>
        <article class="featured-research-row"><div class="featured-research-image"><img src="/website/publications/danxereflect-interacting-with-the-spatio-temporal-past-movements-for-embodied-reflective-choreographic-collaboration/teaser.png" alt="DanXeReflect: Interacting with the Spatio-Temporal Past Movements for Embodied, Reflective Choreographic Collaboration" loading="lazy"></div><div class="featured-research-copy"><div class="featured-research-label">CHI 2026 <span class="featured-research-award">Honorable Mention (Top 5%)</span></div><h3>DanXeReflect: Interacting with the Spatio-Temporal Past Movements for Embodied, Reflective Choreographic Collaboration</h3><div class="featured-research-authors"><strong>Hyunju Kim</strong>, François Guimbretière, Bokyung Lee</div><details style="margin-top:12px;"><summary style="display:flex;justify-content:flex-start;align-items:center;gap:8px;flex-wrap:wrap;list-style:none;cursor:pointer;"><span style="display:inline-flex;align-items:center;gap:6px;padding:6px 12px;border:1px solid #d6b89f;border-radius:5px;color:#805a40;background:white;font-size:14px;font-weight:600;text-decoration:none;cursor:pointer;line-height:1.4;"><svg style="display:inline-block;flex:none;margin:0;width:15px;height:15px;" aria-hidden="true" viewBox="0 0 24 24" width="15" height="15" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M6 3h9l3 3v15H6z M9 10h6 M9 14h6 M9 17h4"/></svg>ABS</span><a style="display:inline-flex;align-items:center;gap:6px;padding:6px 12px;border:1px solid #d6b89f;border-radius:5px;color:#805a40;background:white;font-size:14px;font-weight:600;text-decoration:none;cursor:pointer;line-height:1.4;" href="https://dl.acm.org/doi/10.1145/3772318.3790808" target="_blank" rel="noopener"><svg style="display:inline-block;flex:none;margin:0;width:15px;height:15px;" aria-hidden="true" viewBox="0 0 24 24" width="15" height="15" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M10 13a4 4 0 0 0 6 0l4-4a4 4 0 0 0-6-6l-2 2 M14 11a4 4 0 0 0-6 0l-4 4a4 4 0 0 0 6 6l2-2"/></svg>ACM DL</a><a style="display:inline-flex;align-items:center;gap:6px;padding:6px 12px;border:1px solid #d6b89f;border-radius:5px;color:#805a40;background:white;font-size:14px;font-weight:600;text-decoration:none;cursor:pointer;line-height:1.4;" href="https://youtu.be/FZyWqiVWjB4" target="_blank" rel="noopener"><svg style="display:inline-block;flex:none;margin:0;width:15px;height:15px;" aria-hidden="true" viewBox="0 0 24 24" width="15" height="15" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="5" width="18" height="14" rx="3"/><path d="m10 9 5 3-5 3z" fill="currentColor"/></svg>Video</a></summary><div style="border:1px solid #d6b89f;border-radius:5px;padding:12px;margin-top:10px;"><p style="margin:0;">Choreographic reflection relies on iterative dialogue, where dancers and choreographers refine movement through embodied demonstration and shared feedback in studio rehearsal. With the shift to video, this exchange becomes constrained annotations detach from the body, gestures lose spatial grounding, and subtle variations are difficult to capture. Advances in markerless motion capture enable 3D reconstruction from rehearsal video, allowing past recordings to be re-materialized for embodied interaction in XR. We present DanXeReflect, an XR system that transforms flat video into a virtual studio where movements appear as interactive avatars. Users can re-enact poses to search sequences, perform alternative revisions alongside originals, and attach annotations directly to body parts. A study with choreographers and dancers shows how these embodied interactions reposition spatio-temporal data as collaborative anchors, extending reflective dialogue beyond co-located rehearsal into asynchronous, distributed practice</p></div></details></div></article>
        <article class="featured-research-row"><div class="featured-research-image"><img src="/website/publications/kim2024providing/DualAwareness.png" alt="Providing Dual Awareness using Multimodal Cues for Collaborative Manipulation in Virtual Environments" loading="lazy"></div><div class="featured-research-copy"><div class="featured-research-label">International Journal of Human–Computer Interaction</div><h3>Providing Dual Awareness using Multimodal Cues for Collaborative Manipulation in Virtual Environments</h3><div class="featured-research-authors"><strong>Hyunju Kim</strong>, Jung-Min Park</div><details style="margin-top:12px;"><summary style="display:flex;justify-content:flex-start;align-items:center;gap:8px;flex-wrap:wrap;list-style:none;cursor:pointer;"><span style="display:inline-flex;align-items:center;gap:6px;padding:6px 12px;border:1px solid #d6b89f;border-radius:5px;color:#805a40;background:white;font-size:14px;font-weight:600;text-decoration:none;cursor:pointer;line-height:1.4;"><svg style="display:inline-block;flex:none;margin:0;width:15px;height:15px;" aria-hidden="true" viewBox="0 0 24 24" width="15" height="15" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M6 3h9l3 3v15H6z M9 10h6 M9 14h6 M9 17h4"/></svg>ABS</span><a style="display:inline-flex;align-items:center;gap:6px;padding:6px 12px;border:1px solid #d6b89f;border-radius:5px;color:#805a40;background:white;font-size:14px;font-weight:600;text-decoration:none;cursor:pointer;line-height:1.4;" href="https://www.tandfonline.com/doi/full/10.1080/10447318.2023.2188533" target="_blank" rel="noopener"><svg style="display:inline-block;flex:none;margin:0;width:15px;height:15px;" aria-hidden="true" viewBox="0 0 24 24" width="15" height="15" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M10 13a4 4 0 0 0 6 0l4-4a4 4 0 0 0-6-6l-2 2 M14 11a4 4 0 0 0-6 0l-4 4a4 4 0 0 0 6 6l2-2"/></svg>DOI</a></summary><div style="border:1px solid #d6b89f;border-radius:5px;padding:12px;margin-top:10px;"><p style="margin:0;">Virtual reality (VR) collaborative manipulation requires a proper understanding of the user’s self, other collaborators, and shared objects in the virtual environment. Users must be aware of the movements of themselves and others to coordinate their actions when they hand over an object or move it together. The awareness of collaboration plays an essential role in virtual environments. However, previous studies have focused on providing awareness only for cooperative manipulation. This study proposes a novel framework for dual awareness that comprehensively manages the state of interactions between multiple users and shared virtual objects and provides distinct sensory cues to distinguish themselves from collaborators. The experimental results showed that participants could easily and quickly collaborate on manipulation using our feedback, and they also answered positively in the subjective evaluation.</p></div></details></div></article>
        </div>
  - block: markdown
    id: work-in-progress
    content:
      title: Work in Progress
      text: |
        <div class="featured-research-list">
        <article class="featured-research-row"><div class="featured-research-image"><img src="/website/projects/proxypilot/featured.png" alt="ProxyPilot research system" loading="lazy"></div><div class="featured-research-copy"><div class="featured-research-label">Manuscript in preparation</div><h3>ProxyPilot: Context-Adaptive Delegation of Robot Body Control for Agentic Telepresence Collaboration</h3><details style="margin-top:12px;"><summary style="display:flex;justify-content:flex-start;align-items:center;gap:8px;flex-wrap:wrap;list-style:none;cursor:pointer;"><span style="display:inline-flex;align-items:center;gap:6px;padding:6px 12px;border:1px solid #d6b89f;border-radius:5px;color:#805a40;background:white;font-size:14px;font-weight:600;text-decoration:none;cursor:pointer;line-height:1.4;"><svg style="display:inline-block;flex:none;margin:0;width:15px;height:15px;" aria-hidden="true" viewBox="0 0 24 24" width="15" height="15" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M6 3h9l3 3v15H6z M9 10h6 M9 14h6 M9 17h4"/></svg>ABS</span></summary><div style="border:1px solid #d6b89f;border-radius:5px;padding:12px;margin-top:10px;"><p style="margin:0;">ProxyPilot explores how remote collaborators delegate navigation, viewpoint adjustment, and gestures to an AI-assisted telepresence robot while retaining the ability to reclaim control.</p></div></details></div></article>
        <article class="featured-research-row"><div class="featured-research-image"><img src="/website/publications/walking-together-remote-co-navigation-with-embodied-telepresence/teaser_fixed.png" alt="WalkBeside: Designing Navigational Delegation for a Semi-Autonomous Robot in Embodied Telepresence" loading="lazy"></div><div class="featured-research-copy"><div class="featured-research-label">Manuscript in preparation</div><h3>WalkBeside: Designing Navigational Delegation for a Semi-Autonomous Robot in Embodied Telepresence</h3><details style="margin-top:12px;"><summary style="display:flex;justify-content:flex-start;align-items:center;gap:8px;flex-wrap:wrap;list-style:none;cursor:pointer;"><span style="display:inline-flex;align-items:center;gap:6px;padding:6px 12px;border:1px solid #d6b89f;border-radius:5px;color:#805a40;background:white;font-size:14px;font-weight:600;text-decoration:none;cursor:pointer;line-height:1.4;"><svg style="display:inline-block;flex:none;margin:0;width:15px;height:15px;" aria-hidden="true" viewBox="0 0 24 24" width="15" height="15" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><path d="M6 3h9l3 3v15H6z M9 10h6 M9 14h6 M9 17h4"/></svg>ABS</span><a style="display:inline-flex;align-items:center;gap:6px;padding:6px 12px;border:1px solid #d6b89f;border-radius:5px;color:#805a40;background:white;font-size:14px;font-weight:600;text-decoration:none;cursor:pointer;line-height:1.4;" href="https://youtu.be/U8rHEhlhTNw" target="_blank" rel="noopener"><svg style="display:inline-block;flex:none;margin:0;width:15px;height:15px;" aria-hidden="true" viewBox="0 0 24 24" width="15" height="15" fill="none" stroke="currentColor" stroke-width="1.8" stroke-linecap="round" stroke-linejoin="round"><rect x="3" y="5" width="18" height="14" rx="3"/><path d="m10 9 5 3-5 3z" fill="currentColor"/></svg>Video</a></summary><div style="border:1px solid #d6b89f;border-radius:5px;padding:12px;margin-top:10px;"><p style="margin:0;">WalkBeside explores navigational delegation through a VR-mediated quadruped telepresence robot that follows a local collaborator. Remote users adjust their relative position through natural room-scale movement.</p></div></details></div></article>
        </div>

        - **Replicating the Design Space of Rendered Robot Faces**  
          *Under review, HRI 2027 Short Contributions*  
          Replicated a foundational robot-face perception study with 68 new participants, developing open-source face assets and a reusable web-based evaluation framework.

        - **Make My Body: When a Robot Talks with Its Maker About Its Own Body**  
          *Manuscript in preparation*  
          Investigated human–robot co-design through workshops in which participants constructed a robot’s body while negotiating design decisions with a conversational robot agent.
  - block: markdown
    id: publications
    content:
      title: Publications
      text: |
        ### Peer-Reviewed Full Papers
        
        - **DanXeReflect: Interacting with the Spatio-Temporal Past Movements for Embodied, Reflective Choreographic Collaboration**  
          **Hyunju Kim**, François Guimbretière, Bokyung Lee  
          *CHI ’26 · Honorable Mention (Top 5%)* · [DOI](https://doi.org/10.1145/3772318.3790808) · [Video](https://youtu.be/FZyWqiVWjB4)
        
        - **Designing Embodied Telepresence for Remote Collaboration: A Comparative Study of Robots and Avatars**  
          **Hyunju Kim**, Yeonju Jang, Mose Sakashita, Brandon Woodard, Yuki Suwabe, Danielle Ihechisim Imogu, Xiaozhen Liu, Guy Hoffman, François Guimbretière  
          *PACM HCI (CSCW ’26)* · [DOI](https://doi.org/10.1145/3816921) · [Video](https://youtu.be/uBqfn0VkqQ8)
        
        - **The Effects of Avatar Gender on Ratings of Reconstructed Teaching**  
          Yilu Sun, Yejoon Yoo, **Hyunju Kim**, Xianyi Li, Rimjhim Singh, Yuqing Wu, Wei Yang, Aleshia Hayes, Andrea Stevenson Won  
          *Computers in Human Behavior Reports · 2026* · [DOI](https://doi.org/10.1016/j.chbr.2026.101437)
        
        - **Providing Dual Awareness Using Multimodal Cues for Collaborative Manipulation in Virtual Environments**  
          **Hyunju Kim**, Jung-Min Park  
          *International Journal of Human–Computer Interaction · 2023* · [DOI](https://www.tandfonline.com/doi/full/10.1080/10447318.2023.2188533)
        
        - **VRoxy: Wide-Area Collaboration From an Office Using a VR-Driven Robotic Proxy**  
          Mose Sakashita, **Hyunju Kim**, Brandon Woodard, Ruidong Zhang, François Guimbretière  
          *UIST ’23* · [DOI](https://doi.org/10.1145/3586183.3606743) · [Video](https://www.youtube.com/watch?v=1hpaASC_Xls)
        
        - **ReMotion: Supporting Remote Collaboration in Open Space with Automatic Robotic Embodiment**  
          Mose Sakashita, Ruidong Zhang, Xiaoyi Li, **Hyunju Kim**, Michael Russo, Cheng Zhang, Malte F. Jung, François Guimbretière  
          *CHI ’23* · [DOI](https://dl.acm.org/doi/10.1145/3544548.3580699) · [Video](https://www.youtube.com/watch?v=SaJQQTBBbFw)
        
        - **Human-Centered Dynamic Service Scheduling Approach in Multi-Agent Environments**  
          Yunseo Jung, **Hyunju Kim**, Kyung-Duk Suh, Jung-Min Park  
          *Applied Sciences · 2022* · [MDPI](https://www.mdpi.com/2076-3417/12/21/10850)
        
        - **RealityBrush: An AR Authoring System that Captures and Utilizes Kinetic Properties of Everyday Objects**  
          **Hyunju Kim**, Sanghwa Hong, Junki Kim, Taesoo Jang, Woontack Woo, Seongkook Heo, Byungjoo Lee  
          *Multimedia Tools and Applications · 2021* · [DOI](https://link.springer.com/article/10.1007/s11042-020-09332-4) · [Video](https://youtu.be/y5rFqXztRdk)
        
        ### Extended Abstracts & Posters
        
        - **Reframing Wizard-of-Oz for Proxy-Mediated Interaction**  
          Jieun Kim\* and **Hyunju Kim\*** (\* Co-first authors)  
          *CHI EA ’26* · [DOI](https://doi.org/10.1145/3772363.3799017)
        
        - **MRTransformer: Transforming Avatar Non-verbal Behavior for Remote MR Collaboration in Incongruent Spaces**  
          Cheng Yao Wang, **Hyunju Kim**, Payod Panda, Eyal Ofek, Mar Gonzalez-Franco, Andrea Stevenson Won  
          *ISMAR-Adjunct ’24* · [IEEE Xplore](https://ieeexplore.ieee.org/document/10765238)
        
        - **AvatarPilot: Decoupling One-to-One Motions from Their Semantics with Weighted Interpolations**  
          Cheng Yao Wang, Eyal Ofek, **Hyunju Kim**, Payod Panda, Andrea Stevenson Won, Mar Gonzalez-Franco  
          *ISMAR-Adjunct ’24* · [IEEE Xplore](https://ieeexplore.ieee.org/document/10765138)
        
        - **Comparing the Impact of Professional and Automatic Closed Captions on Video-Watching Experience**  
          **Hyunju Kim**, Yan Tao, Chuanrui Liu, Yuzhuo Zhang, Yuxin Li  
          *CHI EA ’23* · [DOI](https://dl.acm.org/doi/10.1145/3544549.3585634)
        
        - **Button++: Designing Risk-aware Smart Buttons**  
          Eunji Park, **Hyunju Kim**, Byungjoo Lee  
          *CHI EA ’18* · [DOI](https://dl.acm.org/doi/10.1145/3170427.3188645)
        
        ### Other Publications
        
        - **Who Moved the Robot? Contribution Dissolution in Agentic Telepresence**  
          **Hyunju Kim**  
          *Nobody Did This, CSCW ’26 Workshop* · [Workshop Paper](https://kashifimteyaza.github.io/agent-mediated-collaboration/papers.html)
        
        - **SoundFleXR: Selectively Constraining Axes of Audio Rendering Presentations**  
          Brandon Woodard, **Hyunju Kim**, Hyunsung Cho, David Lindlbauer, Rhonda Wilson, Joseph LaViola Jr.  
          *arXiv preprint · 2026* · [arXiv](https://arxiv.org/abs/2611.28020)
  - block: markdown
    id: awards
    content:
      title: Fellowships, Talks & Exhibitions
      text: |
        <div class="activity-grid" style="display:grid;gap:18px;width:100%;margin:auto;">
        <article style="border:1px solid #d8d1ca;border-radius:16px;overflow:hidden;box-shadow:0 3px 8px #0000000a;"><a href="https://peerbots.org/research/fellowship" style="display:block;color:inherit;text-decoration:none;"><img src="https://peerbots.org/Peerbots%20Logo.png" alt="Peerbots logo" style="width:100%;height:160px;object-fit:contain;background:transparent;"><div style="padding:22px;"><small style="opacity:.75;">Fellowship · 2026</small><h3 style="font-size:1.15rem;margin:10px 0;">Peerbots Research Fellowship</h3><p style="font-size:.95rem;margin:0;">Replicating and extending the design space of rendered robot faces to study static and animated expressive cues.</p><p style="font-size:.85rem;margin:14px 0 0;">Learn more →</p></div></a></article>
        <article style="border:1px solid #d8d1ca;border-radius:16px;overflow:hidden;box-shadow:0 3px 8px #0000000a;"><a href="/website/projects/make-my-body/" style="display:block;color:inherit;text-decoration:none;"><img src="/website/media/make-my-body.png" alt="Make My Body workshop poster" style="width:100%;height:160px;object-fit:contain;background:transparent;"><div style="padding:22px;"><small style="opacity:.75;">Lead organizer · Cornell Bowers CIS · Oct 27–28, 2026</small><h3 style="font-size:1.15rem;margin:10px 0;">Make My Body: Robot Design Workshop</h3><p style="font-size:.95rem;margin:0;">Participants co-designed a robot’s physical body through conversation with the robot.</p></div><p style="padding:0 14px;font-size:.85rem;">Learn more →</p></a></article>
        <article style="border:1px solid #d8d1ca;border-radius:16px;overflow:hidden;box-shadow:0 3px 8px #0000000a;"><a href="https://www.dance.nyc/for-audiences/community-calendar/view/NEWGraham-Graham-and-Tech/2025-03-18/" style="display:block;color:inherit;text-decoration:none;"><img src="https://www.dance.nyc/images/users/5703/Floes_image_by_SoHyun_Bae_dancer_-_Grace_Sautter_IMG_3037event_image.jpg" alt="NEW@Graham: Graham &amp; Tech event image" style="width:100%;height:160px;object-fit:contain;background:transparent;"><div style="padding:22px;"><small style="opacity:.75;">Invited talk · Martha Graham School · March 2025</small><h3 style="font-size:1.15rem;margin:10px 0;">NEW@Graham: Graham &amp; Tech</h3><p style="font-size:.95rem;margin:0;">Interactive 3D experiences of Martha Graham choreography.</p><p style="font-size:.85rem;margin:14px 0 0;">Learn more →</p></div></a></article>
        <article style="border:1px solid #d8d1ca;border-radius:16px;overflow:hidden;box-shadow:0 3px 8px #0000000a;"><a href="https://www.pi.tech.cornell.edu/spotlight/activating-dance-archives-exploring-augmented-reality-with-the-repertoire-of-martha-graham" style="display:block;color:inherit;text-decoration:none;"><img src="https://images.squarespace-cdn.com/content/v1/64f7282ac7818a537fe9f402/0c1af8d2-ce93-42e9-bcf4-27a6ed43075e/image10.png" alt="Dance (AR)chive XR headset application" style="width:100%;height:160px;object-fit:contain;"><div style="padding:22px;"><small style="opacity:.75;">Fellowship · 2024</small><h3 style="font-size:1.15rem;margin:10px 0;">PiTech Fellowship: Activating Dance (AR)chives</h3><p style="font-size:.95rem;margin:0;">Exploring augmented reality with the repertoire of Martha Graham.</p><p style="font-size:.85rem;margin:14px 0 0;">Learn more →</p></div></a></article>
        <article style="border:1px solid #d8d1ca;border-radius:16px;overflow:hidden;box-shadow:0 3px 8px #0000000a;"><a href="https://news.cornell.edu/stories/2024/12/exhibit-highlights-arttech-intersections-student-work" style="display:block;color:inherit;text-decoration:none;"><img src="https://as.cornell.edu/sites/default/files/styles/6_4_large/public/2024-12/20241206-milstein-art-and-tech-112-small.jpeg?h=95857c9c&amp;itok=yx14mE_K" alt="Art+Tech Exhibition" style="width:100%;height:220px;object-fit:contain;background:transparent;display:block;margin:0;"><div style="padding:22px;"><small style="opacity:.75;">Exhibition · Cornell · December 2024</small><h3 style="font-size:1.15rem;margin:10px 0;">Art+Tech Exhibition</h3><p style="font-size:.95rem;margin:0;">Interactive XR installation of Martha Graham’s dance archives.</p><p style="font-size:.85rem;margin:14px 0 0;">Learn more →</p></div></a></article>
        <article style="border:1px solid #d8d1ca;border-radius:16px;overflow:hidden;box-shadow:0 3px 8px #0000000a;"><a href="https://www.koreatimes.co.kr/www/art/2023/12/398_315108.html" style="display:block;color:inherit;text-decoration:none;"><img src="https://img.koreatimes.co.kr/upload/newsV2/images/202109/8f00b5477e5f4b049d57df308b3faf86.jpg?w=728" alt="Bechdel Day: Gender Representation Analysis in Korean Films" style="width:100%;height:220px;object-fit:contain;background:transparent;display:block;margin:0;"><div style="padding:22px;"><small style="opacity:.75;">Public engagement · 2021</small><h3 style="font-size:1.15rem;margin:10px 0;">Bechdel Day: Gender Representation Analysis in Korean Films</h3><p style="font-size:.95rem;margin:0;">Frame-by-frame analysis of visual gender representation in Korean films.</p><p style="font-size:.85rem;margin:14px 0 0;">Learn more →</p></div></a></article>
        </div>
  - block: markdown
    id: teaching
    content:
      title: Teaching
      text: |
        **Cornell University: Teaching Assistant**

        - [INFO 6520] Human–Computer Interaction Graduate Studio <a class="teaching-course-button" href="https://classes.cornell.edu/browse/roster/FA26/class/INFO/6520" target="_blank" rel="noopener noreferrer" style="display:inline-flex;align-items:center;gap:5px;padding:3px 9px;margin-left:8px;border-radius:5px;background:#A67C52;color:white;text-decoration:none;font-size:12px;vertical-align:middle;white-space:nowrap;">Course ↗</a>
        - [INFO 5321] Introduction to Rapid Prototyping and Physical Computing <a class="teaching-course-button" href="https://classes.cornell.edu/browse/roster/FA26/class/INFO/5321" target="_blank" rel="noopener noreferrer" style="display:inline-flex;align-items:center;gap:5px;padding:3px 9px;margin-left:8px;border-radius:5px;background:#A67C52;color:white;text-decoration:none;font-size:12px;vertical-align:middle;white-space:nowrap;">Course ↗</a>
        - [INFO 3450] Human–Computer Interaction Design <a class="teaching-course-button" href="https://classes.cornell.edu/browse/roster/FA25/class/INFO/3450" target="_blank" rel="noopener noreferrer" style="display:inline-flex;align-items:center;gap:5px;padding:3px 9px;margin-left:8px;border-radius:5px;background:#A67C52;color:white;text-decoration:none;font-size:12px;vertical-align:middle;white-space:nowrap;">Course ↗</a>
        - [INFO 2950] Introduction to Data Science <a class="teaching-course-button" href="https://classes.cornell.edu/browse/roster/SP23/class/INFO/2950" target="_blank" rel="noopener noreferrer" style="display:inline-flex;align-items:center;gap:5px;padding:3px 9px;margin-left:8px;border-radius:5px;background:#A67C52;color:white;text-decoration:none;font-size:12px;vertical-align:middle;white-space:nowrap;">Course ↗</a>

        **KAIST: Teaching Assistant**

        - [GCT 700] Research Methodology of Human Behavioral Science
        - [CTP 471] Social Networks Theory
---
