Requirements:-
1) Python 3.7 or above
   
2) List of Libraries:-
   1) Torch 
   2) Torchvision
   3) ultralytics
   4) opencv-python
   5) Pillow
   6) Numpy
   7) tkinter
  
3) Datasets:-
   1) YOLOv11 - .pt files (*Two models required*)
   2) FasterRCNN - .pth files (*Two models required*)
   3) HaarCascade - .xml files (*Five model files required*)

4) Total number of fishes choosen - 5 Different Species of fish

5) Tools for Annotation:
   1) Roboflow - YOLOv11, FasterRCNN
   2) Labellmg - YOLOv11
   3) LabelMe - FasterRCNN
   4) Cascade Trainer GUI - HaarCascade
(*I have provided the link to download Cascade Trainer Gui --> "https://amin-ahmadi.com/cascade-trainer-gui/"*)

6) Tools for Training:
   1) YOLOv11- JupyterLab, Google Collab (T4 GPU) 
   2) FasterRCNN- Google Collab(T4 GPU) ( *Requires GPU with Nvidia Core and High RAM for Training* )
   3) HaarCascade- Cascade Trainer GUI
      
____________________________________________________________________________________________________________________
IMPORTANT POINTS:
1) Change the file path in the GUI code.
2) Train with maximum number of epochs so we could get best trained model file.
3) If you are using different Fishes, kindly change the label names in the GUI.
4) This detection GUI can be used on various purposes based on the datasets and labels.
5) For FasterRCNN, we require high GPU so if you dont have enough GPU, train using T4 GPU in Google Collab.
