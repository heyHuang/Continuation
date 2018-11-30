# Continuation
### 含义
**官方解释**     
https://en.wikipedia.org/wiki/Continuation  
**硬核解释**    
传统上， continuation（继续）被定义为一个函数，它代表 "计算剩余的部分" 或者 "接下来要做的事"。  
**三明治解释**   
假设你在厨房里的冰箱前面，正打算做一个三明治。这时你获取一个Continuation放进兜里。然后从冰箱拿了些火鸡和面包做了个三明治，放在了桌子上。现在调用兜里的那个Continuation，你会发现你又站在了冰箱前，正打算做个三明治。但这时桌子上已经有个三明治了，而且火鸡和面包也不见了。于是你吃掉了三明治。  
**抽象解释** 
 一旦我们得到了当前的 continuation 并将它保存在某处，我们就最终将程序当前的状态保存了下来。一个 continuation 对象里保存了从我们获得它的地方重新启动程序的必要信息。当你用这个 continuation “重启”程序时，就会转回到你取得这个对象的那个状态。  
**网络解释**
https://www.kancloud.cn/kancloud/functional-programm-for-rest/56928  


[知识点整理](https://github.com/heyHuang/Continuation/issues/1)  

[CPS和JavaScript](https://github.com/heyHuang/Continuation/issues/3)

[延续和回调的区别](https://github.com/heyHuang/Continuation/issues/4) 


# CPS转换工具
1、BYvoid/Continuation.js  ——解决JavaScript的异步难题  
2、dai-shi/continuation.js  
3、jlongster/unwinder   

