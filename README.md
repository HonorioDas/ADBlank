# ADBlank
### Screenshots

### iPhone

<table align="center" border="0">

<tr>
<td> <img src="https://raw.githubusercontent.com/HonorioDas/ADBlank/master/1.png"> </td>
<td> <img src="https://raw.githubusercontent.com/HonorioDas/ADBlank/master/2.png"> </td>
</tr>

<tr>

</tr>


</table>

### Description

<br>
Safari 瀏覽器專用的擋蓋版廣告延伸插件。目前支援常見的台灣網站，如自由、蘋果、中時、聯合、中央社、NOWnews、新浪、東森、天下、三立、Mobile01、痞客邦、Xuite、T客邦、科技新報等，並且不定期自動更新，並歡迎使用者提報廣告網站。使用 iOS 專用的擋廣告 API，隱私安全無虞。
<br>
瀏覽網站時遇到蓋版網站，往往很突然，與內文無關，又很難關閉。感覺就像是前往目的地的途中，遇到不相干的人拉住你，跟你 blah blah blah 推銷個不停，又很難中斷人家，非常煩人。
<br>
廣告是許多網站賴以為生的收入來源，所以 Blahker 的目的並不是消除所有的廣告，而只針對那些通常與內文無關又煩人的蓋版廣告。目前 ADBlank 已經含括了台灣幾個常見網站的蓋版阻擋規則，未來也將以台灣的網站為主。
<br>

### 廣告阻擋原理與隱私問題

有些 iOS 廣告阻擋器是透過架設 VPN 的方式，阻止裝置存取廣告商的任何資源。但這方式最大的問題就是 VPN 完全知曉使用者的一切網路行為，對於隱私有著極大的潛在風險。

所幸在 iOS 9 之後，Apple 提供了 WebKit API 給開發者來製作廣告阻擋器。Safari 會向插件詢問阻擋網頁元素的規則，插件則按照格式回傳一 JSON 檔。在這過程中，插件程式只負責提供規則，而不知道使用者瀏覽了什麼網站，隱私得到完整的保護。而在 iOS 中則要安裝 app，然後在「設定 > Safari > 內容阻擋器」啟用 app 中所附的插件。

總而言之，Blahker 用以阻擋廣告所使用的方法是絕對不會侵犯隱私的。

### 開發者的感想
廣告阻擋器並不是終極解答。一部分人使用阻擋器，使得網站必須投放更多更重的廣告來平衡收益。到頭來，沒有用阻擋器的使用者反而會看到更多廣告，而來不及阻擋的廣告也只會更多。這其實是個經濟學的課題。
<br>
目前 AD Blank 只想針對使用者體驗最差的蓋版廣告下手。研究的過程中有發現不少網站雖然有廣告，但是沒有那麼令人厭惡，而且載入速度也能滿意。相信一定有更好的方式可以兼顧內容網站的品質與使用者體驗。
<br>

### 開發者的感想
iOS 9.0 以上

### User Information
jx856x@163.com


