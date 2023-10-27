# V2X-Object Detection Dataset

Welcome to the V2X-Object Detection Dataset repository, a fundamental resource designed to support research in real-time object detection for autonomous driving environments.
This dataset is a crucial tool for the validation and benchmarking of innovative research concepts in the field of autonomous driving, leveraging vehicle-to-everything (V2X) communication.

## Publication
For a comprehensive understanding of the dataset and its applications, we recommend referring to our research paper:
- [Read the Full Paper (PDF)](https://arxiv.org/pdf/2308.05234.pdf)


### Citation:
If you use this dataset in your research, please use the following citation:

```text
@article{hawlader2023leveraging,
  title={Leveraging the Edge and Cloud for V2X-Based Real-Time Object Detection in Autonomous Driving},
  author={Hawlader, Faisal and Robinet, Fran{\c{c}}ois and Frank, Rapha{\"e}l},
  journal={arXiv preprint arXiv:2308.05234},
  year={2023}
}
```

## Dataset Overview
- Synthetic dataset using the [CARLA](https://carla.org/) simulator (Open-source simulator for autonomous driving research). , 10k camera frames
- The full dataset contains 10k camera frames and ground truth bounding boxes for three classes: ** vehicles, pedestrians, and traffic lights **
- Split into three subsets:
    - Training (6k images)
    - Validation (2k images)
    - and Testing (2k images)

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
