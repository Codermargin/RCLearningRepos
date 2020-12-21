# 一、安装

- 通过brew安装git

```shell
brew install git
```

# 二、创建ssh key、配置git

- 设置username和email

```shell
git config --global user.name "Codermargin"
git config --global user.email "1273930793@qq.com"
```

- 创建ssh key

```shell
ssh-keygen -t rsa -C "1273930793@qq.com"
```

- 打开pub-key

```shell
cat .ssh/id_rsa.pub
```

- 复制到GitHub中Settings

- 连接验证

```shell
ssh -T git@github.com
```

# 三、本地创建仓库并提交

- 初始化本地仓库

```shell
git init
```

- 将所有文件添加到节点

```shell
git add .
```

- 将文件提交到节点，并注明信息

```shell
git commit -m "MylearningOfTypescript"
```

- 添加远程推送路径

```shell
git remote add origin https://github.com/Codermargin/MyLearningNotes.git
```

- 添加分支节点

```shell
git branch -M main
```

- 进行远程推送

```shell
git push -u origin main
```



# 四、克隆文件

```shell
git clone git@github.com:Codermargin/MyLearningNotes.git
```



# 五、本地修改并提交

- 添加文件到节点

```shell
git add .
```

- 把文件提交到本地仓库，并说明

```shell
git commit -m "MylearningOfTypescript"
```

- 进行远程推送

```shell
git push -u origin main
```

