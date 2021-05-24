---
title: "From Zero to Hero: Towards an Effective Teaching by Demonstration
  Framework for Robot Generalization"
date: 2021-05-24T23:39:04.429Z
summary: Allow everyday users to teach robots by demonstration
draft: false
featured: false
external_link: https://maram-sakr.netlify.app/project/LfD/
image:
  filename: featured
  focal_point: Smart
  preview_only: false
---
Robots are being increasingly used in many areas of our daily life; from industrial and social robots to robots used in medicine and space. The ability for everyday users to deal with these robots will become inevitable in the near future. Robot Learning from Demonstration (LfD) is concerned with programming robots to perform tasks by observing demonstrations from humans without the need for any robot programming experience. The robot performance is bounded by the quality of the provided demonstrations. Many aspects are affecting the demonstration quality. These aspects include the teacher's experience, the data collection method, and the demonstration interface. In this proposal, I focus on the teacher's role to improve the demonstration quality which in turn improves the robot performance. 

This research proposal has three main contributions. First, I plan to quantify the demonstration quality as a first step for improvement. The proposed approach for quantifying the demonstration quality is by extracting the underlying cost functions from expert demonstrations to get the main features that the expert has considered when teaching a robot. Then, a sensitivity analysis will be conducted for all the recovered cost functions with respect to robot learning and generalization. This aims to get the most important cost functions for the robot's performance. Second, these important functions will then be utilized in a training framework for novice users who do not have any robotics experience. Different training techniques are proposed to mitigate all types of learning preferences of the users as well as to explore the best approach for training. The extracted cost functions will be used as scores for the provided demonstrations and the user will observe these scores online while teaching the robot. By doing this, the user will get an idea about the good and bad demonstrations for the robot without the need for any technical details about the robot kinematics and learning. Lastly, two main criteria are defined to pick the most informative demonstrations in the task space. In addition, a guidance system will be used to guide the user for these informative demonstrations every time the user is providing a new demonstration. These contributions target improving the quality of a single demonstration as well as the distribution of a set of demonstrations. Ultimately, the findings from this research will allow naive users to quickly learn how to efficiently teach robots by demonstration.