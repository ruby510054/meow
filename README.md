# 喵記 Meow Diary

一個讓人練習覺察和表達情緒的小網頁。選一個最接近現在的感覺，就會有一隻貓咪跑進窗外的草原，天空也會跟著你的心情變天氣。房間裡還住著一隻你養的貓，會陪著你。

不用安裝、不用註冊，打開網頁就能用。所有記錄只存在你自己的瀏覽器裡。

**線上試玩：<https://ruby510054.github.io/meow/>**

![喵記主畫面：窗外的草原、房間和寵物](docs/main.png)

## 為什麼做這個

喵記想讓「覺察和說出自己的情緒」這件事變得輕鬆一點、可愛一點：每天花幾秒鐘，跟一隻貓說說現在的感覺。

練習辨認和記錄情緒，有一些研究上的好處：

- **說出情緒的名字，情緒會緩和一點**：研究發現，把感受用文字說出來，本身就是一種調節情緒的方式（Lieberman 等人，2007）
- **分得越細，越能好好面對**：能分辨細微情緒差別的人，面對不舒服的情緒時，比較能找到合適的方法應對（Kashdan、Barrett 與 McKnight，2015）。喵記準備了 47 個情緒詞，就是為了讓人比較容易分辨自己的情緒
- **寫下來，對身心都有幫助**：把情緒經驗寫下來，對身心健康有正面的影響（Pennebaker，1997）
- **長期記錄，看見自己的規律**：記錄久了，可以從日曆上看出心情的變化，更認識自己

喵記的四個區塊，是用「舒不舒服（愉悅度）」和「能量高低」來分類情緒，這個做法來自心理學的情緒環狀模型（Russell，1980）。

> 喵記是陪你練習覺察情緒的小工具，不能取代專業的協助。如果你最近常常覺得撐不住，或是有傷害自己的念頭，請找信任的人聊聊，或撥打專線：
> - **安心專線 1925**（24 小時，免付費）
> - **生命線 1995**
> - **張老師 1980**

### 參考資料
- Lieberman, M. D., Eisenberger, N. I., Crockett, M. J., Tom, S. M., Pfeifer, J. H., & Way, B. M. (2007). Putting feelings into words: Affect labeling disrupts amygdala activity in response to affective stimuli. *Psychological Science, 18*(5), 421–428.
- Kashdan, T. B., Barrett, L. F., & McKnight, P. E. (2015). Unpacking emotion differentiation: Transforming unpleasant experience by perceiving distinctions in negativity. *Current Directions in Psychological Science, 24*(1), 10–16.
- Pennebaker, J. W. (1997). Writing about emotional experiences as a therapeutic process. *Psychological Science, 8*(3), 162–166.
- Russell, J. A. (1980). A circumplex model of affect. *Journal of Personality and Social Psychology, 39*(6), 1161–1178.

## 有什麼

### 記錄心情
- 先選「能量高低 × 舒不舒服」四個區塊之一，再從 47 個情緒詞裡挑一個最接近的，每個詞都有一句說明
- 可以複選「混合情緒」；說不上來的時候，也可以改記身體的感覺和跟什麼有關
- 一天可以記很多次，之後也能修改、刪除、補記

![記錄心情：選了「難過」，窗外就下起雨來](docs/record.png)

### 心情天氣
窗外的天空會跟著心情變：開心是晴天、平靜會出現彩虹、煩躁會起風、難過會下雨。

![四種心情天氣：晴朗、彩虹、起風、下雨](docs/weather.png)

### 窗外的草原
- 每次記錄都會有一隻貓跑進草原，花色照情緒的家族決定（共 14 種），頭上戴著那個情緒的小配件
- 貓咪會散步、玩耍、依偎，動作和表情會跟著心情不同
- 點貓咪可以聽牠說那天的心情；點草地可以放小魚乾，也可以踢毛線球

![所有情緒的配件](docs/accessories.png)

### 房間和寵物
- 房間裡住著一隻你養的貓，會在房間裡玩、睡覺，主動找你聊天，表情也會跟著你的心情變
- 可以幫牠取名字、選花色
- 窗簾有三種樣式，可以拖曳拉開、拉上

![窗簾的樣式](docs/curtains.png)

### 出門走走
按「出門走走」就能帶著寵物走到草原上，近距離跟其他貓咪玩。

![出門走走：寵物跟著一起到草原上](docs/outside.png)

### 心情日曆
每天的格子會出現當天的貓咪，也能看到這個月的心情比例。

![心情日曆](docs/calendar.png)

### 其他
- 鋼琴背景音樂、摸貓咪時的喵喵叫和呼嚕聲，都可以分開開關
- 9 種主題顏色，電腦和手機都能用

