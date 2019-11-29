# polyp_detection_based_on_yolov3

We apply YOLO v3 on polyp detection

The data is from CVC colon DB, 380 photos from 15 pieces of colonoscopy.

We retrained the network for 1000 epoch with batch size of 16, 80% of data for training and 20% for testing.

The result is as shown, and the highest one reached the 96.9% of mAP.

The weight is on https://drive.google.com/file/d/1R1rT2CjVm6U1NijyHUgef7aUpLbgI86l/view?usp=sharing, use detect.py to detect new images.
