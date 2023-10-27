# V2X-Object Detection Dataset

Welcome to the V2X-Object Detection Dataset repository, a fundamental resource designed to support research in real-time object detection for autonomous driving environments.
This dataset is a crucial tool for the validation and benchmarking of innovative research concepts in the field of autonomous driving, leveraging vehicle-to-everything (V2X) communication.

## Publication
For a comprehensive understanding of the dataset and its applications, we recommend referring to our research paper:
- [Read the Full Paper (PDF)](https://arxiv.org/pdf/2308.05234.pdf)


**Citation:**
If you use this dataset in your research, please use the following citation:

```text
@article{hawlader2023leveraging,
  title={Leveraging the Edge and Cloud for V2X-Based Real-Time Object Detection in Autonomous Driving},
  author={Hawlader, Faisal and Robinet, Fran{\c{c}}ois and Frank, Rapha{\"e}l},
  journal={arXiv preprint arXiv:2308.05234},
  year={2023}
}
@INPROCEEDINGS{10061953,
  author={Hawlader, Faisal and Robinet, François and Frank, Raphaël},
  booktitle={2023 18th Wireless On-Demand Network Systems and Services Conference (WONS)}, 
  title={Vehicle-to-Infrastructure Communication for Real-Time Object Detection in Autonomous Driving}, 
  year={2023},
  volume={},
  number={},
  pages={40-46},
  doi={10.23919/WONS57325.2023.10061953}}
```

## Dataset Overview
- Synthetic dataset using the CARLA simulator, 10k camera frames
- Ground truth bounding boxes for three classes: vehicles, pedestrians, and traffic lights
- Split into three subsets: Training (6000), Validation (2000) and Testing (2000)


![image](https://github.com/FaisalHawlader/V2X-Dataset/assets/43897254/e9e68ebf-ca45-46e8-9665-b62e948b59ae)

```
[CSV_FILE]
|
+--[TYPE]
|
+--[TIME (ms)]
```
### Example Images
![alt text](https://github.com/raphaelfrank/robobus/blob/main/sample_images.png?raw=true)

## Downloads
To access the complete dataset, please use the following link:
- [Download the Dataset (67GB)](https://uniluxembourg-my.sharepoint.com/:f:/g/personal/faisal_hawlader_uni_lu/EiPjYoflxEFLk5lCQ5O22oQBgMrmnvAzHau4Y6CpMw1ZgA?e=dDPbJN).

## Acknowledments
This work is supported by the [Fonds National de la Recherche of Luxembourg (FNR)](https://www.fnr.lu/), under AFR grant agreement No 17020780 and project acronym ACDC.
