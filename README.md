# SayHello

《[Flask Web 开发实战](http://helloflask.com/book)》 第8章个人博客

Demo: http://bluelog.helloflask.com

![Screenshot](http://helloflask.com/screenshots/bluelog.png)


## 安装

git clone源码
```
$ git clone https://github.com/greyli/bluelog.git
$ cd bluelog
```

安装依赖
```
$ sudo apt-get install libpq-dev python-dev
$ pip3 install -r requirements.txt
```

预先在DB生成假记录
```
$ flask forge

```



启动http服务

```
## Running on http://0.0.0.0:8080/
$ flask run -h 0.0.0.0  -p 8080 
```

在本地尝试访问服务

```
$ curl http://localhost:8080
```

通过浏览器访问服务

```
http://IP:8080
```


