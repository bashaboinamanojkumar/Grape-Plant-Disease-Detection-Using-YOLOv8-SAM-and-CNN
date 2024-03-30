# Grape-Plant-Disease-Detection-Using-YOLOv8-SAM-and-CNN

The grape plant is of immense significance in agriculture and viticulture due to its economic value and widespread cultivation. However, grape plants are susceptible to various diseases that can significantly impact their health and productivity. Therefore, the accurate and timely detection of grape leaf diseases plays a crucial role in ensuring effective disease management, reducing crop losses, and maintaining the overall health of vineyards.

This project aims to develop an automated system for the detection and segmentation of grape leaf blight disease using deep learning techniques. First, a YOLOv8 object detection model is used to identify the presence and location of diseased areas on the grape leaves, producing bounding boxes around these regions. Then, a Segment Anything model (SAM) is utilized to segment the diseased areas based on the bounding box coordinates. Finally, a CNN model is trained on segmented images to accurately classify the grape leaf disease.

The system is evaluated on a dataset of grape leaf images, achieving a high accuracy in detecting and segmenting the diseased areas, and accurately classifying the type of the disease. This system has potential applications in improving the efficiency of grape disease management and reducing crop losses.
