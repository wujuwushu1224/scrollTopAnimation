### 面试问题记录下
 Q:如何实现置顶时滚动条匀速向上，而不是直接到顶。
 
 A:jQuery的animation函数可以快速实现，原生JS需要切分出运动的时间间隔（我理解为就是动画帧），再通过setInterval去执行每一帧的运动距离，让其看起来是个连续的动画。
   
