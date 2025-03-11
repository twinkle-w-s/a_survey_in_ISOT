# Dataset in the field of infrared small targets tracking
Two classic datasets are presented here
这里介绍了两个经典数据集

## Infrared image weak aircraft target detection and tracking dataset in ground_space background & semi-simulation dataset for infrared weak moving target detection in complex background
## olddataset[[Link]](https://pan.baidu.com/s/1Gcvt7R6LMZSZb6gw6QMoGw?pwd=1111)
## 地_空背景下红外图像弱小飞机目标检测跟踪数据集&&复杂背景下红外弱小运动目标检测半仿真数据集

We use the former as the test set and the latter as the training set. At the same time, the multi-target sequence in the original dataset is removed.

我们使用前者作为测试集，后者作为训练集。同时去除了原数据集中多目标的序列。


The test dataset consists of 22 data segments with an average of 735 frames per segment and image pixels of 256*256 pixels. It was captured with a 2-axis electronically controlled rotary table located in a high tower, and included single-target sky background, two-target cross-flight sky background, single-target complex ground background, target from far away to near, target from near to far, target out of the field of view, and target back into the field of view. Difficulties in the dataset include large target signal change (SCR), target tracking in long sequence images (LST), Multi-Target Interference Tracking (MIT), and Weak Target Detection in Complex Environment (WTD). The even distribution of these difficulties in the dataset helps the training set to better simulate the challenges faced by target tracking in real application scenarios.

测试数据集由22个数据段组成，每个数据段平均有735帧，图像像素为256*256像素。它是通过位于高塔中的2轴电子控制转台捕获的，包括单目标天空背景、双目标交叉飞行天空背景、单目标复杂地面背景、目标从远到近、目标从近到远、目标离开视野以及目标重新进入视野。数据集中的难点包括大目标信号变化（SCR）、长序列图像中的目标跟踪（LST）、多目标干扰跟踪（MIT）以及复杂环境中的弱目标检测（WTD）。这些难点在数据集中的均匀分布有助于训练集更好地模拟实际应用场景中目标跟踪面临的挑战。

The train dataset consists of 350 sequences containing 150 segments for single targets, 100 segments for double targets, and 100 segments for triple targets, with sequence lengths between 300 and 1000 frames and an image resolution of 640*512 pixels. The images were captured using an uncooled vanadium oxide microbolometer with a capture frame rate of 30 HZ. The dataset was captured on a sunny, cloudy day and contains five backgrounds: elevation, plan view, top view of vegetation, top view of water, and top view of buildings. The special feature of this dataset is the use of small targets embedded in the background for semi-simulation.

训练数据集由350个序列组成，包含150个单目标片段、100个双目标片段和100个三目标片段，序列长度在300到1000帧之间，图像分辨率为640*512像素。图像是使用非制冷氧化钒微测辐射热计以30 HZ的帧率捕获的。数据集在晴天和阴天捕获，包含五种背景：仰视图、平面图、植被俯视图、水面俯视图和建筑物俯视图。该数据集的特殊之处在于使用嵌入背景的小目标进行半仿真。

## Anti-UAV410 newdataset[[Link]]([https://pan.baidu.com/share/init?surl=2NRarQvIiyZKbXRu5fPGpw&pwd=a410](https://pan.baidu.com/s/1R-L9gKIRowMgjjt52n48-g?pwd=a410))
The Anti-UAV410 dataset consists of 200 training sequences, 90 validation sequence sets, and 120 test sequences. The average length of the sequences is 1069 frames. The pixels of the images are 640*512. Sequence scenes include two different lighting conditions (day and night), two seasons (fall and winter), and a wide range of backgrounds such as buildings (30%), mountains (20%), forests (5%), urban areas (30%), clouds (10%), water (3%), and so on. The captured video sequences were recorded in the mid-wave infrared spectrum at a frame rate of 25 frames per second (FPS). The Anti-UAV410 dataset shows a significant proportion of small targets, with more than half of the targets being less than 50 pixels in size, and even including a certain proportion of small targets (less than 10 pixels in size). At the same time, the length of the sequences is on the long side, which challenges the tracker to have robust target re-detection capabilities. The challenges of the dataset include: out of view (OV), partial overlap (OC), similar temperature (TC), fast (FM), scale variation (SV), and dynamic background blur (DBC). The three subsets are more evenly proportioned on each challenge attribute as the figure 5 shows, at which point the training set can be used to better understand the challenges of UAV tracking in field scenarios.

Anti-UAV410数据集由200个训练序列、90个验证序列集和120个测试序列组成。序列的平均长度为1069帧。图像的像素为640*512。序列场景包括两种不同的光照条件（白天和夜晚）、两个季节（秋季和冬季）以及广泛的背景，如建筑物（30%）、山脉（20%）、森林（5%）、城市区域（30%）、云层（10%）、水面（3%）等。捕获的视频序列以25帧每秒（FPS）的帧率记录在中波红外光谱中。Anti-UAV410数据集显示出显著比例的小目标，超过一半的目标小于50像素，甚至包括一定比例的小目标（小于10像素）。同时，序列的长度较长，这对跟踪器的目标重新检测能力提出了挑战。数据集的挑战包括：视野外（OV）、部分重叠（OC）、相似温度（TC）、快速（FM）、尺度变化（SV）和动态背景模糊（DBC）。如图5所示，三个子集在每个挑战属性上更加均匀分布，此时训练集可以更好地理解野外场景中无人机跟踪的挑战。


