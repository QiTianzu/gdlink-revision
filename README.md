# gdlink-revision
Google Drive 文件直链获取脚本 gdlink 修改版

## 原版 gdlink 下载网址
https://www.moerats.com/usr/shell/gdlink.sh

## gdlink 使用教程
### Google Drive网盘文件直链获取一键脚本 - Rat's Blog
https://www.moerats.com/archives/571/

## gdlink_api
如果您的文件大小小于 100MB，则使用 gdlink 即可。如果您的文件大小大于 100MB，在网页上下载时 Google 将显示“文件过大，Google 无法扫描病毒。”的警告，而不是下载文件。要绕过警告，您需要使用 gdlink_api，使用方法和 gdlink 类似，您只需要将 'Google Drive 文件共享链接'（也可以是文件ID）和 Google Drive API key 作为 gdlink_api 脚本的两个参数即可。使用 gdlink_api 时，可选择是否将 Google Drive API key 保存到脚本中，若选择保存，则下次使用时可不指定 Google Drive API key。

参考自：https://www.wonderplugin.com/online-tools/google-drive-direct-link-generator/

如何申请 Google Drive API key：https://www.wonderplugin.com/wordpress-tutorials/how-to-apply-for-a-google-drive-api-key/
