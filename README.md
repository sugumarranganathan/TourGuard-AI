https://colab.research.google.com/drive/1jjLoX5L-KbnCCpYgWKDtCGTKEXfq8kLJ#scrollTo=xzVxA-rvKf6E

==========

# TourGuard AI

AI-Based Tourist Verification System using YOLO11 and Gradio.

## Project Workflow

Tour Start Photo
→ YOLO11 Person Detection
→ Expected Tourist Count
→ Current Group Photo
→ YOLO11 Person Detection
→ Current Tourist Count
→ Compare Counts
→ Missing / Extra Tourist Detection
→ Alert Generation

---

## Start Group Detection Output

![Start Detection](outputs/start_detection.png)

---

## Current Group Detection Output

![Current Detection](outputs/current_detection.png)

---

## Features

- Tourist Counting
- Missing Tourist Detection
- Extra Person Detection
- YOLO11 Object Detection
- Gradio User Interface

---

## Installation

```bash
pip install -r requirements.txt
```

## Run

```bash
python tourguard_ai.py
```

## Sample Result

```text
Expected Tourists : 51

Current Tourists : 56

Missing Tourists : 0

Extra Persons : 5

Status : ALERT - Extra Persons Detected : 5
```

==================

# TourGuard AI

AI-Based Tourist Verification System

Features:
- Tourist Counting
- Missing Tourist Detection
- Extra Person Detection
- YOLO11 Object Detection
- Gradio Interface

Run:

pip install -r requirements.txt

python tourguard_ai.py
