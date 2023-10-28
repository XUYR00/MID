# **UML之靜態圖---類圖、對象圖**
## ①、什麼是類? 什麼是對象? 他們的關係是什麼?
> 類:類是具有相同屬性和服務的一組對象的集合。為屬於該類的所有對象提供了統一的抽象描述，其內部包括屬性和服務（方法）兩個主要部分。
> 對象：對像是系統中用來描述客觀事物的實體，是構成系統的一個基本單位。一個對象由一組屬性和這組屬性進行操作的一組服務組成。從更抽象的角度來講，對象是問題域或實現域中某些事物的一個抽象，她反應該事物在系統中需要保存的訊息和發揮的作用；它是一組屬性和有權對這些屬性進行操作的一組服務的封裝體。客觀世界是由對象和對象之間的連繫組成的。
> 類與對象的關係就如磨俱與鑄件的關係，類的實例化結果就是對象，而對一類對象的抽象就是類。類描述了一組有相同特徵（屬性）和形同行為（方法）的對象。
## ②、什麼是類圖？
> 類圖一反應類的結構（屬性、操作）以及類之間的關係為主要目的，描述了軟件系統的結構，是一中靜態建模方法。
> 類圖中的「類」與面向對象語言中的「類」的概念是對應的，是對現實世界中事物的抽象。
> ![image](https://github.com/XUYR00/MID/blob/main/1.png) ![image](https://github.com/XUYR00/MID/blob/main/%E9%A1%9E%E5%9C%96.drawio.png)
## ③、用例圖後面為什麼是畫類圖，而不是其他圖，類圖產生於什麼階段，由誰來繪製，類圖它的作用是什麼？
> 因為按照軟件工程的生命週期來運行的話，需求分析階段後便是設計階段了，而類圖產生於設計階段，由系統設計師繪製，其作用是描述系統的架構結構、指導程序員編碼。它包括系統中所有有必要指明的實體類、控制類、界面類及與具體平台有關的所有技術性信息。
## ④、類圖可分為哪兩類？
> (http://developer.51cto.com/art/201007/210700.htm)
## ⑤、站在巨人的肩膀上了解類圖（很棒的一篇文章）
> (https://blog.csdn.net/monkey_d_meng/article/details/6005764)
## ⑥、UML類圖如何繪製？
## 6.1、類的表示
## 6.1.1、類的組成
> 從上到下分為三部分，分別是類名、屬性和操作。
> ![image](https://github.com/XUYR00/MID/blob/main/6.1.1.drawio.png)
## 6.1.2、接口
> 一組操作的集合，只有操作的聲明而沒有實現。接口圖與類圖的主要區別在於頂端的<<interface>>顯示。第一行是接口名稱，第二行是接口方法。接口還有另一種表示方法，俗稱棒棒糖表示方法。唐老鴨是能講人話的唐老鴨，實現了講人話的接口。如圖：
## 6.1.3、抽象類
> 不能被實例化的類，一般至少包含一個抽像操作，與類圖的主要區別在於抽象類的名稱、方法為斜體。
## 6.1.4、模板類
> 一種參數化的類，在編譯時把模板參數綁定到不同的數據類型，從而產生不同的類。
## 6.2、類的關係
## 6.2.1關聯關係: ![image](https://github.com/XUYR00/MID/blob/main/arrow1.png)
>描述了類的結構之間的關係，具有方向、名字、角色和多重性等信息。
![image](https://github.com/XUYR00/MID/blob/main/pic1.png)
>一般的關聯關係語意較弱，也有兩種語意較強，分別是聚合和組合
## 聚合關係:![image](https://github.com/XUYR00/MID/blob/main/arrow2.png)
>特殊關聯關係，指明一個聚合(整體)和組成部分之間的關係
![image](https://github.com/XUYR00/MID/blob/main/pic2.png)
## 組合關係:![image](https://github.com/XUYR00/MID/blob/main/arrow3.png)
>語意更強的聚合，部分和整體具有相同的生命週期
![image](https://github.com/XUYR00/MID/blob/main/pic3.png)
## 6.2.2、泛化關係:![image](https://github.com/XUYR00/MID/blob/main/arrow4.png)
>在面向對象中一般稱為繼承關係，存在於父類與子類、父接口與子接口
![image](https://github.com/XUYR00/MID/blob/main/pic4.png)
![image](https://github.com/XUYR00/MID/blob/main/pic5.png)
## 6.2.3、實現關係:![image](https://github.com/XUYR00/MID/blob/main/arrow5.png)
>對應於類和接口之間的關係
![image](https://github.com/XUYR00/MID/blob/main/pic6.png)
## 6.2.4、依賴關係:![image](https://github.com/XUYR00/MID/blob/main/arrow6.png)
>UML類圖依賴關係是一種使用關係，特定事務的改變有可能會影響到使用該事物的事物，反之不成立。在你想顯示一個事務使用另一個事物時使用，兩個元素之間的一種關係，其中一個元素(服務者)的變化將影響另一個元素(客戶)，或向它(客戶)提供所需信息。

>依賴關係與其他關係的區別鏈結:(https://www.51cto.com/article/208280.html)
## ⑦、類圖思維導圖
![image](https://github.com/XUYR00/MID/blob/main/pic7.png)
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
![image](https://github.com/XUYR00/MID/blob/main/8.2.drawio.png)
## ⑨、對象圖
## 9.1什麼是對象圖?
>對象圖也是靜態圖的一種，但是對象圖描述一個系統在某個時刻的靜態結構，顯示的是對象與對象之間的關係，而類圖描述所有可能的情況。
>>對象圖是類圖的實例，只有對象而無類的類圖就是一個對象圖。對象圖有生命週期因此對象圖只能在系統某一個時間段存在。對象圖作為系統在某一時刻的快照，是類圖中的各個類在某一個時間點上的實例及其關係的靜態寫照。
## 9.2類圖與對象圖的區別?
![image](https://github.com/XUYR00/MID/blob/main/9.2.png)
## 對象圖:
![image](https://github.com/XUYR00/MID/blob/main/9.2.drawio%20(2).png)
