# GH670.github.io
##  wblog.tech  
##  blog建设中...  

#### 1.CNAME的设置  
Q:每次更新部署之后，CNAME消失不见。  
A:将CNAME文件放置到source文件家目录下。
#### 2.README
Q:更新部署一次，README.md消失一次，并且，将README.md放置在source文件目录下更新部署之后，导致.md转化成.html。  
A：在_config.yml设置skip_render来忽略的目录，让解释器跳过渲染。（接1）  
例如：skip_render : README.md  （注意格式规范）
#### 3.Gitment----基于GitHub的评论系统  
注册一个新的 OAuth Application：[https://github.com/settings/applications/new](https://github.com/settings/applications/new)  
- Application name 应用名称(根据实际来填写)  
- Homepage URL 主页网址(应用程序主页的完整URL)  
- Application description 应用说明(应用描述)  
- Authorization callback URL 授权回调URL(一般是博客的域名)  

&nbsp;&nbsp;&nbsp;&nbsp;gitment_repo: ''          #存储评论的 repo name(需要在Github创建)      
Q:无初始化按钮，只显示且不能评论。  
A:Application与_config.yml中gitment_repo一致。   

Q:[object ProgressEvent]  
A:估计。。。作者服务器到期/?
#### 4.Giteement-集成码云评论  
- 更改Gitment为giteement.  
#### 5.blog不定期更新测试中...   
## 后期更新速度变缓。。
# 欢迎各位批评指导...