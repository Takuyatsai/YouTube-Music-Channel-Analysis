# YouTube-Music-Channel-Analysis
![image](https://github.com/Takuyatsai/YouTube-Music-Channel-Analysis/blob/main/Practice/Homepage.png)


本專案透過YouTube v3 API分析部分音樂頻道當前的成長狀況，包括訂閱人數、影片的流量等內容。
若想要從頭開始了解如何達成，可以從[此文章](https://medium.com/@alextsai6290/01-%E4%B8%8D%E5%90%8C%E6%96%B9%E5%BC%8F%E8%A7%80%E5%AF%9Fyoutube%E6%95%B8%E6%93%9A-%E4%B8%80-b248ea6fe5bb)開始探索。

## 選擇頻道
本專案主要查詢音樂相關頻道，並依個人判斷的主題作為分析目標

頻道名稱                  | 類型  | 訂閱人數 |
-------------------------|:---------|:---------|
[Ru's Paino Ru 味春捲](https://www.youtube.com/channel/UCAYrMNl92jw6cpjdpBP8JyA)   |樂器類 |242萬|
[Pan Paino](https://www.youtube.com/channel/UCI7ktPB6toqucpkkCiolwLg)   |樂器類 |347萬|
[2CELLOS](https://www.youtube.com/channel/UCyjuFsbclXyntSRMBAILzbw)   |樂器類 |640萬|
[The Paino Guys](https://www.youtube.com/c/thepianoguys)   |樂器類 |706萬|
[Joe Hisaishi Official](https://www.youtube.com/channel/UCxyzciBLt1Hyw06dlqwAIkw)   |樂器類 |91.8萬|
[Ado](https://www.youtube.com/channel/UCln9P4Qm3-EAY4aiEPmRwEA)   |個人 |479萬|
[Ayase / YOASOBI](https://www.youtube.com/channel/UCvpredjG93ifbCP1Y77JyFA)   |團體 |436萬|
[星野源](https://www.youtube.com/channel/UCPKlrgZXnnb89nSeITvTdGA)   |個人 |150萬|
[美波](https://www.youtube.com/channel/UC2JzylaIF8qeowc7-5VwwmA)   |個人 |135萬|
[あいみょん](https://www.youtube.com/user/aimyong)   |個人 |184萬|
[ヨルシカ / n-buna Official](https://www.youtube.com/c/nbuna)   |個人 |267萬|
[周興哲](https://www.youtube.com/channel/UC7S48XRADBqamQbgLxpBFcQ)   |個人 |114萬|
[周杰倫](https://www.youtube.com/channel/UC8CU5nVhCQIdAGrFFp4loOQ)   |個人 |276萬|
[The First Take](https://www.youtube.com/channel/UC9zY_E8mcAo_Oq772LEZq8Q)   |多個不同團體 |750萬|
[kobasolo](https://www.youtube.com/channel/UCDbQblY1XASbgqOXmy6FOFQ)   |Cover |303萬|
[First To Eleven](https://www.youtube.com/c/FirstToEleven)   |Cover |154萬|

本篇主要使用Python抓取資料，透過Pandas, Numpy, Matplotlib, WordCloud等套件來完成此項專案
