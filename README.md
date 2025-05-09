🚗 Vehicle Detection using YOLOv5 in Google Colab
📝 Project Description
This project demonstrates vehicle detection in images using the YOLOv5 object detection model within a Google Colab environment. It loads a pre-trained YOLOv5 model (yolov5s) from the Ultralytics repository and performs inference on a user-specified image. It filters detections to only show vehicles (cars, trucks, buses, motorbikes) and draws bounding boxes around them with confidence scores.

📁 Project Structure
bash
Copy
Edit
CV_YOLO.ipynb           # Main Colab notebook for vehicle detection
vehicle_detection_result.jpg  # Output image with bounding boxes (generated during runtime)
⚙️ Installation (handled in Colab)
python
Copy
Edit
!pip install torch torchvision torchaudio
!pip install opencv-python
!pip install matplotlib
!pip install yolov5
All necessary packages are automatically installed via pip in the Colab notebook.

🚀 Features
Load a YOLOv5 model (yolov5s) pre-trained on the COCO dataset.

Detect objects in a custom image uploaded by the user.

Filter and display only vehicle-related classes:

car, truck, bus, motorbike

Annotate the image with bounding boxes and confidence scores.

Save and download the annotated result image.

🖼️ Usage Instructions
Upload your image to the Colab environment.

Update the image_path in the notebook with your image file.

Run all cells to:

Load the model

Detect vehicles

Display and save the annotated result

Download the final output

🔍 Example Output
The image displays all detected vehicles with green boxes and labels (e.g., car 0.85).

Output is saved as vehicle_detection_result.jpg.

🧠 Model Info
Model: YOLOv5s

Source: Ultralytics YOLOv5

Dataset: COCO (Common Objects in Context)

