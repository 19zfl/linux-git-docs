# [Linux]Ubuntu下git安装、配置、代码管理
### 一、git安装
#### 1.terminal命令行安装
```terminal
sudo apt update // 可省略
sudo apt install git
```
#### 2.官网安装包安装
git官网：https://git-scm.com/

git中文官网：https://git.p2hp.com/

检验是否安装成功：

```terminal
git --version
```

### 二、git配置
#### 1.配置git名称和邮箱

```terminal
git config --global user.name 19zfl
git config --global user.email 19zfl@git.com
```

检验是否配置成功

```terminal
git config --list
```

