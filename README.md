# CLAS12_Lambda_resolution_REU_2023

This is the work I did as part of the Duke / TUNL 2023 REU program in Nuclear Physics. My goal was to improve the resolution of lambdas at CLAS12 by implementing a neural network. While the results are not immediate improvements, with more training data this model could likely be used to improve the lambda resolution.

I did it as a deep artifical neural network in Python with TensorFlow and Keras. It might work better using the ResNet architecture.

It is somewhat limited running on a CPU since the reconstructed / Monte Carlo matching algorithm takes up a lot of computational power. It is probably limited to about a couple hundred thousand .hipo events on CPU. It would be good to run it on a GPU with higher amounts of training data. 
