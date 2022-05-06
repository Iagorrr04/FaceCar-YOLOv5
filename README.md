<h1 align="center"> FaceCar - YOLOv5</h1>

<p align="center">    The FaceCar project was created during the discpline of TEES (Specials Topics about Software Engineering), given by the teacher Giovanni Almeida Santos at the University of Brasília - FGA, by the software engineering students <a href="https://github.com/Iagorrr04">Iago Rocha</a>, and <a href="https://github.com/JoseFilipi">José Filipi.</a></p>

<div align="center">
<img src="https://github.com/Iagorrr04/FaceCar-YOLOv5/blob/master/images/unb_logo.png"  width="20%">
</div>

<p align="center">    Our main goal is to simulate an app or program that could prevent the driver to fall sleep, or keep driving in several fadigue, tiredness, drosy and any related state that could induce a possibly traffic accident. Using the <a href="https://github.com/ultralytics/yolov5">YOLOv5</a> and python algorithms to detect the driver state and take the due actions to reach this goal.</p>

<div align="center">
    <img src="https://github.com/Iagorrr04/FaceCar-YOLOv5/blob/master/images/example.jpeg" height="5%" width="20%">
</div>

<h2 align="center">About YOLOv5</h2>
<p align="center"> <a href="https://github.com/ultralytics/yolov5">YOLOv5 🚀</a> is a family of object detection architectures and models pretrained on the COCO dataset, and represents <a href="https://ultralytics.com">Ultralytics</a>
 open-source research into future vision AI methods, incorporating lessons learned and best practices evolved over thousands of hours of research and development.</p>
<p align="center"> <i>Check the full documentation at the <a href="https://docs.ultralytics.com">YOLOv5 Docs</a>.</i></p>

 <div align="center">
   <a href="https://github.com/ultralytics">
   <img src="https://github.com/ultralytics/yolov5/releases/download/v1.0/logo-social-github.png" width="2%"/>
   </a>
   <img width="2%" />
   <a href="https://www.linkedin.com/company/ultralytics">
   <img src="https://github.com/ultralytics/yolov5/releases/download/v1.0/logo-social-linkedin.png" width="2%"/>
   </a>
   <img width="2%" />
   <a href="https://twitter.com/ultralytics">
   <img src="https://github.com/ultralytics/yolov5/releases/download/v1.0/logo-social-twitter.png" width="2%"/>
   </a>
   <img width="2%" />
   <a href="https://www.producthunt.com/@glenn_jocher">
   <img src="https://github.com/ultralytics/yolov5/releases/download/v1.0/logo-social-producthunt.png" width="2%"/>
   </a>
   <img width="2%" />
   <a href="https://youtube.com/ultralytics">
   <img src="https://github.com/ultralytics/yolov5/releases/download/v1.0/logo-social-youtube.png" width="2%"/>
   </a>
   <img width="2%" />
   <a href="https://www.facebook.com/ultralytics">
   <img src="https://github.com/ultralytics/yolov5/releases/download/v1.0/logo-social-facebook.png" width="2%"/>
   </a>
   <img width="2%" />
   <a href="https://www.instagram.com/ultralytics/">
   <img src="https://github.com/ultralytics/yolov5/releases/download/v1.0/logo-social-instagram.png" width="2%"/>
   </a>
</div>

<h2 align="center">Quick start example</h2>

<h3>In your local machine</h3>
First make sure you have git, pip, and <a href="https://www.python.org/">Python>=3.7.0</a>, than simply run the following commands.

```bash
# Clone our repo and install the pre requisites.
git clone https://github.com/Iagorrr04/FaceCar-YOLOv5
cd FaceCar-YOLOv5
pip install -r requirements.txt

# Run the algorithm !

# Less hardaware consumption
python3 facecar.py --img 640 --weights runs/train/small/weights/best.pt --source 0 --conf 0.821 --hide-conf --line-thickness 1 --max-det 6 --facecar

```

<h3>Or try it at Google Collab ! <img></img></h3>
<div align="center"><span>🚧 Not done yet 🚧</span></div>
<div align="center">
    <a href="https://colab.research.google.com/github/Iagorrr04/FaceCar-YOLOv5/blob/master/FaceCar_Quick_Start.ipynb">
        <img src="https://github.com/Iagorrr04/FaceCar-YOLOv5/blob/master/images/logo-colab-small.png" width="15%"/>
    </a>

</div>

<h2 align="center">Contributing to our dataset</h2>
<p align="center">As there is not so much free copyright images in the context we need, our dataset become relatively small, and not so much diversified, because we used or own photos to train it, generating an algorithm with less precion than the usual.</p>

<p align="center">In order to sovle this would be necessary to collect more data so we opened our dataset to be collaborative, simply go through our instructions at Google Collab to contribute.</p>
<div align="center">
    <a href="https://colab.research.google.com/github/Iagorrr04/FaceCar-YOLOv5/blob/master/datasetContribution.ipynb" >
        <img src="https://colab.research.google.com/assets/colab-badge.svg\" alt="Contribute at collab\"/>
    </a>
</div>