![手機版](docs/phone.png)

## 開始使用

### 線上使用
直接打開 <https://ruby510054.github.io/meow/> 就可以了。建議使用 Chrome、Edge、Firefox 或 Safari 的新版本。

### 在自己的電腦上使用
下載或 clone 這個專案，用瀏覽器打開 `index.html`。

### 放到你自己的 GitHub Pages
1. Fork 這個 repo（或把專案推到你自己的 repo）
2. 到 repo 的 **Settings → Pages**
3. **Source** 選 **Deploy from a branch**，Branch 選 `main`、資料夾選 `/ (root)`，按 **Save**
4. 等一兩分鐘，就能在 `https://<你的帳號>.github.io/<repo 名稱>/` 打開

## 資料與隱私

- 記錄只存在**你自己的瀏覽器**裡（localStorage），不會上傳到任何地方
- 清除瀏覽器資料、換瀏覽器或換電腦時，記錄會看不到，請偶爾用網頁最下面的「下載備份檔」存一份，之後可以用「從備份檔讀取」讀回來
- 直接打開本機的 `index.html` 和打開 GitHub Pages 的網址，記錄不會互通，需要用備份檔搬過去
- 想重新開始的話，可以用「清除資料」

## 自訂情緒

情緒的分類寫在 [`mood.json`](mood.json)：

```text
quadrants（4 個象限：能量高低 × 舒不舒服）
└─ families（情緒家族，例如「悲傷」）
   └─ emotions（情緒詞）
        id、label.zh、desc（說明）
        valence（愉悅度，-1 ~ 1）、arousal（能量，-1 ~ 1）
special_options：mixed（混合情緒）、unsure（說不上來）
```

為了讓網頁只用一個檔案就能打開，`index.html` 裡放了一份一模一樣的內容（在 `<script type="application/json" id="emotionData">` 裡）。改了 `mood.json` 之後，把那一段整段換成新的內容就好。

- `valence`、`arousal` 決定心情天氣和貓咪的動作
- 新增的情緒詞如果沒有專屬配件，會使用同一個家族的配件
- 新增的家族要對應哪一種表情和花色，寫在 `index.html` 的 `FAMILY_FACE` 和 `FAMILY_COAT`

## 技術

- 整個網頁就是一個 `index.html`：純 HTML、CSS、JavaScript，不需要安裝套件，也不需要建置
- 貓咪、家具、天氣都是用程式畫的 SVG
- 背景音樂和呼嚕聲用 Web Audio API 即時合成；喵叫聲是剪輯過的真實錄音，直接嵌在檔案裡
- 字型使用 Google Fonts 上的 [jf open 粉圓（Huninn）](https://fonts.google.com/specimen/Huninn)，需要網路才會載入，沒有網路時會改用系統字型

```text
.
├── index.html   # 整個網頁
├── mood.json    # 情緒分類
├── README.md
├── LICENSE      # MIT 授權
└── docs/        # README 用的截圖
```

## 素材來源

喵叫聲錄音來自 Wikimedia Commons，已剪輯成單聲、調整音量並調高音調：

| 錄音 | 作者 | 授權 |
|---|---|---|
| [2015-11-24.νιαούρισμα.Νιάου.noise reduced.flac](https://commons.wikimedia.org/wiki/File:2015-11-24.%CE%BD%CE%B9%CE%B1%CE%BF%CF%8D%CF%81%CE%B9%CF%83%CE%BC%CE%B1.%CE%9D%CE%B9%CE%AC%CE%BF%CF%85.noise_reduced.flac) | Tsester | CC0 |
| [Meow of a Siamese cat - freemaster2.wav](https://commons.wikimedia.org/wiki/File:Meow_of_a_Siamese_cat_-_freemaster2.wav) | freemaster2 | CC0 |
| [Weibliche Britisch Kurzhaar will Futter C1277 MIAUEN.wav](https://commons.wikimedia.org/wiki/File:Weibliche_Britisch_Kurzhaar_will_Futter_C1277_MIAUEN.wav) | PantheraLeo1359531 | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |

字型 [jf open 粉圓](https://github.com/justfont/open-huninn-font)（justfont）以 [SIL Open Font License 1.1](https://openfontlicense.org/) 授權。

## 作者

[@ruby510054](https://github.com/ruby510054)

## 授權

程式碼以 [MIT License](LICENSE) 授權，歡迎自由使用、修改和分享，只要保留原本的授權聲明。

喵叫聲錄音和字型依照上面「素材來源」列出的各自授權，不包含在 MIT 授權裡。
