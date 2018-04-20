#获取ip地址对应的实际地址
用法：

`composer require oscarhan/ip-get`


合并到本地项目，在项目中使用

`$ipLocation = new IpGet('../source/qqwry.dat');`
`$list = $ipLocation->getlocation($ip);`

qqwry.dat地址按照项目中实际地址填

效果：
输入
`$ip = '10.100.0.103';`
输出
`$location = '内蒙云基地';`