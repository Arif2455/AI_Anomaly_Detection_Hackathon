# Content of your README
readme_text = """
# AI-Powered Anomaly Detection in Surveillance Videos

## 1. Proposed Solution
We propose an AI-powered anomaly detection system that identifies unusual behavior in surveillance videos using deep learning. The system automatically detects suspicious activities such as loitering, unusual movement, and abandoned objects, reducing reliance on manual monitoring.  

Our approach is unique because it combines **YOLOv5** for object/person detection with an **unsupervised anomaly detection model** to flag abnormal events in real time.

## 2. Technical Approach

**Technologies Used:** Python, OpenCV, YOLOv5, Isolation Forest, Matplotlib

**Process:**
1. Collect input video dataset (UCSD Anomaly Dataset / Avenue Dataset).  
2. Detect people & objects using YOLOv5.  
3. Extract movement patterns and feed into an anomaly detection model.  
4. Flag unusual activity with timestamps.  
5. Display results on a simple dashboard & visualization chart.

## 3. Feasibility and Viability

**Feasibility:**  
- Can be implemented quickly using public datasets, open-source models, and lightweight Python libraries.

**Risks:**  
- Real-time deployment may require GPU and optimized pipelines.

**Mitigation:**  
- For the hackathon, we simulate with pre-recorded videos.  
- System can be scaled to real CCTV feeds in the future.

## 4. Research and References

- UCSD Pedestrian Anomaly Dataset: [Link](http://www.svcl.ucsd.edu/projects/anomaly/dataset.htm)  
- Avenue Dataset: [Link](http://www.cse.cuhk.edu.hk/leojia/projects/detectabnormal/dataset.html)  
- YOLOv5 GitHub: [Link](https://github.com/ultralytics/yolov5)  
- Isolation Forest (Scikit-Learn): [Link](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.IsolationForest.html)

## 5. Usage Instructions
1. Open `main_notebook.ipynb` in Google Colab.  
2. Run all cells sequentially.  
3. Check the dashboard and visualization outputs for flagged anomalies.
"""

# Write the README.md file
with open("README.md", "w") as f:
    f.write(readme_text)

print("README.md created successfully!")
