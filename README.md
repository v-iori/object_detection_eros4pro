<h1 align="center">Face Mask Detection</h1>

## TechStack/framework used

- [OpenCV](https://opencv.org/)
- [Caffe-based face detector](https://caffe.berkeleyvision.org/)
- [Keras](https://keras.io/)
- [TensorFlow](https://www.tensorflow.org/)
- [MobileNetV2](https://arxiv.org/abs/1801.04381)

## Prerequisites

All the dependencies and required libraries are included in the file <code>requirements.txt</code> 

## Installation
1. Clone the repo
```
$ git clone https://github.com/v-iori/mask_detection.git
```

2. Change your directory to the cloned repo 
```
$ cd Face-Mask-Detection
```

3. Create a Python virtual environment named 'Smile' and activate it
```
$ conda create --name Smile
```
```
$ conda activate Smile
```

4. Now, run the following command in your Terminal/Command Prompt to install the libraries required

```
$ cd mask_detection
```
```
$ pip3 install -r requirements.txt
```

## Working

1. Open terminal. Go into the cloned project directory and type the following command:
```
$ python3 train_mask_detector.py --dataset dataset
```

2. To detect face masks in an image type the following command: 
```
$ python3 detect_mask_image.py --image images/pic1.jpeg
```

3. To detect face masks in real-time video streams type the following command:
```
$ python3 detect_mask_video.py 
```

## Owner
based on work done by [Chandrika Deb](https://github.com/chandrikadeb7)



