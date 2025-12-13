# memCS
This is the source code and data for our paper, *Energy-Efficient Compressive Sensing Accelerator Based on Memristors with Hardware-Software Co-Optimization for Edge Computing (Accepted by National Science Review)*.

### 1.code

#### 1.1 AMP algorithm
- The source code of the approximate message passing (AMP) algorithm comes from the formulas in [this paper](https://arxiv.org/pdf/0907.3574).

#### 1.2 MMM & SE strategies
- These two strategies are used to optimize the measurement matrix $\Phi$ and the sparse transform matrix $\Psi$ in the AMP algorithm, respectively.


### 2.data

#### 2.1 1D signal
- The 1D signal in Fig. 3c is a randomly generated signal with length 64, which is sparse in the DCT domain.


#### 2.2 2D image
- The images in Fig. 3d and Figs. 6b, 6c come from the ImageNet dataset categories 'house finch', 'Old English sheepdog', 'great white shark' and 'fox squirrel'.

### 3.classification

#### 3.1 pretrained_models
- A pre-trained convolutional neural network (default: ResNet50) is used here to perform classification inference on the reconstructed images.

#### 3.2 ImageNet

- For the source of the ImageNet-1k dataset, see [here](https://huggingface.co/datasets/ILSVRC/imagenet-1k).
- A tool code based on Python is used to extract images from a specific data structure for experiments.
