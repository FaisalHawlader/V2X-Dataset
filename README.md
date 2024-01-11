# V2X-Object Detection Dataset

Welcome to the V2X-Object Detection Dataset repository, a fundamental resource designed to support research in real-time object detection for autonomous driving environments. This dataset is a crucial tool for validating and benchmarking innovative research concepts in the field of autonomous driving, leveraging vehicle-to-everything (V2X) communication. It can be used for various purposes in the domain of computer vision to computer networking.

## Publication
For a comprehensive understanding of the dataset and its applications, we recommend referring to our research paper " **Leveraging the Edge and Cloud for V2X-Based Real-Time Object Detection in Autonomous Driving**":
- [Read the Full Paper (PDF)](https://doi.org/10.1016/j.comcom.2023.11.025)

### Citation:
If you use this dataset in your research, please use the following citation:

```text
@article{hawlader2024leveraging,
  title={Leveraging the edge and cloud for V2X-based real-time object detection in autonomous driving},
  author={Hawlader, Faisal and Robinet, Fran{\c{c}}ois and Frank, Rapha{\"e}l},
  journal={Computer Communications},
  volume={213},
  pages={372--381},
  year={2024},
  publisher={Elsevier}
}
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
<img height="190" width="350" alt="image" src="https://github.com/FaisalHawlader/V2X-Dataset/assets/43897254/87ded165-aa80-4098-8998-e99e6042539a">
<img height="190" width="320" alt="image" src="https://github.com/FaisalHawlader/V2X-Dataset/assets/43897254/f5b5bb2e-c3b4-4531-b29a-550b931aaa96">


## Downloads
To access the complete dataset, please use the following link:
- [Download the Dataset (15 GB)](https://uniluxembourg-my.sharepoint.com/:f:/g/personal/faisal_hawlader_uni_lu/EiPjYoflxEFLk5lCQ5O22oQBgMrmnvAzHau4Y6CpMw1ZgA?e=dDPbJN).

## Acknowledments
This work is supported by the [Fonds National de la Recherche of Luxembourg (FNR)](https://www.fnr.lu/), under AFR grant agreement No 17020780 and project acronym ACDC.
