# Git入门

## 安装Git
针对不同的操作系统，从https://git-scm.com/downloads下载对应的安装版本进行安装

* 中文版的《Pro Git》是完全免费的： https://git-scm.com/book/zh/v2 

## 拉取远程代码
使用命令行：
```
git clone https://github.com/codeoria/python-1
```

使用VSCode
点击左侧第三个按钮，选择从代码仓克隆，输入网址，即可自动下载完成

## 修改用户名和email
Git允许配置全局的和针对项目的用户名和Email， 这个用户名和Email将会显示在代码修改的记录里，表面由谁修改了这部分代码
* 全局的设置如下：
```
# 从VS Code 的菜单栏“Terminal”启动一个新窗口，输入以下命令，注意替换你自己的用户名和Email
git config --global user.name "Harry Codeoria"
git config --global user.email "harrycodeoria@gmail.com"
```

* 针对项目的配置如下， 我喜欢这种方式，因为我有多个项目以不同的用户名来提交来吗
```
git config --local user.name "Harry Codeoria"
git config --local user.email "harrycodeoria@gmail.com"
```



