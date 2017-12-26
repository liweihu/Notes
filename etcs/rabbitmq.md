# rabbitmq

- rabbitmq windows下的配置文件路径 `%APPDATA%\RabbitMQ\rabbitmq.config`
- 打开管理页面 `sudo rabbitmq-plugins enable rabbitmq_management`
- 查看用户  `sudo rabbitmqctl list_users`
- 新增管理员用户 `sudo rabbitmqctl add_user admin admin`

  `sudo rabbitmqctl set_user_tags admin administrator`
- [管理页面](http://127.0.0.1:15672)
