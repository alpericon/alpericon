# Hi, I'm Alper Düzgün 👋

**ML engineer in the making**, and a senior **Artificial Intelligence & Data Engineering** student at **Istanbul Technical University (İTÜ)**.
I train language models from scratch, fine-tune vision foundation models, and make robots pick things up in simulation.

🔎 **Open to full-time & part-time roles** in **ML / AI Engineering, Data Science, Computer Vision, Robotics and ML Research**. Graduating **January 2027**.

<p>
  <a href="https://www.linkedin.com/in/alper-d%C3%BCzg%C3%BCn-b78b54324"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:alpericon0440@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

## 🔬 What I'm working on

### HaLLM: weight sharing for language models (İTÜ graduation thesis)
[`hazarsozer/hallm`](https://github.com/hazarsozer/hallm)

Does HaLViT's *"half of the weights are enough"* W+Wᵀ trick (CVPR 2024 W) carry over from Vision Transformers to GPT-style language models?
Advised by Prof. B. U. Töreyin. **I've led the project since September 2026.**

- Built a controlled experiment ladder: GPT-style LMs trained from scratch on **WikiText-103** (614M tokens per run). Only the sharing mechanism changes between arms, so every perplexity delta can be attributed to it.
- Quantified the "sharing tax": attention-only W+Wᵀ cuts stored weights by **16.7% for a +3.97% perplexity cost**, the cheapest trade-off of all variants (3 seeds).
- Showed that, at fixed storage, **looping layers beats W+Wᵀ**, both on language modelling *and* on synthetic multi-hop reasoning.
- Ran it like real research: pre-registered hypotheses, multi-seed runs, VRAM pre-flight checks, and checkpoints versioned on Hugging Face. **11 merged PRs.**

`PyTorch` · `Transformers` · `bf16 training` · `experiment design`

---

## 🛠️ Featured projects

| Project | What it does | Stack |
|---|---|---|
| 🎯 [**SAMet: Video Object Segmentation with SAM 2**](https://github.com/alpericon/YZV416E_Project) | *Team project, İTÜ Computer Vision course.* Evaluation and fine-tuning pipeline for Meta's SAM 2 on DAVIS 2017: zero-shot baseline (**0.905 J&F**), mask-decoder fine-tuning with a frozen backbone, and ablations over LR scheduling, boundary loss and uncertainty-weighted losses. | PyTorch, SAM 2, DAVIS, TensorBoard |
| 📈 [**Unsupervised Anomaly Detection in HDFS Logs**](https://github.com/alpericon/Anomaly-Detection-in-System-Logs) | *Pair project with Yusuf Karamustafa (pair-programmed; commits are under his account).* End-to-end pipeline: parses **11M+ log entries (1.47 GB)** with Apache Spark, maps raw messages to 29 event templates, builds 575K block-level traces, and trains an **LSTM autoencoder** that flags anomalous executions without labels. Includes threshold sensitivity and scalability benchmarks. | Apache Spark, PyTorch, LSTM |
| 🤖 [**Robotics Med Cup Collector**](https://github.com/alpericon/Robotics-Med-Cup-Collector) | *Team project.* Autonomous pipeline for a Hello Robot Stretch in MuJoCo: navigate to tables, detect humans and cups, grasp with visual servoing, and drop the cup in the trash. | MuJoCo, YOLO, Python |

### Other projects
- 🚗 [**Real-Time Accident Detection**](https://github.com/yusufkaramustafa/Real-Time-Accident-Detection): *team project.* Classifies vehicle sensor time series (hard braking, sudden acceleration, manoeuvres, crashes) to flag accidents as they happen.
- 🎬 [**TMDB Movie Analytics Dashboard**](https://github.com/itu-dallasli/imdb_dashboard_powerbi): *team project.* Data cleaning and EDA in Python, feeding an interactive Power BI dashboard on budget vs. revenue, production geography and actor co-star networks.

---

## 🧰 Tech stack

**Languages:** Python · TypeScript/JavaScript<br>
**ML / DL:** PyTorch · Hugging Face · Ultralytics YOLO · SAM 2<br>
**Data:** Apache Spark · NumPy · Pandas · Jupyter · Power BI<br>
**Tools:** Git · uv · CUDA · TensorBoard · MuJoCo

---

<sub>📫 Best way to reach me: <a href="mailto:alpericon0440@gmail.com">email</a> or <a href="https://www.linkedin.com/in/alper-d%C3%BCzg%C3%BCn-b78b54324">LinkedIn</a>.</sub>
