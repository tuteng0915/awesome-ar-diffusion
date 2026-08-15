# <img height=34 src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Handshake.png"/> Awesome Diffusion × Autoregression (DiffxAR)
A curated list of hybrid Diffusion + Autoregressive (DiffxAR) models for language, reasoning, multimodal generation, and robots.

Note: Here, **AR** means **AutoRegressive**, not Augmented Reality. Currently, this repository is under construction, some tags may be wrong or unclear, and some important papers may not be covered. We welcome everyone's comments and contributions!

---

## <img height=28 src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Smilies/Smiling%20Face%20with%20Hearts.png"/> Legend


**Diffusion space**

- 🧱 Discrete diffusion (token / categorical space, e.g., D3PM, dLLM).
- 🌊 Continuous / latent diffusion (continuous states or learned latents).

**How diffusion × autoregression interact**

- 🧩 Planner–executor hybrids (Decompose “thinks / plans” & “speaks / executes”).
- 🪜 Training / objective bridges (convert AR LMs into DLMs, shared objectives, distillation).
- ⚙️ Decoding & efficiency hybrids (blockwise decoding, diffusion-forcing, semi-AR decoding).
- 📚 Background / foundation (important context, but not necessarily a direct DiffxAR hybrid).

**Application Domains**

- 🧠 Reasoning & planning (math, logic, tool-use, multi-step CoT).
- 🤖 Embodied / VLA / robotics (vision–language–action, robot policies).
- 👁️ VLM / multimodal models (vision-language or multimodal generation / understanding).
- 💻 Code generation and code reasoning.
- 🧪 AI4Science & scientific modeling (molecules, materials, proteins, scientific reasoning).
- ⚖️ Surveys & overviews.

---

## <img height=34 src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Smilies/Smiling%20Face%20with%20Sunglasses.png"/> Paper List


### 2026

