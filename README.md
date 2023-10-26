# V2X-Dataset

Academic datasets are an important source of information to validate and benchmark novel research concepts. In this paper we present RoboBus, a dataset recorded with a commercial bus on a cross-border public transport route between Luxembourg and France. The dataset contains approximately 8 hours of driving data divided into 15 trips that have been recorded over 4 days. It includes about 1.7 million anonymized images capturedby two road-facing cameras, GNSS traces, data from a 9-axis IMU, and information directly retrieved from the CAN interface of the vehicle including speed, steering angle and position of the accelerator/brake pedals.

## Publication
For the detailed description of the dataset, please refer to our [paper](https://arxiv.org/pdf/2308.05234.pdf). If you use this dataset in your research, please use the following citation:
```text
@article{hawlader2023leveraging,
  title={Leveraging the Edge and Cloud for V2X-Based Real-Time Object Detection in Autonomous Driving},
  author={Hawlader, Faisal and Robinet, Fran{\c{c}}ois and Frank, Rapha{\"e}l},
  journal={arXiv preprint arXiv:2308.05234},
  year={2023}
}
```

## Dataset

### Data Format
```
[CSV_FILE]
|
+--[TYPE]
|
+--[TIME (ms)]
|
+--[CAN_DATA (type 1)]
|  |
|  +—[VEHICLE_SPEED (km/h)]
+--[CAN_DATA (type 2)]
|  |
|  +—[ACC_PEDAL_POSITION]
+--[CAN_DATA (type 3)]
|  |
|  +—[BRK_PEDAL_POSITION]
+--[CAN_DATA (type 4)]
|  |
|  +—[STE_WHEEL_ANGLE]
+--[IMU_DATA (type 50, 51 and 52)]
|  |
|  +—[ACC/MAG/GYR X]
|  +—[ACC/MAG/GYR Y]
|  +—[ACC/MAG/GYR Z]
+--[GNSS_DATA (type 100)]
|  |
|  +—[TIMESTAMP]
|  +—[LATITUDE]
|  +—[LONGITUDE]
|  +—[ALTITUDE]
+--[CAMERA_INFO (type 201 and 202 )]
|  |
|  +—[PATH_TO_IMAGE]
```
### Example Images
![alt text](https://github.com/raphaelfrank/robobus/blob/main/sample_images.png?raw=true)

## Downloads
The total dataset is ~67GB and can be downloaded [here](https://uniluxembourg-my.sharepoint.com/:f:/g/personal/raphael_frank_uni_lu/En6-LdcLQsBChOT90otp4RsBqo2a-HDHoxg8ntdjZYCVHg?e=JvngzB).

## Acknowledments
This work is supported by the [Fonds National de la Recherche of Luxembourg (FNR)](https://www.fnr.lu/), under AFR grant agreement No 17020780 and project acronym ACDC.
