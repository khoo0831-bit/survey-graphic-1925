# 區域計畫專號 1925：《Survey Graphic》全文中譯

1925 年 5 月 1 日出刊的 *The Survey*（Vol. LIV, No. 3, Survey Graphic Number）把整期交給美國區域計畫協會（RPAA）。本專案是這一期的繁體中文全譯，做成可互動閱讀的靜態網站。

## 內容

- 卷首語〈區域社群〉
- 13 篇專文與圖版：孟福〈第四次遷徙〉〈區域——為了安居〉、史坦〈恐龍城市〉、艾克曼〈我們在壅塞中的利害〉、蔡斯〈運煤到紐卡索〉、皮爾森蝕刻〈區域的元素〉、麥凱〈新探險〉、史密斯〈整體地看待一個州〉、布魯爾〈巨型電力——區域的建造者〉、萊特〈通往好住宅之路〉、柏登與賓〈以新城換舊城〉、哈特〈兩代社區〉，以及〈紐約的今日——與明日？〉圖表專頁
- 社論與書評欄「Letters & Life」
- 全部圖說、側欄與續頁；純廣告頁未譯

## 網站功能

- 四次遷徙互動時間軸
- 每篇與每則圖說附原刊頁碼按鈕，可開啟 66 頁原刊掃描對照
- 關鍵概念詞彙註解（註解為譯者所加，非原刊內容）
- 目次定位、字級切換、深淺色模式、手機版面

## 檔案結構

```
index.html        網站本體（單一檔案，CSS/JS 內嵌）
pages/            原刊掃描：pNN.jpg 為全頁，tNN.jpg 為縮圖（NN = 掃描頁序 01–66，原刊頁碼 = NN + 128）
translation/      各篇譯文原稿（Markdown）
.nojekyll         讓 GitHub Pages 原樣發布
```

## 用 GitHub Pages 發布

1. 在 GitHub 建立新的 repository，把本資料夾內所有檔案（含 `.nojekyll`）上傳到根目錄。
2. 進入 Settings → Pages，Source 選 *Deploy from a branch*，Branch 選 `main`、資料夾選 `/ (root)`，按 Save。
3. 約一兩分鐘後即可在 `https://<你的帳號>.github.io/<repository 名稱>/` 瀏覽。

字型由 Google Fonts 載入；離線開啟 `index.html` 時會改用系統字型，功能不受影響。

## 底本與版權

- 底本：*The Survey*, Vol. LIV, No. 3, May 1, 1925，原刊頁 129–194。掃描取自 Internet Archive，識別碼 `survey-1897_1925-05-01_54_3`（https://archive.org/details/survey-1897_1925-05-01_54_3）。
- 原刊於 1925 年在美國出版，已屬美國公有領域。
