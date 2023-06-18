# Side-Project : 考古題共享平台

[![hackmd-github-sync-badge](https://hackmd.io/AULir74LTleQyJQxIXF_2g/badge)](https://hackmd.io/AULir74LTleQyJQxIXF_2g)


## 小組討論
### 第一次討論(2023/05/16)
> 確定小組成員：詹子禾、郭奕漢、張珈豪、李嘉馨、徐薏蓁

提案：
* 李嘉馨：考古題共享平台
    * 匯集各個學校不同書籍和教授的考古題，方便學生們準備考試和提升學習效果。
* 詹子禾：類似"OP.GG"
    * 網站上可以查詢多款遊戲內的攻略，還有統計職業選手的出裝、勝率。
* 郭奕漢：學生管理系統
    * 儲存學生資料、課程選擇、成績紀錄等功能。
* 張珈豪：社交媒體帳戶管理
    *  社交媒體管理工具幫助個人、企業或營銷團隊有效地管理和組織他們在多個社交媒體平台上的帳戶、內容和互動
* 徐薏蓁：Trello
    * 線上任務管理和協作工具，提供可視化看板的方式來組織和追蹤工作流程。

### 第二次討論(2023/05/28)
> **投票結果**

|       題目       | 票數 | 結果 |
|:----------------:| ---- | ---- |
|  **考古題共享平台**  | **3票**  | **✔**    |
| 社交媒體帳戶管理 | 1票  |      |
|   類似"OP.GG"    | 0票  |      |
|   學生管理系統   | 0票  |      |
|      Trello      | 0票  |      |

**投票決定為考古題共享平台**

### 第三次討論(2023/06/02)

> **系統規劃**
> 
* 目標

   藉由匯集淡江大學的各科考古題幫助學生更有效率的準備考試。

* 功能
  * 用戶註冊和登錄
  * 考古題上傳和閱覽
  * 關鍵字搜索和篩選
  * 題型分類
  * 積分制度
  * 共編筆記
  * 私訊
  
* 架構
  * MySQL：用做為後端存儲
  * Flutter：在iOS 和 Android 上開發一致的應用程式
  * Node.js：伺服器端運行環境
  
* 參考範例

   連結：
   https://github.com/NCTUCSUnion/csox

### 第四次討論(2023/06/05)
> **確認分工**

* UI設計
    * **詹子禾**：主頁、搜尋功能
    * **郭奕漢**、**徐薏蓁**：共編筆記
    * **張珈豪**：考古題
    * **李嘉馨**：登入畫面、我的積分
    
* 架構圖
    * **詹子禾**、**李嘉馨**：繪製前端、後端架構圖

* HackMD
    * **詹子禾**：文案撰寫

## 系統文案

* 目標

  藉由匯集淡江大學的各科考古題幫助學生更有效率的準備考試，同時，透過積分制跟共享筆記等功能，鼓勵使用者參與和合作學習。

* 功能
  * 用戶註冊和登錄
  
     目前系統僅專門提供給淡江大學的學生使用，可透過單一登入進入系統。

  * 考古題上傳和閱覽
  
     提供淡江大學各個領域的學科考古題閱讀及下載，若是訪客登入將不提供下載、截圖、複製功能，也不會有答案，和與作者私訊的機會
  
  * 關鍵字搜索和篩選
  
     使用者可以透過關鍵字或是題目上的特殊標籤（例如：管理學、成本分析）達到快速搜尋的目的，也可以透過篩選得到更精確的搜索。
     
  * 題型分類
  
     題目分類，簡單慢慢步入困難循序漸進，將基礎功打紮實
  
  * 積分制度
  
     查閱考古題皆需花費積分 而積分會根據簽到 上傳考古題 或分享平台來取得 主要目的是為了讓使用者願意上傳考古題 並且可以擴大平台的知名度。
  
  * 共編筆記
  
    使用者可以根據自己的需求將考古題統整成一個分類(筆記)也可以邀請其他使用者一起編輯新增該筆記內的題庫。
  
  * 私訊
    分享筆記或是題目的作者，有時可能會發生筆誤或是解題過程有瑕疵，閱讀者可以藉由私訊功能讓作者知道，或是遇到看不太懂得也可以跟作者討論，教學相長

  
* 系統架構圖
![](https://hackmd.io/_uploads/rJBS4IiP3.png)
連結：
https://www.figma.com/file/jL08qUVklpK6lnWh17Bnz2/TKU%E8%80%83%E5%8F%A4%E9%A1%8C%E5%85%B1%E4%BA%AB%E5%B9%B3%E5%8F%B0?type=whiteboard&node-id=0%3A1&t=eRWd0GGXgpIcFfeG-1
 
**MySQL**：用於組織、存儲和管理結構化資料的系統，並提供查詢、一致性、安全性和恢復功能
**Flutter**：Google 開發的跨平台框架，在iOS 和 Android 上開發一致的應用程式
**Node.js**：伺服器端運行環境，具有事件驅動和高效處理大量並發請求的能力，適用於構建可擴展的伺服器端應用程式
 
* 使用者介面

    連結：
    https://www.figma.com/file/Myk6nmfjsEpBtMEvlx12Eo/%E8%80%83%E5%8F%A4%E9%A1%8C%E5%85%B1%E4%BA%AB%E5%B9%B3%E5%8F%B0-UI?type=design&node-id=0%3A1&t=zCqnJjhwYgM47Ui9-1
    
    * 登入頁面
    
    ![](https://hackmd.io/_uploads/BkXf1ehP2.png =30%x) ![](https://hackmd.io/_uploads/HkTJ0JnD2.png =30%x)
    
    * 主頁
    
    ![](https://hackmd.io/_uploads/r1ThILsP3.png =30%x) ![](https://hackmd.io/_uploads/HJB0D8sPh.png =30%x)
    
    * 搜尋
    
    ![](https://hackmd.io/_uploads/BkBrP8jP2.png =30%x)
    
    * 考古題
    
    ![](https://hackmd.io/_uploads/H1xrPPf3P3.png =30%x) ![](https://hackmd.io/_uploads/SyJCPMnwn.png =30%x) ![](https://hackmd.io/_uploads/HJuKuz3Dn.png =30%x) ![](https://hackmd.io/_uploads/SkYeCJ2D2.png =30%x) ![](https://hackmd.io/_uploads/S1WbYM3D2.png =30%x)
    
    * 共邊筆記
    
    ![](https://hackmd.io/_uploads/HyRIKLiD2.png =30%x) ![](https://hackmd.io/_uploads/HJ4Y9Isw3.png =30%x) ![](https://hackmd.io/_uploads/r1FBoUjPn.png =30%x) ![](https://hackmd.io/_uploads/BkZQjIoPh.png =30%x)
    
    * 我的積分
    
    ![](https://hackmd.io/_uploads/ryYFJe2P3.png =30%x) ![](https://hackmd.io/_uploads/SkEzRkhPh.png =30%x)


    








