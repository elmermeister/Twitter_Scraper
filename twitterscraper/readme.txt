1.在路徑裡 開啟 cmd 以下是我的電腦的 每個人的不同
C:\Users\Elmer\Desktop\twitterscraper-master\twitterscraper
2.爬取想要的資料 在cmd中打上

twitterscraper "X AND pregnant" --lang=en --limit 3000 -o tweets.json

X為WORD中的關鍵字 以下以pain-medicine為例

twitterscraper "Pain-medicine AND pregnant" --lang=en --limit 3000 -o tweets.json


3.從 json轉成csv 
跑完之後 資料夾中會有個tweet.json檔
檔案大小不一 則數上限為3000則

在cmd中打上 
python json_to_csv.py 
資料夾中會再出現一個 tweet.csv檔

4.把資料名稱一律改成 
tweet_X.json
tweet_X.csv
並存放在各自的資料夾中


ps . 
1.實驗室電腦3000則跑下來約需50秒 
2.大小寫爬取資料一樣 ex : Vitamin ,vitamin
3.有沒有 '-' 沒有差別 爬起來資料依樣ex :anti-anxiety-meds ,anti anxiety meds 