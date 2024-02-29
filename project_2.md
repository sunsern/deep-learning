# Project 2: DL Capstone project
**Due Mar 29, 2024**

In this project, you will be working as a team to build a state-of-the-art DL model for a
domain of your choice. Once you have picked a problem, you will be looking for the state-of-the-art models and/or techniques for your problem. You might find important DL papers listed below helpful. You and your team will then have to implement and conduct benchmarking to verify the model's claimed performance. Additionaly, you want to also throw in your own twist such as running it on a different set of data, or tweaks some of the knobs to improve the performance.

## Timeline

### Week 8
- Form a group of no more than 5 students
- Choose one of the problems listed below or come up with your own
### Week 9-11
- Research and look for the state-of-the-art deep learning model for the problem of choice
- Implement the DL model and at least one baseline model.
- Design experiments to verify that the model really works better than the baseline model.
- Analyze the results and try to improve the model further.
### Week 12
- Present your project
- Publish a Medium article.

## Deliveries

At the end, you will be turning in the following:

1. A github repo containing notebooks describing your experiments
2. A deck of presentation slides
3. A 10-min presentation
    - All members must be presenting
    - Must cover the following:
        - problem statement
        - solutions before DL
        - state-of-the-art DL model (citation needed)
        - explanation of how the DL model works
        - your own experiments and results
        - lesson learned from the project
4. A medium article report

## List of Deep Learning applications

1.  **Computer Vision:**

  -   Image Classification
  -   Object Detection
  -   Image Segmentation
  -   Facial Recognition
  -   Autonomous Vehicles
2.  **Natural Language Processing (NLP):**

  -   Machine Translation
  -   Sentiment Analysis
  -   Text Generation
  -   Question Answering Systems
  -   Named Entity Recognition
3.  **Speech Recognition:**

  -   Speech-to-Text Conversion
  -   Speaker Recognition
  -   Voice User Interfaces
4.  **Healthcare:**

  -   Medical Image Analysis (MRI, CT Scans)
  -   Disease Diagnosis
  -   Drug Discovery
  -   Personalized Medicine
5.  **Finance:**

  -   Algorithmic Trading
  -   Fraud Detection
  -   Credit Scoring
  -   Risk Assessment
6.  **Robotics:**

  -   Object Grasping and Manipulation
  -   Autonomous Navigation
  -   Human-Robot Interaction
7.  **Generative Models:**

  -   Image Generation
  -   Text Generation
  -   Music Generation
8.  **Recommendation Systems:**

  -   Product Recommendations (e.g., Amazon, Netflix)
  -   Content Personalization
  -   Music and Movie Recommendations
9.  **Virtual Assistants:**

  -   Speech Recognition
  -   Natural Language Understanding
  -   Task Automation
10.  **Art and Creativity:**

  -   Style Transfer
  -   DeepDream
  -   Artistic Image Generation
11.  **Environmental Monitoring:**

  -   Climate Modeling
  -   Deforestation Detection
  -   Wildlife Conservation
12.  **Security and Surveillance:**

  -   Intrusion Detection
  -   Anomaly Detection
  -   Video Surveillance
13.  **Education:**

  -   Adaptive Learning Systems
  -   Intelligent Tutoring Systems
14.  **Autonomous Systems:**

  -   Drones and UAVs
  -   Autonomous Robots
  -   Self-driving Cars
15.  **Industrial Automation:**

  -   Predictive Maintenance
  -   Quality Control
  -   Supply Chain Optimization

## Important Papers Organized by Domain

### Image

