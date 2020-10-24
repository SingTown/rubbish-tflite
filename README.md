# rubbish-tflite
A classification of battery, bottle, can, and cigarette.
[中文README](https://github.com/SingTown/rubbish-tflite/blob/main/README_CN.md)


This model I trained with edgeimpulse, tutorial:
https://docs.edgeimpulse.com/docs/openmv-cam-h7-plus


This is a demo for testing. If you need better results, please use your own images to train, very simple with edgeimpulse.

You can use the `dataset editor` of the OpenMV IDE to open the `dataset` directory to add images and upload training.

## Note:

1. only OpenMV 4 Plus can be used.

## To use:
1. drag labels.txt and trained.tflite to OpenMV Plus.
2. run ei_image_classification.py with OpenMV IDE.
3. you can see result in terminal.

## result
![test_battery](https://github.com/SingTown/rubbish-tflite/blob/main/test/test_battery.png)
![test_bottle](https://github.com/SingTown/rubbish-tflite/blob/main/test/test_bottle.png)
![test_can](https://github.com/SingTown/rubbish-tflite/blob/main/test/test_can.png)
![test_cigarette](https://github.com/SingTown/rubbish-tflite/blob/main/test/test_cigarette.png)
