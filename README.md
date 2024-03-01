# bipedal-robot-learning-collection 

+ This repo is a collection for high-quality robotics papers, with specialization on **bipedal robots** and **reinforcement learning** with **real robot experiments**. Papers on common learning techniques verified on quadrupedal robots, Bayesian optimization, CBF learning, etc., are temporarily excluded.       

+ I hope this can do a service for easy writing of literature review in papers. Abstracts or brief descriptions will later be added.     

+ Welcome to contribute by nominating new papers in Issues.    

  

##### In and after 2023, bold: highly recommended by me

---

- Singh, Rohan P., et al. "Learning bipedal walking for humanoids with current feedback." *IEEE Access* (2023).
- Radosavovic, Ilija, et al. "Learning Humanoid Locomotion with Transformers." *arXiv preprint arXiv:2303.03381* (2023). *I recommend reading v1 on top of v2 for more technical details despite some later-removed false claims"*
- Jeon, Se Hwan, et al. "Benchmarking potential based rewards for learning humanoid locomotion." *2023 IEEE International Conference on Robotics and Automation (ICRA)*. IEEE, 2023.
- C. -Y. Kuo, H. Shin and T. Matsubara, "Reinforcement Learning With Energy-Exchange Dynamics for Spring-Loaded Biped Robot Walking," in *IEEE Robotics and Automation Letters*, vol. 8, no. 10, pp. 6243-6250, Oct. 2023
- **Dao, Jeremy, Helei Duan, and Alan Fern. "Sim-to-Real Learning for Humanoid Box Loco-Manipulation." *arXiv preprint arXiv:2310.03191* (2023).**
- J. Ding, T. L. Lam, L. Ge, J. Pang and Y. Huang, "Safe and Adaptive 3-D Locomotion via Constrained Task-Space Imitation Learning," in *IEEE/ASME Transactions on Mechatronics*, vol. 28, no. 6, pp. 3029-3040, Dec. 2023
- Chen, Yu-Ming, Hien Bui, and Michael Posa. "Reinforcement Learning for Reduced-order Models of Legged Robots." *arXiv preprint arXiv:2310.09873* (2023).
- Smith, Laura, et al. "Learning and adapting agile locomotion skills by transferring experience." *arXiv preprint arXiv:2304.09834* (2023).
- Chun, Yeonghun, et al. "DDPG Reinforcement Learning Experiment for Improving the Stability of Bipedal Walking of Humanoid Robots." *2023 IEEE/SICE International Symposium on System Integration (SII)*. IEEE, 2023.
- Qin, Daoling, et al. "A Heuristics-Based Reinforcement Learning Method to Control Bipedal Robots." *International Journal of Humanoid Robotics* 2350013 (2023): 22.
- **Shi, F. *et al.* (2023). Reference-Free Learning Bipedal Motor Skills via Assistive Force Curricula. In: Billard, A., Asfour, T., Khatib, O. (eds) Robotics Research. ISRR 2022. Springer Proceedings in Advanced Robotics, vol 27. Springer, Cham.**
- Kim, Donghyeon, et al. "Torque-based Deep Reinforcement Learning for Task-and-Robot Agnostic Learning on Bipedal Robots Using Sim-to-Real Transfer." *arXiv preprint arXiv:2304.09434* (2023).
- **Duan, Helei, et al. "Learning Vision-Based Bipedal Locomotion for Challenging Terrain." *arXiv preprint arXiv:2309.14594* (2023).**
- **Li, Zhongyu, et al. "Reinforcement Learning for Versatile, Dynamic, and Robust Bipedal Locomotion Control." *arXiv preprint arXiv:2401.16889* (2024).**
- **Li, Zhongyu, et al. "Robust and versatile bipedal jumping control through multi-task reinforcement learning." *arXiv preprint arXiv:2302.09450* (2023).**
- Li, Yunfei, et al. "Learning Agile Bipedal Motions on a Quadrupedal Robot." *arXiv preprint arXiv:2311.05818* (2023).
- **Haarnoja, Tuomas, et al. "Learning agile soccer skills for a bipedal robot with deep reinforcement learning." *arXiv preprint arXiv:2304.13653* (2023).**
- Castillo, Guillermo A., et al. "Template model inspired task space learning for robust bipedal locomotion." *2023 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)*. IEEE, 2023.
- Cheng, Xuxin, et al. "Expressive Whole-Body Control for Humanoid Robots." arXiv preprint arXiv:2402.16796 (2024). 
- Zhang, Qiang, et al. "Whole-body Humanoid Robot Locomotion with Human Reference." arXiv preprint arXiv:2402.18294 (2024). 
- **Radosavovic, I., Zhang, B., Shi, B., Rajasegaran, J., Kamat, S., Darrell, T., … Malik, J. (2024). Humanoid Locomotion as Next Token Prediction. arXiv preprint arXiv: 2402.19469 (2024).** (Although the authors seem to have a weak RL baseline indicating they are bad at RL tuning, being able to scale with various dynamics-mismatching offline data source can be promising)    
- 



##### before 2023

------

