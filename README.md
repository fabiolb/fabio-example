# Overview

fabio-example is an example HTTP microservice for demonstrating the
consul-aware HTTP load-balancer [fabio](https://github.com/eBay/fabio).

Build it with

```
go get -u github.com/magiconair/fabio-example
```

Run it

```
./fabio-example -addr <service host:port> -prefix host/path,host/path,...

e.g.

./fabio-example -addr 127.0.0.1:5000 -prefix /foo,/bar
```


