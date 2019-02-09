# Transfer_learning_with_ResNet50
Here I am using the pre trained ResNet50 model to classify 3 sets of objects, with Pytorch framework 
I used the tutorial on Transfer learning from the Pcompetitions.ytorch website. I added my own dataset that I created from the wild along with the super small subset of inagenet colllection.
I also observed the run time going down by half when I froze some layers in the model and did the training.
I ran in cpu. I will run this gpu, when I get my 10k dataset which I m working on now. But what I wanted to see was how efficient these models are in classifying some raw wild data along with the data that they knew from their IMAGENET  competitions.
I am also going to use these super efficient models in my object detection algorithm where I am working with fruits data .
I have the script here . The dataset is available on pytorch site.
The other dataset is from my private collection which are not included here. But you can use your own dataset and use the notebook to create the predecitions from this model.
