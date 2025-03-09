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
  \* denotes equal contribution 
</span>

<div style="display: flex; align-items: flex-start; margin-bottom: 40px;">
  <div style="flex: 1; padding-right: 20px;">
    <span style="color:#52ADC8"><b>Crossing the Human-Robot Embodiment Gap with Sim-to-Real Reinforcement Learning using One Human Demonstration</b></span> 
    <a href="https://human2sim2robot.github.io" target="_blank">[paper]</a> 
    <a href="https://human2sim2robot.github.io" target="_blank">[site]</a> <br>
    <sup>Tyler Ga Wei Lum*, <b>Olivia Y. Lee</b>*, C. Karen Liu, Jeannette Bohg <br> 
    <i>In review</i> <br>
    <b>TL;DR: Our real-to-sim-to-real framework trains dexterous manipulation policies with RL in simulation from a single RGB-D human video demonstration, which we deploy zero-shot on a real robot with only minutes of human effort.</b> <br>
    We present Human2Sim2Robot, a real-to-sim-to-real framework for training dexterous manipulation policies using only one RGB-D video of a human demonstrating a task. We leverage reinforcement learning (RL) in simulation to cross the human-robot embodiment gap without wearables, teleoperation, or large-scale data collection typically necessary for imitation learning methods. From the demonstration, we extract two task-specific components: (1) the object pose trajectory to define an object-centric, embodiment-agnostic reward function, and (2) the pre-manipulation hand pose to initialize and guide exploration during RL training. These eliminate the need for task-specific reward engineering. Human2Sim2Robot significantly outperforms baselines across a range of grasping, non-prehensile manipulation, and extrinsic manipulation tasks.</sup>
  </div>
  
  <div style="width: 300px;">
    <img src="/images/h2s2r.png" alt="Human2Sim2Robot" style="width: 100%; margin-bottom: 10px;" />
    <video width="100%" autoplay controls muted loop playsinline>
      <source src="/images/h2s2r.mov" type="video/mp4">
    </video>
  </div>
</div>

<div style="display: flex; align-items: flex-start; margin-bottom: 40px;">
  <div style="flex: 1; padding-right: 20px;">
    <span style="color:#52ADC8"><b>Affordance-Guided Reinforcement Learning via Visual Prompting</b></span> 
    <a href="https://arxiv.org/abs/2407.10341" target="_blank">[paper]</a> 
    <a href="https://sites.google.com/view/affordance-guided-rl" target="_blank">[site]</a> <br>
    <sup><b>Olivia Y. Lee</b>, Annie Xie, Kuan Fang, Karl Pertsch, and Chelsea Finn <br> 
    <i>In review. Robotics Science and Systems (RSS), 2024: <a href="https://sites.google.com/view/rss-taskspec" target="_blank">Task Specification</a> & <a href="https://sites.google.com/view/lifelong-robot-learning" target="_blank">Lifelong Robot Learning</a></i> <br>
    <b>TL;DR: To effectively improve the performance of policies pre-trained on diverse data, we make fine-tuning with online RL more efficient using affordance representations extracted from VLMs zero-shot.</b> <br>
    We present an approach that extracts affordance representations from VLMs via keypoints to define dense shaping rewards for online reinforcement learning. We pretrain policies on Bridge data and a modest number of in-domain demonstrations of the task, and finetune policies online using VLM-generated dense rewards. On a real-world manipulation task, our VLM-generated rewards improve the sample efficiency of autonomous RL, enabling task completion in 20K online finetuning steps. Our approach is robust to reducing in-domain demonstrations used for pretraining, reaching comparable performance in 35K online finetuning steps.</sup>
  </div>
  
  <div style="width: 300px;">
    <img src="/images/affordances.png" alt="Affordance Learning" style="width: 100%;" />
  </div>
</div>

<div style="display: flex; align-items: flex-start; margin-bottom: 40px;">
  <div style="flex: 1; padding-right: 20px;">
    <span style="color:#52ADC8"><b>Play it by Ear: Learning Skills amidst Occlusion through Audio-Visual Imitation Learning</b></span> 
    <a href="https://arxiv.org/abs/2205.14850" target="_blank">[paper]</a> 
    <a href="https://sites.google.com/view/playitbyear" target="_blank">[site]</a>
    <a href="https://roboticsconference.org/2022/program/papers/009/" target="_blank">[publication]</a> <br>
    <sup>Maximilian Du*, <b>Olivia Y. Lee</b>*, Suraj Nair, and Chelsea Finn <br> 
    <i>Robotics Science and Systems (RSS), 2022 <a href="https://youtu.be/qI0zvRp-UnE?t=4034" target="_blank">[recording]</a></i> <br>
    <b>TL;DR: We show that augmenting image input with audio and proprioception, as well as online human interventions, help imitation learning policies improve success on challenging partially-occluded tasks.</b> <br>
    We present a system that learns to complete partially-observed manipulation tasks by reasoning over vision, audio, and memory. We combine offline imitation learning from a modest number of tele-operated demonstrations and online finetuning with human interventions. In simulation, our system benefits from using audio and online interventions, which improve success rates of offline imitation learning by ~20%. On a Franka Emika Panda robot, our system completes manipulation tasks under occlusion with a 70% success rate, 50% higher than a policy that does not use audio.</sup>
  </div>
  
  <div style="width: 300px;">
    <img src="/images/playitbyear.png" alt="Play it by Ear" style="width: 100%;" />
  </div>
</div>

<div style="display: flex; align-items: flex-start; margin-bottom: 40px;">
  <div style="flex: 1; padding-right: 20px;">
    <span style="color:#52ADC8"><b>An updated analysis of satellite quantum-key distribution missions</b></span> 
    <a href="https://arxiv.org/abs/1909.13061" target="_blank">[paper]</a> <br>
    <sup><b>Olivia Y. Lee</b>, Tom Vergoossen <br> 
    We provide a meta-analysis of research and development efforts towards the realization of satellite quantum-key distribution (satellite-QKD). We analyze technical parameters of protocols and infrastructure for performing satellite-based QKD. Following a timeline of key milestones, we summarize globally completed and proposed quantum satellite missions, categorized by specific advancements thus far in satellite-QKD. We conclude by discussing the current technical in satellite-QKD and future research directions to address them.</sup>
  </div>
  
  <div style="width: 290px;">
    <img src="/images/satelliteqkd.png" alt="Play it by Ear" style="width: 100%" />
  </div>
</div>