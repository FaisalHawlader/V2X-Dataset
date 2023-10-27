# V2X-Object Detection Dataset

Welcome to the V2X-Object Detection Dataset repository, a fundamental resource designed to support research in real-time object detection for autonomous driving environments.
This dataset is a crucial tool for the validation and benchmarking of innovative research concepts in the field of autonomous driving, leveraging vehicle-to-everything (V2X) communication.

## Publication
For a comprehensive understanding of the dataset and its applications, we recommend referring to our research paper " **Leveraging the Edge and Cloud for V2X-Based Real-Time Object Detection in Autonomous Driving**":
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
<img width="358" alt="image" src="https://github.com/FaisalHawlader/V2X-Dataset/assets/43897254/bdf76a4a-5612-43c4-b3de-8bfb40c5fb41">

![alt text](https://github.com/raphaelfrank/robobus/blob/main/sample_images.png?raw=true)

## Downloads
To access the complete dataset, please use the following link:
- [Download the Dataset (67GB)](https://uniluxembourg-my.sharepoint.com/:f:/g/personal/faisal_hawlader_uni_lu/EiPjYoflxEFLk5lCQ5O22oQBgMrmnvAzHau4Y6CpMw1ZgA?e=dDPbJN).

## Acknowledments
This work is supported by the [Fonds National de la Recherche of Luxembourg (FNR)](https://www.fnr.lu/), under AFR grant agreement No 17020780 and project acronym ACDC.
