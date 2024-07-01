---
title: "Biconvex Clustering"
publication_types:
  - "article-journal"
authors:
  - S. Chakraborty
  - J. Xu
abstract: "Convex clustering has recently garnered increasing interest due to its attractive theoretical and computational properties, but its merits become limited in the face of high-dimensional data. In such settings, pairwise affinity terms that rely on k-nearest neighbors become poorly specified and Euclidean measures of fit provide weaker discriminating power. To surmount these issues, we propose to modify the convex clustering objective so that feature weights are optimized jointly with the centroids. The resulting problem becomes biconvex, and as such remains well-behaved statistically and algorithmically. In particular, we derive a fast algorithm with closed form updates and convergence guarantees, and establish finite-sample bounds on its prediction error. Under interpretable regularity conditions, the error bound analysis implies consistency of the proposed estimator. Biconvex clustering performs feature selection throughout the clustering task: as the learned weights change the effective feature representation, pairwise affinities can be updated adaptively across iterations rather than precomputed within a dubious feature space. We validate the contributions on real and simulated data, showing that our method effectively addresses the challenges of dimensionality while reducing dependence on carefully tuned heuristics typical of existing approaches. Supplementary materials for this article are available online." 
draft: false
featured: true
url_pdf: "https://www.tandfonline.com/doi/full/10.1080/10618600.2023.2197474"
links:
  - name: "arXiv"
    url: "https://arxiv.org/abs/2008.01760"
url_code: "https://github.com/SaptarshiC98/BCC"
publication:  Journal of Computational and Graphical Statistics
date: "2023-05-17"
tags:
  - Clustering

---
