# Realtime-Facemask-Detection
Python Project using openCV and keras 
 
 Installation

Clone the repo-
$ git clone https://github.com/fuseplan/Realtime-Facemask-Detection.git
Change your directory to the cloned repo-
$ cd Face-Mask-Detection
Create a Python virtual environment named 'test' and activate it-
$ virtualenv test
$ source test/bin/activate
Now, run the following command in your Terminal/Command Prompt to install the libraries required-
$ pip3 install -r requirements.txt

Working

Open terminal. Go into the cloned project directory and type the following command:
$ python3 train_mask_detector.py --dataset dataset
To detect face masks in an image type the following command:
$ python3 detect_mask_image.py --image images/pic1.jpeg
To detect face masks in real-time video streams type the following command:
$ python3 detect_mask_video.py 
for streamlit webapp:
$ streamlit run app.py
