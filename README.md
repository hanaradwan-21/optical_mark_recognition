#  Automatic OMR Grader with Multi-Selection Detection

An advanced Optical Mark Recognition (OMR) system built using **OpenCV** and **Python**. This project doesn't just grade MCQ papers; it intelligently detects multiple selections (cheating/invalid cases) and exports detailed results to **Excel** for professional data tracking.

##  Key Features

*   **Perspective Transformation:** Automatically detects and flattens the MCQ sheet even if the photo is taken at an angle.
*   **Multi-Selection Detection:** Flags questions where more than one bubble is shaded as "Invalid".
*   **Intelligent Feedback:** Highlights correct answers in green, wrong in red, and provides a "Correct Answer" hint for mistakes.
*   **Automated Reporting:** Generates a `Final_Result_Project.xlsx` file containing per-question status and final score.[cite: 1]

##  Built With

*   **Python 3.11+**
*   **OpenCV:** For image processing and contour detection.[cite: 1]
*   **NumPy:** For matrix operations and pixel value analysis.[cite: 1]
*   **Pandas:** For structured data management and Excel export.[cite: 1]
*   **Openpyxl:** Engine for writing Excel files.[cite: 1]

##  Demo Results

| Input Image Processing | Final Graded Output |
| :---: | :---: |
| ![Canny & Thresholding](https://via.placeholder.com/350x350?text=Image+Processing) | ![Final Result](https://via.placeholder.com/350x350?text=Graded+OMR) |
*(Note: Replace these placeholders with your actual project screenshots like the one in image_d72716.jpg!)*

## 📂 Project Structure

*   `OMR_Main.py`: The core engine for image processing and grading logic.[cite: 1]
*   `utlis.py`: Helper functions for reordering points, splitting boxes, and drawing results.[cite: 1]
*   `Final_Result_Project.xlsx`: Auto-generated grading report.[cite: 1]

## ⚙️ How to Run

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YourUsername/OMR-OpenCV-Project.git](https://github.com/YourUsername/OMR-OpenCV-Project.git)
    ```
2.  **Install dependencies:**
    ```bash
    pip install opencv-python numpy pandas openpyxl
