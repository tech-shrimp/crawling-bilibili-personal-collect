<h1>爬取bilibili的自己账号的收藏夹信息，并且json转excel存储</h1>
	防止自己收藏夹什么视频被删都不知道
	
<h2>源文件下载下来有两点需要注意</h2>
1.UID要改。改成自己的

2.路径注意一下。我只放了一个文件夹

<h3>实现思路</h3>

1.先爬取所有收藏夹的id

2.通过爬取的收藏夹的id，再爬取各个收藏夹的每一页（一页最多20个视频）

3.再稍微整理，得到每个收藏夹的json文件

4.最后将根据得到的json文件生成html（未完成）
