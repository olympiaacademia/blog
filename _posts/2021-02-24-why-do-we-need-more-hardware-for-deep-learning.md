---
title: Why do we need more hardware for deep learning?
description: For any neural network, the training phase of the deep learning model
  is the most resource-intensive task.
header: Why do we need more hardware for deep learning?
duration: 5 minutes

---
For any neural network, the training phase of the deep learning model is the most resource-intensive task While training, a neural network takes in inputs, which are then processed in hidden layers using weights that are adjusted during training and the model then spits out a prediction. Weights are adjusted to find patterns in order to make better predictions. Both these operations are essentially matrix multiplications. A simple matrix multiplication can be represented by the image below:  
  
![](https://olympiaacademia.github.io/old/assets/img/in_post_data/1_FlJ_ZPMSlpCdeuAYzC0gPw.png =654x320)  
  
If your neural network has around 10, 100 or even 100,000 parameters. A computer would still be able to handle this in a matter of minutes, or even hours at the most. But what if your neural network has more than 10 billion parameters? It would take years to train this kind of systems employing the traditional approach. Your computer would probably give up before you’re even one-tenth of the way.  
You can achieve this by using a GPU to train your model.  
A GPU is smaller than a CPU but tends to have more logical cores (arithmetic logic units or ALUs, control units and memory cache) than the latter. GPUs are optimized for training artificial intelligence and deep learning models as they can process multiple computations simultaneously. They have a large number of cores, which allows for better computation of multiple parallel processes. Additionally, computations in deep learning need to handle huge amounts of data this makes a GPU’s memory bandwidth most suitable.  
You should also give Cloud GPUs a thought. If you don’t want to buy a bunch of expensive GPUs, you can leverage GPUs on-demand with a cloud-hosting company. They’ll save you from configuring the hardware and best of all, they’re not that expensive — costs can be as little as US$0.25 per hour while you’re using it.