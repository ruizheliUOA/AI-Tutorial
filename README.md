# AI-Tutorial

## 在自己的电脑上配置Python和Pytorch环境

### 安装Visual Studio Code
Visual Studio Code是一款轻量型且功能十分强大的代码编辑器，完美支持Python和Pytorch

1. 下载[VS Code客户端](https://code.visualstudio.com/Download)，根据操作系统选择对应版本的软件安装包。
2. 按照安装步骤完成安装

### 安装Miniconda
Miniconda可以帮助我们创造一个虚拟代码环境，在这个环境中我们可以安装各种项目所需要的代码库或文件包，而不会影响到操作系统中默认的代码环境。这样做的好处是，如果我们在虚拟环境中造成了任何错误，比如代码库版本冲突等，这些问题都不会影响到外部的操作系统环境，我们也就不需要重装系统来解决问题。

1. 下载[Miniconda](https://docs.conda.io/en/latest/miniconda.html)，选择对应操作系统版本的安装包进行安装
2. 安装成功后，打开操作系统命令行工具，输入一下命令:

`conda create -n myenv python=3.9`

`myenv`可以替换成你想起的虚拟环境名字，`python=3.9`可以替换成其他版本的python，比如`python=3.8`
