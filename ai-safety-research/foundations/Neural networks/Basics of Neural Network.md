_Shout out to 3Blue1Brown that provided the content so I can use and study here_

## What are neural networks? 
--> A network of neurons

- **What it is a Neuron?**: --> "a nerve cell with its appendages." A neuron is a ==nerve cell that processes and transmits information== through electrical and chemical signals in the nervous system.
- **What it is a Network?** --> "net-like arrangement of threads, wires, etc., anything formed in the manner of or presenting the appearance of a net or netting." ==Essentially, it is a system that allows two or more devices to exchange information==, resources, and services. You can think of a **network** like a spider web. The transmission lines (analogous to webbing) connect each hardware device (sometimes called nodes).

In machine learning the essence is the same, but they do work a bit different.
### How do they work?

Neurons store information as numbers. These numbers depend on the original information given (input) but ultimately, the network outputs a number between 0 and 1.

The information on the neurons have pass trough layers; These layers send it to it to other layers to act as a filter so it can become more easy to separate and unite parts of information so it can help digest the information, after this is used a bias filter helping to calibrate the ReLU function separate signal from noise, becoming easier for the machine interpret the information given.

The network is also a giant function (for this part it's good to have a basis in linear algebra to have better visualization, I may be lacking in this department)

Most used functions: 
- Matrix Multiplication --> Big tables multiplications (input × weights = weighted sum)
- Dot Product --> Specific products from the tables
- Rectified Linear Unit  --> It's here to say who is positive and who is negative (Aka responsible for hidden layers: activate positive neurons, zero out negatives)
- Sigmoid --> its the output, it squashes the numbers in 0 or 1 to be assign for binary classification


For those how noticed, the entire network is a composed function: input --> matrix multiplication --> ReLU --> matrix multiplication --> Sigmoid --> output. Each operation is a function; stacked together, they form one giant function (a very complicated one); and at the end of it when the information is processed it is sent to be worked according to instructions given, a classic exemple would be a neural network to identify numbers.
