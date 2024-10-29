# multiple-clinical-photography-learning-

## Skin image dataset
1. The image dataset consists of Train, Validation, and Test and is divided into each folder (patient by patient).

2. Each folder contains data from multiple images(photographs) of the same skin lesion for each patient.

3. To implement the model, the data must have the following items; 'pt_num': patient's unique number, 'file_dir': multiple file paths per patient, 'class number': index number of the corresponding class, 'file_num': number of multiple files per patient. We used the json file format for the corresponding forms, and we recommend using json files for main code as well. (However, if you want to use various storage methods such as txt, change some codes.)

4. Consider the example below, where there are two image files per patient for a total of two patients. As shown in the file name format, '1_20240101_1.JPG' indicates that the pt_num is 1, taken on 20240101 (the date), with a file_num of 1. Likewise, '1_20240101_2.JPG' indicates pt_num 1, taken on the same date, with a file_num of 2. Any file naming format is acceptable, but please organize files in a way that supports the use of multiple clinical photographs.

5. You should name the JSON file for the Train dataset as "instancelearning_Train.json" (also create the JSON files for the Validation and Test datasets).


## Installation

To install the required dependencies for this project, use the following command:

```bash
pip install -r requirements.txt
