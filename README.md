https://pyimagesearch.com/2020/12/14/generating-aruco-markers-with-opencv-and-python/
https://pyimagesearch.com/2020/12/21/detecting-aruco-markers-with-opencv-and-python/

## Generating ArUco markers with OpenCV and Python
- python opencv_generate_aruco.py --id 24 --type DICT_5X5_100 --output tags/DICT_5X5_100_id24.png

Here we have generated a 5×5 ArUco marker using a dictionary that allows for 100 unique ArUco IDs. This marker has an ID value of 24, which means that it is the 24th unique marker in the dictionary. The marker is saved to disk as tags/DICT_5X5_100_id24.png.

## Detecting ArUco markers with OpenCV and Python
- python detect_aruco_image.py --image images/50_1.jpg --type DICT_5X5_100

Here we are detecting the ArUco marker in the image aruco_example.png. The marker is detected using the same dictionary that was used to generate the marker. The marker is detected and the ID value is printed to the terminal.