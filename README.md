🍊 Orange Tree Tag Recognition with CNN and OCR
This project presents an automated system for detecting and cataloging ID tags on orange trees using deep learning and optical character recognition (OCR). The system was designed to solve a real-world agricultural challenge: identifying small, sometimes weathered ID tags in complex, natural environments.

🧠 Project Highlights
Model Architecture: Fine-tuned VGG16 CNN, pretrained on ImageNet, adapted for small object detection in outdoor images.

OCR Pipeline: Integrated OCR to extract alphanumeric tag IDs post-classification.

Real-World Constraints: Tackles variability in lighting, weathering, occlusions, and natural background clutter.

Scalability: Designed with deployment and batch-processing in mind, suitable for large-scale agricultural monitoring.

🔍 Problem Statement
In agricultural trials, each orange tree is tagged with a unique ID for tracking traits such as growth, disease resistance, and yield. Manually recording these tags is time-consuming and error-prone. This system automates that process using images captured in the field.

⚙️ Methodology
Data Collection: Field images of trees and ID tags (private dataset).

Preprocessing: Cropping, denoising, contrast enhancement.

CNN Training:

Architecture: VGG16

Fine-tuned on labeled dataset of tag images

OCR Integration: Used Tesseract OCR to extract text from detected tags.

Output: Each image is processed to return the recognized tag ID with confidence scores.
