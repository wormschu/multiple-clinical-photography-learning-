# multiple-clinical-photography-learning-

## Skin image dataset
1.The image dataset consists of Train, Validation, and Test and is divided into each folder (patient by patient).

2.Each folder contains data from multiple images(photographs) of the same skin lesion for each patient.

To implement the model, the data must have the following items; 'pt_num': patient's unique number, 'file_dir': multiple file paths per patient, 'class number': index number of the corresponding class, 'file_num': number of multiple files per patient. We used the json file format for the corresponding forms, and we recommend using json files for main code as well. (However, if you want to use various storage methods such as txt, change some codes.)

## Installation

To install the required dependencies for this project, use the following command:

```bash
pip install -r requirements.txt
