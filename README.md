# 有用没用的
## ssh相关
* ssh-agent 可以把私钥转发的工具,比如A(私钥ssh-agent)=>B(公钥 ssh配置开转发)=>C(公钥)
* ssh-add 配合ssh-agent可以把私钥缓存起来,并且不用输入passphrase,但传统加bash profile的做法还是有一些不足,比如每个终端都要起一个ssh-agent,需要重复输入passphrase
* [keychain](https://wiki.gentoo.org/wiki/Keychain) 一个弥补ssh-agent不足的shell脚本 
* [privacyidea](https://www.privacyidea.org) 一个管理公钥的工具,似乎还可以加二次认证.(简易的跳板机?)

## ruby相关
* rbenv 插件形式管理ruby 原生有curl的证书问题。需要替换源。
* rvm 社区说太重了。

## MacOS

## devops
* [Bats](https://github.com/sstephenson/bats): Bash Automated Testing System

* karabiner 改建专用 里面有一些可以借鉴的快捷键和操作习惯

参考链接:
* [Working with SSH key passphrases](https://help.github.com/articles/working-with-ssh-key-passphrases/)
* [ssh-agent 使用指南](http://segmentfault.com/a/1190000002449006)
* [SSH 密钥管理与 privacyIDEA](https://websetnet.com/zh/ssh-key-management-with-privacyidea/)
* [SSH 密钥类型的的选择（RSA， DSA or Other）](http://blog.sina.com.cn/s/blog_6f31085901015agu.html)
* [大量命令行工具、框架和资料](https://toutiao.io/posts/4kh80/preview)