#### ViT related:
  - [An Image is Worth 16x16 Words: Transformers for Image Recognition at Scale (ViT)](https://arxiv.org/abs/2010.11929)
  - [Emerging Properties in Self-Supervised Vision Transformers](https://arxiv.org/abs/2104.14294)
  - [Training data-efficient image transformers & distillation through attention](https://arxiv.org/abs/2012.12877v2)
  - [Swin Transformer: Hierarchical Vision Transformer using Shifted Windows](https://arxiv.org/abs/2103.14030)
  - [A ConvNet for the 2020s (a CNN that implements several key components that contribute to the performance of Vision Transformers)](https://arxiv.org/abs/2201.03545)
  - [(CLIP) Learning Transferable Visual Models From Natural Language Supervision](https://arxiv.org/abs/2103.00020)

#### Diffusion related:
  - [High-Resolution Image Synthesis with Latent Diffusion Models](https://arxiv.org/abs/2112.10752)
  - [Denoising Diffusion Probabilistic Models (DDPM)](https://arxiv.org/abs/2006.11239)
  - [Classifier-Free Diffusion Guidance](https://arxiv.org/abs/2207.12598)

#### Others:
  - [Taming Transformers for High-Resolution Image Synthesis (VQGAN)](https://arxiv.org/abs/2012.09841)
  - [Segment Anything (SAM)](https://arxiv.org/abs/2304.02643)
  - [DINOv2: Learning Robust Visual Features without Supervision](https://arxiv.org/abs/2304.07193)
  - [Bayesian Flow Networks](https://arxiv.org/abs/2308.07037)

### NLP

- [Language Models are Few-Shot Learners (GPT-3)](https://arxiv.org/abs/2005.14165)

- [Chain-of-Thought Prompting Elicits Reasoning in Large Language Models](https://arxiv.org/abs/2201.11903)

- [Training language models to follow instructions with human feedback](https://arxiv.org/abs/2203.02155)

- [Training Compute-Optimal Large Language Models (Chinchilla)](https://arxiv.org/abs/2203.15556)

- [The Flan Collection: Designing Data and Methods for Effective Instruction Tuning](https://arxiv.org/abs/2301.13688)

- [LLaMA: Open and Efficient Foundation Language Models](https://arxiv.org/abs/2302.13971)

- [Toolformer: Language Models Can Teach Themselves to Use Tools](https://arxiv.org/abs/2302.04761)

### 3D Rendering

- [NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis](https://arxiv.org/abs/2003.08934)

- [Highly accurate protein structure prediction with AlphaFold](https://www.nature.com/articles/s41586-021-03819-2)

## Recent DL Papers

### 2020

- [NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis](https://arxiv.org/abs/2003.08934)
- [Denoising Diffusion Probabilistic Models](https://arxiv.org/abs/2006.11239)
- [Taming Transformers for High-Resolution Image Synthesis](https://arxiv.org/abs/2012.09841)
- [Language Models are Few-Shot Learners](https://arxiv.org/abs/2005.14165)

### 2021

- [Geometric Deep Learning: Grids, Groups, Graphs, Geodesics, and Gauges](https://arxiv.org/abs/2104.13478)
- [Learning Transferable Visual Models From Natural Language Supervision](https://arxiv.org/abs/2103.00020)
- [Highly accurate protein structure prediction with AlphaFold][def]
- [Grokking: Generalization Beyond Overfitting on Small Algorithmic Datasets](https://arxiv.org/abs/2201.02177)
- [LoRA: Low-Rank Adaptation of Large Language Models](https://arxiv.org/abs/2106.09685)
- [Classifier-Free Diffusion Guidance](https://arxiv.org/abs/2207.12598)
- [Emerging Properties in Self-Supervised Vision Transformers](https://arxiv.org/abs/2104.14294)

### 2022

- [Training Compute-Optimal Large Language Models](https://arxiv.org/abs/2203.15556)
- [High-Resolution Image Synthesis with Latent Diffusion Models](https://arxiv.org/abs/2112.10752)
- [Training language models to follow instructions with human feedback](https://arxiv.org/abs/2203.02155)
- [Elucidating the Design Space of Diffusion-Based Generative Models](https://arxiv.org/abs/2206.00364)
- [Cold Diffusion: Inverting Arbitrary Image Transforms Without Noise](https://arxiv.org/abs/2208.09392)

### 2023

- [Toolformer: Language Models Can Teach Themselves to Use Tools](https://arxiv.org/abs/2302.04761)
- [3D Gaussian Splatting for Real-Time Radiance Field Rendering](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/3d_gaussian_splatting_high.pdf)

