关于作者(About)
===========================================================
QQ:2801045898<br/>
E-Mail:2801045898@qq.com<br/>
HaGeSea@outlook.com<br/>

捐赠(Donate)
===========================================================
支付宝(AliPay)<br/>
![AliPay](https://github.com/seaase/ApkModifier/blob/master/alipay.png?raw=true)<br/>
微信(WeiChat Pay)<br/>
![WeChatPay](https://github.com/seaase/ApkModifier/blob/master/weichat.png?raw=true)<br/>
如果愿意，你可以对我捐赠，我也会更加有动力来开发和完善本软件。<br/>
如果没有这些，你可以下载[ApkModifier PRO ](http://pan.baidu.com/s/1eRFakvw)安装后打开，点击广告。以此来支持开发者<br/>

ApkModifier词典文件
==========================================================================================
[英汉词典](https://raw.githubusercontent.com/seaase/ApkModifier/master/EN-CN.db)


ApkModifier 使用中常见问题:
==========================================================================================
1.修改后的Apk安装时出现解析包错误，请签名即可<br/>
2.翻译出现问题，账户翻译字数已超限<br/>
3.修改后安装失败，请签名或破解核心,也有可能需要先卸载原版<br/>
4.签名时出现class invalid...,说明自定义的秘钥需要重新配置,在秘钥管理中删除后重新导入，由于使用了Java序列化来保存秘钥的配置信息，每次升级后，由于混淆的原因导致类名变化，因此出现该问题。这个问题已在3.1.2版本中解决，使用3.1.2版本时，先卸载原版再安装，以后的版本覆盖更新都可以正常使用<br/>

特别提示
==========================================================================================
1.关于安卓7.0打开闪退问题，需要手动到系统设置中给软件权限，由于安卓7.0提高了安全，所以会自动禁用软件的权限<br/>
2.新版安装后崩溃，请清除软件数据，新版与旧版数据有冲突<br/>

使用教程(2017/3/18更新)
==========================================================================================
[教程视频](http://pan.baidu.com/s/1qXQUiLI)

开放部分源代码(Open Source)
==========================================================================================
[Elf-Editor](https://github.com/seaase/Elf-Editor)<br/>
[Arsc-Editor](https://github.com/seaase/ArscEditor)<br/>


更新历史:
==========================================================================================
[v1.0](http://pan.baidu.com/s/1dFgMzQD) <br/>
1.文件管理器功能(复制，剪切，粘贴，删除，重命名)<br/>
2.zip管理器，在打开的压缩包文件中，可以对内部的文件进行随意的移动，修改，并且没有确认是不会保存。<br/>
3.签名Apk<br/>
4.so库文件符号名编辑器(可以修改so中的符号名，但又能保证符号名的hash表被正确修复，如果要克隆一个apk，如果包中有so文件需要改包名，这就起到了作用)<br/> 
5.zipalign 压缩包字节对齐<br/>
6.apk共存<br/>
7.res资源文件混淆(是否查看过QQ安装包内部的文件，发现没有res文件夹，只有r文件夹，其实他用的就是类似的加密)<br/>
8.反编译和回编译Dex文件(手机端apktool也可以，但是安装包却很大)<br/>
9.apk文件以及图片能显示略缩图<br/>
10.arsc,dex,axml字符串常量编辑<br/>

[v1.1](http://pan.baidu.com/s/1hs7KBYW) <br/>
1.更换图标<br/>
2.支持安卓7.0<br/>

[v1.2](http://pan.baidu.com/s/1eSh026e) <br/>
1.更换图标<br/>
2.更换用户界面为安卓2.3风格(原谅作者对2.3觉得非常经典)<br/>
3.修复克隆部分apk时软件闪退<br/>
4.字符串常量池的color的常量支持颜色显示<br/>

[v1.3](https://pan.baidu.com/s/1dF5PafR) <br/>
1.文件管理支持多选操作<br/>
2.优化字符串常量池的搜索方法<br/>
3.设置添加主题选择，可以选择本机主题和怀旧主题<br/>
4.其他一些细小优化<br/>

[v1.4](http://pan.baidu.com/s/1o8M1LAa)(重大更新，下载过词典的请重新更新)<br/>
1.搜索方案优化<br/>
2.字符串常量池添加跳转功能<br/>
3.支持压缩文件(加密，注释)<br/>
4.修复7.0及以上保存arsc文件时的错误<br/>
5.修复7.0及以上无法用系统打开文件<br/>
6.7.0及以上的初始目录改为/mnt<br/>
7.增加词典管理，可以制作自己的词典以及编辑已有词典，支持翻译后的内容保存到词典<br/>
8.其他一些细小优化<br/>

[v1.4.2](http://pan.baidu.com/s/1dF7QZdv)<br/>
1.添加土耳其语言支持<br/>
2.修复res资源混淆时出现的错误<br/>

[v1.4.3](http://pan.baidu.com/s/1i5hu5sp)<br/>
1.添加俄语支持<br/>
2.修复一个小bug<br/>

[v1.4.4](http://pan.baidu.com/s/1ckW6Do)<br/>
1.添加波斯语支持<br/>
2.arsc解析速度提升30%左右<br/>

[v1.5](http://pan.baidu.com/s/1kVO9Xdl)(技术进步)<br/>
1.arsc的所有资源都支持修改，其中color资源还有颜色指示器和选择器<br/>
2.修复克隆时的一些崩溃<br/>
3.arsc解析速度提升<br/>
4.字符串常量池资源搜索支持按id搜索<br/>
5.其他一些细小优化<br/>

[1.5.2](http://pan.baidu.com/s/1dF9Tdct)<br/>
1.修复部分机型访问词典数据库时内存泄漏的问题<br/>
2.修复小bug<br/>

[v1.6](http://pan.baidu.com/s/1slMvOsd)<br/>
1.修复克隆时的一些崩溃<br/>
2.字符串常量池条目长按支持复制内容<br/>
3.翻译语言增加土耳其语言支持<br/>
4.听说安卓6.0不能访问sd卡，特地看了一下<br/>

[v1.6.2](http://pan.baidu.com/s/1hsp4tec)<br/>
1.添加谷歌(Google)翻译<br/>
2.添加维吾尔语言包<br/>

[v1.6.3](http://pan.baidu.com/s/1dFmmAnZ)<br/>
1.优化谷歌翻译速度<br/>
2.翻译支持的语言增加到35种<br/>
3.修复自定义翻译账号不能用的问题<br/>

[v1.6.4](http://pan.baidu.com/s/1bpEHceV)<br/>
1.压缩包浏览根据文件的前几个字节来判断是否是图片或xml,方便对付资源混淆后的软件<br/>

[v1.7](http://pan.baidu.com/s/1bp3RJ6B)<br/>
1.软件体积再次减小了50KB左右，我们的目标是追求小巧强大<br/>
2.加强res资源混淆算法<br/>
3.解决浏览大图片时出现的内存溢出(OOM)情况<br/>

[v1.7.2](http://pan.baidu.com/s/1eS0xYvC)<br/>
1.修复词典翻译时不能翻译有空格的短语问题<br/>
2.修复字符串常量池编辑框不能多行的问题<br/>
3.修复其他一些细小bug<br/>

[v1.7.3](http://pan.baidu.com/s/1gfkNq7p)<br/>
1.修复字符串常量池遇到非法颜色代码时崩溃<br/>

[v1.7.4](http://pan.baidu.com/s/1c2d1N1Y)<br/>
1.修复词典翻译到一半时数据库访问内存溢出而导致崩溃的问题<br/>

[v1.8](http://pan.baidu.com/s/1kV9bXCN)<br/>
1.克隆支持自定义包名<br/>
2.添加西班牙语言<br/>

[v1.8.2](http://pan.baidu.com/s/1qYLJScs)<br>
1.修复部分崩溃问题<br/>
2.去除广告，软件体积又减小了60kB<br/>
3.添加apk属性查看<br/>

[v1.9](http://pan.baidu.com/s/1c2f5utq)<br/>
1.elf的rodata段字符常量支持修改<br/>
2.更新语言<br/>

[v2.0](http://pan.baidu.com/s/1mhAht24)<br/>
1.克隆自定义时对无动态库的apk取消包名长度限制<br/>
2.优化克隆方案<br/>
3.优化so库文件回写算法，已支持arm,x86,mips的动态库修改以及普通二进制文件的修改<br/>
4.修复部分elf文件的rodata修改后无法保存出现Index...的错误<br/>
5.修复部分elf文件编辑后文件变大的问题<br/>
6.设置添加自动签名选项(默认关闭)<br/>

[v2.1](http://pan.baidu.com/s/1c2w0Hva)<br/>
1.修复一个小bug<br/>

[v2.2](http://pan.baidu.com/s/1geArQYR)<br/>
1.修复部分apk混淆后停止运行的问题<br/>
2.更新语言<br/>

[v2.3](http://pan.baidu.com/s/1slUA0Sd)<br/>
1.对于安卓5.0及以上质感化设计(以后再添加更多细节)<br/>
2.修复部分bug<br/>

[v2.4](http://pan.baidu.com/s/1i5mR7NJ)<br/>
1.对5.0及以上重新进行了质感化设计，同时保留了经典主题和本机主题<br/>

[v2.5](http://pan.baidu.com/s/1nvC2mTj)<br/>
1.新增自定义签名、签名管理，创建新签名文件<br/>
2.修复一些小问题<br/>

[v2.5.2](http://pan.baidu.com/s/1slPlrVR)<br/>
1.更新语言<br/>
2.设置添加自定义启动图标<br/>

[v2.5.3](http://pan.baidu.com/s/1qXTGTMO)<br/>
1.修复部分崩溃问题<br/>

[v2.6](http://pan.baidu.com/s/1gfj85rH)<br/>
1.添加APK权限编辑<br/>
2.APK属性查看添加了签名信息的查看<br/>

[v2.7](http://pan.baidu.com/s/1mhNdVvi)<br/>
1.更新语言<br/>
2.优化谷歌翻译速度<br/>

[v2.8](http://pan.baidu.com/s/1qXPEzPq)<br/>
1.修复部分so文件修改后找不到符号的问题<br/>
2.修复某些ARSC打不开的问题<br/>
3.修复ARSC打开时多次重新加载的问题<br/>
4.优化克隆方案，克隆时增加了对Provider组件进行修改<br/>

[v2.9](http://pan.baidu.com/s/1pKLEoJp)<br/>
1.修复部分oat文件解压失败的问题<br/>
2.创建签名功能增加了RSA位数的设置<br/>

[v2.9.2](http://pan.baidu.com/s/1skRa12H)<br/>
1.修复部分apk签名时出现的CRC错误<br/>

[v3.0](http://pan.baidu.com/s/1bppjCrd)<br/>
1.用户界面细节优化。流畅度优化<br/>
2.解决文件图标有时错乱的问题<br/>
3.再次修复部分apk签名时出现的CRC错误<br/>
4.其他一些小变更<br/>

[v3.1](http://pan.baidu.com/s/1dFzUWPr)<br/>
1.修复上个版本发现的崩溃问题<br/>
2.设置的自动签名添加使用自定义签名<br/>
3.设置添加条目宽度自定义<br/>
4.修复签名apk后再查看apk属性无法正确显示签名的问题<br/>

[v3.1.2](http://pan.baidu.com/s/1c2zrbR6)<br/>
1.修复每次更新后用上个版本的自定义秘钥配置来签名时出现的class invalid...错误<br/>

[v3.2](http://pan.baidu.com/s/1i4FfKhR)<br/>
1.提升谷歌翻译速度<br/>
2.翻译增加了翻译本页选项<br/>
3.其他一些内存优化<br/>

[v3.3](http://pan.baidu.com/s/1hsJ1Oc0)<br/>
1.安卓5.0及以上新增两个Holo主题<br/>
2.修复一些少见的Null错误<br/>
3.词典管理增加新功能<br/>

[v3.3.2](http://pan.baidu.com/s/1c1YmQp6)<br/>
1.修复Bug<br/>

[v3.4](https://pan.baidu.com/s/11siIzBFlBdpKiGcN_VttDA)<br/>
1.AXML字符串常量池添加了对应的属性名显示同时去除一些不可编辑的属性<br/>
2.修复克隆时出现的EOFException问题<br/>
3.使用腾讯Bugly自动上传崩溃错误(本软件所需的位置信息以其他是供Bugly和DataEye这些数据统计网用的)<br/>
4.添加了Apk的选项对话框<br/>
5.添加了XML翻译模式(自动寻找出有字符串可编辑的xml文件)<br/>
6.克隆xml文件时根据文件头判断是否是xml文件，从而实现混资源淆过的apk能成功克隆<br/>
7.修复一些小错误<br/>

[v3.4.2](https://pan.baidu.com/s/1s_AxS_BJeODzTuk2rxZp4w)<br/>
1.修复部分崩溃<br/>

[v3.5](https://pan.baidu.com/s/1sQzE9kQxZFlcmbzKFTQIIQ)<br/>
1.修复部分问题<br/>
2.增加越南语言的支持<br/>
3.减小安装包体积<br/>

帮助翻译
==========================================================
如果你愿意，你可以帮作者翻译，语言文件在这[点击下载](https://pan.baidu.com/s/1UdAQWMmCraVMxtJQ0snBUw)

作者的其他作品
==========================================================
[ApkCrack](https://seaase.github.io/ApkCrack/)
