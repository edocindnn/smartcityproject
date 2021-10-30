# licensePlateReader
Simple Python Project using OpenCV to detect and read License Plate
# to do in terminal
first install python using:
# step 1:
python --version
# step 2:
sudo apt update
# step 3:
sudo apt install software-properties-common
# step 4:
sudo add-apt-repository ppa:deadsnakes/ppa
# step 5:
sudo apt update
# step 6:
sudo apt install python3.8
# step 7:
python --version
now, install opencv
# step 1:
pip install opencv-python
then, install tesseract
# step 1:
sudo apt update
# step 2:
sudo apt install tesseract-ocr
then. install pytesseract
# step 1:
pip install pytesseract
# secondly, you have to run the licensePlateDetection.py in terminal itself
I have used ubuntu linux for this, I runned using the line
# python3 licensePlateDetection.py
we have car image:
![car0](https://user-images.githubusercontent.com/89440905/139521353-c8f734fd-ba75-4d22-9f0b-ab7b82bf050e.jpeg)
and while running this code in terminal we get
the respective number plate text as output
