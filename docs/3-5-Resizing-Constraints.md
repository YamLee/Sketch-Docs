# 约束调节

约束是用来约定当Artboard,Symbol或者组调整大小时，其内部图层的调整策略的。

举个例子，当你想调整Artboard或者Symbol对象的长宽时，不管最后调整多宽多高，你总是要让指定的某个图层始终处于中间或者左上角的位置，这时，你就可以通过约束来实现这种效果。

![](https://www.sketch.com/images/pages/docs/03-layer-basics/video/constraints@2x.mp4)

## 应用约束

约束可以应用于任何在Artboard或者组中的图层。当容器中的图层被选中时，你可以在图层的属性编辑框中找到约束的设置区域。这个设置区域可以来设置图层当父容器调整大小时，图层自身调整的具体策略。

![](https://www.sketch.com/images/pages/docs/02-the-interface/constraints.jpg)

如上图所示，设置分为三个部分：在左边部分，你可以定义图层应该固定在哪一边；在中间部分，你可以定义图层跟着父容器一起缩放还是设置成固定的宽高；在右边部分可以用来预览效果，当父容器调整大小时图层（绿色部分）是如何改变的。

默认情况下，Sketch不会给图层添加任何约束。这时，你调整组的大小，组中的图层是跟着父容器一起调整的。

![](https://www.sketch.com/images/pages/docs/03-layer-basics/video/before@2x.mp4)

然而，当你添加约束，将图层左右两边都相对父容器固定，这时候父容器拉伸时，里面被约束的图层在拉伸时左右两边边距就会固定距离，间距不会随着父容器的变化而改变。

![](https://www.sketch.com/images/pages/docs/03-layer-basics/video/after@2x.mp4)

如果你想查看如何在缩放Artboard时调整其内部的约束，可以在Artboard编辑器查看[Adjust Content on resize](https://www.sketch.com/docs/grouping/artboards/#resizing-artboards)选项。


## 案例

如下为一些约束应用的使用场景

### 边缘固定

当需要处理一些通用的界面元素，如导航栏或者tab bar等，如下图所示，你只想横向的拉伸，不改变高度。这种场景的约束应用很简单：只需要设置成固定高度即可。

![](https://www.sketch.com/images/pages/docs/03-layer-basics/video/fix@2x.mp4)

![](https://www.sketch.com/images/pages/docs/03-layer-basics/fix-to-edge.jpg)

你可能会问为什么这里不需要约束固定左右边：因为Sketch默认是将父容器及容器内的图层包括图层间的距离等等一起拉伸的。但是上面的例子中内部图层与父容器边缘没有距离，因此父容器宽度增加，也不会改变内部图层的间距大小。

### 角位置固定

如果与上面的场景不一样，你想要图层固定在父容器的某个位置，但又需要跟父容器有固定的间距，这时，你可以通过固定边缘的约束来实现。如下图所示，当需要将一个icon放到导航栏或者放置一个浮动按钮到指定的左上角时，通过设置固定左边缘和上边缘，然后设置固定高度和宽度，这样当父容器拉伸时，icon始终处在左上角固定位置。

![](https://www.sketch.com/images/pages/docs/03-layer-basics/video/pin-to-corner@2x.mp4)

![](https://www.sketch.com/images/pages/docs/03-layer-basics/pin-to-corner.jpg)

###  固定位置和固定间距

加入你想让一个icon在父容器缩放时，始终保持固定大小，并且保持icon处于居中的位置，你只需要固定好高度和宽度约束，这样icon在父容器缩放时长宽不会改变，只会变相对于父容器的间距，从而保证icon始终处于中间位置。

![](https://www.sketch.com/images/pages/docs/03-layer-basics/video/float@2x.mp4)

![](https://www.sketch.com/images/pages/docs/03-layer-basics/float.jpg)

相反，如果你想固定icon的上下左右边距，icon的宽高随着父容器拉伸也跟着拉伸，你只需要点击固定设置的中间按钮，这样默认四个边就都设置成固定的了。

![](https://www.sketch.com/images/pages/docs/03-layer-basics/video/padding@2x.mp4)

![](https://www.sketch.com/images/pages/docs/03-layer-basics/fix-padding.jpg)


如果你想看Symbol的约束调节相关的实例，可以尝试官方的iOS Design Resources Library，然后通过缩放指定的Symbol来看效果。

