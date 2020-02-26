 # mabo_jili

 ### https://github.com/Zuoxiaoxian/mabo_jili/invitations
 
 
 ## demo1 鼠标移入块区域改变颜色并提示信息 使用的是ng-zorro-antd中的Popover 气泡卡片
 
 ## demo2 使用leaflet实现弹出窗口、标记、处理事件
 
 ## demo3 这个demo是离线的地图实例
 
 ---
 
	1、在leaflet的官网下载地图数据，格式为osm
	2、使用Maperitive将osm处理成Tiles的文件夹，里面放的是256X256的png
	3、替换原来的网址，在tileLayer中。
 
 
 [参考]:https://ng.ant.design/version/1.8.x/components/popover/zh
 
 ### 如何部署
 
 1. git clone 到本地
 
 2. 在nginx中代理
 
 ![详细配置](https://github.com/Zuoxiaoxian/mabo_jili/blob/master/conf_imgs/demo1_config.png)
 
 3. 运行 nginx
 ```bash
	nginx -c XXX.conf
 ```
 
 4. 本地访问 http://127.0.0.1