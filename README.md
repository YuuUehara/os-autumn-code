# Daily Schedule for OS Tutorial Summer of Code 2020

前面还有一堆的什么rust和操作系统的学习在这儿就省略了……毕竟加入的太晚，以后有空了填_(:з」∠)_

# 因为发现时间不行了再加上考试的复习任务就有段时间没做了……不过刚好开学了考试考完了这两天还能自己兴趣做下去（大概）
# 至少有始有终吧。

## Day-1 2020/7/23
### 环境配置
  其实WSL2以前装过的，但是不知道为啥我给卸了，可能是不怎么好用？不过这次就得重装了（悲）
  其实说起来rust倒是在windows下有着十分完整的工具链了……但是那个却确实是有操作系统依赖的，的确是不用为妙。
  基本上算是轻车熟路，以后感觉有条件应该尽量用WSL2环境
### Lab0
  其实主要就是环境的基本配置。基本毫无难度。
  
## Day0 2020/7/24
### Lab1
  Lab1其实本身实验难度并不算大，毕竟指导已经给的十分详细了。
  当然指导的代码也有一些小问题，比如handler.rs中use模块是严重不全的，不过这个其实很容易改。另一个是最后的描述问题，main()的修改事实上应该是将unreachable修改为loop从而满足基本语法要求。
  另外理论上context其实应该加上debug trait但是我这儿时间确实不大够就没加……有点卑微_(:з」∠)_
### Lab1-practice
  1.
    sp - 34 * 8
    在中断结束后才会完成恢复过程，中途是不会发生变化的。
  2.
    这样的程序是没有出口的，它是不会停下来的。
  3.
    实验代码待上传（这就是不常用GitHub的后果）
    
## Day1 2020/7/25
  今天才算是真正第一天开始的实验的日子……当然前面其实应该有Day0 Day-1之类的但是暂时没啥时间补上了有点心累…………
  这一天暂时完成的是完善了的Lab-2（Lab-1在这之前已经完成了），但是暂时还没有上传……
  当然，这一部分其实也真正是Day2写的（悲
  另外晚上看到了大家在群里的发言，确实大家特别强，怎么感觉我好像就有点像是纯属混入其中的鶸……
### Lab2
  

## Day2 2020/7/26
  这一天都在啃Lab3……Lab3开始感觉知识就有些跟不上了，赶得太紧果然不大好
### 顺便开了个跟我好像没太大关系的会
  探讨了下去深圳的条件和深圳的条件，但是好像和晚起步很久的我没有太大的关系，这太致命了（悲）
  其实要说那个Hackthon的形式我是真的很心动了。然而吧……然而吧。
### Lab3
  