| Tag | Paper | Author | Venue | Link |
| --- | ----- | ------ | ----- | ---- |
| 🧱🪜⚙️ | Learning from the Self-future: On-policy Self-distillation for dLLMs | Yifu Luo et al. | arXiv | [arXiv:2606.18195](https://arxiv.org/abs/2606.18195) · [Code](https://github.com/xingzhejun/d-opsd-code) |
| 🧱⚙️🪜 | BlockVLA: Accelerating Autoregressive VLA via Block Diffusion Finetuning | Ruiheng Wang et al. | arXiv | [arXiv:2605.13382](https://arxiv.org/abs/2605.13382) |
| 🌊⚙️ | ELF: Embedded Language Flows | Keya Hu et al. | arXiv | [arXiv:2605.10938](https://arxiv.org/abs/2605.10938) |
| 🧱⚙️🪜 | Fast-dVLM: Efficient Block-Diffusion VLM via Direct Conversion from Autoregressive VLM | Chengyue Wu et al. | arXiv | [arXiv:2604.06832](https://arxiv.org/abs/2604.06832) |
| 🌊🧩⚙️ | CoDAR: Continuous Diffusion Language Models are More Powerful Than You Think | Junzhe Shen et al. | arXiv | [arXiv:2603.02547](https://arxiv.org/abs/2603.02547) |
| 🧱🧩⚙️ | DFlash: Block Diffusion for Flash Speculative Decoding | Jian Chen et al. | arXiv | [arXiv:2602.06036](https://arxiv.org/abs/2602.06036) |
| 🧱⚙️ | Swordsman: Entropy-Driven Adaptive Block Partition for Efficient Diffusion Language Models | Yu Zhang et al. | arXiv | [arXiv:2602.04399](https://arxiv.org/abs/2602.04399) |
| 🧱⚙️🪜 | Causal Autoregressive Diffusion Language Model | Junhao Ruan et al. | arXiv | [arXiv:2601.22031](https://arxiv.org/abs/2601.22031) |
| 🧱⚙️ | Diffusion In Diffusion: Reclaiming Global Coherence in Semi-Autoregressive Diffusion | Linrui Ma et al. | arXiv | [arXiv:2601.13599](https://arxiv.org/abs/2601.13599) |
| 🧱⚙️🪜 | Autoregressive Models Rival Diffusion Models at ANY-ORDER Generation | Tianqi Du et al. | ICLR 2026 | [OpenReview](https://openreview.net/forum?id=vtDUomlazQ) |


### 2025

| Tag | Paper | Author | Venue | Link |
| --- | ----- | ------ | ----- | ---- |
| 🧱🪜⚙️ | Efficient-DLM: From Autoregressive to Diffusion Language Models, and Beyond in Speed | Yonggan Fu et al. | arXiv | [arXiv:2512.14067](https://arxiv.org/abs/2512.14067) |
| 🧱⚙️ | WeDLM: Reconciling Diffusion Language Models with Standard Causal Attention for Fast Inference | Aiwei Liu et al. | arXiv | [arXiv:2512.22737](https://arxiv.org/abs/2512.22737) |
| 🧱🪜⚙️👁️ | DiffusionVL: Translating Any Autoregressive Models into Diffusion Vision Language Models | Lunbin Zeng et al. | arXiv | [arXiv:2512.15713](https://arxiv.org/abs/2512.15713) |
| 🧱🧩⚙️ | ReFusion: A Diffusion Large Language Model with Parallel Autoregressive Decoding | Jia-Nan Li et al. | ICLR 2026 | [OpenReview](https://openreview.net/forum?id=LBtWaUc7FE) |
| 🧱🧩🧠 | TiDAR: Think in Diffusion, Talk in Autoregression | Jingyu Liu et al. | arXiv | [arXiv:2511.08923](https://arxiv.org/abs/2511.08923) |
| 🧱🧩 | Planned Diffusion: A Guiding Diffusion Language Model via Planning | Daniel Israel et al. | arXiv | [arXiv:2510.18087](https://arxiv.org/abs/2510.18087) |
| 🧱🧩🧠 | Planner and Executor: Collaboration Between Discrete Diffusion and Autoregressive Models in Reasoning | Lina Berrayana et al. | arXiv | [arXiv:2510.15244](https://arxiv.org/abs/2510.15244) |
| 🌊🧩🧠 | LaDiR: Latent Diffusion Enhances LLMs for Text Reasoning | Haoqiang Kang et al. | ICLR 2026 | [OpenReview](https://openreview.net/forum?id=z5cPEZ4n6i) |
| 🧱🪜⚙️ | Sequential Diffusion Language Models | Yangzhou Liu et al. | arXiv | [arXiv:2509.24007](https://arxiv.org/abs/2509.24007) |
| 🧱💻 | Dream-Coder 7B: An Open Diffusion Language Model for Code | Zhihui Xie et al. | arXiv | [arXiv:2509.01142](https://arxiv.org/abs/2509.01142) |
| 🧱🪜⚙️ | Fast-dLLM v2: Efficient Block-Diffusion LLM | Chengyue Wu et al. | ICLR 2026 | [OpenReview](https://openreview.net/forum?id=1NZ3DHF9nT) |
| 🧱🪜⚙️ | Blockwise SFT for Diffusion Language Models: Reconciling Bidirectional Attention and Autoregressive Decoding | Bowen Sun et al. | arXiv | [arXiv:2508.19529](https://arxiv.org/abs/2508.19529) |
| 🧱📚 | Dream 7B: Diffusion Large Language Models | Jiacheng Ye et al. | arXiv | [arXiv:2508.15487](https://arxiv.org/abs/2508.15487) |
| 🌊🧩⚙️ | Cosmos: Compressed and Smooth Latent Space for Text Diffusion Modeling | Artem Meshchaninov et al. | NeurIPS 2025 | [NeurIPS](https://papers.neurips.cc/paper_files/paper/2025/hash/1506930fb75c82246e4d8648a66e4b27-Abstract-Conference.html) |
| 🧱👁️ | LLaDA-V: Large Language Diffusion Models with Visual Instruction Tuning | Zebin You et al. | arXiv | [arXiv:2505.16933](https://arxiv.org/abs/2505.16933) |
| 🌊🧩🤖 | HybridVLA: Collaborative Diffusion and Autoregression in a Unified Vision-Language-Action Model | Jiaming Liu et al. | ICLR 2026 | [OpenReview](https://openreview.net/forum?id=H1KDMNOKQn) |
| 🧱🧠 | DiffTOD: Planning with Diffusion Models for Target-Oriented Dialogue Systems | Hanwen Du et al. | ACL 2025 | [ACL Anthology](https://aclanthology.org/2025.acl-long.993/) |
| 🧱🪜 | TESS 2: A Large-Scale Generalist Diffusion Language Model | Jaesung Tae et al. | ACL 2025 | [ACL Anthology](https://aclanthology.org/2025.acl-long.1029/) |
| 🧱⚙️ | Encoder-Decoder Diffusion Language Models for Efficient Training and Inference | Marianne Arriola et al. | NeurIPS 2025 | [NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2025/hash/172e31282df16359324717fcfbdbead3-Abstract-Conference.html) |
| 🧱🪜 | Non-Markovian Discrete Diffusion with Causal Language Models | Yangtian Zhang et al. | NeurIPS 2025 | [OpenReview](https://openreview.net/forum?id=qYSgnmT3dp) |
| 🧱📚 | Large Language Diffusion Models | Shen Nie et al. | NeurIPS 2025 | [OpenReview](https://openreview.net/forum?id=KnqiC0znVF) |
| 🧱⚖️ | On Powerful Ways to Generate: Autoregression, Diffusion, and Beyond | Chenxiao Yang et al. | ICLR 2026 | [OpenReview](https://openreview.net/forum?id=PKidr9Ruli) |
| 🧱🪜⚙️ | D2F: Diffusion LLMs Can Do Faster-Than-AR Inference via Discrete Diffusion Forcing | Xu Wang et al. | ICLR 2026 | [OpenReview](https://openreview.net/forum?id=t5uLZSRjhF) |
| 🧱🧩⚙️🧠 | HEX: Test-Time Scaling in Diffusion LLMs via Hidden Semi-Autoregressive Experts | Jihoon Lee et al. | ICLR 2026 | [OpenReview](https://openreview.net/forum?id=L5y7in91vd) |
| 🧱🪜⚙️ | Block Diffusion: Interpolating Between Autoregressive and Diffusion Language Models | Marianne Arriola et al. | ICLR 2025 | [OpenReview](https://openreview.net/forum?id=tyEyYT267x) |
| 🌊🪜🧠 | Energy-Based Diffusion Language Models for Text Generation | Minkai Xu et al. | ICLR 2025 | [OpenReview](https://openreview.net/forum?id=sL2F9YCMXf) |


### 2024

| Tag | Paper | Author | Venue | Link |
| --- | ----- | ------ | ----- | ---- |
| 🌊🧩🤖 | Diffusion-VLA: Scaling Robot Foundation Models via Unified Diffusion and Autoregression | Junjie Wen et al. | arXiv | [arXiv:2412.03293](https://arxiv.org/abs/2412.03293) |
| 🧱⚙️ | Beyond Autoregression: Fast LLMs via Self-Distillation Through Time | Justin Deschenaux et al. | ICLR 2025 | [OpenReview](https://openreview.net/forum?id=uZ5K4HeNwd) |
| 🧱🪜 | Scaling Diffusion Language Models via Adaptation from Autoregressive Models | Shansan Gong et al. | ICLR 2025 | [OpenReview](https://openreview.net/forum?id=j1tSLYKwg8) |
| 🧱🧠 | Beyond Autoregression: Discrete Diffusion for Complex Reasoning and Planning | Jiacheng Ye et al. | ICLR 2025 | [OpenReview](https://openreview.net/forum?id=NRYgUzSPZz) |
| 🌊🧩 | Diffusion Guided Language Modeling | Justin Lovelace et al. | Findings of ACL 2024 | [ACL Anthology](https://aclanthology.org/2024.findings-acl.887/) |
| 🧱🧠 | Diffusion of Thoughts: Chain-of-Thought Reasoning in Diffusion Language Models | Jiacheng Ye et al. | arXiv | [arXiv:2402.07754](https://arxiv.org/abs/2402.07754) |


### 2023

| Tag | Paper | Author | Venue | Link |
| --- | ----- | ------ | ----- | ---- |
| 🧱⚙️ | Sequential Data Generation with Groupwise Diffusion Process | Sangyun Lee et al. | arXiv | [arXiv:2310.01400](https://arxiv.org/abs/2310.01400) |
| 🌊🧩 | PLANNER: Generating Diversified Paragraph via Latent Language Diffusion Model | Yizhe Zhang et al. | arXiv | [arXiv:2306.02531](https://arxiv.org/abs/2306.02531) |
| 🧱🧩 | AR-Diffusion: Auto-Regressive Diffusion Model for Text Generation | Tong Wu et al. | NeurIPS 2023 | [OpenReview](https://openreview.net/forum?id=0EG6qUQ4xE) |
| 🧱📚 | A Reparameterized Discrete Diffusion Model for Text Generation | Lin Zheng et al. | arXiv | [arXiv:2302.05737](https://arxiv.org/abs/2302.05737) |
| 🧱⚙️ | SSD-LM: Semi-autoregressive Simplex-based Diffusion Language Model for Text Generation and Modular Control | Xiaochuang Han et al. | ACL 2023 | [ACL Anthology](https://aclanthology.org/2023.acl-long.647/) |


### 2022

| Tag | Paper | Author | Venue | Link |
| --- | ----- | ------ | ----- | ---- |
| 🌊📚 | Latent Diffusion for Language Generation | Justin Lovelace et al. | arXiv | [arXiv:2212.09462](https://arxiv.org/abs/2212.09462) |
| 🌊📚 | Diffusion-LM Improves Controllable Text Generation | Xiang Lisa Li et al. | NeurIPS 2022 | [NeurIPS](https://papers.neurips.cc/paper_files/paper/2022/hash/1be5bc25d50895ee656b8c2d9eb89d6a-Abstract-Conference.html) |


### 2021

| Tag | Paper | Author | Venue | Link |
| --- | ----- | ------ | ----- | ---- |
| 🧱📚 | Structured Denoising Diffusion Models in Discrete State-Spaces | Jacob Austin et al. | NeurIPS 2021 | [OpenReview](https://openreview.net/forum?id=h7-XixPCAL) |

---

## Inclusion Criteria

- Include papers that explicitly connect **diffusion** and **autoregressive** modeling in architecture, training, or decoding.
- Include AR-to-diffusion / diffusion-to-AR conversion, distillation, initialization, or blockwise / semi-autoregressive decoding papers.
- Include foundation papers only when they are important background for understanding DiffxAR work; mark them with 📚.
- Exclude papers that only use diffusion in an unrelated modality or only compare against AR baselines without a substantive DiffxAR connection.

---

## <img height=34 src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Objects/Hammer%20and%20Wrench.png"/> Want to Contribute?

We welcome contributions! Please feel free to submit a PR or open an issue if you'd like to add new papers, tools, or correct any mistakes.

### ✅ Guidelines

- Only add papers that **explicitly connect diffusion and autoregression** in **architecture, training, or decoding**.
- Use consistent formatting:  
  `| ICONS | Title | Author | Venue | [arXiv:ID](https://arxiv.org/abs/ID) |`
- Try to tag each paper with:
  - one of **🧱 / 🌊**,
  - whether it is **🧩 / 🪜 / ⚙️ / 📚**, and
  - optional domain tags **🧠 / 🤖 / 👁️ / 💻 / 🧪 / ⚖️**.
- Prefer papers with an **arXiv entry** so that every row has a stable link.
- If a paper has a confirmed and accessible venue page, link only the venue page; otherwise link arXiv.
- If you add a new domain (e.g. speech, music, code), consider adding a short note in the PR explaining how diffusion and AR interact in that setting.

---

## Related Lists

- [Awesome Diffusion Models](https://github.com/heejkoo/Awesome-Diffusion-Models)
- [Awesome Diffusion Language Models](https://github.com/ML-GSAI/Awesome-Diffusion-Language-Models)
- [Awesome LLM Reasoning](https://github.com/atfortes/Awesome-LLM-Reasoning)
