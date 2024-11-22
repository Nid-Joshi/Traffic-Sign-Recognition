# Traffic-Sign-Recognition
A Comparative Analysis in Classifying Traffic Sign Images through Convolutional Neural Networks and Multilayer Perceptrons

Requirements:

- torch==2.2.0
- torchvision===0.17.0
- numpy===1.24.3
- opencv-python==4.9.0.80
- scikit-image==0.20.0
- scikit-learn==1.3.0
- pandas==1.5.3
- matplotlib==3.7.1
- seaborn==0.12.2



Setup_instructions:

1. Code file Details:
	- Main code file (CNN_MLP_Traffic_Signal_Recognition.ipynb)
	- Code file to load the saved models and test them (Load_and_Test.ipynb)
	- Both the saved models (cnn_model.pth & mlp_model.pth)
	- Data folder containing Test (with test images) and Train (with empty class folders meant for indexing) folders.
2. Install the packages mentioned under requirements above.
3. Launch Jupyter notebooks and change directory (cd) to the extracted folder
4. Run the Load_and_Test.ipynb code file to test and evaluate the saved models on the test dataset.
5. If needed, run CNN_MLP_Traffic_Signal_Recognition.ipynb to train the best models on Train dataset (data to be downloaded from https://www.kaggle.com/datasets/meowmeowmeowmeowmeow/gtsrb-german-traffic-sign/data) and save them.
