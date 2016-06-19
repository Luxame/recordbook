什麼是 NVM ?
============

NVM 全名是 Node Version Manager ，是用來管理 Node.js 版本的 Tool ，因為 Node 的版本更新速度很快，可能需要做版本的切換，而使用 NVM 可以快速做到版本的切換。

來看看 NVM 的相關建置與操作指令說明吧！


--------

### 安裝

- Linux

##### Install NVM
```
wget -qO- https://raw.githubusercontent.com/creationix/nvm/v0.31.1/install.sh | bash
```

- Mac OSX

##### Install Homebrew
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

參考網站：[Homebrew](http://brew.sh/)

##### Install Wget
```
brew install wget
```

##### Install NVM
```
wget -qO- https://raw.githubusercontent.com/creationix/nvm/v0.31.1/install.sh | bash
```

- Windows

安裝 [NVM For Windows](https://github.com/coreybutler/nvm-windows)

[下載連結](https://github.com/coreybutler/nvm-windows/releases)

* 下載ZIP檔後解壓縮
* 進入解壓縮出來的資料夾，執行 nvm-setup
* 前面接受授權後都 Next 即可， 在 [ Select Destinatiom Location ] 的項目中可先行記下程式安裝的存放位置，再來持續 Next 至完成安裝即可
* 開啟 `我的電腦` ，在位置列上打上前面所述要記下的安裝存放位置
* 進到 nvm 的資料夾中，在 `install` 指令檔上，右鍵使用 `以系統管理員執行`
* 進到命令提示字元中，按 `ENTER` 鍵出現如下圖後即可關閉相關視窗
![nvm-windows01]()
* 開啟命令提示字元，或開始在搜尋欄上打上 `cmd`
* 在命令提示字元中，打上 `nvm` 出現如下圖表示 nvm 安裝成功
![nvm-windows02]()
