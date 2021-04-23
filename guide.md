## Markdown 语法
[markdown语法](https://www.markdown.xyz/basic-syntax/)

## vscode 代码编辑器
[vscode下载安装](https://code.visualstudio.com/)

VSCode 是一款编辑器。在我开始学习编程时，Sublime Text 都给人眼前一亮。
而随着编辑器的发展，VSCode 无疑是最流行最好用的那款,学习编程务必装好这个软件。

## git学习
[最好用的 Git 教程](https://learngitbranching.js.org/?locale=zh_CN)

常见简单指令

```shell
git add .			# 添加所有修改文件到暂存区
git add [ path ]			# 添加文件
git commit –m “XXXX”		# 提交文件
git push			#上传至远端
git pull			#下载至本地
git init 			# 初始化本地 git 仓库
git status			# 查看当前 git 仓库的状态
git log			# 查看 git 的提交信息
git branch			# 创建 git 分支
```
## github 国内访问问题

 复制下面的内容

# GitHub520 Host Start

```markdown
185.199.108.154               github.githubassets.com
140.82.112.22                 central.github.com
185.199.108.133               desktop.githubusercontent.com
185.199.108.153               assets-cdn.github.com
185.199.108.133               camo.githubusercontent.com
185.199.108.133               github.map.fastly.net
199.232.69.194                github.global.ssl.fastly.net
140.82.113.3                  gist.github.com
185.199.108.153               github.io
140.82.112.4                  github.com
140.82.112.5                  api.github.com
185.199.108.133               raw.githubusercontent.com
185.199.108.133               user-images.githubusercontent.com
185.199.108.133               favicons.githubusercontent.com
185.199.108.133               avatars5.githubusercontent.com
185.199.108.133               avatars4.githubusercontent.com
185.199.108.133               avatars3.githubusercontent.com
185.199.108.133               avatars2.githubusercontent.com
185.199.108.133               avatars1.githubusercontent.com
185.199.108.133               avatars0.githubusercontent.com
185.199.108.133               avatars.githubusercontent.com
140.82.113.9                  codeload.github.com
52.217.9.156                  github-cloud.s3.amazonaws.com
52.217.37.76                  github-com.s3.amazonaws.com
52.216.142.132                github-production-release-asset-2e65be.s3.amazonaws.com
52.217.85.124                 github-production-user-asset-6210df.s3.amazonaws.com
52.216.25.84                  github-production-repository-file-5c1aeb.s3.amazonaws.com
185.199.108.153               githubstatus.com
64.71.168.201                 github.community
185.199.108.133               media.githubusercontent.com
```

2.1 手动方式

2.1.1 修改 hosts 文件
hosts 文件在每个系统的位置不一，详情如下：

Windows 系统：C:\Windows\System32\drivers\etc\hosts
Linux 系统：/etc/hosts
Mac（苹果电脑）系统：/etc/hosts
Android（安卓）系统：/system/etc/hosts
iPhone（iOS）系统：/etc/hosts
修改方法，把第一步的内容复制到文本末尾：

Windows 使用记事本。
Linux、Mac 使用 Root 权限：sudo vi /etc/hosts。
iPhone、iPad 须越狱、Android 必须要 root。

2.1.2 激活生效
大部分情况下是直接生效，如未生效可尝试下面的办法，刷新 DNS：

Windows：在 CMD 窗口输入：ipconfig /flushdns

Linux 命令：sudo rcnscd restart

Mac 命令：sudo killall -HUP mDNSResponder

Tips： 上述方法无效可以尝试重启机器。

> 方法来源于 https://github.com/521xueweihan/GitHub520
