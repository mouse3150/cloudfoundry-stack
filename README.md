Cloudfoundry-Stack
==============
Cloudfoundry-Stack下包括以下几个方面的内容：

1.对Cloudfoundry框架（framework）和服务(server)的扩展，将一些商业中间件集成到Cloudfoundry平台中；

2.改造Router组件，改变最终用户访问应用的方式，app1.tong.com->tong.com/app1或0.0.0.0/app1；

3.改造Warden组件，Warden容器支持挂载NFS；

4.应用通过配置的方式使用绑定的服务，支持平台提供服务，或配置平台外部的服务。如：MYSQL，POST
