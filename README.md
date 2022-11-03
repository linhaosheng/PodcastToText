# PodcastToText
把播客上的音频转为文字


## 技术简介：

1. 状态管理 ： GetX 
2. 网络请求 ： dio
3. 时间工具 :  event bus
4. 数据存储 :  shared_preferences
5. 图片缓存 :  cached_network_image:
6. 集合控件 :  getwidget


## 接口数据
1. 播客订阅-搜索 : https://itunes.apple.com/search?media=podcast&term={search}
2. 订阅播客 ： http://rss.lizhi.fm/rss/1307862.xml （rss.lizhi.fm）
3. 播客下载： http://cdn.lizhi.fm/audio/{id}
4. 曲目 : https://feed.xyzfm.space/99b3wkblwf9c



1. 下载历史 ： 本地数据库记录 (https://feed.xyzfm.space/99b3wkblwf9c)
2. 播放历史 ： 本地数据库记录
3.    订阅 : 本地数据库记录(https://feed.xyzfm.space/99b3wkblwf9c)
4. 播放列表 :  本地数据库记录
   



## UI 设计图:
![image](https://github.com/linhaosheng/PodcastToText/blob/main/design_img/1248.png)
![image](https://github.com/linhaosheng/PodcastToText/blob/main/design_img/1247.png)
![image](https://github.com/linhaosheng/PodcastToText/blob/main/design_img/1246.png)
![image](https://github.com/linhaosheng/PodcastToText/blob/main/design_img/1245.png)
![image](https://github.com/linhaosheng/PodcastToText/blob/main/design_img/1244.png)
![image](https://github.com/linhaosheng/PodcastToText/blob/main/design_img/1243.png)
![image](https://github.com/linhaosheng/PodcastToText/blob/main/design_img/1242.png)
![image](https://github.com/linhaosheng/PodcastToText/blob/main/design_img/1241.png)
