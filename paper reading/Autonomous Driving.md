### Dataset
[BDD100K](http://bdd-data.berkeley.edu/)(the biggest dataset for autonomous driving, UC Berkeley) <br>
[Apolloscapes](http://apolloscape.auto/)(Baidu Apollo) <br>
[KITTI](http://www.cvlibs.net/datasets/kitti/index.php)(Vision Benchmark Suite) <br>
[DBNet](http://www.dbehavior.net/data/egpaper_release.pdf)( A Large-Scale Dataset for Driving Behavior Learning, 厦大+上交) <br>
[comma.ai driving dataset](https://archive.org/details/comma-dataset)(comma.ai) <br>
[Oxford's Robotic Car](http://robotcar-dataset.robots.ox.ac.uk/documentation/#dataset-description)(one route) <br>
[Cityscape](https://www.cityscapes-dataset.com/)(50 different cities) <br>
[CSSAD](http://aplicaciones.cimat.mx/Personal/jbhayet/ccsad-dataset) <br>
[MIT AGE Lab](https://lexfridman.com/carsync/) <br>
[LISA](http://cvrr.ucsd.edu/LISA/datasets.html) <br>
[KUL Belgium Traffic Sign dataset](http://www.vision.ee.ethz.ch/~timofter/traffic_signs/)(Traffic Sign Recognition) <br>
[HDD](https://arxiv.org/pdf/1811.02307.pdf)(A Dataset for Learning Driver Behavior and Causal Reasoning, 本田, 教育邮箱发hdd@honda-ri.com索取) <br>
#### a comparision from HDD
<img alt="driving scene datasets" src="https://github.com/marooncn/learning_note/blob/master/paper%20reading/image/driving%20scene%20datasets.png" width="600"> <br>


### Simulator
[CARLA](http://carla.org/)(Intel, An Open Urban Driving Simulator) <br>
[self-driving-car-sim](https://github.com/udacity/self-driving-car-sim)(Udacity, A self-driving car simulator built with Unity) <br>
[Apollo](http://apollo.auto/)(Baidu Apollo) <br>
[AVS](https://avs.auto/#/)(Uber AVS(autonomous Visualization System)) <br>
[Worldview](https://cruise-automation.github.io/webviz/worldview/#/)(Cruise) <br>
[AADS: Augmented antonomous driving simulation using data-driven algorithms](https://arxiv.org/ftp/arxiv/papers/1901/1901.07849.pdf)(Baidu Apollo, Science Robotics 2019) <br>

### Paper
### Perception
[Pseudo-LiDAR from Visual Depth Estimation: Bridging the Gap in 3D Object Detection for Autonomous Driving](https://arxiv.org/pdf/1812.07179.pdf)(arxiv 2018, Cornell) <br>
[LaserNet: An Efficient Probabilistic 3D Object Detector for Autonomous Driving](https://arxiv.org/pdf/1903.08701.pdf)(arxiv 2019) <br>

### Prediction
[DeepSignals: predicting intent of drivers through visual signals](https://arxiv.org/pdf/1905.01333.pdf)(ICRA 2019, Uber ATG) <br>

### Decision & Control
[End to end learning for self-driving cars](https://github.com/marooncn/learning_note/blob/master/paper%20reading/notes/End%20to%20End%20Learning%20for%20Self-Driving%20Cars.pdf)([code](https://github.com/navoshta/behavioral-cloning)& [Zhihu](https://zhuanlan.zhihu.com/p/60625133), arxiv 2016, Nvidia) <br>
[End-to-end driving via conditional imitation learning](https://github.com/marooncn/learning_note/blob/master/paper%20reading/notes/End-to-end%20Driving%20via%20Conditional%20Imitation%20Learning.pdf)(ICRA 2018, Intel) <br>
[Learning to Navigate in Cities Without a Map](https://arxiv.org/pdf/1804.00168.pdf)(arxiv 2018, DeepMind)<br>
[Learning  to  Drive  in  a  Day](https://github.com/marooncn/learning_note/blob/master/paper%20reading/notes/Learning%20to%20drive%20in%20a%20day.pdf)([blog](https://wayve.ai/blog/learning-to-drive-in-a-day-with-reinforcement-learning), Wayve 2018) <br>
[Learning to Drive from Simulation without Real World Labels](https://github.com/marooncn/learning_note/blob/master/paper%20reading/notes/Learning%20to%20Drive%20from%20Simulation%20without%20Real%20World%20Labels.pdf)([blog](https://wayve.ai/blog/sim2real), [UNIT](https://github.com/marooncn/learning_note/blob/master/paper%20reading/notes/Unsupervised%20Image-to-Image%20Translation%20Networks.pdf), [Unsupervised Conditional GAN](http://speech.ee.ntu.edu.tw/~tlkagk/courses/MLDS_2018/Lecture/CycleGAN.pdf), [domain translation blog](https://blog.csdn.net/a312863063/article/details/83575810), Wayve 2018, Translate images from real environment to simulation to make decision) <br>
[Virtual to Real Reinforcement Learning for Autonomous Driving](https://arxiv.org/pdf/1704.03952v4.pdf)(arxiv 2017, Virtual to Real Image Translation to train RL network) <br>
[ChauffeurNet:  Learning to Drive by Imitating the Best and Synthesizing the Worst](https://export.arxiv.org/pdf/1812.03079)(arxiv 2018, waymo) <br>
[Zero-shot Deep Reinforcement Learning Driving Policy Transfer for Autonomous Vehicles based on Robust Control](https://arxiv.org/pdf/1812.03216.pdf)(ITSC 2018) <br>
[Latent Space Reinforcement Learning for Steering Angle Prediction](https://arxiv.org/pdf/1902.03765.pdf)(arxiv 2019) <br>
[Safe Reinforcement Learning on Autonomous Vehicles](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8593420)(IROS 2018, use prediction model to add masking mechanism to DRL action output to prevent dangerous action.) <br>
[variational end-to-end navigation and localization](https://arxiv.org/pdf/1811.10119.pdf)(ICRA 2019, Proposed Variational end-to-end model learns from raw sensory data as well as coarse grained topology maps to navigate and localize within complex environments.) <br>

### Detection
[Detects Chinese traffic police commanding poses](https://github.com/zc402/ChineseTrafficPolicePose)  <br>

### Evalution
[On Offline Evaluation of Vision-based Driving Models](https://arxiv.org/pdf/1809.04843.pdf)(arxiv 2018) <br>
[Exploring the Limitations of Behavior Cloning for Autonomous Driving](https://arxiv.org/pdf/1904.08980.pdf)(arxiv 2019) <br>

### Transport
[Flow: Architecture and Benchmarking for Reinforcement Learning in Traffic Control](https://arxiv.org/pdf/1710.05465.pdf)([blog](https://flow-project.github.io/), CoRL 2018, UC Berkerly) <br>

### Obstacle Aviodance
[Motion Planning Among Dynamic, Decision-Making Agents with Deep Reinforcement Learning](https://arxiv.org/pdf/1805.01956.pdf)([code](https://github.com/mfe7/cadrl_ros), IROS 2018, MIT) <br>

### Autonomous Drifting
[Autonomous Drifting using Reinforcement Learning](https://github.com/kanakkabara/Autonomous-Drifting) <br>
[Autonomous Drifting using Simulation-Aided Reinforcement Learning](https://weeklyrobotics.com/publications/autonomous_drifting/Cutler16_ICRA_final_submission.pdf) <br>

### Localization
[HF-Net: Robust Hierarchical Localization at Large Scale](https://github.com/ethz-asl/hfnet)([NetVLAD](http://www.liuxiao.org/2019/02/%E8%AE%BA%E6%96%87%E7%AC%94%E8%AE%B0%EF%BC%9Anetvlad-cnn-architecture-for-weakly-supervised-place-recognition/), [SuperPoint](https://blog.csdn.net/honyniu/article/details/87483613)) <br>
