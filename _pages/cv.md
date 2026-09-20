---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}


Education
======
* B.S. in Software Engineering, [Northwestern Polytechnical University](https://www.nwpu.edu.cn/), 2017
* Ph.D in Computer Science and Technology, [Zhejiang University](https://www.zju.edu.cn/), 2024

Work experience
======
* 2018-07 to 2021-05: Research Intern
  * XMov, Shanghai
  * Duties included: Human segmentation algorithm developing and optimizing, human motion generation algorithm researching

* 2021-07 to 2023-01: Research Intern
  * Central Media Technology Institute, HUAWEI, Hangzhou
  * Duties included: Controllable limb movement generation project researching and developing

* 2024-07 to now: Postdoctoral Fellow
  * the State Key Lab of CAD&CG, Zhejiang University, Hangzhou
  * Duties included: Conduct academic research, engage in project work, and assist with student guidance
  
Skills
======
* Programming Language\
  Python/C++/C#
* Machine Learning Libirary\
  PyTorch/TensorFlow/Caffe
* Others\
  MotionBuilder/Unity 3D/OpenGL/Qt/Blender/Office

Publications
======
* [Depth-Adaptive Injection for Stylized Text-to-Motion](https://ieeexplore.ieee.org/document/11693980)\
IEEE Transactions on Visualization and Computer Graphics (TVCG), 2026\
[**Shuaiying Hou**](https://houericsy.github.io/ShuaiyingHou/), [Hongyu Tao](https://thyzju17.github.io/), Junjie Gao, Junheng Fang, Rong Zhang, Yongcong Zhang, Shiqi Zhou, [Weiwei Xu](http://www.cad.zju.edu.cn/home/weiweixu/weiweixu_en.htm)<span class="toggle-info" onclick="toggleInfo(this)">*</span>
<div class="info">corresponding author</div>

* [Mimic-X: A Large-Scale Motion Dataset via Fast Physics-Based Controller Adaptation](https://ojs.aaai.org/index.php/AAAI/article/view/37911) [[Project Page](https://thyzju17.github.io/projects/Mimic-X/)]\
Proceedings of the AAAI Conference on Artificial Intelligence, 2026\
[Hongyu Tao](https://thyzju17.github.io/), [**Shuaiying Hou**](https://houericsy.github.io/ShuaiyingHou/), Junheng Fang, Mingyao Shi, [Weiwei Xu](http://www.cad.zju.edu.cn/home/weiweixu/weiweixu_en.htm)<span class="toggle-info" onclick="toggleInfo(this)">*</span>
<div class="info">corresponding author</div>

* [A causal convolutional neural network for multi-subject motion modeling and generation](https://link.springer.com/article/10.1007/s41095-022-0307-3)\
Computational Visual Media (CVMJ, **spotlight**), 2024 \
[**Shuaiying Hou**](https://houericsy.github.io/ShuaiyingHou/), Congyi Wang, Wenlin Zhuang, Yu Chen, [Yangang Wang](https://www.yangangwang.com/), [Hujun Bao](http://www.cad.zju.edu.cn/home/bao/), [Jinxiang Chai](https://scholar.google.com/citations?user=OcN1_gwAAAAJ&hl=zh-CN), [Weiwei Xu](http://www.cad.zju.edu.cn/home/weiweixu/weiweixu_en.htm)<span class="toggle-info" onclick="toggleInfo(this)">*</span>
<!-- <div class="info" id="info">corresponding author</div> -->

* [A Two-part Transformer Network for Controllable Motion Synthesis](https://ieeexplore.ieee.org/document/10147861)\
IEEE Transactions on Visualization and Computer Graphics (TVCG), 2023\
[**Shuaiying Hou**](https://houericsy.github.io/ShuaiyingHou/), [Hongyu Tao](https://thyzju17.github.io/), [Hujun Bao](http://www.cad.zju.edu.cn/home/bao/), [Weiwei Xu](http://www.cad.zju.edu.cn/home/weiweixu/weiweixu_en.htm)<span class="toggle-info" onclick="toggleInfo(this)">*</span>
<!-- <div class="info" id="info">corresponding author</div> -->

* [Neural Motion Graph](https://dl.acm.org/doi/10.1145/3610548.3618181)\
ACM SIGGRAPH Asia, 2023\
[Hongyu Tao](https://thyzju17.github.io/), [**Shuaiying Hou**](https://houericsy.github.io/ShuaiyingHou/), [Changqing Zou](https://changqingzou.weebly.com/), [Hujun Bao](http://www.cad.zju.edu.cn/home/bao/), [Weiwei Xu](http://www.cad.zju.edu.cn/home/weiweixu/weiweixu_en.htm)<span class="toggle-info" onclick="toggleInfo(this)">*</span>
<div class="info">corresponding author</div>

<!-- Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->

<script>
function toggleInfo(toggle) {
    var info = toggle.parentElement.nextElementSibling;
    if (!info || !info.classList.contains("info")) return;
    info.style.display = (info.style.display === "none" || info.style.display === "") ? "block" : "none";
}
</script>

<style>
span.toggle-info {
    cursor: pointer;
}

div.info {
    display: none;
    margin-left: 5px;
}
</style>
