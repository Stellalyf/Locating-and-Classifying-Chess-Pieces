# Locating-and-Classifying-Chess-Pieces
For the final project of cse455, our team is composed of Colin Acton, Bob Xiaohai Hu, Yifan Liu.

## To run our code
+ **Trainning:** 
Based on google colab, Model_train.ipynb is for training our model, and calculate the accuracy for model performed on testing dataset. you can modify the neural net work type by substitute the 'faster_rcnn_X_101_32x8d_FPN_3x.yaml' in the configuration cell.
 check [dectorn2 offical github page to choose](https://github.com/facebookresearch/detectron2/tree/main/configs/COCO-Detection) what model we can use.
 
+ **Test on customized image:**
Load model weight that already trained from google drive(or from your loacl pc, we also put weights in models folder of this repository, so you can gitclone and just use the model we have trained on customized dataset!

## Our website
**[https://sites.google.com/uw.edu/chesspiecedetection/home]()**

## Project Presentation Video
[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/nXypFB2z2Xw/0.jpg)](http://www.youtube.com/watch?v=nXypFB2z2Xw)

## References
[1] Detectron2 Faster R-CNN Information: https://paperswithcode.com/lib/detectron2/faster-r-cnn

[2] Roboflow Chess Pieces Dataset: https://public.roboflow.com/object-detection/chess-full

[3] R-CNN: https://paperswithcode.com/method/r-cnn

[4] Faster R-CNN: Faster R-CNN: Towards Real-Time Object Detection with Region Proposal Networks 

[5] Chess player robot repository: https://github.com/macs-lab/robotic_chess_player

[6] Chess Pieces Recognition using CNN: https://towardsdatascience.com/board-game-image-recognition-using-neural-networks-116fc876dafa

[7] Detectron2 official Github repository: https://github.com/facebookresearch/detectron2
