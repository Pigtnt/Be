###### tags: 框架

**選語言&框架&說明原因**
===
框架:
---
- 語言@or框架名稱#
    -
    - 簡單敘述
    - 優點
    - 缺點
- @PHP
    -
    - Web 後端語言王，市佔率高達 83.5%，非常的易學易懂易開發
    - 學習曲線低，跨平台開發、語法簡單、開發社群純熟
    - 語法嚴謹度低，複雜程序執行支援差
- #Laravel
    -
    - 為PHP web的框架，是一種 [MVC(Model-View-Controller)](https://tw.alphacamp.co/blog/mvc-model-view-controller) 的架構
        - Model 屬於資料的部份，可能是商業邏輯或是資料庫存取
        - View 屬於顯示的部份，像是 HTML、CSS 等
        - Controller 會偵對請求做出回應及處理，例如從 Model 中取得資料，並要求 View 來顯示
    - Laravel 基本上具備所有網站開發工程全方面的優化，架構漂亮，社群也非常活躍，持續進步
    - 編譯執行上比較緩慢
- @C#
    -
    - 市佔率在第二名，約佔 13% 左右，C#用在網站開發外，還有用在遊戲的引擎 unity，語言開發上由於繼承 Java 的特性，為強語言類別，具有較嚴謹的開發規範，會在本地開發時期就出現錯誤，提升新手開發程式的程式品質
    - 完整的開發生態系，先進的語法功能
    - 複雜的程式碼結構，本地編譯測試速度稍慢些
- @Ruby
    -
    -  Ruby 這個語言決大部分都是使用 Rails 作為網站開發框架。減少開發不必要的瑣碎時間、良好的介面設計，非常快速能夠上手，也提供許多指令和語法，快速完成許多複雜的邏輯功能，建議使用 Mac 或 Linux 作為 Ruby 開發的作業系統，開發有 99% 都是搭配 Rails 進行
    - 語法簡單輕便、開發與部署高效、大量易於使用的商用套件
    - 程式執行效率較差、相較PHP, C# 等語言學習曲線較高
- #Rails
    -
    - Ruby on Rails，簡寫為 RoR，是個嚴格 MVC 架構的框架，這個框架的核心概念為『不做重複的事』與『慣例優於設定』(人類的認知慣例大於自行設定)
    - 這個框架能幫新手快速建立應用程式，但也因為『異常』快速，例如:最經典的 [devise](https://ihower.tw/rails/auth.html) 這個套件，靠幾行指令就能生出完整的會員系統
    - 在真正做客製化調整時，會有比較大的學習曲線和挫折
- @Java
    -
    - 非常貼近所謂『物件導向設計』的理念，也因為獨特的編譯方式，擁有極好的跨平台執行效率。Java 的語法嚴謹，結構嚴密，台灣會使用 Java 寫網頁的，大部分都是銀行金融機構
    - 用途廣泛，職涯道路寬、開發嚴謹軟體結構完整， 執行效率優秀
    - 開發過程極吃電腦記憶體量(緩慢)、程式語法較為龐雜
- #Spring
    -
    - Spring 框架是 Java web 框架。Spring 框架對比一般 MVC 框架最大的特色為使用控制反轉（IOC）與 實現其方法的依賴注入（DI），降低程式間因改動出 Bug 的關聯程度，因此提升了維護性。
    - 集中管理物件，物件和物件之間的耦合度減低，方便維護物件。在不修改程式碼的情況下可以對業務程式碼進行增強，減少重複程式碼，提高開發效率，維護方便
    - 從應用層面來說是沒有缺點的，簡化開發， 如果想深入到底層去了解就非常困難
- @Python
    -
    - 熱門機器學習、AI 等領域的主流撰寫語言，它非常簡潔易讀的程式語言結構，且本身的編譯方法，讓 Python 程式可以快速自由的跨平台執行，不像 Ruby 受限於作業系統(Mac 或 Linux)、Java 受限於緩慢的執行測試速度。
    - 語法簡單、應用層面極廣、熱門度高
    - 執行速率較慢，縮排寫法新手易錯
- #Django
    -
    - 語言為python，Django 的軟體設計模式為 [MTV](https://ycy-tai.medium.com/django-beginner-02-%E9%97%9C%E6%96%BCmtv%E6%9E%B6%E6%A7%8B-c8d55ba5aca5)(Model-Template-View)，是一個與 MVC (Model-View-Controller) 略有不同，但核心概念相同的設計方法，如果要用在長期穩定的大型商業結構，推薦使用 Django。
        - Model : 描述你的資料類型
        - Template : 使用者看到網頁的形式
        - Views : 傳達資料(重點在於資料傳達的內容 
    - Django 框架的代碼結構統一且清晰易懂，開發人員可以像做填空題一樣添加更多功能，也可以設計自定義的類或接口
    - 許多可重用的模塊而限制了開發速度。需要確保以前的版本仍與新版本兼容，導致其運行稍慢。
- #Node.js
    -
    - 實現可以在後端執行 Javascript 的機制，Node.js 也非常易寫，執行效能非常優良，與前面提到的 Ruby, Python 不同。由於全端開發的特性，許多新創公司也開始選用Node.js建構他們的 MVP(Minimum Viable Product)產品，能跨平台開發與執行的語言，難以維護是他常被人詬病的地方
    - 開發快速，輕量、執行效率高、可跨端跨平台執行，Node是一個非阻塞I/O(non-blocking I/O)和事件驅動(event-driven)的JavaScript執行環境(runtime)，所以它非常適合用來構建I/O密集型應用，例如Web服務等。
    - 維護困難，程式碼有Bug 影響範圍較巨大
- #Express
    -
    - express 是基於 node.js web 應用程式的一種開發框架，可以快速搭建一個功能完整的網站。express.js 是建構在 Node.js [中介軟體模組](https://expressjs.com/zh-tw/guide/writing-middleware.html)的
    - 它是快速，集思廣益，極簡的Node.js Web架構。易於與database做連線，像是MongoDB, Redis, MySQL
    - 不能忍[Callback](https://eyesofkids.gitbooks.io/javascript-start-from-es6/content/part4/callback.html)
- @[Golang](https://ithelp.ithome.com.tw/articles/10233791)
    -
    - 是由 Google 發展的泛用型程式語言。同時具備簡潔的語法和優秀的效能
    - 背後的老大哥是google
- #Gin
    -
    - 使用 golang 所開發出來的 web frameworkgin 就是基於gin的設計原理打造，但是效能比 martini 還要強大框架。Gin 是一套用 golang 原生的 net/http package 封裝過後的框架，效能完全有保證，還有各種方便的 data binding 機制
    - JSON validation：Gin 可以解析和驗證傳進來的 JSON。 Crash-free：Gin 可以攔截 HTTP 請求過程中發生的 panic 並從中復活，如此你的伺服器將可以總是活著。
    - 不適合 CPU 密集的應用

**所選用的框架及語言**
===
### 框架:[Gin](https://ithelp.ithome.com.tw/articles/10244740)

### 語言:[Go language](https://ithelp.ithome.com.tw/articles/10233791)
### 理由: 
#### Gin是個簡單輕量的框架，設定簡單，撰寫簡單，沒有太多包袱也不用綁定一堆工具，比起 Spring boot 更好上手，這可以算是優點也算缺點，短周期可以快速開發。Go提供net/http包, 能提供路由、靜態文件、Template、Cookie、檔案系統等。[保留字](https://www.taroballz.com/2018/03/24/Go_package/)只有25個


