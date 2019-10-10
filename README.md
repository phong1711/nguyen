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
 ```swift
 var c = binhphuonga(a: 4)
 print(c)
 var d = binhphuongb(b: 5)
 print(d)
 var S = tongbinhphuong
 var tongbinhphuongab = tongbinhphuong(c: 16, d: 25)
 print(tongbinhphuongab)
 
  func binhphuonga(a: Double) -> Double{
 return pow(a,2)
 }
 func binhphuongb(b: Double) -> Double{
 return pow(b,2)
     }
 func tongbinhphuong(c:Double, d: Double) -> Double{
     var S: Double
     S = (c + d)
     print("tổng bình phương a và b")
     return S
 }
 ```
 
 3. bài tập 3 : *, Viết chương trình nhập vào số nguyên n. Hỏi: 
- n là số nguyên dương hay không? 
- n có phải là số chẵn hay không? 
- n có chia hết cho 5 hay không?
- n có phải là số nguyên tố hay không?
* bài làm :
```swift
 let n: Int = (1*5)
 if  (n > 0) {
    print("n là số nguyên dương")
 }
 else {
 print("n không phải là số nguyên dương")
 }
 
 if n / 2 == 0 {
 print("n là số chẵn")
 }
 else {
 print("n là số lẻ")
 }

 if n / 5 == 1 {
 print("n chia hết cho 5")
 }
 else {
 print("n không chia hết cho 5")
 }
 
 if (n > 1) {
 print("n là số nguyên tố")
 }
 else if (n < 1){
 print("n không phải số nguyên tố")
 }
 ```
 
 4. bài tập 4 : *, Cho 2 số a và b, kiểm tra xem a có chia hết cho b không?
 * bài làm :
 ```swift
 let a: Int = 4
 let b: Int = 4
 if (a / b) == 1 {
 print("a chia hết cho b")}
 else {
 print("a không chia hết cho b")}
```

5. bài tập 5 : *, Tìm giá trị lớn nhất của 2 số
* bài làm :
```swift
 let a = 7
 let b = -5
 if (a>b){
 print("max là \(a)")}
 else if (a<b) {
 print("max là \(b)")
 }
```

6. bài tập 6 : *, Giải phương trình bậc nhất
* bài làm :
```swift
 let a = 4
 let b = 5
 var x = phuongtrinh(a: 4, b: 5)
 print(x)
 
 func phuongtrinh(a: Double,b: Double) -> Double{
     var x: Double
     x = -(a/b)
    print("ax + b =")
     return x
 }
 
 if (x == 0) {
 print("phương trình có vố số nghiệm")
 }
 else if (a == 0 ) {
 print("phương trình vô nghiệm")
 }
 else if ( b == 0 ){
 print("phương trình vô nghiệm")
 }
 else if (a <= 0) {
     print("phương trình có nghiệm duy nhất x = -b : a")
 }
 else if (a >= 0) {
     print("phương trình có nghiệm duy nhất x = -b : a")
 }
```
