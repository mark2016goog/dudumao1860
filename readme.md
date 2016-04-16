## 安装kh\_mod ##

1) 使用一个FTP程序(例如WS\_FTP Lite)在你的Web服务器上创建一个新的目录, 例如: http://www.yourdomain.com/gallery

2) 上传kh\_mod\_041.zip压缩包中的所有文件(包括子文件) 至你的Web服务器上新创建的目录.

3) 使用FTP设置'data'文件夹和'pictures'文件夹的权限为777.

4) 点击打开你的浏览器，例如打开: http://www.yourdomain.com/gallery/

5) 按照向导安装.

6) 最后，你可以从http://www.tangata.de/kh\_mod/获取更多皮肤，存在版本兼容问题

7) Enjoy with kh\_mod


---


## 升级MG2/kh\_mod ##

1) 首先，你应该在管理面板，使用页面下面的“备份数据库”链接保存数据库文件，使用“备份数据库”(在kh\_mod 0.3.0或以上版本使用选择'备份当前数据库'，在菜单: 程序 | 设置).

2) 如果你使用MySQL, 在你升级相册之前，必须切换至'Flat file'(菜单: 程序 | 数据库).

3) 然后删除相册所有的文件和目录，以下文件除外:

- 图像目录 'pictures' - 插件目录 'skins/global' (如果存在) - 数据库目录 'data' (如果存在) - 文件: mg2\_settings.php (如果) - 文件: mg2db\_fdatabase.php - 文件: mg2db\_idatabase.php - 文件: mg2\_log.txt - 文件: database.txt (如果存在)

4) 使用FTP上传kh\_mod.zip压缩包中的所有文件至服务器上相册目录

5) 然后在浏览器地址栏中输入:http://www.yourdomain.com/gallery/mg2_update.php，升级至kh_mod最新版

6) 最后，你可以从http://www.tangata.de/kh\_mod/获取更多皮肤，存在版本兼容问题

7) Enjoy with kh\_mod



---


## MySQL支持 (可选) ##

为了使用MySQL，根据MySQL服务器配置'mg2admin\_sqlstart.php'.

然后,你必须在菜单'选项 | 数据库'的'切换数据库'选择MySQL.

如果提示'成功切换至MySQL',在你的MySQL数据库里会创建一些新的包含相应数据记录的数据表:

- mg2db\_folders

- mg2db\_items

- mg2db\_splashes

- mg2db\_keywords

- mg2db\_item\_keyword -

> mg2db\_counter

- mg2db\_settings

**注意: 同一个数据库只能安装一个相册!**