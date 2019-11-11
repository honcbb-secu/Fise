# Fise
[![Release](https://img.shields.io/badge/%E7%89%88%E6%9C%AC-V1.0-green)](https://github.com/honcbb-secu/Fise/releases)

## 介紹
Firefox Browser Security Gadgets - (Firefox 瀏覽器安全小工具) - 此工具不是出自於**Firefox 官方**所開發「而是由一名安全研究人員**Honc** 開發而成」，**Fise** 工具程式出發初衷為替家長監督孩子(未成年狀態或保護孩子上網安全) 避免洩漏太多相關敏感資訊及防堵相關社群網站及第三方企業存取用戶瀏覽器本地資料，Firefox 瀏覽器內建了可以自主設定(封鎖任何網站存取資料)，但是由於有些孩子未有能力判斷下及容易被解開相關設定，因此Fise 這項程式可以隱藏所有設置並完整防堵一切為了就是讓孩子不輕易的解除設定。

但是最重要的是，若是家長可以自身化為孩子上網導師親自口述及行動讓孩子了解**資訊安全、個資外洩** 的重要性， 遠過於工具安全程式。 

![image](https://i.imgur.com/aY8bKWz.jpg)



## 更新

Fise 程式會跟隨**Firefox 瀏覽器**更新版本而更新程式，未來也會替程式加上更多安全功能，因此更新都是不定時的！用戶如果使用程式遇新版本將會派送通知


## 注意

由於程式都是根據**Firefox 瀏覽器**最新版本狀態下而修改，因此請隨時保持電腦中**Firefox 瀏覽器**為最新版本，否則**啟用安全設置**遇任何瀏覽器出現錯誤狀況或者崩潰情形一律概不負責。


Firefox 版本(Version) 判斷、右上角**開啟選單** > **說明** > **關於Firefox**：

![image](https://i.imgur.com/nhRpfaS.jpg)

## 支援

目前支援Firefox 版本 **70.0.1** (最新)

目前只支援Firefox 瀏覽器 - **[繁體中文(zh-TW)](https://www.mozilla.org/zh-TW/firefox/download/thanks/)** (未來將會擴增其他語言)


## 安全

作者同樣為了保護程式安全因而採用了**軟體加密保護技術** ，所以許多防毒軟體廠商會對**Fise** 這項工具作出誤判情形，但可保證的是**Fise** 沒有任何植入**病毒木馬**及**蒐集用戶瀏覽器所有資訊** 任何情況，因此使用者『大可放心』！若還是對**Fise 程式** 抱著存在可疑情形請勿使用。

## 風險

**Fise 程式** 只修改並移除了設置功能文件然而沒有影響Firefox 瀏覽器核心系統規則，都是可正常情況下使用，若還是**啟用安全設置** 及 **確認 Firefox 繁體中文瀏覽器為最新版本狀態下** 出現任何錯誤運行問題，請聯繫我：honcbb@gmail.com

## 如何使用？

必須先關閉**所有Firefox 瀏覽器** 在開啟程式，剛最初開啟工具執行**啟用安全設置** 會要求先執行**掃描Firefox** 後再重新執行**啟用安全設置**，啟用時必須輸入一組**安全密碼** 方便家長或用戶管理配置下不被任何外來影響到**安全配置** (因此這組密碼非常重要必須記得)，若是想解除安全設置話再執行**移除安全設置** (輸入當初所設密碼)，就可成功恢復原始狀態下。

## 功能
   
   * 移除網站跳出**要允許XXXX 存取您所在的位置嗎？** 詢問通知。
   
   * 隱藏選項>隱私權與安全性>權限【**位置**】選項
   
   
   __功能將會陸續的增加__

## 常見問題

* 為什麼開啟程式出現**請先確定是否有連線！** ? 

    → 『因為程式加入了相關版本驗證通知必須與伺服器作連線確認，因此前提開啟程式下必須先開啟網路執行才行』
    
* 為什麼開啟程式出現**Firefox 瀏覽器官方已經有新版本！請檢查及更新並且至作者專案重新下載新版本程式。** ? 

    → 『此訊息是通知您Firefox 已經有新版本釋出且作者也同步更新程式支援最新瀏覽器版本，因此您需更新瀏覽器版本及至這個專案下載新的版本Fise 工具程式』
    
* 為什麼開啟程式出現**程式已更新！請至作者專案重新下載新版本程式。** ? 

    → 『作者可能新增功能或修補程式相關錯誤Bug 而自行發出的通知，如果只出現這項通知訊息只需至專案重新下載新版本Fise程式即可』
    
 * 為什麼開啟程式出現**元件'MSInet.ocx'或它的依存檔案並未正確地註冊:某檔案遺漏或不正確** ? 

    → 『這個錯誤是因為Fise 程式本身引用了網路驗證MSInet.ocx 組件，必須要有這個檔案才能正確與伺服器驗證並且回傳相關通知訊息，電腦處於兩種情況：
    
    一. 電腦路徑C:\Windows\SysWOW64\* 沒有這個MSInet.ocx檔案，所以須至網路尋找並放置正確路徑即可>[可點我下載](https://www.ocxme.com/files/msinet_ocx)
    
    二. 電腦雖有這個檔案，但沒有給它正確註冊，可參考[這篇文章](https://dotblogs.com.tw/usice0314/2010/04/07/14442) 修改一下註冊即可』
    
    **未來將會為這個錯誤寫成工具直接一鍵解決，敬啟期待！**
    
* 為什麼執行「掃描Firefox」出現 **檢測配置錯誤．．．．請聯繫程式開發者！** ? 

    → 『由於您電腦系統相關規則問題而不支援，請立即聯繫作者處理：honcbb@gmail.com』
    
* Fise 會洩漏使用者資訊？ 

    → 『如上提前面所描述，Fise 只單純提供修改及移除配置相關功能、並無相關擅自蒐集使用者資料及瀏覽器儲存資訊，如果不放心也請別使用』
    
* Fise 這款程式會收費嗎？ 

    → 『不會，一切為終生免費！也不會突然的，有任何問題及程式使用上困擾也歡迎寫信給我知道協助您解決：honcbb@gmail.com』
    
* 我有**啟用安全設置了** ，為什麼小孩或者其他人可以破解及擅自恢復這些設置？

    → 『若有這情形，請同樣立即聯繫開發作者：honcbb@gmail.com，感激不盡！』
    
* 為什麼我成功執行**啟用安全設置** ，有些功能還是**無法成功移除**？ 

    → 『請至``控制台>程式和功能``確認下載安裝的Firefox 瀏覽器是否為繁體中文**zh-TW**』
    
    ![image](https://i.imgur.com/mYAxNLE.jpg)
    
* **啟用安全設置** 與 **移除安全設置** 一定要先關閉Firefox 才能執行嗎？

    → 『是的，若執行時有偵測到Firefox 開啟中會出現警告並且要求關閉才能執行下一步』
    
* Firefox 瀏覽器會因為**啟用安全配置** 變的更容易被駭客入侵？ 

    → 『不會！Fise 這款工具只是在於移除及隱藏相關配置功能，並無修改其中任何系統文件重要程式碼，因此無需擔心！』
    
`以上問題會再陸續增加，若您發現上述 FAQ 沒有解決您的問題請聯絡我：honcbb@gmail.com`
    
    
    

====================

如果您想支持我或鼓勵我的話，經濟允許下不妨請我喝個:coffee:吧:blush:
    
    
    
    
\*文章最後時間修改於2019/11/12\*
    
    
    
   
    

