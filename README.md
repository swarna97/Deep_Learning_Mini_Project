# Deep Learning Mini Project

RESNET-18 on CIFAR 10 with less than 5 million parameters.

With the advent of Backpropagation in Neural Networks, the research in the field of "Image classification" has exploded. Every year various "Very Deep Neural Networks" having 100s of millions of parameters have been trained by larger corporations to win the annual ImageNet challenge with very high accuracy. However, such models are not easy to train on small machines. That begs the question, what happens when the size of the model is limited? Can we achieve reasonably high accuracy? In this project, we try to answer this question. We limit the number of parameters to less than or up to 5 million parameters and try to maximize the accuracy. Our goal is to achieve more than 90% accuracy on the CIFAR-10 dataset while experimenting with various attributes of the model. 

With the best model, we were able to achieve 91.49% accuracy, which meets our desired expectations.


Dataset used: CIFAR-10.

Model used: RESNET-18. 

Final Model Training Notebook : [Notebook](https://github.com/swarna97/Deep_Learning_Mini_Project/blob/main/Notebooks/Model_Training-Adam-512_Final.ipynb)

Model Parameter Tuning Notebook : [Notebook](https://github.com/swarna97/Deep_Learning_Mini_Project/blob/main/Notebooks/Experiment_Model_Parameter.ipynb)

Hyperparameter Tuning Experiments(Batch Size, Epochs, Learning Rate, Scheduler, Optimizer) :  [Experiment](https://github.com/swarna97/Deep_Learning_Mini_Project/tree/main/Notebooks/Experiments)

## Results 
Comparison on Different Batch Size (Accuracy) : 

<img width="512" alt="Screen Shot 2022-11-23 at 7 19 09 PM" src="https://user-images.githubusercontent.com/26515041/203667459-c2ad843f-ee80-40da-a00d-16f9d6ccfdab.png">


![Batch size](https://github.com/swarna97/Deep_Learning_Mini_Project/blob/main/Plots/epoch_vs_accuracy_batch_size.png)

Comparison on Different Batch Size  (Loss): 

![Loss batch size](https://github.com/swarna97/Deep_Learning_Mini_Project/blob/main/Plots/epoch_vs_loss_batch_size.png)

Comparison on Learning Rate: 

<img width="518" alt="Screen Shot 2022-11-23 at 7 23 44 PM" src="https://user-images.githubusercontent.com/26515041/203667876-878e2c13-8ef4-4199-b16d-d9dc205e1dbf.png">

![Learning Rate](https://github.com/swarna97/Deep_Learning_Mini_Project/blob/main/Plots/Learning_Rate.png)

SGD vs ADAM optimizer: 

![sgd_vs_adam](https://github.com/swarna97/Deep_Learning_Mini_Project/blob/main/Plots/sgd_vs_adam.png)

Adam optimizer with and without lookahead:

![adam](https://github.com/swarna97/Deep_Learning_Mini_Project/blob/main/Plots/adam_with_vs_without_lookahead.png)

