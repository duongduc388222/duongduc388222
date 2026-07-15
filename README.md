<div align="center">

<a href="https://ducduong-portfolio.vercel.app/">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=30&duration=3000&pause=800&center=true&vCenter=true&width=900&height=80&lines=Hi%2C+I'm+Duc+Duong;AI+%2F+ML+Researcher;Efficient+LLM+Inference+%26+KV+Cache+Management;Shooting+Toward+Agentic+Systems+%26+RL" alt="Typing SVG" />
</a>

### AI Researcher · CS & Mathematics @ Grinnell College

<a href="https://ducduong-portfolio.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"/></a>
<a href="https://www.linkedin.com/in/duchduong"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="mailto:duongduc@grinnell.edu"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/></a>
<a href="https://scholar.google.com/citations?user=q3b7yDwAAAAJ&hl=vi"><img src="https://img.shields.io/badge/Google%20Scholar-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white" alt="Google Scholar"/></a>

</div>

---

## About Me

I'm an AI/ML researcher focused on efficient large language model inference: making models run faster, longer, and cheaper without giving up accuracy. I'm a Computer Science and Mathematics student at Grinnell College, researching across labs at Rice and Stevens.

Most of my work centers on KV cache management and inference-time reasoning, where sampling, optimization, and systems meet. Increasingly, I'm carrying that efficiency work into agentic systems and reinforcement learning, where inference cost compounds and smarter memory and compute decisions matter most. I treat the whole pipeline as the thing to optimize, not a single model call. Open to research collaborations in efficient ML, NLP, inference-time reasoning, and RL.

**Focus for 2026:** efficient LLM inference, KV cache management, and extending both into agentic and RL systems.

[Portfolio](https://ducduong-portfolio.vercel.app/) · [LinkedIn](https://www.linkedin.com/in/duchduong) · duongduc@grinnell.edu · duonghongduc3003@gmail.com

---

## Publications

**Forget Without Compromise: Nexus Sampling for Streaming KV-Cache Eviction Under Fixed Budgets**
Duc Duong\*, Hoang Anh Duy Le\*, Jianwen Xie, Anshumali Shrivastava, Zhaozhuo Xu · arXiv:2606.23961, 2026
*\*Equal contribution.*

A training-free KV-cache eviction method that replaces the deterministic top-K every prior method relies on with weighted reservoir sampling over an iterative walk that surfaces bridge tokens. At 80% cache eviction it matches dense attention within ~1 point on LongBench while shrinking per-sequence cache memory up to 10× versus dense FlashAttention-2.

[![arXiv](https://img.shields.io/badge/arXiv-2606.23961-B31B1B?style=flat-square&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2606.23961)

---

## Education

**Grinnell College** — B.A. Computer Science & Mathematics · *Aug 2024 – May 2028*

- GPA 4.0 · Dean's List
- Coursework: Machine Learning, Artificial Intelligence, Reinforcement Learning, Linear Algebra, Probability & Statistics, Data Structures & Algorithms.

---

## Experience

**Rice University** — Research Assistant · *Mar 2026 – Present*

- Co-first author of *Nexus Sampling*, a training-free KV-cache eviction method that replaces the deterministic top-K every prior method relies on with weighted reservoir sampling over an iterative walk that surfaces bridge tokens.
- At 80% cache eviction, matched dense attention within ~1 point on LongBench while shrinking per-sequence cache memory up to 10× vs. dense FlashAttention-2, at 1.2–1.3× decode throughput and 15–23% lower per-step latency.
- Established the method's theoretical guarantees: long-run token survival as a product over steps (vs. top-K's collapse on the first below-cutoff step) and provable hub-amplification of bridge tokens.
- Separately researching Langevin dynamics and MCMC sampling to prune latent thought-vector spaces and curb redundant computation.

**Stevens Institute of Technology** — Research Assistant · *Dec 2025 – Present*

- Developing a feature-sampling agent that compresses a 3,000-gene candidate pool to 100–200 genes while holding near-baseline accuracy.
- Architecting a closed-loop agentic research pipeline with MCP-based PubMed retrieval, LASSO regression, and LLM-as-a-judge biomarker scoring.

**Gtel Data Research Group** — R&D Software Engineer · *May – Aug 2025*

- Fine-tuned an Ancient-to-Modern Vietnamese translation model with LoRA/QLoRA for parameter-efficient adaptation.
- Engineered a 1M+ sample synthetic dataset via a round-robin architecture across Gemini API keys for high-throughput curation.
- Ran weekly technical seminars on Transformer and Diffusion architectures and research-to-production workflows.

**Data Glacier** — NLP Intern · *Feb – May 2025*

- Built a hate-speech detection engine (BERT + Hugging Face Transformers) reaching a 0.92 F1 through custom fine-tuning.
- Cut inference latency 45% with Hugging Face Accelerate and ONNX Runtime; deployed containerized microservices on Docker + GCP with CI/CD.

---

## Selected Projects

**Spatial & Demographic Effects on Theft in Los Angeles** · *Dec 2025*
Nested logistic regression on the 2020 LAPD dataset; found population density the strongest negative predictor of theft, and quantified demographic differences in exposure. 1st Prize, USPROC Statistics Research Competition (ASA & CAUSE). [Results →](https://www.causeweb.org/usproc/usclap/2025/spring/winners)

**Predicting Tonal vs. Non-Tonal Languages** · *2024 – 2025*
Engineered spectral and pitch-based features over 125 multilingual clips from 18 countries; benchmarked 7 models to 65% accuracy (+20% over baseline) with reproducible scikit-learn and PyTorch pipelines. [Repo →](https://github.com/duongduc388222/predict-tonal-languages-machine-learning)

---

## Tech

**Languages**

<img src="https://skillicons.dev/icons?i=py,cpp,java,r,bash,latex" height="36" />

**ML / NLP**

<img src="https://skillicons.dev/icons?i=pytorch,tensorflow,sklearn" height="36" />

Also: Hugging Face Transformers · T5 · LoRA/QLoRA · reinforcement learning · ONNX · vector databases

**Systems**

<img src="https://skillicons.dev/icons?i=docker,kubernetes,gcp,aws,linux,git" height="36" />

Also: SQL · CI/CD · low-latency inference

---

## Recognition

- **Iowa Collegiate Mathematics Competition (ICMC)**
  - **First Place** · 96/100, 2026
  - **Second Place** · 99/100, 2025
- **Outstanding Award** — SCUDEM Mathematical Modeling: *AI Ouroboros* · SIMIODE, 2025
- **First Prize** — USPROC Statistics Research Competition · ASA & CAUSE, 2025

---

## GitHub Stats

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=duongduc388222&hide_border=true" height="165" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=duongduc388222&bg_color=ffffff&color=000000&line=3b82f6&point=2563eb&area=true&hide_border=true" width="95%" />

<img src="https://github-profile-trophy.vercel.app/?username=duongduc388222&theme=flat&no-frame=true&margin-w=15" width="95%" />

</div>

---

<div align="center">

**Beyond the work:** variant Sudoku (a devoted [Cracking the Cryptic](https://www.youtube.com/c/CrackingTheCryptic) viewer), badminton, and soccer. Always up for a good puzzle.

</div>
