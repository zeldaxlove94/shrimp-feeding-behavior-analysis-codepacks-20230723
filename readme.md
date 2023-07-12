# yamato shrimp- feeding behavior analysis - codepacks- July 2023

The Code for several important parts of this experiment are organized in this data rack, including the black pixel computation algorithm (used to compute feed coverage), the computational length algorithm (used to compute body length), and the program code for linear regression.

此實驗中幾個重要部分的Code都整理在這個資料架中，其中包括黑色圖元計算演算法（用於計算飼料覆蓋率）、計算長度演算法（用於計算體長）以及線性回歸的程式碼。

## Yolo v8 Instance Segmentation

yolov8_instance_segmentation(yamato_shrimp_project).ipynb - The code for Yolo v8 training and recognition, including the training of the model in the experiment, recognition, and output of binarized images (Yolo v8 訓練和識別的程式碼，包括實驗中模型的訓練、識別以及二值化圖片的輸出) , Colab 傳送門 :<https://colab.research.google.com/drive/1wxqS484QXGSvT9wWTl4kUnrh3e-xRFmi?usp=sharing>

The dataset we used in this study is on Roboflow.實驗中使用的的數據集關於數據集已上傳至Roboflow, Dataset 傳送門 :<https://universe.roboflow.com/amano-shrimp-detection/yamato-shrimp-detection>

For Yolo v8 Example Segmentation Training Original Code, 這裡有訓練Yolo v8實例分割完整教程 :

yolov8 instance segmentation on custom dataset.ipynb - <https://colab.research.google.com/github/roboflow-ai/notebooks/blob/main/notebooks/train-yolov8-instance-segmentation-on-custom-dataset.ipynb>

## black pixel caculation algorithm , length caculation algorithm , and linear regression

black pixel caculation algorithm , curve fitting and parameter search - in '.\black_pix_cal'

length caculation algorithm - in '.\len_cal'

linear regression and result output - in '.\sf_len_analysis'
