### What is a linear regression model? Give an example of a problem formulated as a linear regression model.
### What are input and target variables in a dataset? Give an example.
### What are weights and biases in a linear regression model?
### How do you represent tabular data using PyTorch tensors?
### Why do we create separate matrices for inputs and targets while training a linear regression model?
### How do you determine the shape of the weights matrix & bias vector given some training data?
### How do you create randomly initialized weights & biases with a given shape?
### How is a linear regression model implemented using matrix operations? Explain with an example.
### How do you generate predictions using a linear regression model?
### Why are the predictions of a randomly initialized model different from the actual targets?
### What is a loss function? What does the term “loss” signify?
### What is mean squared error?
### Write a function to calculate mean squared using model predictions and actual targets.
### What happens when you invoke the .backward function on the result of the mean squared error loss function?
### Why is the derivative of the loss w.r.t. the weights matrix itself a matrix? What do its elements represent?
### How is the derivate of the loss w.r.t. a weight element useful for reducing the loss? Explain with an example.
### Suppose the derivative of the loss w.r.t. a weight element is positive. Should you increase or decrease the element’s value slightly to get a lower loss?
### Suppose the derivative of the loss w.r.t. a weight element is negative. Should you increase or decrease the element’s value slightly to get a lower loss?
### How do you update the weights and biases of a model using their respective gradients to reduce the loss slightly?
### What is the gradient descent optimization algorithm? Why is it called “gradient descent”?
### Why do you subtract a “small quantity” proportional to the gradient from the weights & biases, not the actual gradient itself?
### What is learning rate? Why is it important?
### What is torch.no_grad?
### Why do you reset gradients to zero after updating weights and biases?
### What are the steps involved in training a linear regression model using gradient descent?
### What is an epoch?
### What is the benefit of training a model for multiple epochs?
### How do you make predictions using a trained model?
### What should you do if your model’s loss doesn’t decrease while training? Hint: learning rate.
### What is torch.nn?
### What is the purpose of the TensorDataset class in PyTorch? Give an example.
### What is a data loader in PyTorch? Give an example.
### How do you use a data loader to retrieve batches of data?
### What are the benefits of shuffling the training data before creating batches?
### What is the benefit of training in small batches instead of training with the entire dataset?
### What is the purpose of the nn.Linear class in PyTorch? Give an example.
### How do you see the weights and biases of a nn.Linear model?
### What is the purpose of the torch.nn.functional module?
### How do you compute mean squared error loss using a PyTorch built-in function?
### What is an optimizer in PyTorch?
### What is torch.optim.SGD? What does SGD stand for?
### What are the inputs to a PyTorch optimizer?
### Give an example of creating an optimizer for training a linear regression model.
### Write a function to train a nn.Linear model in batches using gradient descent.
### How do you use a linear regression model to make predictions on previously unseen data?
