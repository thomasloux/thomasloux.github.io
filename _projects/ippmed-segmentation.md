---
title: "Segmentation of lung cancer cells in 3D CT Scans"
excerpt: "Implemented a 3D U-Net model using Monai framework to segment lung cancer<br/><img src='/images/video19.gif' width='80%'>"
collection: projects
---

Work done in a team of 2 during the Institut Polytechnique de Paris Medical Data (IPPMeD) hackathon at the Paris Saclay Cancer Cluster (PSCC). A presentation of the project can be found [here](https://thomasloux.github.io/files/defense-3d-segmentation-lung.pdf) and a full report [here](https://thomasloux.github.io/files/report-3d-segmentation-lung.pdf). The code is available on this [repo](https://github.com/thomasloux/hackathon-pscc).

We build a 3D U-Net model using Monai framework to segment lung cancer as a classification task. We use some preprocessing (cropping) and postprocessing (smoothing) techniques to improve the model performance. A sliding window approach is used to limit the size of the model and increase the accuracy.

<img src='/images/sliding_window.png' width='50%'>

We obtain a F1 score (Dice Metric) of 0.5 on our test set and 0.37 on the hackathon test set. We achieve the 2nd best score on the hackathon.

<img src='/images/final-loss-segmentation.png' width='50%'>
Image extracted from Monai [documentation](https://docs.monai.io/en/stable/modules.html)