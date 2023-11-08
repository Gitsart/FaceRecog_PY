# FaceRecog_PY
Face training and recoginition model using openCV
1.Download the source code and extract it . 
2.Move to the extracted directory.
3.Create a folder called "datasets".
4.Inside that create a subdirectory called "username" (with the name   of the person face to get trained and recognized), Skip this step if the folder is already created. 
5.Run the program "gui.py"
6.Camera gets on and it starts to capture the frame. Try to stay in front,facing the camera so that it will capture your face.
7.Type the username mentioned inside the dataset folder.And click train button so that the camera starts to capture.
8.Try to give different expressions so that it takes all the values of your face and gives you the accurate recognition. Wait till it captures 100 faces. 
9.Once the training of face is completed it will automatically creates a XML(extended Markup Language) file of the captured frames.
9.Once it is done press "q" inside the camera window terminal so that it closes, and you can press "Recognize".
10.It tries to load the xml file and if it is matched it will recognize the face with name and confidence value else it will recognize as unknown.
11.In this we have the haarcascade_frontalface_default.xml, haarcascade_frontalface_alt.xml,haarcascade_frontalface_alt2.xml,
haarcascade_profileface.xml file, which assists in detecting and training the human faces
