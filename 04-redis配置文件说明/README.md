# redis配置文件说明

#### bind

>  默认情况下，redis 在 server 上只允许本地的网络接口上监听客户端连接。
>
> 你如果只想让它在一个网络接口上监听，那你就绑定一个IP或者多个IP

#### daemonize

> 默认情况下 redis 不是作为守护进程运行的，如果你想让它在后台运行，你就把它改成 yes。
>
> 当redis作为守护进程运行的时候，它会写一个 pid 到 /var/run/redis.pid 文件里面。

#### pidfile

>  当redis作为守护进程运行的时候，它会把 pid 默认写到 /var/run/redis.pid 文件里面，
> 但是你可以在这里自己制定它的文件位置。

#### port

> 监听端口号，默认为 6379，如果你设为 0 ，redis 将不在 socket 上监听任何客户端连接。



#### protected-mode

> 保护模式