# AI
A

理论学习
机器学习入门推荐课程：
	吴恩达-机器学习 ：https://www.coursera.org/learn/machine-learning
	胡浩基-机器学习 ：https://www.bilibili.com/video/BV1VS4y1J7FX?p=1（哔哩哔哩）
https://classroom.zju.edu.cn/coursedetail?course_id=56213&tenant_code=112（智云课堂）
	其他课程资源
环境配置与工具安装
编程环境与工具
	Python拥有强大的数据处理和分析库，拥有丰富的开源库和框架，是机器学习最常用的编程语言。Python入门课程：https://cs50.harvard.edu/python/2022/
	Anaconda是一个用于科学计算的Python发行版，提供了包管理与环境管理的功能，可以很方便地解决多版本python并存、切换以及各种第三方包安装问题。
Anaconda安装教程：https://blog.csdn.net/fan18317517352/article/details/123035625（Windows版）、https://zhuanlan.zhihu.com/p/32925500（Mac和Linux版）
Python编辑器：Spyder、VS Code (Visual Studio Code)、PyCharm 、Jupyter Notebook、等，用于编写、调试和运行Python代码，通常与Anaconda一起提供，也可以自行下载。
	Spyder：https://github.com/spyder-ide/spyder/releases/latest/download/Spyder_64bit_full.exe
	VS Code：https://code.visualstudio.com/download
	PyCharm：https://www.jetbrains.com/pycharm/download/?section=windows
人工智能框架Pytorch、TensorFlow安装
Pytorch、TensorFlow都分为CPU版本和GPU版本，GPU版本运行速度更快，推荐安装GPU版本。
安装Pytorch、TensorFlow的GPU版本前需要进行CUDA、CUDA Toolkit、cuDNN安装（什么是CUDA、CUDAToolkit、cuDNN）。
CUDA、CUDA Toolkit、cuDNN安装：https://blog.csdn.net/weixin_58864560/article/details/124271279（若安装CPU版本，可忽略此步骤）
创建虚拟环境
为什么要创建虚拟环境
①	避免版本冲突：不同的深度学习框架和相关库通常依赖于不同的库和不同的版本。如果在全局环境中安装所有这些库，可能会导致版本冲突，使得不同的库之间无法正常协同工作。创建虚拟环境可以隔离不同项目所需的库，确保它们不会相互干扰。
②	管理依赖关系：深度学习项目通常需要大量的第三方库，包括不同版本的深度学习框架、数据处理库、可视化工具等。虚拟环境使你能够更轻松地管理这些依赖关系，而不会影响到其他项目。
③	简化维护：虚拟环境可以在项目之间隔离依赖关系，使得项目更容易维护和分享。当你需要共享项目或在不同环境中重复使用时，虚拟环境可以帮助你确保所有依赖项都正确安装。
④	防止污染系统环境：全局环境中的库和依赖项可能会对操作系统和其他应用程序产生不良影响。虚拟环境可以帮助防止系统环境被污染，使得系统更加稳定和可维护。
创建虚拟环境：
1.	进入AnacondaPrompt,创建一个环境：conda create -n name
name自取，例如：
conda create -n pytorch即为创建名为pytorch的虚拟环境，后续可以在这个虚拟环境里安装Pytorch、
conda create -n tensorflow即为创建名为tensorflow的虚拟环境，后续可以在这个虚拟环境里安装TensorFlow)
显示Proceed([y]/n)?输入y然后enter（回车）
2.进入环境：conda activate name
可以看到前面的(base)变成了(name)说明进入环境
更多操作请见Anaconda创建、切换、退出、删除虚拟环境
安装Pytorch
进入Pytorch官网：https://pytorch.org/get-started/locally/，选择平台和版本，得到安装的命令行。进入pytorch虚拟环境，运行命令行进行安装。
 

安装TensorFlow
进入tensorflow虚拟环境，运行pip install tensorflow命令行，即安装最新版本的TensorFlow。（https://www.tensorflow.org/install?hl=zh-cn）

机器学习实例学习与应用
Pytorch官方教程：https://pytorch.org/tutorials/beginner/basics/intro.html、https://github.com/pytorch/examples
TensorFlow官方教程：https://www.tensorflow.org/tutorials?hl=zh-cn
也可以自行搜索网络资源进行学习。

其他
Linux操作


