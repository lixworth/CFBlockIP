# CFBlockIP
caddy平台下，使用Cloudflare API 屏蔽请求次数多的IP

# 使用方法
## 开启Caddy的log
``
log / /usr/local/caddy/log/web.log "{remote} - {user} [{when}] {when_unix} \"{method} {uri} {proto}\" {status} {size} \"{>Referer}\" \"{>User-Agent}\""
``
## 自定义脚本
## 添加定时任务（比如可以使用宝塔面板的定时任务）

## 参考
[https://www.moeelf.com/archives/14.html](https://www.moeelf.com/archives/14.html)
