Requirements:-
1) Python 3.7 or above
   
2) List of Librariries:-
   a) Torch 
   b) Torchvision
   c) ultralytics
   d) opencv-python
   e) Pillow
   f) Numpy
   g) tkinter
  
3) Datasets:-
   a) YOLOv11 - .pt files (*Two models required*)
   b) FasterRCNN - .pth files (*Two models required*)
   c) HaarCascade - .xml files (*Five model files required*)

4) Total number of fishes choosen - 5 Different Species of fish

5) Tools for Annotation:
   Roboflow - YOLOv11, FasterRCNN
   Labellmg - YOLOv11
   LabelMe - FasterRCNN
   Cascade Trainer GUI - HaarCascade
(*I have provided the link to download Cascade Trainer Gui --> "https://amin-ahmadi.com/cascade-trainer-gui/"*)

6) Tools for Training:
   YOLOv11- JupyterLab, Google Collab (T4 GPU) 
   FasterRCNN- Google Collab(T4 GPU) ( *Requires GPU with Nvidia Core and High RAM for Training* )
   HaarCascade- Cascade Trainer GUI
      
____________________________________________________________________________________________________________________
IMPORTANT POINTS:
1) Change the file path in the GUI code.
2) Train with maximum number of epochs so we could get best trained model file.
3) If you are using different Fishes, kindly change the label names in the GUI.
4) This detection GUI can be used on various purposes based on the datasets and labels.
5) For FasterRCNN, we require high GPU so if you dont have enough GPU, train using T4 GPU in Google Collab.
