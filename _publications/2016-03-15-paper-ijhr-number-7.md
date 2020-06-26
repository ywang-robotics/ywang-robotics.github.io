---
title: "Whole body control of a dual-arm mobile robot using a virtual kinematic chain"
collection: publications
permalink: /publication/2016-03-15-paper-ijhr-number-7
excerpt: 'Journal version of the IROS 2015 paper.'
date: 2016-03-15
venue: 'International Journal of Humanoid Robotics'
paperurl: 'http://www.csc.kth.se/~yuquan/paper/ijhrYuquan.pdf'
citation: ' (2016). &quot; Whole body control of a dual-arm mobile robot using a virtual kinematic chain&quot; <i> International Journal of Humanoid Robotics</i>.'
---


Dual-arm manipulators have more advanced manipulation abilities compared to single-arm manipulators and manipulators mounted on a mobile base have additional mobilityand  a  larger  workspace.  Combining  these  advantages,  mobile  dual-arm  robots  are  ex-pected to perform a variety of tasks in the future. Kinematically, the configuration oftwo  arms  that  branches  from  the  mobile  base  results  in  a  serial-to-parallel  kinematic structure. In order to respond to external disturbances, this serial-to-parallel kinematicstructure makes inverse kinematic computations non-trivial, as the motion of the base has to take the needs of both arms into account. Instead of using the dual-arm kinemat-ics directly, we propose to use a Virtual Kinematic Chain (VKC) to specify the common motion of the two arms. We formulate a constraint based programming solution whichconsists  of  two  parts.  In  the  first  part,  we  use  an  extended  serial  kinematic  chain  including the mobile base and the VKC to formulate constraints that realize the desired orientation  and  translation  expressed  in  the  world  frame.  In  the  second  part,  we  use the resolved VKC motion to constrain the common motion of the two arms. In order toexplore the redundancy of the two arms in an optimization framework, we also provide a VKC-oriented manipulability measure as well as its closed-form gradient. We verify the proposed approach with simulations and experiments that are performed on a PR2robot, which has two 7 Degrees of Freedom (DoF) arms and a 3 DoF mobile base.

[Download paper here](http://urn.kb.se/resolve?urn=urn:nbn:se:kth:diva-179638)

Recommended citation:
```bib
@article{wang2016ijhr,
  title={Whole body control of a dual-arm mobile robot using a virtual kinematic chain},
  author={Wang, Yuquan and Smith, Christian and Karayiannidis, Yiannis and {\"O}gren, Petter},
  journal={International Journal of Humanoid Robotics},
  volume={13},
  number={01},
  pages={1550047},
  year={2016},
  publisher={World Scientific}
}
```

