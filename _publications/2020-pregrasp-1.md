---
title: "Learning pregrasp manipulation of objects from ungraspable poses"
collection: publications
permalink: /publication/2020-pregrasp-1
excerpt: 'Using pregrasp manipulation to grasp large, flat objects laying on the table against a wall.'
date: 2020-05-01
venue: 'ICRA 2020'
paperurl: 'https://arxiv.org/abs/2002.06344'
citation: 'Sun, Zhaole, et al. "Learning pregrasp manipulation of objects from ungraspable poses." 2020 IEEE International Conference on Robotics and Automation (ICRA). IEEE, 2020.'
---

Abstract: 

In robotic grasping, objects are often occluded in ungraspable configurations such that no pregrasp pose can be found, eg large flat boxes on the table that can only be grasped from the side. Inspired by humans' bimanual manipulation, eg one hand to lift up things and the other to grasp, we address this type of problems by introducing pregrasp manipulation - push and lift actions. We propose a model-free Deep Reinforcement Learning framework to train control policies that utilize visual information and proprioceptive states of the robot to autonomously discover robust pregrasp manipulation. The robot arm learns to first push the object towards a support surface and establishes a pivot to lift up one side of the object, thus creating a clearance between the object and the table for possible grasping solutions. Furthermore, we show the effectiveness of our proposed learning framework in training robust pregrasp policies that can directly transfer from simulation to real hardware through suitable design of training procedures, state, and action space. Lastly, we evaluate the effectiveness and the generalisation ability of the learned policies in real-world experiments, and demonstrate pregrasp manipulation of objects with various size, shape, weight, and surface friction. 
