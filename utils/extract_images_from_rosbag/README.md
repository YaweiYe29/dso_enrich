# How to use
This program will extract all images from all rosbag files from a given folder.
To call it, execute:
```./extract_images_from_rosbag.py /path/to/bag_files topic_name```

E.g., if your bag files are in /home/user/Downloads and the recorded topic is ```/camera/image_raw```, run:
```./extract_images_from_rosbag.py /home/user/Downloads /camera/image_raw```

The script will create a folder for each bag file (with the same name as the bag file), containing all images from that topic as PNG.
They are named frame_XXXXX.png.