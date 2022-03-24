# FedCL: Federated Contrastive Learning for Multi-center Medical Image Classification  
This is the code for paper FedCL: Federated Contrastive Learning for Multi-center Medical Image Classification.  
**Abstract:**Federated learning, which allows distributed medical institutions to train a shared deep learning model with privacy protection, has become increasingly popular recently. However, in practical application, due to the data difference between different hospitals, the final training model can not achieve the expected effect. In this paper, we propose a federated contrastive learning (FedCL) approach. FedCL is an effective framework that integrates the idea of contrastive learning into federated learning. It uses the feature representation learned by model to carry out contrastive learning, so that the local model gradually approaches the global model with the increase of communication rounds. A large number of experiments show that our method is superior to other federated learning algorithms in medical image classification. At the same time, we also did a lot of ablation experiments to prove the effectiveness of our method.
## Dependencies
+ python >= 3.6.13
+ PyTorch >= 1.8.1
+ torchvision >= 0.8.2
## Parameters
|Parameter|Description|
|----|----|
|model|neural network used in training|
|batch_size|batch_size per gpu|
|drop_rate|dropout rate|
|base_lr|maximum epoch number to train|
|seed|random seed|
|gpu|GPU to use|
|local_ep|local epoch|