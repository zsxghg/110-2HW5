# 作業5
# 使用案列1
| 使用案列名稱 | 會員註冊登入作業 |
| :----- | :----- |
| 使用案列描述 | 使用者進行系統註冊、登入 |
| 主要參與者 | 使用者 |
| 利害關係人與目標 | 使用者:進入系統進行個人基本資料修改 |
| 前置條件 | 帳號密碼沒有註冊過 |
| 後置條件 | 使用者成為會員，可以改個人基本資料 |
| 主要成功情節 | 1.使用者輸入帳號密碼進行註冊 |
|  | 2.使用者依需求填入不同基本資料 |
|  | 3.使用者想成為駕駛，需填入平日上班地點、提供空位數量、聯絡資訊 |
|  | 4.使用者想成為乘客，需填入平日上班地點、出發地點、聯絡資訊 |
|  | 5.使用者可修改上述經本資料 |
| 例外情節 | 系統維護時，暫停會員註冊與使用，顯示維護訊息 |
| 其他需求 | 帳號密碼須為英文數字結合，超過八位 |
# 使用案列2
| 使用案列名稱 | 系統判斷作業 |
| :----- | :----- |
| 使用案列描述 | 系統匹配之判斷 |
| 主要參與者 | 系統 |
| 利害關係人與目標 | 系統可以準確的匹配路線、目的地相同的使用者 |
| 前置條件 | 使用者填入路線、目的地資料 |
| 後置條件 | 無 |
| 主要成功情節 | 1.系統經由導航去判斷使用者填入路線的合理性 |
|  | 2.系統挑選相同路線駕駛與乘客進行匹配 |
|  | 3.系統進行匹配成功與失敗的判斷 | 
|  | 4.紀錄匹配成功的乘客與滿座位的駕駛，使系統不會再用此使用者與其他未匹配的使用者匹配 |
|  | 5.匹配失敗的乘客與座位未滿的駕駛，系統可再次進行匹配 |
| 例外情節 | 系統維護時，暫停會員註冊與使用，顯示維護訊息 |
| 其他需求 | 使用者短時間多次匹配失敗，詢問是否需要幫助 |
# 使用案列3
| 使用案列名稱 | 會員匹配作業 |
| :----- | :----- |
| 使用案列描述 | 系統匹配路線相近駕駛與乘客 |
| 主要參與者 | 駕駛、乘客 |
| 利害關係人與目標 | 駕駛:順利取得客人、乘客:得到適合的駕駛 |
| 前置條件 | 成為會員，並輸入必要資料 |
| 後置條件 | 雙方成功匹配 |
| 主要成功情節 | 1.系統依雙方目的地、通勤路段等匹配駕駛與乘客 |
|  | 2.首次匹配隱藏雙方基本資料，只提供email進行聯絡 |
|  | 3.首次匹配後會詢問雙方意見，確認是否滿意此匹配 |
|  | 4.匹配成功後才將個人資料傳送對方，方便後續事宜 |
|  | 5.匹配失敗可重新批配 |
| 例外情節 | 系統維護時，暫停會員註冊與使用，顯示維護訊息、無可匹配乘客/駕駛，顯是提醒訊息 |
| 其他需求 | 無 |
