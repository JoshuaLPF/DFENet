# DFENet
## Deep Fourier-embedded Network for Bi-modal Salient Object Detection
- **April 29, 2024**  
  The paper is undergoing peer review. The code will be released upon acceptance of the paper.
- In this project, we rethink the acquisition of long-range dependencies in bi-modal salient object detection (BSOD). Inspired by the efficient global representation of fast Fourier transform (FFT), we propose the deep Fourier-embedded network (DFENet), a purely FFT-based model aimed at achieving global relationship alignment in each stage while minimizing memory consumption and complexity, outperforming existing state-of-the-art (SOTA) BSOD models on four RGB-T BSOD benchmark datasets. **To the best of our knowledge, this is the first Fourier-based supervised model in a series of salient object detection tasks.**

## Requirements

List of prerequisites or required libraries for the project to run:

- Pytorch 2.0.0
- Cuda 11.8
- Python 3.8 or higher
- tensorboardX
- opencv-python
- timm == 0.5.4
- thop
- numpy

## Datasets
- VT821, VT1000, VT5000: Baidu cloud disk [link](https://pan.baidu.com/s/1Vv6mYz4RL2VnwWwZWKLHyA), fetch code (djas); 
- VI-RGBT1500: [link](https://github.com/huanglm-me/VI-RGBT1500)
## Pertrain Models

|          |Params(M)| FLOPs(G)| Input size |  Backbone   |      |
|----------|---------|---------|------------|-------------|------|
| DFENet-m | 149.2   |  139.7  |  384x384   | CDFFormer-m | [link](https://pan.baidu.com/s/1j_u9YGr-9zwNOJHJ9WCuqQ), fetch code(kbpy) |
| DFENet-b | 264.6   |  238.0  |  384x384   | CDFFormer-b | [link](https://pan.baidu.com/s/1S23SqxzzsNj-39nkaxb7xA), fetch code(eysg) |
| DFENet-h | 149.8   |  248.3  |  512x512   | CDFFormer-m | [link](https://pan.baidu.com/s/1kaJ4ukqcfhdoq1wvq9EDeQ), fetch code(ph20) |

## Results
The results of our DFENets (-m, -h, and -b) can be found at [link](https://pan.baidu.com/s/19aWbiGBD6AqWrP0e_PwYWw), fetch code(1ryz).

## Evaluation Metrics Toolbox
- The Evaluation Metrics Toolbox is available here: [link](https://github.com/jiwei0921/Saliency-Evaluation-Toolbox).

## Acknowledgements
- Thanks to all the seniors who put in the effort.

## Contact Us
If you have any questions, please contact us ( lvpengfei1995@163.com ).
