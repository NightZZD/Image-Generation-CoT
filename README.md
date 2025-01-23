# Can We Generate Images 🌇 with CoT 🧠?

Official repository for the paper "[Can We Generate Images with CoT? Let's Verify and Reinforce Image Generation Step by Step]()".

[[📖 Paper]()] [[🤗 HF Checkpoints]()] [[🤗 HF Datasets (coming)]()]

## 💥 News
- **[2025.01.23]** We release the code for autoregressive image generation with test-time scaling (ORM, PARM) and DPO 🚀
- **[2025.01.23]** We release the [arXiv paper]() 🚀

## 👀 Reasoning in Image Generation

Chain-of-Thought (CoT) reasoning has been extensively explored by LLMs and LMMs in mathematics. However, it still remains an open question whether such strategies can be applied to **verifying and reinforcing image generation scenarios**. In this project, we provide ***the first*** comprehensive investigation of the potential of CoT reasoning to enhance autoregressive image generation.

<p align="center">
    <img src="figs/fig1.jpg" width="90%"> <br>
</p>

We focus on three CoT reasoning techniques:
1. ***Scaling Test-time Computation*** for verification (ORM, PRM, and our proposed PARM and PARM++)
2. ***Aligning Model Preferences*** with Direct Preference Optimization (DPO)
3. ***Integrating These Techniques*** for complementary effects

Our results demonstrate that these approaches can be effectively adapted and combined to significantly improve the image generation performance:

<p align="center">
    <img src="figs/fig2.jpg" width="100%"> <br>
</p>
  
Furthermore, given the pivotal role of reward models in our findings, we propose the ***P***otential ***A***ssessment ***R***eward ***M***odel (***PARM***) and ***PARM++***, specialized for autoregressive image generation:

1. ***PARM*** adaptively assesses each generation step through a potential assessment approach, merging the strengths of existing reward models.
2. ***PARM++*** further introduces a reflection mechanism to empower generative models to self-correct the previous unsatisfactory image.

<p align="center">
    <img src="figs/fig3.jpg" width="90%"> <br>
</p>

## 💪 Get Started

## 🧠 Related Work

Explore our additional research on **CoT Reasoning**:

- **[MathVerse]** [MathVerse: Does Your Multi-modal LLM Truly See the Diagrams in Visual Math Problems?](https://mathverse-cuhk.github.io/)
- **[MAVIS]** [MAVIS: Mathematical Visual Instruction Tuning with an Automatic Data Engine](https://arxiv.org/pdf/2407.08739)

