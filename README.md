# computer_english
English of computer technology

# CSS
1. transition: 过渡效果
   * property ：css属性的名称
   * duration ：多长时间完成
   * timing-function：转速曲线
   * delay：开始的时候
2. transform: 应用于元素的2D或3D转换。这个属性允许你将元素旋转，缩放，移动，倾斜等
   * 旋转：rotate
   * 缩放：scale
   * 移动：translate
   * 倾斜：skew
   * 矩阵: matrix
3. animate: 动画效果
   * name ：定义的名称
   * duration ：多长时间完成
   * delay ：开始前多长的延迟
   * iteration-count：播放几次
   * direction ：指定是否应该轮流反向播放动画
   * fill-mode：结束的状态
   * play-state：指定动画是否正在运行或已暂停
4. transform-origin: 对元素进行基点位置改变 (transform-origin: x-axis y-axis z-axis)
5. transform-style： 规定被嵌套元素如何在 3D 空间中显示
6. perspective： 规定 3D 元素的透视效果
7. perspective-origin： 规定 3D 元素的底部位置
8. backface-visibility： 定义元素在不面对屏幕时是否可见
9. @keyframes myfirst /*定义动画名*/
   ```
    {
      0%   {background:red; left:0px; top:0px;} /*定义起始帧样式，0%可以换成from*/
      25%  {background:yellow; left:200px; top:0px;}
      50%  {background:blue; left:200px; top:200px;}
      75%  {background:green; left:0px; top:200px;}
      100% {background:red; left:0px; top:0px;} /*定义结束帧样式，100%可以换成to*/
    }
    ```
