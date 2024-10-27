# Secondary-structure-predicition
This project tested 3 different models for protein secondary structure prediction. The project was guided thorugh chatGPT and most of the code was written by ChatGPT. The code was done as a jypiter notebook in google colab. A lot of the code was run using the CPU. The dataset used is this one: 
https://www.kaggle.com/datasets/kirkdco/protein-secondary-structure-2022/data

4 different datasets were used using the code in the file data_to_proj. The values in the code is tested using the code with the following settings:

Dataset, Training sets (#sequences), Test set (#sequences), Start length, End length
Dataset 1: 4000, 1000, 20, 50
Dataset 2, 8000, 2000, 20, 50
Dataset 3, 1600, 4000, 15, 60
Dataset 4, 1600, 4000, 10, 80

In all code one can se the name of the file used. 

Then the code was testing on the three models, Random forest, CNN and Hybrid CNN/RNN using the code in the file: Final_project_initial_testing.ipynb

Then Final_project_Hyper_parameter_tuning.ipynb file is used to run hyper parameter tuning on the three models.The values were then tested using the file Final_project_optimized parameters.ipynb.

These results lead to move forward with the CNN model. Further hyperparametrization was done using the file: Final_project_CNN.ipynb. The values were then tested using the code: Final_CNN_Model.ipynb
