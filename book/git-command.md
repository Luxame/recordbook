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

指令：

```
git init
```

在任何專案中，要做 git 操作的話需要有 `.git` 這個資料夾才能下 git 指令操作。
新專案中建立 `.git` 資料夾，在終端機下 `git init` ， Git 就會建立 `.git` 資料夾

- 把專案下載到自己電腦中

指令：

```
git clone ProjectURL
```

假如開發要藉由 Github 上的開放原始碼專案，我們需要把專案下載到自己電腦中，才能做程式碼更動

下載方式有兩種，一種是用指令操作讓 git 幫我們下載，另外一種則是到你要下載的專案網頁中做下載

以下說明兩種下載方式：

- 使用 Github 上的 Download 功能

  1. 至你要下載的專案網頁下，點開下圖紅色框框處
  ![git](/images/gitclone01.png)
  2. 會看到如下圖，會有個 `Download ZIP` 的按鈕，點選就可以下載專案的壓縮檔了
  ![git](/images/gitclone02.png)

- 使用 `git clone` 指令
