# Git 指令

### Git Config

Git 基本環境設定，設定作者的 username 、 email 、編輯器等慣用設定。

```
$ git config --golbal user.name "username"

設定使用者名稱

$ git config --global user.email "a@a.a"

設定使用者信箱

$ git config --global color.ui true

打開 git 顏色設定，預設沒有開啟顏色

$ git config --global core.editor vim

設定常用編輯器

```

`--golbal` : 表示全域設定



在個別專案中要以其他使用者資訊做 git 操作，把 `--golbal` 拿掉，在專案目錄下重下一次指令即可
