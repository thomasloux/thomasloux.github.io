---
title: "Silo Detection in Satellite Images (Ecole polytechnique x QuantumBlack Hackathon)"
excerpt: "ResNet network to detect silos in satellite images, delivering a real-time, globally-operable prototype within 24 hours and using Grad-CAM for segmentation<br/><img src='/images/heatmap_silo.png' width='80%'>"
collection: projects
---
Work done in a team of 4 during the Ecole polytechnique x QuantumBlack Hackathon for which we earned the first prize. The hackathon presentation can be found [here](https://thomasloux.github.io/files/silo-detection.pdf).

We developed a ResNet network to detect silos in satellite images (93% of accuracy), delivering a real-time, globally-operable prototype within 24 hours and using Grad-CAM for segmentation. The original dataset is a classification problem, with 2 classes: with or without silos. The Grad-CAM technique allows to visualize the activation of the network on the image, and here serves as a segmentation tool to detect the silos. We managed to access real-time satellite images from the Sentinel-2 satellite via API, and the model was able to detect silos in real-time. A simple Streamlit interface was developed to visualize the results after entering the coordinates of the area of interest.

<img src='/images/heatmap_silo.png' width='80%'>