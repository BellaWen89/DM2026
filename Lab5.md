## Challenge 2.1（九宮格計數）
<img width="1320" height="716" alt="image" src="https://github.com/user-attachments/assets/5f8f1b48-61d5-4227-8a60-6a2fc6e0686a" />
<img width="1858" height="753" alt="image" src="https://github.com/user-attachments/assets/08aa7c90-d3ce-4df2-82f8-bb420f61c58f" />
<img width="1743" height="180" alt="image" src="https://github.com/user-attachments/assets/ce5d0a19-9d5f-4647-8c8d-c5b871e15763" />

教學思路：
我會用九宮格遊戲來教初學者。先讓他們觀察每一排，再檢查每一個格子。如果看到「X」，就把地雷數量加一。

降維說明法：
這就像在教室裡找有貼紅色貼紙的桌子。我們一排一排地檢查，每找到一張有紅色貼紙的桌子，就加一。最後就能知道總共有幾張。

透過這次練習，我學會使用巢狀 for 迴圈檢查二維串列中的每一個元素，並使用 if 條件判斷和計數器來計算地雷數量。


## Challenge 2.2（剩餘安全區機率）
<img width="1320" height="739" alt="image" src="https://github.com/user-attachments/assets/fc8999f1-8709-4ce3-86ba-9e64610a4a64" />
<img width="1850" height="744" alt="image" src="https://github.com/user-attachments/assets/4f8388dc-30f5-4219-8b9f-26f98c6075aa" />

教學思路：
我會先教初學者計算剩下多少個格子，再用地雷數量除以剩餘格子數量，最後乘以 100，算出百分比。

降維說明法：
這就像一個袋子裡有 81 顆球，其中 10 顆是紅球。我們先拿走 11 顆不是紅色的球，剩下 70 顆球。如果隨機拿一顆，拿到紅球的機率就是 10 ÷ 70 × 100%，大約是 14.3%。

透過這次練習，我學會使用 Python 的除法和乘法來計算機率，也了解當安全格子被打開後，剩餘格子的地雷機率會改變。


## Challenge 2.3（鄰居檢查器）
<img width="1320" height="625" alt="image" src="https://github.com/user-attachments/assets/049044db-1ddd-414b-b4d2-6c66d23fe55f" />
<img width="1996" height="932" alt="image" src="https://github.com/user-attachments/assets/a58c3b3c-85a9-4147-afde-499f6dbb5796" />

教學思路：
我會先讓初學者觀察串列中的五個元素，再使用 for 迴圈逐一檢查。如果遇到 "X"，就把計數器加一，最後印出地雷總數。

降維說明法：
這就像檢查五個盒子，其中有些盒子放了糖果。我們一個一個檢查，每找到一個有糖果的盒子，就加一。最後就能知道有幾個盒子放了糖果。

透過這次練習，我學會使用 for 迴圈和 if 條件判斷，檢查串列中的元素，並計算符合條件的數量。


## Challenge 2.4（更新盤面）
<img width="1320" height="714" alt="image" src="https://github.com/user-attachments/assets/3233bd42-ad81-445f-adb9-6b6b16a7c656" />
<img width="1994" height="740" alt="image" src="https://github.com/user-attachments/assets/1ccf0c24-6112-4c65-bb39-5008f768a38f" />

教學思路：
我會先讓初學者觀察一個 2×2 的表格，再教他們使用兩層 for 迴圈，逐一檢查每個格子。如果格子裡是 0，就把它改成 1。

降維說明法：
這就像老師檢查學生的作業表格。如果格子裡是 0，就把它改成 1；如果是 "X"，就保持不變。這樣就能理解如何使用程式修改表格中的資料。

透過這次練習，我學會使用巢狀 for 迴圈和索引 board[r][c]，找到二維串列中的元素，並使用 if 條件判斷修改資料。


## Challenge 2.5（地雷密度評估）
<img width="1320" height="849" alt="image" src="https://github.com/user-attachments/assets/3d3fd02a-85eb-4451-931c-7ffc2a82e816" />
<img width="2242" height="700" alt="image" src="https://github.com/user-attachments/assets/3dcf8bcb-528f-4cd7-9f63-251519d48481" />
<img width="1926" height="639" alt="image" src="https://github.com/user-attachments/assets/cd773d62-acad-4924-8762-da2cbba3c59d" />

教學思路：
我會先教初學者計算兩個格子的地雷密度，再使用 if 條件判斷比較百分比，找出比較危險的格子。

降維說明法：
這就像兩個袋子裡有紅球。A 袋有 8 顆球，其中 3 顆是紅球；B 袋有 5 顆球，其中 2 顆是紅球。A 袋抽到紅球的機率是 37.5%，B 袋是 40%。所以 B 袋比較容易抽到紅球。

透過這次練習，我學會使用除法和乘法計算百分比，並利用 if、elif 和 else 比較兩個格子的地雷密度。我也了解判斷危險程度時，不能只看地雷數量，還要考慮周圍格子的總數。




