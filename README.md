**Severstal Steel Defect Detection**

A multi-stage deep learning architecture to detect and categorize flaws on steel surfaces. The process was divided into three stages: binary classification, multilabel classification, and defect segmentation. Each stage was designed to filter and identify specific types of defects, ultimately leading to the generation of segmentation masks for the detected defects. Below is a detailed account of the outcomes at each stage.

Binary Classification: Defect Presence Detection
The first stage involved a binary classification model designed to detect whether any defect was present on the steel surface. 

Multilabel Classification: Defect Type Identification
In the second stage, a multilabel classification model identified the specific types of defects among those flagged by the binary model. 

Defect Segmentation: Generating Masks
For images predicted to have defects, the third stage generated segmentation masks using separate models for each defect type. Four separate segmentation models were employed, each trained to detect and segment a specific type of defect. For images predicted to have defects, the third stage generated segmentation masks using separate models for each defect type.

Methodology of the overall Design:

![image](https://github.com/user-attachments/assets/6b247741-0510-4ece-83da-da756521bc8e)
