# kh\_mod 0.4.2, 10.20.2013 #

  * 修复: 一些关于sql(MySQL) "传统" 模式的问题
  * MySQL接口MySQLi支持PHP 5.4及以上。如果在用一个低版本的PHP，新版本的接口一样可以使用
  * 增加"每日统计" (选项|统计|点击统计)管理
  * 控制面板增加“最新导入项目”系统目录，该目录包含所有最近上传和最近导入的文件
  * 增加了"强制缩略图至设定值"选项, 如果输入同样的高度和宽度（选项|设置），现在将会生成方形缩略图
  * Flowplayer的版本升级至3.2.16
  * JSColor的版本升级至1.4.1
  * Colorbox的版本升级至1.4.7 (最新版本支持IE6)
  * 旋转图片的内存占用减少到30%
  * "mg2admin\_convert.php"更名为"mg2admin\_converter.php"，同时也对代码进行了重写
  * 如果数据库从平面文件切换到MySQL或者切换回去，现在会显示MySQL的计数器和关键词的记录数值。在早期的版本，所有文件（图片、视频或者音频）的数据仅作为一个数据记录。
由于这个原因，现在记录的数值要比过去的版本高。
  * 在管理员邮箱中关于最新评论的通知中将会增加站点页面编码，尽可能避免邮件中的文本显示错误, 除此之外, 移除任何主题栏的标签
  * 基于WebKit核心浏览器(Google Chrome, Safari等)，修复控制面板界面的一些显示问题
  * 一些小修复
  * 更新语言包

# kh\_mod 0.4.1, 12.12.2012 #

  * 修复: 一些与"windows-1253" (Greek)字符集相关的问题
  * Flowplayer升级到3.2.15
  * JSColor升级到1.4.0
  * Colorbox升级到1.3.20.1
  * 增加支持拖放排序的选项，例如排序信息、日期、文件日期和随机排序等
  * 上传和导入模块被重写，特别是支持对大数据的导入
  * 基于Exif信息自动对JPG图片排序支持
  * 增加链接文件夹，它的意思是当鼠标单击该文件夹，并不会打开缩略图，而是打开一个网页链接
  * '所有图片'被重命名为'所有条目' (在所有相关文件)
  * 在admin.php文件中关闭E\_STRICT错误
  * 一些小的修复
  * 更新语言包

# kh\_mod 0.4.0 final, 15.02.2012 #

  * 修正: 在kh\_mod 0.4.0 rc1版本的上传过程中，如果在服务器同路径下有同名文件将会报错.
  * 修正: 一些在与其他HTML页面整合时的文件路径错误
  * JSColor更新至version 1.3.12
  * 完善皮肤以兼容HTML 5
  * 其它一些小的修复
  * 更新语言包

# kh\_mod 0.4.0 rc2, 07.01.2012 #
  * 修正: 在Flat file模式下归档文件不能被创建
  * 统计分析中的设置永久保存
  * 在MySQL数据库的mg2db\_chronicle表中增加statisticsets字段
  * Colorbox更新至version 1.3.19
  * Prototype更新至version 1.7.0
  * Scriptaculous更新至version 1.9.0
  * 方便改变画廊相册的语言情况下有必要使用全名
  * 其它一些小的修复

# kh\_mod 0.4.0 rc1, 21.12.2011 #

  * 皮肤进一步改进
  * 管理面板增加关键词项
  * 管理面板增加书签图片
  * 增加统计分析
  * MySQL数据库增加mg2db\_chronicle表
  * Flowplayer更新至version 3.2.7
  * Colorbox更新至version 1.3.17.1
  * Download function was added
  * 其他一些小的改进
  * 其它一些小的修复
  * 更新语言包

