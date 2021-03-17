---
title: "AdaGrasp: Learning an Adaptive Gripper-Aware Grasping Policy"
subtitle: ""
summary: "ICRA 2021"
authors: [Zhenjia Xu, Beichun Qi, Shubham Agrawal, Shuran Song]
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
abstract: "This paper aims to improve robots’ versatility and adaptability by allowing them to use a large variety of end-effector tools and quickly adapt to new tools. We propose AdaGrasp, a method to learn a single grasping policy that generalizes to novel grippers. By training on a large collection of grippers, our algorithm is able to acquire generalizable knowledge of how different grippers should be used in various tasks. Given a visual observation of the scene and the gripper, AdaGrasp infers the possible grasping poses and their grasp scores by computing the cross convolution between the shape encodings of the input gripper and scene. Intuitively, this cross convolution operation can be considered as an efficient way of exhaustively matching the scene geometry with gripper geometry under different grasp poses (i.e., translations and orientations), where a good “match” of 3D geometry will lead to a successful grasp. We validate our methods in both simulation and real-world environments. Our experiment shows that AdaGrasp significantly outperforms the existing multi-gripper grasping policy method, especially when handling cluttered environments and partial observations."
url_pdf: "https://arxiv.org/pdf/2011.14206.pdf"
url_project: "https://adagrasp.cs.columbia.edu/"
url_code: 'https://github.com/columbia-robovision/adagrasp'
url_video: 'https://www.youtube.com/embed/kknTYTbORfs'
---
