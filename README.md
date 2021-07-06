# Face-Unlock-using-python

In this project, You can train model to detect your face, and show unlock - if face recognised OR Locked vice-versa.
It'll take feed from your mobile camera using IP webcam application and will send it to their server, from their feed will be taken by python script and model will be trained.

# Steps to execute to train model :-
1. Open GetFaces.py and set the directory where all .jpg files of your faces will be stored.
2. Download IP Webcam(android applicaion) in your mobiles, head over to for full tutorial : https://www.instagram.com/p/CEM4eRTABoM/?utm_source=ig_web_copy_link
3. Start server in IP webcam, and enter server address in "URL"(line 25) in GetFaces.py
4. Now run GetFaces.py. It'll take 100 images of your face and store it in your specified directory. 
5. Open TrainModel.py, specify your directory details, and URL. 
6. Run TrainModel.py. 

Now, Your model has been trained to look out for your face in the feed coming from URL. 
