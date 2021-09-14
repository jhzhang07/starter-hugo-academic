---
title: A Bot for Go Game
summary: Designed a bot program with extremely high win ratio in Gogame using Monte Carlo tree search(MCTS).
tags:
- Algorithm
date: "2020"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: Smart

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: 
url_code: ""
url_pdf: "https://www.jhzhang.info/uploads/demo_resume.pdf"
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

使用了蒙特卡洛树搜索即 MCTS 的方法，蒙特卡洛树搜索 MCTS 是
一种针对决策类博弈游戏，运用蒙特卡洛模拟方法进行评估博弈策略的启发
式搜索算法。MCTS 的重点是对最有前途的举动进行分析，并基于对搜索空
间的随机采样来扩展搜索树。在每次模拟 (roll-out) 时，通过随机选择移动来
将游戏进行到最后。然后将每次 roll-out 的最终游戏结果用于对游戏树中的节
点进行加权，以便在将来的 roll-out 中更有可能选择更好的节点。每一轮蒙特
卡洛树搜索均包含四个步骤: 选择 扩展 模拟 反向传播
