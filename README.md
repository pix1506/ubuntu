# 用bash開發一鍵安裝的腳本

## 撰寫動機
許多公司開發大型系統時，通常需要安裝許多不同的檔案來建構，造成整個過程非常繁瑣。當開發完成要交貨給客戶時，也都還要再寫一篇複雜的安裝手冊給客戶看，而大部分客戶可能也都看得霧煞煞。

因此撰寫腳本是解決這個問題的方式，撰寫腳本（Scripting）是利用腳本語言（如Bash、Python、PowerShell等）來自動化一系列任務的過程。在實習期間，剛好有機會學如何撰寫腳本，協助公司簡化安裝過程，讓客戶能一鍵安裝。
目前的大學環境中同學也比較少接觸到這方面的知識，所以就撰寫了這篇簡單描述過程，給有需要的人參考。

本篇會手把手從window教你怎麼安裝Ubuntu Server版到腳本撰寫與實際上機測試
## 目錄
1. 安裝 Ubuntu 18.04.6 LTS (Bionic Beaver)
2. 腳本撰寫過程
3. 實際測試

## 內容
### 一. 安裝 Ubuntu 18.04.6 LTS (Bionic Beaver)
Ubuntu 18.04.6 LTS (Bionic Beaver) 是一個長期支持（LTS）版本，擁有一些特殊的優點，使得許多公司選擇繼續使用這個舊版的 Ubuntu。本篇安裝的是 Server 版，而非一般的 Desktop 版。

**安裝步驟：**
1. 前往 [Ubuntu 下載 ISO 檔](https://releases.ubuntu.com/18.04/)
      ![安裝步驟](readme%20image/圖片2.png)
   
2. 使用 [Rufus](https://rufus.ie/zh_TW/) 製作 Ubuntu 開機碟，可以參考[PYDOING大大的教學影片](https://www.youtube.com/watch?v=i7Uee78td-s)，下圖是製作完成後開機碟的樣子。
      ![安裝後隨身碟的樣子](readme%20image/圖片3.png)
   
      *Ubuntu開機碟（也稱為啟動磁碟或Live USB）是一個可啟動的USB隨身碟或光碟，內含Ubuntu操作系統的安裝程式和Live環境。這個開機碟可以用來執行以下功能：
      a.安裝Ubuntu：你可以使用開機碟來啟動電腦，然後進行Ubuntu的安裝。這是安裝Ubuntu的主要方式，無需預先在電腦上有任何作業系統。
      b.試用Ubuntu：在不改變硬碟上現有作業系統的情況下，你可以直接從USB或光碟上運行Ubuntu，這被稱為Live模式。在這個模式下，你可以測試Ubuntu，確保所有硬體正常運作，然後再決定是否安裝。
      c.修復系統：如果你現有的Ubuntu系統出現問題，開機碟還可以用來進行系統修復或資料救援。

3. 安裝完後便插上隨身碟重開機，開機時電腦品牌的Logo跳出來時就狂按DEL鍵，進入bios。
   (*每台電腦進入bios的按鍵不同，微星是DEL)
      ![補一張啥時進bios]

4. 進入bios之後選擇用開機碟來開機，

### 二. 腳本撰寫過程
（此處可以繼續描述腳本撰寫的內容）

### 三. 實際測試
（描述測試的過程和結果）

