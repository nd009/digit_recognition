# 机器学习工程师纳米学位
# 深度学习
## 项目：搭建一个数字识别项目

### 安装

这个项目要求使用 **Keras** 完成。因此你需要安装下面这些 Python 包：

- [NumPy](http://www.numpy.org/)
- [TensorFlow](http://tensorflow.org)
- [Keras](https://keras.io)

你同样需要安装 [Jupyter Notebook](https://jupyter.org/install.html).

除了上面提到的，对于那些希望额外使用图像处理功能的，你可能需要安装下面的软件：

- [OpenCV](http://opencv.org/)

#### OpenCV

如果你还没有安装 Python，优达学城推荐学生安装 [Anaconda](http://continuum.io/downloads) 这是一个已经打包好的 Python 发行版，它包含了我们这个项目需要的所有的库和软件。然后`OpenCV`可以通过下列命令安装：

```bash
conda install -c menpo opencv3
```

### 代码

初始代码包含在`digit_recognition.ipynb`这个notebook文件中。为了完成项目，你需要在notebook中实现基本的功能并回答关于你的实现和结果的问题。

### 运行

在命令行中，确保当前目录为 `digit_recognition/` 文件夹的最顶层（目录包含本 README 文件），运行下列命令：

```bash
jupyter notebook digit_recognition.ipynb
```

这会启动 Jupyter Notebook 并把项目文件打开在你的浏览器中。
