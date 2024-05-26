Inspired by @karpathy's several fantatic projects I wanted to create write something in C and CUDA for the first time in a while. As the name of the project may suggest, this is a pure C (later on AVX10 and CUDA) reimplementing a U-Net for semantic segmentation. I want to start with a basic Pytorch implementation as a benchmark (both CPU and GPU) and then develop a C version to try to improve the performance.

The code is a work in progress and will develop to include:
- [ ] Basic Python (Pytorch) training script of U-Net
- [ ] Basic Python (Pytorch) inference and benchmarking script
- [ ] C inference for single image
- [ ] C inference for batch of images
- [ ] AVX10 version of the above
- [ ] CUDA version of the above
- [ ] Training in pure C
- [ ] Training in AVX10
- [ ] Training in CUDA

