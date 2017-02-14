 FOLLOW A KUGOU
----------------


vuejs仿写酷狗音乐webapp
-----------------

更新日志：
> 2017/01/01：上一首，下一首功能<br>
> 2016/12/11：完成播放详情页面，进度条控制，歌词显示<br>
> 2016/11/22：导航栏透明渐变。<br>
> 2016/11/10：修改播放器样式，增加播放音乐时的loading状态<br>
> 2016/11/09：完成所有view级别组件<br>

[在线演示][1]<br>
[原站地址][2]<br>
[混合APP打包][5]

主要技术栈：
 - vuejs2.0
 - vue-router
 - vuex
 - vue-resource
 - mint-ui

由于本人的服务器有点渣，后台通过代理返回酷狗列表页这个阶段所需时间极不稳定，所以部分页面采用本地json模拟数据<br>
由于是单页应用，在路由切换时不会暂停音乐播放，是一个小亮点，也可以实现播放列表等功能，可能会加上。
本demo会长期更新，如果觉得还可以的话，给颗star吧。^9^


项目截图：
----
![](https://camo.githubusercontent.com/525779bffeee2a9b4baa49a01b3a0b90f7013b38/687474703a2f2f70312e6271696d672e636f6d2f3536373537312f336335613931333633343538383138322e706e67)<br><br>
![](https://camo.githubusercontent.com/816c9000aba59e5e2990679a669057add4a427d0/687474703a2f2f70312e6271696d672e636f6d2f3536373537312f393564386563613431623339666263662e706e67)<br><br>
![](https://camo.githubusercontent.com/ddd49b46980b5e8605eeb28c6a6eeaedc8405fa5/687474703a2f2f70312e6271696d672e636f6d2f3536373537312f346632663535323264353430336335642e706e67)<br><br>
![](https://camo.githubusercontent.com/ea4f7337c216543da743797c06980b29a26a1578/687474703a2f2f70312e6271696d672e636f6d2f3536373537312f623035613464363132623430626163612e706e67)<br><br>

如何使用
----

 1. 下载本项目到本地
 2. npm install下载依赖
 3. npm run dev


  [1]: http://cs003.m2828.com/demo/kugouApp/
  [2]: http://m.kugou.com
  [3]: http://cs003.m2828.com
  [4]: http://weibo.com/u/5921186675
  [5]: http://pan.baidu.com/s/1eSMb7e6