# 0.4.0 b4, 16.12.2010 #

  * 皮肤全面修复
  * 缩略图排列增加自动、居中、自适应属性值
  * 包含空子相册的相册也可以被删除
  * 相册支持拖拽分类
  * 画廊支持关键词
  * 数据表增加keywords和item\_keyword字段
  * FCKeditor编辑器版本升级至2.6.6
  * Flowplayer播放器版本升级至3.2.5
  * Colorbox弹窗特效1.3.15支持全尺寸查看图像
  * 如果一个重要的进程超时中断，可以通过刷新浏览器继续
  * 考虑到可用存储的测定，PHP环境的全局设置，例如作为htaccess文件
  * 缩略图显示增加URL编码
  * 在安装和相册中增加HTTP-Header 'X-Frame-Options: SAMEORIGIN'
  * 在更新和管理中增加HTTP-Header 'X-Frame-Options: DENY'
  * 安装过程中, 最重要的文件通过SHA1验证
  * 管理密码加密把MD5改为SHA1 (incl. salt)
  * '/skins/_global_'目录被重命名为'addons'并移动至相册根目录
  * mg2db\_fdatabase.php被重名为mg2db\_folders.php
  * mg2db\_idatabase.php被重名为mg2db\_items.php
  * mg2db\_fdatabase数据库表名重命名为mg2db\_folders
  * mg2db\_idatabase数据库表名重命名为mg2db\_items
  * 备份文件被移动到'/data/backup'目录下
  * 高级选项增加“重建修复”功能
  * 幻灯显示增加暂停功能
  * 一些小的改进
  * 一些小的修复
  * 更新语言文件

# 0.3.3, Jan 15, 2010 #

  * New: In the admin area (table view), there are also tooltips available for folders with thumbnails.
  * Update: Prototype to version 1.6.1
  * Update: Scriptaculous to version 1.8.3
  * Changed: The data structure of the MySQL table 'idatabase'
  * Changed: If an import session breaks off based on timeout (maximum execution time), it can be continued by the reload button (browser).
  * Changed: The Exif module was revised.
  * Further minor improvements
  * Several minor fixes


# 0.4.0 b3, Jan 15, 2010 #

  * New: Splash-Images for video and sound content.
  * New: Key word support for pictures, videos etc. (experimental)
  * Update: Flowplayer to version 3.1.5
  * Update: Prototype to version 1.6.1
  * Update: Scriptaculous to version 1.8.3
  * Update: FCKEditor to version 2.6.5
  * Update: WZ Tooltips to version 5.3.1
  * Changed: The data structure of the MySQL table 'idatabase'.
  * Changed: The comment functions were concluded as module in an apart class/file.
  * Changed: The Exif module was revised.
  * Further minor improvements
  * Several minor fixes
  * Updating of languages


# 0.3.2, Jun 07, 2009 #
  * Fixed: In the log entry 'New settings saved' the file name was missing.
  * Changed: The API for the addon 'Random Picture' adapted ('remoteID', 'GALLERY\_ID').
  * Changed: The Tab Control in the admin area (Menu 'Setup') adapted for MSIE 8.
  * New: In the view 'Table' (admin area) the number of pictures of each folder (incl. subfolders) is displayed.
  * New: In the view 'Table' (admin area) all rebuild buttons are protected by a JavaScript dialog.
  * Some minor fixes

# 0.4.0 b2, May 03, 2009 #
  * Fixed: The gallery view 'Thumbnails' was broken sometimes, since a function (mb\_check\_encoding) was called which is missing in PHP less than 4.4.3.
  * Fixed: On uploading or importing pictures with PHP 5.1.2 or above, the function (imagepng) for creating thumbnails obtained an invalid parameter for the image compression.
  * Changed: In the view 'Category' (Menu 'Setup', Option 'Display folders as categories') all pictures in the subfolders are counted now. Beforehand were considered maximally two levels only.
  * Changed: The implementation of the HTML-Editor was improved in the admin area.
  * Changed: Flowplayer updated to version 3.1.0
  * New: Audio-Support of MP3-files by Flowplayer
  * Some minor fixes

# 0.3.1a, Apr. 26, 2009 #
  * Fixed: The gallery view 'Thumbnails' was broken sometimes, since a function (mb\_check\_encoding) was called which is missing in PHP less than 4.4.3.
  * Fixed: On uploading or importing pictures with PHP 5.1.2 or above, the function (imagepng) for creating thumbnails obtained an invalid parameter for the image compression.
  * Changed: In the view 'Category' (Menu 'Setup', Option 'Display folders as categories') all pictures in the subfolders are counted now. Beforehand were considered maximally two levels only.
  * Changed: The implementation of the HTML-Editor was improved in the admin area.
  * Some minor fixes

# 0.4.0 b1, Apr. 12, 2009 #
  * New: Video support for MP4, MOV und FLV by the Flowplayer 3.0.7
  * Changed: Online-Editor HTMLArea replaced by the FCKEditor 2.6.4

