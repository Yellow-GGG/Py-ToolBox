# Py实用工具盒

## 欢迎

欢迎您使用Py实用工具盒！

这一工具盒原本是清华大学2022学年夏季学期课程“信息技术理论与实践”第01小组所完成的小组作业。但我们也期望它能够如同其标题一样，成为一个具有实用价值的项目。我们在这一工具盒中封装了许多有用或有趣的python脚本，希望它能够切实地对您有所帮助！

我们目前所提供的工具包括：

* 学堂自助
* 图像分切
* 文档词云
* 速速转码
* 格式快转
* 性能监控
* 快速水印

用户也可以自行编辑文件tools.py中的内容，以删除不必要的工具或封装自己所使用的脚本。这些工具的详情还请参考工具盒内部说明。

## 说明

本软件以源代码的形式发布，更适合于已安装Python环境的用户使用。我们也尝试过使用pyinstaller等方式进行打包，但封装后文件体积过大，远不能令人满意，遂就此作罢。想要使用本工具盒，可按照以下方式操作：

1. 从python.org中获取最新的Python运行环境

2. 从requirement.txt中安装所需的第三方库环境，请在“Py实用工具盒”文件夹中打开终端或PowerShell，输入以下指令

   ```
   pip install -r requirement.txt
   ```

   回车执行，即可完成环境安装。

3. 在“Py使用工具盒”这一文件夹中打开终端或PowerShell，输入指令

   ```
   python3 main.py
   ```

   回车执行，即可开始运行Py实用工具盒。

环境配置完成后，只需重复步骤3，即可方便地启用这一工具盒。

## 备注

本软件中部分代码为本小组成员自行开发，另一部分则来自网络，这些来源都已在软件中注明。我们对网络中参考的代码做了许多改编，使其更好地融入整体的GUI界面中。

最后，由于本小组成员少有开发经验，学习Python时间并不算长，因此在代码质量方面可能会有所欠缺。相信这一问题在未来会得到改善，但暂时还希望您能够谅解。