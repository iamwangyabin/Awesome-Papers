


> Written with [StackEdit](https://stackedit.io/).

#  Pop-up SLAM: Semantic Monocular Plane SLAM for Low-texture Environments

[paper here](https://arxiv.org/pdf/1703.07334.pdf)  
这篇论文是planslam一种．

文章基于LSD SLAM算法进行的工作．LSD SLAM是一个半直接法的slam框架．

LSD: A fast line segment detector with a false detection control－－用来探测墙壁的线边缘
文章在此基础上提出新方法剔除噪声更加好的分割结果．
这篇论文用因子图来同时优化地面和墙壁两个平面．


＿＿＿＿＿＿＿＿＿＿
剩下还没看，初读起来想法还比较有意思
从效果上来看主要有个问题，就是他们用的检测测算法对房间空旷有比较高的要求，看来不是一般场景能够使用．
能否用深度学习来估算出来整个房间布局？
查一下２０１８cvpr就有了LayoutNet.......真是能想到的都被做过了
不过他们的结果其实不是很好，但是其堪堪可用了．
还有种优化方法：
[How we use Convolutional Neural Networks to estimate the layout of a room](https://www.digitalbridge.com/blog/how-we-use-convolutional-neural-networks-to-estimate-the-layout-of-a-room)
这个室内场景数据集倒是也不错：
**SUN RGB-D: A RGB-D Scene Understanding Benchmark Suite**
