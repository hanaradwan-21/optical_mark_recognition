Automatic OMR Grader with Multi-Selection Detection 📝✅:


This is an advanced Optical Mark Recognition (OMR) system built using Python and OpenCV. It features a modern GUI for ease of use and intelligently detects multiple selections (invalid cases), providing detailed exports to Excel.




🚀 Key Features
User-Friendly GUI: Built with Tkinter for easy image selection and real-time result viewing.

Intelligent Detection:

✅ Correct Answer: Marked in Green.

❌ Wrong Answer: Marked in Red with the correct one highlighted.

⚠️ Multi-Selection: Detects if a student shaded more than one circle (marked in Yellow).

⚪ Empty Answers: Detects unshaded questions.




Perspective Correction: Automatically detects and flattens the answer sheet even if it's tilted.



Data Export: Automatically generates an Excel file (Final_Result_Project.xlsx) with the student's score and question-by-question analysis.



🛠️ Built With
Python: The core programming language.

OpenCV: For image processing and contour detection.

NumPy: For high-speed pixel calculations.

Pandas: For data management and Excel generation.

Tkinter & Pillow: For the graphical user interface.



📂 Project Structure
main.py: The primary script containing the GUI and grading logic.

utlis.py: Helper functions for image manipulation (Perspective transform, splitting boxes).

Final_Result_Project.xlsx: (Auto-generated) The final grading report.





⚙️ How to Run
Install dependencies:

Bash
pip install opencv-python numpy pandas pillow openpyxl
Run the application:

Bash
python main.py
Click Browse to select an image, then click Grade.

💡 Customization
You can easily adjust the settings in main.py:

questions: Number of questions.

choices: Number of options per question.

ans: List of correct answer indices (starting from 0).
