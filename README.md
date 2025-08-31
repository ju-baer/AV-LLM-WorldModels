<div align="center">
   <img src="image.png" alt="AV-LLM-WorldModels Logo" width="300"/>
<h1><b>AV-LLM-WorldModels</b> </h1> 
<h2> <i>Rethinking Autonomous Driving: A Survey and Roadmap for Large Language Models and World Models in Hybrid AV Architectures</i></h2> 

[![Paper](https://img.shields.io/badge/📄_Paper-Coming_Soon-blue?style=for-the-badge)](./paper.pdf)
[![Survey](https://img.shields.io/badge/📚_Survey-Live-green?style=for-the-badge)](#survey)
[![Demos](https://img.shields.io/badge/🎮_Demos-Interactive-orange?style=for-the-badge)](./demos/)
[![Roadmap](https://img.shields.io/badge/🗺️_Roadmap-2025--2030-purple?style=for-the-badge)](#roadmap)
[![License](https://img.shields.io/badge/License-MIT-red?style=for-the-badge)](./LICENSE)

*Bridging Language, Imagination, and Autonomous Intelligence*

</div>

---

## Vision Statement

**What if autonomous vehicles could think, reason, and imagine like humans?**

Traditional AV pipelines are brittle chains of specialized modules. When one breaks, the whole system fails. We propose a revolutionary paradigm where:

- **Large Language Models** serve as reasoning engines for contextual decision-making
- **World Models** act as imagination layers for scenario simulation and edge-case prediction
- **Hybrid Integration** combines the best of modular interpretability and end-to-end generalization

**Why this repo?**
- A curated survey of LLMs, world models, and foundation models in AVs.
- A novel taxonomy of approaches, visualized interactively.
- Conceptual demos showcasing LLM reasoning and world model simulations.
- A forward-looking roadmap for hybrid AV stacks, human-AI interaction, and ethical AV design.
- Community-driven resources to accelerate AV research.

---


## Core Contributions

### Comprehensive Taxonomy
A novel multi-dimensional classification system spanning:
- **Model Types**: LLMs, World Models, Foundation Models, Hybrid Systems
- **AV Tasks**: Perception, Prediction, Planning, Control
- **Modalities**: Vision, LiDAR, Radar, Language, Multimodal
- **Training Paradigms**: End-to-End, Modular, Fine-tuned, Few-shot

### Hybrid Architecture Blueprint
Revolutionary LLM-World Model AV stack:
```
Sensors → Perception → Imagination → Reasoning → Planning → Control
```

### Interactive Demonstrations
Live notebooks showcasing:
- Toy world models for 2D driving scenarios
- LLM-powered reasoning in complex traffic situations
- End-to-end hybrid pipeline simulations

### Future Roadmap
Strategic vision for 2025-2030 covering:
- Interactive natural language AV interfaces
- Simulation-accelerated training
- Culturally adaptive driving systems
- Ethical AI embedding

---

## Survey Navigation

### [World Models](./survey/world_models.md)
*The imagination layer of autonomous systems*
- **Generative Dynamics**: DreamerV3, MuZero, TD-MPC2
- **Driving Simulation**: GAIA-1, MILE, VideoWorldSim
- **Interactive Environments**: Genie, synthetic scenario generation

### [Language Models](./survey/llms.md)
*The reasoning engine for contextual intelligence*
- **Embodied LLMs**: PaLM-E, RT-2, VLA
- **Driving-Specific**: DriveGPT, DriveLM, Lingo-1/2
- **Multimodal Reasoning**: LLaVA, GPT-4V, CLIP-ViT

### [Foundation Models](./survey/foundation_models.md)
*The perception backbone of modern AVs*
- **Unified Frameworks**: UniAD, VAD, OpenDrive
- **BEV Perception**: BEVFormer, TransFusion
- **End-to-End**: E2EAD, Wayve's LINGO-2

### [Multimodal Integration](./survey/multimodal.md)
*Bridging sensors and semantics*
- **Language Grounding**: Talk2Car, BDD-X
- **Cross-Modal Fusion**: Vision-LiDAR-Language models
- **Interactive Communication**: Human-AV interfaces

---

## Featured Demonstrations

| Demo | Description | Complexity | Interactive |
|------|-------------|------------|-------------|
| **Toy World Model** | 2D driving with predictive simulation | Beginner | ✅ |
| **LLM Reasoning** | Natural language traffic decision-making | Intermediate | ✅ |
| **Hybrid Pipeline** | Full LLM-World Model integration | Advanced | ✅ |
| **Taxonomy Explorer** | Interactive model classification | All Levels | ✅ |

---

## Curated Resources

### Papers
The `survey/` folder organizes key papers into categories:
- **World Models**: DreamerV3, MuZero, GAIA-1, Genie, TD-MPC2, MILE, VideoWorldSim, DriveSim-Net, WorldFormer, NeRF-World.
- **LLMs in Robotics/Vision**: PaLM-E, RT-2, DriveGPT, Lingo-1/Lingo-2, DriveLM, LLaVA, GPT-4V, CLIP-ViT, Octo, VLA, AutoLLM, DriveChat.
- **Foundation Models for AV Perception**: BEVFormer, VAD, UniAD, TransFusion, Lingo-AV, OpenDrive, E2EAD.
- **Multimodal Integration**: Sensor fusion and language grounding (e.g., Talk2Car, BDD-X).

Each `.md` file includes paper titles, authors, publication details, and links to arXiv or publisher pages.

### Datasets
The `datasets/` folder curates AV datasets with a focus on language annotations:
- **nuScenes**: Multimodal dataset with camera, LiDAR, and radar.
- **Waymo Open Dataset**: Large-scale dataset for perception and planning.
- **Argoverse 2**: Motion forecasting with rich annotations.
- **Talk2Car**: Language-annotated commands for driving tasks.
- **BDD-X**: Language-augmented driving scenarios.
- **Synthetic Wishlist**: Proposals for generative world model-based datasets to address annotation scarcity.

### Demos
The `demos/` folder includes lightweight Jupyter notebooks:
- **Toy World Model**: Simulates a 2D driving environment using a DreamerV3-like model (PyTorch/JAX).
- **LLM Reasoning**: Demonstrates language-guided planning with Hugging Face Transformers (e.g., LLaVA).
- **Hybrid Pipeline**: Integrates sensor inputs, world model predictions, and LLM reasoning for a simplified AV pipeline.

### Visualizations
The `figures/` folder contains high-quality visuals:
- **Taxonomy Plot**: Interactive 3D plot (Plotly) classifying approaches by model type, task, modality, and training paradigm.
- **AV Pipeline**: Diagram of traditional modular AV stack.
- **LLM-World Model Stack**: Proposed hybrid architecture (input → perception → imagination → reasoning → planning → control).
- **Roadmap Timeline**: Visual timeline for future AV research directions.

## Roadmap and Future Directions

Our roadmap (`roadmap/`) envisions the future of AVs with LLMs and world models:
- **Hybrid AV Stack**: LLMs for reasoning, world models for simulation.
- **Interactive AVs**: Natural language interfaces for human-AV communication (e.g., “park near the café”).
- **Simulation Acceleration**: World models generating rare scenarios (e.g., adverse weather, pedestrian anomalies).
- **Policy and Ethics**: Culturally adaptive AVs with embedded safety constraints.
- **Adversarial Robustness**: Simulating adversarial scenarios to stress-test AVs.
- **Transfer Learning**: Adapting models across domains (urban, rural, highway).
- **Evaluation Metrics**: Standardized metrics for reasoning, safety, and scenario coverage.

Explore `roadmap/future_research.md` for detailed ideas and `roadmap/evaluation_metrics.md` for proposed benchmarks.

---

## Repository Statistics

```
Survey Papers: 150+ curated references
Model Coverage: 50+ LLMs, World Models, Foundation Models  
Datasets: 20+ AV datasets with language annotations
Demos: 4 interactive Jupyter notebooks
```

---
