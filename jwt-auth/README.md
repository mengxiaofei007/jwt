# JwtAuthSystem

`本系统是一个基于jwt的单点登录认证系统。`

## 使用方式
`jwt-auth-server`部署好以后，`client`端引入`jwt-auth-client-spring-boot-starter`依赖，在properties或yml文件中配置好`jwt.auth.serverHost`的路径和`spring.redis.cluster.nodes`的地址，就ok了，多个redis路径以","分隔。

## 设计思路

![ssoSeq](asserts/sso流程图.png?raw=true "Screenshot JWT Spring Security Demo")