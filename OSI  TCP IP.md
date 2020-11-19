# computer network 計算網路概論

![擷取.JPG]_ (擷取.JPG)

```
網路通訊傳輸協定(communcation protocol):在電信領域中,允許兩個或多個在傳輸系統中的終端之間傳播資訊的系統標準。
```
分層是為了利用層次結構可以把開放系統資訊交換問題分解到一系列容易控制的軟硬體模組。
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

1TCP 可靠:資料錯誤會重傳/threeway handshaking

2UDP 不可靠:資料不會重傳,丟失就不見了

會議層(Session Layer)
 
 1負責建立、管理、以及終止兩個通訊主機的對話

表現層 (Presentation Layer)

 1 處理不同資料格式之間的字碼轉換及編碼及解碼
 
應用層 (Application Layer)

 1 檔案、印表、訊息、資料庫、應用服務
 
 2 http、https
``` 
 
