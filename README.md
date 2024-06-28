# Automatic Attendance System using Face Recognition

1. **Modules**: Required modules include Tkinter, PIL, mysql.connector, and OpenCV.
2. **Pages**: Includes login (`login.py`), register (`register.py`), and main attendance system (`main.py`).
3. **Database**: Connects MySQL with `student.py` to store student details.
4. **Images**: Uses images from the "Images" folder for interface design.
5. **Face Detection**: Implements face detection using `haarcascade_frontalface_default.xml` to capture and store student photos in the "data" folder.
6. **Training**: Trains datasets using `train.py` and saves them in `classifier.xml` using the Cascade Classifier.
7. **Face Recognition**: Utilizes LBPH algorithm in `face_recognition.py` to recognize enrolled students, update attendance in `suchir.csv`, and display student information during VideoCapture.
8. **Attendance Management**: Manages attendance using `attendance.py`, importing from `suchir.csv` and exporting to `attendance.csv`.
9. **Additional Features**: Includes help desk (`help.py`) and developer information (`developer.py`) accessible from the main attendance system page.
10. **Exit**: Closes the main attendance system page upon clicking the Exit button.


## **NOte**
- Transferred files from master to main on 28-06-2024
