# 常见问题
## 插件启用篇
- 检查插件文件夹名称为`ZFonts`（大小写敏感）
- 检查服务器是否能连接到`https://auth.zfonts.cn/`，且确认该域名是否已授权
- php最低`5.5+`，建议`7.1+`（正确检查方式是在你的服务器新建一个`test.php`，然后复制粘贴该代码`<?php phpinfo(); ?>`，最后在浏览器访问该文件可以查看`服务器的php信息`）
- 插件目录给`777`权限，包括递归子文件夹和子文件，也可以尝试给`644`或者`755`权限。因为有的服务器上传文件之后，默认给的权限php都无法执行
- 如果是`FTP`上传的文件，需要在`FTP软件`的`传输`-`传输类型`中选择`二进制上传方式`
- 最后确保自己上传的文件没有缺失，比如`ZFonts`文件夹下有`Plugin.php`等文件
## 字体样式篇
- 某些主题可能会发生`样式错乱`，如有情况，请及时`反馈`作者。
- 若该主题已将字体样式`写死`，将`不会产生效果`
## 售后服务篇
- 因插件是`可复制`的商品，购买后`不支持退款`