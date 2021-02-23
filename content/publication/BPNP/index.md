---
title: "End-to-End Learnable Geometric Vision by Backpropagating PnP Optimization"
authors:
- admin
- Alvaro Parra
- Jiewei Cao
- Nan Li
- Tat-Jun Chin
date: "2019-09-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *CVPR 2020*
publication_short: In *CVPR 2020*

abstract: Deep networks excel in learning patterns from large amounts of data. On the other hand, many geometric vision tasks are specified as optimization problems. To seamlessly combine deep learning and geometric vision, it is vital to perform learning and geometric optimization end-to-end. Towards this aim, we present BPnP, a novel network module that backpropagates gradients through a Perspective-n-Points (PnP) solver to guide parameter updates of a neural network. Based on implicit differentiation, we show that the gradients of a ``self-contained" PnP solver can be derived accurately and efficiently, as if the optimizer block were a differentiable function. We validate BPnP by incorporating it in a deep model that can learn camera intrinsics, camera extrinsics (poses) and 3D structure from training datasets. Further, we develop an end-to-end trainable pipeline for object pose estimation, which achieves greater accuracy by combining feature-based heatmap losses with 2D-3D reprojection errors. Since our approach can be extended to other optimization problems, our work helps to pave the way to perform learnable geometric vision in a principled manner. Our PyTorch implementation of BPnP is available on http://github.com/BoChenYS/BPnP.

# Summary. An optional shortened abstract.
summary: We propose BPnP, a network module for backpropagation through a PnP optimizer, as if the optimizer were a differentiable function. 

tags:
featured: true

links:
url_pdf: https://arxiv.org/pdf/1909.06043.pdf
url_project: https://github.com/BoChenYS/BPnP

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

---


