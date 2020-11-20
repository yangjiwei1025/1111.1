

### 1.bandwidth(頻寬), bps()
```
  (1)頻寬是特定時間內可以從一個點傳輸到另一點的數據量
  (2)頻寬（Bandwidth）是類比訊號使用的名詞
  (3)帶寬以比特率表示，並以每秒位數（bps）為單位進行度量。

```
### https://www.stockfeel.com.tw/%E9%A0%BB%E5%AF%AC-%E8%B3%87%E6%96%99%E5%82%B3%E8%BC%B8-%E9%97%9C%E8%81%AF%E6%80%A7/

### 2.RFID
```
  (1)RFID無線射頻辨識（英語：Radio Frequency IDentification
  (2)利用無線電傳輸資訊,不用接觸就能讀取相關資訊
  (3)使用電磁場來自動識別和跟踪附加到對像上的標籤
  (4)沒有電源的可藉由電磁波或的能量
```
### 3.NFC
```
  (1)近距離無線通訊（英語：Near-field communication，NFC）
  (2)由非接觸式射頻識別（RFID）演變而來距離較RFID近
  (3)是短距離而高頻率的無線電裝置
  (4)是一套通訊協議
```
### 4.cellular network
```
  (1)蜂巢式網路（英語：Cellular network），又稱行動網路（mobile network） 
  (2)是一套通訊協定
  (3)因為網路基地台覆蓋範圍呈現六邊形很像蜂巢所以叫蜂巢式網路
  (4)相鄰的區域不能使用相同頻率,會產生"同頻干擾",但是其他的可以
  ```
### 5.technology addiction
```
  (1)technology addiction{GOOGLE翻譯 技術成癮(我個人翻為 網路成癮)}
  (2)現代人過於依賴技術所產生的
  (3)技術的部份包括 視頻遊戲,網絡色情和在線賭博
  (4)因為科技發達而產生的
  ```
### 6.Crowdsourcing vs Crowdfunding[比較題]
  ```
  (1)解決問題 vs 解決資金
  (2)眾籌不是解決微任務，而是解決一種微資金。
  (3)[Crowdsourcing]將業務項目深入到微任務，然後將其分配給具有確切技能的工人，以高效地完成任務。
  (4)[Crowdfunding]眾籌平台將需要資金的個人或實體與願意捐款的社區成員聚集在一起。
```

### 7.metadata
```
  (1)分為 技術性,結構性,管理性
  (2)屬於電子形式的目錄
  (3)支援如指示儲存位置、歷史資料、資源尋找、檔案記錄等功能，進而達成協助資料檢索的目的。
  (4)為描述其他資料資訊的資料
  ```
### 8.CMS
```
  (1)內容管理系統（英語：content management system，縮寫為 CMS）
  (2)管理工作流程的一套制度  
  (3)內容是任何類型的數字資訊的結合體，可以是文字、業務文件、資料庫表單、影片、聲音等等
  (4)屬於後臺
  ```
### 9.DDos Attack
```
  (1)分散式阻斷服務攻擊（distributed denial-of-service attack）
  (2)攻擊者傳大量的垃圾內容給一台伺服器導致伺服器處理不來(Dos)
  (3)一個攻擊者用多台電腦攻擊一台伺服器(DDos)
  (4)死亡之Ping 殭屍網路攻擊 洪水攻擊 LAND攻擊
```
### 10.Botnet
```
  (1)稱為殭屍網路
  (2)駭客用分散式阻斷攻擊(DDos)一次駭入"數萬台電腦"<-殭屍
  (3)利用數萬台電腦傳送垃圾給伺服器造成伺服器癱瘓
  (4)用來傳送偽造包或者是垃圾封包，使預定攻擊目標癱瘓並「阻斷服務」。
```
### 11.RWD
```
  (1)響應式網頁設計（英語：Responsive web design，通常縮寫為RWD）
  (2)是一種網頁設計的技術做法
  (3)在不同的解析度用不一樣的排版來減少進行縮放、平移和捲動等操作行為
  (4)因為一樣排版在不同裝置例如手機電腦平板等會造成不便
```
### 12.SEO
```
  (1)搜尋引擎最佳化（英語：search engine optimization，縮寫為SEO）
  (2)不管哪一種搜尋引擎都有一套自己的演算法
  (3)搜尋引擎會根據演算法推薦給使用者相關資訊
  (4)，利用合理正當的方式，對網站資訊內容進行調整，提升在搜尋引擎上的排名

```
#2.問答與申論題 :OSI Model 與 TCP/IP protocol

