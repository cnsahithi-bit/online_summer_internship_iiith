## TASK -1
We set up a Python virtual environment using venv and installed the Ultralytics package using the command pip install ultralytics. After activating the environment (venv\Scripts\activate), we trained a YOLOv8 object detection model using a pre-defined dataset with the command `yolo detect train model=yolov8n.pt data=coco128.yaml epochs=5 imgsz=320 batch=8`. This generated performance metrics such as precision, recall, and mAP, which were stored in the runs/detect/train/ folder. Next, we performed semantic segmentation using the command `yolo segment predict model=yolov8n-seg.pt source=datasets/coco128/images/va`l, which produced images with pixel-wise colored masks indicating different objects. These outputs demonstrate both object detection and segmentation capabilities of YOLO models.

![performance metrics](https://github.com/user-attachments/assets/66839e5b-ef86-48d2-9a62-bd78dce6d93c)

![confusion matrix](https://github.com/user-attachments/assets/85385422-0d16-4348-837e-19c4180315a5)

