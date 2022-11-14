###### tags: 框架

**選語言&框架&說明原因**
===
框架:
---
- 語言@or框架名稱#
    -
    - 簡單敘述
    - 優點or缺點
- @Java
    -
    - Java是強型別 靜態語言
    - 非常貼近所謂『物件導向設計』的理念，也因為獨特的編譯方式，擁有極好的跨平台執行效率。Java 的語法嚴謹，結構嚴密，台灣會使用 Java 寫網頁的，大部分都是銀行金融機構
    - 用途廣泛，職涯道路寬、開發嚴謹軟體結構完整， 執行效率優秀
    - 開發過程極吃電腦記憶體量(緩慢)、程式語法較為龐雜
- #Spring framework
    -
    - 它提供一些不錯的功能如[依賴注入](https://ithelp.ithome.com.tw/articles/10211847)(Dependency Injection)與箱外模組化。開發Web App
    - 控制反轉IoC:控制反轉是一個設計思想 ，把對於某個物件的控制權移轉給第三方容器 
    <!--
    簡單解釋
    A物件程式內部需要使用B物件 A,B物件中有依賴的成份
    控制反轉是把原本A對B控制權移交給第三方容器
    降低A對B物件的耦合性，讓雙方都倚賴第三方容器。-->
    - 輕量級、鬆散耦合的
    - Spring Web是一個設計良好的Web MVC框架
    - 模組化組織
    - 易於測試
        - 依賴:指的是物件導向中的繼承、實現、擁有等關係。
        - 注入:的意思是從外部傳入。 
        - 箱外模組化如:Spring Serurity、Spring MVC等，這些模組可以大大降低應用程式的開發時間。
        - Web App 優點:跨平台、成本較低、維護更新容易。
        - Web App 缺點:效能較差不適合複雜的購物金流或動畫、遊戲等。對硬體裝置的支援度較低例如：相機、 GPS 地理定位...等功能。
        - 鬆散耦合:耦合指的是系統中元件互相依賴的程度，越少的依賴，重複使用性與彈性就越高。
        - MVC框架:
            - View:負責處理訪客直接見到／互動的東西，即用戶介面(UI)通常由前端的人員去完成
            - Controller:負責決定整個應用程式該怎樣運行
            - Model:負責讀寫和資料轉變的工作，通常由後端開發人員去完成
- #Spring boot
    - 
    - Spring Boot擴展了Spring framework，透過建立Spring application省去了冗長的設定檔(configurations)，在相同功能下Spring boot需要的程式碼相對少。簡單來說Spring Boot是更加簡單地且方便的拓展了Spring本身在開發、測試、部署
    - 易於理解開發應用
    - 使配置變得簡單並彈性
    - 提供有力的管理Rest端點
    - 自動化配置
    - 依賴套件管理簡單
    - 內建[Servlet](https://ithelp.ithome.com.tw/articles/10184867)容器
    - 獨立打包直接運行

- #Node.js
    -
    - 實現可以在後端執行 Javascript 的機制，Node.js 也非常易寫，執行效能非常優良，能跨平台開發與執行的語言
    - 高併發
    - Node是一個非阻塞I/O(non-blocking I/O)和[事件驅動](https://hackmd.io/@sysprog/event-driven-server)(event-driven)的JavaScript執行環境(runtime)，所以它非常適合用來構建I/O密集型應用，例如Web服務等
    - 非阻塞I／O調用後會立即返回結果或一個錯誤，而阻塞I／O調用後則不會立即返回
    - Node.js 很適合小型和輕量級專案
    - JavaScript 是弱型別 動態語言
    - Node.js 的生態完善，但開源組件庫質量參差不齊，更新快，向下不兼容
    - 維護困難，程式碼有Bug 影響範圍較巨大
    - 只支持單核CPU，不能充分利用CPU
    - Debug不方便，錯誤沒有stack trace
- #Express
    -
    - express 是基於 node.js web 應用程式的一種開發框架，可以快速搭建一個功能完整的網站。大量的 HTTP 公用程式方法與中介軟體(Middleware)。
    - 它是快速，集思廣益，極簡的Node.js Web架構。易於與database做連線，像是MongoDB, Redis, MySQL
    - 靈活，具有可擴充性，可以依照個別需要加入各種套件
    - 為Web App框架
    - 為單頁式SPA應用程式
    - 可以為多網頁與SPA混合式Web應用程式
        - 中介軟體(Middleware):是指從發出請求後，到接收回應前，用來處理特定用途的程式。
        <!-- 簡單來說是一個可以接收request 和 response 物件的函數，每個中介軟體可以針對所收到的物件進行修改處理或是解析處理，處理完畢後再決定是否繼續傳給下個中介軟體或是中斷傳遞行為。 -->

**所選用的框架及語言**
===
### 框架:Spring boot

### 語言:Java
### 理由:首先Java是強型別靜態語言，且Spring boot 相較於Spring 對於開發者來說是非常便捷的。其中有很多原本Spring 要自己配置的步驟，Spring boot會幫忙自動化配置。SpringBoot 官方提供了大量日常企業應用研發各種場景的 spring-boot-starter 依賴模組。這些依賴模組都遵循著約定成俗的預設配置，並允許我們根據自身情況調整這些配置。再用上Maven(是一個專案管理與自動化建構工具，主要用於 Java 專案)去解決了軟體開發的兩大難題(如何建構專案&如何管理各種軟體套件的依賴關係)

####

