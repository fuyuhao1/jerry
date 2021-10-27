#  OSI七層的作用

## .[第一層]
- 1.實體層（Physical Layer）在局部區域網路上傳送資料框（Data Frame），它負責管理電腦通訊裝置和網路媒體之間的互通。包括了針腳、電壓、線纜規範、集線器、中繼器、網卡、主機介面卡等。 

## .[第二層]
- 1.資料連結層（Data Link Layer）負責網路尋址、錯誤偵測和改錯。
- 2.分為兩個子層：邏輯鏈路控制（logical link control，LLC）子層和媒介存取控制（Media access control，MAC）子層。

## .[第三層]
- 1.網路層（Network Layer）決定數據的路徑選擇和轉寄，將網路表頭（NH）加至數據包，以形成封包。
- 2.網際網路協定（IP）等。

## .[第四層]
- 1.傳輸層（Transport Layer）把傳輸表頭（TH）加至數據以形成數據包。傳輸表頭包含了所使用的協定等傳送資訊。例如:傳輸控制協定（TCP）等。

## .[第五層]
- 1.會議層（Session Layer）負責在數據傳輸中設定和維護電腦網路中兩台電腦之間的通訊連接。

## .[第六層]
- 1.表達層（Presentation Layer）把數據轉換為能與接收者的系統格式相容並適合傳輸的格式。

## .[第七層]
- 1.應用層（Application Layer）提供為應用軟體而設計的介面，以設定與另一應用軟體之間的通訊。例如：HTTP、HTTPS、FTP、Telnet、SSH、SMTP、POP3等。
