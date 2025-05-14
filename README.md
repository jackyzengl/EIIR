<br>
<p align="center">
<h1 align="center"><strong>Paper list for Embodied Intelligent Industrial Robotics (EIIR)</strong></h1>
  <p align="center">
    <a href='https://jackyzengl.github.io/' target='_blank'>THU IMMV Lab</a>&emsp;
  </p>
</p>

<p align="center">
<img src="IMMV.png" width="180">
</p>

[![arXiv](https://img.shields.io/badge/arXiv-2407.06886-orange)]()
[![](https://img.shields.io/badge/Paper-%F0%9F%93%96-yellow)](https://github.com/jackeyzengl/Embodied_Intelligent_Industrial_Robotics_Paper_List/blob/main/Embodied_Intelligent_Industrial_Robotics_Concepts_and_Techniques.pdf)
[![](https://img.shields.io/badge/Project-%F0%9F%9A%80-pink)](https://github.com/jackeyzengl/Embodied_Intelligent_Industrial_Robotics_Paper_List)

#### We appreciate any useful suggestions for improvement of this paper list or survey from peers. Please raise issues or send an email to **zenglong@sz.tsinghua.edu.cn** and **zcr23@mails.tsinghua.edu.cn**. Thanks for your cooperation! We also welcome your pull requests for this project!

![Concept](EIIR_Concept.png "Concept")
![Framework](EIIR_Framework.png "Framework")

[**Embodied Intelligent Industrial Robotics: Concepts and Techniques**](https://arxiv.org/pdf/2407.06886)

[Chaoran Zhang](https://orcid.org/0009-0003-5190-7104), Chenhao Zhang, Zhaobo Xu, [Qinghongbing Xie](https://github.com/binicey), [Pingfa Feng](https://me.tsinghua.edu.cn/info/1097/1576.htm), [Long Zeng](https://jackyzengl.github.io/)

<p align="center">
<img src="./Survey.png" width="800">
</p>  

## 🏠 About

In recent years, embodied intelligent robotics (EIR) has made significant progress in multi-modal perception, autonomous decision-making, and physical interaction. Some robots have already been tested in general-purpose scenarios such as homes and shopping malls. We aim to advance the research and application of embodied intelligence in industrial scenes. However, current EIR lacks a deep understanding of industrial environment semantics and the normative constraints among industrial operating objects. To address this gap, this paper first reviews the history of industrial robotics and the mainstream EIR frameworks. We then introduce the concept of the **embodied intelligent industrial robotics (EIIR)** and propose **a knowledge-driven EIIR technology framework** for industrial environments.

The framework includes **four main modules**: world model, high-level task planner, low-level skill controller, and simulator. The world model provides industrial working environment knowledge (such as semantic map) and industrial operating object knowledge (such as knowledge graph) that large language model (LLM) lacks. The high-level task planner breaks down natural language tasks into a series of subtasks. The low-level skill controller translates these subtasks into specific, executable skill sequences to realize the physical execution of industrial tasks. The simulator models kinematics, control logic, and environmental interactions to support algorithm development, virtual commissioning, and digital twins at both the single-robot and full-production-line scales.

We also review **the current development of technologies related to each module** and highlight recent progress in adapting them to industrial applications. Finally, we summarize the key challenges EIIR faces in industrial scenarios and suggest future research directions. We believe that EIIR technology will shape the next generation of industrial robotics. Industrial systems based on embodied intelligent industrial robots offer strong potential for enabling intelligent manufacturing. We will continue to track and summarize new research in this area and hope this review will serve as a valuable reference for scholars and engineers interested in industrial embodied intelligence. Together, we can help drive the rapid advancement and application of this technology. 

## 💥 Update Log 
* [2025.05.14] We release the first version of the survey on EIIR！ [[PDF]](https://arxiv.org/pdf/2407.06886)
* [2025.05.14] We release the first version of the paper list for Embodied Intelligent Industrial Robotics (EIIR). This page is continually updating!



## <a id="table-of-contents">📚 Table of Contents </a>

- [Concepts & Surveys](#concepts-surveys)
- [World Model](#world-model)
- [High-level Task Planner](#high-level)
- [Low-level Skill Controller](#low-level)
- [Simulators](#simulators)


## <a id="concepts-surveys"> Concepts & Surveys <a href="#table-of-contents">🔝</a> </a> 

* **Aligning Cyber Space with Physical World: A Comprehensive Survey on Embodied AI**, axXiv, 2024       
Y. Liu, W. Chen, Y. Bai, J.-H. Luo, X. Song, K. Jiang, Z. Li, G. Zhao, J. Lin, G. Li, W. Gao, L. Lin  
[[Paper](https://arxiv.org/pdf/2407.06886)]

* **A Survey of Embodied AI: From Simulators to Research Tasks**, IEEE Transactions on Emerging Topics in Computational Intelligence, 2022       
J. Duan, S. Yu, H.L. Tan, H. Zhu, C. Tan  
[[Paper](https://ieeexplore.ieee.org/abstract/document/9687596)]

* **Embodied Intelligence: A Synergy of Morphology, Action, Perception and Learning**, ACM Computing Surveys, 2025       
H. Liu, D. Guo, A. Cangelosi  
[[Paper](https://dl.acm.org/doi/full/10.1145/3717059)]

* **Large language models for robotics: Opportunities, challenges, and perspectives**, Journal of Automation and Intelligence, 2025       
J. Wang, E. Shi, H. Hu, C. Ma, Y. Liu, X. Wang, Y. Yao, X. Liu, B. Ge, S. Zhang  
[[Paper](https://www.sciencedirect.com/science/article/pii/S2949855424000613)]

* **A Survey of Robot Intelligence with Large Language Models**, Applied Sciences, 2024       
H. Jeong, H. Lee, C. Kim, S. Shin  
[[Paper](https://www.mdpi.com/2076-3417/14/19/8868)]

* **A survey on integration of large language models with intelligent robots**, Intelligent Service Robotics, 2024       
Y. Kim, D. Kim, J. Choi, J. Park, N. Oh, D. Park  
[[Paper](https://link.springer.com/article/10.1007/s11370-024-00550-5)]

* **Embodied Intelligence Toward Future Smart Manufacturing in the Era of AI Foundation Model**, IEEE-ASME Transactions on Mechatronics, 2024       
L. Ren, J. Dong, S. Liu, L. Zhang, L. Wang  
[[Paper](https://ieeexplore.ieee.org/abstract/document/10697107)]

* **Large scale foundation models for intelligent manufacturing applications: a survey**, Journal of Intelligent Manufacturing, 2025       
H. Zhang, S. Semujju, Z. Wang, X. Lv, K. Xu, L. Wu, Y. Jia, J. Wu, W. Liang, R. Zhuang, Z. Long, R. Ma, X. Ma  
[[Paper](https://link.springer.com/article/10.1007/s10845-024-02536-7)]

* **Semantic Mapping for Mobile Robots in Indoor Scenes: A Survey**, Information, 2021       
X. Han, S. Li, X. Wang, W. Zhou  
[[Paper](https://www.mdpi.com/2078-2489/12/2/92)]

* **A Survey of Optimization-based Task and Motion Planning: From Classical To Learning Approaches**, IEEE-ASME Transactions on Mechatronics, 2024       
Z. Zhao, S. cheng, Y. Ding, Z. Zhou, S. Zhang, D. Xu, Y. Zhao  
[[Paper](https://ieeexplore.ieee.org/abstract/document/9393345)]

* **A Survey on Vision-Language-Action Models for Embodied AI**, arXiv, 2024       
Y. Ma, Z. Song, Y. Zhuang, J. Hao, I. King  
[[Paper](https://arxiv.org/pdf/2405.14093)]

* **Knowledge Graphs in Manufacturing and Production: A Systematic Literature Review**, IEEE Access, 2021       
G. Buchgeher, D. Gabauer, J. Martinez-Gil, L. Ehrlinger  
[[Paper](https://www.sciencedirect.com/science/article/pii/S0736584522000485)]

* **Robot learning towards smart robotic manufacturing: A review**, Robotics and Computer-Integrated Manufacturing, 2022       
Z. Liu, Q. Liu, W. Xu, L. Wang, Z. Zhou  
[[Paper](https://www.sciencedirect.com/science/article/pii/S0736584522000485)]

* **Deep reinforcement learning in smart manufacturing: A review and prospects**, CIRP Journal of Manufacturing Science and Technology, 2023       
C. Li, P. Zheng, Y. Yin, B. Wang, L. Wang  
[[Paper](https://www.sciencedirect.com/science/article/abs/pii/S1755581722001717)]

* **Industrial foundation model**, IEEE transactions on cybernetics, 2025       
L. Ren, H. Wang, J. Dong, Z. Jia, S. Li, Y. Wang, et al.  
[[Paper](https://ieeexplore.ieee.org/abstract/document/10922728)]

* **Open X-Embodiment: Robotic Learning Datasets and RT-X Models : Open X-Embodiment Collaboration0**, IEEE International Conference on Robotics and Automation (ICRA), 2024       
A. O’Neill, A. Rehman, A. Maddukuri, A. Gupta, A. Padalkar, A. Lee, et al.  
[[Paper](https://ieeexplore.ieee.org/abstract/document/10611477)]

* **Does your Robot have Skills**, Proceedings of the 43rd international symposium on robotics, 2012       
S. Bøgh, O.S. Nielsen, M.R. Pedersen, V. Krüger, O. Madsen  
[[Paper](https://vbn.aau.dk/ws/portalfiles/portal/69945674/ISR_2012_Paper_ID_1158_FINAL.pdf)]

* **Skills in Assembly**, Institut für Werkzeugmaschinen und Betriebswissenschaften, 2018       
V. Hammerstingl, G. Reinhart  
[[Paper](https://mediatum.ub.tum.de/doc/1428286/952452.pdf)]

* **Digital description of products, processes and resources for task-oriented programming of assembly systems**, Journal of Intelligent Manufacturing, 2017       
J. Backhaus, G. Reinhart  
[[Paper](https://link.springer.com/article/10.1007/s10845-015-1063-3)]

* **Human-Robot Shared Assembly Taxonomy: A step toward seamless human-robot knowledge transfer**, Robotics and Computer-Integrated Manufacturing, 2024       
R.K.-J. Lee, H. Zheng, Y. Lu  
[[Paper](https://www.sciencedirect.com/science/article/pii/S0736584523001618)]

* **Capability-based Frameworks for Industrial Robot Skills: a Survey**, IEEE 18th International Conference on Automation Science and Engineering (CASE), 2022       
M. Pantano, T. Eiband, D. Lee  
[[Paper](https://ieeexplore.ieee.org/abstract/document/9926648)]

* **Domain-Specific Languages: An Annotated Bibliography**, ACM Sigplan Notices, 2000       
A. Deursen, P. Klint, J. Visser  
[[Paper](https://dl.acm.org/doi/abs/10.1145/352029.352035)]

* **A Survey on Domain-Specific Languages in Robotics**, 4th International Conference on Simulation, Modeling, and Programming for Autonomous Robots (SIMPAR), 2014       
A. Nordmann, N. Hochgeschwender, S. Wrede  
[[Paper](https://link.springer.com/chapter/10.1007/978-3-319-11900-7_17)]

* **A Survey on Domain-Specific Modeling and Languages in Robotics**, Journal of Software Engineering for Robotics, 2016         
A. Nordmann, N. Hochgeschwender, D. Wigand, S. Wrede   
[[Paper](https://pub.h-brs.de/frontdoor/deliver/index/docId/2674/file/100-583-1-PB.pdf)]

* **Springer Handbook of Robotics**, Springer, 2008       
B. Siciliano, O. Khatib  
[[Book](https://link.springer.com/book/10.1007/978-3-319-32552-1?source=shoppingads&locale=en-jp&gclid=Cj0KCQiAwJWdBhCYARIsAJc4idCcF2us102UDVGHpi9py3j3kDIRfTV8W-cT0Jx8dgDKWGwDZj2053EaAqIdEALw_wcB)]

## <a id="world-model">  World Model <a href="#table-of-contents">🔝</a> </a>

### Semantic Map

* **Learning 3d semantic scene graphs from 3d indoor reconstructions**, Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2020         
J. Wald, H. Dhamo, N. Navab, F. Tombari  
[[Paper](https://openaccess.thecvf.com/content_CVPR_2020/papers/Wald_Learning_3D_Semantic_Scene_Graphs_From_3D_Indoor_Reconstructions_CVPR_2020_paper.pdf)]

* **Scenegraphfusion: Incremental 3d scene graph prediction from rgb-d sequences**, Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2021         
S.-C. Wu, J. Wald, K. Tateno, N. Navab, F. Tombari  
[[Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Wu_SceneGraphFusion_Incremental_3D_Scene_Graph_Prediction_From_RGB-D_Sequences_CVPR_2021_paper.pdf)]

* **Incremental 3d semantic scene graph prediction from rgb sequences**, Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2023         
S.-C. Wu, K. Tateno, N. Navab, F. Tombari  
[[Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Wu_Incremental_3D_Semantic_Scene_Graph_Prediction_From_RGB_Sequences_CVPR_2023_paper.pdf)]

* **3D dynamic scene graphs: Actionable spatial perception with places, objects, and humans**, arXiv, 2020         
A. Rosinol, A. Gupta, M. Abate, J. Shi, L. Carlone  
[[Paper](https://arxiv.org/pdf/2002.06289)]

* **Hydra: A real-time spatial perception system for 3D scene graph construction and optimization**, arXiv, 2022         
N. Hughes, Y. Chang, L. Carlone  
[[Paper](https://arxiv.org/pdf/2201.13360)]

* **Context-Aware Entity Grounding with Open-Vocabulary 3D Scene Graphs**, 7th Conference on Robot Learning (CoRL), 2023         
H. Chang, K. Boyalakuntla, S. Lu, S. Cai, E.P. Jing, S. Keskar, S. Geng, A. Abbas, L. Zhou, K. Bekris   
[[Paper](https://proceedings.mlr.press/v229/chang23b/chang23b.pdf)]

* **ConceptFusion: Open-set Multimodal 3D Mapping**, ICRA2023 Workshop on Pretraining for Robotics (PT4R), 2023       
K.M. Jatavallabhula, A. Kuwajerwala, Q. Gu, M. Omama, T. Chen, A. Maalouf, S. Li, G.S. Iyer, S. Saryazdi, N.V. Keetha  
[[Paper](https://openreview.net/pdf?id=zEyavwx3qf)]

* **ConceptGraphs: Open-Vocabulary 3D Scene Graphs for Perception and Planning**, IEEE International Conference on Robotics and Automation (ICRA), 2024        
Q. Gu, A. Kuwajerwala, S. Morin, K.M. Jatavallabhula, B. Sen, A. Agarwal, C. Rivera, W. Paul, K. Ellis, R. Chellappa   
[[Paper](https://ieeexplore.ieee.org/abstract/document/10610243)]

* **Hierarchical open-vocabulary 3d scene graphs for language-grounded robot navigation**, First Workshop on Vision-Language Models for Navigation and Manipulation at ICRA, 2024        
A. Werby, C. Huang, M. Büchner, A. Valada, W. Burgard  
[[Paper](https://openreview.net/pdf?id=TL0Hb9OwfR)]

* **Indoor and outdoor 3d scene graph generation via language-enabled spatial ontologies**, IEEE Robotics and Automation Letters, 2024         
J. Strader, N. Hughes, W. Chen, A. Speranzon, L. Carlone   
[[Paper](https://ieeexplore.ieee.org/abstract/document/10487851)]

### Knowledge Graph
* **Knowledge graph construction for product designs from large CAD model repositories**, Advanced Engineering Informatics, 2022         
A.G. Bharadwaj, B. Starly   
[[Paper](https://www.sciencedirect.com/science/article/abs/pii/S1474034622001409)]

* **Assembly Information Model Based on Knowledge Graph**, Journal of Shanghai Jiaotong University (Science), 2020         
Z. Chen, J. Bao, X. Zheng, T. Liu   
[[Paper](https://link.springer.com/article/10.1007/s12204-020-2179-y)]

* **Knowledge Graph-Based Assembly Resource Knowledge Reuse towards Complex Product Assembly Process**, Sustainability, 2022         
J. Strader, N. Hughes, W. Chen, A. Speranzon, L. Carlone   
[[Paper](https://www.mdpi.com/2071-1050/14/23/15541)]

* **A knowledge graph–based structured representation of assembly process planning combined with deep learning**, The International Journal of Advanced Manufacturing Technology, 2024         
X. Shi, X. Tian, J. Gu, F. Yang, L. Ma, Y. Chen, T. Su   
[[Paper](https://link.springer.com/article/10.1007/s00170-024-13785-4)]

* **An approach to capturing and reusing tacit design knowledge using relational learning for knowledge graphs**, Advanced Engineering Informatics, 2022         
J. Jia, Y. Zhang, M. Saad   
[[Paper](https://www.sciencedirect.com/science/article/abs/pii/S1474034621002548)]

* **A Knowledge Graph-Based Approach for Assembly Sequence Recommendations for Wind Turbines**, Machines, 2023         
M. Liu, B. Zhou, J. Li, X. Li, J. Bao   
[[Paper](https://www.mdpi.com/2075-1702/11/10/930)]

* **A question answering system for assembly process of wind turbines based on multi-modal knowledge graph and large language model**, Journal of Engineering Design, 2023         
Z. Hu, X. Li, X. Pan, S. Wen, J. Bao  
[[Paper](https://www.tandfonline.com/doi/abs/10.1080/09544828.2023.2272555)]

* **KGAssembly: Knowledge graph-driven assembly process generation and evaluation for complex components**, International Journal of Computer Integrated Manufacturing, 2022         
B. Zhou, J. Bao, Z. Chen, Y. Liu  
[[Paper](https://www.tandfonline.com/doi/abs/10.1080/0951192X.2021.1891572)]

* **An assembly process planning pipeline for industrial electronic equipment based on knowledge graph with bidirectional extracted knowledge from historical process documents**, Journal of Intelligent Manufacturing, 2024         
Y. Xiao, S. Zheng, J. Leng, R. Gao, Z. Fu, J. Hong   
[[Paper](https://link.springer.com/article/10.1007/s10845-024-02423-1)]

* **The development of an ontology for describing the capabilities of manufacturing resources**, Journal of Intelligent Manufacturing, 2019         
E. Järvenpää, N. Siltala, O. Hylli, M. Lanz   
[[Paper](https://link.springer.com/article/10.1007/s10845-018-1427-6)]

* **Implementation of capability matchmaking software facilitating faster production system design and reconfiguration planning**, Journal of Manufacturing Systems, 2019         
E. Järvenpää, N. Siltala, O. Hylli, M. Lanz   
[[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0278612519300883)]

* **Semantic models and knowledge graphs as manufacturing system reconfiguration enablers**, Robotics and Computer-Integrated Manufacturing, 2024           
F. Mo, J.C. Chaplin, D. Sanderson, G. Martinez-Arellano, S. Ratchev   
[[Paper](https://www.sciencedirect.com/science/article/pii/S073658452300100X)]

* **A framework for manufacturing system reconfiguration and optimisation utilising digital twins and modular artificial intelligence**, Robotics and Computer-Integrated Manufacturing, 2023         
F. Mo, H.U. Rehman, F.M. Monetti, J.C. Chaplin, D. Sanderson, A. Popov, A. Maffei, S. Ratchev    
[[Paper](https://www.sciencedirect.com/science/article/pii/S073658452200206X)]

* **Skill Manipulation Method of Industrial Robot Based on Knowledge Graph for Assembly Scene**, Cognitive Computation and Systems, Springer Nature Singapore, 2023         
D. Zhong, S. Miao, R. Miao, F. Sun, Z. Wen, H. Huang, N. Wang   
[[Paper](https://link.springer.com/chapter/10.1007/978-981-99-2789-0_24)]

## <a id="high-level">  High-level Task Planner <a href="#table-of-contents">🔝</a> </a>

### General Task planning

#### LLM-based
* **ProgPrompt: Generating Situated Robot Task Plans using Large Language Models**, NeurIPS, 2022       
I. Singh, V. Blukis, A. Mousavian, A. Goyal, D. Xu, J. Tremblay, D. Fox, J. Thomason, A. Garg  
[[Paper](https://openreview.net/pdf?id=aflRdmGOhw1)]
* **Task and Motion Planning with Large Language Models for Object Rearrangement**, IROS, 2023       
Y. Ding, X. Zhang, C. Paxton, S. Zhang  
[[Paper](https://ieeexplore.ieee.org/abstract/document/10342169)]
* **On Grounded Planning for Embodied Tasks with Language Models**, AAAI, 2023       
B. Yuchen Lin, C. Huang, Q. Liu, W. Gu, S. Sommerer, X. Ren  
[[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/26549)]
* **LLM-State: Open World State Representation for Long-horizon Task Planning with Large Language Model**, ArXiv, 2023       
S. Chen, A. Xiao, D. Hsu  
[[Paper](https://arxiv.org/abs/2311.17406)]
* **GRID: Scene-Graph-based Instruction-driven Robotic Task Planning**, IROS, 2024       
Z. Ni, X. Deng, C. Tai, X. Zhu, Q. Xie, W. Huang, X. Wu, L. Zeng  
[[Paper](https://ieeexplore.ieee.org/abstract/document/10801291)]
* **LLM-Planner: Few-Shot Grounded Planning for Embodied Agents with Large Language Models**, ICCV, 2023       
C.H. Song, J. Wu, C. Washington, B.M. Sadler, W.-L. Chao, Y. Su  
[[Paper](https://ieeexplore.ieee.org/abstract/document/10378628)]
* **Embodied Task Planning with Large Language Models**, ArXiv, 2023       
Z. Wu, Z. Wang, X. Xu, J. Lu, H. Yan  
[[Paper](https://arxiv.org/pdf/2307.01848)]
* **Vision-Language Interpreter for Robot Task Planning**, ICRA, 2024       
K. Shirai, C.C. Beltran-Hernandez, M. Hamaya, A. Hashimoto, S. Tanaka, K. Kawaharazuka, K. Tanaka, Y. Ushiku, S. Mori  
[[Paper](https://ieeexplore.ieee.org/abstract/document/10611112)]
* **Enhancing the LLM-Based Robot Manipulation Through Human-Robot Collaboration**, IEEE Robotics and Automation Letters, 2024       
H. Liu, Y. Zhu, K. Kato, A. Tsukahara, I. Kondo, T. Aoyama, Y. Hasegawa  
[[Paper](https://ieeexplore.ieee.org/abstract/document/10561501)]
* **Ensuring Safety in LLM-Driven Robotics: A Cross-Layer Sequence Supervision Mechanism**, IROS, 2024       
Z. Wang, Q. Liu, J. Qin, M. Li  
[[Paper](https://ieeexplore.ieee.org/document/10801576)]
* **SafeAgentBench: A Benchmark for Safe Task Planning of Embodied LLM Agents**, ArXiv, 2024       
S. Yin, X. Pang, Y. Ding, M. Chen, Y. Bi, Y. Xiong, W. Huang, Z. Xiang, J. Shao, S. Chen  
[[Paper](https://arxiv.org/abs/2412.13178)]
* **Safe Planner: Empowering Safety Awareness in Large Pre-Trained Models for Robot Task Planning**, AAAI, 2025       
S. Li, Z. Ma, F. Liu, J. Lu, Q. Xiao, K. Sun, L. Cui, X. Yang, P. Liu, X. Wang  
[[Paper](https://ojs.aaai.org/index.php/AAAI/article/view/33602)]
* **Safety Guardrails for LLM-Enabled Robots**, ArXiv, 2025       
Z. Ravichandran, A. Robey, V. Kumar, G.J. Pappas, H. Hassani  
[[Paper](https://arxiv.org/pdf/2503.07885)]
* **Language, Camera, Autonomy! Prompt-engineered Robot Control for Rapidly Evolving Deployment**, ACM/IEEE International Conference on Human-Robot Interaction, 2024       
J.P. Macdonald, R. Mallick, A.B. Wollaber, J.D. Peña, N. McNeese, H.C. Siu  
[[Paper](https://dl.acm.org/doi/abs/10.1145/3610978.3640671)]
* **Plug in the Safety Chip: Enforcing Constraints for LLM-driven Robot Agents**, ICRA, 2024       
Z. Yang, S.S. Raman, A. Shah, S. Tellex  
[[Paper](https://ieeexplore.ieee.org/abstract/document/10611447)]

#### VLA-based
* **A Survey on Vision-Language-Action Models for Embodied AI**, ArXiv, 2024       
Y. Ma, Z. Song, Y. Zhuang, J. Hao, I. King  
[[Paper](https://arxiv.org/abs/2405.14093)]
* **RT-1: Robotics Transformer for Real-World Control at Scale**, ArXiv, 2022       
 A. Brohan, N. Brown, J. Carbajal, Y. Chebotar, J. Dabis, C. Finn, K. Gopalakrishnan et al.  
[[Paper](https://arxiv.org/abs/2212.06817)]
* **RT-2: Vision-Language-Action Models Transfer Web Knowledge to Robotic Control**, ArXiv, 2023       
A. Brohan, N. Brown, J. Carbajal, Y. Chebotar, X. Chen, K. Choromanski, T. Ding, D. Driess et al.  
[[Paper](https://arxiv.org/abs/2307.15818)]
* **OpenVLA: An Open-Source Vision-Language-Action Model**, ArXiv, 2024       
M.J. Kim, K. Pertsch, S. Karamcheti, T. Xiao, A. Balakrishna, S. Nair, R. Rafailov et al.  
[[Paper](https://arxiv.org/abs/2406.09246)]
* **3D-VLA: A 3D Vision-Language-Action Generative World Model**, ICML, 2024       
H. Zhen, X. Qiu, P. Chen, J. Yang, X. Yan, Y. Du, Y. Hong, C. Gan  
[[Paper](https://dl.acm.org/doi/abs/10.5555/3692070.3694603)]
* **A Dual Process VLA: Efficient Robotic Manipulation Leveraging VLM**, ArXiv, 2024       
B. Han, J. Kim, J. Jang  
[[Paper](https://arxiv.org/abs/2410.15549)]
* **SpatialVLA: Exploring Spatial Representations for Visual-Language-Action Model**, ArXiv, 2025       
D. Qu, H. Song, Q. Chen, Y. Yao, X. Ye, Y. Ding, Z. Wang, J. Gu, B. Zhao, D. Wang, X. Li  
[[Paper](https://arxiv.org/pdf/2309.09919)]
* **Bi-VLA: Vision-Language-Action Model-Based System for Bimanual Robotic Dexterous Manipulations**, IEEE International Conference on Systems, Man and Cybernetics, 2024       
K. Fidèle Gbagbe, M. Altamirano Cabrera, A. Alabbas, O. Alyunes, A. Lykov, D. Tsetserukou  
[[Paper](https://ieeexplore.ieee.org/abstract/document/10831380)]
* **RoboNurse-VLA: Robotic Scrub Nurse System based on Vision-Language-Action Model**, ArXiv, 2024       
S. Li, J. Wang, R. Dai, W. Ma, W.Y. Ng, Y. Hu, Z. Li  
[[Paper](https://arxiv.org/html/2409.19590v1)]
* **VLABench: A Large-Scale Benchmark for Language-Conditioned Robotics Manipulation with Long-Horizon Reasoning Tasks**, ArXiv, 2024       
S. Zhang, Z. Xu, P. Liu, X. Yu, Y. Li, Q. Gao, Z. Fei, Z. Yin, Z. Wu, Y.-G. Jiang, X. Qiu  
[[Paper](https://arxiv.org/html/2412.18194)]

### Industrial Task planning
#### Knowledge and Skill-based
* **Knowledge Graphs in Manufacturing and Production: A Systematic Literature Review**, IEEE Access, 2021       
G. Buchgeher, D. Gabauer, J. Martinez-Gil, L. Ehrlinger  
[[Paper](https://ieeexplore.ieee.org/document/9393345)]
* **Self-developing fuzzy expert system: a novel learning approach, fitting for manufacturing domain**, Journal of Intelligent Manufacturing, 2009       
A. Iqbal, N.U. Dar, N. He, M.M.I. Hammouda, L. Li  
[[Paper](https://link.springer.com/article/10.1007/s10845-009-0252-3)]
* **A. Sánchez García, Expert system based controller for the high-accuracy automatic assembly of vehicle headlamps**, Expert Systems with Applications, 2011       
J. Gámez García, J. Gómez Ortega, S. Satorres Martínez  
[[Paper](https://www.sciencedirect.com/science/article/pii/S0957417411005902)]
* **Expert System based on RPW Technique to Evaluating Multi Product Assembly Line Balancing Solution**, International Journal of Computer Applications, 2012       
A. Manoria, S.K. Mishra, S.U. Maheshwar  
[[Paper](https://www.ijcaonline.org/archives/volume40/number4/5034-7185/)]
* **Knowledge-driven industrial robotics for flexible production**, International Conference on Intelligent Engineering Systems (INES), 2017          
M. Merdan, E. List, W. Lepuschitz   
[[Paper](https://ieeexplore.ieee.org/document/8118560)]
* **Assembly Process Knowledge Graph for Digital Twin**, International Conference on Automation Science and Engineering (CASE), 2021       
Y. Jiang, C. Chen, X. Liu  
[[Paper](https://ieeexplore.ieee.org/document/9551554)]
* **Knowledge-driven framework for industrial robotic systems**, Journal of Intelligent Manufacturing, 2021       
T. Hoebert, W. Lepuschitz, M. Vincze, M. Merdan  
[[Paper](https://link.springer.com/article/10.1007/s10845-021-01826-8)]
* **KGAssembly: Knowledge graph-driven assembly process generation and evaluation for complex components**, International Journal of Computer Integrated Manufacturing, 2021       
B. Zhou, J. Bao, Z. Chen, Y. Liu  
[[Paper](https://www.tandfonline.com/doi/full/10.1080/0951192X.2021.1891572)]
* **A Knowledge Graph-based knowledge representation for adaptive manufacturing control under mass personalization**, Manufacturing Letters, 2023       
Z. Qin, Y. Lu  
[[Paper](https://www.sciencedirect.com/science/article/pii/S2213846323001438)]
* **Towards robust assembly with knowledge representation for the planning domain definition language (PDDL)**, Robotics and Computer-Integrated Manufacturing, 2015       
Z. Kootbally, C. Schlenoff, C. Lawler, T. Kramer, S.K. Gupta  
[[Paper](https://www.sciencedirect.com/science/article/pii/S0736584514000672)]
* **ROSPlan: Planning in the Robot Operating System**, International Conference on Automated Planning and Scheduling, 2015       
M. Cashmore, M. Fox, D. Long, D. Magazzeni, B. Ridder, A. Carrera, N. Palomeras, N. Hurtós, M. Carreras  
[[Paper](https://dl.acm.org/doi/10.5555/3038662.3038708)]
* **SkiROS—A Skill-Based Robot Control Platform on Top of ROS**, A. Koubaa (Ed.) Robot Operating System (ROS), 2017       
F. Rovida, M. Crosby, D. Holz, A.S. Polydoros, B. Großmann, R.P.A. Petrick, V. Krüger  
[[Paper](https://link.springer.com/chapter/10.1007/978-3-319-54927-9_4)]
* **An extendable framework for intelligent and easily configurable skills-based industrial robot applications**, The International Journal of Advanced Manufacturing Technology, 2022       
L. Heuss, C. Gonnermann, G. Reinhart  
[[Paper](https://link.springer.com/article/10.1007/s00170-022-09071-w)]
* **Improved Domain Modeling for Realistic Automated Planning and Scheduling in Discrete Manufacturing**, International Conference on Emerging Technologies and Factory Automation (ETFA), 2018       
A. Rogalla, A. Fay, O. Niggemann  
[[Paper](https://ieeexplore.ieee.org/abstract/document/8502631)]
* **Generating consistent PDDL domains with Large Language Models**, ArXiv, 2024       
P. Smirnov, F. Joublin, A. Ceravola, M. Gienger  
[[Paper](https://arxiv.org/pdf/2404.07751)]

#### Learning-based
* **Deep reinforcement learning in smart manufacturing: A review and prospects**, CIRP Journal of Manufacturing Science and Technology, 2023       
C. Li, P. Zheng, Y. Yin, B. Wang, L. Wang  
[[Paper](https://www.sciencedirect.com/science/article/pii/S1755581722001717)]
* **Robot learning towards smart robotic manufacturing: A review**, Robotics and Computer-Integrated Manufacturing, 2022       
Z. Liu, Q. Liu, W. Xu, L. Wang, Z. Zhou  
[[Paper](https://www.sciencedirect.com/science/article/pii/S0736584522000485)]
* **Deep Learning-Based Robot Vision: High-End Tools for Smart Manufacturing**, IEEE Instrumentation & Measurement Magazine, 2022       
H. Zhang, L.Z. Liu, H. Xie, Y. Jiang, J. Zhou, Y. Wang  
[[Paper](https://ieeexplore.ieee.org/abstract/document/9756392)]
* **Deep Learning-based Multimodal Control Interface for Human-Robot Collaboration**, Procedia CIRP, 2018       
H. Liu, T. Fang, T. Zhou, Y. Wang, L. Wang  
[[Paper](https://www.sciencedirect.com/science/article/pii/S2212827118303846)]
* **Industrial Robot Control with Object Recognition based on Deep Learning**, Procedia CIRP, 2018       
X. Chen, J. Guhl  
[[Paper](https://www.sciencedirect.com/science/article/pii/S2212827118300350)]
* **Industrial Robot Grasping with Deep Learning using a Programmable Logic Controller (PLC)**, International Conference on Automation Science and Engineering (CASE), 2020       
E. Solowjow, I. Ugalde, Y. Shahapurkar, J. Aparicio, J. Mahler, V. Satish, K. Goldberg, H. Claussen  
[[Paper](https://ieeexplore.ieee.org/document/9216902)]
* **Heterogeneous knowledge graph-driven subassembly identification with ensemble deep learning in Industry 4.0**, International Journal of Production Research, 2024       
C. Zhang, Y. Jing, G. Zhou, H. Yan, F. Chang  
[[Paper](https://www.tandfonline.com/doi/full/10.1080/00207543.2024.2430450)]
* **Reinforcement learning for facilitating human-robot-interaction in manufacturing**, Journal of Manufacturing Systems, 2020       
H. Oliff, Y. Liu, M. Kumar, M. Williams, M. Ryan  
[[Paper](https://www.sciencedirect.com/science/article/pii/S0278612520301084)]
* **A flexible manufacturing assembly system with deep reinforcement learning**, Control Engineering Practice, 2022       
J. Li, D. Pang, Y. Zheng, X. Guan, X. Le  
[[Paper](https://www.sciencedirect.com/science/article/pii/S0967066121002343)]
* **A Model-Based Reinforcement Learning and Correction Framework for Process Control of Robotic Wire Arc Additive Manufacturing**, ICRA, 2020       
A.G. Dharmawan, Y. Xiong, S. Foong, G.S. Soh  
[[Paper](https://ieeexplore.ieee.org/abstract/document/9197222)]
* **Spatiotemporal path tracking via deep reinforcement learning of robot for manufacturing internal logistics**, Journal of Manufacturing Systems, 2024       
F. Fan, G. Xu, N. Feng, L. Li, W. Jiang, L. Yu, X. Xiong  
[[Paper](https://www.sciencedirect.com/science/article/pii/S0278612523001218)]
* **A novel fine-grained assembly sequence planning method based on knowledge graph and deep reinforcement learning**, Journal of Manufacturing Systems, 2023       
M. Jiang, Y. Guo, S. Huang, J. Pu, L. Zhang, S. Wang  
[[Paper](https://www.sciencedirect.com/science/article/pii/S027861252400164X)]
* **Optimised Learning from Demonstrations for Collaborative Robots**, Robotics and Computer-Integrated Manufacturing, 2021       
F. Fan, G. Xu, N. Feng, L. Li, W. Jiang, L. Yu, X. Xiong  
[[Paper](https://www.sciencedirect.com/science/article/pii/S0736584521000533)]
* **Contact Skill Imitation Learning for Robot-Independent Assembly Programming**, IROS, 2019       
S. Scherzinger, A. Roennau, R. Dillmann  
[[Paper](https://ieeexplore.ieee.org/document/8967523)]
* **An electromyography signals-based human-robot collaboration method for human skill learning and imitation**, Journal of Manufacturing Systems, 2022       
T. Zhang, H. Sun, Y. Zou, H. Chu  
[[Paper](https://www.sciencedirect.com/science/article/pii/S0278612522001170)]
* **Learning-Based Automation of Robotic Assembly for Smart Manufacturing**, Proceedings of the IEEE, 2021       
S. Ji, S. Lee, S. Yoo, I. Suh, I. Kwon, F.C. Park, S. Lee, H. Kim  
[[Paper](https://ieeexplore.ieee.org/document/9383829)]

#### LLM-based
* **Industrial foundation model: architecture, key technologies, and typical applications**, Scientia Sinica Informationis, 2024       
L. Ren, H. Wang, J. Dong, Z. Jia, S. Li, Y. Wang, Y. Laili, D. Huang, L. Zhang, W. Wu, B. Li  
[[Paper](https://www.sciengine.com/SSI/doi/10.1360/SSI-2024-0185)]
* **A Voice-Controlled Motion Reproduction Using Large Language Models for Polishing Robots**, International Conference on Mechatronics (ICM), 2023       
Y. Tanaka, S. Katsura  
[[Paper](https://ieeexplore.ieee.org/document/10101966)]
* **An LLM-based vision and language cobot navigation approach for Human-centric Smart Manufacturing**, Journal of Manufacturing Systems, 2024       
T. Wang, J. Fan, P. Zheng  
[[Paper](https://www.sciencedirect.com/science/article/pii/S0278612524000864)]
* **LLM4PlC: Harnessing large Language Models for Verifiable Programming of PlCs in Industrial Control Systems**, International Conference on Software Engineering: Software Engineering in Practice (ICSE-SEIP), 2024       
M. Fakih, R. Dharmaji, Y. Moghaddas, G.Q. Araya, O. Ogundare, M.A.A. Faruque  
[[Paper](https://ieeexplore.ieee.org/abstract/document/10554746)]
* **Embodied intelligence in manufacturing: leveraging large language models for autonomous industrial robotics**, Journal of Intelligent Manufacturing, 2024       
H. Fan, X. Liu, J.Y.H. Fuh, W.F. Lu, B. Li  
[[Paper](https://link.springer.com/article/10.1007/s10845-023-02294-y)]
* **Embodied Intelligence: Bionic Robot Controller Integrating Environment Perception, Autonomous Planning, and Motion Control**, IEEE Robotics and Automation Letters, 2024       
Y. Gan, B. Zhang, J. Shao, Z. Han, A. Li, X. Dai  
[[Paper](https://ieeexplore.ieee.org/abstract/document/10472590)]
* **An LLM-based approach for enabling seamless Human-Robot collaboration in assembly**, CIRP Annals, 2024       
C. Gkournelos, C. Konstantinou, S. Makris  
[[Paper](https://www.sciencedirect.com/science/article/pii/S000785062400012X)]
* **Embodied Intelligence in Additive Manufacturing**, IOP Conference Series: Materials Science and Engineering, 2024       
J. Xu, Y. Xie, F. Iida  
[[Paper](https://www.researchgate.net/publication/387241112_Embodied_Intelligence_in_Additive_Manufacturing)]
* **Revolutionizing Battery Disassembly: The Design and Implementation of a Battery Disassembly Autonomous Mobile Manipulator Robot(BEAM-1)**, IROS, 2024       
Y. Peng, Z. Wang, Y. Zhang, S. Zhang, N. Cai, F. Wu, M. Chen  
[[Paper](https://arxiv.org/abs/2407.06590)]
* **Agent as Cerebrum, Controller as Cerebellum: Implementing an Embodied LMM-based Agent on Drones**, ArXiv, 2024       
H. Zhao, F. Pan, H. Ping, Y. Zhou, Agent as Cerebrum  
[[Paper](https://arxiv.org/abs/2311.15033)]
* **Embodied AI for dexterity-capable construction Robots: DEXBOT framework**, Advanced Engineering Informatics, 2024       
H. You, T. Zhou, Q. Zhu, Y. Ye, E.J. Du  
[[Paper](https://www.sciencedirect.com/science/article/pii/S1474034624002209)]
* **Manufacturing Domain QA with Integrated Term Enhanced RAG**, IJCNN, 2024       
Y. Bei, Z. Fang, S. Mao, S. Yu, Y. Jiang, Y. Tong, W. Cai  
[[Paper](https://ieeexplore.ieee.org/document/10649905)]
* **AMGPT: A large language model for contextual querying in additive manufacturing**, Additive Manufacturing Letters, 2024       
A. Chandrasekhar, J. Chan, F. Ogoke, O. Ajenifujah, A. Barati Farimani  
[[Paper](https://www.sciencedirect.com/science/article/pii/S2772369024000409)]
* **A Conceptual Framework for a Latest Information-Maintaining Method Using Retrieval-Augmented Generation and a Large Language Model in Smart Manufacturing: Theoretical Approach and Performance Analysis**, Machines, 2025       
H. Choi, J. Jeong  
[[Paper](https://www.mdpi.com/2075-1702/13/2/94)]
* **Domain-Specific Manufacturing Analytics Framework: An Integrated Architecture with Retrieval-Augmented Generation and Ollama-Based Models for Manufacturing Execution Systems Environments**, Processes, 2025       
H. Choi, J. Jeon  
[[Paper](https://www.mdpi.com/2227-9717/13/3/670)]
* **An advanced retrieval-augmented generation system for manufacturing quality control**, Advanced Engineering Informatics, 2025       
J.A. Heredia Álvaro, J.G. Barreda  
[[Paper](https://www.sciencedirect.com/science/article/pii/S147403462400658X)]
* **Joint Knowledge Graph and Large Language Model for Fault Diagnosis and Its Application in Aviation Assembly**, IEEE Transactions on Industrial Informatics, 2024       
P. Liu, L. Qian, X. Zhao, B. Tao  
[[Paper](https://ieeexplore.ieee.org/document/10463190)]
* **Scene-Driven Multimodal Knowledge Graph Construction for Embodied AI**, IEEE Transactions on Knowledge and Data Engineering, 2024       
Y. Song, P. Sun, H. Liu, Z. Li, W. Song, Y. Xiao, X. Zhou  
[[Paper](https://ieeexplore.ieee.org/abstract/document/10531671)]



## <a id="low-level"> Low-level Skill Controller <a href="#table-of-contents">🔝</a> </a> 

### Skills

#### Pick and Place

* **Skill Manipulation Method of Industrial Robot Based on Knowledge Graph for Assembly Scene**, Cognitive Computation and Systems, 2023       
 D. Zhong, S. Miao, R. Miao, F. Sun, Z. Wen, H. Huang, N. Wang    
[[Paper](https://link.springer.com/chapter/10.1007/978-981-99-2789-0_24)]
* **SkiROS—A Skill-Based Robot Control Platform on Top of ROS**, A. Koubaa (Ed.) Robot Operating System (ROS): The Complete Reference (Volume 2), Springer International Publishings, 2023       
F. Rovida, M. Crosby, D. Holz, A.S. Polydoros, B. Großmann, R.P.A. Petrick, V. Krüger    
[[Paper](https://link.springer.com/chapter/10.1007/978-3-319-54927-9_4)]
* **An extendable framework for intelligent and easily configurable skills-based industrial robot applications**, The International Journal of Advanced Manufacturing Technology, 2022       
L. Heuss, C. Gonnermann, G. Reinhart    
[[Paper](https://link.springer.com/chapter/10.1007/978-981-99-2789-0_24)]
* **Learning-Based Automation of Robotic Assembly for Smart Manufacturing**, Proceedings of the IEEE, 2021       
S. Ji, S. Lee, S. Yoo, I. Suh, I. Kwon, F.C. Park, S. Lee, H. Kim    
[[Paper](https://ieeexplore.ieee.org/abstract/document/9383829)]
* **Enhancing Learning Capabilities of Movement Primitives under Distributed Probabilistic Framework for Assembly Tasks**, International Conference on Systems, Man, and Cybernetics (SMC), 2020       
L. Wang, S. Jia, G. Wang, A. Turner, S. Ratchev    
[[Paper](https://ieeexplore.ieee.org/abstract/document/9283066)]
* **A Prototype-Based Skill Model for Specifying Robotic Assembly Tasks**, IEEE International Conference on Robotics and Automation (ICRA), 2018       
F. Nägele, L. Halt, P. Tenbrock, A. Pott      
[[Paper](https://ieeexplore.ieee.org/abstract/document/8462885)]
* **Ontology Based AI Planning and Scheduling for Robotic Assembly**, International Conference on Intelligent Robots and Systems (IROS), 2024       
J. Zhao, B. Vogel-Heuser, J. Ao, Y. Wu, L. Zhang, F. Hartl, D. Hujo, Z. Bing, F. Wu, A. Knoll, S. Haddadin, B. Vojanec, T. Markert, A. Kraft      
[[Paper](https://ieeexplore.ieee.org/abstract/document/10802295)]
* **SkiROS2: A skill-based Robot Control Platform for ROS**, International Conference on Intelligent Robots and Systems (IROS), 2023       
M. Mayr, F. Rovida, V. Krueger    
[[Paper](https://ieeexplore.ieee.org/abstract/document/10342216)]
* **A Taxonomic Framework for Task Modeling and Knowledge Transfer in Manufacturing Robotics**, Association for the Advancement of Artificial Intelligence(AAAI), 2012       
J. Huckaby, H.I. Christensen    
[[Paper](https://cdn.aaai.org/ocs/ws/ws0915/5337-22710-1-PB.pdf)]
* **A new skill based robot programming language using UML/P Statecharts**, IEEE International Conference on Robotics and Automation (ICRA), 2013       
U. Thomas, G. Hirzinger, B. Rumpe, C. Schulze, A. Wortmann    
[[Paper](https://ieeexplore.ieee.org/abstract/document/6630615)]
* **Knowledge-based instruction of manipulation tasks for industrial robotics**, Robotics and Computer-Integrated Manufacturing, 2015       
M. Stenmark, J. Malec      
[[Paper](https://lup.lub.lu.se/search/publication/b71ce47c-fc98-484f-8745-dbdf0ddf8f8c)]
* **Flexible Robotic Assembly Based on Ontological Representation of Tasks, Skills, and Resources**, International Joint Conferences on Artificial Intelligence Organization, 2021       
P. Schäfer, F. Steinmetz, S. Schneyer, T. Bachmann, T. Eiband, F. Lay, A. Padalkar, C. Sürig, F. Stulp, K. Nottensteiner      
[[Paper](https://elib.dlr.de/144979/)]
* **Definition and Initial Case-Based Evaluation of Hardware-Independent Robot Skills for Industrial Robotic Co-Workers**, International Symposium on Robotics, 2014       
R.H. Andersen, T. Solund, J. Hallam      
[[Paper](https://ieeexplore.ieee.org/abstract/document/6840115)]
* **Skill-based instruction of collaborative robots in industrial settings**, Robotics and Computer-Integrated Manufacturing, 2018       
C. Schou, R.S. Andersen, D. Chrysostomou, S. Bøgh, O. Madsen    
[[Paper](https://www.sciencedirect.com/science/article/pii/S0736584516301910)]
* **RAZER—A HRI for Visual Task-Level Programming and Intuitive Skill Parameterization**, IEEE Robotics and Automation Letters, 2018       
F. Steinmetz, A. Wollschläger, R. Weitschat    
[[Paper](https://ieeexplore.ieee.org/abstract/document/8269311)]
* **Intuitive Task-Level Programming by Demonstration Through Semantic Skill Recognition**, IEEE Robotics and Automation Letters, 2019       
F. Steinmetz, V. Nitsch, F. Stulp    
[[Paper](https://ieeexplore.ieee.org/abstract/document/8763979)]
* **Collaborative Programming of Conditional Robot Tasks**, International Conference on Intelligent Robots and Systems (IROS), 2020       
C. Willibald, T. Eiband, D. Lee    
[[Paper](https://ieeexplore.ieee.org/abstract/document/9341212)]
* **Toward a library of manipulation actions based on semantic object-action relations**, International Conference on Intelligent Robots and Systems, 2013       
M.J. Aein, E.E. Aksoy, M. Tamosiunaite, J. Papon, A. Ude, F. Wörgötter    
[[Paper](https://ieeexplore.ieee.org/abstract/document/6697011)]
* **Knowledge for Synchronized Dual-Arm Robot Programming**, Association for the Advancement of Artificial Intelligence(AAAI), 2017       
M. Stenmark, E.A. Topp, M. Haage, J. Malec    
[[Paper](https://cdn.aaai.org/ocs/16021/16021-69860-1-PB.pdf)]
* **Skill-based Engineering and Control on Field-Device-Level with OPC UA**, International Conference on Emerging Technologies and Factory Automation (ETFA), 2019       
P. Zimmermann, E. Axmann, B. Brandenbourger, K. Dorofeev, A. Mankowski, P. Zanini    
[[Paper](https://ieeexplore.ieee.org/abstract/document/8869473)]
* **Teaching new tricks to a robot learning to solve a task by imitation**,  IEEE Conference on Robotics, Automation and Mechatronics, 2010       
C.A.A. Calderon, R.E. Mohan, Z. Changjiu    
[[Paper](https://ieeexplore.ieee.org/abstract/document/5513180)]
* **Skill-based Programming Framework for Composable Reactive Robot Behaviors**, International Conference on Intelligent Robots and Systems (IROS), 2020       
Y. Pane, E. Aertbeliën, J.D. Schutter, W. Decré    
[[Paper](https://ieeexplore.ieee.org/abstract/document/9340985)]
* **Towards Digital Twins for Industrial Assembly - Improving Robot Solutions by Intuitive User Guidance and Robot Programming**, IEEE International Conference on Emerging Technologies and Factory Automation (ETFA), 2020       
L.C. Sørensen, S. Mathiesen, R. Waspe, C. Schlette    
[[Paper](https://ieeexplore.ieee.org/abstract/document/9212072)]
* **MASD: A Multimodal Assembly Skill Decoding System for Robot Programming by Demonstration**, IEEE Transactions on Automation Science and Engineering, 2018       
Y. Wang, Y. Jiao, R. Xiong, H. Yu, J. Zhang, Y. Liu    
[[Paper](https://ieeexplore.ieee.org/abstract/document/8263146)]
* **Robot Assembly Skills Based on Compliant Motion**,  International Symposium on Robotics, 2016       
F. Dai, A. Wahrburg, B. Matthias, H. Ding    
[[Paper](https://ieeexplore.ieee.org/abstract/document/7559116)]
* **Autonomous planning for mobile manipulation services based on multi-level robot skills**, International Conference on Intelligent Robots and Systems, 2009       
M. weser, J. Zhang    
[[Paper](https://ieeexplore.ieee.org/abstract/document/5353901)]

* **From Demonstrations to Skills for High-Level Programming of Industrial Robots**, AAAI, 2016       
M. Stenmark, E.A. Topp    
[[Paper](https://cdn.aaai.org/ocs/14091/14091-62035-1-PB.pdf)]

* **Ontology-Based Knowledge Representation for Increased Skill Reusability in Industrial Robots**, International Conference on Intelligent Robots and Systems (IROS), 2018       
E.A. Topp, M. Stenmark, A. Ganslandt, A. Svensson, M. Haage, J. Malec    
[[Paper](https://ieeexplore.ieee.org/abstract/document/8593566/)]

* **Learning and Sequencing of Object-Centric Manipulation Skills for Industrial Tasks**, International Conference on Intelligent Robots and Systems (IROS), 2020       
L. Rozo, M. Guo, A.G. Kupcsik, M. Todescato, P. Schillinger, M. Giftthaler, M. Ochs, M. Spies, N. Waniek, P. Kesper, M. Burger      
[[Paper](https://ieeexplore.ieee.org/abstract/document/9341570)]
* **Dynamic task classification and assignment for the management of human-robot collaborative teams in workcells**, The International Journal of Advanced Manufacturing Technology, 2018       
G. Bruno, D. Antonelli      
[[Paper](https://link.springer.com/article/10.1007/s00170-018-2400-4)]
* **Intuitive skill-level programming of industrial handling tasks on a mobile manipulator**, International Conference on Intelligent Robots and Systems, 2014       
M.R. Pedersen, D.L. Herzog, V. Krüger      
[[Paper](https://ieeexplore.ieee.org/abstract/document/6943203)]
* **Robot skills for manufacturing: From concept to industrial deployment, Robotics and Computer-Integrated Manufacturing**, Robotics and Computer-Integrated Manufacturing, 2016       
M.R. Pedersen, L. Nalpantidis, R.S. Andersen, C. Schou, S. Bøgh, V. Krüger, O. Madsen      
[[Paper](https://www.sciencedirect.com/science/article/pii/S0736584515000575)]
* **Inferring the Geometric Nullspace of Robot Skills from Human Demonstrations**, IEEE International Conference on Robotics and Automation (ICRA), 2020       
C. Cai, Y. Liang, N. Somani, Y. Wu      
[[Paper](https://ieeexplore.ieee.org/abstract/document/9197174/)]
* **A Hierarchical Human-Robot Interaction-Planning Framework for Task Allocation in Collaborative Industrial Assembly Processes**, IEEE Robotics and Automation Letters, 2017       
L. Johannsmeier, S. Haddadin      
[[Paper](https://ieeexplore.ieee.org/abstract/document/7421993)]
* **Integration of a Skill-based Collaborative Mobile Robot in a Smart Cyber-physical Environment**, Procedia Manufacturing, 2017       
R.E. Andersen, E.B. Hansen, D. Cerny, S. Madsen, B. Pulendralingam, S. Bøgh, D. Chrysostomou      
[[Paper](https://www.sciencedirect.com/science/article/pii/S2351978917304171)]
* **A Vertical and Cyber–Physical Integration of Cognitive Robots in Manufacturing**, Proceedings of the IEEE, 2016       
V. Krueger, A. Chazoule, M. Crosby, A. Lasnier, M.R. Pedersen, F. Rovida, L. Nalpantidis, R. Petrick, C. Toscano, G. Veiga      
[[Paper](https://ieeexplore.ieee.org/abstract/document/7440782/)]
* **Testing the vertical and cyber-physical integration of cognitive robots in manufacturing**, Robotics and Computer-Integrated Manufacturing, 2019       
V. Krueger, F. Rovida, B. Grossmann, R. Petrick, M. Crosby, A. Charzoule, G. Martin Garcia, S. Behnke, C. Toscano, G. Veiga      
[[Paper](https://www.sciencedirect.com/science/article/pii/S0736584517304465)]
* **A Framework for Robot Manipulation: Skill Formalism, Meta Learning and Adaptive Control**, IEEE International Conference on Robotics and Automation (ICRA), 2019       
L. Johannsmeier, M. Gerchow, S. Haddadin      
[[Paper](https://ieeexplore.ieee.org/abstract/document/8793542)]
* **Integration of Autonomous Task Planning into Reconfigurable Skill-Based Industrial Robots**, International Conference on Emerging Technologies and Factory Automation (ETFA), 2020       
L. Heuss, G. Reinhart      
[[Paper](https://ieeexplore.ieee.org/abstract/document/9212005/)]
* **Task Adaptation Based on Hierarchical Constraints Classification for Safe Industrial Robots**, IEEE/ASME Transactions on Mechatronics, 2015       
N.M. Ceriani, A.M. Zanchettin, P. Rocco, A. Stolt, A. Robertsson      
[[Paper](https://ieeexplore.ieee.org/abstract/document/7102768)]
* **Design and development of a software architecture for autonomous mobile manipulators in industrial environments**, International Conference on Industrial Technology (ICIT), 2015       
F. Rovida, V. Krüger      
[[Paper](https://ieeexplore.ieee.org/abstract/document/7125585)]
* **Task planning for human robot interactive processes**, International Conference on Emerging Technologies and Factory Automation (ETFA), 2016       
N. Wantia, M. Esen, A. Hengstebeck, F. Heinze, J. Rossmann, J. Deuse, B. Kuhlenkoetter      
[[Paper](https://ieeexplore.ieee.org/abstract/document/7733523)]
* **Concept for the automated adaption of abstract planning domains for specific application cases in skills-based industrial robotics**, Journal of Intelligent Manufacturing, 2024       
L. Heuss, D. Gebauer, G. Reinhart      
[[Paper](https://link.springer.com/article/10.1007/s10845-023-02211-3)]
* **Knowledge-driven framework for industrial robotic systems**, Journal of Intelligent Manufacturing, 2023       
T. Hoebert, W. Lepuschitz, M. Vincze, M. Merdan      
[[Paper](https://link.springer.com/article/10.1007/s10845-021-01826-8)]
* **Does your Robot have Skillss**, International Symposium on Robotics, 2012       
S. Bøgh, O.S. Nielsen, M.R. Pedersen, V. Krüger, O. Madsen      
[[Paper](https://vbn.aau.dk/en/publications/does-your-robot-have-skills)]
* **Cyber-Physical-Robotics Modelling of modular robot cells for automated planning and execution of assembly tasks**, Mechatronics, 2016       
J. Michniewicz, G. Reinhart      
[[Paper](https://www.sciencedirect.com/science/article/pii/S0957415815000574)]
* **Flexible skill-based control for robot cells in manufacturing**, Frontiers in Robotics and Ai, 2022       
T. Wiese, J. Abicht, C. Friedrich, A. Hellmich, S. Ihlenfeldt      
[[Paper](https://www.frontiersin.org/journals/robotics-and-ai/articles/10.3389/frobt.2022.1014476/full)]
* **Modular lightweight robot system for aircraft production using a generic OPC UA skill concept**, Production Engineering, 2023      
P. Koch, P. Rawal, N. Töpfer, T. Haß, C. Böhlmann, W. Hintze      
[[Paper](https://link.springer.com/article/10.1007/s11740-023-01183-w)]
* **Robot Learning from Demonstration based on Human-in-the-loop Reinforcement Learning**, International Conference on Automation Science and Engineering (CASE), 2024       
C. Li, T. Yu, Q. Chang      
[[Paper](https://ieeexplore.ieee.org/abstract/document/10711559/)]
* **Towards Self-Configuring Plug & Produce Robot Systems Based on Ontologies**, International Conference on Automation, Robotics and Applications (ICARA), 2023       
C. Eymüller, J. Hanke, A. Poeppel, W. Reif      
[[Paper](https://ieeexplore.ieee.org/abstract/document/10126075)]
* **Contact-Aware Shaping and Maintenance of Deformable Linear Objects With Fixtures**, International Conference on Intelligent Robots and Systems (IROS), 2023       
K. Chen, Z. Bing, F. Wu, Y. Meng, A. Kraft, S. Haddadin, A. Knoll      
[[Paper](https://ieeexplore.ieee.org/abstract/document/10341726/)]
* **Learn from Robot: Transferring Skills for Diverse Manipulation via Cycle Generative Networks**, International Conference on Automation Science and Engineering (CASE), 2023       
Q. Yang, J.A. Stork, T. Stoyanov      
[[Paper](https://ieeexplore.ieee.org/abstract/document/10260484)]
* **Learning Hierarchical Robot Skills Represented by Behavior Trees from Natural Language**, International Conference on Cooperative Information Systems(CoopIS), 2023       
K. Wang, Y. Zhao, S. Dai, M. Yang, Y. He, N. Zhang      
[[Paper](https://link.springer.com/chapter/10.1007/978-3-031-46846-9_20)]
* **MT-RSL: A multitasking-oriented robot skill learning framework based on continuous dynamic movement primitives for improving efficiency and quality in robot-based intelligent operation**, Robotics and Computer-Integrated Manufacturing, 2024       
Y.M. Ning, T.J. Li, C. Yao, W.Q. Du, Y. Zhang, Y.H. Huang      
[[Paper](https://www.sciencedirect.com/science/article/pii/S0736584524001042)]
* **Flexible modeling and execution of semantic manufacturing processes for robot systems**, International Conference on Emerging Technologies and Factory Automation (ETFA), 2024       
I. Kessler, A. Perzylo      
[[Paper](https://ieeexplore.ieee.org/abstract/document/10710791)]
* **PPR-Net:Point-wise Pose Regression Network for Instance Segmentation and 6D Pose Estimation in Bin-picking Scenarios**, International Conference on Intelligent Robots and Systems (IROS), 2019       
Z. Dong, S. Liu, T. Zhou, H. Cheng, L. Zeng, X. Yu, H. Liu      
[[Paper](https://ieeexplore.ieee.org/abstract/document/8967895)]
* **PPR-Net++: Accurate 6-D Pose Estimation in Stacked Scenarios**, IEEE Transactions on Automation Science and Engineering, 2022       
L. Zeng, W.J. Lv, Z.K. Dong, Y.J. Liu      
[[Paper](https://ieeexplore.ieee.org/abstract/document/9537584)]
* **Reinforcement Learning Based Pushing and Grasping Objects from Ungraspable Poses**, IEEE International Conference on Robotics and Automation (ICRA), 2023       
H. Zhang, H. Liang, L. Cong, J. Lyu, L. Zeng, P. Feng, J. Zhang      
[[Paper](https://ieeexplore.ieee.org/abstract/document/10160491)]
* **Domain Adaptation on Point Clouds for 6D Pose Estimation in Bin-Picking Scenarios**, International Conference on Intelligent Robots and Systems (IROS), 2023       
L. Zhao, M. Sun, W.J. Lv, X.Y. Zhang, L. Zeng      
[[Paper](https://ieeexplore.ieee.org/abstract/document/10341920)]
* **SD-Net: Symmetric-Aware Keypoint Prediction and Domain Adaptation for 6D Pose Estimation In Bin-picking Scenarios**, International Conference on Intelligent Robots and Systems (IROS), 2024       
D.T. Huang, E.T. Lin, L. Chen, L.F. Liu, L. Zeng      
[[Paper](https://ieeexplore.ieee.org/abstract/document/10802595)]

#### Transport

* **SkiROS—A Skill-Based Robot Control Platform on Top of ROS**, A. Koubaa (Ed.) Robot Operating System (ROS): The Complete Reference (Volume 2), Springer International Publishings, 2023       
F. Rovida, M. Crosby, D. Holz, A.S. Polydoros, B. Großmann, R.P.A. Petrick, V. Krüger    
[[Paper](https://link.springer.com/chapter/10.1007/978-3-319-54927-9_4)]
* **Digital description of products, processes and resources for task-oriented programming of assembly systems**, Journal of Intelligent Manufacturing, 2017       
J. Backhaus, G. Reinhart      
[[Paper](https://link.springer.com/article/10.1007/s10845-015-1063-3)]
* **RoBetArme Project: Human-robot collaborative construction system for shotcrete digitization and automation through advanced perception, cognition, mobility and additive manufacturing skills**, Open research Europe, 2024       
I. Kostavelis, L. Nalpantidis, R. Detry, H. Bruyninckx, A. Billard, S. Christian, M. Bosch et al.    
[[Paper](https://pmc.ncbi.nlm.nih.gov/articles/PMC10879757/)]
* **Ontology Based AI Planning and Scheduling for Robotic Assembly**, International Conference on Intelligent Robots and Systems (IROS), 2024       
J. Zhao, B. Vogel-Heuser, J. Ao, Y. Wu, L. Zhang, F. Hartl, D. Hujo, Z. Bing, F. Wu, A. Knoll, S. Haddadin, B. Vojanec, T. Markert, A. Kraft      
[[Paper](https://ieeexplore.ieee.org/abstract/document/10802295)]
* **SkiROS2: A skill-based Robot Control Platform for ROS**, International Conference on Intelligent Robots and Systems (IROS), 2023       
M. Mayr, F. Rovida, V. Krueger    
[[Paper](https://ieeexplore.ieee.org/abstract/document/10342216)]
* **A Taxonomic Framework for Task Modeling and Knowledge Transfer in Manufacturing Robotics**, Association for the Advancement of Artificial Intelligence(AAAI), 2012       
J. Huckaby, H.I. Christensen    
[[Paper](https://cdn.aaai.org/ocs/ws/ws0915/5337-22710-1-PB.pdf)]
* **Skill-based Engineering and Control on Field-Device-Level with OPC UA**, International Conference on Emerging Technologies and Factory Automation (ETFA), 2019       
P. Zimmermann, E. Axmann, B. Brandenbourger, K. Dorofeev, A. Mankowski, P. Zanini    
[[Paper](https://ieeexplore.ieee.org/abstract/document/8869473)]
* **Autonomous planning for mobile manipulation services based on multi-level robot skills**, International Conference on Intelligent Robots and Systems, 2009       
M. weser, J. Zhang    
[[Paper](https://ieeexplore.ieee.org/abstract/document/5353901)]
* **Intuitive skill-level programming of industrial handling tasks on a mobile manipulator**, International Conference on Intelligent Robots and Systems, 2014       
M.R. Pedersen, D.L. Herzog, V. Krüger      
[[Paper](https://ieeexplore.ieee.org/abstract/document/6943203)]
* **Robot skills for manufacturing: From concept to industrial deployment, Robotics and Computer-Integrated Manufacturing**, Robotics and Computer-Integrated Manufacturing, 2016       
M.R. Pedersen, L. Nalpantidis, R.S. Andersen, C. Schou, S. Bøgh, V. Krüger, O. Madsen      
[[Paper](https://www.sciencedirect.com/science/article/pii/S0736584515000575)]
* **A Vertical and Cyber–Physical Integration of Cognitive Robots in Manufacturing**, Proceedings of the IEEE, 2016       
V. Krueger, A. Chazoule, M. Crosby, A. Lasnier, M.R. Pedersen, F. Rovida, L. Nalpantidis, R. Petrick, C. Toscano, G. Veiga      
[[Paper](https://ieeexplore.ieee.org/abstract/document/7440782/)]
* **Testing the vertical and cyber-physical integration of cognitive robots in manufacturing**, Robotics and Computer-Integrated Manufacturing, 2019       
V. Krueger, F. Rovida, B. Grossmann, R. Petrick, M. Crosby, A. Charzoule, G. Martin Garcia, S. Behnke, C. Toscano, G. Veiga      
[[Paper](https://www.sciencedirect.com/science/article/pii/S0736584517304465)]
* **Integration of Autonomous Task Planning into Reconfigurable Skill-Based Industrial Robots**, International Conference on Emerging Technologies and Factory Automation (ETFA), 2020       
L. Heuss, G. Reinhart      
[[Paper](https://ieeexplore.ieee.org/abstract/document/9212005/)]
* **Design and development of a software architecture for autonomous mobile manipulators in industrial environments**, International Conference on Industrial Technology (ICIT), 2015       
F. Rovida, V. Krüger      
[[Paper](https://ieeexplore.ieee.org/abstract/document/7125585)]
* **Concept for the automated adaption of abstract planning domains for specific application cases in skills-based industrial robotics**, Journal of Intelligent Manufacturing, 2024       
L. Heuss, D. Gebauer, G. Reinhart      
[[Paper](https://link.springer.com/article/10.1007/s10845-023-02211-3)]
* **Does your Robot have Skillss**, International Symposium on Robotics, 2012       
S. Bøgh, O.S. Nielsen, M.R. Pedersen, V. Krüger, O. Madsen      
[[Paper](https://vbn.aau.dk/en/publications/does-your-robot-have-skills)]
* **Modular lightweight robot system for aircraft production using a generic OPC UA skill concept**, Production Engineering, 2023      
P. Koch, P. Rawal, N. Töpfer, T. Haß, C. Böhlmann, W. Hintze      
[[Paper](https://link.springer.com/article/10.1007/s11740-023-01183-w)]
* **Flexible modeling and execution of semantic manufacturing processes for robot systems**, International Conference on Emerging Technologies and Factory Automation (ETFA), 2024       
I. Kessler, A. Perzylo      
[[Paper](https://ieeexplore.ieee.org/abstract/document/10710791)]
* **Integration of a Skill-based Collaborative Mobile Robot in a Smart Cyber-physical Environment**, Procedia Manufacturing, 2017      
R.E. Andersen, E.B. Hansen, D. Cerny, S. Madsen, B. Pulendralingam, S. Bøgh, D. Chrysostomou      
[[Paper](https://www.sciencedirect.com/science/article/pii/S2351978917304171)]
* **Production planning for collaborating resources in cyber-physical production systems**, Production Engineering, 2023      
P. Koch, P. Rawal, N. Töpfer, T. Haß, C. Böhlmann, W. Hintze      
[[Paper](https://www.sciencedirect.com/science/article/pii/S2212827120306089)]
* **ROS-Based Robot Simulation for Repetitive Labor-Intensive Construction Tasks**, International Conference on Industrial Informatics (INDIN), 2020      
R. Lankin, K. Kim, P.C. Huang      
[[Paper](https://ieeexplore.ieee.org/abstract/document/9442192)]
* **A Two-Stage Reinforcement Learning Approach for Robot Navigation in Long-range Indoor Dense Crowd Environments**, International Conference on Intelligent Robots and Systems (IROS), 2024      
X.H. Jing, X. Xiong, F.H. Li, T. Zhang, L. Zeng      
[[Paper](https://ieeexplore.ieee.org/abstract/document/10801711)]
* **Mobile Robot Oriented Large-Scale Indoor Dataset for Dynamic Scene Understanding**, International Conference on Robotics and Automation (ICRA), 2024      
Y.F. Tang, C. Tai, F.X. Chen, W.T. Zhang, T. Zhang, X.P. Liu, Y.J. Liu, L. Zeng      
[[Paper](https://ieeexplore.ieee.org/abstract/document/10611489)]

#### Press-fit

* **Skill Manipulation Method of Industrial Robot Based on Knowledge Graph for Assembly Scene**, Cognitive Computation and Systems, 2023       
F. Sun, J. Li, H. Liu, Z. Chu    
[[Paper](https://link.springer.com/chapter/10.1007/978-981-99-2789-0_24)]

* **Learning-Based Automation of Robotic Assembly for Smart Manufacturing**, Proceedings of the IEEE, 2021       
S. Ji, S. Lee, S. Yoo, I. Suh, I. Kwon, F.C. Park, S. Lee, H. Kim    
[[Paper](https://ieeexplore.ieee.org/abstract/document/9383829)]

* **A Prototype-Based Skill Model for Specifying Robotic Assembly Tasks**, IEEE International Conference on Robotics and Automation (ICRA), 2018       
F. Nägele, L. Halt, P. Tenbrock, A. Pott      
[[Paper](https://ieeexplore.ieee.org/abstract/document/8462885)]

* **Ontology Based AI Planning and Scheduling for Robotic Assembly**, International Conference on Intelligent Robots and Systems (IROS), 2024       
J. Zhao, B. Vogel-Heuser, J. Ao, Y. Wu, L. Zhang, F. Hartl, D. Hujo, Z. Bing, F. Wu, A. Knoll, S. Haddadin, B. Vojanec, T. Markert, A. Kraft      
[[Paper](https://ieeexplore.ieee.org/abstract/document/10802295)]

* **SkiROS2: A skill-based Robot Control Platform for ROS**, International Conference on Intelligent Robots and Systems (IROS), 2023       
M. Mayr, F. Rovida, V. Krueger    
[[Paper](https://ieeexplore.ieee.org/abstract/document/10342216)]

* **A Taxonomic Framework for Task Modeling and Knowledge Transfer in Manufacturing Robotics**, Association for the Advancement of Artificial Intelligence(AAAI), 2012       
J. Huckaby, H.I. Christensen    
[[Paper](https://cdn.aaai.org/ocs/ws/ws0915/5337-22710-1-PB.pdf)]

* **A new skill based robot programming language using UML/P Statecharts**, IEEE International Conference on Robotics and Automation (ICRA), 2013       
U. Thomas, G. Hirzinger, B. Rumpe, C. Schulze, A. Wortmann    
[[Paper](https://ieeexplore.ieee.org/abstract/document/6630615)]

* **RAZER—A HRI for Visual Task-Level Programming and Intuitive Skill Parameterization**, IEEE Robotics and Automation Letters, 2018       
F. Steinmetz, A. Wollschläger, R. Weitschat    
[[Paper](https://ieeexplore.ieee.org/abstract/document/8269311)]

* **Intuitive Task-Level Programming by Demonstration Through Semantic Skill Recognition**, IEEE Robotics and Automation Letters, 2019       
F. Steinmetz, V. Nitsch, F. Stulp    
[[Paper](https://ieeexplore.ieee.org/abstract/document/8763979)]

* **Knowledge for Synchronized Dual-Arm Robot Programming**, Association for the Advancement of Artificial Intelligence(AAAI), 2017       
M. Stenmark, E.A. Topp, M. Haage, J. Malec    
[[Paper](https://cdn.aaai.org/ocs/16021/16021-69860-1-PB.pdf)]

* **Skill-based Engineering and Control on Field-Device-Level with OPC UA**, International Conference on Emerging Technologies and Factory Automation (ETFA), 2019       
P. Zimmermann, E. Axmann, B. Brandenbourger, K. Dorofeev, A. Mankowski, P. Zanini    
[[Paper](https://ieeexplore.ieee.org/abstract/document/8869473)]

* **From Demonstrations to Skills for High-Level Programming of Industrial Robots**, AAAI, 2016       
M. Stenmark, E.A. Topp    
[[Paper](https://cdn.aaai.org/ocs/14091/14091-62035-1-PB.pdf)]

* **Learning and Sequencing of Object-Centric Manipulation Skills for Industrial Tasks**, International Conference on Intelligent Robots and Systems (IROS), 2020       
L. Rozo, M. Guo, A.G. Kupcsik, M. Todescato, P. Schillinger, M. Giftthaler, M. Ochs, M. Spies, N. Waniek, P. Kesper, M. Burger      
[[Paper](https://ieeexplore.ieee.org/abstract/document/9341570)]

* **Dynamic task classification and assignment for the management of human-robot collaborative teams in workcells**, The International Journal of Advanced Manufacturing Technology, 2018       
G. Bruno, D. Antonelli      
[[Paper](https://link.springer.com/article/10.1007/s00170-018-2400-4)]

* **A Framework for Robot Manipulation: Skill Formalism, Meta Learning and Adaptive Control**, IEEE International Conference on Robotics and Automation (ICRA), 2019       
L. Johannsmeier, M. Gerchow, S. Haddadin      
[[Paper](https://ieeexplore.ieee.org/abstract/document/8793542)]

* **Task Adaptation Based on Hierarchical Constraints Classification for Safe Industrial Robots**, IEEE/ASME Transactions on Mechatronics, 2015       
N.M. Ceriani, A.M. Zanchettin, P. Rocco, A. Stolt, A. Robertsson      
[[Paper](https://ieeexplore.ieee.org/abstract/document/7102768)]

* **Task planning for human robot interactive processes**, International Conference on Emerging Technologies and Factory Automation (ETFA), 2016       
N. Wantia, M. Esen, A. Hengstebeck, F. Heinze, J. Rossmann, J. Deuse, B. Kuhlenkoetter      
[[Paper](https://ieeexplore.ieee.org/abstract/document/7733523)]

* **Does your Robot have Skillss**, International Symposium on Robotics, 2012       
S. Bøgh, O.S. Nielsen, M.R. Pedersen, V. Krüger, O. Madsen      
[[Paper](https://vbn.aau.dk/en/publications/does-your-robot-have-skills)]

* **Cyber-Physical-Robotics Modelling of modular robot cells for automated planning and execution of assembly tasks**, Mechatronics, 2016       
J. Michniewicz, G. Reinhart      
[[Paper](https://www.sciencedirect.com/science/article/pii/S0957415815000574)]

* **Flexible skill-based control for robot cells in manufacturing**, Frontiers in Robotics and Ai, 2022       
T. Wiese, J. Abicht, C. Friedrich, A. Hellmich, S. Ihlenfeldt      
[[Paper](https://www.frontiersin.org/journals/robotics-and-ai/articles/10.3389/frobt.2022.1014476/full)]

* **Learn from Robot: Transferring Skills for Diverse Manipulation via Cycle Generative Networks**, International Conference on Automation Science and Engineering (CASE), 2023       
Q. Yang, J.A. Stork, T. Stoyanov      
[[Paper](https://ieeexplore.ieee.org/abstract/document/10260484)]

* **Motion Generators Combined with Behavior Trees: A Novel Approach to Skill Modelling**, International Conference on Intelligent Robots and Systems (IROS), 2018       
F. Rovida, D. Wuthier, B. Grossmann, M. Fumagalli, V. Krüger      
[[Paper](https://ieeexplore.ieee.org/abstract/document/8594319/)]

* **Skill acquisition for industrial robots: From stand-alone to distributed learning**, International Conference on Automatica (ICA-ACCA), 2016       
I. Lopez-Juarez      
[[Paper](https://ieeexplore.ieee.org/abstract/document/7778517)]

* **Learning Forceful Manipulation Skills from Multi-modal Human Demonstrations**, International Conference on Intelligent Robots and Systems (IROS), 2021       
A.T. Le, M. Guo, N.v. Duijkeren, L. Rozo, R. Krug, A.G. Kupcsik, M. Bürger      
[[Paper](https://ieeexplore.ieee.org/abstract/document/9636828)]

* **Simulation-based Learning of the Peg-in-Hole Process Using Robot-Skills**, International Conference on Intelligent Robots and Systems (IROS), 2022       
A. Lämmle, P. Tenbrock, B. Bálint, F. Nägele, W. Kraus, J. Váncza, M.F. Huber      
[[Paper](https://ieeexplore.ieee.org/abstract/document/9982212)]


#### Screw

* **Digital description of products, processes and resources for task-oriented programming of assembly systems**, Journal of Intelligent Manufacturing, 2017       
J. Backhaus, G. Reinhart      
[[Paper](https://link.springer.com/article/10.1007/s10845-015-1063-3)]

* **A Prototype-Based Skill Model for Specifying Robotic Assembly Tasks**, IEEE International Conference on Robotics and Automation (ICRA), 2018       
F. Nägele, L. Halt, P. Tenbrock, A. Pott      
[[Paper](https://ieeexplore.ieee.org/abstract/document/8462885)]

* **Ontology Based AI Planning and Scheduling for Robotic Assembly**, International Conference on Intelligent Robots and Systems (IROS), 2024       
J. Zhao, B. Vogel-Heuser, J. Ao, Y. Wu, L. Zhang, F. Hartl, D. Hujo, Z. Bing, F. Wu, A. Knoll, S. Haddadin, B. Vojanec, T. Markert, A. Kraft      
[[Paper](https://ieeexplore.ieee.org/abstract/document/10802295)]

* **Flexible Robotic Assembly Based on Ontological Representation of Tasks, Skills, and Resources**, International Joint Conferences on Artificial Intelligence Organization, 2021       
P. Schäfer, F. Steinmetz, S. Schneyer, T. Bachmann, T. Eiband, F. Lay, A. Padalkar, C. Sürig, F. Stulp, K. Nottensteiner      
[[Paper](https://elib.dlr.de/144979/)]

* **Towards Digital Twins for Industrial Assembly - Improving Robot Solutions by Intuitive User Guidance and Robot Programming**, IEEE International Conference on Emerging Technologies and Factory Automation (ETFA), 2020       
L.C. Sørensen, S. Mathiesen, R. Waspe, C. Schlette    
[[Paper](https://ieeexplore.ieee.org/abstract/document/9212072)]

* **MASD: A Multimodal Assembly Skill Decoding System for Robot Programming by Demonstration**, IEEE Transactions on Automation Science and Engineering, 2018       
Y. Wang, Y. Jiao, R. Xiong, H. Yu, J. Zhang, Y. Liu   
[[Paper](https://ieeexplore.ieee.org/abstract/document/8263146)]

* **Dynamic task classification and assignment for the management of human-robot collaborative teams in workcells**, The International Journal of Advanced Manufacturing Technology, 2018       
G. Bruno, D. Antonelli      
[[Paper](https://link.springer.com/article/10.1007/s00170-018-2400-4)]

* **Modular lightweight robot system for aircraft production using a generic OPC UA skill concept**, Production Engineering, 2023      
P. Koch, P. Rawal, N. Töpfer, T. Haß, C. Böhlmann, W. Hintze      
[[Paper](https://link.springer.com/article/10.1007/s11740-023-01183-w)]

* **Robot Learning from Demonstration based on Human-in-the-loop Reinforcement Learning**, International Conference on Automation Science and Engineering (CASE), 2024       
C. Li, T. Yu, Q. Chang      
[[Paper](https://ieeexplore.ieee.org/abstract/document/10711559/)]

* **Towards Self-Configuring Plug & Produce Robot Systems Based on Ontologies**, International Conference on Automation, Robotics and Applications (ICARA), 2023       
C. Eymüller, J. Hanke, A. Poeppel, W. Reif      
[[Paper](https://ieeexplore.ieee.org/abstract/document/10126075)]

* **Learning Forceful Manipulation Skills from Multi-modal Human Demonstrations**, International Conference on Intelligent Robots and Systems (IROS), 2021      
A.T. Le, M. Guo, N.v. Duijkeren, L. Rozo, R. Krug, A.G. Kupcsik, M. Bürger      
[[Paper](https://ieeexplore.ieee.org/abstract/document/9636828/)]

* **Skill-based programming of complex robotic assembly tasks for industrial application**, e & i Elektrotechnik und Informationstechnik, 2019      
S.C. Akkaladevi, A. Pichler, M. Plasch, M. Ikeda, M. Hofmann      
[[Paper](https://link.springer.com/article/10.1007/s00502-019-00741-4)]

* **Programming: Transferring Task Constraints into Constraint-Based Unified Force-Impedance Control**, International Conference on Robotics and Automation (ICRA), 2024      
K. Karacan, R.J. Kirschner, H. Sadeghian, F. Wu, S. Haddadin        
[[Paper](https://frankiewoo.github.io/publication/karacan-2024-icra/karacan-2024-icra.pdf)]


#### Weld

* **Digital description of products, processes and resources for task-oriented programming of assembly systems**, Journal of Intelligent Manufacturing, 2017         
J. Backhaus, G. Reinhart   
[[Paper](https://link.springer.com/article/10.1007/s10845-015-1063-3)]

* **Automatic welding-robot programming based on product-process-resource models**, The International Journal of Advanced Manufacturing Technology, 2024         
I.-M. Sarivan, O. Madsen, B.V. Wæhrens   
[[Paper](https://link.springer.com/article/10.1007/s00170-024-13409-x)]

* **Dynamic task classification and assignment for the management of human-robot collaborative teams in workcells**, The International Journal of Advanced Manufacturing Technology, 2018         
G. Bruno, D. Antonelli   
[[Paper](https://link.springer.com/article/10.1007/s00170-018-2400-4)]

* **Skill acquisition for industrial robots: From stand-alone to distributed learning**, The IEEE International Conference on Automatica (ICA-ACCA), 2016         
I. Lopez-Juarez   
[[Paper](https://ieeexplore.ieee.org/abstract/document/7778517)]

#### Rivet & Glue

* **Enhancing Learning Capabilities of Movement Primitives under Distributed Probabilistic Framework for Assembly Tasks**, IEEE International Conference on Systems, Man, and Cybernetics (SMC), 2020         
L. Wang, S. Jia, G. Wang, A. Turner, S. Ratchev   
[[Paper](https://ieeexplore.ieee.org/abstract/document/9283066)]

* **A Taxonomic Framework for Task Modeling and Knowledge Transfer in Manufacturing Robotics**, CogRob@AAAI, 2012         
J. Huckaby, H.I. Christensen   
[[Paper](https://cdn.aaai.org/ocs/ws/ws0915/5337-22710-1-PB.pdf)]

#### Measure

* **SkiROS—A Skill-Based Robot Control Platform on Top of ROS**, Robot Operating System (ROS): The Complete Reference, 2017         
F. Rovida, M. Crosby, D. Holz, A.S. Polydoros, B. Großmann, R.P.A. Petrick, V. Krüger   
[[Paper](https://link.springer.com/chapter/10.1007/978-3-319-54927-9_4)]

* **Learning-Based Automation of Robotic Assembly for Smart Manufacturing**, Proceedings of the IEEE, 2021         
S. Ji, S. Lee, S. Yoo, I. Suh, I. Kwon, F.C. Park, S. Lee, H. Kim   
[[Paper](https://ieeexplore.ieee.org/abstract/document/9383829)]

* **A Prototype-Based Skill Model for Specifying Robotic Assembly Tasks**, IEEE International Conference on Robotics and Automation (ICRA), 2018         
F. Nägele, L. Halt, P. Tenbrock   
[[Paper](https://ieeexplore.ieee.org/abstract/document/8462885)]

* **A Taxonomic Framework for Task Modeling and Knowledge Transfer in Manufacturing Robotics**, CogRob@AAAI, 2012         
J. Huckaby, H.I. Christensen   
[[Paper](https://cdn.aaai.org/ocs/ws/ws0915/5337-22710-1-PB.pdf)]

* **Definition and Initial Case-Based Evaluation of Hardware-Independent Robot Skills for Industrial Robotic Co-Workers**, ISR/Robotik 2014; 41st International Symposium on Robotics, 2014         
R.H. Andersen, T. Solund, J. Hallam   
[[Paper](https://ieeexplore.ieee.org/abstract/document/6840115)]

* **Toward a library of manipulation actions based on semantic object-action relations**, IEEE/RSJ International Conference on Intelligent Robots and Systems, 2013         
M.J. Aein, E.E. Aksoy, M. Tamosiunaite, J. Papon, A. Ude, F. Wörgötter   
[[Paper](https://ieeexplore.ieee.org/abstract/document/6697011)]

* **Skill-based Engineering and Control on Field-Device-Level with OPC UA**, IEEE International Conference on Emerging Technologies and Factory Automation (ETFA), 2019         
P. Zimmermann, E. Axmann, B. Brandenbourger, K. Dorofeev, A. Mankowski, P. Zanini   
[[Paper](https://ieeexplore.ieee.org/abstract/document/8869473)]

* **Teaching new tricks to a robot learning to solve a task by imitation**, IEEE Conference on Robotics, Automation and Mechatronics, 2010         
C.A.A. Calderon, R.E. Mohan, Z. Changjiu   
[[Paper](https://ieeexplore.ieee.org/abstract/document/5513180)]

* **Skill-based Programming Framework for Composable Reactive Robot Behaviors**, IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2020         
Y. Pane, E. Aertbeliën, J.D. Schutter, W. Decré  
[[Paper](https://ieeexplore.ieee.org/abstract/document/9340985)]

* **Autonomous planning for mobile manipulation services based on multi-level robot skills**, IEEE/RSJ International Conference on Intelligent Robots and Systems, 2009         
M. weser, J. Zhang   
[[Paper](https://ieeexplore.ieee.org/abstract/document/5353901)]

* **From Demonstrations to Skills for High-Level Programming of Industrial Robots**, AAAI Fall Symposia, 2016         
M. Stenmark, E.A. Topp   
[[Paper](https://cdn.aaai.org/ocs/14091/14091-62035-1-PB.pdf)]

* **Ontology-Based Knowledge Representation for Increased Skill Reusability in Industrial Robots**, IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2018         
E.A. Topp, M. Stenmark, A. Ganslandt, A. Svensson, M. Haage, J. Malec   
[[Paper](https://ieeexplore.ieee.org/abstract/document/8593566)]

* **Learning and Sequencing of Object-Centric Manipulation Skills for Industrial Tasks**, IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2020         
L. Rozo, M. Guo, A.G. Kupcsik, M. Todescato, P. Schillinger, M. Giftthaler, M. Ochs, M. Spies, N. Waniek, P. Kesper, M. Burger   
[[Paper](https://ieeexplore.ieee.org/abstract/document/9341570)]

* **Intuitive skill-level programming of industrial handling tasks on a mobile manipulator**, IEEE/RSJ International Conference on Intelligent Robots and Systems, 2014         
M.R. Pedersen, D.L. Herzog, V. Krüger   
[[Paper](https://ieeexplore.ieee.org/abstract/document/6943203)]

* **Robot skills for manufacturing: From concept to industrial deployment**, Robotics and Computer-Integrated Manufacturing, 2016         
M.R. Pedersen, L. Nalpantidis, R.S. Andersen, C. Schou, S. Bøgh, V. Krüger, O. Madsen   
[[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0736584515000575)]

* **A Hierarchical Human-Robot Interaction-Planning Framework for Task Allocation in Collaborative Industrial Assembly Processes**, IEEE Robotics and Automation Letters, 2017         
L. Johannsmeier, S. Haddadin   
[[Paper](https://ieeexplore.ieee.org/abstract/document/7421993)]

* **Integration of a Skill-based Collaborative Mobile Robot in a Smart Cyber-physical Environment**, Procedia Manufacturing, 2017         
R.E. Andersen, E.B. Hansen, D. Cerny, S. Madsen, B. Pulendralingam, S. Bøgh, D. Chrysostomou   
[[Paper](https://www.sciencedirect.com/science/article/pii/S2351978917304171)]

* **A Vertical and Cyber–Physical Integration of Cognitive Robots in Manufacturing**, Proceedings of the IEEE, 2016         
V. Krueger, A. Chazoule, M. Crosby, A. Lasnier, M.R. Pedersen, F. Rovida, L. Nalpantidis, R. Petrick, C. Toscano, G. Veiga   
[[Paper](https://ieeexplore.ieee.org/abstract/document/7440782)]

* **Testing the vertical and cyber-physical integration of cognitive robots in manufacturing,**, Robotics and Computer-Integrated Manufacturing, 2019         
V. Krueger, F. Rovida, B. Grossmann, R. Petrick, M. Crosby, A. Charzoule, G. Martin Garcia, S. Behnke, C. Toscano, G. Veiga   
[[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0736584517304465)]

* **Integration of Autonomous Task Planning into Reconfigurable Skill-Based Industrial Robots**, 25th IEEE International Conference on Emerging Technologies and Factory Automation (ETFA), 2020         
L. Heuss, G. Reinhart   
[[Paper](https://ieeexplore.ieee.org/abstract/document/9212005)]

* **Reactive Task Adaptation Based on Hierarchical Constraints Classification for Safe Industrial Robots**, IEEE/ASME Transactions on Mechatronics, 2015         
N.M. Ceriani, A.M. Zanchettin, P. Rocco, A. Stolt, A. Robertsson   
[[Paper](https://ieeexplore.ieee.org/abstract/document/7102768)]

* **PPR-Net:Point-wise Pose Regression Network for Instance Segmentation and 6D Pose Estimation in Bin-picking Scenarios**, IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2019         
Z. Dong, S. Liu, T. Zhou, H. Cheng, L. Zeng, X. Yu, H. Liu   
[[Paper](https://ieeexplore.ieee.org/abstract/document/8967895)]

* **PPR-Net++: Accurate 6-D Pose Estimation in Stacked Scenarios**, IEEE Transactions on Automation Science and Engineering, 2022         
L. Zeng, W.J. Lv, Z.K. Dong, Y.J. Liu   
[[Paper](https://ieeexplore.ieee.org/abstract/document/9537584)]

* **Reinforcement Learning Based Pushing and Grasping Objects from Ungraspable Poses**, IEEE International Conference on Robotics and Automation (ICRA), 2023         
H. Zhang, H. Liang, L. Cong, J. Lyu, L. Zeng, P. Feng, J. Zhang   
[[Paper](https://ieeexplore.ieee.org/abstract/document/10160491)]

* **Domain Adaptation on Point Clouds for 6D Pose Estimation in Bin-Picking Scenarios**, IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2023         
L. Zhao, M. Sun, W.J. Lv, X.Y. Zhang, L. Zeng   
[[Paper](https://ieeexplore.ieee.org/abstract/document/10341920)]

* **SD-Net: Symmetric-Aware Keypoint Prediction and Domain Adaptation for 6D Pose Estimation In Bin-picking Scenarios**, IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2024         
D.T. Huang, E.T. Lin, L. Chen, L.F. Liu, L. Zeng   
[[Paper](https://ieeexplore.ieee.org/abstract/document/10802595)]

* **Production planning for collaborating resources in cyber-physical production systems**, Procedia CIRP, 2020         
M. Krä, L. Vogt, C. Härdtlein, S. Schiele, J. Schilp   
[[Paper](https://www.sciencedirect.com/science/article/pii/S2212827120306089)]

* **ROS-Based Robot Simulation for Repetitive Labor-Intensive Construction Tasks**, IEEE 18th International Conference on Industrial Informatics (INDIN), 2020         
R. Lankin, K. Kim, P.C. Huang   
[[Paper](https://ieeexplore.ieee.org/abstract/document/9442192)]

* **A Two-Stage Reinforcement Learning Approach for Robot Navigation in Long-range Indoor Dense Crowd Environments**, IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS) 2024         
X.H. Jing, X. Xiong, F.H. Li, T. Zhang, L. Zeng   
[[Paper](https://ieeexplore.ieee.org/abstract/document/10801711)]

* **Mobile Robot Oriented Large-Scale Indoor Dataset for Dynamic Scene Understanding**, IEEE International Conference on Robotics and Automation (ICRA), 2024         
Y.F. Tang, C. Tai, F.X. Chen, W.T. Zhang, T. Zhang, X.P. Liu, Y.J. Liu, L. Zeng   
[[Paper](https://ieeexplore.ieee.org/abstract/document/10611489)]

* **Skill acquisition for industrial robots: From stand-alone to distributed learning**, IEEE International Conference on Automatica (ICA-ACCA), 2016         
I. Lopez-Juarez   
[[Paper](https://ieeexplore.ieee.org/abstract/document/7778517)]

* **Skill-based programming of complex robotic assembly tasks for industrial application**, e & i Elektrotechnik und Informationstechnik, 2019         
S.C. Akkaladevi, A. Pichler, M. Plasch, M. Ikeda, M. Hofmann   
[[Paper](https://link.springer.com/article/10.1007/s00502-019-00741-4)]

* **Dual-Alignment Domain Adaptation for Pedestrian Trajectory Prediction**, IEEE Robotics and Automation Letters, 2024         
W. Li, F. Li, X. Jing, P. Feng, L. Zeng   
[[Paper](https://ieeexplore.ieee.org/abstract/document/10719677)]

* **FusedNet: End-to-End Mobile Robot Relocalization in Dynamic Large-Scale Scene, IEEE Robotics and Automation Letters**, IEEE Robotics and Automation Letters, 2024         
F.x. Chen, Y. Tang, C. Tai, X.p. Liu, X. Wu, T. Zhang, L. Zeng   
[[Paper](https://ieeexplore.ieee.org/abstract/document/10457947)]


#### Check

* **An extendable framework for intelligent and easily configurable skills-based industrial robot applications**, The International Journal of Advanced Manufacturing Technology, 2022         
L. Heuss, C. Gonnermann, G. Reinhart   
[[Paper](https://link.springer.com/article/10.1007/s00170-022-09071-w)]

* **Digital description of products, processes and resources for task-oriented programming of assembly systems**, Journal of Intelligent Manufacturing, 2017         
J. Backhaus, G. Reinhart   
[[Paper](https://link.springer.com/article/10.1007/s10845-015-1063-3)]

* **A Prototype-Based Skill Model for Specifying Robotic Assembly Tasks**, IEEE International Conference on Robotics and Automation (ICRA), 2018         
F. Nägele, L. Halt, P. Tenbrock, A. Pott   
[[Paper](https://ieeexplore.ieee.org/abstract/document/8462885)]

* **Collaborative Programming of Conditional Robot Tasks**, IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2020         
C. Willibald, T. Eiband, D. Lee   
[[Paper](https://ieeexplore.ieee.org/abstract/document/9341212)]

* **Toward a library of manipulation actions based on semantic object-action relations**, IEEE/RSJ International Conference on Intelligent Robots and Systems, 2017         
M.J. Aein, E.E. Aksoy, M. Tamosiunaite, J. Papon, A. Ude, F. Wörgötter   
[[Paper](https://ieeexplore.ieee.org/abstract/document/6697011)]

* **Knowledge for Synchronized Dual-Arm Robot Programming**, AAAI Fall Symposia, 2017         
I. Lanese, U.P. Schultz, I. Ulidowski   
[[Paper](https://cdn.aaai.org/ocs/16021/16021-69860-1-PB.pdf)]

* **Skill-based Programming Framework for Composable Reactive Robot Behaviors**, IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2020         
Y. Pane, E. Aertbeliën, J.D. Schutter, W. Decré   
[[Paper](https://ieeexplore.ieee.org/abstract/document/9340985)]

* **A Hierarchical Human-Robot Interaction-Planning Framework for Task Allocation in Collaborative Industrial Assembly Processes**, IEEE Robotics and Automation Letters, 2017         
L. Johannsmeier, S. Haddadin   
[[Paper](https://ieeexplore.ieee.org/abstract/document/7421993)]

* **Integration of a Skill-based Collaborative Mobile Robot in a Smart Cyber-physical Environment**, Procedia Manufacturing, 2017         
R.E. Andersen, E.B. Hansen, D. Cerny, S. Madsen, B. Pulendralingam, S. Bøgh, D. Chrysostomou   
[[Paper](https://www.sciencedirect.com/science/article/pii/S2351978917304171)]

* **A Vertical and Cyber–Physical Integration of Cognitive Robots in Manufacturing**, Proceedings of the IEEE, 2016         
V. Krueger, A. Chazoule, M. Crosby, A. Lasnier, M.R. Pedersen, F. Rovida, L. Nalpantidis, R. Petrick, C. Toscano, G. Veiga   
[[Paper](https://ieeexplore.ieee.org/abstract/document/7440782)]

* **Testing the vertical and cyber-physical integration of cognitive robots in manufacturing**, Robotics and Computer-Integrated Manufacturing, 2019         
V. Krueger, F. Rovida, B. Grossmann, R. Petrick, M. Crosby, A. Charzoule, G. Martin Garcia, S. Behnke, C. Toscano, G. Veiga   
[[Paper](https://www.sciencedirect.com/science/article/abs/pii/S0736584517304465)]

* **Reactive Task Adaptation Based on Hierarchical Constraints Classification for Safe Industrial Robots**, IEEE/ASME Transactions on Mechatronics, 2015         
N.M. Ceriani, A.M. Zanchettin, P. Rocco, A. Stolt, A. Robertsson   
[[Paper](https://ieeexplore.ieee.org/abstract/document/7102768)]

* **Does your Robot have Skills**, Proceedings of the 43rd international symposium on robotics, 2012       
S. Bøgh, O.S. Nielsen, M.R. Pedersen, V. Krüger, O. Madsen  
[[Paper](https://vbn.aau.dk/ws/portalfiles/portal/69945674/ISR_2012_Paper_ID_1158_FINAL.pdf)]

* **Learning Hierarchical Robot Skills Represented by Behavior Trees from Natural Language**, Cooperative Information Systems: 29th International Conference, 2024       
K. Wang, Y. Zhao, S. Dai, M. Yang, Y. He, N. Zhang  
[[Paper](https://link.springer.com/chapter/10.1007/978-3-031-46846-9_20)]

* **Flexible modeling and execution of semantic manufacturing processes for robot systems**, IEEE 29th International Conference on Emerging Technologies and Factory Automation (ETFA), 2024       
I. Kessler, A. Perzylo  
[[Paper](https://ieeexplore.ieee.org/abstract/document/10710791)]

* **Motion Generators Combined with Behavior Trees: A Novel Approach to Skill Modelling**,  IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2018       
. Rovida, D. Wuthier, B. Grossmann, M. Fumagalli, V. Krüger  
[[Paper](https://ieeexplore.ieee.org/abstract/document/8594319)]


#### Spray & 3D-Print

* **RoBetArme Project: Human-robot collaborative construction system for shotcrete digitization and automation through advanced perception, cognition, mobility and additive manufacturing skills**, Open research Europe, 2024         
I. Kostavelis, L. Nalpantidis, R. Detry, H. Bruyninckx, A. Billard, S. Christian, M. Bosch, K. Andronikidis, H. Lund-Nielsen, P. Yosefipor, U. Wajid, R. Tomar, F.L. Martinez, F. Fugaroli, D. Papargyriou, N. Mehandjiev, G. Bhullar, E. Goncalves, J. Bentzen, M. Essenbak, C. Cremona, M. Wong, M. Sanchez, D. Giakoumis, D. Tzovaras   
[[Paper](https://pmc.ncbi.nlm.nih.gov/articles/PMC10879757/)]

* **ROS-Based Robot Simulation for Repetitive Labor-Intensive Construction Tasks**, IEEE 18th International Conference on Industrial Informatics (INDIN), 2020         
R. Lankin, K. Kim, P.C. Huang   
[[Paper](https://ieeexplore.ieee.org/abstract/document/9442192)]


### Control Languages

* **Reversible Execution for Robustness in Embodied AI and Industrial Robots**, IT Professional, 2021         
I. Lanese, U.P. Schultz, I. Ulidowski   
[[Paper](https://ieeexplore.ieee.org/abstract/document/9464113)]

* **Model for Web-Application based Configuration of Modular Production Plants with automated PLC Line Control Code Generation**, Procedia CIRP, 2019         
M. Schäfer, P. Moll, L. Brocke, S. Coutandin, J. Fleischer   
[[Paper](https://www.sciencedirect.com/science/article/pii/S2212827119304317)]

* **A Novel Block-Based Programming Framework for Non-programmers to Validate PLC Based Machine Tools for Automotive Manufacturing Facilities**, 11th International Conference on Developments in eSystems Engineering (DeSE), 2018         
W. Koehler, Y. Jing  
[[Paper](https://ieeexplore.ieee.org/abstract/document/8648600)]

* **From Offline Towards Real-Time Verification for Robot Systems**, IEEE Transactions on Industrial Informatics, 2018         
R. Wang, Y. Wei, H. Song, Y. Jiang, Y. Guan, X. Song, X. Li  
[[Paper](https://ieeexplore.ieee.org/abstract/document/8245858)]

* **From Gestures to Behaviours: An Empirical Study on Behaviour-Driven Development Scenarios to Support End-User Programming of Collaborative Robots**, 8th IFToMM International Symposium on Robotics and Mechatronics (ISRM), 2024         
J.P. De la Rosa, J. Solis, K. Nakamori, G.A.G. Ricardez, J. Håkansson, A.S. Sorensen, T.R. Silva   
[[Paper](https://link.springer.com/chapter/10.1007/978-3-031-59888-3_33)]

* **A Domain Specific Language for Robot Programming in the Wood Industry <i>A Practical Example</i>**, 14th International Conference on Informatics in Control, Automation and Robotics (ICINCO), 2017         
V.J.E. Jiménez, H. Zeiner   
[[Paper](https://pdfs.semanticscholar.org/833e/69fd62e68267bbdf9eb12ec7e93a41b76e8d.pdf)]

* **Using a Textual DSL With Live Graphical Feedback to Improve the CPS' Design Workflow of Hardware Engineers**, 19th Conference on Computer Science and Intelligence Systems (FedCSIS), 2024         
T. Bolwerk, M. Alonso, M. Schuts   
[[Paper](https://ieeexplore.ieee.org/abstract/document/10736067)]

* **A Novel Task Language for Natural Interaction in Human-Robot Systems for Warehouse Logistics**, 14th International Conference on Computer Science & Education (ICCSE), 2019         
P. Detzner, T. Kirks, J. Jost  
[[Paper](https://ieeexplore.ieee.org/abstract/document/8845336)]

* **<i>RoboLang</i>: A Simple Domain Specific Language to Script Robot Interactions**, 16th International Conference on Ubiquitous Robots (UR), 2019         
C.J. Sutherland, B. MacDonald   
[[Paper](https://ieeexplore.ieee.org/abstract/document/8768625)]

* **Salty-A Domain Specific Language for GR(1) Specifications and Designs**, International Conference on Robotics and Automation (ICRA), 2019         
T. Elliott, M. Alshiekh, L.R. Humphrey, L. Pike, U. Topcu   
[[Paper](https://ieeexplore.ieee.org/abstract/document/8793722)]

* **PyDSLRep: A domain-specific language for robotic simulation in V-Rep**, Plos One, 2020         
A.C. Jiménez, J.P. Anzola, V. García-Díaz, R.G. Crespo, L.P. Zhao   
[[Paper](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0235271)]

* **A hybrid approach to user-oriented programming of collaborative robots**, Robotics and Computer-Integrated Manufacturing, 2022         
D. Fogli, L. Gargioni, G. Guida, F. Tampalini  
[[Paper](https://www.sciencedirect.com/science/article/pii/S073658452100106X)]

* **EzSkiROS: enhancing robot skill composition with embedded DSL for early error detection**, Frontiers in Robotics and Ai, 2025         
M. Rizwan, C. Reichenbach, R. Caldas, M. Mayr, V. Krueger   
[[Paper](https://www.frontiersin.org/journals/robotics-and-ai/articles/10.3389/frobt.2024.1363443/full)]

* **Rapid state machine assembly for modular robot control using meta-scripting, templating and code generation**, IEEE-RAS 17th International Conference on Humanoid Robotics (Humanoids), 2017         
B. Ridge, T. Gaspar, A. Ude   
[[Paper](https://ieeexplore.ieee.org/abstract/document/8246943)]

* **Assembly: A Web-Based Multi-Robot Programming and Simulation Tool**, IFAC-PapersOnLine, 2022         
T.B. Ionescu   
[[Paper](https://www.sciencedirect.com/science/article/pii/S2405896322002130)]

* **RoboSC: a domain-specific language for supervisory controller synthesis of ROS applications**, International Conference on Robotics and Automation (ICRA), 2023         
B. Wesselink, K. de Vos, I. Kuertev, M. Reniers, E. Torta   
[[Paper](https://ieeexplore.ieee.org/abstract/document/10161436)]

* **PDDL - The Planning Domain Definition Language**, 1998         
M. Ghallab, C. Knoblock, D. Wilkins, A. Barrett, D. Christianson, M. Friedman, C. Kwok, K. Golden, S. Penberthy, D. Smith, Y. Sun, D. Weld   
[[Paper](https://www.researchgate.net/profile/Craig-Knoblock/publication/2278933_PDDL_-_The_Planning_Domain_Definition_Language/links/0912f50c0c99385e19000000/PDDL-The-Planning-Domain-Definition-Language.pdf)]

* **Architectural modelling for robotics: RoboArch and the CorteX example**, Frontiers in Robotics and Ai, 2022         
W. Barnett, A. Cavalcanti, A. Miyazawa   
[[Paper](https://www.frontiersin.org/journals/robotics-and-ai/articles/10.3389/frobt.2022.991637/full)]

* **Unlocking underrepresented use-cases for large language model-driven human-robot task planning**, Advanced Robotics, 2024         
S. Wanna, F. Parra, R. Valner, K. Kruusamaee, M. Pryor   
[[Paper](https://www.tandfonline.com/doi/full/10.1080/01691864.2024.2366974)]

* **Assembly language design and development for reconfigurable flexible assembly line, Robotics and Computer-Integrated Manufacturing**, Robotics and Computer-Integrated Manufacturing, 2023         
L.C. Xiao, L. Zeng, Z.B. Xu, X.P. Liu   
[[Paper](https://www.sciencedirect.com/science/article/pii/S0736584522001491)]

* **A flexible control system for reconfigurable assembly lines**, Journal of Physics: Conference Series, 2021         
L. Xiao, X. Jing, L. Zeng, X. Liu   
[[Paper](https://iopscience.iop.org/article/10.1088/1742-6596/2029/1/012001/meta)]

## <a id="simulators"> Simulators <a href="#table-of-contents">🔝</a> </a> 

### Robot Simulators

* **Design and use paradigms for Gazebo, an open-source multi-robot simulator**,IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2004         
N. Koenig, A. Howard   
[[Paper](https://ieeexplore.ieee.org/abstract/document/1389727)]

* **Mujoco: A physics engine for model-based control, in:  2012 IEEE/RSJ international conference on intelligent robots and systems**, IEEE/RSJ international conference on intelligent robots and systems, 2012         
E. Todorov, T. Erez, Y. Tass  
[[Paper](https://ieeexplore.ieee.org/abstract/document/6386109)]

* **V-REP: A versatile and scalable robot simulation framework**, IEEE/RSJ International Conference on Intelligent Robots and Systems, 2013         
E. Rohmer, S.P.N. Singh, M. Freese   
[[Paper](https://ieeexplore.ieee.org/abstract/document/6696520)]

* **Pybullet, a python module for physics simulation for games, robotics and machine learning**, 2016         
E. Coumans, Y. Bai   
[[Page](https://pybullet.org/wordpress/)]

* **Isaac gym: High performance gpu-based physics simulation for robot learning**, arXiv, 2021         
V. Makoviychuk, L. Wawrzyniak, Y. Guo, M. Lu, K. Storey, M. Macklin, D. Hoeller, N. Rudin, A. Allshire, A. Handa   
[[Paper](https://arxiv.org/pdf/2108.10470)]

* **Nvidia isaac sim: Robotics simulation and synthetic data**, 2023         
NVIDIA   
[[Page](https://developer.nvidia.com/isaac/sim)]

* **Ai2-thor: An interactive 3d environment for visual ai**, arXiv, 2017         
E. Kolve, R. Mottaghi, W. Han, E. VanderBilt, L. Weihs, A. Herrasti, M. Deitke, K. Ehsani, D. Gordon, Y. Zhu   
[[Paper](https://arxiv.org/pdf/1712.05474)]

* **Virtualhome: Simulating household activities via programs**, Proceedings of the IEEE conference on computer vision and pattern recognition, 2018         
X. Puig, K. Ra, M. Boben, J. Li, T. Wang, S. Fidler, A. Torralba   
[[Paper](https://openaccess.thecvf.com/content_cvpr_2018/papers/Puig_VirtualHome_Simulating_Household_CVPR_2018_paper.pdf)]

* **Vrkitchen: an interactive 3d virtual environment for task-oriented learning**, arXiv, 2019         
X. Gao, R. Gong, T. Shu, X. Xie, S. Wang, S.-C. Zhu   
[[Paper](https://arxiv.org/pdf/1903.05757)]

* **Habitat: A platform for embodied ai research**, Proceedings of the IEEE/CVF international conference on computer vision, 2019         
M. Savva, A. Kadian, O. Maksymets, Y. Zhao, E. Wijmans, B. Jain, J. Straub, J. Liu, V. Koltun, J. Malik   
[[Paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Savva_Habitat_A_Platform_for_Embodied_AI_Research_ICCV_2019_paper.pdf)]

* **igibson 1.0: A simulation environment for interactive tasks in large realistic scenes**, IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2021         
B. Shen, F. Xia, C. Li, R. Martín-Martín, L. Fan, G. Wang, C. Pérez-D’Arpino, S. Buch, S. Srivastava, L. Tchapmi   
[[Paper](https://ieeexplore.ieee.org/abstract/document/9636667)]

* **iGibson 2.0: Object-Centric Simulation for Robot Learning of Everyday Household Tasks**, Conference on Robot Learning, 2022         
C. Li, F. Xia, R. Martín-Martín, M. Lingelbach, S. Srivastava, B. Shen, K.E. Vainio, C. Gokmen, G. Dharan, T. Jain   
[[Paper](https://proceedings.mlr.press/v164/li22b.html)]

* **ThreeDWorld: A Platform for Interactive Multi-Modal Physical Simulation**, Advances in Neural Information Processing Systems (NeurIPS), 2021         
C. Gan, J. Schwartz, S. Alter, M. Schrimpf, J. Traer, J. De Freitas, J. Kubilius, A. Bhandwaldar, N. Haber, M. Sano   
[[Paper](https://openreview.net/pdf?id=db1InWAwW2T)]


### Production Line Simulators

* **KUKA.Sim**, KUKA, [[Page](https://www.kuka.com/en-de/products/robot-systems/software/planning-project-engineering-service-safety/kuka_sim)]

* **RobotStudio**, ABB, [[Page](https://new.abb.com/products/robotics/software-and-digital/robotstudio)]

* **ROBOGUIDE**, FANUC, [[Page](https://www.fanuc.eu/eu-en/accessory/software/simulation-software-roboguide)]

* **MotoSim**, Yaskawa, [[Page](https://www.yaskawa.eu.com/products/software/productdetail/product/motosim-eg-vrc_1686)]

* **Robotmaster**, Hypertherm Associates, [[Page](https://www.robotmaster.com)]

* **RoboDK**, RoboDK, [[Page](https://robodk.com/)]

* **ArtiMinds RPS**, Artiminds Robotics, [[Page](https://www.artiminds.com/robotics-software-and-services/robot-programming-suite-basic/)]

* **DELMIA**, Dassault Systèmes, [[Page](https://www.3ds.com/products/delmia)]

* **Visual Components**, Visual Components, [[Page](https://www.visualcomponents.com/products/)]

* **Tecnomatix**, Siemens, [[Page](https://plm.sw.siemens.com/en-US/tecnomatix/?srsltid=AfmBOoqcCMdYptEBiK_oNNfDAxf3mXC4GaexNR-_spDt9cnrSL0W3j6T)]


## 📰 Citation 
If you think this survey is helpful, please feel free to leave a star ⭐️ and cite our paper:

```bibtex
@article{

}
```
## 👏 Acknowledgements
The template for this project was forked from [HCPLab-SYSU's website](https://github.com/HCPLab-SYSU/Embodied_AI_Paper_List?tab=readme-ov-file). Thanks for sharing the amazing template!
