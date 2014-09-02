**The end of fun, Apple have just patched**


Here is appleID password bruteforce pOc.
It's only p0c, so there is no
	

* MultiThreading feature
* Save-State-On-Exception feature


do it yourself


It uses Find My Iphone service API, where bruteforce protection was not implemented. Password list was generated from top 500 RockYou leaked passwords, which satisfy appleID password policy. Before you start, make sure it's not illegal in your country. 

Be good :)


Follow us on twitter @hackappcom

---------------------------
2014-9-2 9:57:38

iCloud 泄露事件，从目前掌握的信息来看，其实只是 find my iphone 某个API忘记设置防暴，然后成功被爆，目前漏洞已经修补.

Github 上找来的 ibrute 代码，看看知道怎么回事了就好

---------------------------
2014-9-2 11:44:54

据一份报告指出，一个攻击iCloud账户的Python脚本已经浮出了水面，而且它显然利用了Find My iPhone功能的漏洞。

据悉，采用这种攻击方式来“暴力穷举”iCloud账号的话，不仅不会被封锁，还不会向账号持有人发出警告。

据The Next Web报道，该脚本于本周一被放到了GitHub上，并且严重归咎于Find My iPhone服务竟然没有对密码尝试次数作出限制。

一旦账号密码被破除，攻击者就可以肆意访问苹果所提供的全部服务。不过苹果已紧急将尝试上限设定为五次，脚本作者也证实苹果已封堵上这一漏洞。

据脚本作者(Twitter用户)Hackapp所述，该漏洞“在所有提供很多认证接口的服务中普遍存在”，而攻击者只需掌握简单的嗅探知识和反向技巧就能得逞。


