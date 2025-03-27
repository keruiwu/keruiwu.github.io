---
layout: default
---

# About me
I am a Computer Science undergraduate student at [Rensselaer Polytechnic Institute](https://www.rpi.edu/) who expects to graduate in May 2025. I am honored to participate various research programs with been advised by Professor [Lei Yu](https://leiyucs.github.io/), [Bülent Yener](https://www.cs.rpi.edu/~yener/), and [Jianxi Gao](https://www.gaojianxi.com/). 

# Research
My research mainly lies in the intersection of machine learning, time series analysis, and system security. Specifically, I am interested in developing or taking advantage of efficient and robust deep learning models to solve real-world problems in various domains such as cybersecurity, biology, and geophysics.

Recently I have been working on the following projects:

* **Robustness of Graph Reduction Against GNN attacks**: We empirically investigate the robustness of graph reduction methods, algorithms that was originally aimed to accelerate the training of graph neural networks(GNNs), aginst various poisoning and backdoor attacks. 


* **Deep Learning-based Time Series Analysis for Science**: We developed end-to-end deep learning models to analyze time series data in various scientific domains, such as earthquake detection in geophysics and seizure detection in biology. We also explored various unsupervised domain adaptation techniques to improve the generalization of the models.

* **Efficiently Solving Steady-State of Complex Dynamical Systems**: We proposed a novel two-stage approach to efficiently compute steady stages in large-scale dynamical systems while maintaining the low state error. This method achieved a 2970-fold speedup compared to the traditional numerical integration method when dealing with 8000-node networks. 

# Publication
### On the Robustness of Graph Reduction Against GNN Backdoor [[pdf](https://arxiv.org/pdf/2407.02431)]

Yuxuan Zhu, Michael Mandulak, **Kerui Wu**, George Slota, Yuseok Jeon, Ka-Ho Chow, Lei Yu

Accepted by **AISec 2024**

### Understanding the Impact of Graph Reduction on Adversarial Robustness in Graph Neural Networks [[pdf](https://arxiv.org/pdf/2412.05883)]

**Kerui Wu**, Ka-Ho Chow, Wenqi Wei, Lei Yu

Preprint on **arXiv**

# Awards
### 1st Place in Seizure Detection Challenge with 7000$ Award [[leaderboard](https://epilepsybenchmarks.com/challenge/)]
**Kerui Wu**, Ziyue Zhao, Bülent Yener

Organized by **The International Conference on Artificial Intelligence in Epilepsy and Other Neurological Disorders (AI-NEURO) 2025** and **EPFL**


# Technical Contribution
## China Construction Bank Achievement System
##### React.JS, Go, MySQL, Azure
<img src="assets/img/ccb.png" style="width:240px;height:240px;margin-right:10px;float:left">[China Construction Bank](https://www.ccb.com/eng/home/index.shtml) is one of China's four major state-owned banks. The Dianlong Branch in Kunming is a secondary branch of the China Construction Bank, with 11 sub-branches in Kunming and hundreds of employees. To help the branch managers track and manage the performance of each sub-branch, position, and employee, I proposed and implemented a web-based performance tracking system with React.JS as frontend framework. Employees can submit their daily performance metrics, such as the amount of fixed deposits, current deposits, financial products sold, and the number of new accounts opened for customers. Managers can view performance scores calculated based on rules defined by the bank and systematically evaluate the performance of each employee. Comprehensive Restful APIs, with the use of GinGonic framwork written in Go, are provided for managers to sort and filter the data. **The system is currently used by all 11 sub-branches in Kunming city.**
<br>

## Submitty Open Source
##### HTML, JavaScript, PHP, SQL
<img src="assets/img/submitty.png" style="width:240px;height:240px;margin-right:10px;float:left">[Submitty](https://submitty.org/index/overview) is an open source course management, assignment submission, exam and grading system that is widely used by Computer Science departments in Rensselaer Polytechnic Institute and other universities. I contributed to the development of the system as a [full-stack developer in 2023 spring](https://submitty.org/index/people) by implementing several new features like customizable pronouns setting, which involved front-end development using HTML and JavaScript, backend API creation with PHP, and database schema design using SQL. I also found and fixed several bugs in the system. So far, [5 of my pull requests](https://github.com/Submitty/Submitty/pulls?q=is:pr+author:keruiwu) have been merged into the main branch of the Submitty repository.
<br>
<br>

## Wox Translater Plugin
##### Python, BeautifulSoup
<img src="assets/img/wox.gif" style="width:240px;height:150px;margin-right:10px;float:left">[Wox](http://www.wox.one/) is a full-featured launcher, access programs and web contents as you type. I developed a plugin for Wox that can translate English to Chinese and vice versa by scraping Cambridge dictionary using BeautifulSoup. Because of the nature of scraping, users can directly download the plugin to use without any registration or API key. The plugin is currenly live on the [Wox plugin store](http://www.wox.one/plugin/409).
<br>
<br>

## Ocean Dynamic Wallpaper
##### HTML, JavaScript
<img src="assets/img/ocean.gif" style="width:240px;height:125px;margin-right:10px;float:left">This is a dynamic wallpaper that simulates the ocean written in Canvas element in HTML and animation in JavaScript. Bubbles are generated with random radius, color, and moving speed, where users can click bubbles by tracking the mouse's coordinates. Project repository can be found in [GitHub](https://github.com/keruiwu/Ocean_Dynamic_Wallpaper). 