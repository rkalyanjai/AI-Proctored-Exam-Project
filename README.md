# AI-Proctored-Exam-Project
# Module 1:- student_audio_recognition:-
## Packages used:-
   Speech Recognition:-pip install SpeechRecognition
## Ide used:-
   Jupyter Notebook
## Description:-
By using this module, we first checked if any audio is coming from student background. if so, we convert that background audio to text file and then matched that text file with the Question paper. If some frequent words matched with the question paper, then it will show "Malpractice" otherwise if only general noise is coming then, it will show a warning to the student. 
Here, we converted the audio file to text file using google speech recognition and then compared the text to the question paper using python.

# Module 2:- face_detector_in_image:-
## Packages used:-
   Opencv:- pip install opencv-python  
   Haar cascades: - It is an Object Detection Algorithm used to identify faces in an image or a real time video.
## Ide used:-
   Jupyter Notebook
## Description:-
First we converted the input image(jpeg/jpg) into grayscale using opencv. Then, we detected the faces using Haar Cascade XML file(where the cascade funtion is trained with a lot of images and based on that training, it is able to detect the number of faces in an image). Then, we put rectangular boxes around the faces using opencv and we just printed the output image on the screen. We also calculated number of faces using python.
