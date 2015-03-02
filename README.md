# rem layout
移动端基于`rem`布局的`demo`页

页面布局计算的时候,比如设计稿为`640px`的宽度,那么计算的基数就是`640/16=40px`

一个`banner`宽度为`640px`的时候,对应的`rem`单位就是 `16rem`,无需考虑移动端各种屏幕大小

需要注意的是当像素在缩放情况下小于`1px`的时候,需要设置不同`devicePixelRatio`下对应的缩放大小,比如2倍屏设置`[data-dpr="2"] .demo{border:2px solid #ccc;}`,3倍屏类推.
