# Git 入門練習專案

<img src="https://octodex.github.com/images/Professortocat_v2.png" align="right" height="200px" />

這是一個以 Git 入門練習為目的的前端小遊戲專案。專案內包含一個以開發者主題為靈感的方塊遊戲，玩家需要透過操作方塊，匹配不同的錯誤樣式並清除畫面中的區塊。
這個專案的目的是讓使用者在實際操作中練習 Git 的基本指令與流程，例如建立分支、提交變更、合併分支等。

## 專案簡介

這個專案是一個結合 HTML、CSS 與 JavaScript 的簡單網頁遊戲，靈感來自 Tetris 風格的操作方式。遊戲中會隨機出現不同的「錯誤模式」，玩家需要在棋盤上拼出對應的圖樣，並在成功匹配後獲得分數。

## 遊戲特色

- 以開發者常見錯誤為主題，例如 Null Pointer、Memory Leak、Syntax Error 等
- 支援左右移動、旋轉、快速下落與暫停
- 會顯示目前目標模式與分數
- 遊戲結束後可重新開始

## 專案結構

- src/index.html：遊戲頁面的 HTML 結構
- src/index.js：遊戲邏輯與互動控制
- src/patterns.js：錯誤模式資料
- src/style.css：畫面樣式
- src/testfile.txt：測試用檔案

## 如何執行

1. 下載或複製這個倉庫到本機。
2. 打開 src/index.html 即可在瀏覽器中開始遊戲。
3. 若使用 VS Code，也可以搭配 Live Server 擴充功能來預覽。

## 操作方式

- 左右方向鍵：移動方塊
- 上方向鍵：旋轉方塊
- 下方向鍵：加速下落
- 空白鍵：直接落下
- P：暫停/繼續遊戲

## 這個專案適合做什麼

這個專案非常適合拿來練習 Git 的基本操作，例如：

- 新增與修改檔案
- 建立提交（commit）
- 切換分支（branch）
- 合併變更（merge）
- 透過 Pull Request 進行協作

---

&copy; 2025 GitHub &bull; [行為準則](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) &bull; [MIT 授權條款](https://gh.io/mit)

