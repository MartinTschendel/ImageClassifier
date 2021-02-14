# ImageClassifier

Here I built a deep convolutional neural network that can classify photos of dogs and cats.<br>
It is inspired by the tutorial ["How to Classify Photos of Dogs and Cats"](https://machinelearningmastery.com/how-to-develop-a-convolutional-neural-network-to-classify-photos-of-dogs-and-cats/#comment-597191) from Jason Brownlee.<br>
The model is trained on a dataset of totally 10,000 pictures of dogs and cats, that is taken from the udemy course "Machine Learning A-Z".<br><br>
<b>Performance of the final model, measured over 20 epochs</b><br>
Final model  
* consists of a convolutional neural network with 3 blocks
* applies image data augmentation
* uses 'adam' for the optimzier (stochastic gradient descent)<br>

Blue lines refer to training set<br>
Orange lines refer to test set<br>
<img src="https://github.com/MartinTschendel/ImageClassifier/blob/main/line_charts.PNG" width="400">

