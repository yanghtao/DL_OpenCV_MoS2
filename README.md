# DL_OpenCV_MoS2
MoS2因其优异的光电性能在近年来被研究者们广泛关注，而对于低维MoS2，其独特的能带结构(单层MoS2具有直接带隙，多层则具有间接带隙)使得研究者们在做深入研究时需要对其厚度进行表征，而目前制备层状MoS2的方法大多为机械剥离和CVD等，这些方法在制备的MoS2都具有分布不均匀且厚度难确定的特点，研究者们在研究其性能时，进行表征的过程耗时耗力，因此，我们通过深度学习算法，来进行机器自动识别
厚度信息，以减轻研究者们的工作量，促进研究进程。此外，最近有研究者发现CVD制备的MoS2其因单双层的扭角不同，会使得其性能发生改变，因此，我们在语义分割网络模型识别得到厚度的基础上，通过OpenCV图像处理算法，对MoS2样品进行自动检测其厚度，面积和扭角等信息。

# 安装环境
python == 3.8
pytorch == 1.10.1
opencv-python == 4.5.6
其余安装包可参考```requearst.txt```文件

# 代码模块介绍
为了方便大家使用我们提供的代码去自己制作数据集进行训练，或复现我们的实验，这里我们将整个语义分割所需的全部流程都进行详细说明，在此，仅简单介绍各模块的功能，具体如何使用，可产靠各模块内部的ReadMe文件，且结合文章的附录部分。
