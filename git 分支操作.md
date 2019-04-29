### 查看分支
> git branch -av
### 创建分支
> git branch {名称}

> git cheackout -b {名称} {基于那个分支} 穿件新分支  并切换到新分支上
### 切换分支
> git checkout {分支名}
### 删除分支
> git branch -D {分支名}

### 修改提交过的commit 的message
> git commit --amend 最近一次的变更

> git rebase -i {修改上一次}  *分布式不要用
### 比较暂存区 与 HEAD 的不同
> git diff --cached   可以用某个文件名称
### 把暂存区 恢复 成HEAD
> git reset HEAD  所有的
> git reset HEAD -- {文件名}
### 把工作区 变成暂存区的
> git checkout -- {文件名}
### 回退commit 
> git reset --hard {HASH值}  慎用
### 查看某两个分支的不同
> git diff {分支名} {分支名} -- {文件名}
### 删除文件
> git rm {文件名}
### 把缓存区 保存起来
> git stash {文件}

> git stash apply  把保存的拿出来  暂存还在
> git stash pop     把保存的拿出来  暂存就不在了
### 不需要管理的文件

> gitignore     git里搜索一下就行了


