# Envoy-Proxy-Simple-Demo

此`Repository`用`Envoy`對`Golang Server`做了簡單的代理Demo

## 需要安裝

* `docker`
* `docker-compose`

## How to run?

啟動`docker-compose`

```bash
$ docker-compose build
$ docker-compose up
```

連入`localhost:8080`

## 參考

* [Github - envoy](https://github.com/envoyproxy/envoy/blob/7c9202879eadfe68ed49c635273d7580aabe1314/configs/google_com_proxy.v2.yaml)