# springboot
java springboot redisson mybatis maven

使用SpringBoot+RabbitMQ，保证消息100%投递成功并被消费，并使用mail功能发送邮件。。。
其他功能：
    1。使用注解的方式进行防止重复提交（短时间多次请求服务器）和冥等校验（连续相同的请求会导致不同的结果）
    2。使用了动态代理的方式完成了消息的确认机制。
    3。包含了Redisson的示例代码
    4。动态代理，静态代理和工厂模式的示例代码
    5。rabbitMQ 100%确认投递成功机制实现。
    6。关于跨域的配置。
    7。常见的工具类（ip,dateTime,json,随机验证码,正则等）
    8。一些简单的静态页面。（登录，404。error）
