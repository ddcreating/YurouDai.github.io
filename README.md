# Yurou (Ronia) Dai | 代雨柔

Ph.D. Student in Computer Science, Lehigh University  
Medical AI · Neuroimaging · Deep Learning

[Homepage](https://ddcreating.github.io/YurouDai.github.io/) · [Google Scholar](https://scholar.google.com/citations?user=PdnyfV0AAAAJ&hl=en) · [GitHub](https://github.com/ddcreating) · [Email](mailto:yrd224@lehigh.edu)

## About

I am a Ph.D. student in Computer Science at Lehigh University, advised by Prof. Lifang He. My research focuses on medical AI for neuroimaging, with an emphasis on learning-based fMRI preprocessing and brain representation learning. I study how image processing and representation choices affect downstream predictive modeling.

My current work uses functional and structural MRI from datasets including ADHD-200, ABIDE, and the Human Connectome Project (HCP). Before joining Lehigh, I worked as a Research Assistant at City University of Hong Kong on autonomous driving systems. My earlier research explored self-supervised learning for human mobility and trajectory analysis.

I am interested in industry research and applied machine learning internships, particularly in medical imaging, AI for healthcare, and computer vision. I enjoy translating research ideas into practical, reproducible software.

Outside research, I enjoy photography, walking, hiking, and spending time in nature.

## Research

- **Learning-based neuroimaging pipelines.** Integrating brain extraction, motion correction, registration, and downstream analysis into trainable workflows for fMRI.

- **Brain representation learning.** Studying convolutional and graph neural networks for MRI analysis, including representations derived from regional time series and functional connectivity.

- **Evaluation of medical AI.** Examining how preprocessing, anatomical alignment, and brain parcellation affect predictive performance and computational efficiency.

## Projects

The first three entries describe related components of my ongoing doctoral research.

### Learning-Based fMRI Preprocessing and Analysis

Ongoing research, Lehigh University

- Developing a framework that connects learnable preprocessing modules with downstream fMRI classification, using structural MRI for anatomical reference where appropriate.
- Building training and data-processing workflows for 4D fMRI and comparing conventional and learning-based preprocessing approaches, including fMRIPrep, BrainSuite, and DeepPrep.
- Investigating brain extraction, motion correction, and EPI-to-T1 and T1-to-template registration, with attention to both image quality and downstream utility.

### Neuroimaging Classification on ADHD-200 and ABIDE

Ongoing research, Lehigh University

- Developing and evaluating CNN-based classification workflows and exploring functional-connectivity representations for graph-based analysis.
- Preparing neuroimaging data, inspecting preprocessing quality, and studying the effects of atlas-based parcellation and spatial normalization on model inputs.
- Using subject-level cross-validation to assess classification performance while keeping each participant within a single split.

### Brain Graph Learning with HCP fMRI

Ongoing research, Lehigh University

- Constructing brain graphs from regional fMRI time series and functional connectivity.
- Evaluating graph neural network baselines, including Chebyshev graph convolutions and graph attention, for subject-level prediction using resting-state fMRI.

### Self-Supervised Human Mobility Learning

June 2020 – June 2022, UESTC

- Developed and evaluated self-supervised approaches to next-location prediction and trajectory classification.
- Explored spatiotemporal data augmentation and contrastive learning to capture patterns in human mobility.

## Selected Publications

1. Liao, Y., Keung, J., Zhang, J., **Dai, Y.**, & Liu, S. (2025). Evaluate Inference Attacks: Attack and Defense against 2D Semantic Segmentation Models. *ACM Transactions on Autonomous and Adaptive Systems*.
2. Liao, Y., Zhang, J., Keung, J., Xiao, Y., & **Dai, Y.** (2025). Advancing autonomous driving system testing: Demands, challenges, and future directions. *Information and Software Technology*, 107859.
3. Cao, C., Zhou, F., **Dai, Y.**, Wang, J., & Zhang, K. A Survey of Mix-based Data Augmentation: Taxonomy, Methods, Applications, and Explainability. *ACM Computing Surveys*, 57(2), Article 37, 1–38. Published online in 2024; issue dated February 2025. [DOI](https://doi.org/10.1145/3696206).
4. Liu, L., **Dai, Y.**, Cao, Y., & Zhou, F. (2024). Survey of User Geographic Location Prediction Based on Online Social Network. *Journal of Computer Research and Development*, 61(2), 385–412.
5. Zhou, F., **Dai, Y.**, Gao, Q., Wang, P., & Zhong, T. (2021). Self-supervised human mobility learning for next-location prediction and trajectory classification. *Knowledge-Based Systems*, 228, 107214.
6. **Dai, Y.**, Yang, Q., Zhang, F., & Zhou, F. (2021). Trajectory prediction model of social network users based on self-supervised learning. *Journal of Computer Applications*, 41(9), 2545.

[Full publication list on Google Scholar](https://scholar.google.com/citations?user=PdnyfV0AAAAJ&hl=en).

## Education

### Lehigh University

Ph.D. in Computer Science, August 2024 – Present

Department of Computer Science and Engineering. Advisor: Prof. Lifang He.

### University of Electronic Science and Technology of China

Master of Software Engineering, September 2019 – June 2022

School of Information and Software Engineering. Advisor: Prof. Fan Zhou.

### Chongqing Normal University

Bachelor of Software Engineering, September 2015 – June 2019

School of Computer and Information Science.

## Experience

### Doctoral Research, Lehigh University

November 2024 – Present

- Conducting research on end-to-end fMRI preprocessing and analysis under the supervision of Prof. Lifang He.
- Developing model and data-processing components, running comparative experiments, and implementing distributed training workflows for neuroimaging research.

### Research Assistant, City University of Hong Kong

August 2022 – February 2024

- Contributed to localization and mapping in an autonomous driving system built on Autoware.universe and ROS, using LiDAR data and NDT/SLAM methods.
- Processed point-cloud maps and generated Lanelet2 semantic maps using Vector Map Builder.
- Developed a real-time surround-view system with four fisheye cameras using PyQt and OpenCV.

### Teaching Assistant, University of Electronic Science and Technology of China

Spring 2020

- Supported the course Theory and Technology of Network Security.

## Selected Honors

- Provincial Outstanding Graduate, Education Department of Sichuan, 2022.
- National Scholarship, Ministry of Education of China, 2021.
- Excellent Teaching Assistant, UESTC, 2020.

## Contact

Email: [yrd224@lehigh.edu](mailto:yrd224@lehigh.edu)  
Location: Bethlehem, Pennsylvania, USA

## Website

This repository contains my personal academic homepage. The site uses the existing jemdoc stylesheet and a single `index.html` page.
