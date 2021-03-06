# Hash
1. **一个建立Hash验证和验证Hash的Shell**
2. **一个计算hash的页面（只支持字符串）** [连接](https://invalidcode.github.io/hash-web/)

## 帮助
```
帮助：
	[必选]
		[-u|-c]	   建立|验证
		[-m|-s]	    md5|sha1
		[-f File]	位置
	[可选]
		[-v]	显示过程
	[其他]
		[-h]	帮助
版本：
	Beta:1.45.1
```
## 范例
```
$ ls
hash
$ ./hash -umsvf hash
开始建立验证:
正在建立md5验证:
ac62b3ad05d95ec1084e0fa9c18c8c56  ./hash
建立md5验证成功！
正在建立sha1验证:
613ca708817a08c127ab6819f2eef607dda4c369  ./hash
建立sha1验证成功！
建立验证成功！
$ ./hash -cmsvf hash
开始验证:
正在md5验证:
./hash: 成功
md5验证成功！
正在sha1验证:
./hash: 成功
sha1验证成功！
验证成功！
```
## 更新
1. 修复无法建立文件夹内文件的Hash
2. 优化显示
3. 抛弃提示和输入，采用选项和参数
3. 优化运行速度，加快50%
4. 加入Github，正式开源
5. 修复显示空行BUG

## 计划
1. 修复测试BUG
2. 优化显示，提高用户体验

