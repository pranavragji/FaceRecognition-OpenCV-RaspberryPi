# FaceRecognition-OpenCV-RaspberryPi

For this project you require

1.Raspberry Pi

2.Pi Cam

3.Python 3

4.OpenCV

We have to first detect the face, gather the data of the faces, train and recognize the faces.

I am using the Rasbian OS for the Raspberry Pi3B+. The NOOBS OS can be used for this project as well.

Steps:

-Enable Camera from the interface options in the terminal (raspi-config)

-Install OpenCV3 (This may take 5-6 hours)

-After Installing OpenCV Test Your Camera by using the simpleCamTest.py File

-After confirming that your camera works, you can would have to create a directory for your image datasets and your trainer folder.

-Create Directory for FacialRecognitionProject and in this directory create another two directories, one named dataset and one named trainer.

-Now you can run the Face dataset, Face Training and Face recognition codes.

-The Face Dataset code will ask you for a user id. The id matches to the ids in the recognition code. Simply add the name to the correct id. This will help recognize the faces. 
















Notes: 

The Blue sticker side of the Pi Cam should be facing the USB ports.

sudo modprobe bcm2835-v4l2    <--- This is an important code which helped me throughout this project. If while running the camera you get an assertion failed error, running the code will solve it.

For displaying your raspberry pi to your Windows Computer you can use RemoteDesktop. You require your RaspberryPi's IP address which you can find by using the ifconfig command and taking the inet address. This address will connect you to your raspberry pi and you will have to put your username and password for your pi. Typically your username is "pi" and password is "raspberry".
But you have to enable SSH from your interfacing options.

To shutdown your Raspberry Pi from RemoteDesktop run this Command. (sudo shutdown -h now)

References:

https://www.hackster.io/mjrobot/real-time-face-recognition-an-end-to-end-project-a10826

https://www.hackster.io

https://www.pyimagesearch.com/
