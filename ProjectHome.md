
---


## kh\_mod中文发布： ##

<font color='red'>kh_mod 0.4.2   简体中文版发布 （2013.10.20）</font>

kh\_mod 0.4.1       简体中文版发布 （2012.12.12）

kh\_mod 0.4.0 pl3   小BUG修复更新 （2012.09.16）

kh\_mod 0.4.0 pl1   小BUG修复更新 （2012.02.22）

kh\_mod 0.4.0 final 简体中文版发布（2012.02.16）

kh\_mod 0.4.0 final 中文语言包发布（2012.02.15）

kh\_mod 0.4.0 b4    简体中文版发布（2011.08.05）

kh\_mod 0.3.3       简体中文版发布（2010.03.27）

**同步镜像**：http://code.google.com/p/kh-mod/

**问题反馈**：http://code.google.com/p/dudumao1860/issues/list


---


## kh\_mod更新记录： ##

**kh\_mod 0.4.2简体中文版（20131020）**

- 修复: 一些关于sql(MySQL) "传统" 模式的问题

- MySQL接口MySQLi支持PHP 5.4及以上。如果在用一个低版本的PHP，新版本的接口一样可以使用

- 增加"每日统计" (选项|统计|点击统计)管理

- 控制面板增加“最新导入项目”系统目录，该目录包含所有最近上传和最近导入的文件

- 增加了"强制缩略图至设定值"选项, 如果输入同样的高度和宽度（选项|设置），现在将会生成方形缩略图

- Flowplayer的版本升级至3.2.16

- JSColor的版本升级至1.4.1

- Colorbox的版本升级至1.4.7 (最新版本支持IE6)

- 旋转图片的内存占用减少到30%

- "mg2admin\_convert.php"更名为"mg2admin\_converter.php"，同时也对代码进行了重写

- 如果数据库从平面文件切换到MySQL或者切换回去，现在会显示MySQL的计数器和关键词的记录数值。在早期的版本，所有文件（图片、视频或者音频）的数据仅作为一个数据记录。
由于这个原因，现在记录的数值要比过去的版本高。


- 在管理员邮箱中关于最新评论的通知中将会增加站点页面编码，尽可能避免邮件中的文本显示错误, 除此之外, 移除任何主题栏的标签

- 基于WebKit核心浏览器(Google Chrome, Safari等)，修复控制面板界面的一些显示问题

- 一些小修复

- 更新语言包

**kh\_mod 0.4.1简体中文版（20121212）**

- 修复: 一些与"windows-1253" (Greek)字符集相关的问题

- Flowplayer升级到3.2.15

- JSColor升级到1.4.0

- Colorbox升级到1.3.20.1

- 增加支持拖放排序的选项，例如排序信息、日期、文件日期和随机排序等

- 上传和导入模块被重写，特别是支持对大数据的导入

- 基于Exif信息自动对JPG图片排序支持

- 增加链接文件夹，它的意思是当鼠标单击该文件夹，并不会打开缩略图，而是打开一个网页链接

- '所有图片'被重命名为'所有条目' (在所有相关文件)

- 在admin.php文件中关闭E\_STRICT错误

- 一些小的修复

- 更新语言包

**~~kh\_mod 0.4.0 pl3（20120916）~~该版本未提供中文版更新**

**~~kh\_mod 0.4.0 pl1（20120222）~~该版本未提供中文版更新**

**kh\_mod 0.4.0 final简体中文版（20120216）**

- 修复【删除原始文件】-【上传】/【导入】BUG

**kh\_mod 0.4.0 final简体中文版（20110216）**

- 修正: 在kh\_mod 0.4.0 rc1版本的上传过程中，如果在服务器同路径下有同名文件将会报错.

- 修正: 一些在与其他HTML页面整合时的文件路径错误

- JSColor更新至version 1.3.12

- 完善皮肤以兼容HTML 5

- 其它一些小的修复

- 对安装和升级过程汉化，简体中文版默认使用中文语言包

- 更新语言包，修正更新部分词条

**~~kh\_mod 0.4.0 rc2（20120107）~~该版本未提供中文版更新**

**~~kh\_mod 0.4.0 rc1（20111221）~~该版本未提供中文版更新**

具体参见：http://code.google.com/p/dudumao1860/wiki/Changelog


---


## kh\_mod协作介绍： ##

kh\_mod 0.4.0 final是基于MG2 v0.5.1的一款免费的相册管理程序。

相比MG2的简洁，kh\_mod的功能更强大一些。

本程序由dudumao和CU Klemens共同编写完成。


---


## kh\_mod在线演示： ##

中文演示：http://img.dudumao.net/

德文演示：http://www.tangata.de/fotos_final/?ln=en


---


## kh\_mod功能特点： ##

● 无需数据库即可使用，也可以在后台切换至Mysql数据库

● HTTP方式在线上传，FTP/SSH上传根目录导入

● 相册无限级向下分级，自由拖拽排序

● 相册缩略图自动生成，相册封面固定/随机显示图片

● 代码架构合理，极速明快，执行效率高

● 图像/相册支持隐藏、加密以及定时发布等

● 相册支持图片/音频/视频等类型的媒体文件发布

● 支持图片评论，评论信息通过Email通知管理员

● 可启用伪静态，易于SEO优化，便于外链地址使用


---


## kh\_mod安装升级： ##

### kh\_mod 的安装 ###

1.下载本站汉化版，并上传到服务器；

2.使用FTP上传工具设置data文件夹和pictures文件夹的\*权限\*为777；

3.打开http://yourdomain ， 点击页面底部按钮，系统自动配置，填写账号和密码，安装完成；

4.系统在初始化安装阶段已修改默认修改中文语言包；

5.kh\_mod 0.3.3中文版完成安装。

### kh\_mod 的升级 ###

根据程序附带的说明文档readme.txt中的升级方法进行升级！

---


## MYSQL数据库启用： ##


打开/includes/mg2admin\_sqlstart.php；

分别修改以下四个参数：


define('DB\_NAME', 'mg2\_db');		// 数据库名称

define('DB\_USERNAME', 'root');	        // 数据库用户名

define('DB\_PASSWORD', '');		// 数据库密码

define('DB\_SERVER','localhost');       // 数据库服务器地址




---


## kh\_mod 的下载 ##

kh\_mod 各版本英文原版、简体中文版、语言包、皮肤插件下载：http://code.google.com/p/dudumao1860/downloads/list


分流下载1：http://down.chinaz.com/soft/26668.htm

分流下载2：http://down.admin5.com/code_php/44053.html

分流下载3：http://www.codepub.com/d/downpage.php?n=1&id=17469::1267152332

分流下载4：http://www.softhy.net/soft/22000.htm

分流下载5：http://www.codefans.net/soft/7905.shtml

分流下载6：http://www.hicode.cn/download/kh-mod-11430.html

分流下载7：http://www.downcode.com/downcode/j_15320.shtml

分流下在8：http://code.knowsky.com/down/15982.html


Copyright (C) 2012  All Rights Reserved.