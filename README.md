# python_crawler
python爬虫项目.初学,包含了新浪微博,内涵段子,妹子图等

初学python,简单的学习了一些网站的爬虫.相关爬虫只是学习,没有任何商业使用,如果侵权,请联系删除.

1.新浪微博  使用了新浪微博的SDK(其实是[廖雪峰](https://www.liaoxuefeng.com/),非常感谢)

2.微信相关  使用了itchat的框架,很强大,使用起来也非常简单

3.lehui,yungao  这个就是纯粹的抓取数据了,可以存储到csv,也可以存储到mysql中,主要使用了requests和lxml框架

4.内涵段子,百思不得姐,糗事百科等都是类似的,抓取数据,其中涉及到分页抓取,其实有好几种方法,页数递增或者获取到"下一步"等

5.妹子图,使用同样的方式抓取妹子图片,保存到本地,这个项目中使用了leancloud云存储,可以注册使用,非常方便. 

6.妹子图合成视频  使用opencv,将图片合成视频,使用opencv的方法,这个是在树莓派上操作运行的,暂时没有相关代码,稍候会上传,使用方法也很简单,VideoWriter函数,设置视频名称,视频格式,帧率,视频宽高

后续慢慢学习更新.