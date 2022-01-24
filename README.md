# git-message-template

> 此專案中`git-message.txt`為git提交時的訊息範本，遵循此範本增加commit可讀性

## 設定

1. 進入想設定的git提交範本的專案目錄
```
cd projectPath/
```

2. 編輯git config檔案
```shell
vim .git/config
```

3. 加入範本路徑
```text
[commit]
  template = {path}/.gitmessage.txt
```
