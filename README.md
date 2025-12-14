# memCS
This is the source code and data for our paper: *Yunrui Jiao, Han Zhao, Jianshi Tang, et al., A memristor-based energy-efficient compressed sensing accelerator with hardware-software co-optimization for edge computing, National Science Review, 2025; nwaf499*.

### 1.code

#### 1.1 AMP algorithm
- The source code of the approximate message passing (AMP) algorithm comes from the formulas in [this paper](https://arxiv.org/pdf/0907.3574).

#### 1.2 MMM & SE strategies
- These two strategies are used to optimize the measurement matrix $\Phi$ and the sparse transform matrix $\Psi$ in the AMP algorithm, respectively.



### 2.classification

- The dataset and source code for this section are saved here.

#### 2.1 pretrained_models
- A pre-trained convolutional neural network (default: ResNet50) is used here to perform classification inference on the reconstructed images.

#### 2.2 ImageNet

- For the source of the ImageNet-1k dataset, see [here](https://huggingface.co/datasets/ILSVRC/imagenet-1k).
- A tool code (./ImageNet/parquet_to_image.ipynb) is used to extract images from a specific data structure for experiments.
