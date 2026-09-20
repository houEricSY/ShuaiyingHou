---
title: "Depth-Adaptive Injection for Stylized Text-to-Motion"
collection: publications
permalink: /publications/paper-5
excerpt: "Discrete text-to-motion generation models are powerful tools for synthesizing diverse human motions, yet endowing them with controllable, high-fidelity stylistic variations remains challenging. Direct retraining or fine-tuning these models often disrupts the fragile discrete token distributions learned by masked generative models, leading to optimization instability, style-content entanglement, and degraded motion quality or text alignment. To address these limitations, we propose the Modular Injection Framework (MIF), a framework for conditional adaptation of masked discrete text-to-motion models. For optimization stability, MIF employs a continuous residual injection mechanism to fuse conditioning signals within the hidden states of the pretrained backbone. Crucially, through systematic ablation, we uncover a depth-aware structural behavior: assigning injection to different transformer layers with depth-adaptive weights introduces a beneficial architectural bias. This design effectively aids to strike better trade-offs between style representation and motion quality, allowing the network to modulate high-frequency stylistic details while preserving low-frequency semantic content. Furthermore, to explore the generality of MIF, we adopt a distribution-aware adaptation strategy to extend MIF to novel motion adaptation and cross-modal music-conditioned dance synthesis. Based on target-domain reconstruction and codebook utilization statistics, the strategy determines which pretrained components remain fixed and which are trainable. Extensive experiments demonstrate our method's superior stylized motion quality and robust cross-domain adaptability. Notably, our method also supports temporal and cross-task composition."
date: '2026-09-16'
venue: 'IEEE Transactions on Visualization and Computer Graphics (TVCG)'
paperurl: 'https://ieeexplore.ieee.org/document/11693980'
citation: 'S. Hou, H. Tao, J. Gao, J. Fang, R. Zhang, Y. Zhang, S. Zhou and W. Xu, "Depth-Adaptive Injection for Stylized Text-to-Motion," in IEEE Transactions on Visualization and Computer Graphics, pp. 1–12, 2026, doi: 10.1109/TVCG.2026.3734489.'
---

[Download paper here](https://ieeexplore.ieee.org/document/11693980)

[**Shuaiying Hou**](https://houericsy.github.io/ShuaiyingHou/), [Hongyu Tao](https://thyzju17.github.io/), Junjie Gao, Junheng Fang, Rong Zhang, Yongcong Zhang, Shiqi Zhou, [Weiwei Xu](http://www.cad.zju.edu.cn/home/weiweixu/weiweixu_en.htm)


**BibTeX**\
@article{hou2026depth,\
  author={Hou, Shuaiying and Tao, Hongyu and Gao, Junjie and Fang, Junheng and Zhang, Rong and Zhang, Yongcong and Zhou, Shiqi and Xu, Weiwei},\
  journal={IEEE Transactions on Visualization and Computer Graphics},\
  title={Depth-Adaptive Injection for Stylized Text-to-Motion},\
  year={2026},\
  pages={1--12},\
  doi={10.1109/TVCG.2026.3734489}\
}
