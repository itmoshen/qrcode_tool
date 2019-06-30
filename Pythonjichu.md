# Python基础

### pyinstaller

将Python脚本打包为exe可执行文件，以方便部署在其他电脑上运行，常用用法：

```
pyinstaller -F -i 图标路径 Python源文件路径
(参数说明：-F表示生成单个可执行文件，-i表示设置可执行文件图标，-w表示不显示控制台窗口)
```



### pip包管理器常用用法

pip install 包名    # 安装指定的第三方包（从国外官方服务器上下载）

pip install 包名 -i https://pypi.douban.com/simple    # 安装指定的第三方包（从国内豆瓣镜像服务器上下载）

pip uninstall 包名    # 卸载某个包

pip list    # 显示所有已经安装的包



### 模块和包

模块(Module)：就是一个Python源文件，模块可以被直接运行，还可以被其他模块调用

包(Package)：就是一个文件夹，用来存放若干个模块，解决模块命名冲突问题，为了和普通文件夹区分开来，规范的做法是在包下面创建一个_ __init_ _ _.py文件



