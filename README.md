# gitnotess
My git Note

我的git学习笔记
=======================

## 1.1 设置
### 1.1.1 设置姓名、邮箱
```git
      $ git config --global user.name "pooking"
      $ git config --global user.email "pookingcn@gmail.com"
```

### 1.1.2 设置行尾
#### unix/mac:
    $ git config --global core.autocrlf input
    $ git config --global core.selfcrlf true
#### windows:
    $ git config --global core.autocrlf true
    $ git config --global core.selfcrlf true
    
-----------------------

## 2.1 创建项目
> 创建仓库

### 从零新建项目
创建目录

    $ mkdir codeDir
    $ cd codeDir
    
初始化

    $ git init
    
新建、提交文件
    
    $ touch 1.txt
    $ git add 1.txt
    $ git commit -m "提交说明"
    
> 说明
> 该操作执行后，文件同步到本地仓库

    
    
    
