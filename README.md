models/darknet_fusion.py - Contains our Fusion model
mpdels/darknet_baseline.py - Contains the baseline model

To train the model:
./train.py -d /media/loahit/T7/RangeNet_dataset/data_odometry_velodyne -ac darknet21.yaml

give path -d PATH_TO_DATASET

Modify line 27 of darknet.yaml config file to choose model

baseline - darknet_baseline
Fusion model - darknet_fusion


