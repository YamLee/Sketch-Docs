# 属性编辑器（Inspector）

在Sketch右边的属性编辑框是用来编辑当前所选图层的各个属性或者所选工具的选项。当你在设计时选中指定的图层后，属性编辑框就会显示各个部分的属性内容。

属性编辑器中的属性不是所有都可见的，主要还是取决于你当前所选的图层的类型，以及图层是否被包含在Group或者Artboard中。属性编辑器中的各个部分可以折叠和展开。

## 对齐操作

在属性编辑框顶部是对图层做对齐操作的选项。当你选中一个或者多个图层时，这些button就会被激活。更多有关对齐操作的功能介绍可以参考[Moving Layers](https://www.sketch.com/docs/layer-basics/moving-layers/)

![](https://www.sketch.com/images/pages/docs/02-the-interface/align@2x.jpg)

## 图层属性

图层属性的编辑在属性编辑框的上边部分，其中包括了所选图层的属性选项，尺寸大小，旋转角度，翻转，还有特定图层的特定属性，例如修改多边形状的顶点数。

![](https://www.sketch.com/images/pages/docs/02-the-interface/general-attributes.jpg)

在高度和宽度编辑框中间有一个锁定按钮，点击此按钮会锁定图层的宽高编辑比例，也就是说按钮锁定的话，改变高度，宽度也会按比例改变。

当你编辑方形图层时，你可以通过设置Radius(圆角半径)为方形图层创建圆角，这个选项在 [round或smooth corners](https://www.sketch.com/docs/shapes#round-and-smooth-corners)中也适用。


## 编辑框

对应的属性编辑框中不是普通的文本。如果你将鼠标光标放到编辑框上边，这时在编辑框右边会出现一个上下的箭头，你可以点击上下箭头来增加或酱烧编辑框中的值。

如果你按住Shift键再点击上下箭头，Sketch会以10为单位来增加或减少，而不是以1为单位；按住Option键则又会以0.1为单位来增减。

![](https://www.sketch.com/images/pages/docs/02-the-interface/math.jpg)


### 上下按键操作

当你直接在编辑框中输入数值时，编辑框右边的上下按键就会消失，但是按键的功能任然存在，可以通过键盘上的上下按键来实现相同的功能，Shift和Option按住后操作也是一样的效果的

### 快速调节值

当编辑框选中后，移动鼠标光标到会出现一个左右方向的箭头，此时水平方向左右拖动可以快速增减编辑框中的值。有些编辑框是底部出现的左右方向箭头，此时拖动也能实现同样的效果。

同理按住Shift或Option按键能以10或0.1的增减来调整设置的值。

如果在设计中不能确定设置具体多少值，可以通过全速的拖动来试探，从而快速找出你想要的效果。

### 数值计算

在编辑框中另一个比较酷炫的功能是你可以在编辑框中直接对数值型的编辑框应用数学表达式来计算最终的结果。你可以做加减乘除，在某些情况下还可以通过百分比来调整数值。
举个例子，你可以在选择一个或者多个图层后在编辑数值的输入框是使用  ```+, –, \*,  /```来编辑。
你还可以对一组或artboard中的单个或多个对象的宽高进行百分比计算。Sketch按照最终计算的数值来放大或缩小对象。（如现在将一个宽度为960像素的图层设置宽度为10%那么Artboard会将图层宽度变为96像素）。

![](https://www.sketch.com/images/pages/docs/02-the-interface/video/operations@2x.mp4)

在设置方形圆角半径的输入框中可以单独设置各个角的圆角半径，通过**；**隔开（如：40;0;40;0）。

## Resizing

当你选中的图层是在Artboard或者组当中时，这个修改大小的编辑部分才会在属性编辑器中展示出来。这个功能是用来设置当Artboard或者组大小发生变化时对应的画布如何改变。

想要了解更多有关Resizing的信息，可以参考[Resizing Constraints](https://www.sketch.com/docs/layer-basics/constraints/)这个章节

## 外观和样式设置

图层的外观和样式设置可以在属性编辑框的这个部分调整，你可以设置填充色，边界线，阴影，和模糊度等样式属性。

所有的这些属性的设置可以通过创建一个[Shared Style](https://www.sketch.com/docs/styling/shared-styles)来保存样式。

要想新增图层的样式属性，可以通过点击属性标题右边的**+**按钮，如下图所示:

![](https://www.sketch.com/images/pages/docs/02-the-interface/style-properties.jpg)

当需要添加新的填充色，边界线颜色或者阴影时，会有一个颜色选择弹框来选择[color](https://www.sketch.com/docs/styling/color/):

![](https://www.sketch.com/images/pages/docs/02-the-interface/inspector-fill.jpg)

你可以通过勾选左边的勾选框来选择是否显示和隐藏当前样式。当有一个或多个边界线或阴影未选中时，可以通过删除按钮来删除为选中的属性设置。

![](https://www.sketch.com/images/pages/docs/02-the-interface/inspector-fill-remove.jpg)

同样设置模糊度时，也可以通过隐藏选框来选择隐藏或显示模糊度样式效果。你还可以设置模糊类型和模糊的半径。

## 导出

在样式设置块的下面是资源导出选项。在这里你可以将你设计的所有东西导出成图像文件。在标题的右边同样有一个**+**的按钮来选择导出的尺寸，类型等。更多有关导出的设置可以查看[这里](https://www.sketch.com/docs/exporting/)

![](https://www.sketch.com/images/pages/docs/02-the-interface/inspector-make-exportable.jpg)


