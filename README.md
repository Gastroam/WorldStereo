<div align="center">
<h2 align="center">
  <br>
  <a href="https://github.com/FuchengSu/WorldStereo">WorldStereo: Bridging Camera-Guided Video Generation and Scene Reconstruction via 3D Geometric Memories</a>
</h2>

**Yisu Zhang**<sup>1,2*</sup>, **Chenjie Cao**<sup>2*</sup>, **Tengfei Wang**<sup>2†</sup>, <br>
**Xuhui Zuo**<sup>2</sup>, **Junta Wu**<sup>2</sup> **Jianke Zhu**<sup>1‡</sup>, **Chunchao Guo**<sup>2</sup>

<sup>1</sup>Zhejiang University &nbsp;&nbsp; <sup>2</sup>Tencent Hunyuan
<br>
<small>*Equal Contribution, †Project Lead, ‡Corresponding Author</small> 

[![arXiv](https://img.shields.io/badge/arXiv-2602.24233-b31b1b.svg)]()


</div>

---
## 📅 News

*   `[2026.03]` 📄 Paper is now available on arXiv: [https://arxiv.org/abs/](https://arxiv.org/abs/)
*   `[TBD]` 🚧 We are planning to release the **Code** and **Model Weights** . Please stay tuned!

## 📖 Abstract
Recent advances in foundational Video Diffusion Models (VDMs) have yielded significant progress. Yet, despite the remarkable visual quality of generated videos, reconstructing consistent 3D scenes from these outputs remains challenging, due to limited camera controllability and inconsistent generated content when viewed from distinct camera trajectories.
In this paper, we propose \textbf{WorldStereo}, a novel framework that bridges camera-guided video generation and 3D reconstruction via two dedicated geometric memory modules. 
Formally, the global-geometric memory enables precise camera control while injecting coarse structural priors through incrementally updated point clouds.
Moreover, the spatial-stereo memory constrains the model's attention receptive fields with 3D correspondence to focus on fine-grained details from the memory bank.
These components enable WorldStereo to generate multi-view-consistent videos under precise camera control, facilitating high-quality 3D reconstruction.
Furthermore, the flexible control branch-based WorldStereo shows impressive efficiency, benefiting from the distribution matching distilled VDM backbone without joint training.
Extensive experiments across both camera-guided video generation and 3D reconstruction benchmarks demonstrate the effectiveness of our approach. Notably, we show that WorldStereo acts as a powerful world model, tackling diverse scene generation tasks (whether starting from perspective or panoramic images) with high-fidelity 3D results.
