# 🕳️ Potholes Detection using YOLOv8

This project uses the **YOLOv8 Nano** model to detect and locate potholes in road images. It’s designed to help automate the identification of road defects for smart city and transportation infrastructure applications.

---

##  Dataset

- **Source:** [Roboflow Universe – Kuwait Potholes](https://universe.roboflow.com/ai-training-session/kuwait-potholes/dataset/1)
- **Total Images:** 688
- **Annotations:** Provided in YOLO format (TXT)
- **Classes:** 1 (`pothole`)

---

##  Model

- **Model Used:** `yolov8n.pt` (YOLOv8 Nano)
- **Framework:** [Ultralytics YOLOv8](https://docs.ultralytics.com/)
- **Training Resolution:** 640x640
- **Epochs:** 20
- **Inference Mode:** Single image, batch, or folder predictions

---

##  Project Structure
a.Potholes_obj_detection.ipynb -: Contains the code regarding object detection

b.data.yaml -: Dataset configuration for YOLOv8

c.README.md 

##  How to Run the Project (Google Colab)

1. Clone or upload the project to Google Colab.
2. Mount Google Drive and unzip your dataset if needed.
3. Make sure to install Ultralytics:

   ```python
   !pip install ultralytics

## Author
Siddharth Mishra
GitHub: @Siddharth330-max
