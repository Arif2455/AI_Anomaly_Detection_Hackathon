# AI-Powered Anomaly Detection in Surveillance Videos

## 1. Proposed Solution
Our project detects unusual behavior in surveillance videos using AI. It can automatically spot suspicious activities like loitering, unusual movement, or abandoned objects.

We use YOLOv5 to detect people and objects, and an unsupervised anomaly detection model to flag anything abnormal in real time.

## 2. How We Did It
**Technologies Used:** Python, OpenCV, YOLOv5, Isolation Forest, Matplotlib  

**Steps:**
1. Collected video datasets (UCSD Pedestrian / Avenue).  
2. Detected people & objects using YOLOv5.  
3. Analyzed movement patterns with an anomaly detection model.  
4. Flagged unusual activity with timestamps.  
5. Displayed results on a simple dashboard with charts.

## 3. Feasibility
- Can be done quickly using public datasets and Python libraries.  
- Real-time deployment may need a GPU.  
- For the hackathon, we tested with pre-recorded videos. Scalable to live CCTV feeds.

## 4. References
- [UCSD Pedestrian Anomaly Dataset](http://www.svcl.ucsd.edu/projects/anomaly/dataset.htm)  
- [Avenue Dataset](http://www.cse.cuhk.edu.hk/leojia/projects/detectabnormal/dataset.html)  
- [YOLOv5 GitHub](https://github.com/ultralytics/yolov5)  
- [Isolation Forest (Scikit-Learn)](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.IsolationForest.html)

## 5. How to Run
1. Open `main_notebook.ipynb` in Google Colab.  
2. Run all cells sequentially.  
3. Check the dashboard and charts to see flagged anomalies.
