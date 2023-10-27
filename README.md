# V2X-Object Detection Dataset

Welcome to the V2X-Object Detection Dataset repository, a fundamental resource designed to support research in real-time object detection for autonomous driving environments.
This dataset is a crucial tool for the validation and benchmarking of innovative research concepts in the field of autonomous driving, leveraging vehicle-to-everything (V2X) communication, and can be used for different purposes.

## Publication
For a comprehensive understanding of the dataset and its applications, we recommend referring to our research paper " **Leveraging the Edge and Cloud for V2X-Based Real-Time Object Detection in Autonomous Driving**":
- [Read the Full Paper (PDF)](https://arxiv.org/pdf/2308.05234.pdf)

**Abstract:** Environmental perception is a key element of autonomous driving because the information received from the perception module influences core driving decisions. An outstanding challenge in real-time perception for autonomous driving lies in finding the best trade-off between detection quality and latency. Major constraints on both computation and power must be taken into account for real-time perception in autonomous vehicles.  Larger detection models tend to produce the best results but are also slower at runtime. Since the most accurate detectors may not run in real-time locally, we investigate the possibility of offloading computation to edge and cloud platforms, which are less resource-constrained. We create a synthetic dataset to train object detection models and evaluate different offloading strategies. We measure inference and processing times for object detection on real hardware, and we rely on a network simulation framework to estimate data transmission latency. Our study compares different trade-offs between prediction quality and end-to-end delay. Following the existing literature, we aim to perform object detection at a rate of 20Hz. Since sending raw frames over the network implies additional transmission delays, we also explore the use of JPEG and H.265 compression at varying qualities and measure their impact on prediction. We show that models with adequate compression can be run in real-time on the edge/cloud while outperforming local detection performance.

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
<img height="190" width="320" alt="image" src="https://github.com/FaisalHawlader/V2X-Dataset/assets/43897254/bdf76a4a-5612-43c4-b3de-8bfb40c5fb41">
<img height="190" width="360" alt="image" src="https://github.com/FaisalHawlader/V2X-Dataset/assets/43897254/87ded165-aa80-4098-8998-e99e6042539a">
<img height="190" width="320" alt="image" src="https://github.com/FaisalHawlader/V2X-Dataset/assets/43897254/f5b5bb2e-c3b4-4531-b29a-550b931aaa96">


## Downloads
To access the complete dataset, please use the following link:
- [Download the Dataset (40 GB)](https://uniluxembourg-my.sharepoint.com/:f:/g/personal/faisal_hawlader_uni_lu/EiPjYoflxEFLk5lCQ5O22oQBgMrmnvAzHau4Y6CpMw1ZgA?e=dDPbJN).

## Acknowledments
This work is supported by the [Fonds National de la Recherche of Luxembourg (FNR)](https://www.fnr.lu/), under AFR grant agreement No 17020780 and project acronym ACDC.