# 0.3.1, Apr. 12, 2009 #
  * Fixed: An empty gallery (without pictures) couldn't switch from Flatfile to MySQL.
  * Fixed: In the flatfile mode not all pictures could be deleted. At least one picture had to stay in the gallery.
  * Fixed: If still no folder were created, thus existing pictures were not displayed in the gallery!
  * Fixed: If the comment counter was switched off and on as well as at the same time a comment was posted, thus the number of comments was not correctly determined.
  * Fixed: During the processing of a date with the month in three characters, a function (stripos) missing in PHP 4.x was used.
  * Fixed: In the Folder and Picture Editor the time statement 'PM' resp. 'p.m.' was ignored.
  * Fixed: If in the dialogs 'Upload' or 'Import' the option 'Delete originals' was selected, nevertheless the size of the original picture was displayed instead of the smaller one.
  * Changed: The display of 'mg2\_log.txt' is completely filtered. Which means that all applicable characters are converted to HTML entities.
  * Changed: If the file 'mg2\_log.txt' is greater than 300 KByte, thus it will be no longer completely deleted, but the last 360 entries remain.
  * Changed: Before thumbnails will be created or pictures rotated, first the required main memory is calculated.
  * Changed: Now, thumbnails are created in the format of the original picture. This means that thumbs of PNG pictures are saved in the PNG format, thumbs of GIF pictures are saved in the GIF format and so on (before thumbnails were always saved in the JPEG format).
  * Changed: Still existing links to MG2 (www.minigal.dk) were completely removed.
  * Changed: In the file 'style.css' of all skins the selector 'table.category' is extended by 'text-align:left;'. Thus the justification in the view 'Category' is left also in MSIE 7.0 and Opera 9.0 or above.
  * New: All Event Handlers will be removed from the comment entries, e.g. 'onMouseOver'.
  * New: The intro text in the view 'Category' can be set global to 'Force align left' and 'Force justify' (Menu 'Setup', Section 'Folder content').
  * New: In the Menu 'Setup | Server' the size and access permissions of important gallery files will be displayed.
  * A lot of minor fixes
  * Updating of languages

# 0.3.0 final, Oct. 31, 2008 #
  * New: In the admin login the cursor is set in the password field by JavaScript.
  * Some minor fixes

# 0.2.4, Oct. 29, 2008 #
  * Fixed: Bug introduced with kh\_mod version 0.2.3: Items will be sorted according to their ID, not to their name, although the sorting mode is selected 'Name'.
  * Fixed: The import of MG2 0.5.0/0.5.1 image data mixed thumbnail height with timestamp.
  * New: In the admin login the cursor will set in the password field by JavaScript.
  * Some minor fixes

# 0.3.0 rc2, Oct. 04, 2008 #
  * Fixed: The import of MG2 0.5.0/0.5.1 image data mixed thumbnail height with timestamp.
  * Changed: Updating file 'password.php' in all skins
  * Some minor fixes and improvements
  * Updating of languages

# 0.3.0 rc1, Aug. 15, 2008 #
  * Fixed: Bug introduced with kh\_mod version 0.3.0 b5 resp. 0.2.3: Items will be sorted according to their ID, not to their name, although the sorting mode is selected 'Name'.
  * New: SEO-Links, e.g. 'image180.html' (optional)
  * New: Admin mode for gallery. This will automatically be activated, if you call the gallery via admin area. In admin mode, counters will be locked and passwords will not be checked for protected folders.
  * New: Time format selectable, e.g. Hour:Minute AM/PM
  * Changed: The captcha addon works also without Freetype support.
  * Some minor fixes and improvements
  * Updating of languages

# 0.3.0 b6, Jun. 06, 2008 #
  * New: HTTP Header inserted in 'index.php' and 'admin.php' for included JavaScript.
  * New: HTTP Header inserted in 'index.php' and 'admin.php' for included CSS.
  * New: HTTP-Header 'X-Robots-Tag' selectable in the admin area.
  * New: HTML-Metatags 'noarchive' and 'nosnippet' selectable in the admin area.
  * New: Comments can be verified by captcha, white- and blacklist (Menu 'Setup/Comments').
  * New: The comment form can be hidden in the image view (Menu Setup/Comments).
  * New: Restore module (Menu 'Setup/Database')
  * New: Backup files deletable in the admin area (Menu 'Setup/Database').
  * New: Counter management with MySQL support (optional).
  * New: The web server can be set on the character set of the language file (Menu 'Setup/Advanced').
  * New: Language file splitted in 'xx\_XX.admin.php' and 'xx\_XX.gallery.php'.
  * New: Gallery View 'Categories' for folder in all skins (optional).
  * New: 'Latest image' as folder icon selectable (Folder Editor).
  * New: Automatic setting of new folder positions (Folder Editor).
  * New: Tooltips for thumbnails in the gallery (optional)
  * Changed: Skins were completely revised.
  * Changed: Improved Exif data display
  * Some minor fixes and improvements
  * Updating of languages


