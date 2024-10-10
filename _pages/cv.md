---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Experience
======
- **Research Intern, Shakhnovich Lab, Harvard University**, April 2024 - August 2024
    - Run well-tempered 100ns metadynamics for protein complex binding free energy prediction, using GROMACS and PLUMED on a Slurm HPC environment
    - Evaluate energy minimization MD methods to predict binding free energy using ESM3 as encoder for SVM regressor: "Does Structural Information Improve ESM3 for Protein Binding Affinity Prediction?" Accepted at Machine Learning in Structural Biology Workshop at NeurIPS. I demonstrated a unexpected loss of around 0.2 Spearman Correlation using relaxed structures compared to wildtype structure.

- **AI Software Engineer Intern, Pretto**, June 2023 - August 2023
    - Managed deployment and access control on platforms such as GCP, Azure AI, and Heroku.
    - Focused on optimizing user adoption and ease of use across multiple features, including:
        - Automated Document Generation: Created automatic summary reports from client files using GPT.
        - Call Transcription and Summarization: Leveraged Whisper and GPT to transcribe and summarize phone calls.
        - Bank Statement Analysis: Analyzed bank statements using Python libraries (pandas) and text extraction from PDFs.
        - Internal Knowledge Search Engine: Researched and implemented Retrieval-Augmented Generation (RAG) techniques to enable a search engine that retrieves and generates answers from company knowledge, using diverse content sources. Implemented with LangChain and Pinecone.
        - Interactive Slackbot Development: Built an interactive Slackbot to improve internal workflows.

Projects
======
- **RNA Clustering with Graph Neural Networks**, Bioinformatics Project, 2024
Work done with Yann Ponty, Sebastian Will and Johannes Lutzeyer. I use a GNN encoder (Residual Gated Graph Convolutional Network) to cluster RNA secondary structures. The model achieves a RSME of 3 on the distance prediction, which correponds to a actual error of 3 base pairs on a total of 50, considered as an acceptable error for clustering.

- **Fake News Detection**, Deep Learning Project, 2023
Work done with Ekimetrics.
In a team of 4, we train a Ensemble Model using Machine Learning algorithms (Linear Regression, XGBoost...), LSTM model with Word2Vec and BERT model to detect fake news on the dataset 'LIAR'. Bert achievs a 70% accuracy on the test set.

- **Segmentation of lung cancer cells in 3D CT Scans**, Institut Polytechnique de Paris Medical Data (IPPMeD), 2023
Work done in a team of 2. We build a 3D U-Net model using Monai framework to segment lung cancer. We obtain a F1 score (Dice Metric) of 0.5 on our test set and 0.37 on the hackathon test set. We achieve the 2nd best score on the hackathon.

- **Reinforcement Learning for the CartPole problem**, 2023
I implement a Q-Table and a Deep Q-Network (DQN) to solve the CartPole problem. The Q-Table achieves a score of 250 on average, while the DQN achieves a score of 100 at most, facing convergence issues.

- **Silo Detection in Satellite Images**, Ecole polytechnique x QuantumBlack Hackathon, 2022
Work done in a team of 4. We developed a ResNet network to detect silos in satellite images (93\% of accuracy), delivering a real-time, globally-operable prototype within 24 hours and using Grad-CAM for segmentation. We won the hackathon by achieving the best score on the test set.


Education
======
- **Applied mathematics, Ecole polytechnique**, 2021-2025
    - Honors: Outstanding Investment and Outstanding Leadership awards (given to around 10% of the most active students).

    Courses mainly in applied maths and computer science
    - Foundations of Machine Learning
    - Stochastic Models in Finance
    - Operational Research: Mathematical Aspects and B Applications
    - Image Analysis and Computer Vision
    - Advanced Deep Learning
    - Random and statistical modeling of processes
    - Random Models in the Environment and Evolution

    Additional coursework in the health/biology domain:
    - Drug Sciences
    - Computational analysis of high-throughtput sequencing data
    - Bioinformatics Project in clustering of RNA secondary structures using GNN encoders

- **Deep Learning, MVA (Mathematiques, Vision, Apprentissage), ENS Paris-Saclay**, 2024-2025
    Courses in Machinea Learning: 
    - Reinforcement Learning
    - Topological Data Analysis
    - Time Series analysis
    - Computational Statistics
    - Convex Optimization

Skills
======
- **Programming Languages**: Python, C++, OCaml, Java, SQL
- **Programming Frameworks**: PyTorch, Scikit-Learn, Monai, HuggingFace, spaCy, LangChain, Pandas, Numpy
- **Technologies**: Deep Learning, Computer Vision, Natural Language Processing, Git, GCP, Slurm

Extra-Curricular Activities
======
- Student Union representative in charge around 150 clubs, managing event planning, legal matters, and accounting, while being responsible for an annual budget of 2 million euros
- As the Artificial Intelligence Treasurer, I played a key role in organizing the annual hackathon in collaboration with QuantumBlack at Ecole polytechnique on detection of methane detection