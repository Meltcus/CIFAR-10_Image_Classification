**Purpose of each file included in the Github Repo:**
1) README.md
  -  Outlines the steps to execute the code for data pre-processing.
  -  Describe the steps for running the code to train, evaluate, and apply the models.

2) COMP472_ProjectReport_Alvi_Rahath.pdf
  -  Highlights the changes made for variants of each model, specifically noting how each deviates from the main model.
  -  Details the training methodology: number of epochs, learning rate, loss function used, and other relevant training hyperparameters.
  -  Mentions any optimization algorithms or techniques used, like mini-batch gradient descent, Adam optimizer, etc. 
  -  Presents the metrics (accuracy, precision, recall, and F1-measure) of the four ML models and their variants.
  -  Offers insights into each model’s performance relative to the others. For instance, if one model has a higher recall but lower precision, 
  -  Discussed its implications in the context of facial image analysis.
  -  Displays the confusion matrices for each model.
  -  Identifies which classes were most frequently confused and discusses any model-specific reasons that might be behind these misclassifications.
  -  Highlights well-recognized classes and speculates on the reasons behind their success.
  -  Reflects on how depth (for the decision tree, MLP, and CNN) influenced performance. 
  -  Discuss how layer size (for MLP) and kernel size (for CNN) variations affected the model’s recognition abilities.
  -  Summarized the primary findings: which model performed best and why?
    
3) 472_Project.ipynb
  -  Encompasses scripts for data visualization and dataset processing.
  -  PyTorch code for the four models, including the variants, code for evaluation as well as saving, loading, and testing the models.
  -  bp stands for bullet point in regards to the format of the project guidelines


  
Note: For simplicity we want the files to be downloaded locally rather than using the mount Google Drive feature.

**Instructions to run code/models:**

1) It is strongly recommended you have Google Colab Pro to run the code quickly.

2) Ensure you have at least 1GB of disk space memory on your device to download the saved models.

3) Open the following Google Drive link: [COMP472_Project](https://drive.google.com/drive/folders/1hGBebT5Q5dsLiAhd9kLqgdzHK7FBPrKO?usp=drive_link) to find saved models
 Within the models directory, there are 4 saved model directories, each containing their respective saved model files.

4) Download all 4 zip directories locally

5) Unzip each directory
6) Drag and drop all of the downloaded/saved files onto the Google Colab environment

7) Before running any models, you must run the Blocks 1, 2, 3 and 4 in that order.
    a) To run Gaussian Naive Bayes models: Run Block 7 
    b) To run Decision Tree models: Run Block 11
    c) To run Multi-Layer Perceptron models: Run Blocks 15 
    d) To run Convolutional Neural Network models: Run Blocks 20
    e) Comments under each block specify which portion of the project requirements is being answered.
		
NOTE: You may skip these steps and run Blocks 1 to 20 sequentially if you do not want the saved models, instead you will train and save the models from scratch on the Google Colab runtime environment. This will take SIGNIFICANTLY longer. Not recommended.





https://drive.google.com/drive/folders/1hGBebT5Q5dsLiAhd9kLqgdzHK7FBPrKO?usp=drive_link
