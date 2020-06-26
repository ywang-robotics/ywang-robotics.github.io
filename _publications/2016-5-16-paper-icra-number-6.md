---
title: "Adaptive object centered teleoperation control of a mobile manipulator"
collection: publications
permalink: /publication/2016-5-16-paper-icra-number-6
excerpt: 'A quadratic programming approach to tele-operate a mobile robot.'
date: 2016-05-16
venue: '2016 IEEE International Conference on Robotics and Automation'
paperurl: 'http://urn.kb.se/resolve?urn=urn:nbn:se:kth:diva-182902'
---
 Tele-operation of a mobile robot manipulating and exploring an object shares many similarities with the manipulation of virtual objects in a 3D design software such as AutoCAD. The user interfaces are however quite different, mainly for historical reasons. In this paper we aim to change that, and draw inspiration from the 3D design community to propose a teleoperation interface control mode that is identical to the ones being used to locally navigate the virtual viewpointof most Computer Aided Design (CAD) softwares.

The proposed mobile manipulator control framework thus allows the user to focus on the 3D objects being manipulated, using control modes such as orbit  object and pan  object, supported by data from the wrist mounted RGB-D sensor. The gripper of the robot performs the desired motions relative to the object, while the manipulator arm and base moves in a way that realizes the desired gripper motions. The system redundancies are exploited in order to take additional constraints, such as obstacle avoidance, into account, using a constraint based programming framework.

[Download paper here](http://urn.kb.se/resolve?urn=urn:nbn:se:kth:diva-182902)

Recommended citation:
```bib
@inproceedings{baaberg2016icra,
  title={Adaptive object centered teleoperation control of a mobile manipulator},
  author={B{\aa}berg, Fredrik and Wang, Yuquan and Caccamo, Sergio and {\"O}gren, Petter},
  booktitle={IEEE International Conference on Robotics and Automation (ICRA)},
  pages={455--461},
  year={2016},
}
```

