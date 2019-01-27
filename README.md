## Dog breed detection project

This is a project about identifying dog breed from images of dogs while I was completing nanodegree program on deep learning at Udacity.
There are two approaches, one is using small convolutional network and the other transfer learning from pretrained vgg16 network.

To see the results just download and open the dog_app.ipynb.html file.

To run the Jupyter notebook do the following
1) Clone the repository
2) Install install [`miniconda`](http://conda.pydata.org/miniconda.html) on your computer.
3) Create a new `conda` [environment](http://conda.pydata.org/docs/using/envs.html), for example dog-breed
	- __Linux__ or __Mac__: 
	```
	conda create -n dog-breed python=3.6
	source activate dog breed
	```
	- __Windows__: 
	```
	conda create --name dog-breed python=3.6
	activate dog-breed
4) Install PyTorch and torchvision; this should install the latest version of PyTorch.
	
	- __Linux__ or __Mac__: 
	```
	conda install pytorch torchvision -c pytorch 
	```
	- __Windows__: 
	```
	conda install pytorch -c pytorch
	pip install torchvision

5) Install a few required pip packages, which are specified in the requirements text file (including OpenCV).
```
pip install -r requirements.txt
```

6) Run jupyter notebook from command line in dog-breed-detection folder.

Please let me know if there are problems with the installation!

