# commonly used git commands

1. clone (下载一个远程的版本库/如Github上的repository，只要一开始下载一次)
```bash
git clone git@github.com:yiting-wang/Kesci.git
```

2. add (把新加入本地版本库的文件添加到track list里面)
```bash
git add -A
```

3. commit (把本地的修改提交到本地版本库)
```bash
git commit -a -m "your comments"
```

4. push (把本地版本库上传到远端版本库，如github)
```bash
git push origin master
```

5. pull (把远端版本库的最新内容下载到本地版本库)
```bash
git pull
```

6. status (查看当前工作目录的修改，做了哪些修改还没有commit)
```bash
git status
```

7. log (检查之前的log，做了几次更改的记录)
```bash
git log
```