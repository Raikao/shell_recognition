# Snail detection model

## How to Train the model

Run [this Colab Notebook](https://colab.research.google.com/github/Raikao/shell_recognition/blob/master/snail_detection_colab.ipynb).



## How to run inference on frozen TensorFlow graph

Requirements:
- `morph_frozen_inference_graph.pb` Frozen TensorFlow object detection model downloaded from Colab after training. Can be downloaded in [here](https://drive.google.com/file/d/1C61lK-Gnnxl9yKRW2CdvsnJivrKQ04EE/view?usp=sharing)
- `morph_label_map.pbtxt` File used to map correct name for predicted class index downloaded from Colab after training. Can also be downloaded [here](https://drive.google.com/file/d/1C61lK-Gnnxl9yKRW2CdvsnJivrKQ04EE/view?usp=sharing)

The images used for the training can also be found in this drive [link](https://drive.google.com/file/d/1YpZtL8gKYEXVr6Ik4Z-ZHglWXmrLGoQq/view?usp=sharing)

Run the following Jupyter notebook locally.
```
local_inference_test.ipynb
```

This repository has been based on [Dlogy blog](https://www.dlology.com/blog/how-to-train-an-object-detection-model-easy-for-free/) and using the code from [Tony607](https://github.com/Tony607/object_detection_demo).

