---
layout: research_detail
title: Visual Navigation
area_id: visual-navigation
permalink: /research/visual-navigation/
description: "Visual navigation in complex scenes is a core capability of embodied AI. We are committed to researching how agents, relying solely on visual sensors, can understand high-level instructions (e.g., natural language) and plan and execute safe, efficient movement in open scenes filled with uncertainties (e.g., complex layouts, dynamic pedestrians, unknown traversability). The core challenge lies in building navigation systems that can integrate semantic understanding, motion prediction, and environmental affordance inference."
content_groups:
  - title: "Semantic Understanding and Spatial Reasoning"
    # image: "/images/research_img/semantic_spatial.jpg"
    caption: "Parsing spatial semantics and grounding them to visual observations."
    description: |
      We explore how agents parse the spatial semantics within natural language instructions and ground them to visual observations, performing spatial reasoning by 'building a mental map.' We aim to break through the limitations of the first-person perspective and construct cross-modal, multi-scale spatial representation and reasoning capabilities.

      Our research enables agents to understand complex instructions like 'go to the red chair next to the window' and navigate accordingly.

  - title: "Motion Prediction"
    # image: "/images/research_img/motion_prediction.jpg"
    caption: "Predicting future trajectories of surrounding agents."
    description: |
      To enable safe navigation in dynamic environments, agents need the ability to predict the future trajectories of surrounding agents (e.g., pedestrians, vehicles). Our research develops algorithms that can anticipate movement patterns and adjust navigation strategies accordingly.

      This capability is crucial for applications in crowded environments where collision avoidance is essential.

  - title: "Affordance Inference"
    # image: "/images/research_img/affordance.jpg"
    caption: "Understanding environmental possibilities for action."
    description: |
      We research how agents understand the 'affordances' of the environment—the possibilities for action that the environment offers them—covering terrain traversability, object interactivity, and the functional properties of target objects.

      This understanding enables agents to make informed decisions about which paths are navigable and which objects can be interacted with.

  - title: "Evolutionary Learning for Navigation"
    # image: "/images/research_img/evolutionary.jpg"
    caption: "Autonomous evolution of navigation capabilities."
    description: |
      We explore how agents can autonomously evolve their navigation capabilities during the testing phase (i.e., when performing tasks in new environments) through online adaptation or memory-reflection mechanisms, to overcome the distribution shift between training and testing scenarios.

      This approach enables agents to continuously improve their performance in novel environments without requiring extensive retraining.

---