# bipedal-robot-learning-collection 

+ This repo is a collection for high-quality robotics papers, with specialization on **bipedal locomotion** and **reinforcement learning** with **real robot experiments**. I hope this can do a service for easy writing of literature review in papers. 

+ I separate the papers into the different categories: `Balance`, `Adaptation`, `Skillful`, `Human2Humanoid`. Welcome to contribute by nominating new papers in Issues. Last update: Jan 12 2025.    

+ For all relevant papers before CoRL 2024, there is a complete list in branch `archive/beforeCoRL2024`. Due to the explosive increase in the number of papers, I am not maintaining a full list of all the papers.
  

## Balance
This category is named after Marc Raibert's book, _Legged Robots that Balance_. The papers in this category makes the main line of bipedal locomotion: to balance on any terrain in the wild. In this line, the focus is to learn the locomotion capability, and there are three subtopics: 1) hybrid methods with model-based heuristics, 2) end-to-end learning, and 3) engineering choices that matter. For studies on sim-to-real transfer using POMDP formulations, please refer to the `Adaptation` category. 

+ Li et al. Using deep reinforcement learning to learn high-level policies on the atrias biped. ICRA 2019.

+ Xie et al. Learning locomotion skills for cassie: Iterative design and sim-to-real. CoRL 2020.

+ Kevin et al. Learning spring mass locomotion: Guiding policies with a reduced-order model. RAL 2021.

+ Rodriguez et al. DeepWalk: Omnidirectional bipedal gait by deep reinforcement learning. ICRA 2021.

+ Li et al. Reinforcement learning for robust parameterized locomotion control of bipedal robots. ICRA 2021.

+ Duan et al. Learning task space actions for bipedal locomotion. ICRA 2021.

+ Siekmann et al. Sim-to-real learning of all common bipedal gaits via periodic reward composition. ICRA 2021.

+ Castillo et al. Robust feedback motion policy design using reinforcement learning on a 3D digit bipedal robot. IROS 2021.

+ Duan et al. Sim-to-Real Learning of Footstep-Constrained Bipedal Dynamic Walking. ICRA 2022.

+ Rajan et al. Linear Policies are Sufficient to Realize Robust Bipedal Walking on Challenging Terrains. RAL 2022.

+ Duan et al. Learning Dynamic Bipedal Walking Across Stepping Stones. IROS 2022.

+ Michael et al. Towards Real Robot Learning in the Wild: A Case Study in Bipedal Locomotion. CoRL 2022.

+ Batke et al. Optimizing Bipedal Maneuvers of Single Rigid-Body Models for Reinforcement Learning. Humanoids 2022.

+ Singh et al. Learning Bipedal Walking On Planned Footsteps For Humanoid Robots. Humanoids 2022.

+ Shi et al. Reference-Free Learning Bipedal Motor Skills via Assistive Force Curricula. ISRR 2022.

+ Heon et al. Benchmarking potential based rewards for learning humanoid locomotion. ICRA 2023.

+ Castillo et al. Template model inspired task space learning for robust bipedal locomotion. IROS 2023.

+ Kim et al. Torque-based Deep Reinforcement Learning for Task-and-Robot Agnostic Learning on Bipedal Robots Using Sim-to-Real Transfer. RAL 2023.

+ Duan et al. Learning vision-based bipedal locomotion for challenging terrain. ICRA 2024.

+ Chen et al. Reinforcement learning for reduced-order models of legged robots. ICRA 2024.

+ van Marum et al. Revisiting Reward Design and Evaluation for Robust Humanoid Standing and Walking. IROS 2024.

+ My own work. Learning Generalized Legged Locomotion. to be released 2024/2025.


## Adaptation
Real-world deployments often face the uncertainties in robot dynamics and sensing. Therefore, a wise way is to be adaptive to these uncertainties, which is mostly achieved by utilizing the history data. Some of the works can focus on skills, but they stand out with decent sim-to-real transfer via adaptation.

