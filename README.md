REDIS
=========

通过 ansible 部署在容器下运行的 Hadoop 服务。

Installation
--------------

`ansible-galaxy install gengxiankun.redis`

Role Variables
--------------

variable | description
------------ | -------------
OPT_PATH | 部署目录
REDIS_CONTAINER_NAME | Redis 容器名称
REDIS_PORT | Redis 对外端口

Example Playbook
----------------

    - hosts: servers
      roles:
         - gengxiankun.redis

License
-------

GPL-2.0-or-later, MIT, etc

Author Information
------------------

This role was created in 2019 by Xiankun Geng, Learn more about the author's role in [galaxy](https://galaxy.ansible.com/gengxiankun).
