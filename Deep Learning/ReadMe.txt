The command I executed during the presentation:

For YOLO:
object_detection_yolo.py --image=./dataset/dog416.png

For MaskRCNN
mask_rcnn.py --model=./models/mask_rcnn_inception_v2_coco_2018_01_28.pb --config=./models/mask_rcnn_inception_v2_coco_2018_01_28.pbtxt --input=./dataset/run.mp4
