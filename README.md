# Iwenli.NetWork.Crawler
基于.net的网络爬虫程序。爬取整站美女照片。

## 程序说明
+ 1.开发在vs2015社区版
+ 2.引用了2个NuGet程序包Newtonsoft.json和network.fishlee.net
+ 3.使用队列存储页面以及图片抓取任务，多线程处理方式。各任务互不干扰
+ 4.程序运行进度实时保存，再也不会害怕宕机啦~
+ 5.实时print抓取日志

##爬取图片的地址 http://www.mmjpg.com/

程序运行稳定高效，运行3次还没有出现异常，总共爬取10w+张照片，有图有真相 ->

###程序运行图
![程序运行图][1]

###爬取效果图-每个详情页一个文件夹（按详情标题起名，如果详情标题不符合文件夹命名规则则创建随机文件夹名）
![爬取效果图][2]

###抓取到的美女图哦^^
![抓取到的美女图][3]

  [1]: https://github.com/iwenli/Iwenli.NetWork.Crawler/blob/master/Iwenli.NetWork.Crawler/images/QQ%E6%88%AA%E5%9B%BE20170222082454.png
  
  [2]: https://github.com/iwenli/Iwenli.NetWork.Crawler/blob/master/Iwenli.NetWork.Crawler/images/QQ%E6%88%AA%E5%9B%BE20170222082510.png
  
  [3]: https://github.com/iwenli/Iwenli.NetWork.Crawler/blob/master/Iwenli.NetWork.Crawler/images/QQ%E6%88%AA%E5%9B%BE20170222090122.png
  
