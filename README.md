# Attendance_System
This is an attendance system which utilizes facial recognition to take attendance.

Taking attendance is a necessary but really tedious task especially in big organisations. Many times people lose attendance due to manual errors. To prevent all this, an attendance system which uses facial recognition to mark attendance has been introduced in this project. 

This project makes a CSV file of registered student's information after user registration. For marking attendance, this program utilises the training images dataset which was created during user registration to identify the registered users and mark their ID number, name, time and date of presence in a CSV file. A new CSV file is created each day for marking attendance.

This program is easy to use. For a new user registration, the user has to enter his/her Institute allotted ID number and name of the user. Then the user has to click on take images which will open the webcam of the user's device. This will take several images of the user to train the image dataset. Then select sve profile and registration will be completed. Now for taking attendance, select take attendance and after successful user verification from the image datasets, the ID, name and time of attendance for the user will appear in the Attendance Chart as well as a CSV file will be updates with the same details.

REQUIRED PYTHON LIBRARIES
OpenCV
Numpy
Pandas
Os
Tkinter

ADDITIONAL REQUIREMENT: For this program to run, 'haarcascade_frontalface_default.xml' is required along with the python file of the program which contains the haar cascade features of a face.

![image](https://user-images.githubusercontent.com/82457446/170761513-8ddfecc2-0be9-4444-b736-a79a99d5d781.png)



