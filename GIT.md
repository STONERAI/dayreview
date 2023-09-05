# GIT

```
Git是一个分布式版本控制系统。
```

## 一：Git工作机制

![未命名绘图.drawio](C:\Users\admin\Pictures\Camera Roll\未命名绘图.drawio.png)

## 二：Git和代码托管中心

```
局域网
GitLab
互联网
GitHub
Gitee
```

## 三：Git常用命令

```
git config --global user.name 用户名                          设置用户签名
git config --global user.email 邮箱							设置用户签名
git init                                                     初始化本地库（获取文件的管理权限）
git status                                                   查看本地库的状态
git add 文件名                                                添加到暂存区
git commit -m "日志信息" 文件名                                 提交到本地库
git reflog                                                    查看历史记录
git reset --hard 版本号                                        版本穿梭
```

![未命名绘图.drawio](C:\Users\admin\Pictures\Camera Roll\未命名绘图.drawio.png)

```
git链有三个部分组成
①：分支指针
②：head指针(用于切换分支)
③：版本节点
```

## 四：Git分支操作

```
git branch 分支名                创建分支
git branch -v                   查看分支
git checkout 分支名              切换分支
git merge    分支名              把指定的分支合并到当前分支上
```

```
git merge 产生冲突的原因为 同一个文件的同一个位置有两套完全不同的修改
```

## 五：远程仓库操作

```
git remote -v                     查看当前所有远程地址别名
git remote add 别名 远程地址        起别名
git push 别名 分支                 推送本地分支上的内容到远程仓库
git clone 远程地址                 将远程仓库的内容克隆到本地
git pull  远程地址别名 远程分支名    将远程仓库对于分支最新内容拉夏利后与当前本地分支直接合并
```

