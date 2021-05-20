# ADMIN-DEMO

spring boot admin + consul

有一些配置的坑
1. spring-boot-admin-starter-server的version必须要 >= spring boot的version，比如这里是（2.2.2 > 2.2.0），不然可能无法起服务。
2. spring-boot-admin-starter-server的2.2.0版本在读取日志时有BUG。关联issue为 https://github.com/codecentric/spring-boot-admin/issues/1318
