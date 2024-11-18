# Defect Detection in 3D Printing
<b>Bachelor's Thesis Project</b>

Welcome to the official repository for Defect Detection in 3D Printing, a Bachelor's Thesis project focused on leveraging advanced object detection models (YOLOv5 and YOLOv11) to identify defects in 3D-printed objects. This project combines computer vision, machine learning, and domain-specific problem-solving to enhance the quality control process in additive manufacturing.

## Project Overview

Additive manufacturing, or 3D printing, has revolutionized how we create objects by enabling complex, highly customizable designs. However, the quality assurance of 3D-printed components remains a significant challenge due to defects that may occur during printing. This project addresses this challenge by implementing state-of-the-art object detection models to automate defect detection, thereby reducing the reliance on manual inspection.

Key Features:
1. <b>Automated Defect Detection:</b> Identify common defects such as layer shifts, stringing, and under-extrusion.
2. <b>YOLO-based Object Detection Models:</b> Evaluate and compare YOLOv5 and YOLOv11 for detecting anomalies in 3D prints.
3. <b>Custom Dataset:</b> Built a comprehensive dataset containing annotated defect images for model training and testing.
4. <b>Performance Optimization:</b> Focused on precision, recall, and inference time to ensure practical usability in real-time applications.

## Methodology
1. <b>Dataset Preparation:</b> Labeled the dataset with bounding boxes for precise defect localization & performed image augmentation to improve model generalization.
2. <b>Model Training:</b> Implemented YOLOv5 and YOLOv11 in Google Collab and optimized hyperparameters for better accuracy and inference speed.
3. <b>Evaluation:</b> Compared YOLOv5 and YOLOv11 based on precision, recall, F1-score, and mAP (Mean Average Precision).

## Future Work
1. Extend the dataset with more defect types and variations.
2. Explore other state-of-the-art object detection architectures like YOLOv11 and DETR.
3. Integrate the detection system into a 3D printing pipeline for real-time defect monitoring.

