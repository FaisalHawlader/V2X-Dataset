# V2X-Object Detection Dataset

Welcome to the V2X-Object Detection Dataset repository, a fundamental resource designed to support research in real-time object detection for autonomous driving environments. This dataset is a crucial tool for validating and benchmarking innovative research concepts in the field of autonomous driving, leveraging vehicle-to-everything (V2X) communication. It can be used for various purposes in the domain of computer vision to computer networking.

## Publication
For a comprehensive understanding of the dataset and its applications, we recommend referring to our research paper " **Leveraging the Edge and Cloud for V2X-Based Real-Time Object Detection in Autonomous Driving**":
- [Read the Full Paper (PDF)](https://arxiv.org/pdf/2308.05234.pdf)

### Citation:
If you use this dataset in your research, please use the following citation:

```text
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
- Synthetic dataset using the [CARLA](https://carla.org/) simulator (Open-source simulator for autonomous driving research).
- The dataset contains 10k camera frames and ground truth bounding box annotations for three classes:
  - **vehicles (bus, car), pedestrians, and traffic lights**
- Split into three subsets:
    - Training (6k images)
    - Validation (2k images)
    - and Testing (2k images)
```text
V2X-Dataset (format):
    - Train
        - images
          - .*.bmp
        - labels
          - *.txt
    - Test
        - images
          - .*.bmp
        - labels
          - *.txt
    - Validation
        - images
          - .*.bmp
        - labels
          - *.txt
```
### Example Images
<img height="190" width="320" alt="image" src="https://github.com/FaisalHawlader/V2X-Dataset/assets/43897254/bdf76a4a-5612-43c4-b3de-8bfb40c5fb41">
<img height="190" width="360" alt="image" src="https://github.com/FaisalHawlader/V2X-Dataset/assets/43897254/87ded165-aa80-4098-8998-e99e6042539a">
<img height="190" width="320" alt="image" src="https://github.com/FaisalHawlader/V2X-Dataset/assets/43897254/f5b5bb2e-c3b4-4531-b29a-550b931aaa96">
<img height="190" width="320" alt="image" src="(https://github.com/FaisalHawlader/V2X-Dataset/assets/43897254/15d95158-85ed-44db-b8b1-45fe1db69d11)">



## Downloads
To access the complete dataset, please use the following link:
- [Download the Dataset (40 GB)](https://uniluxembourg-my.sharepoint.com/:f:/g/personal/faisal_hawlader_uni_lu/EiPjYoflxEFLk5lCQ5O22oQBgMrmnvAzHau4Y6CpMw1ZgA?e=dDPbJN).

## Acknowledments
This work is supported by the [Fonds National de la Recherche of Luxembourg (FNR)](https://www.fnr.lu/), under AFR grant agreement No 17020780 and project acronym ACDC.
