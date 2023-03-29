# Jordanian Traffic Signs Detection using YOLOv7

## Overview
This repository contains a YOLOv7 model trained on the Jordanian (Arabic) Traffic Signs dataset. The dataset can be found at https://www.kaggle.com/datasets/khaledhweij/jordanian-traffic-signs. The model achieves a mean average precision of 99% for a threshold of 0.5 and 88% for a threshold of 0.95. Additionally, there are two test scripts included: `image_test.py` for testing the model on images, and `video_test.py` for testing on videos.

## Requirements
Before using the test scripts, please make sure that `cv2.imshow` is running correctly in your environment.

## How to Use
To use the trained model for detection, first clone the repository:
```
git clone https://github.com/ahmed-saad1997/Traffic-signs-detection-YOLOV7-.git
```

To test the model, first install the required packages by running:
```
pip install -r yolov7/requirements.txt
```

To test the model on images, run the following command:
```
python yolov7/image_test.py
```

To test the model on videos, run the following command:
```
python yolov7/video_test.py
```
If you want to train the model, you can do so by running cells in `traffic_signs_detection_yolov7.ipynb`.
Note that this notebook created in colab so make sure to modify paths.

Make sure to modify the paths.

## Credits
The YOLOv7 model used in this repository is based on the implementation by WongKinYiu, which can be found at https://github.com/WongKinYiu/yolov7. The model was trained on the Jordanian (Arabic) Traffic Signs dataset, which was compiled by Khaled Hweij and can be found at https://www.kaggle.com/datasets/khaledhweij/jordanian-traffic-signs.

## License
This repository is licensed under the MIT License. See the LICENSE file for more information.