### 1.解釋 communication protocol(簡稱協定 protocol)
```
協議定義了傳送訊息的規則，語法，語義和同步以及可能的錯誤恢復方法。
```
### 2. Why Layering? (為何要分層 ?)
```
為了將一個複雜的問題簡單化，分層模型就出現了，將一個複雜的問題分為多個層次，
每次只解決一個問題，而且層與層之間儘量實現低耦合，層內實現高內聚，下層的改變不會對上層產生過大的影響。


```
##### 原文網址：https://kknews.cc/tech/veejgqa.html
### 3. 列出 OSI Model 與 TCP/IP protocol對應圖
```
    註 1: 需用中英文寫出各層的名稱
    註 2:須說明 OSI Model每一層的簡略功能
```

| OSI Model | --- | TCP/IP protocol | --- |
| --- | --- | --- | --- |
| 第7層 應用層 （Application Layer）  | 提供為應用軟體而設計的介面，以設定與另一應用軟體之間的通訊。例如：HTTP、HTTPS、FTP、Telnet、SSH、SMTP、POP3等。 |  |  |
| 第6層 表達層 （Presentation Layer）  | 把數據轉換為能與接收者的系統格式相容並適合傳輸的格式。 | 應用層application layer | 例如HTTP、FTP、DNS  |
| 第5層 會議層 （Session Layer）  | 負責在數據傳輸中設定和維護電腦網路中兩台電腦之間的通訊連接。 |  |   |
| 第4層 傳輸層 （Transport Layer） | 把傳輸表頭（TH）加至數據以形成數據包。傳輸表頭包含了所使用的協定等傳送資訊。TCP,UDP,TLS/SSL更多 |傳輸層transport layer |例如TCP、UDP、RTP、SCTP  |
| 第3層 網路層 （Network Layer） |  決定數據的路徑選擇和轉寄，將網路表頭（NH）加至數據包，以形成封包。IP（v4·v6） ,ICMP（v6）  | 網路層internet layer | 對於TCP/IP來說這是網際網路協定（IP） |
| 第2層 資料連結層（Data Link Layer） | 負責網路尋址、錯誤偵測和改錯。當表頭和表尾被加至數據包時，會形成資訊框（Data Frame）。|   |  |
| 第1層 實體層  （Physical Layer） | 負責管理電腦通訊裝置和網路媒體之間的互通 | 連結層link layer | 例如乙太網路、Wi-Fi、MPLS等。 |

###4. 簡述 下列協定的功能 與特色並說明它們 運作在 TCP/IP的哪一層?
```
   (1)HTTP vs HTTPS (2) TELNET vs SSH (3)DNS (4)IP (5)ICMP
```
```

```

###5. TCP vs UDP
```
[1]英文全名
[2]須說明 reliable(可靠) vs un-reliable(不可靠)
[3]如何達到reliable(可靠)
[4]Three-way handshaking機制
```
```
[1] 英語：User Datagram Protocol，縮寫：UDP；英語：Transmission Control Protocol，縮寫：TCP

{2} TCP 前面所介紹的傳送層檢測手續﹐都會在 TCP 中得到實現。

    UDP 信息可能會在網路傳送過程中丟失﹑重複﹑或不依順序﹐
    
[3] 對於某些訊息量較大、時效性大於可靠性的傳輸來說(比方說語音 / 影像)，UDP 的確是個不錯的選擇。

```
```
[4]Three-way handshaking機制 
    A  =發出請求>  B
     
    A  <回復+請求= B
  
    A  =發出回復>  B
```
###6.簡述下列網路設備  主要功能 與 特色 及 運作在 OSI哪一層
```
(1) Hub vs Repeater
(2)Switch vs Bridge
(3)Router vs L3 Switch
(4)Proxy
```
```
(1) Hub vs Repeater
主要功能   hub 是把乙太網路的節點連接在一起，從任一個連接埠收到的訊號可以從其他的連接 埠再轉送出去  ,  Repeater  一個將輸入訊號增強放大的類比裝置，而不考慮輸入訊號種類
特色      hub 實現移動、增加和修改的自動化 , Repeater 增加通訊距離,提高可靠性                                                  
運作在 OSI哪一層    皆在實體層
```
```
(2)Switch vs Bridge
主要功能 
特色 
運作在 OSI哪一層
```
```
(3)Router vs L3 Switch
主要功能 
特色 
運作在 OSI哪一層
```
```
(4)Proxy
主要功能 
特色 
運作在 OSI哪一層
```
###7.簡述下列 簡述下列 address(位址 )的意義 與定義 在 OSI Model哪一層
```
(1)PORT address
(2)IP address
(3)MAC address
```
```
(1)PORT address
```
```
(2)IP address
```
```
(3)MAC address
```

