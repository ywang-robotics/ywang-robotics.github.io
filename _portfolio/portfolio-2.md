---
title: "A Quadratic-Programming Approach to Dual-arm Mobile Manipulation"
excerpt: "We provide the optimization-based robot control approach that  enables a modular description of robotic tasks and a reactive solution in real-time. <br/><img src='/images/pr2-museum.png'>"
collection: portfolio
---

As a continuition of my Master thesis project back in 2010, I realized optimization is a powerful tool for specifying control problems with inequalities. We documented the first result for a visual servoing problem in the [51st IEEE CDC in 2012](/publication/2012-12-10-paper-cdc-number-10), where we addressed the visibility constraint for [Position-based Visual servoing](https://www.youtube.com/watch?v=tS0_SCJ-UQc) through the model predictive control approach.  

The optimization formulation provides a modular approach to specify objectives and constraints. Using a pan-cleaning task performed by the Schunk light weight arms, we demonstrated at [IFAC World congress 2014](/publication/2014-08-15-paper-ifac-number-9) the following: 

*  Quadratic programming (QP) provides a smoother trajectory compared to Linear programming (LP) thanks to its unique optimum.
*  Task-space specifications, e.g., admittance control, can be easiliy integrated into the QP, either as a part of the objective or as a constraint.
*  QP can simultaneously fulfill multiple objectives by scalarize a weighting sum.

[![Pan-cleaning task by the Schunk arms](/images/dumbo_cover_image.png)](https://www.youtube.com/watch?v=M1j4e8Zncw8)


A mobile base increases the robot workspace thus enables a better potential for a robot to serve in our daily life.  The PR2 robot is equiped with two 7 DOF arms and a 3 DOF mobile base. We address the synchronization of these three group of degrees of freedoms on the kinamatic level with a virtual kinematic chain. We presented the prellimenary result at [IROS-2015](/publication/2015-10-10-paper-iros-number-8) and documented it later at [IJHR](/publication/2016-03-15-paper-ijhr-number-7).

In a straight forward manner, we can apply the QP for tele-operation problems. We provided new controller mode for a 5 DOF manipulator mounted on the KUKA youbot at [ICRA-2016](2016-5-16-paper-icra-number-6).

[![Mobile table manipulation](/images/PR2-table.png)](https://www.youtube.com/watch?v=HO_amCdft-A)


Recently, I summarized the QP formulation and documented it at [RCIM](/publication/2019-10-01-paper-rcim-number-4).
