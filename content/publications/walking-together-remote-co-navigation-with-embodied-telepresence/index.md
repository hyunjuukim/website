---
title: "WalkBeside: Designing Navigational Delegation for a Semi-Autonomous Robot in Embodied Telepresence"
authors:
  - Hyunju Kim
  - Under Review
date: 2026-04-23
publishDate: 2026-04-21T00:00:00Z
publication_types: []
publication: Under Review
publication_short: ""
abstract: "When a remote guest joins a local collaborator to explore an unfamiliar site, such as during infrastructure assessment or architectural walkthroughs, they must navigate an unseen environment while engaging in collaboration. Existing systems place the full burden of navigation on the remote user, fragmenting attention between driving the robot and participating in the task. We argue that this limitation arises not from insufficient autonomy, but from how navigational control is structured. We present WalkBeside, an interaction design in which the local collaborator leads, the robot follows by default, and the remote user continuously adjusts their position by simply moving within their physical room. This room-scale movement is mapped directly onto the robot’s position relative to the collaborator, allowing the remote user to step closer, shift to the side, or hold back as naturally as they would in person. Grounded in the “contesting control framework”, we design a mechanism which (1) surrenders navigation to the local collaborator by default, (2) maintains spatial awareness through an embodied view, and (3) expresses positional adjustment through implicit physical movement. We instantiate this through a VR-mediated quadruped telepresence system. WalkBeside enables remote users to participate as spatially engaged partners and full collaborators."
summary: 
tags:
  - Under Review
featured: true
weight: 2
hugoblox:
  ids:
links:
  - type: pdf
    url: "https://drive.google.com/file/d/1hm60cwdczuj-z7ZTrGykBFNx3EnfEw4r/view?usp=sharing"
  # - type: code
  #   url: ""
  # - type: dataset
  #   url: ""
  # - type: poster
  #   url: ""
  # - type: project
  #   url: ""
  # - type: slides
  #   url: ""
  # - type: source
  #   url: ""
  - type: video
    url: "https://youtu.be/U8rHEhlhTNw"
image: 
  filename: "teaser_fixed.png"
  caption: ""
  focal_point: ""
  preview_only: false
projects: []
slides: ""
draft: false
status: review
---
<!-- 
## Motivations

Telepresence robots have moved beyond simple “videoconferencing on wheels,” yet navigating dynamic, human-populated environments remains difficult. Remote operators often lack peripheral awareness, have an incomplete sense of space, and rely on unstable camera views. These limitations become especially apparent in large environments, where operators must simultaneously manage low-level steering and higher-level collaborative goals. Beyond workload, navigation also poses a legibility problem: when a robot slows, stops, or changes direction, collaborators may not know whether this behavior reflects the operator’s intent, automated collision avoidance, or a system error. This ambiguity makes it difficult to interpret navigational authority in the moment, creating friction during collaboration.

Shared and semi-autonomous navigation systems help reduce manual control by automating functions such as obstacle avoidance or path planning. However, these approaches often treat autonomy as functional assistance, without clearly communicating how control is distributed between the operator, the system, and local collaborators. When the boundary between “what the operator intended” and “what the system executed” is not perceptible, both operators and collaborators lose a stable basis for interpreting robot motion as intentional or reactive.

Virtual Reality (VR) offers a complementary approach by supporting embodied spatial understanding. Through immersive first-person perception and bodily interaction, VR allows operators to experience the remote environment more directly and to express intent through continuous signals such as head orientation, body movement, and gaze. These embodied cues can ground navigation in perception rather than discrete commands, making intent potentially easier to convey.

At the same time, integrating VR with physical telepresence introduces challenges. Operators move within limited, room-scale spaces, while robots navigate large, obstacle-rich environments that impose constraints not fully represented in VR. Direct mappings can become unsafe or unintuitive, while increased automation can blur agency and weaken the sense of embodied control.

This project explores how locomotion, navigation, and automation can be coupled to preserve navigational authority while enabling safe, context-aware execution. We present a VR-mediated telepresence platform that uses embodied interaction not only to control movement, but to make intent legible and negotiable during remote collaboration. -->