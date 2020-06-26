---
title: "A transformation of the position based visual servoing problem into a convex optimization problem"
collection: publications
permalink: /publication/2012-12-10-paper-cdc-number-10
excerpt: 'We introduce a two step method that transforms the position-based visual servoing problem into a convex optimization problem with linear constraints.'
date: 2012-12-10
venue: '51st IEEE Conference on Decision and Control'
paperurl: 'https://ieeexplore.ieee.org/document/6426022'
citation: ' (2012). &quot; A transformation of the position based visual servoing problem into a convex optimization problem &quot; <i> 51st IEEE Conference on Decision and Control</i>.'
---

Here we address the problem of moving a camera from an initial pose to a final pose. The trajectory between the two poses is subject to constraints on the camera motion and the visibility, where we have bounds on the allowed velocities and accelerations of the camera and require that a set of point features are visible for the camera. We assume that the pose is possible to retrieve from the observations of the point features, i.e., we have a Position Based Visual Servoing Problem with constraints. We introduce a two step method that transforms the problem into a convex optimization problem with linear constraints. In the first step the rotational motion is restricted to be of a certain type. This restriction allows us to retrieve an explicit solution of the rotational motion that is optimal in terms of minimizing geodesic distance. Furthermore, this restriction guarantees that the rotational motion satisfies the constraints. Using the explicit solution, we can formulate a convex optimization problem for the translational motion, where we include constraints on workspace and visibility.


[Download paper here](http://www.csc.kth.se/~yuquan/paper/vs_mpc_CDC.pdf)

Recommended citation:
```bib
@inproceedings{wang2012cdc,
  title={A transformation of the position based visual servoing problem into a convex optimization problem},
  author={Wang, Yuquan and Thunberg, Johan and Hu, Xiaoming},
  booktitle={IEEE 51st IEEE Conference on Decision and Control (CDC)},
  pages={5673--5678},
  year={2012},
}
```