# 0.2.3, May 16, 2008 #
  * Fixed: In the skins 'rounded' and 'framed' didn't display the file 'thumbs.php', if comments are present.
  * New: HTTP Header inserted in 'index.php' und 'admin.php' for included JavaScript
  * New: HTTP Header inserted in 'index.php' und 'admin.php' for included CSS
  * New: 12 new date formats
  * Changed: Improved Exif data display
  * Changed: Improved MSIE 7/Vista compatibility
  * Some minor fixes and improvements

# 0.3.0 b5, Apr. 15, 2008 #
  * New: The programming of click and comment counter was redesigned and the file format adapted to MG2.
  * New: Backup module (Menu 'Setup/Database')
  * New: Image sorting by drag 'n' drop completely integrates (Folder Editor, button beside 'Position').
  * New: 12 new date formats
  * Changed: MySQL support improvements
  * Changed: Improved MSIE 7/Vista compatibility
  * Some minor fixes and improvements
  * Updating of languages

# 0.3.0 b4, Mar. 03, 2008 #
  * New: Click and comment counter was integrated into the gallery.
  * New: Display of the file name changeable (upper and lower case, with and without extension).
  * Changed: MySQL support revised.
  * Some minor fixes and improvements

# 0.2.2, Dec. 31, 2007 #
  * Fixed: Error in calculation of image size corrected.
  * Changed: The update function 'check\_new\_version' removed for MG2.
  * Changed: Function to create thumbnails and mediums optimized.
  * Some minor fixes and improvements

# 0.3.0 b3, Dec. 31, 2007 #
  * Changed: The update function 'check\_new\_version' removed for MG2.
  * New: Directory structure of the server importable (Menu 'importing').
  * New: Extended options for the selection of folder icons (Folder Editor).
  * New: Number of columns and rows can be set different for each folder.
  * New: Behavior with mouse-click on image in the menu 'setup' selectable
('With mouse-click on image go to').
  * New: Images can be protected by transparent GIF.
  * New: File name can be displayed as image headline (Menu 'Setup').
  * New: Image headline as 'alt' attribute usable (Menu 'Setup').
  * Some minor fixes and improvements

# 0.3.0 b2a, Nov. 09, 2007 #
  * Changed: The update function 'check\_new\_version' deactivated for MG2.
  * Some minor fixes and improvements

# 0.3.0 b2, Oct. 31, 2007 #
  * New: MySQL support (experimental)
  * New: New comments become locked (optional)
  * New: The email addresses in comments can be hidden for the gallery
  * New: Comments can be locked and unlocked, resp. (Picture Editor)
  * Some minor fixes and improvements

# 0.3.0 b1, July 8, 2007 #
  * New: Image sorting by drag 'n' drop (Folder Editor, button beside 'Position').
  * New: Random icons for folders can be also created from contained subfolders (Folder Editor).
  * New: Extended upload options (Menu 'Upload'), e.g. target directory on web server.
  * New: Extended import options (Menu 'Import').
  * New: Display of important web server settings (Menu 'Setup/Server').
  * New: Further setting options designated in the 'Setup' menu.

# 0.2.1, May 19, 2007 #
  * Changed: There are new parameters for the call of pictures 'iID' and folders 'fID' in version 0.2.0. Thus old links were no longer valid to pictures and folders. In 0.2.1 both the new and the old parameters 'id' and 'list' can be used.
  * Fixed: The setting HTML Metatag 'robots' in the admin area didn't run correctly
  * Fixed: Incompatibility to PHP5 in 'mg2\_functions.php'.
  * Fixed: Display error with Opera 9.20 in 'viewimage\_exif.php' for all skins.

# 0.2.0 final, Apr. 30, 2007 #
  * New: Entry 'Photographer' in the Picture Editor.
  * New: Gallery title, folder name, file name and Image title can be used for the meta tag 'title'.
  * New: Meta tag 'robots' selectable by admin inteface.
  * New: Extended Exif display, all values can be switched off one by one.
  * New: Improved the calculation of the Exif value 'Exposure time' for cellphone cams.
  * New: Thumbnail bar for image navigation (optional).
  * New: Logging of IP and host with comment entries (optional).
  * New: 'data' directory for database and log files.
  * Some minor fixes and improvements
  * Adaption of standard skins
  * Updating of languages

