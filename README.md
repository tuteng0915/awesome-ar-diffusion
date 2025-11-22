# <img height=34 src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Hand%20gestures/Handshake.png"/> Awesome Diffusion × Autoregression (DxAR)
A curated list of hybrid Diffusion + Autoregressive (ARxDiff) models for language, reasoning, and robots.

<img height=220 src="./img/dxar.png" alt="Diffusion × Autoregression hybrid models illustration"/>

---

## <img height=28 src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Smilies/Nerd%20Face.png"/> Legend

- 🔗 **Hybrid (Diffusion × Autoregression)** – explicit collaboration between a diffusion module and an autoregressive module.
- 💭 **Diffusion-style generation** – masked / block / discrete diffusion or flow matching.
- 📝 **Autoregressive-style generation** – left-to-right or causal decoding.
- 🧠 **Language & reasoning**
- 🤖 **Embodied / VLA / robotics**
- ⚡ **Inference efficiency / decoding tricks**
- 📐 **Theory / general frameworks**

---

## <img height=34 src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Smilies/Smiling%20Face%20with%20Sunglasses.png"/> Paper List

### 🧠 Language & Reasoning

#### 2025
- 2025 🔗🧠 Planner and Executor: Collaboration Between Discrete Diffusion and Autoregressive Models in Reasoning. [arXiv:2510.15244](https://arxiv.org/abs/2510.15244)
- 2025 🔗🧠 Planned Diffusion: A Guiding Diffusion Language Model via Planning. [arXiv:2510.18087](https://arxiv.org/abs/2510.18087)
- 2025 🔗🧠 TiDAR: Think in Diffusion, Talk in Autoregression. [arXiv:2511.08923](https://arxiv.org/abs/2511.08923)
- 2025 🔗⚡ D2F: Diffusion LLMs Can Do Faster-Than-AR Inference via Discrete Diffusion Forcing. [arXiv:2508.09192](https://arxiv.org/abs/2508.09192)
- 2025 ⚡💭 Fast-dLLM: Training-free Acceleration of Diffusion LLM by Enabling KV Cache and Parallel Decoding. [arXiv:2505.22618](https://arxiv.org/abs/2505.22618)
- 2025 ⚡💭 HEX: Test-Time Scaling in Diffusion LLMs via Hidden Semi-Autoregressive Experts. [arXiv:2510.05040](https://arxiv.org/abs/2510.05040)

#### 2024
- 2024 🔗🧠 Diffusion Guided Language Modeling. [arXiv:2408.04220](https://arxiv.org/abs/2408.04220)
- 2024 💭📝 Simple and Effective Masked Diffusion Language Models. [arXiv:2406.07524](https://arxiv.org/abs/2406.07524)
- 2024 💭📝 Meta-DiffuB: A Contextualized Sequence-to-Sequence Text Diffusion Model with Meta-Exploration. [arXiv:2410.13201](https://arxiv.org/abs/2410.13201)

#### 2023
- 2023 💭📝 AR-Diffusion: Auto-Regressive Diffusion Model for Text Generation. [arXiv:2305.09515](https://arxiv.org/abs/2305.09515)

#### 2022
- 2022 💭📝 SSD-LM: Semi-autoregressive Simplex-based Diffusion Language Model for Text Generation and Modular Control. [arXiv:2210.17432](https://arxiv.org/abs/2210.17432)

---

### 🤖 Embodied / VLA

#### 2025
- 2025 🤖🔗 HybridVLA: Collaborative Diffusion and Autoregression in a Unified Vision-Language-Action Model. [arXiv:2503.10631](https://arxiv.org/abs/2503.10631)

#### 2024
- 2024 🤖🔗 Diffusion-VLA: Scaling Robot Foundation Models via Unified Diffusion and Autoregression. [arXiv:2412.03293](https://arxiv.org/abs/2412.03293)

---

### 📐 Theory & General Frameworks

#### 2025
- 2025 📐 On Powerful Ways to Generate: Autoregression, Diffusion, and Beyond. [arXiv:2510.06190](https://arxiv.org/abs/2510.06190)

#### 2023
- 2023 📐 Sequential Data Generation with Groupwise Diffusion Process. [arXiv:2310.01400](https://arxiv.org/abs/2310.01400)

---

## <img height=34 src="https://raw.githubusercontent.com/Tarikul-Islam-Anik/Animated-Fluent-Emojis/master/Emojis/Office/Memo.png"/> How to Use This Repo

- Start from **Language & Reasoning** if you care about hybrid diffusion–AR language models (DxAR) for text.
- Look at **Embodied / VLA** for robot and vision-language-action hybrids.
- Check **Sign Language & Motion** for non-verbal sequence generation.
- See **Theory & General Frameworks** for conceptual overviews of autoregression vs diffusion.

---


## 🧩 Want to Contribute?

We welcome contributions! Please feel free to submit a PR or open an issue if you'd like to add new papers, tools, or correct any mistakes.

### ✅ Guidelines

- Only add papers that **explicitly connect diffusion and autoregression** (model or decoding).
- Use consistent formatting: `YEAR ICONS Title. [arXiv:ID](https://arxiv.org/abs/ID)`.
- Prefer papers with an **arXiv entry** so that every bullet has a stable link.
- If you add new domains (e.g., speech, images, code), consider adding a new section with its own icon.
