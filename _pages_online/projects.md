---
title: "Projects"
layout: archive
permalink: /projects/
---

<style>
a:link, a:visited {
  text-decoration: none;
}

a:hover, a:active {
  text-decoration: underline;
}
</style>

  - **VAU-R1: Advancing Video Anomaly Understanding via Reinforcement Fine-Tuning**
    - Duration: *01/05/2025 - 06/06/2025*
    - Motivation: Video Anomaly Understanding (VAU) is vital for smart cities, surveillance, and disaster response but remains difficult due to the need for precise spatio-temporal reasoning and interpretability. Current methods lack causal/contextual understanding and standardized reasoning benchmarks.
    - Key Contributions:
      - VAU-R1: A reinforcement fine-tuning framework that enhances MLLM reasoning on anomaly tasks, outperforming standard supervised methods.
      - VAU-Bench: The first large-scale benchmark with Chain-of-Thought annotations for anomaly reasoning, featuring diverse videos, QA pairs, temporal labels, and rationales.
      - Unified Evaluation: A comprehensive protocol assessing reasoning quality, accuracy, and temporal localization.
    - Resources: [Project Page](https://q1xiangchen.github.io/VAU-R1/), [Code](https://github.com/GVCLab/VAU-R1), [Paper](https://arxiv.org/abs/2505.23504), [Data](https://huggingface.co/datasets/7xiang/VAU-Bench)

  - **Synthesizing Artistic Realism: Stroke Painting Algorithms with Shader Enhancements  (PainterApp)**
    - Duration: *23/05/2024 - 30/05/2024*
    - Objective: Develop an enhanced method for synthesizing artistic realism through advanced stroke painting algorithms with shader enhancements. The goal was to transfer the stroke painting style from real-world photographs to digital images, improve the visual quality of these algorithms, and create a user-friendly interface for creating digital paintings with realistic brush strokes. The project also aimed to present vivid and lifelike representations of digital paintings in 3D.
    - Achievements:
      - Improved the visual quality of stroke painting algorithms from previous methods through cosine mapping, logistic function mapping, and shader enhancements.
      - Developed an efficient and user-friendly program for creating digital paintings with realistic brush strokes.
      - Achieved vivid and lifelike representations of digital paintings in 3D, bridging the gap between 2D and 3D painting rendering techniques.
    - Resources: [GitHub](https://github.com/HuilinChen943/paintercpp), [Technical Report ](/files/cg_report.pdf)

  - **Motion meets Attention: Video Motion Prompts**
    - Duration: *20/11/2023 - 19/01/2024*
    - Supervisor: [Dr. Lei Wang](https://leiwangr.github.io/), [Prof. Piotr Koniusz](https://www.koniusz.com/), [Prof. Tom Gedeon](https://users.cecs.anu.edu.au/~Tom.Gedeon/)
    - Accpeted by: [**ACML 2024**](https://www.acml-conf.org/2024/) [<span style="color: red;">Long presentation, 5.67% for long presentations</span>,<span style="color: blue;"> 26% overall acceptance rate</span>]
    - Research Grant: **NCI Adaptater Scheme Q4 2023 (HPC funding scheme)**
    - Objective: Enhance the extraction and utilization of motion features in video content for action recognition tasks by developing a novel 'motion prompt layer'. This layer employs a modified Sigmoid function with adjustable slope and shift parameters to create and modulate attention maps from frame differencing maps. This setup aims to overcome the limitations of traditional 'blind motion extraction' methods by ensuring that only relevant motion signals are highlighted and used as inputs to the model, thereby improving the accuracy and efficiency of action recognition systems.
    - Achievements:
      - Developed a novel video motion prompt layer that can be seamlessly integrated into existing video model architectures like SlowFast, X3D, and TimeSformer.
      - Introduced a temporal attention variation regularization to ensure smooth continuity of attention maps, enhancing the model's generalizability and interpretability.
      - Achieved state-of-the-art performance on various benchmarks, including the large-scale FineGym and MPII Cooking 2 datasets for fine-grained action recognition.
    - Resources: [Project Page](https://q1xiangchen.github.io/motion-prompts/), [Code](https://github.com/q1xiangchen/VMPs), [Paper](https://arxiv.org/abs/2407.03179)

  - **Vehicle Image Translation: Adapting Synthetic Styles to Real-World Scenarios**
    - Duration: *19/10/2023 - 30/10/2023*
    - Objective: This project focuses on the application of Generative Adversarial Networks (GANs), specifically CycleGAN, for the purpose of image-to-image translation. The goal is to stylistically adapt vehicle images from the synthetic Vehicle-X dataset to resemble those in the real-world VeRi dataset, enhancing the robustness and accuracy of vehicle recognition algorithms.
    - Achievements:
      - Successfully trained a CycleGAN model to transform the style of Vehicle-X images to align with VeRi dataset aesthetics.
      - Improved the domain adaptation for vehicle recognition tasks in varied lighting and environmental conditions.
    - Resources: [GitHub](https://github.com/q1xiangchen/CycleGAN_vehicle), [Technical Report ](/files/I2I_report.pdf)