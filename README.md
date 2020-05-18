# AnimalCrossingLineBotUpdateDoc
此為「集合啦！動物森友會」於Line上的機器人「Line狸端機」的更新紀錄與反饋回應紀錄

---
## 機器人功能與指令
1. 找DIY配方 輸入做[道具關鍵字] 例如: @做櫻花、@做櫻花傘
> 此功能進行模糊比對，如果搜尋櫻花可能會取得更多與櫻花相關的配方<br>
> 特別注意當如果輸入配方的內容包含精準內容時，僅會顯示精準項目，例如搜尋「鏟子」時，會直接帶出鏟子的配方，不會出現「金色鏟子」
> 如果有要查看其他鏟子資訊，建議輸入「@做**鏟**」的關鍵字

2. 找島民與特殊島民資訊 輸入誰是[島民名稱]或[島民名稱]是誰 例如: 誰是阿保、傑克是誰、誰是狸克
> 此功能支援中(繁體)、英文、日本搜尋

3. 查種族分類 「@種族」例如: @種族
> @符號目前設計是半形

4. 找島民種族 「@種族 種族名稱」 例如: @種族 貓
> 目前僅支援行動裝置上的Line APP <br>
> 使用**精準比對**

5. 找島民個性分類 輸入「@個性」例如: @個性
> 目前僅支援行動裝置上的Line APP <br>
> 使用**精準比對**

6. 找島民個性 輸入「@個性 個性分類」例如: @個性 自戀、@個性 悠閒
> 目前僅支援行動裝置上的Line APP <br>
> 使用**精準比對**

7. 找今天誰生日 輸入「@生日」例如: @生日
> 僅顯示今日生日的島民

8. 找島民生日 輸入「@生日 Month/Day」例如: @生日 04/22、@生日 12/31
> 輸入錯誤將不回應

9. 查詢售價 輸入「@賣魚名稱/昆蟲名稱/植物水果名稱」(目前僅支援魚、昆蟲、水果植物) 例如: @賣鱒魚、@賣狼蛛、@賣櫻桃
> 目前僅支援魚、昆蟲<br>
> 使用**精準比對**

10. 查詢蟲魚捕捉情報「@魚 [魚名稱]」、「@蟲 [蟲名稱]」 例如: @魚 鯨鯊、@蟲 狼蛛
> 目前僅支援魚、昆蟲<br>
> 使用**精準比對**比對單一項目
> 使用**模糊比對**比對多個選單
> 這個分類是官方的分類，因此青蛙、鯊魚、鯨魚等，雖然不是魚，但是被分類到@魚

11. 查詢某月蟲魚清單「@魚 (月份)月」、「@蟲 (月份)月」 例如: @魚 7月, @蟲 7月
> 目前功能顯示較為簡陋，請見諒

12. 查詢化石 輸入「@植物 [植物名稱]」 例如: @植物 橘色波斯菊
> 使用**模糊比對**

13. 查詢化石 輸入「@化石 [化石名稱]」 例如: @化石 暴龍
> 使用**模糊比對**

14. 查詢藝術品 輸入「@藝術品 [藝術品分類、名稱、真實名稱]」例如: @藝術品 名畫、@藝術品 雕塑、@藝術品 名貴的名畫、@藝術品 星空
> 使用**模糊比對**
> 特別加入畫作真偽，也加入真實畫作的名字與作者，都可以透過關鍵字來搜尋到

15. 查詢家具 輸入「@找 [家具名稱]」 例如: @找 木吉他、@找 螞蟻農場
> 使用**模糊比對**，但遇到多個相似項目必須精準比對<br>
> Icon圖示分別為：可以改造、可以浬點購買、可以DIY、可以網購<br>
> 支援 家具、裝飾品、壁掛物、地毯、地版、壁紙、柵欄分類
> @找為新增的指令，原本的@家具依舊可以用，但建議使用@找(比較精簡)

16. 查詢服飾 輸入「@找 [服飾名稱]」 例如: @服飾 蘋果服、@服飾 牛仔帽、@服飾 針織罩衫&襯衫
> 使用**模糊比對**，但遇到多個相似項目必須精準比對<br>
> Icon圖示分別為：可以改造、可以浬點購買、可以DIY、可以網購<br>
> 支援 上身、下身、套裝、頭戴、飾品、鞋子、背包、雨傘


17. 方便工具 輸入「@tools」

18. 在聊天室與群組移除「Line狸端機」 輸入「@bye」
---
# 更新版本
20200518
* [Released] v2020051801 新增「@找」指令內容，加入改造本體、樣式、數量與DIY反查
> 近期會進行翻譯

20200515
* [Released] v2020051501 調整@魚[月份]與@蟲[月份]指令
> 改採用網頁顯示

20200512
* [Fixed] v2020051202 資料修正「DIY:高架花籃、島民:柴姐」指令
* [Released] v2020051201 新增島民房子與贈與服裝風格顏色偏好
> 送對應的顏色服飾有助於增加好感度

20200511
* [Released] v2020051102 新增查詢「@找 xxx」指令(原@家具指令)
* [Released] v2020051101 新增查詢「@服飾 xxx」指令

