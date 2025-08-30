# bipedal-robot-learning-collection 

+ This repo is a collection for high-quality robotics papers, with specialization on **bipedal locomotion** and **reinforcement learning** with **real robot experiments**. I hope this can do a service for easy writing of literature review in papers. 

+ I separate the papers into the different categories: `Balance`, `Adaptation`, `Skillful`, `Human2Humanoid`. Welcome to contribute by nominating new papers in Issues. Last update: June 21 2025.    

+ For all relevant papers before CoRL 2024, there is a complete list in branch `archive/beforeCoRL2024`. Due to the explosive increase in the number of papers, I am not maintaining a full list of all the papers.
  

## Balance
This category is named after Marc Raibert's book, _Legged Robots that Balance_. The papers in this category makes the main line of bipedal locomotion: to balance on any terrain in the wild. In this line, the focus is to learn the locomotion capability, and there are three subtopics: 1) hybrid methods with model-based heuristics, 2) end-to-end learning, and 3) hardware and algorithmic engineering choices that matter. For studies on sim-to-real transfer using POMDP formulations, please refer to the `Adaptation` category. 

+ Li et al. Using deep reinforcement learning to learn high-level policies on the atrias biped. ICRA 2019. [[paper](https://arxiv.org/pdf/1809.10811)]

+ Xie et al. Learning locomotion skills for cassie: Iterative design and sim-to-real. CoRL 2020. [[paper](https://proceedings.mlr.press/v100/xie20a/xie20a.pdf)]

+ Kevin et al. Learning spring mass locomotion: Guiding policies with a reduced-order model. RAL 2021. [[paper](https://arxiv.org/pdf/2010.11234)]

+ Rodriguez et al. DeepWalk: Omnidirectional bipedal gait by deep reinforcement learning. ICRA 2021. [[paper](https://www.ais.uni-bonn.de/papers/ICRA_2021_Rodriguez.pdf)]

+ Li et al. Reinforcement learning for robust parameterized locomotion control of bipedal robots. ICRA 2021. [[paper](https://arxiv.org/pdf/2103.14295)] [[video](https://www.youtube.com/watch?v=goxCjGPQH7U)]

+ Duan et al. Learning task space actions for bipedal locomotion. ICRA 2021. [[paper](https://arxiv.org/pdf/2011.04741)]

+ Siekmann et al. Sim-to-real learning of all common bipedal gaits via periodic reward composition. ICRA 2021. [[paper](https://arxiv.org/pdf/2011.01387)]

+ Castillo et al. Robust feedback motion policy design using reinforcement learning on a 3D digit bipedal robot. IROS 2021. [[paper](https://arxiv.org/pdf/2103.15309)] 

+ Duan et al. Sim-to-Real Learning of Footstep-Constrained Bipedal Dynamic Walking. ICRA 2022. [[paper](https://arxiv.org/pdf/2203.07589)]  

+ Rajan et al. Linear Policies are Sufficient to Realize Robust Bipedal Walking on Challenging Terrains. RAL 2022. [[paper](https://arxiv.org/pdf/2109.12665)]

+ Duan et al. Learning Dynamic Bipedal Walking Across Stepping Stones. IROS 2022. [[paper](https://arxiv.org/pdf/2205.01807)]   

+ Michael et al. Towards Real Robot Learning in the Wild: A Case Study in Bipedal Locomotion. CoRL 2022. [[paper](https://proceedings.mlr.press/v164/bloesch22a/bloesch22a.pdf)] [[video](https://sites.google.com/view/op3-vision-wild)]

+ Batke et al. Optimizing Bipedal Maneuvers of Single Rigid-Body Models for Reinforcement Learning. Humanoids 2022. [[paper](https://arxiv.org/pdf/2207.04163)]

+ Singh et al. Learning Bipedal Walking On Planned Footsteps For Humanoid Robots. Humanoids 2022. [[paper](https://arxiv.org/pdf/2207.12644)]

+ Shi et al. Reference-Free Learning Bipedal Motor Skills via Assistive Force Curricula. ISRR 2022. [[paper](https://link.springer.com/chapter/10.1007/978-3-031-25555-7_21)] [[video](https://fanshi14.github.io/me/isrr22)]

+ Heon et al. Benchmarking potential based rewards for learning humanoid locomotion. ICRA 2023. [[paper](https://arxiv.org/pdf/2307.10142)] 

+ Castillo et al. Template model inspired task space learning for robust bipedal locomotion. IROS 2023. [[paper](https://arxiv.org/pdf/2309.15442)]

+ Kim et al. Torque-based Deep Reinforcement Learning for Task-and-Robot Agnostic Learning on Bipedal Robots Using Sim-to-Real Transfer. RAL 2023. [[paper](https://arxiv.org/pdf/2304.09434)]

+ Duan et al. Learning vision-based bipedal locomotion for challenging terrain. ICRA 2024. [[paper](https://arxiv.org/pdf/2309.14594)]

+ Chen et al. Reinforcement learning for reduced-order models of legged robots. ICRA 2024. [[paper](https://arxiv.org/pdf/2310.09873)] [[video](https://sites.google.com/view/ymchen/research/rl-for-roms)] [[code](https://github.com/yminchen/rom-mpc-rl)]

+ van Marum et al. Revisiting Reward Design and Evaluation for Robust Humanoid Standing and Walking. IROS 2024. [[paper](https://arxiv.org/pdf/2404.19173)]

+ Liao et al. Berkeley Humanoid: A Research Platform for Learning-based Control. arXiv 2024. [[paper](https://berkeley-humanoid.com/static/berkeley_humanoid.pdf)] [[website](https://berkeley-humanoid.com/)] [[code](https://github.com/HybridRobotics/isaac_berkeley_humanoid)]

+ Xia et al. The Duke humanoid: Design and control for energy efficient bipedal locomotion using passive dynamics. arXiv 2024. [[paper](https://arxiv.org/pdf/2409.19795)] [[website](http://www.generalroboticslab.com/blogs/blog/2024-09-29-dukehumanoidv1/index.html)] [[code](https://github.com/generalroboticslab/DukeHumanoidv1)]

+ Xue et al. HugWBC: A Unified and General Humanoid Whole-Body Controller for Fine-Grained Locomotion. RSS 2025. [[paper](https://arxiv.org/pdf/2502.03206)] [[website](https://hugwbc.github.io/)]

+ He et al. Attention-Based Map Encoding for Learning Generalized Legged Locomotion. Science Robotics 2025. [[paper](https://www.science.org/stoken/author-tokens/ST-2851/full)]   



## Adaptation
Real-world deployments often face the uncertainties in robot dynamics and sensing. Therefore, a wise way is to be adaptive to these uncertainties, which is mostly achieved by utilizing the history data. Some of the works can focus on skills, but they stand out with decent sim-to-real transfer via adaptation.

+ Yu et al. Sim-to-real transfer for biped locomotion. IROS 2019. [[paper](https://arxiv.org/pdf/1903.01390)]

+ Siekmann et al. Learning Memory-Based Control for Human-Scale Bipedal Locomotion. RSS 2020. [[paper](https://arxiv.org/pdf/2006.02402)]

+ Siekmann et al. Blind bipedal stair traversal via sim-to-real reinforcement learning. RSS 2021. [[paper](https://arxiv.org/pdf/2105.08328)]

+ Dao et al. Sim-to-Real Learning for Bipedal Locomotion Under Unsensed Dynamic Loads. ICRA 2022. [[paper](https://arxiv.org/pdf/2204.04340)]

+ Kumar et al. Adapting Rapid Motor Adaptation for Bipedal Robots. IROS 2022. [[paper](https://arxiv.org/pdf/2205.15299)] [[video](https://ashish-kmr.github.io/a-rma/)]

+ Li et al. Robust and versatile bipedal jumping control through multi-task reinforcement learning. RSS 2023. [[paper](https://arxiv.org/pdf/2302.09450)]

+ Li et al. Reinforcement Learning for Versatile, Dynamic, and Robust Bipedal Locomotion Control. IJRR 2024. [[paper](https://arxiv.org/pdf/2401.16889)] [[video](https://www.youtube.com/watch?v=sQEnDbET75g)]

+ Gu et al. Advancing Humanoid Locomotion: Mastering Challenging Terrains with Denoising World Model Learning. RSS 2024. [[paper](https://arxiv.org/pdf/2408.14472)]

+ Wang et al. Toward Understanding Key Estimation in Learning Robust Humanoid Locomotion. IROS 2024. [[paper](https://arxiv.org/pdf/2403.05868)]

+ Radosavovic et al. Real-world humanoid locomotion with reinforcement learning. Science Robotics 2024. [[paper](https://arxiv.org/pdf/2303.03381)] [[website](https://learning-humanoid-locomotion.github.io/)]

+ Radosavovic et al. Learning Humanoid Locomotion over Challenging Terrain. arXiv 2024. [[paper](https://arxiv.org/pdf/2410.03654)] [[website](https://humanoid-challenging-terrain.github.io/)]

+ Long et al. Learning Humanoid Locomotion with Perceptive Internal Model. arXiv 2024. [[paper](https://arxiv.org/pdf/2411.14386)] [[website](https://junfeng-long.github.io/PIM/)]

## Skillful
The community is not satisfied with only balancing. We want loco-manipulation, we want parkour. A special focus here is how to design the rewards, and the framework, on top of sim-to-real transfer.

+ Shi et al. Learning agile hybrid whole-body motor skills for thruster-aided humanoid robots. IROS 2022. [[paper](https://ieeexplore.ieee.org/abstract/document/9981974)] [[video](https://fanshi14.github.io/me/ral22)]

+ Yu et al. Dynamic Bipedal Maneuvers through Sim-to-Real Reinforcement Learnin. Humanoids 2022. [[paper](https://arxiv.org/pdf/2207.07835)]

+ Dao et al. Sim-to-Real Learning for Humanoid Box Loco-Manipulation. ICRA 2024. [[paper](https://arxiv.org/pdf/2310.03191)]

+ Haarnoja et al. Learning agile soccer skills for a bipedal robot with deep reinforcement learning. Science Robotics 2024. [[paper](https://arxiv.org/pdf/2304.13653)] [[website](https://sites.google.com/view/op3-soccer)]

+ Dhruva et al. Learning Robot Soccer from Egocentric Vision with Deep Reinforcement Learning. CoRL 2024. [[paper](https://arxiv.org/pdf/2405.02425)] [[website](https://sites.google.com/view/vision-soccer)]

+ Zhang et al. WoCoCo: Learning Whole-Body Humanoid Control with Sequential Contacts. CoRL 2024. [[paper](https://arxiv.org/pdf/2406.06005)] [[website](https://lecar-lab.github.io/wococo/)] [[code](https://github.com/LeCAR-Lab/wococo)]

+ Zhuang et al. Humanoid Parkour Learning. CoRL 2024. [[paper](https://arxiv.org/pdf/2406.10759)] [[website](https://humanoid4parkour.github.io/)]

+ Pandit et al. Learning Decentralized Multi-Biped Control for Payload Transport. CoRL 2024. [[paper](https://arxiv.org/pdf/2406.17279)] [[website](https://decmbc.github.io/)] [[code](https://github.com/osudrl/decentralized_multibiped_controller)]

+ He et al. Learning getting-up policies for real-world humanoid robots. RSS 2025. [[paper](https://arxiv.org/abs/2502.12152)] [[website](https://humanoid-getup.github.io/)] [[code](https://github.com/RunpeiDong/humanup)]  

+ Huang et al. Learning Humanoid Standing-up Control across Diverse Postures. RSS 2025. [[paper](https://arxiv.org/abs/2502.08378)] [[website](https://taohuang13.github.io/humanoid-standingup.github.io/)] [[code](https://github.com/OpenRobotLab/HoST)]    

+ Zhang et al. FALCON: Learning Force-Adaptive Humanoid Loco-Manipulation. arXiv 2025. [[paper](https://arxiv.org/abs/2505.06776)] [[website](https://lecar-lab.github.io/falcon-humanoid/)] [[code](https://github.com/LeCAR-Lab/FALCON/)]   

+ Xue et al. LeVERB: Humanoid Whole-Body Control with Latent Vision-Language Instruction. arXiv 2025. [[paper](https://arxiv.org/abs/2506.13751)]

+ Li et al. Hold My Beer: Learning Gentle Humanoid Locomotion and End-Effector Stabilization Control. arXiv 2025. [[paper](https://lecar-lab.github.io/SoFTA/resources/Main-Paper.pdf)] [[website](https://lecar-lab.github.io/SoFTA/)]

+ Xie et al. KungfuBot: Physics-Based Humanoid Whole-Body Control for Learning Highly-Dynamic Skills. arXiv 2025. [[paper](https://arxiv.org/abs/2506.12851)] [[website](https://kungfu-bot.github.io/)]

## Human2Humanoid  
Humanoids share the human morph, so a natural idea is to using human data for humanoid control. This can involve two types of works: 1) make humanoids move like humans, and 2) help humans teleoperate humanoids and collect data.

+ Bohez et al. Imitate and Repurpose: Learning Reusable Robot Movement Skills From Human and Animal Behaviors. arXiv 2022. [[paper](https://arxiv.org/pdf/2203.17138)] [[website](https://sites.google.com/view/robot-npmp)]

+ Tang et al. HumanMimic: Learning Natural Locomotion and Transitions for Humanoid Robot via Wasserstein Adversarial Imitation. ICRA 2024. [[paper](https://arxiv.org/pdf/2309.14225)] [[video](https://www.youtube.com/watch?v=sdM11yHpzi8)]

+ Cheng et al. Expressive Whole-Body Control for Humanoid Robots. RSS 2024. [[paper](https://arxiv.org/pdf/2402.16796)] [[website](https://expressive-humanoid.github.io/)] [[code](https://github.com/chengxuxin/expressive-humanoid)]

+ Zhang et al. Whole-body Humanoid Robot Locomotion with Human Reference. IROS 2024. [[paper](https://arxiv.org/pdf/2402.18294)] [[video](https://www.youtube.com/watch?v=7hK2ySYBa1I)]

+ He et al. Learning Human-to-Humanoid Real-Time Whole-Body Teleoperation. IROS 2024. [[paper](https://arxiv.org/pdf/2403.04436)] [[website](https://human2humanoid.com/)] [[code](https://github.com/LeCAR-Lab/human2humanoid)]

+ He et al. OmniH2O: Universal and Dexterous Human-to-Humanoid Whole-Body Teleoperation and Learning. CoRL 2024. [[paper](https://arxiv.org/pdf/2406.08858)] [[website](https://omni.human2humanoid.com/)] [[code](https://github.com/LeCAR-Lab/human2humanoid)]

+ Fu et al. HumanPlus: Humanoid Shadowing and Imitation from Humans. CoRL 2024. [[paper](https://arxiv.org/pdf/2406.10454)] [[website](https://humanoid-ai.github.io/)] [[code](https://github.com/MarkFzp/humanplus)]

+ Dugar et al. Learning Multi-Modal Whole-Body Control for Real-World Humanoid Robots. arXiv 2024. [[paper](https://arxiv.org/pdf/2408.07295)] [[website](https://masked-humanoid.github.io/mhc/)]

+ He et al. Hover: Versatile neural whole-body controller for humanoid robots. ICRA 2025. [[paper](https://hover-versatile-humanoid.github.io/resources/HOVER_paper.pdf)] [[website](https://hover-versatile-humanoid.github.io/)] [[code](https://github.com/NVlabs/HOVER/)]

+ Lu et al. Mobile-television: Predictive motion priors for humanoid whole-body control. ICRA 2025. [[paper](https://mobile-tv.github.io/resources/pmp.pdf)] [[website](https://mobile-tv.github.io/)] [[code](https://github.com/OpenTeleVision/TeleVision)]

+ Ji et al. ExBody2: Advanced Expressive Humanoid Whole-Body Control. arXiv 2024. [[paper](https://arxiv.org/pdf/2412.13196)] [[website](https://exbody2.github.io/)]

+ He et al. ASAP: Aligning Simulation and Real-World Physics for Learning Agile Humanoid Whole-Body Skills. RSS 2025. [[paper](https://arxiv.org/pdf/2502.01143)] [[website](https://agile.human2humanoid.com/)] [[code](https://github.com/LeCAR-Lab/ASAP)]

+ Zhuang et al. Embrace Collisions: Humanoid Shadowing for Deployable Contact-Agnostics Motions. arXiv 2025. [[paper](https://arxiv.org/pdf/2502.01465)] [[website](https://project-instinct.github.io/)]

+ Li et al. AMO: Adaptive Motion Optimization for Hyper-Dexterous Humanoid Whole-Body Control. RSS 2025. [[paper](https://roboticsconference.org/program/papers/61/)] [[website](https://amo-humanoid.github.io/)]   

+ Chen et al. GMT: General Motion Tracking for Humanoid Whole-Body Control. arXiv 2025. [[paper](https://arxiv.org/abs/2506.14770)] [[website](https://gmt-humanoid.github.io/)]  
