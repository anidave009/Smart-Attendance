Steps To Run Project->
1.git clone <repo-link>
cd <project-folder>
pip install -r requirements.txt

2.Create a TrainingImage folder inside the project directory.(remove the original one and create new empty folder in which images will be stored automatically once you train the images ).

3.Update file paths in attendance.py and automaticAttendance.py to match your system.

4. Run the project:
   
Project Workflow
Register Your Face: Enter your ID & Name → Click Take Image → The system captures up to 50 images for training.
Train the Model: Click Train Image → Converts images into a numerical format for recognition.
Mark Attendance: Click Automatic Attendance, enter the subject name, and the system will recognize faces and record attendance.
View Attendance: Click View Attendance to see records in a tabular format.
