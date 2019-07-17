# 移动图层

你可以通过选中图层后拖动鼠标来移动图层,还可以通过在移动是按住**Shift**键来限制选中的图层只能沿横向或者纵向移动。

当你移动（或者调节大小）指定图层时，Sketch会自动将当前图层与其他图层做对齐操作，如果Sketch没有自动对齐，可能是你隐藏了[辅助线](https://www.sketch.com/docs/canvas/measuring/)。你可以通过菜单栏中的如下操作**View>Canvas>Show All Guides**来显示辅助线。

如果你按住了Option键然后拖动图层，会复制一个图层拖动，原始的图层任留在原地。如果再按下**Command+D**键，Sketch会以复制一个新的图层放置在与拖动图层相同便宜距离的地方。

## 移动被遮盖的图层

另外一个需要注意的问题是移动被遮盖住的图层。通常情况下，当你点击并拖动操作，相应的图层就会马上选中并且跟随拖动移动到一个新的位置。

正常条件下，这非常方便，但是这也可能会造成一个隐藏的问题，就是如果一个图层A完全被另一个图层B盖住。如果想拖动图层A,每次点选图层A都会操作成选中图层B，解决这个问题可以通过按住**Option + Command**键然后通过图层列表选中指定图层，最后拖动即可：

![](https://www.sketch.com/images/pages/docs/03-layer-basics/video/move-altcmd@2x.mp4)

## 对齐图层

为了快速移动选中的图层，你可以通过属性框右上区域的对齐按钮来对图层做对齐平分操作：

![](https://www.sketch.com/images/pages/docs/03-layer-basics/align.jpg)

如上图所示，左边的最开始的两个按钮用来做水平分布<svg xmlns="http://www.w3.org/2000/svg" width="31" height="17" viewBox="0 0 17 17">  <g fill-rule="evenodd">    <rect width="1" height="13" x="2" y="2" rx=".5"></rect>    <rect width="1" height="13" x="14" y="2" rx=".5"></rect>    <path fill-opacity=".35" stroke="#000" d="M7.25,4.5 L9.75,4.5 C10.1642136,4.5 10.5,4.83578644 10.5,5.25 L10.5,11.75 C10.5,12.1642136 10.1642136,12.5 9.75,12.5 L7.25,12.5 C6.83578644,12.5 6.5,12.1642136 6.5,11.75 L6.5,5.25 C6.5,4.83578644 6.83578644,4.5 7.25,4.5 Z"></path>  </g></svg> 和垂直分布<svg xmlns="http://www.w3.org/2000/svg" width="31" height="17" viewBox="0 0 17 17">  <g fill-rule="evenodd" transform="rotate(90 8.5 8.5)">    <rect width="1" height="13" x="2" y="2" rx=".5"></rect>    <rect width="1" height="13" x="14" y="2" rx=".5"></rect>    <path fill-opacity=".35" stroke="#000" d="M7.25,4.5 L9.75,4.5 C10.1642136,4.5 10.5,4.83578644 10.5,5.25 L10.5,11.75 C10.5,12.1642136 10.1642136,12.5 9.75,12.5 L7.25,12.5 C6.83578644,12.5 6.5,12.1642136 6.5,11.75 L6.5,5.25 C6.5,4.83578644 6.83578644,4.5 7.25,4.5 Z"></path>  </g></svg>。你还可以通过**Arrange>Distribute Objects**菜单选项或者快捷键**Control-Command-V**或者**Control-Command-H**来完成同样的操作。如果你想设置指定的间距来平分可以通过[Make Grid](https://www.sketch.com/docs/canvas/rulers-guides-grids/#make-grid)工具来设置。这个工具将[pixel fitting](https://www.sketch.com/docs/preferences/layers/#pixel-fitting)也会作为计算是的最终的尺寸尽可能的精确。

紧接着的六个按钮（左对齐<svg xmlns="http://www.w3.org/2000/svg" width="31" height="17" viewBox="0 0 17 17">  <g fill-rule="evenodd">    <rect width="1" height="13" x="2" y="2" rx=".5"></rect>    <rect width="9" height="4" x="4.5" y="6.5" fill-opacity=".35" stroke="#000" rx=".25"></rect>  </g></svg>，水平居中<svg xmlns="http://www.w3.org/2000/svg" width="31" height="17" viewBox="0 0 17 17"><g fill-rule="evenodd"><path d="M9,6 L8,6 L8,2.5 C8,2.22385763 8.22385763,2 8.5,2 C8.77614237,2 9,2.22385763 9,2.5 L9,6 Z M9,11 L9,14.5 C9,14.7761424 8.77614237,15 8.5,15 C8.22385763,15 8,14.7761424 8,14.5 L8,11 L9,11 Z"></path><rect width="10" height="4" x="3.5" y="6.5" fill-opacity=".35" stroke="#000" rx=".25"></rect></g></svg>，右对齐<svg xmlns="http://www.w3.org/2000/svg" width="31" height="17" viewBox="0 0 17 17">  <g fill-rule="evenodd" transform="matrix(-1 0 0 1 17 0)">    <rect width="1" height="13" x="2" y="2" rx=".5"></rect>    <rect width="9" height="4" x="4.5" y="6.5" fill-opacity=".35" stroke="#000" rx=".25"></rect>  </g></svg>，顶部对齐<svg xmlns="http://www.w3.org/2000/svg" width="31" height="17" viewBox="0 0 17 17">  <g fill-rule="evenodd" transform="rotate(90 8.5 8.5)">    <rect width="1" height="13" x="2" y="2" rx=".5"></rect>    <rect width="9" height="4" x="4.5" y="6.5" fill-opacity=".35" stroke="#000" rx=".25"></rect>  </g></svg>，垂直居中<svg xmlns="http://www.w3.org/2000/svg" width="31" height="17" viewBox="0 0 17 17">  <g fill-rule="evenodd" transform="rotate(90 8.5 8.5)">    <path d="M9,6 L8,6 L8,2.5 C8,2.22385763 8.22385763,2 8.5,2 C8.77614237,2 9,2.22385763 9,2.5 L9,6 Z M9,11 L9,14.5 C9,14.7761424 8.77614237,15 8.5,15 C8.22385763,15 8,14.7761424 8,14.5 L8,11 L9,11 Z"></path>    <rect width="10" height="4" x="3.5" y="6.5" fill-opacity=".35" stroke="#000" rx=".25"></rect>  </g></svg>，和底部对齐<svg xmlns="http://www.w3.org/2000/svg" width="31" height="17" viewBox="0 0 17 17"><g fill-rule="evenodd" transform="matrix(0 -1 -1 0 17 17)"><rect width="1" height="13" x="2" y="2" rx=".5"></rect><rect width="9" height="4" x="4.5" y="6.5" fill-opacity=".35" stroke="#000" rx=".25"></rect></g></svg>）是用来做图层的对齐操作的。

当多个图层同时被选中时，在MacBook Pro的Touch Bar上如下分布和对齐的快捷操作按钮

![](https://www.sketch.com/images/pages/docs/touchbar/tb-align.jpg)

如果你想将图层与画板做对齐，只需要按住**Option**键然后点击对应的对齐按钮就可以了。同理可应用与多个图层被选中的情况，还有一种方法是通过组合多个图层然后再操作组合的对齐。

如果需要与指定的对象来对齐图层，首先要通过锁定按钮<svg width="17" height="17" viewBox="0 0 17 17" xmlns="http://www.w3.org/2000/svg">    <g fill-rule="evenodd" transform="translate(4 2)">        <path fill-rule="nonzero" d="M2,6 L7,6 L7,3.5 C7,2.12168932 5.87918071,1 4.5,1 C3.12168932,1 2,2.12081929 2,3.5 L2,6 Z M1,3.5 C1,1.56700338 2.57093664,0 4.5,0 C6.43299662,0 8,1.57093664 8,3.5 L8,7 L1,7 L1,3.5 Z"></path>        <rect width="7" height="5" x="1" y="7" fill-opacity=".35"></rect>        <path fill-rule="nonzero" d="M8.0021643,12 C8.00074743,11.9999989 8.00002599,10.3343086 8,7.00292933 C8,7.00208098 5.66594523,7.00110454 0.9978357,7 C0.999252574,7.00000114 0.999974007,8.66569137 1,11.9970707 C1,11.997919 3.33405477,11.9988955 8.0021643,12 Z M0,7.00292933 C0,6.44902676 0.446311399,6 0.997544646,6 L8.00245535,6 C8.55338405,6 9,6.43788135 9,7.00292933 L9,11.9970707 C9,12.5509732 8.5536886,13 8.00245535,13 L0.997544646,13 C0.446615951,13 0,12.5621186 0,11.9970707 L0,7.00292933 Z"></path>    </g></svg>锁定图层列表中的对齐图层（或者通过**Shift-Command-L**快捷键）。如果未锁定指定的对象，Sketch会默认外层的图层作为对齐标准。


## 通过智能分布来移动多个图层

通过智能分布你可以水平或垂直平分多个图层。通过选择两个或者多个图层然后点击并拖动图层间出现的句柄。

如果你选择的图层分布是不均匀的，智能分布将根据你选择句柄所属图层间的空间均等分布。

> 注意：在Sketch 55中，智能分布仅一次应用于一个方向（水平或垂直间距）。

