# SmartTrack: Behavior-Aware Lost Object Detection System

This project is an AI-based surveillance system that detects and tracks people and personal belongings using YOLOv8 and ByteTrack. The system analyzes human-object interactions to classify object states and identify important events.

## Tools and Technologies

* Python
* Google Colab
* YOLOv8
* ByteTrack
* OpenCV
* Scikit-learn

## Datasets

- ABODA Dataset: https://github.com/kevinlin311tw/ABODA
- CAVIAR Dataset: http://homepages.inf.ed.ac.uk/rbf/CAVIARDATA1/

## Evaluation Metrics

* Precision
* Recall
* F1-score
* FPS

## Object States

* Safe
* Forgotten Object
* Suspicious Pickup

## How to Run

1. Open the notebook in Google Colab.
2. Upload the required video file.
3. Run all cells.
4. The system will perform detection, tracking, interaction analysis, and evaluation.

## Project Output

The system classifies each object into one of the following states:

* Safe
* Forgotten Object
* Suspicious Pickup
