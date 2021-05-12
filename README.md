# Image-Recognition


Unzip the zip file submitted (Final Project).

There are 4 files inside "Final Project" folder:
  1. datasets folder
  2. Project Codes folder
  3. documentation file
  4. ReadMe file
  
### Setup
>Datasets Folder consists of 2 folders for "MNIST" and "OCR"
  MNIST has 4 zip files
  OCR has 1 zip file
  
Note: Please unzip the letter.data.gz file in the same OCR folder.
 
### Extracting and saving the data from datasets
>Go to "Project Codes" folder and run the following notebooks
  1. OCR_Extraction.ipynb
  2. MNIST_Extraction.ipynb

Now we can see train and test folders inside MNIST and OCR folders, which consists of their respected image files.
Here, we can also see that pickle files are also generated during extraction. These pickle files are loaded during the execution of our models.

Note: Pickle files are extremely useful in the Data Science projects, since they save the generated files on our local machine, and can be 
reloaded into multiple projects. This reduces the pre-processing step, when we are running multiple classifers on the same data on different scripts.

## Execution of Classifiers
>In the "Project Codes" folder, you should be able to see the following notebooks
  . Logistic Regression for OCR.ipynb
  . KNN for OCR.ipynb
  . Neural Network for OCR.ipynb
  . Logistic Regression for MNIST.ipynb
  . KNN for MNIST.ipynb
  . Neural Network for MNIST.ipynb
  
You would be able to run each individual notebook respectively and find the displayed classifier results.
