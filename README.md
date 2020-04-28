<br>
<div align="center">
  <img src="https://user-images.githubusercontent.com/44631215/80526256-7015cf80-89cd-11ea-8ffa-ad0234451773.PNG">
</div>
<br><br><br>


[![Python](https://img.shields.io/pypi/pyversions/tensorflow.svg?style=plastic)](https://badge.fury.io/py/tensorflow)
<a href="https://opencv.org/"><img alt="openCV" src="https://img.shields.io/badge/OpenCV-4.3.0-red.svg"/></a>
<a href="https://www.djangoproject.com/"><img alt="django" src="https://img.shields.io/badge/django-3.0-green.svg"/></a>
  <a href="https://www.djangoproject.com/"><img alt="djangorestframework" src="https://img.shields.io/badge/djangorestframework-3.10.3-brightgreen.svg?style=flat"/></a>
  <br>
  <p>
  
<h2>Motivation</h2></br>
</p>
<p align="center">
  <img src="https://user-images.githubusercontent.com/44631215/80531155-174a3500-89d5-11ea-82a7-27d428533fd1.gif">
</p>
<br><br>
<p>With the recent development of the Internet and streaming services, more Internet lectures are being created, and demand is also increasing.
However, these Internet lectures continue to have a similar system, and there are still things that cause discomfort by listening in the system.
First, the Internet lecture is a structure in which the lecturer and the viewer cannot interact.
Viewers have a hard time knowing where they haven't seen if they haven't focused on the lecture.
Even video providers can't tell which part of their video wasn't responding well and where the viewers had a good concentration rate.
So, we developed a READ solution, Reaction evaluation & aggregation data, to solve this problem.
It is a process divided into Reaction evaluation part that judges user's concentration and Aggregation data part that collects viewer's data and analyzes it to give feedback to video providers.
Through this solution, video viewers can analyze the concentration level of the video to compensate for the lack of concentration and provide motivation to increase concentration.
Video providers can also see the concentration of viewers, grasp the strengths and weaknesses of their video, and make efforts to improve the video.
  </p>
<br>

<h2>Install</h2></br>

See the [Python install guide](https://www.python.org/downloads/) for the
[pip package](https://www.python.org/downloads/pip) to install the necessary modules to run basic Python functions.
```
$ pip install scikit-learn
```
```
$ pip install numpy
```
```
$ pip install pandas
```
<br>
The OpenCV module can be installed via pip.

```
$ python -m pip install opencv-python
```
<br>
Make sure opencv is installed properly.

```
 import cv2
print(cv2.__version__)
```
<br>
Install to complement the poor usability of OpenCV.

```
$ pip install dlib
```
```
$ pip install imutils
```
<br>
Use GridSearchCV to find the best parameters.

```
$ pip install xgboost
```
<br>

[Download](https://pjreddie.com/darknet/yolo/) the yolo-coco file in read\analyzer for real-time object detection.

<br>

It is a platform that provides video and utilizes user information and analyzes it using a web server and a pro-end.
We installed these two because we used bootstrap as django and frontend as backend.
<br>
<h4>bootstrap</h4>
Since we created a web page with bootstrap, you can use bootstrap if you want to [change it to a web page](https://getbootstrap.com/docs/3.3/getting-started/) of your choice.
<br>
<h4>Django</h4>
Python 3.x version or higher is possible, so check the version.

```
$ python --version
$ pip install django
$pip3 install djangorestframework
```
<br>
To run the server, run a cmd window in the part of manage.py in the READ file.

```
$ manage.py migrate
$ python manage.py runservero
```
<br>
<div align="center">
  <img src="https://user-images.githubusercontent.com/44631215/80536016-af97e800-89dc-11ea-885c-38ffc93e3825.jpg">
</div><br>
After running the server, proceed to membership registration and store the membership information on the DB.

```
$ manage.py migrate --run-syncdb
```
<br>
In order to distinguish between video providers and viewers, they are classified by level in Django administration.<br>
<div align="center">
  <img src="https://user-images.githubusercontent.com/44631215/80536029-b45c9c00-89dc-11ea-96b9-c0a4f03eb271.PNG">
</div>
<h2>Credits</h2></br>
Gachon University software department

***김보배 김동욱 하은영***
<br>
<h2>Opensource</h2></br>
<a href="https://canvasjs.com/">canvas.js<img alt="canvas.js" src="https://www.comparasoftware.com/wp-content/uploads/2018/07/canvasjslogo.png"/></a>

<a href="https://www.chartjs.org/">chart.js<img alt="chart.js" src=https://1stwebdesigner.com/wp-content/uploads/2016/05/chart-thumb.jpg"/></a>
  
[xgboost]
