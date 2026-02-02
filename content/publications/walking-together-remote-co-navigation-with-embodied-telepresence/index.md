---
title: "Walking Together: Remote Co-Navigation with Embodied Telepresence"
authors:
  - me
author_notes:
  - ""
date: 2026-02-01
publishDate: 2026-02-02T01:02:15.558Z
publication_types: 
  - Under Developments
publication: ""
publication_short: ""
abstract: We present a VR-mediated telepresence navigation system that treats room-scale embodied motion as high-level intent while an autonomy layer executes collision-aware robot motion in dynamic environments. Using a Unitree Go2 with live 360° video, the system supports anchor-based exploration and side-by-side collaboration, making intent–execution coupling and agency boundaries observable. We frame the prototype as a design probe to study legibility of navigational authority during shared autonomy.
summary: We conducted a user study examining how local participants collaborate with remote partners telepresented as robots versus avatars, revealing distinct participation patterns shaped by embodiment.
tags:
  - Robot
  - VR
featured: true
weight: 2
hugoblox:
  ids:
links:
  # - type: pdf
  #   url: ""
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
    url: "https://youtu.be/wWPZ5oO2llQ"
image: 
  filename: "teaser.png"
  caption: ""
  focal_point: ""
  preview_only: false
projects: []
slides: ""
draft: false
status: review
---

## Motivations

Telepresence robots have moved beyond simple “videoconferencing on wheels,” yet navigating dynamic, human-populated environments remains difficult. Remote operators often lack peripheral awareness, have an incomplete sense of space, and rely on unstable camera views. These limitations become especially apparent in large environments, where operators must simultaneously manage low-level steering and higher-level collaborative goals. Beyond workload, navigation also poses a legibility problem: when a robot slows, stops, or changes direction, collaborators may not know whether this behavior reflects the operator’s intent, automated collision avoidance, or a system error. This ambiguity makes it difficult to interpret navigational authority in the moment, creating friction during collaboration.

Shared and semi-autonomous navigation systems help reduce manual control by automating functions such as obstacle avoidance or path planning. However, these approaches often treat autonomy as functional assistance, without clearly communicating how control is distributed between the operator, the system, and local collaborators. When the boundary between “what the operator intended” and “what the system executed” is not perceptible, both operators and collaborators lose a stable basis for interpreting robot motion as intentional or reactive.

Virtual Reality (VR) offers a complementary approach by supporting embodied spatial understanding. Through immersive first-person perception and bodily interaction, VR allows operators to experience the remote environment more directly and to express intent through continuous signals such as head orientation, body movement, and gaze. These embodied cues can ground navigation in perception rather than discrete commands, making intent potentially easier to convey.

At the same time, integrating VR with physical telepresence introduces challenges. Operators move within limited, room-scale spaces, while robots navigate large, obstacle-rich environments that impose constraints not fully represented in VR. Direct mappings can become unsafe or unintuitive, while increased automation can blur agency and weaken the sense of embodied control.

This project explores how locomotion, navigation, and automation can be coupled to preserve navigational authority while enabling safe, context-aware execution. We present a VR-mediated telepresence platform that uses embodied interaction not only to control movement, but to make intent legible and negotiable during remote collaboration.