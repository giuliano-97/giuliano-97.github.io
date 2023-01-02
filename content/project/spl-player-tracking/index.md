---
title: Long-term Player Tracking in the RoboCup Soccer SPL
summary: A framework for long-term player tracking in video recordings of soccer matches in the RoboCup Soccer Standard Platform League.
tags:
  - Deep Learning
  - Computer Vision
  - Multi-Object Tracking
  - Robotics
  - RoboCup
date: '2022-07-01T00:00:00Z'

image:
  caption: Tracked players in RoboCup SPL final of 2019
  focal_point: Smart

links:
  - icon: github
    icon_pack: fab
    name: Code
    url: https://github.com/nomadz-ethz/spl-player-tracking-release.git
---
In order to evaluate progress in [RoboCup Soccer](https://www.robocup.org/domains/1), automated video analysis tools are needed to compute game statistics such as ball possession and field coverage. To that end, the players have to be detected, identified, and tracked reliably for the entire duration of the match. Player tracking in the [Standard Platorm League](https://spl.robocup.org) is especially challenging since all the players look exactly the same, except for the color of their jersey, so state-of-the-art apperance-based approaches for pedestrian or vehicle tracking would fail. The proposed tracking framework uses non-linear optimization to fuse information from different sources - visual short-term tracking, self-localization from the players, game events, and jersey color detection - and is capable of reliably tracking players over 5 minute sequences with >90% accuracy.