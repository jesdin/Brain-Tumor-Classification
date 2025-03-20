# Brain-Tumor-Classification
Brain Tumor Classification using Transfer Learning Inception V3

## Setup
Clone the Repository
```
git clone git@github.com:jesdin/Brain-Tumor-Classification.git
cd Brain-Tumor-Classification
```

Create and Activate Conda Environment. Install required libraries
```
conda create -n bt_class python=3.10.9
conda activate bt_class
pip install -r requirements.txt
```

Create Directories for Data and Model
```
mkdir data
mkdir model
```

Download the Dataset
```
kaggle datasets download -d masoudnickparvar/brain-tumor-mri-dataset --unzip -p ./data

```