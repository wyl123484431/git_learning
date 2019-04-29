### 记录一些常见的git命令
### git 下载
> https://git-scm.com/download/win

> https://git-scm.com/download/mac

### 添加配置
> git config [--local | --global | --system] user.name 'Your name'

> git config [--local | --global | --system] user.email 'Your email'

### 查看配置
> git config  [--local | --global | --system] --list

### 清除设置
> git config --unset --local user.name

> git config --unset --global user.name

> git config --unset --system user.name

### 在本地新建一个git仓库
先进入到要创建的文件目录
> git init {文件夹的名称}

 cd 进入创建好的文件目录
 * **配置完成后 ls  -al 查看  .git 是隐藏的文件夹**

可以创建当前文件夹的配置信息
> git --config --local user.name 'your name'

> git --config --local user.email 'your email'

![avatar](https://s2.ax1x.com/2019/04/29/E1GPnP.png)

> git add {文件} 把文件提交到git  让git管控 提交到暂存区（stage）
> git add -u 把所有的都提交到暂存区

> git commit -m'解释'

> git status {文件} 查看文件状态

> git log {文件} 查看日志

![image](8A9140E4ACF8428CA374FA499D0885EF)

### 给文件重命名 快捷方式
> git mv {原文件名} {重新的命名}

> git commit -m'解释'

### 查看版本历史
> git log --oneline 简洁

> git log -n4 最近几次

> git branch -v 有几个分支

> git log --oneline --all 查看所有分支

> git log --oneline --all -n4

> git log --oneline {分支名}

> git log --oneline --all -n4 --graph 图形化的

> git help --web log 

### git 可视化工具
> gitk



