# Read-NN
Binary Classification of Reads by Deep learning neural network

Requirements:

- Currently requires GPU access and CUDA
- Python 3.69, and there may be critical differences with respect to other python versions
- Biopython 1.76
- Pytorch 1.3.0
- Numpy 1.18.1

Run: loads the read datasets, randomly chooses a 25% validation set and evaluates performance, printing accuracy results

python3 check_inference.py
