
<H1 align="center">
YOLOv8 Object Detection with DeepSORT Tracking (ID + Trails)
</H1>

## Google Colab File Link (A Single Click Solution)
The Google Colab file link for YOLOv8 object detection and tracking is provided below. You can check the implementation in Google Colab, and it's a single-click implementation. Just select the Run Time as GPU, and click on Run All.

[`Google Colab File`](https://colab.research.google.com/drive/1U6cnTQ0JwCg4kdHxYSl2NAhU4wK18oAu?usp=sharing)

## Object Detection and Tracking (ID + Trails) using YOLOv8 on Custom Data
## Google Colab File Link (A Single Click Solution)
[`Google Colab File`](https://colab.research.google.com/drive/1dEpI2k3m1i0vbvB4bNqPRQUO0gSBTz25?usp=sharing)

## YOLOv8 Segmentation with DeepSORT Object Tracking

[`Github Repo Link`](https://github.com/niloybiswas190448/Vehicle_Detection_thesis)

## Steps to Run Code

- Clone the repository:
git clone https://github.com/niloybiswas190448/Vehicle_Detection_thesis.git


- Go to the cloned folder:
cd Vehicle_Detection_thesis

- Install the dependencies:
pip install -e '.[dev]'


- Set the directory:
cd ultralytics/yolo/v8/detect


- Download the DeepSORT files from Google Drive:
https://drive.google.com/drive/folders/1kna8eWGrSfzaR6DtNJ8_GchGgPMv3VC8?usp=sharing

- After downloading the DeepSORT ZIP file from the Drive, unzip it. Go into the subfolders and place the `deep_sort_pytorch` folder into the `yolo/v8/detect` folder.

- Download a sample video from Google Drive:
gdown "https://drive.google.com/uc?id=1rjBn8Fl1E_9d0EMVtL24S9aNQOJAveR5&confirm=t"


- Run the code with the command below:

For YOLOv8 object detection + tracking:
python predict.py model=yolov8l.pt source="test3.mp4" show=True

For YOLOv8 object detection + tracking + vehicle counting:
- Download the updated `predict.py` file from Google Drive and place it into the `ultralytics/yolo/v8/detect` folder:
https://drive.google.com/drive/folders/1awlzTGHBBAn_2pKCkLFADMd1EN_rJETW?usp=sharing

- For YOLOv8 object detection + tracking + vehicle counting:
python predict.py model=yolov8l.pt source="test3.mp4" show=True


### RESULTS

#### Vehicles Detection, Tracking, and Counting
![](./figure/figure1.png)

#### Vehicles Detection, Tracking, and Counting
![](./figure/figure3.png)

(https://www.linkedin.com/posts/niloy-biswas-92003b1b3_deeplearning-trafficmanagement-smartcity-activity-7201622636068564992-fsdv?utm_source=share&utm_medium=member_desktop)
