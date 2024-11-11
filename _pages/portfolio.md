---
layout: archive
title: "Portfolio"
permalink: /portfolio/
author_profile: true
---

{% include base_path %}

More on my personal background: I am a U.S. citizen who grew up and was educated in Singapore. Besides research, I worked as a software engineer at Salesforce and at several startups, ranging from deep tech (quantum computing) to B2C companies based in Southeast Asia and the United States. I also studied abroad at the University of Oxford (Magdalen College) in Fall 2022, where I studied graph representation learning and philosophy of mind, and tried my hand at rowing! I enjoy playing tennis, hiking, reading (+ occasionally writing) science fiction, and brush calligraphy.

Inspired by my interdisciplinary coursework, I am drawn to research leveraging cognitive science for robot learning and visual understanding. I aim to better understand human cognitive processes, such as multimodal perception, curiosity, and interactive learning, to develop human-inspired learning algorithms for robotics.

Below is an assortment of works that summarize my academic interests. 

<!-- {% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %} -->

Thesis Papers
======
<span style="color:#52ADC8">**Leveraging Affordance Representations for Robot Learning**</span> [\[thesis\]](/files/Honors_Thesis.pdf){:target="_blank"} [\[publication\]](https://doi.org/10.25740/jp127mt8218){:target="_blank"} <br> <!-- [\[publication\]] -->
  <sub> *Undergraduate Honors Thesis*<br>
  Humans are capable of adapting to novel environments quickly using prior knowledge from past experiences. We can identify new instantiations of previously encountered object classes and easily apply previously learned skills to these new objects, both of which current embodied AI agents struggle with. Online reinforcement learning, where a robotic agent learns a mapping from states to actions to maximize a reward signal, provides a potential solution by enabling robots to learn from trial-and-error. However, current methods are sample-inefficient, lack shaping rewards, and require frequent resets. We propose a method to address the lack of shaping rewards using affordances, the action potential of objects, to create a dense shaping reward for online reinforcement learning. We leverage state-of-the-art vision-language models (VLMs) to predict keypoint-based affordance representations, which we use as intermediate dense rewards for online reinforcement learning, in addition to sparse task completion rewards. We demonstrate that dense shaping rewards speed up online reinforcement learning for robotic manipulation, and enables robots to succeed on a variety of object manipulation tasks, informed by human interaction priors encoded in VLMs. </sub> <br>
  <sub style="font-size:11px">*Topics: Affordances, Online Reinforcement Learning, Vision-Language Models, Robotics, Learning from Human Videos*</sub>

Teaching
======
<span style="color:#52ADC8">**Summer 2024: CS 229 Machine Learning**</span> <br>
   <sub> *Taught by Prof. Jehangir Amjad*</sub> <br>
   <sub style="font-size:11px">*Topics: Machine Learning, Supervised Learning, Unsupervised Learning*</sub>

<span style="color:#52ADC8">**Winter & Spring 2024: CS 224N Natural Language Processsing with Deep Learning**</span> <br>
   <sub> *Taught by Prof. Tatsunori Hashimoto / Prof. Diyi Yang (Winter 2024) and Prof. Christopher Manning (Spring 2024)*</sub> <br>
    <sub style="font-size:11px">*Topics: Natural Language Processing, Machine Learning, Deep Learning*</sub>

<span style="color:#52ADC8">**Fall 2023, Fall 2024: CS 157 Computational Logic**</span> <br>
   <sub> *Taught by Prof. Michael Genesereth*</sub> <br>
   <sub style="font-size:11px">*Topics: Propositional Logic, Relational Logic, Functional Logic*</sub>

Computational Projects
======
<span style="color:#52ADC8">**Today Years Old: Adapting Language Models to Word Shifts**</span> [\[paper\]](/files/2023-win-cs224n-paper.pdf){:target="_blank"} [\[poster\]](/files/2023-win-cs224n-poster.pdf){:target="_blank"} [\[code\]](https://www.github.com/oliviaylee/today-years-old){:target="_blank"} <br>
  <sub> *Final report, poster, and code for Stanford's CS 224N: Natural Language Processing with Deep Learning (Winter 2023)*<br>
  Finetuned GPT-2 and RoBERTa to predict word embeddings for novel lexical items from Urban Dictionary given their definitions. </sub> <br>
  <!-- I finetuned GPT-2 and RoBERTa to predict word embeddings for novel lexical items given their definitions. The model was finetuned via supervised learning on word embeddings for lexical items in a regular dictionary, using embeddings from the pretrained models off-the-shelf as ground-truth embeddings. The resultant model as used to predict word embeddings for Urban Dictionary words given their definitions. -->
  <sub style="font-size:11px">*Topics: Natural Language Processing, Machine Learning, Supervised Learning, Domain Adaptation*</sub>

<span style="color:#52ADC8">**A Shot in the Dark: Modeling Improved Zero-Shot and Few-Shot Transfer Learning with Self-Supervised Models for Sentiment Classification**</span> [\[paper\]](/files/2022-spr-cs229-paper.pdf){:target="_blank"} [\[poster\]](/files/2022-spr-cs229-poster.pdf){:target="_blank"} <br>
  <sub> *Final report and poster for Stanford's CS 229: Machine Learning (Spring 2022)*<br>
  Modeled transfer learning with self-supervised embeddings to optimize model performance on sentiment classification tasks.</sub> <br>
  <!-- We modeled transfer learning with self-supervised embeddings and supervised models at various scales to optimize model performance on sentiment classification tasks compared to DistilBERT. -->
  <sub style="font-size:11px">*Topics: Natural Language Processing, Machine Learning, Self-Supervised Learning, Transfer Learning*</sub>
   
<span style="color:#52ADC8">**Model Predictive Curiosity**</span> [\[paper\]](/files/2022-spr-psych240a-paper.pdf){:target="_blank"} [\[poster\]](/files/2022-spr-psych240a-poster.pdf){:target="_blank"} <br>
  <sub>*Final report and poster for Stanford's PSYCH 240A: Curiosity in Artificial Intelligence (Spring 2022)*<br>
  Proposed Model Predictive Curiosity (MPCu) to optimize for high-curiosity action values and enrich multi-object interactions in a Box2D environment.
  <!-- We proposed Model Predictive Curiosity (MPCu), a framework that backpropagates on curiosity values predicted by a forward dynamics model to select curiosity-maximizing actions. We demonstrated the capability of MPCu to optimize for high-curiosity action values and enrich multi-object interactions in Box2D environment. --> </sub> <br>
  <sub style="font-size:11px">*Topics: Curiosity-Based Models, Model-Based Reinforcement Learning, Representation Learning, Self-Supervised Learning*</sub>

<span style="color:#52ADC8">**Machine Learning-based platform using iBeacon Sensors for Product Location and Indoor Navigation to Improve Consumer Retail Experience**</span><br>
  <sub>*High school research engineering project (2018-2019)*<br>
  <!-- We trained an automatic speech recognition engine contextualized to Singaporean accents and terminology, which we incorporated into a mobile app to help consumers navigate local supermarkets with verbal queries. During testing, we combined the mobile app with a lattice formation of bluetooth low-energy sensors in a convenience store, which identified the user’s position relative to the intended item, then generated and displayed the shortest path. -->
  Trained an automatic speech recognition engine contextualized to Singaporean accents and terminology. Created a mobile app to help consumers navigate local supermarkets with verbal queries.</sub> <br>
  <sub style="font-size:11px">*Topics: Natural Language Processing, Speech Recognition, Speech-To-Text, Recommendation Systems, Shortest Path Generation, Indoor Geolocation, Bluetooth Sensor Systems*</sub>

Philosophy Papers
======
<span style="color:#52ADC8">**The Missing Piece: Dispelling the Mystery of Introspective Illusion**</span> [\[paper\]](/files/2023-spr-phil186-paper.pdf){:target="_blank"} <br>
  <sub>*Final paper for Stanford's PHIL 186: Philosophy of Mind (Spring 2023)*<br>
  I argue that explaining the potency of phenomenal illusions is the crucial missing piece for a sound illusionist theory. I present two main desiderata for a positive theory of illusionism by drawing connections to related theories of consciousness, namely global workspace theory (Dennett, 2001) and Buddhist philosophy. </sub> <br>
  <!-- I address the question of why illusionism, the view that phenomenal characteristics of mental states are illusory, is so hard to stomach. Beyond explaining how the illusion of phenomenality arises, a robust theory of illusionism must adequately explain the incredible strength of the illusion and the difficulty of freeing oneself from the grip of this enduring intuition. Frankish (2016) attempts to address the former but not the latter, and I argue that explaining the potency of phenomenal illusions is the crucial missing piece for a sound illusionist theory. I present two main desiderata for a positive theory of illusionism by drawing connections to related theories of consciousness, namely global workspace theory (Dennett, 2001) and Buddhist philosophy. </sub> <br> --> 
  <sub style="font-size:11px">*Topics: Consciousness, Illusionism, Higher-Order Thought Theory, Wittgenstein*</sub> 

<span style="color:#52ADC8">**Consciousness, Phenomenality, and the Representational Layer**</span> [\[paper\]](/files/2023-win-symsys202-paper.pdf){:target="_blank"} <br>
  <sub>*Final paper for Stanford's SYMSYS 202: Theories of Consciousness (Winter 2023)*<br>
  I propose that metacognition on top of the representational layer, beyond mere possession of representational states, is critical for consciousness, and explore how phenomenality is introduced in this process. I discuss the implications of this proposal for the functional and evolutionary roles of consciousness.</sub> <br>
  <!-- I propose that metacognition on top of the representational layer, beyond mere possession of representational states, is critical for consciousness. I also distinguish between lower-level sensory states used only as intermediates in perceptual processing (e.g., edge detection, shape from shading), and higher-level sensory states (outputs of perceptual processing), and explore the introduction of phenomenality in this process. I finally discuss the implications of the above proposals for the functional and evolutionary roles of consciousness.-->
  <sub style="font-size:11px">*Topics: Consciousness, Representationalism, Phenomenality, Higher-Order Thought Theory, Global Workspace Theory*</sub>

<span style="color:#52ADC8">**Philosophy of Mind: Wittgenstein, The Unconscious Mind, and Self-Knowledge**</span> [\[paper\]](/files/2022-fall-oxfordphil-essays.pdf){:target="_blank"} <br>
  <sub>*Collection of essays for OSPOXFRD 199: Philosophy of Mind (Fall 2022)*<br>
  A compilation of essays written for my Directed Reading in Philosophy of Mind, during my quarter abroad at Oxford. Each essay was written to prepare for biweekly tutorial discussions over the quarter. Topics included other minds, the privacy of experience, the unconscious mind, and self-knowledge.
  <!--The four essay titles and topics are: <br>
  Essay 1: Might your new philosophy tutor be a non-conscious ‘zombie’ for all you know? (Topic: Other Minds) <br>
  Essay 2: Might you see red where I see blue? (Topic: The Privacy of Experience) <br> 
  Essay 3: What is it to make the unconscious conscious? (Topic: The Unconscious Mind) <br> 
  Essay 4: How is knowledge of my own states of mind possible? (Topic: Self-Knowledge)-->
  </sub> <br>
  <sub style="font-size:11px">*Topics: Philosophy of Mind, Philosophy of Psychology, Wittgenstein, Private Language Argument, Consciousness, Self-Knowledge*</sub>

<span style="color:#52ADC8">**Predictive Processing: Efficiently processing high-dimensional, multimodal inputs**</span> [\[paper\]](/files/2022-spr-symsys205-paper.pdf){:target="_blank"} <br>
  <sub>*Final paper for Stanford's SYMSYS 205: The Philosophy and Science of Perception (Spring 2022)*<br>
  I explore the plausibility of the predictive processing framework over the standard bottom-up model of perception. I specifically explore efficient processing of high-dimensional multimodal inputs, where the qualitative space of each modality has unique dimensionality and structure.</sub> <br>
  <sub style="font-size:11px">*Topics: Multimodal Perception, Perceptual Cognition, Cognitive Processing*</sub>

<span style="color:#52ADC8">**Large Language Models: Intelligence, Understanding, and Intentionality**</span> [\[paper\]](/files/2021-fall-symsys207-paper.pdf){:target="_blank"} <br>
  <sub>*Final paper for Stanford's SYMSYS 207: Conceptual Issues in Cognitive Neuroscience (Fall 2021)*<br>
  I argue that modern large language models (LLMs) cannot achieve strong intelligence.
  </sub> <br>
  <sub style="font-size:11px">Author's Note (March 2023): This paper was written before the release of ChatGPT and GPT-4 (or GPT-x, depending on how far in the future you're reading this). In hindsight, I acknowledge this paper does not give sufficient credit to the impressive emergent behaviors observed in LLMs. However, my stance towards purely language-based models are still generally aligned with this paper. Another work that articulates views I am sympathetic to is [Shanahan (2022)](https://arxiv.org/pdf/2212.03551.pdf){:target="_blank"}. That said, there are many cool developments expanding on LLMs (like vision-language models, or grounded language models more generally) that I'm excited about! </sub> <br>
  <sub style="font-size:11px">*Topics: Natural Language Processing, Artificial Intelligence, Natural Language Understanding, Intentionality*</sub>

Mathematics Papers
======
<span style="color:#52ADC8">**Asymmetric Processes**</span> [\[paper\]](/files/2024-win-math101-paper2.pdf){:target="_blank"} <br>
  <sub>*Research paper for Stanford's MATH 101: Math Discovery Lab (Winter 2024)*<br>
  Analyzes two asymmetric Markov models: first where particle number stays constant, and second where particles enter and exit at certain rates. We study probability distributions of particle configurations at equilibrium, and properties such as average particle speed, irreducibility, aperiodicity, and double stochasticity. </sub> <br>
  <sub style="font-size:11px">*Topics: Markov Processes, Markov Chains, Probability Theory*</sub> 

<span style="color:#52ADC8">**Infinite Coin Tosses**</span> [\[paper\]](/files/2024-win-math101-paper1.pdf){:target="_blank"} <br>
  <sub>*Research paper for Stanford's MATH 101: Math Discovery Lab (Winter 2024)*<br>
  Explores cumulative distribution functions for infinite coin tosses, parameterized by the probability *p* of flipping heads. We graph the outcomes of simulated coin flips and study properties of the cumulative distribution function, analyzing its pathological behavior in terms of continuity, differentiability, and arc length. </sub> <br>
  <sub style="font-size:11px">*Topics: Probability Theory, Continuous Random Variables*</sub>

<span style="color:#52ADC8">**Hilbert's 10th Problem**</span> [\[paper\]](/files/2023-spr-phil152-paper.pdf){:target="_blank"} <br>
  <sub>*Research paper for Stanford's PHIL 152: Computability and Logic (Spring 2023)*<br>
  A proof of Hilbert's 10th Problem: determining the solvability of Diophantine equations over integers.
  </sub> <br>
  <sub style="font-size:11px">*Topics: Computability Theory*</sub>

Technical Reports
======
<span style="color:#52ADC8">**The Future of Human-Machine Interaction: Keeping Humans in the Loop**</span> [\[paper\]](/files/2022-fall-ospoxfrd29-paper.pdf){:target="_blank"} <br>
  <sub>*Final paper for Stanford's OSPOXFRD 29: Artificial Intelligence & Society (Fall 2022)* <br>
  The doomsday ending that humans will be demolished in the fierce intelligence competition with AI systems, while remarkably enduring, is a narrow view that distracts us from active measures that can be taken in the present day. I assert that a key tenet of AI development going forward should be keeping humans in the loop,, and evalute three technical research areas facilitating human-in-the-loop AI development and deployment. Distinguishing between non-immediate decision making (e.g., data analytics and robotics) and time-sensitive, safety-critical decision making (e.g., autonomous vehicles and aircraft) is key to understanding how to best facilitate human-AI collaboration in each case.</sub> <br>
  <sub style="font-size:11px">*Topics: Human-AI Interaction, AI Safety, Human-In-The-Loop Development, Decision-Making*</sub>

<span style="color:#52ADC8">**A Proposal for Building Safety Benchmarking Services in CAIS systems**</span> [\[paper\]](/files/2021-spr-seri-paper.pdf){:target="_blank"} <br>
  <sub>*Final report for Stanford Existential Risk Initiative's AI research program (Spring 2021)*<br>
  I propose a protocol encompassing safety benchmarking services for CAIS systems, ranging from pre-deployment safety benchmarks applied during model training to post-deployment safety benchmarks.</sub> <br>
  <!-- I propose a protocol encompassing safety benchmarking services for CAIS systems, ranging from pre-deployment safety benchmarks that are applied during model training (transparency tools, systems enabling robust and safe exploration, and performance when subject to adversarial policies) to post-deployment safety benchmarks that are applied during model application (monitoring systems and trip wires to ensure agent behavior is within safety standards and expectations). -->
  <sub style="font-size:11px">*Topics: AI Safety, Benchmarking Tools, AI Existential Risk*</sub>

<span style="color:#52ADC8">**Implications of the Comprehensive AI Services Framework on AI Safety Research**</span> [\[paper\]](/files/2021-win-seri-paper.pdf){:target="_blank"} <br>
  <sub>*Final report for Stanford Existential Risk Initiative's AI research program (Winter 2021)*<br>
  I argue that developing powerful AI systems in line with the Comprehensive AI Systems (CAIS) framework outlined in [*Reframing Superintelligence* (2019)](https://www.fhi.ox.ac.uk/wp-content/uploads/Reframing_Superintelligence_FHI-TR-2019-1.1-1.pdf){:target="_blank"} should be encouraged, due to the potential for enhanced safety measures to mitigate AI existential risk.</sub> <br>
  <sub style="font-size:11px">*Topics: AI Safety, Hierarchical Reinforcement Learning, AI Existential Risk*</sub>

<span style="color:#52ADC8">**Autonomous Vehicles: From Vision to Reality**</span> [\[paper\]](/files/2020-fall-cs56n-paper.pdf){:target="_blank"} <br>
  <sub>*Final paper for Stanford's CS 56N: Great Discoveries and Inventions in Computing, taught by Prof. John Hennessey (Fall 2020)*<br>
  We provide an analysis of current developments in autonomous driving, and discuss the technological hurdles that lie ahead in enhancing the security of autonomous systems and implementation of the system at scale.</sub> <br>
  <!-- We analyze challenges in consumer safety and securing autonomous systems against unwanted exploitation from a technical perspective, with additional commentary on the ethical and policy implications of these devlopments, to make projections about the future of autonomous vehicles. -->
  <sub style="font-size:11px">*Topics: Autononous Driving, Computer Vision, LiDAR/RADAR Sensor Systems, AI Safety*</sub>

<!-- <span style="color:#52ADC8">**When Worlds Collide: Challenges and Opportunities in Virtual Reality**</span> [\[paper\]](/files/2021-fall-history44q-paper.pdf){:target="_blank"} [\[publication\]](https://ojs.stanford.edu/ojs/index.php/sjfgss/article/view/2109){:target="_blank"} <br>
  <sub>*Final paper for Stanford's HISTORY 44Q: Gendered Innovations in Science, Medicine, Engineering, and Environment (Fall 2021)<br>
  Published in peer-reviewed journal, Embodied: The Stanford Undergraduate Journal of Feminist, Gender, and Sexuality Studies*<br>
  I explore virtual reality (VR) software applications that contain discriminatory content and promote harassment behaviors, and explore innovation processes and design choices to reframe VR applications so that they promote gender and social equality. </sub> <br>
  <sub style="font-size:11px">*Topics: Virtual Reality, Gendered Innovations*</sub>
  <!-- I explore virtual reality (VR) software applications that contain discriminatory content and promote harassment behaviors towards historically underrepresented communities, and identify innovation processes to reframe VR applications so that they promote gender and social equality. I also explore design choices in VR hardware that tend to exclude females. To address this, I propose a better sex balance in research participants is needed to rethink reference models for VR hardware, leading to more sex-sensitive VR headsets. -->
