---
layout: single
title: "Research"
permalink: /research/
---

My current research bridges **Conversational AI**, **HealthTech ML**, and **Human–AI Interaction** — focusing on ethical, explainable, and empathetic systems for real-world guidance and cognitive health.

---

### 🧭 1. Peer-Mentor Advising Chatbot (Thesis Project)
**Title:** *Survey-Grounded Style + Template→Rewrite vs Plain LLM*  
**Advisors:** Prof. Susan McRoy (UWM)  
**Duration:** Feb 2025 – Present  

This research builds a peer-mentor ↔ student advising chatbot that compares two advisor strategies:  
1. **Raw LLM dialogs**, and  
2. **Template→Rewrite generation**, where stored academic values (GPA, prerequisites, workload) are inserted via templates and rewritten by the model for fluency and empathy.

We evaluate four setups — *Survey only*, *Survey + Ethics*, *Survey + Templates*, and *Survey + Ethics + Templates* — across weak, average, and strong student profiles.

**Key Focus Areas**
- Factual accuracy and tone alignment in academic advising dialogs  
- Role of survey-grounded and ethics-informed style conditioning  
- Template-guided neural generation for trustworthy educational AI  

**Methods**
- Llama-3.1-8B-Instruct (local, via Ollama/LM Studio)  
- Template→Rewrite pipeline with JSON logging for factual audits  
- LLM-as-judge evaluation (factuality / empathy / relevance / naturalness)  
- Human pilot with peer mentors & staff evaluators  

**Goal:** Develop reproducible frameworks for *trustworthy, empathetic dialog agents* in academic and career contexts.  

---

### 🧠 2. Hybrid Semantic–Graph Speech Analysis for Alzheimer’s Detection
**Title:** *Correlating Semantic Graph Patterns with Cognitive Decline Markers*  
**Advisors:** Prof. Lu He (UWM)  
**Duration:** Oct 2025 – Present  
**Accepted at:** SEAWINDS Symposium 2025 (MSOE)

This project explores the early detection of Alzheimer’s disease using **speech-based graph analytics** and **semantic embeddings**.  
We model spontaneous speech as semantic graphs, extracting features such as node degree, edge density, and global coherence, then correlate these with cognitive-decline markers.

**Pipeline Overview**
- **Input:** DementiaBank Pitt Corpus (transcript-only access)  
- **Feature Extraction:** NetworkX + Sentence-BERT embeddings  
- **Modeling:** Graph-metric + Transformer hybrid pipeline  
- **Outcome:** Identify early linguistic disorganization patterns predictive of Alzheimer’s onset  

**Goal:** Advance explainable speech biomarkers for cognitive health monitoring.  

---

### 🧩 Research Themes
- Empathetic and trustworthy dialog design  
- Ethical large-language-model grounding  
- Multimodal (semantic + graph) signal fusion for health AI  
- Evaluation frameworks combining human + LLM judgment  

---

📍 *Updated: November 3 2025*
