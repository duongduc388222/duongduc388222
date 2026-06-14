# Duc Duong

**AI Researcher · CS & Mathematics @ Grinnell College**

AI/ML researcher working on efficient LLM inference, inference-time reasoning, and agentic systems. I care about the math underneath the models — sampling, optimization, and the systems that make inference fast — and currently research KV-cache-efficient inference and closed-loop agentic pipelines across labs at Rice and Stevens. Open to research collaborations in efficient ML, NLP, and quantitative methods.

**Focus for 2026:** efficient LLM inference, inference-time reasoning, and applied quantitative research.

📍 [Portfolio](https://ducduong-portfolio.vercel.app/) · 💼 [LinkedIn](https://www.linkedin.com/in/duchduong) · ✉️ duongduc@grinnell.edu · 📨 duonghongduc3003@gmail.com

---

## Education

**Grinnell College** — B.A. Computer Science & Mathematics · *Aug 2024 – May 2028*

- GPA 4.0 · Dean's List
- Coursework: Machine Learning, Artificial Intelligence, Linear Algebra, Probability & Statistics, Data Structures & Algorithms, Quantitative Modeling
- Certifications: Oracle Certified Data Science Professional · GARP FRM Candidate

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

## Quant

Pursuing the **GARP Financial Risk Manager (FRM)** designation alongside coursework in probability, statistics, and quantitative modeling. I'm interested in systematic and quantitative research — applying the same sampling, optimization, and inference work I do in ML to market data, risk, and signal. Currently building toward research-grade strategies and working through quant finance literature.

---

## Tech

**Languages** · Python · C++ · Java · R · SQL · Bash · LaTeX
**ML / NLP** · PyTorch · TensorFlow · Hugging Face · Transformers · T5 · LoRA/QLoRA · Reinforcement Learning · ONNX · vector databases
**Systems** · GCP · Docker · Linux · CI/CD · low-latency inference · Git

---

## Recognition

- **1st Prize** — USPROC Statistics Research Competition (ASA & CAUSE, 2025)
- **2nd Place** — Iowa Collegiate Mathematics Competition (99/100, 2025)
- **Outstanding Award** — SCUDEM Math Modeling 2025: *AI Ouroboros* (SIMIODE)

---

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=duongduc388222&show_icons=true&hide_border=true&count_private=true" height="150" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=duongduc388222&layout=compact&hide_border=true&langs_count=8" height="150" />
</div>
