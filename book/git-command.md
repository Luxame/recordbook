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

$ git config --list

查看所設定的環境變數

```

`--golbal` : 表示全域設定



在個別專案中要以其他使用者資訊做 git 操作，把 `--golbal` 拿掉，在專案目錄下重下相關指令即可

### Start Git

Git 環境設定好就可以開使進入使用 Git 對專案的操作了！

- 建立一個新的 Repository

在任何專案中，要做 git 操作的話需要有 `.git` 這個資料夾才能下 git 指令操作。
新專案中建立 `.git` 資料夾，在終端機下 `git init` ， Git 就會建立 `.git` 資料夾
