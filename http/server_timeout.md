<!-- YAML
added: v0.9.12
-->

* {Number} 默认为 `120000` (`2` 分钟)。

socket 被认定为超时的空闲毫秒数。

注意，socket 的超时逻辑是在连接上设定的，所以改变这个值只影响服务器新建的连接，而不会影响任何已存在的连接。

设为 `0` 可禁用请求连接的所有自动超时行为。

