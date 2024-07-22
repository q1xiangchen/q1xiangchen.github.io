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

## Industry Projects
  - **Robust anomaly detection in human-centric videos**
    - Duration: *01/01/2024 - 30/06/2024*
    - Investigators:
      - Lead CI: [Dr. Lei Wang](https://leiwangr.github.io/)
      - Researchers: Qixiang Chen, Xiuyuan Yuan, Liyun Zhu, Arjun Raj, Liwen Luo
    - Research Grant: **The NCI National AI Flagship Merit Allocation Scheme**
    - Objective: This project aims at developing advanced computer vision and deep learning techniques to identify and characterise anomalies in video data where humans are central. The project leverages cutting-edge technology to enhance security, safety, and surveillance systems, making them more effective in detecting unusual behaviours and events, which may range from security breaches and accidents to rare medical conditions in healthcare applications.
    - Achievements:
      The significance of this project lies in its unique focus on human-centric videos. While anomaly detection in videos is an established field, the novelty emerges from its specialised applications in situations where human activity is central. The innovative aspects include (i) Robustness: The project seeks to develop highly reliable models capable of detecting anomalies in complex, real-world scenarios, where human interactions and activities can vary significantly. (ii) Real-time analysis: By applying these methods to real-time video streams, the project addresses the demand for timely responses to anomalies in security, industrial, and healthcare settings. (iii) Ethical considerations: The project incorporates ethical considerations, such as ensuring privacy and avoiding bias in the identification of anomalies, thereby making the technology responsible and trustworthy.

## Academic Projects
  - **MotionNetLite: Video Dynamics Distillation for Scalable Models**
    - I am a Assistant Researcher in this project
    - Duration: *01/01/2024 - 31/12/2024*
    - Research Grant: **National Computational Merit Allocation Scheme 2024 (NCMAS 2024)**
    - Objective: In this research project, we aim to develop more lightweight video data formats which are able to efficiently distill the motions at different granular levels by removing redundant information while focusing on the core dynamics. We also explore the acceleration of training and testing while reducing the amount of video data for storage, and answer a scientific question ‘How much information is contained in the video data and in what format?’. Many downstream video processing tasks will benefit from our video dynamic distillation process, towards making video understanding much easier and more efficient. This also opens up a new research direction in exploring better video data representations for more lightweight cutting-edge video models.
    - Achievements:
      This work has potential to impact Safety and Security, Future Cities, IoT, Agri-business, Defence via applications in Health and wellbeing, Safety, and Innovative industries. Our work focuses on researching advanced technologies from data that support all areas of science and society to provide national benefit. Video understanding, e.g., action recognition and anomaly detection, is needed in surveillance of airports, malls, etc. It has applications in monitoring health and well-being of elderly population, in farming, and analysis of crops. This project has also potential to ‘Shape Societal Transformations’. For instance, action recognition is a necessary component in recognition from wearable clothing, monitoring health and exercise regimes in the gym, recommendation systems via wearables, recognition of fake videos on social media, etc.

      This project focuses on ‘Analysing, Representing and Modelling data’, as video processing models require spatio-temporal modeling of time series, video frames, sequences, etc. My proposal aims at overcoming ‘Fundamental limits of data’, e.g. by learning in-the-wild and reinforcement learning to explore natural sources of information (e.g. predicting future evolution of video frames learns intrinsic manifold of video/motion data). I hope to bring my ideas to the social media, wearable devices, and recommender systems thus shaping ‘data-driven society’.

  - **A closer look at finegrained motions (Honours research project)**
    - Duration: *19/02/2024 - <span style="color: blue;">present</span>*
    - Supervisor: [Dr. Lei Wang](https://leiwangr.github.io/)
    - Objective: For this project, we aim to develop a model that can accurately identify the fine-grained motions performed in a video. 

## Completed Projects
  - **Synthesizing Artistic Realism: Stroke Painting Algorithms with Shader Enhancements**
    - Duration: *23/05/2024 - 30/05/2024*
    - Objective: Develop an enhanced method for synthesizing artistic realism through advanced stroke painting algorithms with shader enhancements. The goal was to transfer the stroke painting style from real-world photographs to digital images, improve the visual quality of these algorithms, and create a user-friendly interface for creating digital paintings with realistic brush strokes. The project also aimed to present vivid and lifelike representations of digital paintings in 3D.
    - Achievements:
      - Improved the visual quality of stroke painting algorithms from previous methods through cosine mapping, logistic function mapping, and shader enhancements.
      - Developed an efficient and user-friendly program for creating digital paintings with realistic brush strokes.
      - Achieved vivid and lifelike representations of digital paintings in 3D, bridging the gap between 2D and 3D painting rendering techniques.
    - Resources: [GitHub](https://github.com/HuilinChen943/paintercpp), [Technical Report ](/files/cg_report.pdf)
    
  - **Towards building general-purpose multimodal foundation models**
    - I am a Assistant Researcher in this project
    - Duration: *01/10/2023 - 31/12/2023*
    - Research Grant: **NCI Adaptater Scheme Q4 2023 (HPC funding scheme)**
    - Scope: Vision-language pre-training (VLP) has attracted rapidly growing attention in both computer vision and NLP communities due to the emergence of large-scale multimodal foundation models like Contrastive Language-Image Pre-training (CLIP). It is very encouraging to see that many Vision-Language (VL) systems have been deployed in industry. For example, iPhone can generate image captions read by VoiceOver for vision-impaired users. Although multimodal intelligence has been applied in many areas including image-text, core computer vision and video-text tasks, there are still many factors to be considered including robustness to new domains, fairness and responsible AI issues.
    - Aim: One common theme stands out is how to build a general-purpose multi-modal foundation model. We aim to build a foundation model that is stable and generalisable, and can be readily adopted to various downstream tasks, ranging from image-level vision tasks (e.g., image classification, retrieval, and captioning), region-level vision tasks (e.g., object detection and phrase grounding), to pixel-level vision tasks (e.g., segmentation and image generation). In order to build a general-purpose foundation model, we need a unified model architecture that can be readily scaled up; and when being pre-trained at scale, it can be readily adopted to various downstream computer vision and VL tasks.

  - **Motion meets Attention: Video Motion Prompts**
    - Duration: *20/11/2023 - 19/01/2024*
    - Supervisor: [Dr. Lei Wang](https://leiwangr.github.io/)
    - Objective: Enhance the extraction and utilization of motion features in video content for action recognition tasks by developing a novel 'motion prompt layer'. This layer employs a modified Sigmoid function with adjustable slope and shift parameters to create and modulate attention maps from frame differencing maps. This setup aims to overcome the limitations of traditional 'blind motion extraction' methods by ensuring that only relevant motion signals are highlighted and used as inputs to the model, thereby improving the accuracy and efficiency of action recognition systems.
    - Achievements:
      - Developed a novel video motion prompt layer that can be seamlessly integrated into existing video model architectures like SlowFast, X3D, and TimeSformer.
      - Introduced a temporal attention variation regularization to ensure smooth continuity of attention maps, enhancing the model's generalizability and interpretability.
      - Achieved state-of-the-art performance on various benchmarks, including the large-scale FineGym and MPII Cooking 2 datasets for fine-grained action recognition.
    - Resources: [Project Page](https://q1xiangchen.github.io/motion-prompts/)

  - **Vehicle Image Translation: Adapting Synthetic Styles to Real-World Scenarios**
    - Duration: *19/10/2023 - 30/10/2023*
    - Objective: This project focuses on the application of Generative Adversarial Networks (GANs), specifically CycleGAN, for the purpose of image-to-image translation. The goal is to stylistically adapt vehicle images from the synthetic Vehicle-X dataset to resemble those in the real-world VeRi dataset, enhancing the robustness and accuracy of vehicle recognition algorithms.
    - Achievements:
      - Successfully trained a CycleGAN model to transform the style of Vehicle-X images to align with VeRi dataset aesthetics.
      - Improved the domain adaptation for vehicle recognition tasks in varied lighting and environmental conditions.
    - Resources: [GitHub](https://github.com/q1xiangchen/CycleGAN_vehicle), [Technical Report ](/files/I2I_report.pdf)