+ Yu et al. Sim-to-real transfer for biped locomotion. IROS 2019.

+ Siekmann et al. Learning Memory-Based Control for Human-Scale Bipedal Locomotion. RSS 2020.

+ Siekmann et al. Blind bipedal stair traversal via sim-to-real reinforcement learning. RSS 2021.

+ Dao et al. Sim-to-Real Learning for Bipedal Locomotion Under
Unsensed Dynamic Loads. ICRA 2022.  

+ Kumar et al. Adapting Rapid Motor Adaptation for Bipedal Robots. IROS 2022.  

+ Li et al. Robust and versatile bipedal jumping control through multi-task reinforcement learning. RSS 2023.

+ Li et al. Reinforcement Learning for Versatile, Dynamic, and Robust Bipedal Locomotion Control. IJRR 2024.

+ Gu et al. Advancing Humanoid Locomotion: Mastering Challenging Terrains with Denoising World Model Learning. RSS 2024.

+ Wang et al. Toward Understanding Key Estimation in Learning Robust Humanoid Locomotion. IROS 2024.

+ Radosavovic et al. Real-world humanoid locomotion with reinforcement learning. Science Robotics 2024.

+ Radosavovic et al. Learning Humanoid Locomotion over Challenging Terrain. arXiv 2024.

+ Long et al. Learning Humanoid Locomotion with Perceptive Internal Model. arXiv 2024.

## Skillful
The community is not satisfied with only balancing. We want loco-manipulation, we want parkour. A special focus here is how to design the rewards, and the framework, on top of sim-to-real transfer.

+ Shi et al. Learning agile hybrid whole-body motor skills for thruster-aided humanoid robots. IROS 2022. 

+ Yu et al. Dynamic Bipedal Maneuvers through Sim-to-Real Reinforcement Learnin. Humanoids 2022.

+ Dao et al. Sim-to-Real Learning for Humanoid Box Loco-Manipulation. ICRA 2024.

+ Haarnoja et al. Learning agile soccer skills for a bipedal robot with deep reinforcement learning. Science Robotics 2024.

+ Dhruva et al. Learning Robot Soccer from Egocentric Vision with Deep Reinforcement Learning. CoRL 2024.

+ Zhang et al. WoCoCo: Learning Whole-Body Humanoid Control with Sequential Contacts. CoRL 2024.

+ Zhuang et al. Humanoid Parkour Learning. CoRL 2024.

## Human2Humanoid  
Humanoids share the human morph, so a natural idea is to using human data for humanoid control. This can involve two types of works: 1) make humanoids move like humans, and 2) help humans teleoperate humanoids and collect data.

+ Bohez et al. Imitate and Repurpose: Learning Reusable Robot Movement Skills From Human and Animal Behaviors. arXiv 2022.

+ Tang et al. HumanMimic: Learning Natural Locomotion and Transitions for Humanoid Robot via Wasserstein Adversarial Imitation. ICRA 2024.

+ Cheng et al. Expressive Whole-Body Control for Humanoid Robots. RSS 2024.

+ Zhang et al. Whole-body Humanoid Robot Locomotion with Human Reference. IROS 2024.

+ He et al. Learning Human-to-Humanoid Real-Time Whole-Body Teleoperation. IROS 2024.

+ He et al. OmniH2O: Universal and Dexterous Human-to-Humanoid Whole-Body Teleoperation and Learning. CoRL 2024.

+ Fu et al. HumanPlus: Humanoid Shadowing and Imitation from Humans. CoRL 2024.

+ Dugar et al. Learning Multi-Modal Whole-Body Control for Real-World Humanoid Robots. arXiv 2024.

+ He et al. Hover: Versatile neural whole-body controller for humanoid robots. arXiv 2024. 

+ Lu et al. Mobile-television: Predictive motion priors for humanoid whole-body control. arXiv 2024.