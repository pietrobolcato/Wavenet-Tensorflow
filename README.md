# Tensorflow Wavenet 

This repository implements Wavenet (https://www.deepmind.com/blog/wavenet-a-generative-model-for-raw-audio) using tensorflow. 

## How to run 

- Install the dependencies by running: ```pip install -r requirements_gpu.txt```
- Train using ```python train.py```. Please refer to the original paper as for best-practice at training time.
- Once the network is trained, run inference with ```python generate.py```  
