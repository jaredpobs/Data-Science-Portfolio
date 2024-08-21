## [Project 1: Factors Affecting Student Grades](https://github.com/jaredpobs/Data-Science-Portfolio/blob/main/Python%20notebooks/Student_Grades.ipynb)
- This project is about finding factors affecting Student Grades from our dataset. In our dataset, we only used these factors: health, study time, and absences to predict the grades. Grades are represented in three columns in the dataset: G1, G2, and G3.
- We found that health and absences have a very low and negligible negative correlation with students' grades. Study time has a slight positive correlation with the grades of the student.
- A new column called "Average" was created by averaging columns G1, G2, and G3, which are students' grades for each quarter.
- A Linear Regression model was created to predict the average of G2 and G3 as independent variables. The dependent variables used are health, study time, absences, and G1. The model had an accuracy of 83.3%
- Discovered that health, study time, and absences had minimal impact on student performance, contrary to initial expectations.

## [Project 2: Detecting People Using Their Phones While Walking](https://github.com/jaredpobs/Data-Science-Portfolio/blob/main/Python%20notebooks/Preoccupied_detection_YOLOv9.ipynb)
- Developed a computer vision system to detect pedestrians and pedestrians using their phones while walking, leveraging the YOLOv9 object detection algorithm within Google Colab.
- Utilized Roboflow for streamlined dataset management and employed pre-trained weights to speed up model development.
- Trained and fine-tuned a YOLOv9 model on a custom dataset, achieving a mean Average Precision (mAP) of 92.9%.
- Visualized detection results by overlaying bounding boxes on images, showcasing the model's capability to locate and classify individuals using their phones while walking precisely.
