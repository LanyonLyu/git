# GIT

个人代码仓库。

## 克隆

```bash
git clone https://github.com/LanyonLyu/git.git
cd git
```

## 状态

初始骨架仓库，默认分支 `main`。项目内容按需补充。

## 说明

本仓库配置了 `http.sslBackend=openssl`。若你的环境使用系统 schannel 且工作正常，
可以删除该配置回到默认行为：

```bash
git config --unset http.sslBackend
```
