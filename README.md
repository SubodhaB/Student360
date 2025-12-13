# Student Behavior Detection – Dataset Engineering PoC

## Project Type
Machine Learning / Computer Vision (YOLOv8)

## Contributor
Member-1 – Dataset Engineering & Model Training

## Objective
This repository demonstrates the complete dataset engineering and model training pipeline
for detecting student behavior ("copying") from classroom/exam video footage.

## Scope of PoC
End-to-end workflow:
Raw video → Frame extraction → Annotation → YOLOv8 dataset → Training → Evaluation

## My Responsibilities
- Raw video collection (with consent)
- Frame extraction using Python
- Dataset preparation (train/valid/test split)
- Annotation using Roboflow (class: copying)
- YOLOv8 model training using Google Colab
- Model evaluation and export of trained weights

## Dataset Pipeline
1. Extract frames from video at fixed time intervals
2. Upload frames to Roboflow
3. Manually annotate copying behavior
4. Export dataset in YOLOv8 format
5. Train YOLOv8 model on Google Colab

## Model
- Architecture: YOLOv8
- Task: Object Detection
- Class: copying

## Evidence
- Roboflow annotation screenshots
- Training logs and evaluation metrics
- Sample prediction images

## Notes
This repository contains only sample data and scripts.
Full dataset is excluded due to size and privacy concerns.
