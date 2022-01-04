> 交互式教程：[https://try.redis.io/](https://try.redis.io/)

## String 操作

| 命令      | 具体                           | 解释                                                     |
| --------- | ------------------------------ | -------------------------------------------------------- |
| SET/GET   | SET key value                  | 设置指定 key 的值                                        |
|           | GET key                        | 获取指定 key 的值                                        |
| GETSET    | GETSET key value               | 将给定 key 的值设为 value ，并返回 key 的旧值(old value) |
| MGET/MSET | MSET key value [key value ...] | 同时设置一个或多个 k-v 对                                |
|           | MGET key1 [key2]               | 获取所以（一个或多个）给定 key 的值                      |
