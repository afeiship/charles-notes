# charles:

## problems
> Charles cannot configure your proxy settings while it is on a read-only volume. Perhaps you are

~~~
sudo chown -R root "/Applications/Charles.app/Contents/Resources"
sudo chmod -R u+s "/Applications/Charles.app/Contents/Resources"
~~~
- https://superuser.com/questions/1490116/charles-4-2-8-cannot-configure-your-proxy-settings-while-it-is-on-a-read-only-vo


## step:
1. 下载： https://www.weiyun.com/disk/folder/4efd47050f6948d83f0c3606ee8784b0
2. 将 Charles.app 拖至 应用程序 文件夹
3. 复制 charles.jar 至 /Applications/Charles.app/Contents/Java/
4. 使用 SN.txt 中的序列码即可(用下面的就可以了)
5. 下载了最新版： Charles_4.2.8_xclient.info.dmg

## charles (SN.txt):
~~~
// Charles Proxy License
// 适用于Charles任意版本的注册码，谁还会想要使用破解版呢。
// Charles 4.2目前是最新版，可用。
Registered Name: https://zhile.io
License Key: 48891cf209c6d32bf4
~~~



## https support:
1. iphone donwload:
- http://www.charlesproxy.com/getssl/
2. 手机设置：
~~~
Charles https Client SSL handshake failed: An unknown issue occurred processing the certificate

2017-04-10
设置-通用-关于本机-证书信任设置，信任下证书应该就好了
~~~
<img width="500" src="https://ws2.sinaimg.cn/large/006tKfTcly1g0t44p6wz7j30hs0vkdgv.jpg"/>


## resources
- https://www.cnblogs.com/wangyiwei/p/7773397.html
- http://www.charlesproxy.com/getssl/