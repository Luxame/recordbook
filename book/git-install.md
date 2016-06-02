# Git 安裝

前面說到 Git 是一個跨平台的版本控制系統，所以是能在 Windows 、 Mac OS X 、 Linux / UNIX 不同的作業系統上執行。

下面將說明各系統的安裝說明。

### Mac OS X

蘋果電腦只要從 App Store 裡面，下載安裝 Xcode 就會有 Git 了，不需要額外步驟。

也可以用 Homebrew 下載安裝的 Git 不使用 Apple Xcode 所內建的

Homebrew 安裝：

```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

更多關於 Homebrew 相關資訊可以參考以下連結：

[Homebrew](http://brew.sh/)

使用 Homebrew 安裝 Git 參考資料：

[Step-by-Step on How to Update Git on Mac](http://michaelcrump.net/step-by-step-how-to-update-git/)


### Linux ( 以 Ubuntu 為例 )

開啟終端機( Terminal )，在終端機上打上以下指令

```
sudo apt-get install git
```

等候安裝完成即可！

### Windows

至 Git 官方網站下載安裝程式：

[Git for Windows](https://git-scm.com/downloads)

下載完成後，執行程式依照程式詢問問題做相關調整設定

參考資料：

[30 天精通 Git 版本控管 (02)：在 Windows 平台必裝的三套 Git 工具](http://ithelp.ithome.com.tw/articles/10132333)

-----------------------------------------------

在各個系統中完成 Git 的安裝，想確認是否有成功可以在 終端機/命令提示字元 中下 `git` 指令

出現如下圖所示即代表成功！

![git](/images/git01.png)
