# NOte:
- Should refer to main branch or [here](https://github.com/Su-ok/Automatic-Attendance-System) for better understanding of the project

# Automatic Attendance System using Face Recognition

1. Installation of the required module: Tkinter, PIL, mysql.connector, OpenCV.
2. Creation of login page(login.py), register page(register.py) and Main Attendance System page(main.py).
3. Creation of Student Details Page(student.py), making connection of MySQL database with the python file and storing details of all the enrolled students.
4. All the images for creating the pages are taken from the “Images” folder.
5. Inside the student.py file, we will be taking photos samples using Face detection(with the help of an XML file, “haarcascade_frontalface_default.xml”), generating data sets, storing it into a separate file(or folder), “data”, and redirecting the stored photo samples into the Photos tab from the main page.
6. Training the stored datasets in Train Data Set page(train.py), using the Cascade Classifier and saving the trained datasets in an XML file, “classifier.xml”.
7. In our project, Face Recognition is done by using the Local Binary Pattern Histograms, i.e. LBPH algorithm, making use of the predict variable, to predict the trained images/datasets, and confidence variable, to measure the distance(or similarity) of the image captured with the closest histogram/stored images.
   In this way, we will be performing Face Recognition in Face Recognition page(face_recognition.py), by making use of the trained datasets(from classifier.xml) in order to recognize the enrolled student, displaying some information about the student during VideoCapture, and automatically updating their presence in a csv file, “suchir.csv”.
8. In the Attendance System page(attendance.py), we will be using the csv file, “suchir.csv”, to import the attendance and export it into the main csv attendance file, “attendance.csv”, to finally mark the attendance of the student for the particular day.
9. Additional information has been put in two buttons, help desk(help.py) and developer(developer.py) which can be accessed from the Main Attendance System page.
10. Lastly, by clicking on the Exit button, the Main Attendance System page will be closed.
