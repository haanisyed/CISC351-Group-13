# Replication Package: Impact of Adversarial Attacks on Autonomous Car Object Detection

**Authors**: Haani Syed, Viren Tated, Anneth Sivakumar, Sidhardh Alluri

## Overview
This repository contains all code to replicate our research study on the object detection security of autonomous vehicles.

## Datasets

IPRPAS Dataset: https://borealisdata.ca/dataset.xhtml?persistentId=doi:10.5683/SP3/O8DLSU

KITTI Dataset:https://www.cvlibs.net/datasets/kitti/

COCO Dataset: https://cocodataset.org/



## Repository
```
.
├── Data/
│   ├── data.zip           
│   └── queries.md
├── RQ1/
│   └── RQ1PCA-OCSVM.ipynb         # Jupyter notebook for RQ 1 PCA Object Detection System
    └── RQ1YOLOv7.ipynb         # Jupyter notebook for RQ 1 YOLOv7
├── RQ2/
│   ├── RQ2.ipynb         # Jupyter notebook for RQ 2 

├── RQ3/
│   ├── RQ3.ipynb 


├── requirements.txt         # Python package dependencies
└── README.md             
```



## Requirements
- Python 3.9+
- Jupyter Notebook
- 7-zip for data extraction purposes
- 2x RTX A5000 (24G) GPUs
- 256G RAM
- 32 cores ADM Epyc 2.6/3.3GHz


## Setup Instructions


### Research Question 1

1. Download: Left_Images1.zip and Label.zip from the IPRPAS Dataset link

2. Extract Data: Unzip both files into new folders (Done by RQ1PCA-OCSVM.ipynb script)

3. Install Dependencies

4. Run the remaining RQ1PCA-OCSVM.ipynb script


The setup for testing against the YOLOv7 model is present in the code file, RQ1YOLOv7.ipynb.


### Research Question 2

1. Download: Left_Images1.zip and Label.zip from the IPRPAS Dataset link

2. Extract Data: Unzip both files into new folders (Done by RQ2.ipynb script)

3. Install Dependencies

4. Run the remaining RQ2.ipynb script


### Research Question 3

1. Download: data-tracking-image_2 and kitti-step.tar.gz from KITTI Website

2. Extract Data: Unzip files into new folders (Done by RQ3.ipynb script) (Requires Google COLAB, requirements in Google Colab automatically installed)

3. Extract traffic_signs.zip into RQ3.ipynb working environment

4. Install Dependencies

5. Download GhostBusters from https://github.com/ymirsky/GhostBusters/tree/master

6. Replace GB_model in GhostBusters with the updated GB_model_updated on this directory

7. Run Remainder of Script

## Contact
For technical assistance and inquiries on datasets used:

Haani Syed: 21ahs7@queensu.ca

Viren Tated: viren.tated@queensu.ca

Anneth Sivakumar: 21as221@queensu.ca

Sidhardh Alluri: 21sva3@queensu.ca
