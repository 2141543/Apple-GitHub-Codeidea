 

## OfficialTranslation-SourceAnnotation




## 导语 📌 

>我们追求技术的提升，关注技术的发展历程；作为从事技术工作的伐码猿，有个想法（`仅是个人想法`），这个想法工程量之大（`遇到，用到，最新技术点，点点积累，及时补充吧`），从事技术多年也算是对所花费时间的一个总结（`算是对技术这块的一个目标吧`）。

>这篇文章的内容仅是【UIKit框架 各文件分类的一个简明介绍】，  
**重点 -> 重点 -> 重点**（`重要的事情说 2+1 遍`），    
**我的「想法和行动」都在文章末尾**



## OfficialTranslation-SourceAnnotation



当你「了解权威 & 进阶原理」的时候，网搜的众多中 ~ ~（自行脑补）。做只有思想的伐码猿，做到「实用概念，不文言」&「实现原理，简明详解」，从零开始，由浅入深。 以简化初学者入门和老司机回顾的繁索过程，尽快切入主题，快速使用起来。这里只等你的到来 ！



![ ](http://upload-images.jianshu.io/upload_images/2230763-3471e189f31650c4.jpeg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)



## 我 GitHub 工程已创建好，只等你的到来

**在「时间 & 知识 」有限内，总结的文章难免有「未全、不足 」的地方，还望各位好友指出，以提高文章质量**。


### iOS·官方译文 学习整理

- [从 NSURLConnection 到 NSURLSession 译文](https://custompbwaters.github.io/官方译文+活用/从%20NSURLConnection%20到%20NSURLSession.html)。


- [NSURLSession译文+活用](https://custompbwaters.github.io/官方译文+活用/NSURLSession译文+活用.html)。


- [UIWebView译文+活用](https://custompbwaters.github.io/官方译文+活用/UIWebView译文+活用.html)。


- [UIBezierPath译文+活用](https://custompbwaters.github.io/官方译文+活用/UIBezierPath译文+活用.html)。


- [UIView API 官方文档译文](https://custompbwaters.github.io/官方译文+活用/UIView%20API%20官方译文.html)。






### iOS·三方框架 学习整理

- [AFNetworking（v3.0+）源码学习总结(一)—AFURLSessionManager](https://custompbwaters.github.io/源码注解+活用/AFN（v3.0+）源码学习总结(一)—AFURLSessionManager.html)。


- [AFNetworking（v3.0+）源码学习总结(二)— AFHTTPSessionManager](https://custompbwaters.github.io/源码注解+活用/AFN（v3.0+）源码学习总结(二)—AFHTTPSessionManager.html)。


- [AFNetworking（v3.0+）源码学习总结(三)— Serialization 序列化](https://custompbwaters.github.io/源码注解+活用/AFN（v3.0+）源码学习总结(三)—%20Serialization%20序列化.html)。


- [AFNetworking（v3.0+）源码学习总结(四)— ReachAbility 网络状态监听](https://custompbwaters.github.io/源码注解+活用/AFN（v3.0+）源码学习总结(四)—%20ReachAbility%20网络状态监听.html)。


- [AFNetworking（v3.0+）源码学习总结(五)— Security 网络通信安全策略](https://custompbwaters.github.io/源码注解+活用/AFN（v3.0+）源码学习总结(五)—%20Security%20网络通信安全策略.html)。


- [AFNetworking（v3.0+）源码学习总结(六)— UIKit+AFN工具类](https://custompbwaters.github.io/源码注解+活用/AFN（v3.0+）源码学习总结(六)—%20UIKit+AFN工具类.html)。



- [AFNetworking（v3.0+）框架学习总结(四框架二次封装)](https://custompbwaters.github.io/源码注解+活用/AFN（v3.0+）框架学习总结(四框架二次封装).html)。


- [AFNetworking（v3.0+）框架学习总结(三框架基本使用)
](https://custompbwaters.github.io/源码注解+活用/AFN（v3.0+）框架学习总结(三框架基本使用).html)。


- [AFNetworking（v3.0+）框架学习总结(二内部逻辑处理过程)](https://custompbwaters.github.io/源码注解+活用/AFN（v3.1.0）框架学习总结(二内部逻辑处理过程).html)。


- [AFNetworking（v3.1.0）框架学习总结(一框架结构)](https://custompbwaters.github.io/源码注解+活用/AFN（v3.1.0）框架学习总结(一框架结构).html)。


- [SDWebImage框架学习总结](https://custompbwaters.github.io/源码注解+活用/SD框架学习总结.html)。


- [SDWebImage源码学习总结(一)—SDWebImageManager](https://custompbwaters.github.io/源码注解+活用/SD源码学习总结(一)—SDWebImageManager.html)。



- [SDWebImage源码学习总结(二)—SDImageCache
](https://custompbwaters.github.io/源码注解+活用/SD源码学习总结(二)—SDImageCache.html)。



- [SDWebImage源码学习总结(三)—SDWebImageDownloader](https://custompbwaters.github.io/源码注解+活用/SD源码学习总结(三)—SDWebImageDownloader.html)。



- [MJExtension框架学习总结](https://custompbwaters.github.io/源码注解+活用/MJExtension框架学习总结.html)。










***



**总之，学习一门第三方框架库的时侯，需要追根溯源，才好提纲切领，即能掌握全局，又能深入细节。从框架源码出发，结合事件业务逻辑处理的机制，再深入到各个功能点或再次封装，就会胸有成竹而不乱阵脚了。**


温馨提示：☕️    
所有文章将「迁移 & 后续」对应两个工程下，这两个想法是个长期而持续的目标吧，如果你感觉看我写的文章对你 利大于弊 . . .（`由于个人 「时间 & 知识」 有限，是心有余而力有限，欢迎你的 Star & Fork`）。



## 「译文 & 框架」注解演示

- [iOS·UIView API 官方文档译文](http://www.jianshu.com/p/dd227f886185)


- [AFNetworking（v3.1.0）框架结构注解](http://www.jianshu.com/p/519611e875cd)



## GitHub工程地址

 - [UIKit 框架，归类整理，各分类文件注解，并对每一类中常用的功能进行案例渐进式解析，从零开始，由浅入深；以简化初学者入门和老司机回顾的繁索过程，尽快切入主题，快速使用起来。这里只等你的到来 ！Star & Fork](https://github.com/CustomPBWaters/UIKit-Framework-OpenSource)


 - [iOS·Objective-C 实用文章详解整理专题](https://github.com/CustomPBWaters/OfficialTranslation-SourceAnnotation/blob/master/iOS·Objective-C%20实用文章详解整理.md)


 


## 期待

- 如果在阅读过程中遇到 error，希望你能 Issues 我，谢谢。

- 如果你想为【官方译文源码注解】分享点什么，也希望你能 Issues 我，我非常想为这篇文章增加更多实用的内容，谢谢。

- [「博客原文」](https://custompbwaters.github.io/2017/03/18/感悟·生活/开源技术/)对本专题我会【不定时、持续更新、一些 学习心得与文章、实用才是硬道理】^_^.


## About me

【我也是对所花费时间的一个总结】

我只是个【有思想的伐码猿🐒】加上【自己的学习总☕️】写出来的文章。
 

![↑ 《伐码吧》 --> "兄弟"   ↑ 可否帮我达到 100的目标 ，谢谢 ](http://upload-images.jianshu.io/upload_images/2230763-6746b831e7f456f6.gif?imageMogr2/auto-orient/strip)
 

