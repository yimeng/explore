# 有用没用的
## ssh相关
* ssh-agent 可以把私钥转发的工具,比如A(私钥ssh-agent)=>B(公钥 ssh配置开转发)=>C(公钥)
* ssh-add 配合ssh-agent可以把私钥缓存起来,并且不用输入passphrase,但传统加bash profile的做法还是有一些不足,比如每个终端都要起一个ssh-agent,需要重复输入passphrase
* [keychain](https://wiki.gentoo.org/wiki/Keychain) 一个弥补ssh-agent不足的shell脚本 
