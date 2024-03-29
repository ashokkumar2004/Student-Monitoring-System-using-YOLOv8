# Student Monitoring System using YOLOv8

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

## Overview

The **Student Monitoring System** is a project designed to monitor student engagement during class hours using YOLOv8, a state-of-the-art object detection algorithm. The system processes video footage captured in classrooms, converts it into frames, and utilizes Roboflow for annotation. Two classes, "High Attention" and "Low Attention," are annotated using bounding boxes generated by Roboflow. This system aims to provide insights into student interactions during class, distinguishing between engaging and less engaging sessions.

## Project Features

- **YOLOv8 Object Detection Algorithm:** Employs YOLOv8 for accurate and efficient detection of objects in video frames.

- **Roboflow Annotation:** Utilizes Roboflow to annotate frames with bounding boxes, indicating the presence of students and their attention levels.

- **Two Attention Classes:** Classifies students into "High Attention" and "Low Attention" categories based on their interactions in the classroom.

- **Class Session Analysis:** Provides insights into the dynamics of class sessions, distinguishing between interactive and less interactive periods.

## Project Structure

- **`/data`:** Contains video data and annotated frames.
- **`/model`:** Stores the YOLOv8 model and associated files.
- **`/scripts`:** Scripts for data preprocessing, model training, and analysis.
- **`/results`:** Output files, reports, and analysis results.