20200510
* [Fixed] v2020051003 修正Bug(DIY:改造icon顯示)
* [Fixed] v2020051002 修正Bug(@種族 綿羊2 沒反應、@種族 小熊 3沒反應、個性成熟及悠閒男女、家具:液晶螢幕無法顯示)
* [Released] v2020051002 新增家具指令資料(包含柵欄、地板、地毯、壁紙)
* [Fixed] v2020051001 家具指令無反應bug

20200509
* [Released] v2020050901 新增家具指令資料(包含柵欄、地板、地毯、壁紙)
* [Fixed] v2020050901 修正資料(島民:儒林口頭禪)

20200508
* [Fixed] v2020050802 修正資料(DIY:鑄鐵花園長椅)
* [Fixed] v2020050801 調整因為更新樣板產生的bug、修正資料(島民:章丸丸口頭禪)
* [Released] v2020050801 更新島民樣板，新增項目(偏好衣服的顏色與風格)，*注意:此並非島民喜顏色，而是衣服的偏好顏色與風格*

20200507
* [Fixed] v2020050702 修正(DIY:綠色草裙、花園長椅，島民:肉肉、余板)
* [Released] v2020050701 新增特殊島民(指令範例:「誰是狸克」)

20200506
* [Released] v2020050603 新增壁掛資料(指令範例:「@家具 壁掛式蠟燭」
* [Fixed] v2020050603 修正資料(DIY:星星側背包)
* [Fixed] v2020050602 修正資料(蟲:竹節蟲、島民:史培亞)、調整UI
* [Released] v2020050601 家具指令新增項目(擺飾類)

20200505
* [Fixed] v2020050501 資料修正(DIY:手押式汲水器、星星掛掛旗)

20200504
* [Released] v2020050401 新增雜物販售(例如:@賣金礦石、@賣沙錢)
* [Fixed] v2020050401 資料修正(島民性別遺漏:花卷)

20200503
* [Fixed] v2020050302 資料修正(家具來源未翻譯完成導致bug未顯示)
* [Fixed] v2020050301 資料修正(DIY:竹製燭台、深色竹地毯、繽紛三色堇花圈)

20200502
* [Fixed] v2020050204 新增資料(植物:椰子)
* [Fixed] v2020050203 資料修正(DIY:石桌)
* [Fixed] v2020050202 UX調整(昆蟲、魚查詢)
* [Released] v2020050201 新增家具查詢

20200501
* [Fixed] v2020050101 資料修正(島民:番茄醬的名言、DIY:夏蜜柑服)

20200430
* [Released] v2020043003 新增魚與昆蟲月份彙整清單、新增賣植物清單
* [Fixed] v2020043002 資料植物指令錯誤「@植物 xx」、Bug修正
* [Fixed] v2020043001 資料修正(DIY配方: 石凳子)、加入遊戲1.2.0版的植物內容(灌木)

20200429
* [Fixed] v2020042903 調整「@藝術品」指令使用者體驗與修正誤植內容、調整「是誰」指令bug
* [Released] v2020042902 新增植物情報功能
* [Update] v2020042901 調整「賣」、「做」指令

20200428
* [Released] v2020042802 新增蟲魚情報功能
* [Fixed] v2020042801 資料修正(DIY配方: 常見庭園石、高聳庭園石、棕櫚樹燈)

20200427
* [Released] v2020042702 修正流量問題
* [Fixed] v2020042701 資料修正(DIY配方: 鋼筋)

20200426
* [Released] v2020042601 說明文字修正、資料修正(DIY配方:圓木長椅、高架花籃、徽章門牌)
* [Released] v2020042601 新增化石查詢、藝術品查詢(辨識功能與真實資訊

20200424
* [Released] v2020042402 新增化石查詢、藝術品查詢
* [Fixed] v2020042401 修正資料(DIY配方名稱:野外圓木長椅、銀河系地板、--椰子燈--)

20200423
* [Fixed] v2020042301 修正資料(DIY配方名稱:鑄鐵花園長椅、鐵甲面罩、金頭盔；島民生日太平)

20200422
* [Released] v2020042203 修正資料(DIY配方名稱:流水素麵；島民名稱范妮莎、毬藻)
* [Released] v2020042202 新增生日查詢、個性查詢
* [Fixed] v2020042201 加入資料(鑄鐵花園長椅、草編後背包)
* [Fixed] v2020042201 修正資料(日落蛾名稱錯誤、金色糞金龜名稱錯誤、俞司廷名稱錯誤)

20200421
* [Released] v2020042002 新增蟲類、魚類查詢售價
* [Fixed] v2020042101 加入資料(高架花籃)


20200420
* [Released] v2020042002 新增可以查詢種族功能
* [Fixed] v2020042001 修正DIY工作台比對問題


20200419
* [Fixed] v2020041902 修正島民英文名稱大小寫比對問題
* [Fixed] v2020041901 調整找尋島民敏感度，僅有「結尾為**是誰**」、「開頭為**誰是**」會被進行搜尋

---
# 問卷反饋
所有填表單回饋於我的問題，我將於此地方進行回覆，希望有答覆到你們的問題:) <br>
👉 https://lihi1.com/nY9Ah

---
# 致謝
* 梓鈞
* ShihChi Hsu
* 阿D(許仲廷)
* 林澄子
* 林孟璇
* KeKe

## 特別感謝
提供所有回報的人🙏<br> 如果您也有提供資料並想公布致謝名單，請與我聯絡😃

## 我也想貢獻
如果您對資料校正翻譯也有興趣，歡迎連絡我
