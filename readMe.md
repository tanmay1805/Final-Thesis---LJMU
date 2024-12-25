# Final Thesis - LJMU - Comparative Study of Deep Learning models for ASL Recognition

--------------------------

This repo contains files that were used to conduct the comparative study for ASL recognition systems using deep learning models.



### Data Preparation

--------------------------

For data preparation, the dataset was used from https://github.com/dxli94/WLASL/tree/master/start_kit

The videos downloaded from following instructions this repo are then used to run the file `Data Preparation And EDA/Data_Prep_YOLO.ipynb`.
This file converts raw videos dataset to YOLO compatible structure.
Another form of dataset is the parquet files taken from https://www.kaggle.com/datasets/himanko/landmarks-wlasl.

Final Dataset is available under https://drive.google.com/drive/folders/1l6Rre8Zya9amogycJyjme39Q6kgyNKd8?usp=sharing which is used for model training.

File `Data Preparation And EDA/data.yaml` is used for YOLO model training.

### EDA

--------------------------

For EDA, run files under `Data Preparation And EDA/EDA_WLASL.ipynb` and `Data Preparation And EDA/Data_Prep_YOLO.ipynb`.

### Model Training

--------------------------

For YOLO Model - `Model Training/WLASL_YOLO.ipynb`

For Swin Transformer Model - `Model Training/WLASL_swin_transformer.ipynb`

For CNN Model - `Model Training/WLASL_CNN.ipynb`

