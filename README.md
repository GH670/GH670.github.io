# GH670.github.io
##  wblog.tech  
##  blog建设中...  

#### 1.CNAME的设置  
Q:每次更新部署之后，CNAME消失不见。  
A:将CNAME文件放置到source文件家目录下。
#### 2.README
Q:更新部署一次，README.md消失一次，并且，将README.md放置在source文件目录下更新部署之后，导致.md转化成.html。  
A：在_config.yml设置skip_render来忽略的目录，让解释器跳过渲染。  
例如：skip_render : README.md  （注意格式规范）
#### 3...  

# 欢迎各位批评指导...