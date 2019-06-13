# 图层列表框

图层列表框包含了当前编辑页中的所有图层。你可以在图层列表框中看到每一个图层的属性，例如图层的隐藏或者锁定，也可以通过重命名和排序来重新组织图层。


## 多页编辑

Sketch可以允许你在设计时使用多个界面，你可以通过在图层列表上的弹出菜单来进行页面的切换（你也可以通过Fn+ 上箭头/下箭头的快捷键来切换）。图层列表只会展示当前所选页面的所有图层。

![](https://www.sketch.com/images/pages/docs/02-the-interface/video/switcher@2x.mp4)

如果你想重新组织界面或者在各个界面中移动图层，可以如下操作显示界面列表窗口：

![](https://www.sketch.com/images/pages/docs/02-the-interface/video/page-list@2x.mp4)

点击添加按钮**+**可以新增界面。邮件选中的界面会有选择菜单弹出，选择菜单包括了复制当前界面和删除界面。

![](https://www.sketch.com/images/pages/docs/02-the-interface/page-list-menu.jpg)

你还可以拖动图层或者Artboard将其移动到另一个界面中，如果拖动是按住option键则会复制一份再移动到另一个界面中：

![](https://www.sketch.com/images/pages/docs/02-the-interface/video/page-list-drag@2x.mp4)

## 画板

[Artboards](https://www.sketch.com/docs/grouping/artboards/)的标题在图层列表中会以粗体字展示，并且带有特性的画板标志的图标。画板被列在图层列表的顶部，并且画板不能包含其他画板。

画板中选中图层的标题会被显示在图层列表的顶部，即便是当前画板中有很多图层可见。

## Masks

当图层是一个遮罩类型时，在图层标题前面会以一个小箭头的icon来表示。被标记成遮罩的图层与它下面的图层重叠的话就会形成裁剪，遮罩图层以外内容被裁减掉，然后剩下的内容与遮罩图层重叠。更多的Mask使用可以参考[如何使用蒙版](https://www.sketch.com/docs/shapes/masking/)

![](https://www.sketch.com/images/pages/docs/02-the-interface/masks.jpg)

## 合并操作

合并操作是用来将多个简单图层组合成复杂图形的一些列工具方法。组合后的复杂形状图层左边会有一个三角形指示，点击这个三角指示按钮会列出这个复杂图形的简单组合图形简称子路径，你可通过查看或编辑这个子路径再次调整复杂的组合图形。

合并操作刚开始理解起来有点困难，你可以[查看更多合并操作信息](https://www.sketch.com/docs/shapes/boolean-operations/)。

![](https://www.sketch.com/images/pages/docs/02-the-interface/boolean-operations.jpg)


## Symbols和样式分享

[Symbols](https://www.sketch.com/docs/symbols/)是图层的集合，可以当做中一种公共的设计组件，多个地方可以复用同一个Symbol。一个Symbol在图层列表框中不能展示它里面的层级，但是可以在画布中通过双击这个Symbol组件来进行编辑，或者[展开Symbole选择指定的图层](https://www.sketch.com/docs/symbols/overrides/#selecting-overrides)。

[Library Symbol](https://www.sketch.com/docs/libraries/library-symbols)是Symbol的另一种类型，它属于外部文件，也就是说可以为其他的项目引用。 与本地Symbol不同的是，当你双击然后编辑其内容时，它们所属的库也可以跟着修改的。

[共享样式](https://www.sketch.com/docs/styling/shared-styles/)用于在多个图层之间保持图层样式的一致，并且它们可以应用于形状和文本图层。 在Sketch中为了表示形状或文本图层使用了共享样式，其预览（图层列表标题左边的形状图）将以紫色显示，而不是通常的灰色。

![](https://www.sketch.com/images/pages/docs/02-the-interface/layers.jpg)



## 隐藏和锁定图层

画布中的任何图层或者组合对象都可以隐藏，你可以通过点击图层右边的眼睛按钮来控制隐藏或者显示（或者快捷键Shift-Cmd-H）。如果这个眼睛图片一直显示着则表示当前图层是隐藏的。

同样的，按住Option键然后光标停留在图层上，原先的眼睛按钮会变成锁定按钮，点击锁定按钮，当前的图层就会被锁定，既不能选中编辑也不能移动，要想操作需要再点击锁定按钮进行解锁。锁定图层的操作也可以通过快捷键（Shift-Cmd-L)来操作。

## 筛选图层

在图层列表框的底部有一个Filter字样的按钮编辑区域，这个地方可以用来过滤图层。如果想查找指定名称的图层，可以在filter输入框中直接输入图层的名字，匹配到的结果就会显示在图层列表中。

你也可以通过图层的类型来筛选图层。通过点击Filter图标，在弹出的菜单中选择想要筛选的图层类型，默认在未选指定类型的情况下是全部图层类型都显示。

![](https://www.sketch.com/images/pages/docs/02-the-interface/filter-options.jpg)


