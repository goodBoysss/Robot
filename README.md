# 飞书机器人消息推送
机器人消息推送，支持消息类型：文本，卡片，图片等。现支持机器人：企业微信、钉钉、飞书


## 环境要求

* PHP >= 5.6


## 安装（composer包）
```shell
composer require tianmiao/robot
```



## 示例
```php

Tianmiao\Robot::getInstance()->sendMsg("hello word");

```
