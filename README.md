# OOAD-WEEK10
Sequence Diagram

ส่งการบ้าน 5 รูป
* การสนทนาระหว่าง Bella Jacob และ Edward

![](http://www.plantuml.com/plantuml/img/RO_12O0m34NldI8BP04HAO8NjuWsg12hr4hNjz0IKBmbFxptYRqYXNZlOaQQZmcmWvv521gOISIK1NDSxWsGln87Y2l3kHwUZHbSek0KhMHDMyIN4H9jSVDBDRUeOlRksraTFwLgLxdYDa_veGS0)

 ```
@startuml
Jacob -> Bella : call
Bella --> Jacob : answer the phone
Edward -> Bella: call
Edward <-- Bella : call waiting
Bella <- Jacob : end call
Bella --> Edward : answer the phone
Edward <- Bella : end call
@enduml
 ```
* การสั่งของออนไลน์ ระหว่าง Opal Oke และ ไปรษณีย์ 

![](http://www.plantuml.com/plantuml/img/RP5HZiCW34J_ESLSW0j4rQhT_rLMsbw04hT18IO2KYctNoUGgehwYNcU6Tldb4tCy-XLEnaF_OLs83HeOqSHgNSn9mJsZacjFtebLhB1nTemSyQtuG4yZpTfEAXSe-5qb_eOc1OunkNwezHl45UFazQLIyJTRcOoSayepEPvqgXFGH-KCPbeoMEIMZK-Pji4Fs0rdu15C55yIhm6jYSxVEfuvuu6ZkyXZYQxmFjGWbJY4FJeBCIVUp1r40r4ikIUj4rUcjwYbXszc7rFFfBfbZBvArVkrsiiOLRgB17biFy0)

 ```
 @startuml
Opal -> Oke : Order shirts online
Oke --> Opal : Account Bank number 
Opal -> Oke : Transfer money in ATM

Postal <-- Oke : send shirts at the Postal
Oke <-  Postal : get parcel post number
Oke --> Opal : send parcel post number

Opal --> Postalserver : check parcel post number
Postalserver--> Opal : send information

Postal-->Opal : get parcel post
Opal --> Postal : Signed for receive the parcel

Opal --> Oke :  receive shirts already
Oke -> Opal : thank you

@enduml
 
  ```




README.md 
md เป็นภาษา Markdown นิยมใช้ใน wiki ของ github 

ตัวอย่างโค้ด
```
# Heading ระดับ 1 
## Heading ระดับ 2
### Heading ระดับ 3
 
```

ผลที่ได้
# Heading ระดับ 1 
## Heading ระดับ 2
### Heading ระดับ 3


## Code ภาษาซี

ตัวอย่างโค้ด
<pre>
  ``` c
  #include <stdio.h>
  Main()
  {
     Printf("Hello");
  }
  ```
</pre> 
ผลที่ได้
  ``` c
  #include <stdio.h>
  Main()
  {
     Printf("Hello");
  }
  ```
 
