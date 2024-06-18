# 作業7 - 最短運輸距離
本次作業提供一張鐵路路線圖，假設每個城市之間的路線長度是一樣的(假設為1)，每座城市在程式中的代號如下:
Smedshammer 0
Mizala 1
Kalwellpope 2
Frazerburgh 3
Shikasaki 4
我們要用廣度優先走訪的方式找到以下三個資訊:
1. 每個城市相鄰的城市
2. 使用BFS走訪每座城市的結果
3. 找出一個城市到其他城市的最短距離
在bfs函式中會進行廣度優先走訪，其中global distance變數紀錄最短距離，並列出每個城市相鄰的城市、使用BFS走訪每座城市的結果，並找到一個城市到其他城市的最短距離，請完成這個函式，這個函式不用回傳數值。
