# douyin_online
抖音网页版|抖音PC版|抖音桌面版   
演示网站：http://douyin.liangmlk.cn


开发架构：
  php+python+redis+oss  
  php网站  
  pytho爬虫  
  redis数据缓存  
  oss存储抖音视频  
  
特点：
  1.基于PHP+PYTHON3开发  
  2.python用于采集抖音的热门视频，并下载到本地，然后通过python sdk上传到阿里云的oss中进行保存  
  3.网站使用CDN加速，针对静态资源+抖音视频进行了CDN，秒开抖音视频  
  4.播放器使用了video.js,实现了抖音类似的重复播放  
  5.页面样式采用瀑布流的形式，并兼容 WAP,APP,PC  
  6.懒性加载视频，通过ajax异步加载视频，降低网络带宽的消耗  
  7.可以打通微信公众号，打造一个微信端抖音  
 
 具体的技术细节和实现原理可以加wx:cqwanhl私聊
