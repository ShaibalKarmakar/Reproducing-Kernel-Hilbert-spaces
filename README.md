# Reproducing-Kernel-Hilbert-spaces
Exploiting the kernel trick
RKHS.py creates a RKHS kernel induced by a positive definite matrix.

RKHS.ipynb 
demonstrates how the kernel trick works in the case of soft SVM-classifier.
The code is written in pytorch and can be easily adapted to use GPU if needed. (Use a variable, say "device" and set the necessary tensors to 'cuda').
Pytorch is used to perform the gradient descent step using Adam optimizer.
