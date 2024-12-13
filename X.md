# 安装

系统安装“花园明朝字体”，用来展示生僻字

```
font_face: "PingFangSC-Regular,HanaMinA,HanaMinB"
```


# 同步开源作者仓库

git fetch upstream
git checkout main
git merge upstream/main  # or `git rebase upstream/main`
git push origin main


# 同步迁移

[多设备同步 | oh-my-rime输入法](https://www.mintimate.cc/zh/guide/deviceSync.html )

同步迁移，也就是用rime的同步机制进行迁移。适用于，已经有rime_mint.userdb.txt文件，想把luna.userdb.txt融合进rime_mint.userdb.txt文件内。

很简单，在sync文件夹下，新建一个temp文件夹，把并把luna.userdb.txt更名为rime_mint.userdb.txt(文件里面的#@/db_name改为rime_mint)。这样合并时 Rime 会认为这是另一个设备上的词库将其合并过来。