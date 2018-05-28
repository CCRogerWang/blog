# 聯絡方式  
手機：0916031171
Email：roger77622@gmail.com  
Line ID：chunchiwang

# 個人資料  
王濬淇/男/1988  
國立臺灣海洋大學 資訊工程系  
國立臺灣科技大學 資訊工程所 (肄業)
工作年資：5年  
LinkedIn：https://www.linkedin.com/in/ccrogerwang/  
Github：https://github.com/CCRogerWang  
期望職位：Sr. iOS Developer  
期望薪資：月薪80k~100k  

# 工作經歷  
### 一零四資訊科技股份有限公司 （ 2015年4月 ~ ）  
進入104資訊科技是一個機緣，一位104的Hunter問我是否有興趣，思考幾天後，決定去了解這間公司。面試時問了在前公司做的專案，在結束面試前給了一個小作業(實作當時104工作快找的職務列表頁)，提交了我的作業後，正式加入了104資訊科技。

**104職涯社群**  
上傳大頭照的裁切的模組，其中使用了104的網路套件跟RestFul API做溝通，利用[Jastor](https://github.com/elado/jastor)開源套件建立model。由於網路套件不易開發與維護[Jastor](https://github.com/elado/jastor)也不再維護了，我推薦同事使用 [AFNetworking](https://github.com/AFNetworking/AFNetworking)來當作與API溝通的新工具，使用[JSONModel](https://github.com/jsonmodel/jsonmodel)來當作替代[Jastor](https://github.com/elado/jastor)的方案。  

**企業大師**   
是一個人事系統，使用者可以利用App請假、查詢薪資、打卡上下班還有公司內部的社群以及聊天系統，iOS的App版本由我負責。除了Apple的UI Framework外，還使用了CoreLocation，以及上述的[AFNetworking](https://github.com/AFNetworking/AFNetworking)跟[JSONModel](https://github.com/jsonmodel/jsonmodel)。聊天室的部分使用[JSQMessagesViewController](https://github.com/jessesquires/JSQMessagesViewController)來客製化UI，Long-polling的技術跟server溝通。

**CocoaPods**  
由於團隊使用的第三套件很多且沒有被整理，所以我推薦團隊使用。自己也寫了一篇關於[如何建立private的pods](https://github.com/CCRogerWang/blog/issues/4)的教學。開發公告平台套件並且建立private pods來發佈給公司內部使用。  

**職涯經紀人**  
是一個依照您的履歷表來幫您自動推薦工作的App，像市面上的交友軟體一樣可以左滑右滑選擇喜歡或不喜歡的人，App內可以左滑右滑選擇喜歡或不喜歡的工作。根據您的選擇，App會更了解您想要的工作再推薦給您。  
部長想嘗試使用Swift來開發，由於部分的Feature已經用Objective-C開發好了，這是第一個Swift跟Objective-C混合開發的專案。導入[Alamofire](https://github.com/Alamofire/Alamofire)和Restful API溝通、[ObjectMapper](https://github.com/Hearst-DD/ObjectMapper/)建立model。再利用[AlamofireObjectMapper](https://github.com/tristanhimmelman/AlamofireObjectMapper)將接收到的JSON轉成建立好的model物件。

**Giver**  
Giver是一個傳承經驗的App，裡面有兩種角色：Giver指的是有專業的經驗想要傳承的人，Taker為想要學習某些專頁。App提供了兩方互相交流的機會。可以利用Giver分享文章、教學給Taker，我們還導入了直播，利用Straas的服務，讓Giver分享自身的經驗給眾多的Taker期望能超越比純文字教學的效果。

**104工作快找**  
104工作快找是一個重要、龐大且歷史悠久的App，程式碼之間相依性非常嚴重，導致維護或是開發新需求都要花較多的時間成本。雖然遵守了MVC架構，但是Controller已經過於龐大。  
在我經手的新需求中，嚐試寫成模組減少相依性，除了MVC架構外，我會切出另一塊Manager去處理資料相關的邏輯，避免Controller過於龐大，增加維護的成本。我也使用Autolayout來處理UI之間的位置。

### 蓋德科技股份有限公司 （ 2013年10月 ~ 2015年4月 ）
蓋德科技是一間開發穿戴式裝置的公司，公司開發的App主要是顯示Server來的資訊以及從App設定一些參數來控制裝置。

**安全天使**  
我在此專案負責維護與開發新功能。安全天使是一個多語系且平凡使用到地圖的專案，可以描繪出穿戴者目前的位置跟軌跡。有穿戴者因此[撿回一命](https://www.youtube.com/watch?v=EFaexuiz8Fc)。使用了MapKit來處理地圖的部分，網路套件是使用URLConnection來跟server取得資料。整個專案的UI是利用storyboard來開發。

**防丟天使**  
我在此專案突破的是開發了一套判斷裝置是否在使用者設定的電子圍籬內的[演算法](http://alienryderflex.com/polygon/)提供給開發Server的同仁套用，和輸入電子圍籬的UI介面。跟裝置溝通是使用CoreBluetooth，如果裝置超過設定範圍，裝置跟手機皆會發出警示音。

# 學習經歷

### 自我學習
近年來Deep Learning廣為人知，接觸過Machine Learning的我也很有興趣，所以參加了Andrew Ng在Coursera上開的[Deep Learning Specialization](https://zh-tw.coursera.org/specializations/deep-learning)並且拿到了[證書](https://zh-tw.coursera.org/specializations/deep-learning)。此課程詳細說明了Deep Learning的技術及由來，從Logistic Regression出發，講到了cost function、gradient descent、Neural Network、Back Propagation、mutil-layer Neural Network、CNN以及RNN，讓我獲益良多。  
近期內準備持續學習[Machine Learning with TensorFlow on Google Cloud Platform Specialization](https://www.coursera.org/specializations/machine-learning-tensorflow-gcp)。

### 資策會行動開發應用軟體程式設計師養成班
學習到開發iOS、Android跟HTML的技術，在結業前夕，也上架了自己的App，本身喜歡打籃球，籃球場上除了自身的技術更重要的是戰術上的配合，所以我設計了一款可以帶著走的戰術板App，請看[Demo影片](https://www.youtube.com/watch?v=iRfnTcN6oEs)。簡單的拖曳場上的旗子再按下播放鈕，戰術一目瞭然。如果擔心旗子都長得一樣，雙擊旗子還可以更換成自己的照片。

### 國立臺灣科技大學 資訊工程所
在研究所學習Machine Learning是一個很特別的經驗，我研究的題目是Anomaly Detection，利用one-class SVM對高速公路的交通資訊做建模期望找到異常的情形(這裡指的是車禍)。期間由於個人的規劃所以離開了研究所。

### 國立臺灣海洋大學 資訊工程系
學習到基本的計算機概論、資料結構、演算法、資料庫以及多種的程式語言，例如c/c++、組合語言、java、php等。

### 致謝  
感謝您閱讀我的經歷，期待有機會與您共事。  
