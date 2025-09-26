DeepSORT with YOLOv5

This repository contains an implementation of **DeepSORT (Deep Simple Online and Realtime Tracking)** integrated with **YOLOv5** for object detection and multi-object tracking.  
It allows you to detect and track multiple objects (such as pedestrians, vehicles, etc.) in real-time from video streams or image sequences.

---

🚀 Features
- YOLOv5 for high-accuracy object detection  
- DeepSORT for robust multi-object tracking  
- Real-time tracking on videos and webcam streams  
- Configurable to track different object classes  
- Lightweight and modular codebase

---

📂 Project Structure

deepSort_with_yolov5/
│── models/ # YOLOv5 model files
│── deep_sort/ # DeepSORT tracker implementation
│── utils/ # Helper functions
│── runs/ # (Excluded) Example detection outputs
│── main.py # Entry point for running detection + tracking
│── requirements.txt # Python dependencies
│── README.md # Project documentation


---

🛠️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/deepSort_with_yolov5.git
   cd deepSort_with_yolov5

2. Install dependencies:
pip install -r requirements.txt

▶️ Usage

Run object detection + tracking on a video:
python main.py --source path/to/video.mp4

Run with a webcam:
python main.py --source 0

⚠️ Note

Example output videos (dash.mp4, walking.mp4) and img.gif were too large for GitHub and are excluded or uploaded to drive with the link attached in the results.

📊 Results

Watch the pedestrian tracking demo:

[Demo Video (Google Drive)](https://drive.google.com/file/d/1FtHm8imCToP3V8y5sYxTXwbc_9RGLBZ4/view?usp=sharing)

-Pretrained Weights
Download yolov5s.pt from[(Google Drive)](https://drive.google.com/file/d/184IIkQqF7nKPiHemgd-4i_0jj_Btmvxl/view?usp=sharing) and place it inside the `weights/` folder.

-Usage
Run detection and tracking on a video:

```bash
python detect_sort.py --source path/to/video.mp4 --weights yolov5s.pt

📜 License

This project is for educational and research purposes.
Check YOLOv5 License for model usage terms.

🙌 Acknowledgements

Ultralytics YOLOv5

nwojke/deep_sort




