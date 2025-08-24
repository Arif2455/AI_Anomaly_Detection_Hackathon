# This line is just for you in Colab, it will NOT appear in README
readme_text = """
# AI-Powered Anomaly Detection in Surveillance Videos

## 1. Proposed Solution
Our project detects unusual behavior in surveillance videos using AI. It can automatically spot suspicious activities like loitering, unusual movement, or abandoned objects.

## 2. How We Did It
Python, OpenCV, YOLOv5, Isolation Forest, Matplotlib

Steps:
1. Collected video datasets.
2. Detected people & objects with YOLOv5.
3. Analyzed movement patterns with anomaly detection.
4. Flagged unusual activity.
5. Displayed results on dashboard.

## 3. Feasibility
Tested on pre-recorded videos, scalable to live CCTV feeds.

## 4. References
- UCSD Pedestrian Dataset
- Avenue Dataset
- YOLOv5 GitHub
- Isolation Forest (Scikit-Learn)

## 5. How to Run
1. Open main_notebook.ipynb in Colab.
2. Run all cells.
3. Check the dashboard and charts.
"""

# Write README.md (the file itself will not contain Python comments)
with open("README.md", "w") as f:
    f.write(readme_text)
