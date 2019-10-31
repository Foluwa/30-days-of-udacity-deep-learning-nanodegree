## Day 5 / 30

## Day 5: October 30, 2019

### I started Lesson 7: Deep learning with Pytorch.

![Tensors](tensors.png)

[Tensors](https://machinelearningmastery.com/introduction-to-tensors-for-machine-learning/) are the fundamental data structure for neural networks WHILE [PyTorch](), a framework for building and training neural networks AND Features are input data for your network.

	- A tensor with one dimension is a vector.

	- A 2 dimensional tensor has its value spaning from left to right and up to down i.e a Matrix.

	- A 3 dimensional tensor is an array with three indices i.e RGB color images.



### Functions in Pytorch
	
	- torch.sum() [ y = activation(torch.sum(features * weights) + bias)]
	>>	

	- torch.mm()
	>>

	- torch.matmul() 
	>>

	- torch.manual_seed()
	>>

	- torch.randn()
	>>

	- torch.from_numpy() [To create a tensor from a Numpy array]
	>>


	- .numpy() [To convert a tensor to a Numpy array]
	>>

#####  [ For torch.from_numpy() and  numpy() the memory is shared between the Numpy array and Torch tensor, so if you change the values in-place of one object, 		 the other will change as well. ]


