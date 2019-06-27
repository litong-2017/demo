# demo

### 查看远程分支详细信息
```git remote -v```

### 推送到远程主分支
```git push origin master```

### 推送到远程开发分支
```git push origin dev```

### 拉取远程主分支
```git pull origin master```

### 创建分支 (远程无dev分支)
```
git checkout -b dev      # 本地创建dev分支并切换到dev分支

git push origin master   # 推送本地dev分支到远程仓库
```
### 创建分支 (远程有dev分支)
```
git checkout -b dev      #新建并切换到本地dev分支

git pull origin dev      #本地分支与远程分支相关联
```


