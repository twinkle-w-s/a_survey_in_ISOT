# A_survey_in_ISOT
This paper mainly reviews the development of infrared small target tracking after 2010, which has mainly gone through three stages: traditional methods, correlation filtering, and deep learning related methods.

这里主要梳理了从10年之后的红外小目标跟踪领域的发展，经历了传统方法、相关滤波、深度学习相关方法三个阶段。
# Papers
## Some tranditional methods
* Algorithms for optical weak small targets detection and tracking: review[[Paper]]一篇关于小目标跟踪的综述，比较老2003年的
### TBD(Track-before-detect)
* Detecting-and-tracking-dim-moving-point-target-in-Infrared[[Paper]](https://www.sciencedirect.com/science/article/abs/pii/S1350449504000878)
* Infrared small target detection based on sparse representation[[Paper]](http://journal.sitp.ac.cn/hwyhmb/hwyhmben/article/abstract/100359)
* A Modified Dynamic Programming Approach for Dim Target Detection and Tracking[[Paper]](https://ieeexplore.ieee.org/abstract/document/5300953)动态规划在TBD上的改进
### PF(Particle Filter)
* 新遗传粒子滤波的红外弱小目标跟踪与检测[[Paper]](https://journal.xidian.edu.cn/xdxb/EN/abstract/abstract11005.shtml)
* An Intelligent Particle Filter for Infrared Dim Small Target Detection and Tracking[[Paper]](https://ieeexplore.ieee.org/abstract/document/9761758)

### MS(Mean Shift)
* Tracking of infrared small-target based on improved Mean-Shift algorithm[Paper]
* Small Target Tracking Based on Histogram Interpolation Mean Shift[[Paper]](https://jeit.ac.cn/en/article/doi/10.3724/SP.J.1146.2009.01245)
* A mean shift algorithm based on modified Parzen window for small target tracking[[paper]](https://ieeexplore.ieee.org/document/5495375)这是小目标的
## Correlation filter
* Dim and Small Target Detection Based on Improved Spatio-Temporal Filtering[paper](https://ieeexplore.ieee.org/document/9580632?denied=)
* AutoTrack: Towards High-Performance Visual Tracking for UAV With Automatic Spatio-Temporal Regularization[[paper]](https://openaccess.thecvf.com/content_CVPR_2020/html/Li_AutoTrack_Towards_High-Performance_Visual_Tracking_for_UAV_With_Automatic_Spatio-Temporal_CVPR_2020_paper.html)
* Evaluation of Feature Channels for Correlation-Filter-Based Visual Object Tracking in Infrared Spectrum[[paper]](https://www.cv-foundation.org/openaccess/content_cvpr_2016_workshops/w9/html/Gundogdu_Evaluation_of_Feature_CVPR_2016_paper.html)
* Infrared Dim-Small Target Tracking Based on Guide Filter and Spatiotemporal Context Learning
* Infrared dim target tracking based on guide filter and Bayes classification[[Paper]](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/10157/101573I/Infrared-dim-target-tracking-based-on-guide-filter-and-Bayes/10.1117/12.2247411.short)
* IRSDT: A framework for infrared small target tracking with enhanced detection[[paper]](https://www.mdpi.com/1424-8220/23/9/4240)
### KCF
* Infrared dim-small target tracking via singular value decomposition and improved Kernelized correlation filter[[Paper]](https://www.sciencedirect.com/science/article/pii/S1350449516304832)
* Real-time detection and tracking of infrared small targets based on grid fast density peaks searching and improved KCF[[paper]](https://www.sciencedirect.com/science/article/pii/S1350449522001621)
* Fast and Robust Infrared Image Small Target Detection Based on the Convolution of Layered Gradient Kernel[[Paper]](https://ieeexplore.ieee.org/document/9454439?denied=)
### SRDCF
* STRCFD: Small Maneuvering Object Tracking via Improved STRCF and Redetection in Near Infrared Videos[[Paper]](https://ieeexplore.ieee.org/abstract/document/10379631)
### Correlation filter with DL methods
* Deep convolutional neural networks for thermal infrared object tracking[[paper]](https://www.sciencedirect.com/science/article/pii/S0950705117303544)
## DL methods

### Siamese method
* Infrared small target tracking based on an improved SiamRPN[[Paper]](https://www.sciencedirect.com/science/article/pii/S135044952300378X)
### Transformer method
# Datasets
* AntiUAV-410[[Link]](https://github.com/HwangBo94/Anti-UAV410/tree/main/reports/AntiUAV410)
