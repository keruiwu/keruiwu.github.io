---
layout: default
---

# About me
I am a Computer Science undergraduate student at [Rensselaer Polytechnic Institute](https://www.rpi.edu/) who expects to graduate in May 2023. I am honored to participate various research programs with been advised by Professor [Lei Yu](https://leiyucs.github.io/), [Bulent Yener](https://www.cs.rpi.edu/~yener/), and [Jianxi Gao](https://www.gaojianxi.com/). 

# Research
My research mainly lies in the intersection of machine learning, time series analysis, and system security. Specifically, I am interested in developing or taking advantage of efficient and robust deep learning models to solve real-world problems in various domains such as cybersecurity, biology, and geophysics.

Recently I have been working on the following projects:

* **Robustness of Graph Reduction Against GNN attacks**: We empirically investigate the robustness of graph reduction methods, algorithms that was originally aimed to accelerate the training of graph neural networks(GNNs), aginst various poisoning and backdoor attacks. 


* **Time Series Analysis on Multivariate Seismic Data**: We explored the performance of cutting-edge deep learning based time series models on tackling earthquake detection, phase identification, and onset time picking tasks under both supervised(classification) and unsupervised(anomaly detection) settings.

* **Efficiently Solving Steady-State of Complex Dynamical Systems**: We proposed a novel two-stage approach to efficiently compute steady stages in large-scale dynamical systems while maintaining the low state error. This method achieved a 2970-fold speedup compared to the traditional numerical integration method when dealing with 8000-node networks. 

# Publication
## Conference
### On the Robustness of Graph Reduction Against GNN Backdoor [[pdf](https://arxiv.org/pdf/2407.02431)]

Yuxuan Zhu, Michael Mandulak, **Kerui Wu**, George Slota, Yuseok Jeon, Ka-Ho Chow, Lei Yu

Accepted by **AISec 2024**

<p><img src="assets/img/backdoor_publication.png" style="width:240px;height:240px;margin-right:10px;float:left">This paper conducts a thorough examination of the
robustness of graph reduction methods in scalable GNN training in
the presence of state-of-the-art backdoor attacks. We performed a
comprehensive robustness analysis across six coarsening methods
and six sparsification methods for graph reduction, under three
GNN backdoor attacks against three GNN architectures. Our findings indicate that the effectiveness of graph reduction methods in
mitigating attack success rates varies significantly, with some methods even exacerbating the attacks. Through detailed analyses of
triggers and poisoned nodes, we interpret our findings and enhance
our understanding of how graph reduction influences robustness
against backdoor attacks. These results highlight the critical need
for incorporating robustness considerations in graph reduction
for GNN training, ensuring that enhancements in computational
efficiency do not compromise the security of GNN systems.</p>

## Undergraduate Thesis
### Femtosecond Laser Micro Machining [[pdf](assets/file/laser.pdf)]

**Kerui Wu**, Sixue Xing, Yuri V Lvov

<p><img src="assets/img/laser.gif" style="width:240px;height:240px;margin-right:10px;float:left">We simulated the micro-machining process with a femtosecond laser using a mathematical model. The study involved identifying and developing a differential equation that could be applied in the simulation program. A 3D graph was generated to illustrate the relationship between the laser's radius and the density of free electrons, which serves as the criterion for determining the completion of the micro-machining process. Additionally, a C++ program was developed to simulate this process more efficiently, achieving faster runtime compared to Matlab.</p>

### Identifying Vulnerable Child Care Centers Due to Effects of Temperature and Precipitation

**Kerui Wu**, Weihao Li, Yanfeng Liu, Chiting Lu, Jinhui Yu, Tianze Zhu, Thilanka Munasinghe

<p><img src="assets/img/childcare.png" style="width:240px;height:240px;margin-right:10px;float:left">Childcare centers gather lots of children who need protection. Focusing on minimizing physical harm, the impact of natural hazards induced by precipitation and temperature fluctuations on childcare center buildings is a critical concern. Heavy rainfall and extreme temperatures can compromise structural integrity and pose health risks. Leveraging historical data from NASA's Global Precipitation Mission and childcare center locations from Homeland Infrastructure Foundation-Level Data, we processed and cleaned the dataset, utilizing machine learning clustering algorithms. The K-means clustering algorithm and Gaussian Mixture Model, among others, classified childcare centers based on precipitation and temperature data, with silhouette scores above 0.3. Visualization on a US map revealed varying risks among states, influenced by environmental factors. This study underscores the importance of incorporating additional elements like wind and snowfall in future research to assess childcare facility risks and regional vulnerabilities comprehensively.</p>