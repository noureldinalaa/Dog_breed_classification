[//]: # (Image References)

[image1]: ./images/sample_dog_output.png "Sample Output"


# Dog_breed_classification
Dog breed classifier using convolutional neural network(This Project is part from Udacity's deep learning nanodegree))

## Project Overview
The aim of this project is giving the model an image of a dog , and the model will identify an estimate of the canine's breed . But if it is supplied with an image of human , the model will identify the resembling dog breed.


![Sample Output][image1]

## Project Instructions

### Instructions

1. Clone the repository and navigate to the downloaded folder.
	
	```	
		git clone https://github.com/noureldinalaa/Dog_breed_classification.git
		cd Dog_breed_classification    
	```
2. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/dogImages`.  The `dogImages/` folder should contain 133 folders, each corresponding to a different dog breed.

3. Download the [human dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz).  Unzip the folder and place it in the repo, at location `path/to/dog-project/lfw`. 

4. Install packages like pytorch and torch vision and some pip packages in requirements text file :
	```
		conda install pytorch torchvision -c pytorch
            pip install -r requirements.txt
	```
5. Open a terminal window and navigate to the project folder. Open the notebook and follow the instructions.
	
	```
		jupyter notebook dog_app.ipynb
	```

## Further work 
To try different Model architecture to achieve higher acuuracy .
