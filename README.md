# VTUN (Virtual Tunnel)

通过TCP/IP建立虚拟隧道

## 特点

目前基本上与原版保持一致，去除了通讯中出现的VTUN明文字眼，后期可能会加入流量混淆。

## 依赖

```sh
lzo2
openssl
```

## 编译

```sh
./configure
make
make install
```
