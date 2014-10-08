MyBatis Memcached Extension By Donnie
===========================

MyBatis-Memcached extension Memcached support for MyBatis Cache.

This extension based on [official mybatis-memcached 1.0.0](https://github.com/mybatis/memcached-cache/tree/mybatis-memcached-1.0.0)

该项目基于[mybatis-memcached 1.0.0](https://github.com/mybatis/memcached-cache/tree/mybatis-memcached-1.0.0)官方项目

Compatible with all original configuration

兼容原有所有配置

Additional Features 新增特性
----------

* Add SASL support
* 支持通过SASL连接memcached服务器
* Add Refuse Period option to wait for some time when the memcached connection refused
* 添加refuse period选项，用于在memcached服务器链接断开之后的一段时间不使用memcached

Official Configuration 官方配置
----------

* [official mybatis-memcached docs](http://mybatis.github.io/memcached-cache/)

New Configuration 新增配置选项
----------

* `org.mybatis.caches.memcached.sasl=[true|false]` flag to enable/disable the sasl connection
* `org.mybatis.caches.memcached.username` the username when using sasl
* `org.mybatis.caches.memcached.password` the password when using sasl
* `org.mybatis.caches.memcached.refuseperiod` the refuse period (in millisecond)



