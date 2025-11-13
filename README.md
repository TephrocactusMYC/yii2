# 项目简介
使用yii2框架，开发了一个统计俄罗斯、乌克兰军事冲突相关信息的网站，完整实现前后端开发。

没有采用absolute等yii2的模板，而是在advanced的基础上，直接使用php、js、css进行开发。本项目前端的展示主要依赖于`Echarts`，进行动态展示。**这是本项目好看的核心**。
# 功能展示
## 前台
### 主页
主页采取动态背景的方式，展示了一些高清精美的背景图。`成为会员`控件为注册功能入口
![yii-1](https://raw.githubusercontent.com/TephrocactusHC/mybolgimg/master/yii-1.png)

在时间轴和背景图中间，提供了各个图表模块的入口控件
![yii-3](https://raw.githubusercontent.com/TephrocactusHC/mybolgimg/master/yii-3.png)
在主页下方，采取`时间轴`的方式展示新闻。
![yii-4](https://raw.githubusercontent.com/TephrocactusHC/mybolgimg/master/yii-4.png)
#### 新闻内部
在时间轴部分，仅仅展示新闻的摘要，进入文章界面，展示新闻的图片、标题、详细内容
![yii-5](https://raw.githubusercontent.com/TephrocactusHC/mybolgimg/master/yii-5.png)
### 地图模块
选取了Echarts进行动态地图展示，分别展示了难民、制裁、援助、花销的数量，可以动态展示各个国家的相关数据数量，并且支持地图的放大和国家高亮。
![yii-6](https://raw.githubusercontent.com/TephrocactusHC/mybolgimg/master/yii-6.png)
### 经济、军事、外交模块
**本部分主要采取以Echarts的条形图和折线图的方式，展示对应的数据变化和数据对比**

具体如下所示：
![yii-7](https://raw.githubusercontent.com/TephrocactusHC/mybolgimg/master/yii-7.png)
同时支持鼠标停留显示具体数据，当然，这都是Echarts特性
![yii-8](https://raw.githubusercontent.com/TephrocactusHC/mybolgimg/master/yii-8.png)
同时，也支持数据高亮
![yii-9](https://raw.githubusercontent.com/TephrocactusHC/mybolgimg/master/yii-9.png)
甚至可以将折线图和条形图放在同一个图里
![yii-10](https://raw.githubusercontent.com/TephrocactusHC/mybolgimg/master/yii-10.png)
### 评论模块
评论模块第一个功能是展示网友评论，这里同样采取时间轴的方式进行展示。

这里我们会展示评论的用户名和留言的时间
![yii-11](https://raw.githubusercontent.com/TephrocactusHC/mybolgimg/master/yii-11.png)
在提交留言的时候，同样可以自动获取留言的用户名
![yii-12](https://raw.githubusercontent.com/TephrocactusHC/mybolgimg/master/yii-12.png)
## 后台
### 对数据库的操作
可以直接对数据库的表进行增删改查的操作。
![yii-13](https://raw.githubusercontent.com/TephrocactusHC/mybolgimg/master/yii-13.png)
### 上传文件
上传文件界面。注意，这里需要管理员才能实现这一功能，如果是普通的用户，是不能上传文件的。
![yii-14](https://raw.githubusercontent.com/TephrocactusHC/mybolgimg/master/yii-14.png)
