# Introducing-Python_Fumitaka-Osawa
First practice of python coding. According to the book from Fumitaka Osawa


#此為Python 練習上碰到的相關指令與習題，一章節區分，並且練習紀錄於此


Lesson 5-2 Hit&Blow in one int--


import random

a = random.randint(0 , 9)
print(a)

b = int(input("輸入數字哦>"))  #要有int，否則會變成用數值比較字串，不論正確與否都會回絕

if a == b:
    print("you are right")
else:
    print("you are wrong")

