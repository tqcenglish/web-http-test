# web 测试

简单的 Web 性能测试。

1. python
1. node
1. go
1. openresty

## python

``` shell
python3.6 http.py
```

## node

``` shell
node http.js
```

## go

``` shell
./httpgo
```

## openresty

``` shell
/usr/local/Cellar/openresty/1.11.2.3/nginx/sbin/nginx -p `pwd`/ -c nginx.conf
```

## 测试

``` shell
ab -n 8000 -c 80  http://127.0.0.1:3000/
```