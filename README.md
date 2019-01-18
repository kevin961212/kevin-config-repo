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
