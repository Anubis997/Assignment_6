# Assignment_6_Part_1

![image](https://github.com/Anubis997/Assignment_6_Part_1/assets/96742087/fa4c2052-4c3e-4ab5-955d-9c150b15c674)



In this assignment, we have calculated backpropagation values step by step.

1. Initially, we work forward through the network, i.e we calculate the expressions for every neuron in the network.
For example, h1=w1*i1+w2*i2. Similarly, we calculate h2, and subsequent neurons such as a_h1,o1,etc.

2. Next we try to gauge rate of error change with respect to all the weights we encountered in the network so far.
We use chain rule of differentiation to calculate partial differentials with respect to previous weights.

For example,  ∂E_Total/∂w1= ∂E_Total/∂a_h1*∂a_h1/∂h1*∂h1/∂w1

3. Using the same pattern, we calculate partial derivative of E_Total w.r.t to all the weights and in the next iteration
we update weights using Wnew=Wold-learning_rate*∂E_Total/∂wold

As number of iterations increase, the difference between predicted values and original value will go to zero, i.e the error decreases.
As we increased the learning rate in this case, loss converged faster.

Here are the respective results for different learning rates:
![Learning_rate_0 1](https://github.com/Anubis997/Assignment_6_Part_1/assets/96742087/57a9a779-71b2-42be-9c2c-43d57e6c172b)

![Learning_rate_0 2](https://github.com/Anubis997/Assignment_6_Part_1/assets/96742087/5b4700ab-8e3d-45d8-bc3e-5011cc446647)

![Learning_rate_0 5](https://github.com/Anubis997/Assignment_6_Part_1/assets/96742087/63b1fd60-57a6-4241-a840-30a5c3a6011f)

![Learning_rate_0 8](https://github.com/Anubis997/Assignment_6_Part_1/assets/96742087/e3e2601e-e6d7-474f-978f-2714db2903f6)

![Learning_rate_1](https://github.com/Anubis997/Assignment_6_Part_1/assets/96742087/9e6ddefa-bff9-4067-9630-c9c268b9833d)

![Learning_rate_2](https://github.com/Anubis997/Assignment_6_Part_1/assets/96742087/b4b22c08-46ff-4aaa-ad06-ad75c4660178)