# 0.2.0 b1, Feb. 28, 2007 #
  * New: Overwrite existing images by web interface (menu 'Upload').
  * New: Support of subfolders for pictures.
  * New: The data base works now with associative arraies, so that the indices of the pictures and folders are identical to the respective array index.

# 0.1.0 pl1, Jan. 25, 2007 #
  * Fixed: Access to Admin area without password.
  * New: Displaying the number of comments per picture in the table view (Admin).

# 0.1.0 final, Dec. 24, 2006 #
  * Fixed: 'exif.php' revised, 'ExposureTime', 'ShutterSpeed', 'Flash', 'ApertureWidth' and 'MaxApertureWidth' supply now correct values.
  * Fixed: The format of date '%Y%m%d' could not be recognized by JS Calendar, e.g. the calendar indicated to NaN at '20050830, 20:35' everywhere.
  * Fixed: Empties bold tags into 'viewimage\_begin.php' line 13 against CSS exchanged.
  * Changed: XML attribute added to all html tags.
  * Changed: Unnecessary program code removes, 'dec2frac()' and 'getlanguages()' from 'mg2\_function.php'
  * Changed: If the entered date isn't recognized (in the picture or folder editor), the stored date is no longer changed to the current date.
  * New: Click counter basic functions integrates in 'mg2\_function.php' for the counter addon.
  * New: Language selection in the gallery now also possible by $_GET, e.g. &ln=en (ISO 639-1). The language selection is saved in the session variable '$selectlang'.
  * New: Variable '$mg2->modversion' defines for the version of kh\_mod.
  * New: The eMail address in the admin setup is verified now by PHP.
  * New: Format of date '%e/%m %Y' added, e.g. 3/11 2008
  * New: 'lang' directory protected by '.htaccess'
  * Some minor fixes and improvements
  * Updated languages_

# 0.1.0 b3, Nov. 28, 2006 #
  * Fixed: Except the root folder no other folder could be opened (only with the update).
  * Fixed: In each case the first comment of a picture was sent as email to the Admin.
  * Fixed: The name of root folder was set automatically, if it did not exist.
  * Fixed: Sometimes problems with the recognition of the language files, during the installation of full version.
  * Fixed: Thumbnails within the admin area have displayed sometimes the date of the previous picture.
  * Fixed: HTMLArea text formatting error eliminates.
  * Changed: Comment delete function protected against inadvertent deletion by 'Reload Button'.
  * Changed: Date functions revises, changed over from 'date()' to 'strftime()' and date locates.
  * Changed: 'viewimage\_comment.php' adapted to new format of date.
  * Changed: For Exif 'Original' date now 'DTOpticalCapture' is used instead 'DateTime'.
  * Changed: The value of the HTTP charset header is determined now by the loaded language file.
  * Changed: Special characters for the verification of inputs are now in the language files.
  * Changed: The output buffer of status messages for rebuilding thumbs, is now switched off.
  * Changed: HTMLArea file 'htmlarea.js' was compressed.
  * Changed: 'admin.css' with the Font 'Helvetica' supplements.
  * New: Calendar Theme 'calendar\_mg2.css'
  * New: 'includes' folder protected by '.htaccess'
  * New: Workaround by 'touch()' for the function 'imagejpeg()' inserted, for 'safe mode' only.
  * New: If active skin is no longer present, now an error message is indicated after login.
  * Some minor fixes and improvements
  * Updated languages

# 0.1.0 b2, Nov. 04, 2006 #
  * Folders are sortable according to different criteria.
  * Numbers for folders and pictures as sorting criterion.
  * Folders and individual pictures can be locked.
  * Folders and pictures can be published automatically on a determinate date.
  * Displaying file names under the thumbnails (optional).
  * Thumbnails size in the admin area adjustable.
  * All thumbnails of a folder can be generated at one go.
  * Arbitrary name for the root folder selectable.
  * With the picture upload and import, the target folder is freely selectable.
  * The passwort protection of folders is applying to subfolders, too (optional).
  * Comments are editable now in the admin area.
  * Comment files will be deleted from the admin area, if no entry is more contained there.
  * Comments can be verified by JavaScript (optional).
  * Form verification for comments by PHP, in especially to a formally correct email address.
  * Contents of incorrect forms for comments are repeated indicated.
  * Comments de- and ascending sortable.
  * Rotation of GIF pictures (if by the installed GD version supports).
  * Tooltips for mini thumbs available (admin area).
  * All JavaScript functions (HTMLArea, Tooltips etc.) can be switched off one by one.