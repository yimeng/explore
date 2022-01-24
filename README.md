# 有用没用的
## 总结的比我好的
* [awesome-sysadmin](https://github.com/kahun/awesome-sysadmin) 总结了很多工具
## 网站分享
* [stackshare](https://stackshare.io)
* [packagecloud](https://packagecloud.io)

## ssh相关
* ssh-agent 可以把私钥转发的工具,比如A(私钥ssh-agent)=>B(公钥 ssh配置开转发)=>C(公钥)
* ssh-add 配合ssh-agent可以把私钥缓存起来,并且不用输入passphrase,但传统加bash profile的做法还是有一些不足,比如每个终端都要起一个ssh-agent,需要重复输入passphrase
* [keychain](https://wiki.gentoo.org/wiki/Keychain) 一个弥补ssh-agent不足的shell脚本 
* [privacyidea](https://www.privacyidea.org) 一个管理公钥的工具,似乎还可以加二次认证.(简易的跳板机?)
* sshuttle 一个ssh代理的"路由"软件 sshuttle -r root@eip 192.168.0.0/16 -D

## ruby相关
* rbenv 插件形式管理ruby 原生有curl的证书问题。需要替换源。
* rvm 社区说太重了。

## MacOS

* [terminal-notifier](https://github.com/julienXX/terminal-notifier) 充分利用通知条的命令行小程序
* [karabiner](https://pqrs.org/osx/karabiner/) 改建专用 里面有一些可以借鉴的快捷键和操作习惯

## devops
* [Bats](https://github.com/sstephenson/bats): Bash Automated Testing System
* [serverspec](http://serverspec.org） puppet的自动化测试工具
* [rspec](http://rspec.info) ruby的自动化测试工具
* [cucumber](https://cucumber.io)
* [webhook](https://github.com/adnanh/webhook) 一个go写的简单的搭建webhook工具
* [KeyBox](http://sshkeybox.com/index.html) key管理，附带二次认证等等
* [pulp](http://pulpproject.org/) yum同步工具
* [redash](https://redash.io) 数据可视化神器，类似于kibana，但更灵活高效。
* [stackstorm](https://stackstorm.com) 运维里的IFTTT
* [mmock](https://github.com/jmartin82/mmock) golang写的mock工具
* [testinfra](https://github.com/philpep/testinfra) python自动化测试工具
* [molecule](https://github.com/metacloud/molecule) ansible role自动化测试工具
* [caddy](https://caddyserver.com) golang写的http server，傻瓜化配置https
* [graphql-engine](https://github.com/hasura/graphql-engine) 使用Postgres数据库自动生成前端GraphQL的工具，可以用来做CMDB。
* [Traefik](https://traefik.io) 云原生时代的nginx
* [sampler](https://github.com/sqshq/sampler) 命令行的监控dashboard
* [statusfy](https://statusfy.co) 开源的系统状态dashboard
* [shellcheck](https://www.shellcheck.net/#) 检测shell语法的工具
* [concourse](https://concourse-ci.org) 一个流水线即代码的工具
* [locust](https://locust.io) python压力测试的工具 有简单的展示界面
* [boomer](https://github.com/myzhan/boomer) 用golang写的locust工具 有grafana展示界面
* [bytebase](https://bytebase.com) SQL审核和Schema管理工具

## 个人效率
* [taskwarrior](https://taskwarrior.org) 一个命令行的todo工具
* [huginn](https://github.com/huginn/huginn) 一个个人的ifttt工具
* [monday](www.Monday.com) 时间轴管理网站

## 有意思的东西
* [为什么prometheus默认端口是9090，里面有一堆列表](https://github.com/prometheus/prometheus/wiki/Default-port-allocations)
* [Node-RED](https://nodered.org) IoT里的IFTT
* [cloudcraft](https://cloudcraft.co) terraform的可视化网站
* [liquibase](https://www.liquibase.org) 数据库版本控制系统

## docker
* [container-structure-test](https://github.com/GoogleCloudPlatform/container-structure-test) google的容器单元测试框架

## 安全
* [xca] (https://sourceforge.net/projects/xca) 一个PKI体系的GUI客户端
* [cfssl] (https://github.com/cloudflare/cfssl) cloudflare家的PKI/CA工具 命令行下相当好用

## 博客
* [n4mine](https://n4mine.github.io) 一个滴滴的哥们，监控的内容很有价值

## k8s
* [shell-operator](https://github.com/flant/shell-operator#kubernetes) 使用k8s事件来触发shell命令的东西

## demo
* [podinfo](https://github.com/stefanprodan/podinfo) 一个用golang写的演示程序，适合搭配flux使用：）
* [k3d-demo](https://github.com/iwilltry42/k3d-demo) k3d的一些演示场景
* [guestbook](https://kubernetes.io/zh/docs/tutorials/stateless-application/guestbook/) k8s官方的guestbook demo
* [Sock Shop](https://github.com/microservices-demo/microservices-demo) Weaveworks家的demo
* [Car-Hailing APP](https://github.com/Johnny850807/Waber)
* [混沌工程&可观测性](https://mp.weixin.qq.com/s/Tv14Er8WDnHceGdUHhpJzg)

## 参考链接:
* [Working with SSH key passphrases](https://help.github.com/articles/working-with-ssh-key-passphrases/)
* [ssh-agent 使用指南](http://segmentfault.com/a/1190000002449006)
* [SSH 密钥管理与 privacyIDEA](https://websetnet.com/zh/ssh-key-management-with-privacyidea/)
* [SSH 密钥类型的的选择（RSA， DSA or Other）](http://blog.sina.com.cn/s/blog_6f31085901015agu.html)
* [大量命令行工具、框架和资料](https://toutiao.io/posts/4kh80/preview)

## 博客
* [伪架构师](https://blog.fleeto.us/#posts)
