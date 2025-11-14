# Research

## Overview

Our research group is dedicated to advancing the frontiers of embodied AI, aiming to build intelligent agents capable of autonomous perception, decision-making, and interaction within open, dynamic, and complex physical environments. We focus on transcending the limitations of traditional static perception by exploring the "perception–decision–action–feedback" closed loop. Our goal is to develop more general, proactive, and efficient embodied AI systems that can flexibly adapt to the complex and ever-changing real world, achieving general, active, efficient environmental perception and precise navigation.

Our research efforts primarily revolve around the following three closely interconnected directions:

1.  **Embodied Perception**
    Exploring how agents can acquire higher-quality perceptual information through active interaction with the environment, continuously learn new knowledge, and achieve efficient, selective perception based on task requirements. Core research directions include active visual perception, continual learning for perception, and task-driven visual perception.

2.  **Visual Navigation**
    Investigating how agents understand natural language instructions, perform spatial reasoning, predict dynamic object motion, understand environmental affordances, and ultimately plan safe and efficient movement paths in complex scenes. Simultaneously, we focus on how agents can adapt to unknown environments through evolutionary learning.

3.  **Cross-Disciplinary Exploration**
    Integrating cutting-edge technologies such as world models, vision-language navigation, and vision-language-action models to promote the development of next-generation embodied AI systems that are safer, more reliable, and possess zero-shot generalization capabilities.

---

## Subpage 1: Embodied Perception

Embodied perception breaks the framework of traditional static image recognition by integrating the perceptual process into the interactive loop between the agent and the environment. This allows the agent to dynamically adjust its perception strategies according to task demands, shifting from "passively receiving information" to "actively acquiring information." Our objective is to endow agents with generalized perception capabilities, making them adaptable to the diverse requirements of multi-task scenarios while balancing perception efficiency and robustness.

### Core Technical Directions

**Active Visual Perception**
Addressing the limitations of passive perception, such as restricted viewpoints and incomplete information, we research how to optimize information acquisition by actively controlling sensor movement. This aims to obtain more complete and clearer observations of targets, enhancing the robustness of recognition and interaction.

**Continual Perceptual Learning**
We study how agents can effectively learn new knowledge and avoid "catastrophic forgetting" of old knowledge when continuously encountering new categories and tasks, gradually building general perception and lifelong learning capabilities.

**Task-Driven Visual Perception**
Addressing the need for efficient perception in complex embodied tasks, we investigate how to trim redundant information and achieve precise perception based on task objectives. By adaptively adjusting the computational resources and regions of interest of the perception system, we aim to balance perception speed and accuracy.

---

## Subpage 2: Visual Navigation

Visual navigation in complex scenes is a core capability of embodied AI. We are committed to researching how agents, relying solely on visual sensors, can understand high-level instructions (e.g., natural language) and plan and execute safe, efficient movement in open scenes filled with uncertainties (e.g., complex layouts, dynamic pedestrians, unknown traversability). The core challenge lies in building navigation systems that can integrate semantic understanding, motion prediction, and environmental affordance inference, enabling agents to achieve autonomous path planning in unknown or dynamic environments.

### Core Technical Directions

**Semantic Understanding and Spatial Reasoning**
We explore how agents parse the spatial semantics within natural language instructions and ground them to visual observations, performing spatial reasoning by "building a mental map." We aim to break through the limitations of the first-person perspective and construct cross-modal, multi-scale spatial representation and reasoning capabilities.

**Motion Prediction**
To enable safe navigation in dynamic environments, agents need the ability to predict the future trajectories of surrounding agents (e.g., pedestrians, vehicles).

**Affordance Inference**
We research how agents understand the "affordances" of the environment—the possibilities for action that the environment offers them—covering terrain traversability, object interactivity, and the functional properties of target objects.

**Evolutionary Learning for Navigation**
We explore how agents can autonomously evolve their navigation capabilities during the testing phase (i.e., when performing tasks in new environments) through online adaptation or memory-reflection mechanisms, to overcome the distribution shift between training and testing scenarios.

---

## Subpage 3: Other Research

Building upon the core technologies of embodied perception and navigation, we further expand into related research areas such as multimodal fusion and system deployment. We aim to construct a complete research chain from "basic theory – core technology – practical application," promoting the transition of embodied AI technology from the laboratory to real-world scenarios.

### Core Research Topics

**Integration of Multimodal Large Models and Embodied AI**
We explore the deep fusion mechanisms of multimodal information (e.g., language, vision, spatial) to enhance agents' understanding and decision-making capabilities. Research directions include MLLM-based instruction parsing for vision-language navigation, cross-modal map representation learning, and natural language-driven fine-grained perception. Leveraging the knowledge transfer capabilities of multimodal large models, we strive to reduce system training costs and enhance zero-shot generalization capabilities.

**World Model Pre-training and Safe Planning**
We focus on agents' capabilities for environmental modeling and prediction, researching pre-training methods for general world models (e.g., the PreLAR framework) to enable accurate modeling of environmental dynamics and physical rules. Combined with reinforcement learning, we implement safe and feasible trajectory planning that ensures navigation efficiency while satisfying multiple constraints such as obstacle avoidance, speed limits, and comfort, providing key technical support for safety-critical scenarios like autonomous driving.