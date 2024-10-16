# upload

### 在命令列上建立一個新的儲存庫
```
echo "# upload" >> README.md
：這會在名為 README.md 的文件中添加一行包含 "# upload" 的文本。如果文件不存在，它會創建一個。

git init
：這個命令會初始化一個新的 Git 儲存庫。

git add README.md
：這個命令會將 README.md 文件添加到暫存區，以便在下一次提交時包含它。

git commit -m "first commit"
：這個命令會將暫存區中的文件提交到本地儲存庫，並附加提交消息 "first commit"。

git branch -M main
：這個命令會創建或重命名當前分支為 "main"。

git remote add origin https://github.com/abin0517918/upload.git
：這個命令會將遠程儲存庫設置為指定的 URL。

git push -u origin main
：這個命令會將 "main" 分支推送到設置的遠程儲存庫上，並將本地的 "main" 分支設置為跟蹤遠程的 "main" 分支。
```

### 從命令列推送現有儲存庫
```
git remote add origin https://github.com/abin0517918/upload.git
git branch -M main
git push -u origin main
```
