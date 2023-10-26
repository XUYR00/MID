# **UML之靜態圖---類圖、對象圖**
## ①、什麼是類? 什麼是對象? 他們的關係是什麼?
> 類:類是具有相同屬性和服務的一組對象的集合。
## ②、
## ③、
## ④、
## ⑤、
## ⑥、
## 6.2、類的關係
## 6.2.1關聯關係: ![image](https://github.com/XUYR00/MID/blob/main/arrow1.png)
>描述了類的結構之間的關係，具有方向、名字、角色和多重性等信息。
![image]()
>一般的關聯關係語意較弱，也有兩種語意較強，分別是聚合和組合
## 聚合關係:![image](https://github.com/XUYR00/MID/blob/main/arrow2.png)
>特殊關聯關係，指明一個聚合(整體)和組成部分之間的關係
![image](https://github.com/XUYR00/MID/blob/main/pic2.png)
## 組合關係:![image](https://github.com/XUYR00/MID/blob/main/arrow3.png)
>語意更強的聚合，部分和整體具有相同的生命週期
## 6.2.2、泛化關係:![image](https://github.com/XUYR00/MID/blob/main/arrow4.png)
>在面向對象中一般稱為繼承關係，存在於父類與子類、父接口與子接口
## 6.2.3、實現關係:![image](https://github.com/XUYR00/MID/blob/main/arrow5.png)
>對應於類和接口之間的關係
## 6.2.4、依賴關係:![image](https://github.com/XUYR00/MID/blob/main/arrow6.png)
>UML類圖依賴關係是一種使用關係，特定事務的改變有可能會影響到使用該事物的事物，反之不成立。在你想顯示一個事務使用另一個事物時使用，兩個元素之間的一種關係，其中一個元素(服務者)的變化將影響另一個元素(客戶)，或向它(客戶)提供所需信息。
## ⑦、類圖思維導圖
## ⑧、以機房收費系統為實例繪製類圖
## 8.1、首先尋找類，可通過尋找名詞，動詞來確定
>需求過程中的名詞組
>
![image](https://github.com/XUYR00/MID/blob/main/8.1%E5%90%8D%E8%A9%9E%E7%B5%84.png)
>
>需求過程中的動詞組
>
![image](https://github.com/XUYR00/MID/blob/main/8.1%E5%8B%95%E8%A9%9E%E7%B5%84.png)
## 8.2、繪製類圖
![image]()
## ⑨、對象圖
## 9.1什麼是對象圖?
>對象圖也是靜態圖的一種，但是對象圖描述一個系統在某個時刻的靜態結構，顯示的是對象與對象之間的關係，而類圖描述所有可能的情況。
>>對象圖是類圖的實例，只有對象而無類的類圖就是一個對象圖。對象圖有生命週期因此對象圖只能在系統某一個時間段存在。對象圖作為系統在某一時刻的快照，是類圖中的各個類在某一個時間點上的實例及其關係的靜態寫照。
## 9.2類圖與對象圖的區別?
![image](https://github.com/XUYR00/MID/blob/main/9.2.png)
## 對象圖:
![image]()

