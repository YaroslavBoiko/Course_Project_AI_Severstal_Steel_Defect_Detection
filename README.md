# Course Project AI Severstal Steel Defect Detection


**This course work is devoted to solving the problem of finding defects on a sheet of metals**


This section describes the steps you need to take to complete the training and testing process
(So, how to use all that is here)


- 1. You need to download the data from https://www.kaggle.com/c/severstal-steel-defect-detection/data and replace it with the           severstal-steel-defect-detection folder.
  2. You need to download weights - [model.pth](https://drive.google.com/drive/folders/1-yrtFpC2sQnL22xJmV7dO6N5BNDTqf3F), if you want to check my already finished implementation, and put this file in the input / unet-starter-model-file
  3. Now before training the neural network you need to download all the necessary libraries via `pip install -r requirements.txt`
  4. And the final step is to choose whether you want to train and test the neural network, or just test it.  
  - 4.1 If you want to test:
    - 4.1.1. Run the Test.ipynb file
  - 4.2 If you want to train and test:
      You have two options to do it all with one file or two (with decomposition, the essence is better understood)
    - 4.2.1. If you want by one file - run Yaroslav Boiko_Main.ipynb
    - 4.2.2. If you want by two files, run Train.ipynb first, then Test.ipynb.
  5. You can check the results on the [kaggle](https://www.kaggle.com).
