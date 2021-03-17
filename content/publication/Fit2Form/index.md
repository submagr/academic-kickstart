---
title: "Fit2Form: 3D Generative Model for Robot Gripper Form Design"
subtitle: ""
summary: "CoRL 2020"
authors: ["Huy Ha*", "Shubham Agrawal*", "Shuran Song"]
author_notes:
- "Equal contribution"
- "Equal contribution"
tags: [3D-Computer-Vision, Robotics]
date: 2020-11-01
lastmod: 2020-11-01
featured: true 
draft: false
# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]
abstract: "The 3D shape of a robot's end-effector plays a critical role in determining it's functionality and overall performance. Many industrial applications rely on task-specific gripper designs to ensure the system's robustness and accuracy. However, the process of manual hardware design is both costly and time-consuming, and the quality of the resulting design is dependent on the engineer's experience and domain expertise, which can easily be out-dated or inaccurate. The goal of this work is to use machine learning algorithms to automate the design of task-specific gripper fingers. We propose Fit2Form, a 3D generative design framework that generates pairs of finger shapes to maximize design objectives (i.e., grasp success, stability, and robustness) for target grasp objects. We model the design objectives by training a Fitness network to predict their values for pairs of gripper fingers and their corresponding grasp objects. This Fitness network then provides supervision to a 3D Generative network that produces a pair of 3D finger geometries for the target grasp object. Our experiments demonstrate that the proposed 3D generative design framework generates parallel jaw gripper finger shapes that achieve more stable and robust grasps compared to other general-purpose and task-specific gripper design algorithms."
url_pdf: "https://arxiv.org/pdf/2011.06498.pdf"
url_project: "https://fit2form.cs.columbia.edu/"
url_code: 'https://github.com/columbia-robovision/fit2form'
# url_dataset: ''
# url_poster: ''
# url_slides: ''
# url_source: ''
url_video: 'https://www.youtube.com/embed/utKHP3qb1bg'
image:
  caption: ""
  focal_point: ""
  preview_only: false
---
