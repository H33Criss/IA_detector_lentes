<h1 align="left">🤖Proyecto final de IA</h1>

###

<img align="right" height="100" src="https://raw.githubusercontent.com/goktug97/PyYOLO/master/pyyologo.png"  />

###

<p align="left">Este proyecto utiliza la camara para detectar el objeto "lente" 🕶️ en tiempo real.<br><br>Se usa la tecnología de seguimiento de objetos Ultralytics Yolo V11</p>

###

<h2 align="left">Algunas demostraciones</h2>

###

<img align="left" height="200" src="https://raw.githubusercontent.com/H33Criss/IA_detector_lentes/refs/heads/main/demostraciones/2.gif"  />

###

<img align="left" height="200" src="https://raw.githubusercontent.com/H33Criss/IA_detector_lentes/refs/heads/main/demostraciones/3.gif"  />

###

<img align="left" height="200" src="https://raw.githubusercontent.com/H33Criss/IA_detector_lentes/refs/heads/main/demostraciones/4.gif"  />

###

<img align="left" height="200" src="https://raw.githubusercontent.com/H33Criss/IA_detector_lentes/refs/heads/main/demostraciones/5.gif"  />

###

<br clear="both">

<h2 align="left">Desarrollo con estas tecnologías</h2>

###

<div align="left">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" height="40" alt="python logo"  />
  <img width="12" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" height="40" alt="vscode logo"  />
</div>

###

<h2 align="left">Entrenamiento</h2>

###

<p>Detección por sobre la segmentación</p>

`yolo task=detect mode=train epochs=200 data=dataset/dataset.yaml model=yolov8n.pt imgsz=512 batch=2 conf=0.4 amp=True`

<p>Más <strong>epochs</strong> en un modelo con menos carga <strong>(Yolov8n)</strong> computacional fue mas beneficioso</p>

###
