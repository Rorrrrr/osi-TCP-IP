# computer network 計算網路概論



```
網路通訊傳輸協定(communcation protocol):在電信領域中,允許兩個或多個在傳輸系統中的終端之間傳播資訊的系統標準。
```
```
分層是為了利用層次結構可以把開放系統資訊交換問題分解到一系列容易控制的軟硬體模組中。
```
```

實體層( physical layer)
 
1 為資料端裝置提供傳送資料通路
 
2傳輸資料
 
3設備:集線器hub 

資料連結層(Data Link Layer)
 1流量控制 錯誤控制
 
 2MAC 網卡有48bit 獨一無二的實體位址
 
 3設備:交換器 switch

網路層(Network Layer ) 

 1提供路由和尋址的功能，使兩終端系統能夠互連且決定最佳路徑，並具有一定的擁塞控制和流量控制的能力
 
 2IP 網路定址
 
 3設備:路由器roter  二或多個網路相連接,在網路上將資料導引到正確的通訊裝置
 
傳輸層(Transpot Layer)

1TCP:(Transmission Control Protoco) ,可靠,資料錯誤會重傳/threeway handshaking

2UDP:(User Datagram Protocol) ,不可靠,資料不會重傳,丟失就不見了
三向交握 (Three-way Handshake):client  ---SYN-->  Server
                                 |     <--SYN+ACK-- |
                                 |     ---ACK--->   |
會議層(Session Layer)
 
 1負責建立、管理、以及終止兩個通訊主機的對話

表現層 (Presentation Layer)

 1 處理不同資料格式之間的字碼轉換及編碼及解碼
 
應用層 (Application Layer)

 1 檔案、印表、訊息、資料庫、應用服務
 
 2 http、https
``` 
```
1HTTP:(HyperText Transfer Protocol),規範了客戶端請求與伺服器回應的標準，OSI中的應用層
 HTTPS:(HyperText Transfer Protocol Secure),使用HTTP進行通訊但通訊過程有進行加密在OSI中的應用層
2.TELNET:供使用者在本地主機執行遠端主機上的工作。在應用層
  SSH:(Secure Shell),通過在網路中建立安全隧道來實現SSH客戶端與伺服器之間的連接,在應用層
3.DNS:將域名和IP位址相互對映的一個分散式資料庫，能夠使人更方便地存取網際網路
4.IP:(Internet Potocol),任務僅僅是根據源主機和目的主機的位址來傳送資料,Network Layer
5.ICMP:(Internet Control Message Protocol),提供可能發生在通訊環境中的各種問題回饋,Network Layer
```
```

Hub:集中網路內多條纜線,並傳輸所有資料至中央裝置,Physical Layer
Repeater:將輸入訊號增強放大的類比裝置,
Switch集中多條纜線的中心點,但他指將資料傳給預先決定的收件方,Data Link Layer
Bridge:網路的多個網段在資料鏈路層連接起來,Data link Layer
Router:一種將二或多個網路相連接,並負責導引資料網路傳輸到達正確目的地,Neterwork Layer
L3 Switch:以硬體的方式來加速路由運算與封包傳送率並結合Layer 2 的彈性設定,Data Link Layer
Proxy:允許一個客戶端通過這個服務與另一個網路終端進行非直接的連接
```
```

PORT address:在一個電腦作業系統中扮演通訊的端點,每個通訊埠都會與主機的IP位址及通訊協定關聯Transport Layer
IP address:當裝置連接網路，裝置將被分配一個IP位址,相當於住家地址 Neterwork Layer
MAC address:MAC位址用於在網路中唯一標示一個網卡，一台裝置若有一或多個網卡，則每個網卡都需要並會有一個唯一的MAC位址=身分證,DATA Link Layer
```
