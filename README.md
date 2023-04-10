# openai-wechat-mini-program
独家chatgpt3.5秒速回复保姆级小程序搭建教程
首先做一下前期准备工作
1.HBuilderX-高效极客技巧 (dcloud.io)下载安装HBuilder X
2.服务空间 - uniCloud (dcloud.net.cn)创建服务空间
3.函数计算 FC (aliyun.com) 创建代理
4.注册一个微信小程序mp.weixin.qq.com
5.下载微信开发者工具
文件下载下来后用HbuilderX打开，然后进行部署
![image](https://user-images.githubusercontent.com/130371533/230917465-2b3b0e6f-015c-40da-82fb-3602c132039a.png)
右键这里，初始化云空间
![image](https://user-images.githubusercontent.com/130371533/230917683-cb44ee56-0719-4de2-bddf-55c46207a9aa.png)
这里填写你的小程序id和密钥
现在我们进行函数部署，阿里云里面找到“函数计算”
![image](https://user-images.githubusercontent.com/130371533/230918102-aa8b81a9-c8b1-46a9-8cc2-94a3c7b6e367.png)
应用里面找到nginx，按照指引默认选择创建就行
![image](https://user-images.githubusercontent.com/130371533/230918302-943da7ca-8a6a-4b8a-b5eb-4ecca6dd8d94.png)
进入函数页面，点击刚才创建的函数。选择函数代码，然后将里面的代码替换为压缩包里面的代码，全部复制粘贴进去即可。
![image](https://user-images.githubusercontent.com/130371533/230918552-739b862a-9b1a-4d32-8ff8-c4b8bef6c3a6.png)
![image](https://user-images.githubusercontent.com/130371533/230918678-1f150b99-07b8-453e-a7c2-6f0e4caa5cb1.png)
完成后部署代码，复制url地址，回到HbuilderX
![image](https://user-images.githubusercontent.com/130371533/230918892-b2857a43-b9dc-40b9-9c2e-f13464f9b458.png)
将刚才的url粘贴到这里
到这里前端的搭建基本就完成了，可以尝试运行到微信开发者看一下，记得将开发者里面的id也改成你自己的
现在我们搭建后端，后端就简单很多，关联一下项目
![image](https://user-images.githubusercontent.com/130371533/230919291-6c62b522-3083-4293-a57d-5b586e290ac3.png)
![image](https://user-images.githubusercontent.com/130371533/230919401-9d326241-741d-4e78-97c0-e6aec397929e.png)
绑定到前端的项目中，然后运行到浏览器，chrome，加载时间会比较久，耐心等一下就好
![image](https://user-images.githubusercontent.com/130371533/230919766-e29c207a-4592-4525-9498-c6f7d0a5a5b8.png)
出现这个页面就代表进入成功了，然后在后台里面输入你的apikey，就可以正常使用小程序了
后台还有很多可以设置的功能，这个可以自行尝试一下。如果没有自己的apikey，也可以联系我。
