# 字字动画 Jimeng 无限并发插件

正式版本发布与自动更新仓库。

## 下载与安装

请前往 [最新正式版](https://github.com/IDENTITYRS/jimeng-updates/releases/latest)，下载名称以 `-full.zip` 结尾的完整安装包。解压插件文件夹至字字动画的 `_internal/plugins/video_plugins`，重启软件并选择插件，按原有授权方式激活。

## 自动更新

插件设置中的“版本更新”板块会在打开时检查更新，也可手动检查。发现新版后点击更新按钮，完成下载和签名校验后，独立更新助手会提示退出字字动画。完全退出后自动安装，再重新打开软件。

更新保留账号、授权、配置、任务记录及模型缓存。安装失败自动恢复旧版本。更新直接使用公开 GitHub Release，无需登录 GitHub。

## Release 附件

- `jimeng-版本-full.zip`：首次安装的完整插件包。
- `jimeng-版本.zip`：插件自动更新使用的程序包。
- `update.json`：版本、更新内容和 SHA-256 校验清单。
- `update.sig`：更新清单的 RSA 签名。

只上传干净的发布程序，不包含账号、授权记录、浏览器数据或签名私钥。完整更新记录见 [CHANGELOG.md](CHANGELOG.md)。
