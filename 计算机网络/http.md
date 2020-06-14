### 请求方法

- get
- post
- delete
- put
- Options  预检请求  --- 在客户端发送的是复杂请求且跨域时会默认先发送options请求；（除get post外均是复杂请求，如果get post上带了自定义请求头也会变成复杂请求）

### 跨域

1、 通过jsonp跨域
 2、 document.domain + iframe跨域
 3、 location.hash + iframe
 4、 window.name + iframe跨域
 5、 postMessage跨域
 6、 跨域资源共享（CORS）
 7、 nginx代理跨域
 8、 nodejs中间件代理跨域
 9、 WebSocket协议跨域

### 状态码

##### 1xx

- 101  websocket

##### 2xx

- 204  无响应体
- 206   请求部分数据  实现断点续传

##### 3xx

- 301   永久重定向
- 302   临时重定向
- 304   服务端缓存

##### 4xx

- 400	客户端参数不正确
- 401    没有权限 未登录
- 403    没有权限  登录了没权限
- 405     服务端不支持此请求方式

##### 5xx   服务器端问题