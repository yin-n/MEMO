# Git - Pycharm

### Git proxy：

```git

git config --global --unset http.proxy

git config --global --unset https.proxy


```

### 如何将pycharm的项目提交到github：

#### 	1.首先,要在settings--version control里面添加自己的账号 

选择用login via tokens

**那么如何生成tokens?**
    
在github网页--settings--Developer settings--Personal access tokens--Generate new token(note 随便填写)

最后,将tokens 复制即可（建议将tokens保存到本地）。

#### 	2.在github创建项目，并在clone下来

```
git clone http...
```

#### 	3.在pycharm打开这个项目，如果有更新的内容

在Terminal输入

```
git add .
```

然后，在工具栏找到git--commit可以添加自己提交的注释。

最后，push即可。

在Terminal输入：

```
git push
```

