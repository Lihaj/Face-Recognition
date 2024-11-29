# Assignment for Facial Emotion Recognition

## Pip command to install all the required libraries in one line ->

pip install shutil sklearn pandas numpy matplotlib seaborn tqdm tensorflow keras pillow opencv-python mtcnn

There are 6 phases, namely-

1. Data Preprocessing
2. Load the Dataset
3. Data Analysis
4. Feature Extraction
5. Model Creation
5. Plot the Results
6. Test with Image Data

## How to run the code ->

- At the Data preprocessing phase you have to call the function Crop_and_save() to crop the faces and save them in an output folder.
    In order to do that you have to change file paths input_folder = 'Data/Sad'
                                                    output_folder = 'Processed Data/Sad'
    Ex:- For crop and save Angry folder images change the file paths to input_folder = 'Data/Angry'
                                                                          output_folder = 'Processed Data/Angry'
- Now run each cell.
