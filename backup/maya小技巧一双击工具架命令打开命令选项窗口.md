我们知道在maya中，选择菜单命令时同时按住Ctrl+Shift可以将当前选择命令加入工具架，但是有一些命令有一些选项窗口，以绑定为例，常用的调整骨骼轴向，镜像权重等，加入工具架并不能做到很方便的调出这些命令的选项窗口，可以额外简单设置一下，以调整骨骼轴向为例，命令为

`OrientJoint;`

我们只需要在命令后面加上Options即可，也就是变成

`OrientJointOptions;`

然后将上面命令配置到双击Double Click Command下即可，如下图所示：

![shelfTips](https://github.com/mxyblog/mxyblog.github.io/assets/32597778/673aeea3-3611-4250-b83d-622ff209c778)

可以依葫芦画瓢，本办法适合大多数有选项窗口的菜单命令