+ Cassie and Digit   
  The cassie simulatoin environment: [link](https://github.com/osudrl/cassie-mujoco-sim)    
  - Xie, Zhaoming, et al. "Feedback control for cassie with deep reinforcement learning." 2018 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS). IEEE, 2018.  
  - Xie, Zhaoming, et al. "Learning locomotion skills for cassie: Iterative design and sim-to-real." Conference on Robot Learning. PMLR, 2020.   
  - Siekmann, Jonah, et al. "Learning Memory-Based Control for Human-Scale Bipedal Locomotion." Robotics science and systems. 2020.
  - Siekmann, Jonah, et al. "Blind bipedal stair traversal via sim-to-real reinforcement learning." Robotics science and systems. 2021.  
  - Green, Kevin, et al. "Learning spring mass locomotion: Guiding policies with a reduced-order model." IEEE Robotics and Automation Letters 6.2 (2021): 3926-3932.
  - Li, Zhongyu, et al. "Reinforcement learning for robust parameterized locomotion control of bipedal robots." 2021 IEEE International Conference on Robotics and Automation (ICRA). IEEE, 2021.   
  - Duan, Helei, et al. "Learning task space actions for bipedal locomotion." 2021 IEEE International Conference on Robotics and Automation (ICRA). IEEE, 2021.  
  - Siekmann, Jonah, et al. "Sim-to-real learning of all common bipedal gaits via periodic reward composition." 2021 IEEE International Conference on Robotics and Automation (ICRA). IEEE, 2021.  
  - Castillo, Guillermo A., et al. "Robust feedback motion policy design using reinforcement learning on a 3D digit bipedal robot." 2021 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS). IEEE, 2021.
  - Dao, Jeremy, et al. "Sim-to-Real Learning for Bipedal Locomotion Under Unsensed Dynamic Loads." 2022 IEEE International Conference on Robotics and Automation (ICRA). IEEE, 2022.  
  - Duan, Helei, et al. "Sim-to-Real Learning of Footstep-Constrained Bipedal Dynamic Walking." 2022 IEEE International Conference on Robotics and Automation (ICRA). IEEE, 2022.  
  - Rajan, Lokesh Krishna, et al. "Linear Policies are Sufficient to Realize Robust Bipedal Walking on Challenging Terrains." IEEE Robotics and Automation Letters (2022).  
  - Duan, Helei, et al. "Learning Dynamic Bipedal Walking Across Stepping Stones." arXiv preprint arXiv:2205.01807 (2022). 
  - Kumar, Ashish, et al. "Adapting Rapid Motor Adaptation for Bipedal Robots." arXiv preprint arXiv:2205.15299 (2022).  
  - Batke, Ryan, et al. "Optimizing Bipedal Maneuvers of Single Rigid-Body Models for Reinforcement Learning." arXiv preprint arXiv:2207.04163 (2022).   
  - Yu, Fangzhou, et al. "Dynamic Bipedal Maneuvers through Sim-to-Real Reinforcement Learning." arXiv preprint arXiv:2207.07835 (2022).  
  - More to be added
+ Darwin OPx  
  - Yu, Wenhao, et al. "Sim-to-real transfer for biped locomotion." 2019 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS). IEEE, 2019.
  - Bloesch, Michael, et al. "Towards Real Robot Learning in the Wild: A Case Study in Bipedal Locomotion." Conference on Robot Learning. PMLR, 2022.
  - Bohez, Steven, et al. "Imitate and Repurpose: Learning Reusable Robot Movement Skills From Human and Animal Behaviors." arXiv preprint arXiv:2203.17138 (2022).
  - Masuda, Shimpei, and Kuniyuki Takahashi. "Sim-to-Real Learning of Robust Compliant Bipedal Locomotion on Torque Sensor-Less Gear-Driven Humanoid." arXiv preprint arXiv:2204.03897 (2022).  
  - Byravan, Arunkumar, et al. "NeRF2Real: Sim2real Transfer of Vision-guided Bipedal Motion Skills using Neural Radiance Fields." arXiv preprint arXiv:2210.04932 (2022).  
  - More to be added
+ Other Platforms  
  - Li, Tianyu, et al. "Using deep reinforcement learning to learn high-level policies on the atrias biped." 2019 International Conference on Robotics and Automation (ICRA). IEEE, 2019.
  - Rodriguez, Diego, and Sven Behnke. "DeepWalk: Omnidirectional bipedal gait by deep reinforcement learning." 2021 IEEE International Conference on Robotics and Automation (ICRA). IEEE, 2021.   
  - Yu, Chen, and Andre Rosendo. "Multi-Modal Legged Locomotion Framework with Automated Residual Reinforcement Learning." arXiv preprint arXiv:2202.12033 (2022).  
  - Singh, Rohan Pratap, et al. "Learning Bipedal Walking On Planned Footsteps For Humanoid Robots." arXiv preprint arXiv:2207.12644 (2022).   
  - Gams, A., Petrič, T., Nemec, B. *et al.* Manipulation Learning on Humanoid Robots. *Curr Robot Rep* **3**, 97–109 (2022). https://doi.org/10.1007/s43154-022-00082-9
  - Shi, Fan, et al. "Learning agile hybrid whole-body motor skills for thruster-aided humanoid robots." *2022 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)*. IEEE, 2022.
