---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---
<!--
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
-->
<span style="display: inline-block;">
  <sup>\* denotes equal contribution </sup> 
</span>

<span style="display: inline-block;">
  <img src="/images/h2s2r.png" alt="Human2Sim2Robot" style="width: 300px;float: right; margin-left: 10px;" />
  <span style="color:#52ADC8">**Crossing the Human-Robot Embodiment Gap with Sim-to-Real Reinforcement Learning using One Human Demonstration**</span> [\[paper\]](https://human2sim2robot.github.io){:target="_blank"} [\[site\]](https://human2sim2robot.github.io){:target="_blank"} <br>
    <sup>Tyler Ga Wei Lum\*, **Olivia Y. Lee**\*, C. Karen Liu, Jeannette Bohg <br> 
    *In review.* <br>
    **TL;DR: We develop a real-to-sim-to-real framework that trains dexterous manipulation policies with RL in simulation from a single RGB-D human video demonstration. These policies can be deployed zero-shot on a real robot with only minutes of human effort.** <br>
    We propose Human2Sim2Robot, a novel real-to-sim-to-real framework for training dexterous manipulation policies using only one RGB-D video of a human demonstrating a task. Our method utilizes reinforcement learning (RL) in simulation to cross the human-robot embodiment gap without relying on wearables, teleoperation, or large-scale data collection typically necessary for imitation learning methods. From the demonstration, we extract two task-specific components: (1) the object pose trajectory to define an object-centric, embodiment-agnostic reward function, and (2) the pre-manipulation hand pose to initialize and guide exploration during RL training, which together eliminate the need for task-specific reward shaping and tuning. We demonstrate that Human2Sim2Robot significantly outperforms baselines across a range of grasping, non-prehensile manipulation, and extrinsic manipulation tasks. </sup> 
</span>

<span style="display: inline-block;">
  <img src="/images/affordances.png" alt="Affordance Learning" style="width: 300px;float: right; margin-left: 10px;" />
  <span style="color:#52ADC8">**Affordance-Guided Reinforcement Learning via Visual Prompting**</span> [\[paper\]](https://arxiv.org/pdf/2407.10341.pdf){:target="_blank"} [\[site\]](https://sites.google.com/view/affordance-guided-rl){:target="_blank"} <br>
    <sup>**Olivia Y. Lee**, Annie Xie, Kuan Fang, Karl Pertsch, and Chelsea Finn <br> 
    *In review. Robotics Science and Systems (RSS), 2024: [Task Specification](https://sites.google.com/view/rss-taskspec){:target="_blank"} & [Lifelong Robot Learning](https://sites.google.com/view/lifelong-robot-learning){:target="_blank"}* <br>
    **TL;DR: To effectively improve the performance of policies pre-trained on diverse data, we make fine-tuning with online RL more efficient using affordance representations extracted from VLMs zero-shot.** <br>
    We present an approach that extracts affordance representations from VLMs via keypoints to define dense shaping rewards for online reinforcement learning. We pretrain policies on Bridge data and a modest number of in-domain demonstrations of the task, and finetune policies online using VLM-generated dense rewards. On a real-world manipulation task, our VLM-generated rewards improve the sample efficiency of autonomous RL, enabling task completion in 20K online finetuning steps. Our approach is robust to reducing in-domain demonstrations used for pretraining, reaching comparable performance in 35K online finetuning steps.
    <!-- We present an approach that extracts affordance representations via visual prompting to define dense rewards for online reinforcement learning. We leverage the impressive ability of VLMs to reason about affordances through keypoints in zero-shot to define dense shaping rewards for robotic learning. On a real-world manipulation task specified by natural language description, the VLM-generated rewards improve the sample efficiency of autonomous RL, enabling success task completion in 20K online finetuning steps. Additionally, we demonstrate the robustness of the approach to reducing the number of in-domain demonstrations used for pretraining, reaching comparable performance in 35K online finetuning steps. --> </sup> 
</span>

<span style="display: inline-block;">
  <img src="/images/playitbyear.png" alt="Play it by Ear" style="width: 300px;float: right; margin-left: 10px;" />
  <span style="color:#52ADC8">**Play it by Ear: Learning Skills amidst Occlusion through Audio-Visual Imitation Learning**</span> [\[paper\]](https://arxiv.org/pdf/2205.14850.pdf){:target="_blank"} [\[site\]](https://sites.google.com/view/playitbyear){:target="_blank"} [\[publication\]](https://roboticsconference.org/2022/program/papers/009/){:target="_blank"}<br>
    <sup>Maximilian Du\*, **Olivia Y. Lee**\*, Suraj Nair, and Chelsea Finn <br>
    *Robotics Science and Systems (RSS), 2022 [\[recording\]](https://youtu.be/qI0zvRp-UnE?t=4034){:target="_blank"}* <br> 
    **TL;DR: We show that augmenting image input with audio and proprioception, as well as online human interventions, help imitation learning policies improve success on challenging partially-occluded tasks.** <br>
    We present a system that learns to complete partially-observed manipulation tasks by reasoning over vision, audio, and memory. We combine offline imitation learning from a modest number of tele-operated demonstrations and online finetuning with human interventions. In simulation, our system benefits from using audio and online interventions, which improve success rates of offline imitation learning by ~20%. On a Franka Emika Panda robot, our system completes manipulation tasks under occlusion with a 70% success rate, 50% higher than a policy that does not use audio.
    <!-- We propose a system that learns to complete challenging, partially-observed manipulation tasks by reasoning over visual and audio inputs. Our system combines offline imitation learning from a modest number of tele-operated demonstrations and online finetuning using human provided interventions. In simulation, our system benefits from using audio and online interventions improve the success rate of offline imitation learning by ~20%. On a Franka Emika Panda robot, our system completes manipulation tasks (e.g. extracting keys from a bag) with a 70% success rate, 50% higher than a policy that does not use audio. -->
    </sup>
</span>
 
<span style="display: inline-block;">
  <img src="/images/satelliteqkd.png" alt="Satellite-QKD" style="width: 290px;float: right; margin-left: 10px;" />   
  <span style="color:#52ADC8">**An updated analysis of satellite quantum-key distribution missions**</span> [\[paper\]](https://arxiv.org/pdf/1909.13061.pdf){:target="_blank"} <br>
  <sup>**Olivia Y. Lee**, Tom Vergoossen<br>
    We provide a meta-analysis of research and development efforts towards the realization of satellite quantum-key distribution (satellite-QKD). We analyze technical parameters of protocols and infrastructure for performing satellite-based QKD. Following a timeline of key milestones, we summarize globally completed and proposed quantum satellite missions, categorized by specific advancements thus far in satellite-QKD. We conclude by discussing the current technical in satellite-QKD and future research directions to address them.
    <!-- We provide a meta-analysis of research and development efforts that have contributed to the realization of satellite quantum-key distribution (satellite-QKD). We present an overview of the various technical parameters of performing satellite-based QKD regarding protocols and infrastructure. Following a timeline of key milestones in the development of satellite-QKD, we present a high-level summary of globally completed and proposed quantum satellite missions, categorized by specific advancements thus far in satellite-QKD. We conclude with a discussion on the technical challenges currently faced in satellite-QKD and future directions to address these challenges. -->
  </sup>
</span>

<!-- 6/24/2024:
<span style="display: inline-block;">
  <img src="/images/affordances.png" alt="Affordance Learning" style="width: 250px;float: right; margin-left: 10px;" />
  <span style="color:#52ADC8">**Learning Affordances from Human Videos for Autonomous Robotic Exploration**</span> <br>
    <sup>**Olivia Y. Lee**, Annie Xie, Karl Pertsch, Suraj Nair, and Chelsea Finn <br>
    *Ongoing Project, presented at the [Stanford Symbolic Systems Annual Research Showcase](https://symsys.stanford.edu/events/ssp-fall-2023-poster-fair){:target="_blank"}* <br>
    We are developing a real robot system that autonomously explores and gathers in-domain experience by leveraging priors from human data. To do so, we address the lack of well-shaped rewards, a key challenge for robotic exploration, by leveraging structural assumptions from human interaction data. I have conducted preliminary experiments in simulation and am currently testing the approach on a real robot system.</sup> 
</span>
-->