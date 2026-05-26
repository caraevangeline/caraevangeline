# Hi, I'm Cara Evangeline 👋

**Machine Learning Engineer · London, UK**

ML Engineer with 5 years building and shipping production ML systems: spanning real-time computer vision, vision-language models, and full MLOps automation across major UK retail environments. Currently expanding into LLMs, RAG pipelines, and generative AI.

🎓MSc Big Data Science with Distinction · Queen Mary University of London | B.Tech Computer Science · NIT India

---

## What I do at VCA Technology

### Machine Learning Engineer · Feb 2025 – Present

- Optimised **Florence-2** and other VLMs for production: HuggingFace PyTorch → ONNX → TensorRT, fusing into three GPU-resident modules to eliminate CPU-fallback bottlenecks
- Evaluated zero-shot vision models: **SmolVLM, LLaVA, CLIP, SAM, YOLO-World** on real-time CCTV data to assess out-of-the-box vs fine-tuned approaches
- Trained **Co-DETR** (ViT backbone) for an internal annotation pipeline, cutting manual effort by **70%** and eliminating outsourcing costs
- Delivered a first-iteration POC for a major UK supermarket franchise at **90% F1** → went into live production
- Built an end-to-end **ClearML MLOps pipeline** (ingestion → training → ONNX conversion → eval) across distributed GPU workers and queues
- Managing 10+ concurrent projects, balancing rapid prototyping with production stability

### Data Scientist · Oct 2021 – Jan 2025

- Delivered a **cross-camera person re-identification and theft-detection system** deployed across major UK retail stores, **82–85% Rank@1** accuracy in forensic tracking
- Trained a **colour classification model** for CCTV under variable lighting and weather, lifting accuracy from ~**30% to 75%+** over classical colour-binning baselines
- Curated a **1M+ image thermal-imaging dataset** for large-scale classification under challenging environmental conditions
- Designed scalable annotation pipelines using CVAT and Encord SDKs at scale

---

## Impact by numbers

| Metric | Result |
|---|---|
| Retail CV POC (supermarket client) | 90% F1-score → live production |
| Manual annotation effort reduction | 70% cut via Co-DETR pipeline |
| Person re-identification accuracy | 82–85% Rank@1 across retail stores |
| Colour classification improvement | ~30% → 75%+ over classical methods |
| Thermal-imaging dataset curated | 1M+ images |

---

## Projects

### PaperQA - RAG over Research Corpus
*LangChain · Chroma · HuggingFace · RAGAS · LLM-as-a-Judge*

- End-to-end RAG pipeline over CV research papers: chunking, embedding, MMR retrieval (k=5), LLM response generation
- Full evaluation suite: RAGAS metrics (faithfulness, context precision/recall, answer relevancy) + LLM-as-a-Judge rubric (1–5 across faithfulness, relevance, correctness, coherence)
- Multi-model comparison CLI: Phi-3, GPT-4o, GPT-4o-mini, Claude Haiku, Claude Sonnet

🔗 [github.com/caraevangeline/PaperQA-RAG-over-Research-Corpus](https://github.com/caraevangeline/PaperQA-RAG-over-Research-Corpus)

---

### Multi-Vehicle Detection with Knowledge Distillation
*Co-DETR (ViT teacher) · YOLOv8-Nano (student) · 3LC · ONNX*

- Distilled a Co-DETR transformer teacher → YOLOv8-Nano student on a noisy Kaggle multi-vehicle dataset
- Used 3LC platform for embedding-based annotation error discovery and iterative label correction
- ~0.75 mAP on test set (~0.90 estimated true mAP after noise correction); deployed via PyTorch + ONNX

🔗 [github.com/caraevangeline/Kaggle-Computer-Vision-Challenge](https://github.com/caraevangeline/Kaggle-Computer-Vision-Challenge)

---

### Cross-Task Transfer Learning in Visually Grounded Dialogue *(MSc Thesis)*
*VGG16 · LSTM · GuessWhat?! dataset · Oracle · Guesser · QGen*

- Built a shared VGG16 + 512-dim LSTM encoder over the GuessWhat?! dataset (160K+ dialogues, 672K Q&A pairs) feeding three task heads: Oracle, Guesser (classification), and QGen (generation)
- **Key finding:** cross-type transfer (generation → classification) degraded accuracy by up to **30%** with a frozen encoder (QGen → Guesser: 59.44% → 30.2%)
- Same-type transfer preserved accuracy (Oracle → Guesser: 59.63% vs 59.44% baseline); full fine-tuning halved convergence time (6 → 3 epochs)

🔗 [github.com/caraevangeline/Cross-Task-Transfer-Learning](https://github.com/caraevangeline/Cross-Task-Transfer-Learning)

---

## Stack

**Generative AI & NLP:** LLMs · RAG · LangChain · HuggingFace · RAGAS · VLMs · Prompt Engineering

**Computer Vision:** YOLO · Co-DETR · Florence-2 · CLIP · SAM · ReID · EfficientNet · OpenCV

**ML & Deployment:** PyTorch · ONNX · TensorRT · Docker · ClearML · AWS · GCP · Flask

**Languages:** Python · C++ · SQL · R

---

## GitHub stats

![GitHub streak](https://streak-stats.demolab.com?user=caraevangeline&hide_border=true)
---

## Find me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-caraevangeline-blue?style=flat&logo=linkedin)](https://linkedin.com/in/caraevangeline)
[![Email](https://img.shields.io/badge/Email-caraevangeline10@gmail.com-red?style=flat&logo=gmail)](mailto:caraevangeline10@gmail.com)