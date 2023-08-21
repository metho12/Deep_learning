# Deep_learning

- Types of machine learning inspired by human brain.
- Structure : Artifical neural Networks.
- It needs a massive number of data to be trained.
- It also needs high GPU.
- It takes time to be trained.
- It is the most used.


- Famous Frameworks:

1- Tensor-flow
2- Keras.
3- Python 
4- DI4I 
5- Coffe 
6- Microsoft cognitive toolkit.


-Deep learning vs machine learning 


Deep learning will give you a lot of benefits:

1- No dimensionality reduction.
2- No Feature extraction.
3- Deal with structural and un structure data (audio, images, videos, even text)
4- more data more accurate and performance.
5- Complex problems.




But with cost 

1- A lot of training time 
2- high Computational power GPU.
3- Huge amount of data.
4- more data will lead to saturation.


Deep learning 


Why not deep learning 
1- simple problems.
2- acceptable error 
3- Small data .

applicatins
1- customer supoort. 

2- medical care 
3- self driving care.
4- face Recognition 
5- object detection 
6- Recommendations 
7- Robotics 


Steps of deep learning :

1- the network will be layers on neurons.
2- first layer : input layer.
3- last layer : output layer.
4- in the middle: the hidden layers(for computations, feature extraction)
5- the input data will be a flatten matrix to the first layer (each pixel to a neuron )
6- Networks for a layer are connected to the neurons of the next layer using channels.
7- each channel assigned a value = weight 
8- the neuron value will be multiplied by the wight + the bias (neuron value )
9- the result value will be passed tp a threshold value called = activation function.
10 - the result of the activation function will determine if the particular neurons will get activation or not .
11- Activation neurons will pass the data to the neuron of the next layer using the channels.
12 - And so on the data will be propagated Through the Networks (forward  propagation)
13 - in the output layer the neuron with highest value(probability)fires the output (predicted)
14- during this Process the network will compare the prediction output with the real output to realize the error 
(backward  propagation)
15- Based on the this the weight are being adjusted 
16- this Process will continue untils the Network can predict the output correctly (most of cases)


ANN 

1- Build on top of biological neuron network.
2- The simplest ANN consist of hidden layer.
3- many layers = deep neural network 
4- Each neuron connects to another and has an associated weight and threshold.
5- the first weight are generated randomly, then be optimized.
6- if the output of any individual neuron is above the threshold value , that node is activation (send data to the net layer)if not no data will be passed (this feature is not important ) 
7- There are many hidden layer types, most general is dense layer 
8- all deep learning networks build on top of gradient descent.

Advantages:

1- ANN has the ability to learn and model non-linear and complex relationship as many relationships between input and output are non-linear.
2- after training ANN can infer unseen relationships from unseen data, and hence it is generalized.
3- Unlike many machine learning models, ANN does not have restrictions on datasets like data should be Gaussian distributed or way other distribution.

- Application:
1- image preprocessing and character recognition
2- forecasting 
3- Credit rating 
4- Fraud Detection 




 

