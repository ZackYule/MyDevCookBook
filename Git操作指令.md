# Git操作指令

### 1. 远程删除

1. 预览将要删除的文件

```sh
git rm -r -n --cached 文件/文件夹名称 

加上 -n 这个参数，执行命令时，是不会删除任何文件，而是展示此命令要删除的文件列表预览。
```

2. 确定无误后删除文件

```sh
git rm -r --cached 文件/文件夹名称
```

3. 提交到本地并推送到远程服务器

```sh
git commit -m "提交说明"
git push origin master
```

4. 修改本地 .gitignore 文件 并提交

```bash
  git commit -m "提交说明"
  git push origin master
```