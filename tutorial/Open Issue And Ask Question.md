# 請求排除疑難雜症

相信各位在開發過程中一定會遇到疑難雜症，像是以目前來說，我已經幫了不少的同學解決了許多問題。

那麼顯然的，當你遇到問題的時候，狂 call 助教的通訊管道，或者在助教下課的時候堵人都不是一個好辦法。畢竟助教也是人，而且也挺忙。

這時候我們可以善用協作者的角色，來適時的提出 issue 並討論。



在這份文件中，我將教你在團隊中如何向專案管理者（或者比較資深的人）提出 issue，並描述什麼樣的 issue 會比較好。

當然，這份文件並不代表 100% 的正確，每個人有每個人的作法，它只是一份純分享心得的文件。



## Goal

這份文件期望你可以學會這些東西。

- [x] 如何使用 issue 功能。
- [x] 確保你知道了《提問的智慧》，且認識到了錯誤的提問方式。
- [x] 讓我們建立一個系統化的提問管道。

如果你確定你已經會了第一點與第二點，請直接閱讀 Issue 章節。



## How

提出 issue 並不難，就像平常向人詢問問題一樣。

> 「嗨，助教，我遇到了 ... 的問題，我已經嘗試了 ....，但問題還是沒有解決，想請您有空時能夠協助我們解決這個問題。」



但身為一個資工人，我會期許你希望準備向他人求助時，是能夠準備好解決問題的所有材料。

首先提問可能就是一個很大的智慧，這邊分享一份文件叫做[提問的智慧](https://github.com/ryanhanwu/How-To-Ask-Questions-The-Smart-Way)，並且希望這東西可以列為資工系國文必修教材。



### 提問

在附錄中我會提出錯誤的問問題方式，主要的是，我會希望你能夠像是以下的範例，描述清楚自己的問題。

以下的問題是我習慣向他人提問的方式。

> 嗨，我是資工三的黃漢軒，我正在使用 `v4.87.63` 版本的遊戲框架開發遊戲，但我遇到了 `ToggleAnimation()` 方面的問題，當我設定一個 `CMovingBitmap` 時，即使我已經設定該動畫是單次動畫，但使用 `ToggleAnimation()` 時動畫依然不會開始，我已經嘗試閱讀了 `ToggleAnimation()` 與 `ShowBitmap()` 的 Source Code，並且也已經確保了 `ToggleAnimation()` 有被執行，但依然找不到解決問題的方法，想請您有空時能夠協助我們解決這個問題。

主要分成了「你的環境是什麼」、「你正在做什麼」、「你遇到了什麼問題」、「你做了什麼嘗試」，這樣有助於讓我們更了解你已經做了什麼嘗試，能夠減少重複的提問必要的問題，以及更了解你遇到的問題，我們也可以針對你遇到的問題進行排除。



### 分出 bug 分支

第二個部分是，當前版本有問題時，我們可以分出一個分支來負責解決問題。

分出分支的好處在於我們可以知道問題是在哪個節點發生，以及當我們解決問題時，不會與你目前正在工作的分支影響。

以下的圖可以幫助你更好了解分出 bug 分支的意義，盡請參考。

<img src="https://i.imgur.com/KL8eZsR.png" alt="image-20230308013026757"  />



## Issue

在這一門課，我希望大家可以用這樣的方式，當你遇到了你與你的組員都無法解決的問題時，請**開啟 issue 並將 assignees 設成我**。



當你要開 Issue 時：

1. 若提供程式碼是解決問題的必要材料，請分出一個 bug 分支，能夠用於 debug。
2. 詳細描述遇到的問題，撰寫 Issue 標題與 Issue 的內容。
3. 詳細描述你希望在哪個分支上進行 debug。

當我收到的時候，就會上去嘗試解決。



以下是一個範例。

![image-20230308014325425](https://i.imgur.com/kdMctPR.png)



最後，不用以下對上的方式請求解決問題，你應該把我當作協助你們專案的好朋友，也祝你們開發順利。



## 附錄

### 詢問問題的錯誤範例

#### 錯誤範例：TCP 的詢問問題方式

> 嗨，在嗎，有空嗎，約嗎。

這樣的詢問問題方式顯然是不好的，我得要回答「在喔」接下來再等你有空的時候回訊息，真正看到問題要很久之後了。

你不需要先三方握手，我們比較喜歡你直接把問題砸過來，幫你解決問題的人不想解決或者在忙就不會回覆，想解決就會解決完後回覆你。



#### 錯誤範例：堪比通靈的方式問問題

> 我的圖片打不開

> 我的程式打不開

> 為什麼寫程式的工具跳出了很多紅紅的東西

沒人看得懂你想問什麼，求你了，不要這樣做。



#### 錯誤範例：沒有經過整理或思考的問題

> 我發現到了一個問題，圖片沒有夾在肯德基最近新出的乖乖裡，而且拌義大利麵的糖醋醬沒有混凝土的味道。

> 我發現到了一個問題，我發現圖片的載入會讓我家的松鼠開始肚子餓，並且我家停在停機坪的挖土機會開始施放星爆氣流斬。

> 請問練習 3/3 號截止是指 3 月 3 號的凌晨 12 點，還是指 3 月 2 號的 23 點 59 分呢？

通常不會這麼誇張，但請確定你問的題目不會讓人看不懂，甚至答案是淺而易見的。



#### 錯誤範例：缺東缺西的問題

> 我發現圖片沒辦法被載入

通常要了解這個問題的全貌，會需要再額外問好幾個問題，例如遊戲框架的版本多少，圖片有沒有確實放到資料夾，跳出了什麼錯誤訊息等。

為了彼此的時間著想，我認為我們要求一個圓。