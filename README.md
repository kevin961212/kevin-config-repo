# kevin-config-repo

#### 项目介绍
Spring Cloud Config


访问配置文件的格式：
/{application}/{profile}[/{label}]
/{application}-{profile}.yml
/{label}/{application}-{profile}.yml
/{application}-{profile}.properties
/{label}/{application}-{profile}.properties

命中默认的配置application.yml（优先级高）：
http://localhost:8080/master/xxx-default.yml

命中设置的配置foobar-dev.yml：
http://localhost:8080/master/foobar-dev.yml

查看默认的配置
http://localhost:8080/xxx/dedault/master

查看设置的配置
http://localhost:8080/foobar/dev/master

bootstrap.*里面的配置   ---->连接Config server，加载远程配置    --->加载application.*里面的配置



配置文件配置git上的uri

对称加解密：使用yml时需要加上单引号，如果是properties格式则不需要单引号



#### 软件架构
软件架构说明


#### 安装教程

1. xxxx
2. xxxx
3. xxxx

#### 使用说明

1. xxxx
2. xxxx
3. xxxx

#### 参与贡献

1. Fork 本项目
2. 新建 Feat_xxx 分支
3. 提交代码
4. 新建 Pull Request


#### 码云特技

1. 使用 Readme\_XXX.md 来支持不同的语言，例如 Readme\_en.md, Readme\_zh.md
2. 码云官方博客 [blog.gitee.com](https://blog.gitee.com)
3. 你可以 [https://gitee.com/explore](https://gitee.com/explore) 这个地址来了解码云上的优秀开源项目
4. [GVP](https://gitee.com/gvp) 全称是码云最有价值开源项目，是码云综合评定出的优秀开源项目
5. 码云官方提供的使用手册 [https://gitee.com/help](https://gitee.com/help)
6. 码云封面人物是一档用来展示码云会员风采的栏目 [https://gitee.com/gitee-stars/](https://gitee.com/gitee-stars/)