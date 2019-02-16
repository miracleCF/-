# 常见git命令

### 1配置账户

```
git config --global user.name “your_username” #设置用户名
```

```
git config --global user.email “your_registered_github_Email” #设置邮箱地址(建议用注册giuhub的邮箱)
```

### 2clone已有仓库

```
git clone git@github.com:XXX/yyyy.git //XXX为github的用户名，yyy为仓库名
```

### 3查看文件状态

git status

### 4 提交

```
git add mmm.sss //mmm为文件名称，sss为文件拓展名（常用git add .）
git commit -m "hhh" //hhh为git commit 提交信息，是对这个提交的概述

git log//用于查看提交日志
git push //更新GitHub上的仓库
```

