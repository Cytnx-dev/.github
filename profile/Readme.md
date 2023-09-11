## Cytnx:

**Cytnx** (pronounced as \textit{sci-tens}) is a library designed for Quantum/classical Physics simulations.


#### - Dual languages:
The library is built from bottom-up, with both C++ and Python in mind right at the beginning of development. That’s why nearly 95% of the APIs are exactly the same at both C++ and Python ends.

#### - User friendly APIs:
Most of Cytnx APIs share very similar interfaces as the most common and popular libraries: numpy/scipy/pytorch. This is specifically designed so as to reduce the learning curve for users. Furthermore, we implement these easy-to-use Python libraries interfacing to the C++ side in hope to benefit users who want to bring their Python programming experience to the C++ side and speed up their programs.


#### - Heterogeneous acceleration:
Cytnx also supports multi-devices (CPUs/GPUs) directly on the base container level. Especially, not only the container but also our linear algebra functions share the same APIs regardless of the devices where the input Tensors are stored, just like pytorch. This provides users the ability to accelerate the code without worrying too much about details of multi-device programming.

#### - Build TN Algorithm at ease: 
For algorithms in physics, Cytnx provides powerful tools such as UniTensor, Network, Bond, Symmetry etc. These objects are built on top of Tensor objects, specifically aiming to reduce the developing work of Tensor network algorithms by simplifying the user interfaces.


## User Guide:
    https://kaihsinwu.gitlab.io/Cytnx_doc/index.html


## API documentations:
    https://kaihsinwu.gitlab.io/cytnx_api/






