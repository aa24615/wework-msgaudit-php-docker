# wework-msgaudit-php-docker

企业微信-会话内容存档PHP扩展sdk docker镜像

PHP扩展来源于 [https://github.com/pangdahua/php7-wxwork-finance-sdk](https://github.com/pangdahua/php7-wxwork-finance-sdk)		

我们对其提供docker中运行,省去您在繁琐安装步骤上的麻烦


### 要求

docker

docker-compose


### 运行


```shell
sh run.sh
```


### 说明


本镜像也同时为你准备了mysql 与 redis 如不需要注释即可			

默认安装是php7.4-fpm版本 如需cli版 请在Dockerfile自行修改	

本镜像只是帮您安装好扩展,安装完需要自己去测试代码  


### 目录

php/C_sdk 企业微信C语言sdk
php/php7-wxwork-finance-sdk 将C语言sdk转换为PHP扩展
php/extension 安装扩展时临时目录


###  参与贡献

1. fork 当前库到你的名下
2. 在你的本地修改完成审阅过后提交到你的仓库
3. 提交 PR 并描述你的修改，等待合并

### 联系我们

QQ交流群 [825443653](https://jq.qq.com/?_wv=1027&k=It3u9hrp)

###  License

[MIT license](https://opensource.org/licenses/MIT)


