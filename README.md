# Medical Plant Detection App

This is a Streamlit application for detecting medical plants in an image using the YOLO model. Users can upload an image, and the application will detect specified medical plants.

## Features

- Upload an image in various formats (JPG, JPEG, PNG, BMP, WEBP).
- Detect medical plants in the uploaded image using a pre-trained YOLO model.
- Display the uploaded image and the image with detected medical plants side by side.
- Adjust the model's confidence threshold using a slider.
- View the detection results with bounding box coordinates.

## Requirements

- Python 3.6+
- Streamlit
- PIL (Pillow)
- ultralytics (YOLO)

## Installation

1. Clone the repository :
   ```sh
   git clone https://github.com/your-username/medical-plant-detection-app.git
   cd medical-plant-detection-app
2. Install the required packages :
   ```sh
   pip install -r requirements.txt
3. Ensure you have the YOLO model weight file (best.pt) and place it in the project directory.

## Usage

1. Run the Streamlit app:
  ```sh
 streamlit run app.py
  ```
2. Open your web browser and go to http://localhost:8501.
3. Use the sidebar to upload an image and select the desired model confidence.

4. Click the "Detect Objects" button to see the results.
