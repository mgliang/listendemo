# redissubdemo
springboot入门--springboot集成redis实现消息发布订阅模式
TestController：负责触发redis 消息发送；
RedisConfig ：配置监听redis订阅消息容器包括订阅主题
以及重写消息适配器并绑定消息处理器，利用反射调用消息接收容器里的处理方法
###2020-08-03
