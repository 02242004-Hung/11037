# GitHub 是一個「透過Git 進行版本控制」的「原始碼代管服務平台」。
```
是各種開源軟體(專案)的聚集地，只要專案作者公開這個專案，任何人都能存取、使用、甚至對專案的內容做出修改，
而專案作者能對這些改動用Git (等等會介紹的版本控制工具)來進行控管，進而達成一種「共同創作」的理念。
Git 與其他版控系統最大的差異就於，它解決了「單一儲存區」這項最致命的缺點，改為「分散式儲存」，
DVCs（Distributed Version Control System） 將資料分散於不同設備上(就是儲存資料的本地端)，
如此一來，就算其中一處設備損壞，也不影響其他用戶使用。
GitHub 是公開的線上平台，因此很適合拿來放一些作品集，或著是共同編輯的文案等。
而且每當有人對文案進行改動，GitHub 還會記下改動時間、編輯者等資訊，
又能在更動時檢查後再與原版合併，因此很方便團隊進行共同編輯。
```
基礎python應用
```
## 輸入與輸出(Input and Output)
python輸入:input() python輸出: print() python格式化輸出技術
## 讀取使用者輸入的整數==>使用eval()函數
a = eval(input("請輸入："))
## 可以一次輸入多（兩）個資料
a,b = eval(input("請輸入兩個數位："))
## 無條件進位 math.ceil(number) 
## 無條件捨去 math.floor(number )
## 四捨五入 round(number )
```
## 程式流程控制　之 選擇(判斷) SELECTION /DECISION
```
Python 程式碼縮排
Python 語言以冒號「:」及縮排來表示程式區塊
縮排為 1 個 Tab 鍵或 4 個空白鍵
PS: Python沒有switch
單向判斷式（if⋯）: 是非題｜對的才要做
if [條件]:
   {條件滿足才會執行}
雙向判斷式（if⋯else）: 二選一｜一定要選的
if [條件]:
   {條件滿足才會執行}
else
   {條件不滿足才會執行}
多向判斷式（if⋯elif⋯else）: 多選一
```
## 簡易計算機
```
print("選項:")
print("輸入 '+' 讓兩個數值互加")
print("輸入 '-' 讓兩個數值互減")
print("輸入 '*' 讓兩個數值互乘")
print("輸入 '/' 讓兩個數值互除")
print("輸入 'exit' 來結束程式")
user_input = input(": ") 

if user_input == "+":
   num1 = float(input("請輸入數字:"))
   num2 = float(input("請輸入另一個數字:"))
   result = str(num1 + num2)
   print("答案是 " + result)
elif user_input == "-":
   num1 = float(input("請輸入數字:"))
   num2 = float(input("請輸入另一個數字:"))
   result = str(num1 - num2)
   print("答案是 " + result)
elif user_input == "*":
   num1 = float(input("請輸入數字:"))
   num2 = float(input("請輸入另一個數字:"))
   result = str(num1 * num2)
   print("答案是 " + result)
elif user_input == "/":
   num1 = float(input("請輸入數字:"))
   num2 = float(input("請輸入另一個數字:"))
   result = str(num1 / num2)
   print("答案是 " + result)
else:
   print("不知道你在輸入什麼") 
```      
