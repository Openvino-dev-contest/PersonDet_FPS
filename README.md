# PersonDet_FPS
Detecting the person on your screen</br>
![Showcase](https://github.com/Openvino-dev-contest/PersonDet_FPS/blob/main/image/demo.gif)

# How to install
1. Install Python on your PC, and we recommand Python 3.7 for your first try</br>
https://www.python.org/downloads/
2. Start your CMD terminal and run "pip install -r requirement.txt", to install all the dependancy
3. run "python main.py -m ./model/person-detection-0202.xml"

# How it works
The program will capture 512x512 from the screen , and then</br>
figure out the position of any person in front of you.

# Tips
1. Do not scale your Windows sreen</br>
![Showcase](https://github.com/Openvino-dev-contest/PersonDet_FPS/blob/main/image/donotscale.png)</br>
2. This application only works on 1920x1080 resolution