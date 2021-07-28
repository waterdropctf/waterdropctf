# waterdropctf: 一个基于容器的CTF战队训练平台

此项目用于整合主要服务和应用

* [waterdropctf-engine](https://github.com/waterdropctf/waterdropctf-engine)
  * 目前是闭源的状态，如果想加入该项目，请联系ssst0n3
  * 通过提供docker镜像的形式提供服务
  * 提供swagger-ui形式的api
* [waterdropctf-frontend](https://github.com/waterdropctf/waterdropctf-frontend)
  * 基于waterdropctf-engine的api开发的demo前端
  * 这是一个demo项目，主要是为了演示一些基础功能，大家可以参考并开发更加炫酷的前端

## Quick Start
```
docker-compose -f docker-compose.yml -f docker-compose.prod.yml up -d
```
