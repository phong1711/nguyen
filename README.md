# nguyen
---------------------------------
## **DAY01**
1. bài tập 1 : Cho bán kính hình cầu, tính và in ra diện tích, thể tích của hình cầu đó.
Hướng dẫn: S = 4πR 2 và V = (4/3)πR 3
 * bài làm :
 ```swift
   let π = 3.14
   
   var S = tinhdientich
   func tinhdientich(R: Double) -> Double{
    var S: Double
    S = (4 * π * R)
    print("diện tích hình cầu ")
    return pow(S,2)
   }
   var dientich = tinhdientich(R: 21)
   print(dientich)
   
   var V = tinhthetich
   func tinhthetich(R: Double) -> Double{
    var V: Double
    V = ((4/3) * π * R)
    print("thể tích hình cầu ")
    return pow(V,3)
   }
   var thetich = tinhthetich(R: 21)
   print(thetich)
   
 ```
 
2. bài tập 2 : tính tổng bình phươgn 2 số a và b (a và b nhập từ bàn phím)
 - bài làm :

   
